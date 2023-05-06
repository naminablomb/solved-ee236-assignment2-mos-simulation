Download Link: https://assignmentchef.com/product/solved-ee236-assignment2-mos-simulation
<br>
<strong>Simulation Exercise: PMOS characteristics</strong>

<ol>

 <li>Download the model file for PMOS transistor(from ALD1107 model file) from the “Downloads” .</li>

 <li>Write ngspice netlist to plot <em>I<sub>D</sub></em>/<em>V<sub>DS </sub></em>characteristics for the same with the voltage <em>V<sub>GS </sub></em>varied from -1.5 V to -3 V in steps of -0.5 V. You may vary <em>V<sub>DS </sub></em>from 0 V to -5 V.</li>

</ol>

Show all the 4 curves on a single plot.

<ol start="3">

 <li>From these characteristics, obtain <em>r<sub>DS </sub></em>(linear region) for each value of <em>V<sub>GS</sub></em>. ”Early voltage” and <em>r</em><sub>0 </sub>in saturation region.</li>

</ol>

Effect of body bias:

<ol>

 <li>Bias the transistor in linear region by keeping <em>V<sub>DS </sub></em>= 200 mV.</li>

 <li>Now write ngspice netlist to plot <em>I<sub>D</sub></em>/ <em>V<sub>GS </sub></em>characteristics by varying <em>V<sub>GS </sub></em>from 0 to -5 V for <em>V<sub>SB</sub></em>=0V. 3. Repeat the above step to get four more sets of <em>I<sub>D</sub></em>/ <em>V<sub>GS </sub></em>characteristics for <em>V<sub>SB </sub></em>= 1, 2, 3, and 4 V.</li>

 <li>Show all five <em>I<sub>D</sub></em>/ <em>V<sub>GS </sub></em>characteristics on the same plot.</li>

 <li>Obtain the value of threshold voltage from each plot.</li>

 <li>Plot <em>V<sub>t </sub></em>v/s <em>V<sub>SB </sub></em>and find the value of <em>α</em>.</li>

</ol>

**ALD1107 SPICE Parameter File

.MODEL ALD1107 PMOS (LEVEL=1 CBD=0.5p CBS=0.5p CGDO=0.1p CGSO=0.1p GAMMA=.45 + KP=100u L=10E-6 LAMBDA=0.0304 PHI=.8 VTO=-0.82 W=20E-6)

1