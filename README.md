# nce_nuclear_containment
# Preliminary desing of a nuclear reactor containment

This repository contains preliminary design notes for the inner containment core of a nuclear reactor. Generally, the nuclear containment is made of two separate layers. The inner one is made of prestressed concrete and is designed in order to keep its structural integrity during severe accidents as LOCA (loss-of-coolant accident) where the pressure inside the reactor rises almost instantly and is followed by a large increase in temperatures. Also during the exploitation of the power plant, the maintenance plan comprises periodical pressure tests where the pressure inside is increased and airtightness is measured on the outside. 

On the other hand, the outer shell is usually made of reinforced concrete and is designed to withstand either man-induced accidents as an airplane crash or an explosion but also natural hazards as tsunamis, floods etc. In between the two protective layers, there is placed monitoring equipment for assessing the stress-strain state of different points in the prestressed concrete and also sensors to determine the airtightness of the inner shell.

A simulation modeled in LS-Dyna of an airplane crash and the implied strains and efforts is posted: https://vimeo.com/296400223. 
Basically, this project represents a part of my work in a team (mainly the design notes) from a wider assignment described here: **1_Reactor_Building_Subject_2015-2016.pdf** while I was an Erasmus+ exchange student at École spéciale des travaux publics, du bâtiment et de l'industrie (ESTP Paris).

The preliminary dimensioning of the prestressed cement grouted tendons is presented in this document: **2_Design notes_rev7.pdf**  while the presentation I have held at the end of the project can be found in this document: **3_Presentation_Nuclear Containment design.pdf**.

**4_LS-Dyna_Source_Containment_Aircraft_impact.k** contains the model file for the simulation of an aircraft crash into the outer layer.
