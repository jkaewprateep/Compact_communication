# Compact_communication
Compact communication messages to examples of pulse modulation in communication devices, the pulse codes may related to the environment and there are many controller or joystick message wrappers hanldes of the input into the PyGame environment over serials or discrete messages as a binary or numeric value reference.

<b> 🧸💬 For incompatible PLE or joystick libraries for a duration of time playing games will cause no response feedback action of the player because the reference number is close but not exactly the same and they are conversion between numeric and discrete when discrete serial is not fully supported or not support by the newer versions of games as serial does it before. </b></br>
🐑💬 ➰ It is simply a wide method at the time of using the multiplexer to divide messages and compare the response for the actions, the multiplexer is a very fast calculation with a summing function and it can perform multiple requests at the same time since a single multiplexer uses can perform at 4 inputs at a time. </br>

<p align="center" width="100%">
    <img width="40%" src="https://github.com/jkaewprateep/Compact_communication/blob/main/cascade_communication.png"> </br>
    <b> Pulse code modulo </b>
</p>

### 🧸💬 The 5 player actions versus 12 monster actions with pulse modulation

🐨🎁🎵🎶 The leading numbers communication is natural encryption because there are multiple levels of communication level ```understanding```, ```compatibility```, and ```user experiences```. The summation method used in the validation method can tell you quickly about what is the signals communicating and you can describe in detail and respond to feedback. ```High contrast number``` is the operating system or active code running such as ```SOS``` and ```FOD``` . </br>

```
player 5 actions, monsters 12 actions

input =   [ 0, 0, 1, 1, 1, 2, 2, 2, 2, 2, 2, 2, 2, 1, 1, 1, 4, 4, 4, 4, 4, 4, 3, 3, 3, 1, 1, 1, 0, 0 ]
monster = [ 0, 0, 2, 2, 4, 1, 1, 1, 3, 3, 0, 0, 2, 2, 4, 1, 1, 1, 3, 3, 0, 0, 2, 2, 4, 1, 1, 1, 3, 3 ]

input =   [ 0, 0][1, 1, 1][2, 2, 2, 2, 2, 2, 2, 2][1, 1, 1][4, 4, 4, 4, 4, 4][3, 3, 3][1, 1, 1][0, 0 ]
monster = [ 0, 0][2, 2][4][1, 1, 1][3, 3][0, 0][2, 2][4][1, 1, 1][3, 3][0, 0][2, 2][4][1, 1, 1][3, 3 ]
```

<p align="center" width="100%">
    <img width="40%" src="https://github.com/jkaewprateep/Compact_communication/blob/main/pulse_code_modulation.png"> </br>
    <b> Pulse code communication signals </b>
</p>

### 🧸💬 Mapping method

```
conditions 	1 -> { 1, 2, 4 } ==> 3 / 12 == 0.25
			2 -> { 1, 2, 3 } ==> 3 / 12 == 0.25
			3 -> { 2, 4 }    ==> 2 / 12 == 0.167
			4 -> { 0, 1, 3 } ==> 3 / 12 == 0.25
			...

conditions  		[1, 1, 1] -> [2, 2][4]
			[3, 3, 3] -> [2, 2][4]
```

### 🧸💬 Mapping method - sequence
```
			[2, 2][4][1, 1, 1][3, 3][0, 0][2, 2][4][1, 1, 1][3, 3][0, 0][2, 2][4][1, 1, 1][3, 3]
			|------------ 0 -------------||------------ 1 -------------||------------ 2 -------------|
			|------------------------------------------ 1 -------------------------------------------|
			
	A		['0', '0', '0', '0', '0', '0', '0', '0', '0', '0', '0', '1']
	B		['0', '0', '0', '0', '0', '0', '0', '0', '0', '0', '1', '0']
	AB		['0', '0', '0', '0', '0', '0', '0', '0', '0', '0', '1', '1']
			[------A-----][------B------][------C------][-------D------]
	C		['0', '0', '0', '1', '1', '0', '0', '0', '0', '0', '1', '1']	==> 
	D		['0', '0', '0', '0', '1', '1', '0', '0', '0', '0', '1', '1']	==> 
	Q1		['0', '0', '0', '1', '1', '1', '0', '0', '0', '1', '0', '0']	==> 
	SUM		[-----00-----][-----16------][-----00------][------14------]	==> FOD
```
