# Instructions
1. Install Jupyter Notebook and Python Software in your device.
2. Create a new file in Jupyter by clicking `New->New File`.
3. Open the file in `Plecs` which would be linked with `Python`.
4. In the Plecs Simulation window Click:`File -> PLECS Preferences -> General`.
5. Select the `RPC Interface Port`,the tick box will turn blue.And set the Interface as `1080` in the box beside the `RPC Interface Port`.
6. Set an `Output Signal` block from `Library Browser` and `Multiplexer` from `Library Browser`.
7. Connect the output of the `Scope` whose plot you want to obtain to `Multiplexer` and the output of `Multiplexer` to `Output Signal`.

# Python Code

**Import Libraries**

import xmlrpc.client as xml

import os

import time

import matplotlib.pyplot as plt

model = 'model_name'  

file_type = '.plecs'

`model_name = The name of the plecs file that to be linked with Python API`.

**Code for API**

plecs = xml.Server("http://localhost:1080/RPC2").plecs

plecs.get('model_name'/L1')

plecs.set(model+'/L1','L','0.005')

plecs.get('model_name'/R1')

plecs.set(model+'/R1','R','10')

time = plecs.simulate(model)['Time']

current = plecs.simulate(model)['Values'][1]

voltage = plecs.simulate(model)['Values'][0]

plt.plot(time,current)

plt.plot(time,voltage)

plt.grid

**Points to Remember**
1. The above code is for linking the simulation file to Python script in Jupyter Notebook.
2. Both the Jupyter Notebook and `Plecs File` should be opened otherwise the simulation file will not run.
3. To change the parameters of a certain block/device you need to follow the get/set code where L1,R1 etc stands for the name of that certain block/device which can be known by selecting the block in simulation window.
4. Set the desired value as you want in your circuit and then `Run` the Python code simultaneously the Plecs file will also initialize and run.
5. The `Values` and `Plot` will be displayed in the output of Python code.

