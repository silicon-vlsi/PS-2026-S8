# About

This is a documentaion repo for everything [PLECS](https://plexim.com).

# Getting Started

This is a simple tutorial for Design and Simulation of Buck Converter.

- Launch **PLECS STANDALONE** in the system and open it.
- Create a new model _schematic_: Click `Create -> new model` OR (`Ctrl+n`), a blank schematic page (_SchematicPage_) will appear.
- Open the library browser: `SchematicPage -> Window -> Library Browser` (`Ctrl+L`)
- **Select Library Elements** (In SchematicPage):
  - Select DC Voltage Source (`LibraryBrowser->Electrical->Sources-> Voltage Source DC`) : Drag and droop it in the SchematicPAge
  - Inductor/Resistor/Capacitor (`LibraryBrowser-> Electrical-> Passive Components-> Inductor/Resistor/Capacitor`)
  - MOSFET/Diode (`LibraryBrowser->Electrical->Power Semiconductors-> MOSFET/Diode`)
  - Ammeter/Voltmeter (`LibraryBrowser->Electrical->Meters->Ammeter/Voltmeter`)
  - Scope/Display(`Library->System-> Scope/Display`)
  - Pulse Generator ( `Library->Control->Sources-> Pulse Generator`)
  - **SAVE**: `File->SavAs`

- **Draw Schematic**
![Buck Converter Schematic](images/plecs-schematic-buck.jpeg)

We are going to wire the above schemtic.
- **Basic Schematic Commands**:
  - To fit shole schematic in the screen: `View -> Normal(100%)` (`Ctl+=`)
  - Drag elements: `Left-click->Drag`
    - **NOTE** For connected device, `MiddleClick -> Drag` to move without draging the wires.
  - Rotate/Flip: `Select Element -> Ctrl+R/F`
  - Copy/Paste: `Ctrl+C/V`
  - Connecting Wires: `SelectNode` (Plus sign appears) `-> LeftClick -> Drag` to connecting node.
  - Changing Parameters for eg. Scope: `DoubleClick` on elemet, `File-> ScopeParameters -> no Of Plots`
  - **NOTE** Keep saving
  - Changing _Instance Name_ : `DoubleClick` on the name of the instance (eg. `V_dc`) and change the name.
- **Udate schematic Parameters**:
  - `V_dc`: 20 V
  - Diode : $V_f = 0.8V$ , $R_{ON} = 0.8 \Omega$
  - MOSFET: $R_{ON}=0.1 \Omega$  
  - Inductor: $L = 1e-3$
  - Capacitor: $C = 6.25 \mu F$
  - Resistors: $R1 = 10 \Omega$ 


