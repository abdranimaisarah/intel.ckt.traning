# INTEL.CKT.TRAINING(2023)

## Day 1(WW01.4'23)- Fundamental of VLSI Design and Overview or Sand to Silicon

 <details>
<summary>Learning</summary>
<br>
 
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
 
 <br>
</details>

<details>
<summary>Assignment</summary>
<br>

 
<br>
</details>

 ## Day 2(WW02.1'23)- Details of IC Manufacturing Process
 
 <details>
<summary>Learning</summary>
<br>
 
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
    
    
    (a) Wafer Formation
    - wafer cut from boule, cylindrical ingots of single crystal silicon.
    - some amount of impurities added to the melt to provide the crystal.
    - A seed crystal is deep into the melt to initiate crystal growth.
    - Seed gradually withdrawn from the melt and simultaneously rotated.
    - The seed withdrawal and rotation rates determines the diameter of ingot.
        <img width="172" alt="image" src="https://user-images.githubusercontent.com/122240906/212214940-d13af078-c3f8-4ea1-8dc3-7fc2f2c47825.png">
        <img width="415" alt="image" src="https://user-images.githubusercontent.com/122240906/212215077-b5d40c15-8944-4692-9339-b91157748812.png">
    
    (b) Photolithography
       - patterning process.
       - wafer coated by the photoresist and subjected to selectiv illumination through the photomask.
       - photomask is constucted with chromium.
       - used UV light to expose- the photorist.
       <img width="218" alt="image" src="https://user-images.githubusercontent.com/122240906/212219497-5ec17755-ee07-48a0-85dc-3ebb57cb4a30.png">

    (c) Well and Channel Formation
    - Nwell : pmos bule in a n-well, nmos place in p substrate.
    - Pwell : nmos bule in a p-well, pmos place in  n substrate.
    - Twin well : emergence of nwell process.
    - Triple well : provide isolation between analog and digital blocks in mixed signal chips. used to isolate high density dynamic memory for logic.

    (d) Silicon Dioxide(Sio2)
    - Oxidation achived by heating the silicon wavef in oxidizing atmostphere.

    (e) Isolation
    - to avoid interaction between devices.
    - form thick oxide by LOCOS process - Local Oxidation of Silicon
        
    (f) Gate Oxide
    - Form gate oxide for transistor. 
    - gate also consist thin gate layer oxide.

     (g) Gate and Source/Drain Formations.
     - Grow gate oxide to accommodate gate/drain/source --> deposit polysilicon --> patter polysilicon --> etch exposed gate oxide --> implant pMos/nMOS source&drain region.

     (h) Contact and Metallization
     - Make contact cut to source/drain/gate according to contact mask.-hole etched in dielectric after source/drain formation.
     - make from alluminium, copper or tungsten.

     (i) Passivation
     - Final process is adding a protectiove glass layer.
     - to prevent ingress of contaminants.
      
      (j) Metrology
      - Measurement process to give feedback to manufacturing process.
<br>
</details>

<details>
<summary>Assignment</summary>
<br>
 
 ## <img width="379" alt="image" src="https://user-images.githubusercontent.com/122240906/212737597-cb40cd6a-26eb-4525-b526-a4f8febef521.png">
 
 ## <img width="284" alt="image" src="https://user-images.githubusercontent.com/122240906/212738470-6e9a5dc0-7ba3-467c-be5c-ec7864042ddf.png">
 
 ## <img width="345" alt="image" src="https://user-images.githubusercontent.com/122240906/212739386-e25bff7c-97bc-467f-9e49-60d50b17111b.png">
 
 ## <img width="296" alt="image" src="https://user-images.githubusercontent.com/122240906/212740097-1eec28ad-51c9-4eba-acd0-15f2776851d3.png">
 
 ## <img width="283" alt="image" src="https://user-images.githubusercontent.com/122240906/212741235-53e5feb2-bf8e-4cee-96f7-ca28bb8c090c.png">
 
 ## <img width="301" alt="image" src="https://user-images.githubusercontent.com/122240906/212742089-a2f2343a-2ef3-42a2-868e-fed0283b35e7.png">
 
 ## <img width="271" alt="image" src="https://user-images.githubusercontent.com/122240906/212742643-05948b4c-d9e2-46db-82fe-2d06b29ac3b3.png">
 
 ## <img width="319" alt="image" src="https://user-images.githubusercontent.com/122240906/212743020-ebab4270-dd57-44b7-887d-139c0c14534d.png">
 

<br>
</details>

 ## Day 3(WW02.3'23)- CMOS Fabrication Process in DSM and UDSM Tech
 
<details>
<summary>Learning</summary>
 <br>
 
 ### Submicron CMOS Process
 
 Disadvantages :
 - pn junction usage, to isolate transistor becomes impractical as transistor size decrease.
 - LOCOS disadvantage; bird's beak effect, the surface area loss to this encroachment.
 - LOCOS advantage; simple flow, high oxide quality due to LOCOS structure thermally grown.
 <img width="230" alt="image" src="https://user-images.githubusercontent.com/122240906/212546268-fd095a42-b0ae-415b-8110-8f77ff25f676.png">
 

  ### Sallow Trench Isolation (STI) Process
  
  - Preffered isolation process for deep-submicron process --> No Bird's beak(reduced active to active spacing).
  - Much suitable for the increase density in small area.
  - Disadvantages : a lot of process steps.
  
  <img width="248" alt="image" src="https://user-images.githubusercontent.com/122240906/212547601-465f2e9a-49bd-49a6-9882-4aa22e381faa.png">

   
  ### Deep Submicron (DSM) and Ultra Deep Submicron(UDSM) CMOS Technology
  
 - Type of resistor in DSM CMOS Technology.
 <img width="476" alt="image" src="https://user-images.githubusercontent.com/122240906/212549423-199d416a-bb3c-4340-abee-d252582c85ae.png">

 - Type of capacitor in DSM CMOS Technology.
 <img width="542" alt="image" src="https://user-images.githubusercontent.com/122240906/212549447-1b9c71f8-cc40-4eb4-b3ac-4baca19d7ebe.png">

- DSM Fabrication Process

<img width="439" alt="image" src="https://user-images.githubusercontent.com/122240906/212549198-38427377-ee5b-47b9-86b8-7dcebab5f13e.png">
 
- DSM vs UDSM
<img width="666" alt="image" src="https://user-images.githubusercontent.com/122240906/212550430-ebb41b06-4d04-464f-b5be-ba36f13f702d.png">

<br>
</details>

<details>
<summary>Assignment</summary>
<br>
 

1. List the five basic MOS fabrication processing steps and give the purpose or function
of each step.
 
 
   (a)	Photolithography – pattern setting
 
   (b)	Implantation – add dopants to silicon
 
   (c)	Deposition – add new layers(metals,oxides)
 
   (d)	Etching – take away sections of layers
 
   (e)	Oxidation – for gate oxides, need native oxides

 
 2. What is the difference between positive and negative photoresist and how is photoresist
used?
 
    Photoresist is a light-sensitive material used in several processes such as photolithography and photoengraving, to form a patterned coating on a surface.

    Positive photoresist : light will weaken the resist, and create a hole. the portion of the photoresist that is exposed to light becomes soluble to the photoresist developer. The unexposed portion of the photoresist remains insoluble to the photoresist developer.

    Negative photoresist : light will toughen the resist and create an etch resistant mask.  the portion of the photoresist that is exposed to light becomes insoluble to the photoresist developer. The unexposed portion of the photoresist is dissolved by the photoresist developer.

3. Sketch the approximate cross sectional view of a NMOS transistor in a p-substrate.
   Identify each region and identify the connections at the top surface of the integrated
   circuit for the source, drain, gate and bulk/substrate.
 
   ![image](https://user-images.githubusercontent.com/122240906/212733659-e12d7c1e-201b-4f8a-94a4-9b6ab883863a.png)

4. Consider a mask that is opaque everywhere except for a transparent circle in the center.
   Metal is deposited on a substrate followed by an application of negative photoresist
   which is patterned with the mask described. After exposure, developing, and
   subsequent etching, what will remain?
 
   A coating where the mask placed.

5. What is the difference between submicron, deep submicron and ultra-deep submicron
process?
 
  ![image](https://user-images.githubusercontent.com/122240906/212733689-259d4903-d3c6-4818-9156-7b9562de924b.png)

6. What are the advantages of ultra-deep submicron process over deep submicron process.
 
   -Small length size
 
   - low cutoff current
 
   - high cutoff frequency, more speed

7. What is the difference between LOCOS and STI process?
 
   The difference of STI process compared to LOCOS is that a shallow trench is etched into the silicon substrate. Therefore, STI is best for the device isolation process compared to LOCOS.

8. Why for body connection a heavily doped n+ or p+ is used?

9. What is use of silicide and poolside
 
   Silicide and Polycide is used to minimize parasitic resistance, polycide( silicide on polysilicon), silicide(self aligned silicide) on source-drain
 
   Siliside :
   - To form electrical contacts between the semiconductor device and the supporting interconnect structure.
   - Silicide (compound of silicon with metal) is formed on gates (polysilicon), sources and drains (Si wafer) as three MOS transistor electrodes in order to     reduce contact resistance to metal wiring layers.
   - Silicide formation has the effect of lowering the resistance of each electrode, ability to withstand high temperature, oxidizing ambients and good contact to other materials.

10. Which process steps used for control threshold voltage and punch-through effect?
 
    Threshold voltage can be controlled by adjusting the oxide thickness and channel length during oxidation(gate oxide) steps. 

11. Draw a top view, front view and 3D view of a CMOS inverter and annotate the length
and width of both PMOS and NMOS transistor.
 
    ![image](https://user-images.githubusercontent.com/122240906/212733727-701a70ab-c0e0-4fd0-945e-8fc42bf5937d.png)


12. Why sidewall spacer are used in DSM technology?
 
    To insulate the drain and source metal contacts from the gate of the transistor.

13. What are the advantages of Deep N-well technology over n-well technology?
 
    Reduce noise coupling between sensitive analog areas and more noisy digital regions in mixed-signal designs

14. What is passivation layer?
 
    Passivation layer or passivation layers are formed to protect the internal semiconductor devices after the completion of metallization. The passivation layers are typically formed with deposition of an oxide layer and a nitride layer.

15. What is Bird’s beak in LOCOS process and what is the impact on the transistor
performance?
 
    Bird Beak is an active to active spacing.
 
    Bird beak causing the surface area loss to this encroachment.

 
<br>
</details>

 ## Day 4(WW02.5'23)- Metal Oxide Semiconductor(MOS) Structure
 
<details>
<summary>Learning</summary>
<br>
 
  ### Metal Oxide Semiconductor(MOS) Device Structure
  
 - MOS junction - A capacitor
                - No current-voltage relationship, on capacitor-voltage relationship.

<img width="157" alt="image" src="https://user-images.githubusercontent.com/122240906/212551398-9b7349ed-0a32-4dcb-99f5-e4b7d3e06128.png">

### Metal Oxide Semiconductor(MOS) Fabrication

- Process to create SiO2 on top of silicon, called Oxidation.
- Process to deposit poly-silicon on top of SiO2 called Metallization.

### Ideal MOS Junction or Capacitor

 - No charge in the device if V=0
 - Substrate is uniformly doped.
 - All charge is 0 (Interface charge, Trapped charge, Fixed charge, mobile charge, etc..)
 <img width="256" alt="image" src="https://user-images.githubusercontent.com/122240906/212551717-4dd1b5a6-e029-4c2c-aa53-95a7c4d78dc1.png">
 - 4 condition in ideal case: 

 (1) Accumulation Mode (v<0)
  - Accumulation occurs when voltage applied less than the flatband voltage.
  - The negative charge on the gate attracts holes from the substrate to the oxide-semiconductor interface.
  - Pile of majority carrier at the interface.
  - Charge at the surface directly proportional to voltage
<img width="224" alt="image" src="https://user-images.githubusercontent.com/122240906/212552359-49da06c0-d23e-4c0f-b561-d24501d73f9e.png">

(2)  Depletion Mode ( V > 0)
  -  More positive voltage than the flatband voltage is applied, a negative charge builds up in the semiconductor
  -  The depletion layer width further increases with increasing gate voltage.
 
 (3) Strong Inversion Mode (V > and equal Vt)
  - at Vt, channel form at the surface of semiconductor due to inversion charges.
  - Before Vt, charge come from negatively charged ionized acceptors.
  - After Vt, more charge comes from electron rather that depleting the holes.
  - More negetive charge required for semiconductor is comes from the mobile electron.
  - this negetive charge emerged to the oxide-semiconductor interface, this charge is due to minority carriers, so called inversion layer.
  
 (4) Flatband
  - Refers to fact that the energy band diagram of the semiconductor is flat, which implies that no charge exists in the semiconductor.
  
### C-V Characteristic of MOS Structure

<img width="349" alt="image" src="https://user-images.githubusercontent.com/122240906/212553498-ca33966c-27fa-4fa7-b9d0-f41e2a3b68eb.png">

 

<br>
</details>

<details>
<summary>Assignment</summary>
<br>
 
1. The main differences between ideal and real MOS structure :

2. The different modes of operation in a MOS junction : 

   ![image](https://user-images.githubusercontent.com/122240906/217449365-2612ff97-2f39-4d17-9493-b83f6a6d6f97.png)

 
3. The difference between weak inversion and strong inversion of a MOS junction :
 
   ![image](https://user-images.githubusercontent.com/122240906/217450185-4704bb1b-8156-45ea-ae78-83fbc0b43888.png)

4. What is Metal-to-semiconductor work function : 

   ![image](https://user-images.githubusercontent.com/122240906/217453220-39cd78e0-fe18-462f-bea1-8fe001a0882f.png)
 
 5. For a heavily n-doped poly-silicon metal and a p-substrate semiconductor, what will be the metal-to-semiconductor work function? Positive or negative?
   
   Positive
 
 6. For a heavily p-doped poly-silicon metal and a n-substrate semiconductor, what will be the metal-to-semiconductor work function? Positive or negative?
 
   Negative
 
 7. What is threshold voltage of a MOS junction? Express threshold voltage for a non-ideal MOS junction.
 
   ![image](https://user-images.githubusercontent.com/122240906/217455996-2320d69a-0231-4a41-b024-37a1014f6813.png) 
 
 8. If the oxide (SiO2) increases for a MOS structure, the threshold voltage will increase or decrease?
     
    Threshold voltage of MOS increases as the thickness of oxide layer increases.
 
 9. Instead of a lightly doped p-substrate, if you use a heavily doped p-substrate in a MOS structure then what will be the change in threshold voltage? Will it   increase or decrease?

     Threshold voltage will decreased with the increase of lightly doped.
 
 10. Describe, why MOS capacitance stay minimum at very high frequency and back to high value at low frequency.

     The higher frequency has high resistivity, which inactive the minority carriers rapidly at the interface between oxide and semiconductor.
     Majority carriers, minority carriers, and interface states contribute to the MOS or MOSFET capacitance. Majority carriers can follow very high frequencies, but      the minority carriers and a part of the interface states cannot follow high frequencies. This is why the contribution to capacitance from the interface states        will be absent at high frequencies and also from the minority carriers in the MOS capacitor.
 
<br>
</details>
  
## Day 5(WW03.2'23)- Metal Oxide Semiconductor Field Effects Transistor
 
<details>
<summary>Learning</summary>
<br>
 
- The metal–oxide–semiconductor field-effect transistor (MOSFET) is a type of field-effect transistor (FET), most commonly fabricated by the controlled oxidation of silicon.
 
- MOSFETs are electronic devices used to switch or amplify voltages in circuits. It is a voltage controlled device and is constructed by three terminals.
 
 ![image](https://user-images.githubusercontent.com/122240906/217462067-21b2e9b5-0cf7-4dc4-8a18-ed0a969659ab.png)

 
  ### MOSFET Operations
 
 For an enhancement-mode, n-channel MOSFET, the three operational modes are:
   (1) Cutoff, subthreshold, and weak-inversion mode.
   (2) Triode mode or linear region (also known as the ohmic mode.
   (3) Saturation or active mode.
 
   #### MOSFET Operations
 
   ![image](https://user-images.githubusercontent.com/122240906/217466053-ac1a5bac-3076-49bc-9b1f-4c74d2e98c69.png)

 Formula to calculate current :
 
 (N-Channel) :
 
 ![image](https://user-images.githubusercontent.com/122240906/217464076-6960f587-52d7-4b76-b4a6-81848f737267.png)
 
 MOSFET Channel Profile :
 
   ![image](https://user-images.githubusercontent.com/122240906/217464364-f6e5a73b-be19-4d1a-8069-1bc289222d03.png)
 
  (P-Channel) :
 
 ![image](https://user-images.githubusercontent.com/122240906/217466267-aa64ad39-2f83-43cd-99ac-2b792bf0bb44.png)
 
 
  #### ID-VGS Characteristics

   <img width="337" alt="image" src="https://user-images.githubusercontent.com/122240906/217467208-2d073135-f9e4-4e66-aca8-9026409221c6.png">

   <img width="328" alt="image" src="https://user-images.githubusercontent.com/122240906/217468144-064fb8b6-4a40-482e-8074-dbbb41843e12.png">

   #### ID-VGS Characteristics with body bias
 
   <img width="334" alt="image" src="https://user-images.githubusercontent.com/122240906/217467383-1442070f-0511-462e-8f50-f8e59dbfd3e3.png">

  - Body bias is the voltage at which the body terminal (4th terminal of mos) is connected. Body effect occurs when body or substrate of transistor is not biased at same level as that of source. 
  - Forward body bias scales down the threshold voltage and reverse body bias increases the threshold voltage.
 
 #### ID-VDS Characteristics: Channel Length Modulation

 <img width="347" alt="image" src="https://user-images.githubusercontent.com/122240906/217468742-83c1778e-8fd6-4107-a199-d85ef98f952c.png">

 
 - In a MOSFET operating in the saturation region, the channel length modulation effect causes a decrease in the output resistance.
 - For a MOSFET operating in saturation region the channel length modulation effect causes a decrease in output resistance. The drain characteristics becomes less flat. If we consider channel modulation, the value of Rd will be always less than infinity. So, channel length modulation decreases the output resistance.
 
 <br>
</details>

<details>
<summary>Assignment 5</summary>
<br>
 
 - N/A

<br>
</details>
  
## Day 6(WW03.4'23)- MOSFET Intrinsic Capacitance
 
<details>
<summary>Learning</summary>
<br>
 
 ### MOSFET Intrinsic Capacitance Intro

 - Intrinsic capacitance is a transistor parasitic capacitance generated between the power and ground nets.
 - The intrinsic capacitances of MOSFETs largely determine the switching speed and transient behavior of the devices.
 - Proper representations of these non-linear capacitances being used to develop accurate simulation models and to improve understanding of the device behavior.
 
 
  ### MOSFET Intrinsic Capacitance: Cutoff Region
 
 <img width="254" alt="image" src="https://user-images.githubusercontent.com/122240906/217488980-33dc370e-8661-4c7c-a07f-0740ccb60022.png">

 - no channel capacitance
 - Only gate-to-bulk capacitance (High value)
 
  ### MOSFET Intrinsic Capacitance: Saturation Region
 
 <img width="259" alt="image" src="https://user-images.githubusercontent.com/122240906/217489208-304c42d4-6787-4b34-be2d-74a18865b575.png">

 - Cgsch : Gate-to-channel at source side
 - No drain side capacitance because of pinch-off
 - <img width="76" alt="image" src="https://user-images.githubusercontent.com/122240906/217490598-1e0657dc-4792-491c-bb3d-084a36d381e8.png">
 
  ### MOSFET Intrinsic Capacitance: Linear Region
 
 <img width="252" alt="image" src="https://user-images.githubusercontent.com/122240906/217489095-d3b813d8-5afe-436d-8c6a-075e61016c31.png">

 - Cgsch, Cgdch : Gate-to-channel at source side and gate-to-channel at drain side
 - Voltage dependent
 - <img width="101" alt="image" src="https://user-images.githubusercontent.com/122240906/217490348-58f0742c-1528-44d3-b45b-b5ad7ef26fb0.png">
 

 ### Schematic Design, Circuit Simulation, Layout Design and Postlayout Simulation
 
  #### Custom IC design process
 
 <img width="343" alt="image" src="https://user-images.githubusercontent.com/122240906/217491353-b15875dc-4a9e-4af8-9eac-63755efa823d.png">

 
  #### Custom IC Design Flow using Tools
 
 (1) Schematic drawing phase
     
     Schematic creation --> Symbol Creation --> Create testbech for simulations.
 
 <img width="346" alt="image" src="https://user-images.githubusercontent.com/122240906/217496279-a1f6e9c9-0ae1-4a77-891a-62490feb4a2e.png">

 
 (2) Circuit Simulation Phase (Pre-layout)
 
     Launch ADE-L --> Select simulation type(DC sweep/AC simulation/Transient) --> save desire waveforms to plot and add menasurement using calculators to plot for some predefined functions (rise time, fall time, delay, derivative, gain margin, phase margin etc) --> run simulations.
 
 <img width="348" alt="image" src="https://user-images.githubusercontent.com/122240906/217494925-edb101a6-4e20-4cca-8ac0-f2df04f3c82a.png">

 <img width="353" alt="image" src="https://user-images.githubusercontent.com/122240906/217495287-79b423e1-5a46-4b50-9f03-e97b0c634ae3.png">

 (3) Layout Design and Verification Phase
 
     Generate layout from schematic --> Place the components --> Routing between the components, supply and ground --> Verify the layout with the design rule (DRC) --> Verify the layout with schematic (LVS) --> Extract the parasitic and create a schematic view of the that extracted netlist.
 
 <img width="350" alt="image" src="https://user-images.githubusercontent.com/122240906/217495514-ed1846ee-6b9e-4f2f-b5bb-3856b300f3a3.png">
 
 (4) Post Layout Simulation Phase (Post-layout)
 
     Create config view --> Do the simulation for both views and compare the result --> Follow same process as you have done pre-layout simulation. Only difference is instead of schematic netlist you will use parasitic extracted netlist.
 
 
  <br>
</details>

<details>
<summary>Assignment 6</summary>
<br>
 
 - to be updated

<br>
</details>
     

 
 

 
 

 
 
 
 
