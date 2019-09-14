Supercritical Steam And Its Consequences For The Nuclear Energy Plant Balance
 Austin T. Rotker and John B. Mahoney

Abstract

 	Supercritical steam is currently in use with conventional coal-fired power plants, and literature suggests that its use as a working fluid in a BWR design could increase thermodynamic efficiency by almost 30% . However, it appears that thus far little research has been done into how supercritical steam would affect the balance of plant (BOP) beyond increased turbine efficiency. Our research will attempt to model an entire BOP system, including pumps, safety and bypass systems and multiple turbines and condensers, as well as investigate the strains placed on this system by normal operation and theoretical accident scenarios. We will do this using python and Cortix, a network simulation library.

Introduction

 	Since the beginning of the industrial revolution over two centuries ago, the name of the heat engine game has been increased cycle efficiency. Many approaches to this have been tested, from older more conventional methods of increasing heat transfer efficiency between fuel and working fluid, to more novel ones such as selection of an unconventional working fluid. The improvements present in a Super Critical Water Reactor (SCWR) operate off the principles of the latter, with the liquid water or steam working fluid of a PWR or BWR design replaced with critical fluid at extremely high pressure (>22 MPa) and temperature (>500 °C) . The usage of supercritical steam in conventional coal-fired power plants has been proven to increase turbine efficiency, as the higher temperature and pressure of the inlet supercritical fluid allows a turbine to extract more energy per unit mass before the fluid is expanded to its outlet temperature. 
  
	Although there have been numerous studies into the positive effects of supercritical steam as the working fluid used in a conventional steam system (the first supercritical steam boiler was patented in the 1930’s) , little attention has been paid to the macroscopic behavior of the BOP required to keep a SCWR running safely and efficiently. This is worrying, as the SCWR BOP’s very nature necessitates an extremely rigorous analysis. Any analysis performed must address how conventional unit operations and equipment responds to the additional stresses a nuclear reactor places on its BOP, namely: radiochemical effects on the working fluid; additional strains from higher liquid flowrate, temperatures and pressures; and the need for effective and multiply redundant safety systems. These issues pose major potential challenges to plant safety and operating economics and their modelling will ultimately decide the feasibility of the SCWR concept just as much as any analysis of reactor physics.


Methods And Approach

	Our group will draw on studies of the thermodynamic and radiochemical properties of supercritical steam, and will apply it to a BOP model along with additional thermodynamic and physical considerations of the fluid’s interaction with all the unit operations and safety systems. We will do this by formulating mathematical models for all these processes and then creating python modules to model each individual unit operation and subsystem (the reactor, pumps, piping, condensers, turbines, safety systems and sensors and controls). Finally, after validation of the individual models they will be stitched together and run concurrently using the Cortix library to analyze the behavior and feasibility of the system as a whole.

Expected Outcomes

	After the final network simulation has been stitched together, our group expects to have a definitive analysis of the safety and economic feasibility of an entire 660 MW SCWR plant. This analysis will include in-depth quantitative and qualitative review of “normal” operation as well as theoretical accident scenarios, as well as areas that require more scientific review to enhance the accuracy of the model.

References

MacDonald, Phillip, et al. “Feasibility Study of Supercritical Light Water Cooled Reactors for Electric Power Production Progress Report for Work Through September 2003; 2nd Annual Report and 8th Quarterly Report.” INEEL, Sept. 2003.

Bartels, D.M., et al. “Supercritical Water Radiolysis Chemistry Supercritical Water Corrosion.”

De Almeida, Valmor, and Austin Rotker. “Dpploy/Engy-4350.” Nuclear Reactor Engineering, 23 Aug. 2019, github.com/dpploy/engy-4350.

De Almeida, Valmor. “Network Dynamics Simulation¶.” Network Dynamics Simulation - Cortix 0.1.0 Documentation, Cortix Group, 2019, cortix.org/.
