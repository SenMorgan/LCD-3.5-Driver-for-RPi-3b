LCD driver for the Raspberry PI Installation<br>
====================================================
2018-05-22
Updated by Sen Morgan to support last Raspbian version 4.14.39-v7+ #1112.<br>
Pay attention at config.txt-35 files! You can correct them for your favourite parametrs (exept last 2 lines).
Also you can correct or change panel config files for your own. You can find your panel config file in ```/home/pi/.config/lxpanel/LXDE-pi/panels/panel```.
When you are switching back to the HDMI, all old config files will be restored.
  
In case if you are starting it first time:<br>
	```cd LCD-show```<br>
	```sudo chmod +x LCD35-show```<br>
	```sudo chmod +x LCD-hdmi```<br>
	```./LCD35-show fts```<br>
	then choose "YES" to install a new touchscreen driver. After that you don't need to use "fts" parametr.<br>	
  
If you want to change rotation, use 90, 180 or 270 parametr:<br>
  ```./LCD35-show 90```<br><br>
If you need to switch back to the traditional HDMI port use:<br>
  ```./LCD-hdmi```<br>

Wait a few minutes, the system will restart automatically, enjoy with your LCD.
-------------------------------------------------------------------------------
<br><br>



