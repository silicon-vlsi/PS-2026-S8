# About

This is a documentaion repo for everything [PLECS](https://plexim.com).

# BUCK CONVERTER

This is a simple tutorial for Design and Simulation of Buck Converter.

- Launch **PLECS STANDALONE** in the system and open it.
- Create a new model _schematic_: Click `Create -> new model` OR (`Ctrl+n`), a blank schematic page (_SchematicPage_) will appear.
- Open the library browser: `SchematicPage -> Window -> Library Browser` (`Ctrl+L`)
- **Select Library Elements** (In SchematicPage):
  - Select DC Voltage Source (`LibraryBrowser->Electrical->Sources-> Voltage Source DC`) : Drag and droop it in the SchematicPage
  - Inductor/Resistor/Capacitor (`LibraryBrowser-> Electrical-> Passive Components-> Inductor/Resistor/Capacitor`)
  - MOSFET/Diode (`LibraryBrowser->Electrical->Power Semiconductors-> MOSFET/Diode`)
  - Ammeter/Voltmeter (`LibraryBrowser->Electrical->Meters->Ammeter/Voltmeter`)
  - Scope/Display(`Library->System-> Scope/Display`)
  - Pulse Generator ( `Library->Control->Sources-> Pulse Generator`)
  - **SAVE**: `File->Save As`

- **Draw Schematic**
![Buck Converter Schematic](images/Buck_Circuit.png)

We are going to wire the above schemtic.
- **Basic Schematic Commands**:
  - To fit whole schematic in the screen: `View -> Normal(100%)` (`Ctl+*`)
  - Drag elements: `Left-click->Drag`
    - **NOTE** For connected device, `MiddleClick -> Drag` to move without draging the wires.
  - Rotate/Flip: `Select Element -> Ctrl+R/F`
  - Copy/Paste: `Ctrl+C/V`
  - Connecting Wires: `SelectNode` (Plus sign appears) `-> LeftClick -> Drag` to connecting node.
  - Changing Parameters for eg. Scope: `DoubleClick` on elemet, `File-> ScopeParameters -> no Of Plots`
  - **NOTE** Keep saving
  - Changing _Instance Name_ : `DoubleClick` on the name of the instance (eg. `V_dc`) and change the name.
- **Update schematic Parameters**:
  - `V_dc`: 20 V
  - Diode : $V_f = 0.8V$ , $R_{ON} = 0.001 \Omega$
  - MOSFET: $R_{ON}=0.1 \Omega$  
  - Inductor: $L = 5m H$
  - Capacitor: $C = 6.25 \mu F$
  - Resistors: $R1 = 10 \Omega$
  - Pulse Source: $Freq = 10kHz$
- **Simulation**
   - To start the simulation (`Simulation->Start`) OR (`Ctrl+t`).
   - To set the time span of simulation:`Simulation->Simulation parameters->Time span` OR (`Ctrl+l`)
   - Observe the Output volatage on the display block.
   - The output voltage should be higher than the input voltage,here it should be `V_m1`: 11.5994 V.
   - **NOTE** If there wii be any simulation error or any error in circuit connection then `Diagnostics` window will appear,highlighting the error part in the cirucit.
- **SCOPE ANALYSIS**
   - Select the scope element to view the plots.
   - Click on (`View menu->Show legend`) to know the exact plot of corresponding block element.
   - For labelling the subplots:(`File->Scope Parameters->Plot->Title/Axis label/Time axis`).
   - To know a particular value on the subplot place the `Cursor` on the waveform,the value will appear.
   - To have the subplots in a synchronized order (`View->Zoom to fit`)
   - To know the properties of the plots and waveform:
      - Select the `Cursors` icon.
      - Two vertical lines will appear on the plot(Cursor1 and Cursor2).
      - We can select the range by dragging the cursors as per requirement.
      - Click on the drop down arrow beside it.
      - Now select the properties like (Max,min,THD,Delta,RMS,Slope,etc).
      - This will give all the local properties within the choosen range.
      - All the data will appear in the data window at the bottom of the scope window.
    - The plot can  be saved as pdf file by (`File->Export->As pdf`).
  - **PLOT**
     ![Buck Converter Scope](images/Buck_scope.png)
    



     
    
    

