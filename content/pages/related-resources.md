---
content_type: page
title: Related Resources
uid: 75dbdf7c-80e7-be23-8752-a93976c0adb5
---

PSPICE Simulation Information
-----------------------------

Download the Microsim (now known as Orcad) DesignLab Release 8 Evaluation version, containing both Schematics and PSpice for PCs. A more up-to-date version can be downloaded from [OrCAD](http://www.orcad.com/).

[Spice tutorial](http://homepage.seas.upenn.edu/~jan/spice/spice.overview.html) (courtesy of University of Pennsylvania Department of Electrical Engineering). In particular, see [How to Get Started with PSpice](http://homepage.seas.upenn.edu/~jan/spice/spice.guide.html#PSPICE).

### (Almost) Ideal Diode Model

idealdiode.lib ([LIB](/courses/electrical-engineering-and-computer-science/6-334-power-electronics-spring-2007/related-resources/idealdiode.lib)) – If you're creating your circuit with the "Schematics" tool, incorporate this library into "Schematics" as follows: Select Analysis -> Library and Include Files. Type the filename idealdiode.lib in the filename box (including the path to the file), and click Add Library. If you're creating your circuit using a standard textfile netlist, add the following lines to your file:

X1 (node 1) (node 2) diode\_ideal  
.lib idealdiode.lib

idealdiode.slb ([SLB](/courses/electrical-engineering-and-computer-science/6-334-power-electronics-spring-2007/related-resources/idealdiode.slb)) – If you're creating your circuit with the "Schematics" tool, incorporate this _symbol_ library into "Schematics" as follows: Select Options -> Editor Configuration. Select the Library Settings button, and then add the file idealdiode.slb. If you're creating your circuit using a standard textfile netlist, you do NOT need this file.

Half-wave rectifier with freewheeling diode and Commutating Inductance ([CIR](/courses/electrical-engineering-and-computer-science/6-334-power-electronics-spring-2007/related-resources/halfwave.cir))

Full-wave rectifier with Commutating Inductance and Current Source Load ([CIR](/courses/electrical-engineering-and-computer-science/6-334-power-electronics-spring-2007/related-resources/fullwave.cir))

Full-wave rectifier with RL Load ([CIR](/courses/electrical-engineering-and-computer-science/6-334-power-electronics-spring-2007/related-resources/RL_load.cir))

Another SPICE simulator that may be used is LTSPICE/SwitcherCAD III, developed by Linear Technology. Software and information can be downloaded from [Linear Technology](http://www.linear.com/company/software.jsp).

PSIM Power Electronics Simulator
--------------------------------

Try out the PSIM power electronics simulator for free! A demo version is available from [POWERSIM](http://www.powersimtech.com/).

More Free Resources
-------------------

The [Power Supply Manufacturer database](http://www.powersupplies.net/) is dedicated to designers of Switch Mode Power Supplies, and features:

*   How to design a Switch Mode Power Supply, including software tools and examples.
*   How to simulate a power supply. See PSpice simulation waveforms on their SMPS Simulation page.
*   Lists of companies manufacturing power supplies.
*   Information regarding SMPS components and component suppliers.
*   Various technical articles.