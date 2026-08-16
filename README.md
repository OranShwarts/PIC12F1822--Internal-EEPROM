<div>
	<h1>Project Name: PIC12F1822 - Internal EEPROM</h1>
	<div>
		<h3>🗺️ Project Overview</h3>
		<p>Bare-metal C driver for writing and reading 32-bit unsigned long values to PIC12F1822 internal EEPROM with LED status verification.</p>
	</div>
	<hr>
</div>
<div>
	<div>
		<h4>📋 Key Hardware Specifications</h4>
		<ul type="disc">													
			<li>Operating Voltage	-5V</li>
			<li>Microcontroller		-PIC12F1822</li>
			<li>Target Peripheral	-Internal EEPROM</li>
			<li>Interface Protocol	-None</li>
		</ul>
	</div>
	<hr>
	<div>
		<h4>🔌 Pinout Connections</h4>
		<table>
			<tr>
				<th>MCU Pin</th>							
				<th>Peripheral Pin</th>	
				<th>Function / Description</th>			
			</tr>
			<tr>
				<td>RA0</td>
				<td>ICSPDAT & BLUE LED</td>	
				<td>ICSP & Writing to EEPROM done</td>												
			</tr>
			<tr>
				<td>RA1</td>
				<td>ICSPCLK & GREEN LED</td>	
				<td>ICSP & Reading from EEPROM OK</td>												
			</tr>
			<tr>
				<td>RA2</td>
				<td>RED LED</td>	
				<td>Reading from EEPROM ERROR</td>												
			</tr>
			<tr>
				<td>RA3</td>
				<td>ICSP-VPP</td>	
				<td>ICSP</td>												
			</tr>
		</table>
	</div>
	<div>
		<h4>📐 Circuit schematic designed for this setup</h4>
		<img src="Schematics/schematic.png" alt="Circuit Schematic" width="600"/>
	</div>
	<hr>
	<div>
		<h4>📂 Repository Structure</h4>
		<pre>
├── Src/            Source code (.c) and headers (.h)
├── Schematics/     Circuit diagrams and pinout configurations
├── Datasheets/     Official IC datasheets
└── Pictures/     	Pictures associated to the project
		</pre>
	</div>
</div>