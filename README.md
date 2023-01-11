# INTEL.CKT.TRAINING(2023)

## Day 1(WW01.4'23)- Fundamental of VLSI Design and Overview or Sand to Silicon


### Intro : Steps to create GITHUB REPO :

1) Register using intel email address
2) Login, create repo and start write-up.


### Analog VLSI CKT Design , Presenter : Prof Santunu Sarangi

1)Basic Unix

2)Analog Design - sch drawing tools

3)Digital - Verilog, EDA,synthesis,etc

4)Book reference : Fundamentals of electric circuit, Charles K.Alexander & Matthew N.O Sadiku


### Fundamental VLSI :Overview of Sand to Silicon

What is VLSI?
1) Motherboard --> Chip --> Waver --> Die
2) Die contain of : 
 - Microcontroller, memory,analog and digital circuit. --> Implemented of VLSI.
3) Good Design must fullfill following requirement :
 - Functionality (Performance, low power)
 - Low Cost
 - Timely execution
 4) Design quality checks :
 - Testability
 - Yield
   What is yield? 
   - percentage of the actual number of chip produced on one wafer.  (number of chip working)
   - % Yield = (good die/ total die) X 100 %
 - Realibility (EOS,ESD,noise,crosstalk,etc)
 
 
 ## Day 2(WW02.1'23)- Details of IC Manufacturing Process
 
 ### Analog IC Design Process
 1) Electrical Design(Schematic design) :
    - It is a starting to the Analog design, which is designer start with defining the specification of the circuit/schematic.
    - Followed by circuit drawing and verifiying the design using Analog design schematic tools such as Virtuoso,Presto and etc.
    - Besides specifications requirement, robustness of the design can be ensure by reliability test(EOS, Aging,RV,etc).

2) Physical Design(Layout Design) :
   - Process of representing electrical design(schematic) in layout.
   - Start with physical design such as floorplan, placement and routing.
   - Followed by the physical verification - Check LVS, DRC rule.
   - Lastly is parasitic extraction, whereby extracting the layout so that design can be validate with RC parasitic.

3) Test Design :
   - Process of coordinating,planning and implementing the Analog Design performance.
   - Type of test : Functional,Parametric,static, dynamic.
   
4) Flow chart of Analog Design process as below :

![image](https://user-images.githubusercontent.com/122240906/211698970-2c723d32-8229-45f1-b3cd-f2ce3b22ef5e.png)

5) Analog IC Design Process and Relation with CAD and PDK

![image](https://user-images.githubusercontent.com/122240906/211699618-aaeab87b-a51e-4562-bbfc-2aed9ea77a48.png)

6) Keynote : Designer should always design a practical circuit based on the device limit, technology constraints and physical implementations in order to meet the criteria of high performance, low power and low cost. Therefore the understand of layout design is important to minimize the iteration in design process.

 ### CMOS Technology
 
 1) Comparison of BJT and Mosfet :
 ![image](https://user-images.githubusercontent.com/122240906/211700541-34105d9c-b730-4ff7-923b-9d05bfd1c8e0.png)
 

 ### CMOS Fabrication Process 
 
 1) Process steps :
    Wafer Formation(sand to silocon) --> Photolithography --> Well and Channel Formation --> Sio2 Deposition --> Isolation 
    --> Gate Oxide Creation --> Gate and Source/Drain Formations --> Contacts and Metalizations --> Passivation --> Metrology.
    
    
    .......TO BE CONTINUE(EDITTING IN PROGESS)

 
