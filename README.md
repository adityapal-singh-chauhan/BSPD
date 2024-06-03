<H1>BSPD - Brake System Plausibiltiy Device</H1>  
<BR /><H3>
A non - programmable brake, accelerator plausibility circuit.<BR />
Built for FSAE, according to Formula Bharat specs 2024.<BR /></H3>
<ul>
	<li>It feautes upper and lower thresholds for fault detection</li>
	<li>Disconnection or damage to sensor will also trigger the circuit.</li>
  <li>acc/brake_upper_trig - potentiometer sets the sensors output voltage trigger threshold.</li>
  <li>acc/brake_lower_trig - potentiometer sets the minimum volatage output of the sensor.</li>
  <li>The timing for 500ms wait and 10s shutdown can also be fine tuned.</li> 
	<li>onboard volatge regulation(input 15v - 5.5v)</li>
</ul>

![BSPD](https://github.com/adityapal-singh-chauhan/BSPD/assets/130316879/5b80491d-db41-4d8a-a6f7-f563caf7fd32)

SCHEMATIC

![schematic](https://github.com/adityapal-singh-chauhan/BSPD/assets/130316879/e237543f-76af-4403-9893-05773414f2a0)

PCB layout
![PCB](https://github.com/adityapal-singh-chauhan/BSPD/assets/130316879/3f2f436c-61b1-4c4c-aa0e-a8168134c835)


LTspice sim:
![all signals](https://github.com/adityapal-singh-chauhan/BSPD/assets/130316879/2cd5fa3a-d958-4d05-83c5-80bb5fb50b94)
red - fault signal<BR />
green - 500ms wait<BR />
blue - shutdown trigger<BR />
