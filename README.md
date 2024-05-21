# ONAIRPANEL2IP

## USB Software Update Instructions
1.  Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message “***Upgrade Firmware***” will be displayed. Press **< ENTER >**.
    > If a different message appears on the display, search for the updated software in the main menu (Update Firmware) and select from **Only This Unit**, **Multiple Fixture**, or **Other Fixture Type**. A list of the updated software files will be displayed. 
3.	Select the file that needs to be uploaded. The message “***Are you sure?***” will be displayed. Press **< ENTER >**.
    > If the selected file is incorrect, the upgrade will fail, and the display will go back to the main interface. Repeat steps 1–3 using the correct file.
5.	If the selected file is correct, the upgrade will start. DO NOT turn off the power or disconnect the USB during the process. USB update can take several minutes to complete.
6.	When the update is completed, the product will automatically reboot.
7.	Go to **Fixture Information** on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.


### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need to do a Force Upload.

&nbsp;  

## Force Upload
1.	Link the target fixture to the main fixture via a DMX 5-pin connection. Ensure that the target fixture is turned off.
2.	Turn on the main fixture and set its protocol to **DMX512**.
3.	Plug the flash drive into the USB-C port of the main fixture.
4.	Go to **Upgrade Firmware** on the menu map.
5.	Choose between Multiple Fixture and Other Fixture Type. Press **< ENTER >**.
    * **Multiple Fixture:** Both the target fixture and main fixture are from the same product line (e.g., 2 Color STRIKE M fixtures).
    * **Other Fixture Type:** The target fixture and main fixture are from different product series (e.g., a Color STRIKE M as the target fixture and a Maverick Silens 2 Profile as the main fixture).
6.  Select the file that needs to be uploaded. The message “***Are you sure?***” will appear on the screen. Press **< ENTER >**. Turn on the target fixture within 1–2 seconds of pressing **< ENTER >**. The display on the target fixture should remain off.
    a. The main fixture will show the update progress (0–100%).
    b. The target fixture’s display will turn on, and a notification “***<UPDATE>***” will appear on the screen.
7.  DO NOT turn off power or remove the USB flash drive. Once the software is done uploading, the target fixture will automatically reboot.
8.	Go to the target fixture’s main menu and confirm that the firmware version has been updated.
9.	Reboot the target fixture.


### Special Notes
*  A Force Upload process requires a target fixture (the fixture that needs a Force Upload and a main fixture (the fixture that controls the upload process).
*  The Force Upload process can only be done one target fixture at a time.

&nbsp;  

## Software Versions

[V2.0.0 – onAir Panel 2 IP](https://github.com/Chauvet-Pro/ONAIRPANEL2IP/blob/2fcb0135f47e8a98f51ab89a8d6df66c27dce10d/firmware/V2.0.0_02-18-24.zip)
- Improved network control capabilities and bug fixes

[V1.230811 – onAir Panel 2 IP](https://github.com/Chauvet-Pro/ONAIRPANEL2IP/blob/2fcb0135f47e8a98f51ab89a8d6df66c27dce10d/firmware/V1.230811.zip)
- Added an IP Mode that enables users to change the IP address to Static, Manual, or DHCP

[V1.221226 – onAir Panel 2 IP](https://github.com/Chauvet-Pro/ONAIRPANEL2IP/blob/2fcb0135f47e8a98f51ab89a8d6df66c27dce10d/firmware/V1.221226.zip)
- Fixed inconsistencies in the brightness between the two LED boards when fast strobe with calibration on is activated

[V1.220530 – onAir Panel 2 IP](https://github.com/Chauvet-Pro/ONAIRPANEL2IP/blob/2fcb0135f47e8a98f51ab89a8d6df66c27dce10d/firmware/V1.220530.zip)
- For internal housekeeping.

[V1.220317 – onAir Panel 2 IP](https://github.com/Chauvet-Pro/ONAIRPANEL2IP/blob/2fcb0135f47e8a98f51ab89a8d6df66c27dce10d/firmware/V1.220317.zip)
- Added X and Y control personalites

[V1.210918 – onAir Panel 2 IP](https://github.com/Chauvet-Pro/ONAIRPANEL2IP/blob/2fcb0135f47e8a98f51ab89a8d6df66c27dce10d/firmware/V1.210918.zip)
- Released software version
