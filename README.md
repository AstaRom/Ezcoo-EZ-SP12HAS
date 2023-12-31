## <p align="center">Recovery Ezcoo EZ-SP12HAS</p>

### Initial data:
The device was connected to the "Firmware" connector.

The firmware was updated using programs (UartAssist, FlyMcu).<br>
During this operation, the power supply of the device (5v) was lost, the firmware is not finished.<br>
***"UartAssist"*** does not see the device, the LED (OUT2) on the front panel is dimly lit.

### Recovery steps:
Disassemble the device.<br>
On the printed circuit board we find two contacts with the inscription ***"ISP"***.
We prepare the wire (jumper).<br>
We do not connect power to the splitter, only a USB cable to your PC (firmware port).<br>
We close two ***"ISP"*** contacts (it's easier to do this from the back of the board, since there is less chance of touching other elements).

<table>  
  <tr>
    <td colspan="2"><p align="center">ISP contact's on the board</p></td>
  </tr>
  <tr>
    <td><img width="650" height="380" src="https://raw.githubusercontent.com/AstaRom/Ezcoo-EZ-SP12HAS/master/ISP%20contacts.jpg"/></td>
  </tr>
</table>

Open the program (FlyMcu), select the port and firmware file.<br>
Connect power to the splitter, in the program press the button ***"Start to ISP (p)"***.<br>
After the process is completed, turn off the power, remove the jumper.<br>
The device has been restored.