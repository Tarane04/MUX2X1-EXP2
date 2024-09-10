![WhatsApp Image 2024-09-10 at 22 03 18_cb7bfd8c](https://github.com/user-attachments/assets/31120ebc-a3b0-44b2-92d7-5d2a30c14158)`EXP02--Design-Implementation-of-Full-Custom-2-1-MUX-using-Cadence-EDA-Tools`

`AIM:` 

To design and implement a 2:1 multiplexer (MUX) circuit using Cadence EDA tools, analyse its functionality and performance, and understand the principles of digital logic design, including schematic creation, layout design, and simulation. Tools Required: • Personal Computer • Cadence Virtuoso Software

`S C H E M A T I C S I M U L A T I O N PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION Commands to get into Cadence`

-Right Click and open the terminal window <brk>

-Type the following commands as follows and press enter. 
• csh<brk>
• source /cadence/install/cshrc <brk>
• virtuoso Procedure for Schematic simulation using Cadence <brk>

-Now two windows must open <brk>
i)virtuoso/command interpreter window <brk>
ii)”Whats New…” <brk>

-Close the 2nd window

Use 1st window i.e virtuoso window(CIW) for further processing.<brk>
i. Create a New Library <brk>
ii. Create Schematic Cell view.<brk>
iii. Create the Symbol for schematic Cell view.<brk>
iv. Create the test Cell view. <brk>
v. Analog simulation by spectre<brk>

i) Procedure for Creating New Library. <brk>
• File –New – Library <brk>
• Name : Give name for ur library Ex: VLSILAB_EXP_1<brk>
• Enable Attach to an existing technology library, Click OK <brk>
• Attach the library to the technology library gpdk045.Click OK <brk>

ii) Create Schematic Cell view. • Go to 1st window i.e virtuoso(CIW) <brk>
• File-New-Cell view • Setup the new file form Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View_Schematic Type: Schematic press OK <brk>
• Add the required components from the libraries and make the connections.  Go to instance fixed menu or use shortcut key “I” from keypad to go instances  Click on browse. This opens the library browser  Now select the appropriate library for components like  Gpdk45 ------------------------nmos1v, pmos1v  Create Input and Output pins  Make the connections by using fixed narrow wire key  Click Check and Save button image

iii) Creating the Symbol for schematic Cell view 
• In the schematic window, execute  Create – Cell view – From Cell view  The cell view from cell view window appears  Check Lib Name, Cell Name, From View name must be schematic Press ok • Now Symbol generation form appears. Click Ok If No changes required 
• A new window with with default symbol is created.<brk>
• Edit the symbol if you want to give actual symbol shape else continue. <brk>
• Execute Create-Cell view-from cell view • Library Name and Cell Name must be same which you have used for schematic. Press OK • Check for the position of pin side.Prss OK<brk> 
• Edit for the shape by Create-Shape-Choose required options to edit.<brk>

![WhatsApp Image 2024-09-10 at 22 04 13_17107dbe](https://github.com/user-attachments/assets/6b0d1f24-0856-4045-a2a9-948747dfa4bc)

iv) Creating the new test cell view<brk>
• Go to CIW window, Execute File-New-Cell view  Setup the new file form  Library: Select the one you created.  Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test  View: Schematic  Type: Schematic press OK <brk>
• Follow the step 3(ii) d to make the required connections image

![WhatsApp Image 2024-09-10 at 22 05 41_c12e0e48](https://github.com/user-attachments/assets/e2a0c769-f17a-458f-be26-d96f0e1bac8d)


Analog simulation by SPECTRE. <brk>
• In test cell view window <brk>
• Launch – ADE L(Analog Design Environment)  Execute Setup—Simulation/directory/Host A new window opens  Set the simulation window to spectre and click ok  Execute Analysis – Choose. A window opens.  Select the type and set the specifications and press OK  Execute Output s—to be plotted – Select on Schematic  Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
• Execute Simulation -- Net list and Run image

![WhatsApp Image 2024-09-10 at 22 05 41_383ac9e5](https://github.com/user-attachments/assets/9bd0ce08-96a5-49df-83f1-f2debec1f6fc)


`For Transient Analysis Settings and Output image`


![WhatsApp Image 2024-09-10 at 22 03 18_cb7bfd8c](https://github.com/user-attachments/assets/30bf1863-8742-444c-9578-a75a4b2acf03)


`Results:`

-The experiment successfully demonstrated the design and implementation of a 2:1 MUX using Cadence EDA tools.<brk>
-The successful verification through schematic, layout, and simulation underscores the effectiveness of using Cadence EDA tools for digital circuit design.<brk>
