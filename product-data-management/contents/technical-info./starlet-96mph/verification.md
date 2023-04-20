# Verification

<figure><img src="../../../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

## &#x20;   <mark style="color:blue;">1. Field Verification 2, Non-IVD for 96 Probe Head</mark>

### &#x20;       1-1. Intended Use

'Field Verification 2' provides the means to verify the:

* Cover Safety
* Barcode Reading
* Positioning the Pipetting Channels and Multi-Probe Heads
* Pipetting Performance (Trueness and Precision) of the Pipetting Channels and Multi-Probe Heads
* easyPunch features
* Temperature (Heating and Cooling)
* Shaker Orbit and Frequency



### &#x20;       1-2. Unit Affected & Prerequsite

Seegene STARlet equipped with CO-RE 96 Modular ARM & Multi-Probe-Head II.

The User Software, Instrument, Labware, and external Devices such as Heater and Shakers have to be installed and functioning properly prior to performing the Field Verification 2.

The following Verifications can be run:

| Verification Processes | Software Version |
| ---------------------- | ---------------- |
|                        |                  |

* **Required Tools:**
  * [x] **Verification\_Starlet\_Mod.lay & Verification\_Starlet\_Mod.res**
  * [x] **HamHeaterShaker Folder(Which includes 'HSLHamHeaterShakerLib')**
  * [x] **Hamilton Software(Venus Non-IVD)**
  * [x] **Field Verification 2 SW(FK2, Non-IVD)**
  * [x] **IT\_Sensor\_Driver**
  * [x] **Hamilton Heater Shaker**
  * [x] **Field Verification 2 Packaging**
  * [x] **Field Verification 2 Consumables Kits Packaging**

{% hint style="info" %}
As for the details about the 'Field Verification 2 & Consumables Kits Packaging',

refer to the section -[field-verification-packaging.md](../../service-info./starlet-96mph/part-list/field-verification-packaging.md "mention")
{% endhint %}



### &#x20;       1-3. Summary

In advance, MUST preemptively conduct all the Macros and Teaching procedures for STARlet equipped with CO-RE 96 Modular ARM & Multi-Probe-Head II.

After that, able to conduct the following verification procedures for Seegene STARlet equipped with CO-RE 96 Modular ARM & Multi-Probe-Head II.

1. Install the Hamilton Heater Shaker at position No. 22
2. Cover Safety
3. Barcode Reading
4. Positioning the 1000μL Pipetting Channels
5. Positioning the 96 Probe Heads
6. Volume Verification of the 1000μL Pipetting Channels
7. Volume Verification of the 300μL 96 Probe Heads
8. Volume Verification of the 1000μL 96 Probe Heads
9. Temperature for Hamilton Heater Shaker
10. Shaker Orbit and Frequency for Hamilton Heater Shaker
11. Conduct the Teaching for the HHS after installing it at position No.16



### &#x20;       1-4. Recommendation

Field Verification 2 tools need to re-calibrate based on the interval shown below.

| Tools requiring Re-Cal.                         | Interval | Cal. Source    |
| ----------------------------------------------- | -------- | -------------- |
| Barcode Verification Carrier                    | 2 years  | Hamilton       |
| Reader Check Plate                              | 1 year   | Hamilton       |
| IR Sensor Measurement Tool                      | 1 year   | Optris         |
| Balance WXS or SAG                              | 1 year   | Mettler Toledo |
| 20g Calibration Weight                          | 2 years  | Mettler Toledo |
| Ambient Temperature / Humiditu Measurement Tool | 1 year   | Testo          |

### &#x20;       1-5. Part Information

As for the details about the 'Field Verification 2 & Consumables Kits Packaging',

refer to the section -[field-verification-packaging.md](../../service-info./starlet-96mph/part-list/field-verification-packaging.md "mention")



### &#x20;       **1-6. Procedure**

### &#x20;           **A. Hamilton Software(Venus Non-IVD) Installation**

1. Execute the Hamilton Software Installer(Venus, Non-IVD).
2. Install it following each step referring to the guide shown on the popped-up window.

{% hint style="warning" %}
In the case of the error shown below on the execution of 'Hamilton Run Control',

_<mark style="color:red;">\*Error: Cannot open database connection. (Login failed for user 'Hamilton'. Reason: Server is in single user mode. Only one administrator can connect at this time) (0x60 - 0x12 - 0x12)</mark>_

&#x20;                                     ![](<../../../../.gitbook/assets/image (76).png>)



Conduct the adding and assigning the user for 'Lab'(i.e., 'Lab Method Programmer', 'Lab Operator', 'Lab Operator 2', 'Lab Remote Service', 'Lab Service') into the group membership on the Device Manager.



Refer to the section -' (Link)' for the procedure above.
{% endhint %}

{% hint style="warning" %}
In the case of the error shown below on the execution of 'Hamilton Run Control',

_<mark style="color:red;">\*Error: Cannot open database connection. (A network-related or instance-specific error occurred while establishing a connection to SQL Server. The server was not found or was not accessible. Verify that the instance name is correct and that SQL Server is configured to allow remote connections. (provider: SQL Network Interfaces, error: 26 - Error Locating Server/Instance Specified)) (0x60 - 0x12 - 0x12)</mark>_

&#x20;                                     ![](<../../../../.gitbook/assets/image (256).png>)



Conduct the setting of the 'Vector Database Connection Setting'.



Refer to the section -' (Link)' for the procedure above.
{% endhint %}



### &#x20;           **B. Field Verification 2 Software(FK2, Non-IVD) Installation**

1. Execute the Field Verification 2 Software Installer(FK2, Non-IVD).
2. Install it following each step referring to the guide shown on the popped-up window.



### &#x20;           C. Deck Layouts & HamHeaterShaker Labware files

1. Copy and paste the 'Verification\_Starlet\_Mod.lay' and 'Verification\_Starlet\_Mod.res' into the directory ('C:\Program Files(x86)\HAMILTON\Method\Verification).
2. Copy and paste the Folder named 'HamHeaterShaker' into the directory ('C\Program Files(x86)\HAMILTON\LabWare).

{% hint style="warning" %}
Do not rename the files - 'Verification\_Starlet\_Mod.lay' and 'Verification\_Starlet\_Mod.res'&#x20;

Do not rename the folder and files for the 'HamHeaterShaker Folder(Which includes 'HSLHamHeaterShakerLib')'.
{% endhint %}



### &#x20;           D. Install the Hamilton Heater Shaker

1. Install the Hamilton Heater Shaker at position No. 22.

{% hint style="danger" %}
In advance, MUST power the equipment off completely to connect the HHS Cable to the equipment's port.
{% endhint %}

{% hint style="warning" %}
The installation position of the Hamilton Heater Shaker on the Verification and Seegene STARlet 96Head Method is different from each other.



Please keep in mind each installation position.

* Seegene STARlet 96Head Method: Position No.16
* Verification: Position No.22
{% endhint %}



### &#x20;           E. Cover Safety Verification

1. Execute the 'Microlab STAR Verification 2' program.
2. Select the checkbox for the 'Cover Safety Verification' in the Start Dialog window. Then, click 'OK'.
3. Conduct the 'Cover Safety Verification' following each step guide shown on the window.
4. If the 'Cover Safety Verification' is processed completely, the 'Cover Safety Report' will pop up automatically. Then, close it and click 'OK'

{% hint style="info" %}
Reports will be found in the directory (C:\Program Files\HAMILTON\System)
{% endhint %}



### &#x20;           F. Barcode Reading

1. Execute the 'Microlab STAR Verification 2' program.
2. Select the checkbox for the 'Barcode Verification' in the Start Dialog window. Then, click 'OK'.
3. Put the 'Environmental Conditions' measured by the 'Ambient Temperature and Humidity Measurement Tool' Then, click 'OK'
4. Put the 'Serial No.' and 'Calibration Date' of the 'Barcode Verification Carrier'. Then, click 'OK'
5.  Place the 'Barcode Verification Carrier' on the selected track until the stop hook.

    Then, click 'OK' and wait for the 'Barcode Verification' to be processed completely.
6. 'Barcode Verification Report' will pop up automatically. Then, close it and click 'OK'.

{% hint style="info" %}
Reports will be found in the directory (C:\Program Files\HAMILTON\System)
{% endhint %}



### &#x20;           G. Positioning the 1000μL Pipetting Channels

1. Execute the 'Microlab STAR Verification 2' program.
2. Select the checkbox for the '1000μL Pipetting Channel Position Verification' in the Start Dialog window. Then, click 'OK'.
3. Put the 'Environmental Conditions' measured by the 'Ambient Temperature and Humidity Measurement Tool' Then, click 'OK'
4. Check if the Teaching Needles are in the Waste Block. Then, click 'OK'
5. Wait for the 'Barcode Verification' to be processed completely.
6. 'Position Verification Report' will pop up automatically. Then, close it and click 'OK'.

{% hint style="info" %}
Reports will be found in the directory (C:\Program Files\HAMILTON\System)
{% endhint %}



### &#x20;           H. Positioning the 96 Probe Heads

1. Execute the 'Microlab STAR Verification 2' program.
2. Select the checkbox for the '96 Multi-Probe Head Position Verification' in the Start Dialog window. Then, click 'OK'.
3. Fill in all requested data and press the ‘OK’ button to continue.
4. Select a reachable Position on the Deck and type in the desired Track Number where the Plate-Tip Carrier shall be loaded.
5. Place all Labware exactly as described onto the Plate-Tip Carrier.
6. Check for free access to the CO-RE 96-Probe Head. Press the ‘OK’ button to continue.
7. The CO-RE 96-Probe Head Position Verification is processed automatically.
8. Failed or passed. The Verification Procedure will finish with either a ‘failed’ or a ‘passed’ status. Click ‘OK’ to continue.
9. 'Position Verification Report' will pop up automatically. Then, close it and click 'OK'.

{% hint style="info" %}
Reports will be found in the directory (C:\Program Files\HAMILTON\System)
{% endhint %}



### &#x20;           I. Volume Verification of the 1000μL Pipetting Channels



### &#x20;           J. Volume Verification of the 300μL 96 Probe Head



### &#x20;           K. Volume Verification of the 1000μL 96 Probe Head



### &#x20;           L. Temperature for Hamilton Heater Shaker

1. Execute the 'Microlab STAR Verification 2' program.
2. Select the checkbox for the 'Temperature Verification' in the Start Dialog window. Then, click 'OK'.
3. Check the 'Track / Site-Position', 'Status', 'Expiry Date', and 'Remark'. Then, select the checkbox for the 'Hamilton Heater Shaker' and click 'OK'
4. Put the 'Environmental Conditions' measured by the 'Ambient Temperature and Humidity Measurement Tool' Then, click 'OK'
5. Wait for 20 min. for the Heating Up Phase.
6. After then, connect the IR Temperature Sensor cable to the USB Port of the PC.
7. Check or define the Calibration date. Then, click 'OK'
8. Wait for the 'Temperature Verification' to be processed completely.
9. 'Temperature Verification Report' will pop up automatically. Then, close it and click 'OK'.

{% hint style="danger" %}
At the end of the 'Temperature Verification', the surface still be hot!
{% endhint %}

{% hint style="warning" %}
If requested, perform the USB Driver(IR Sensor Driver) installation for the IR Temperature Sensor.

Note: Ignore the warning during installation.
{% endhint %}

{% hint style="warning" %}
If the 'Temperature Verification' failed, please repeat to conduct the 'Temperature Verification' until passed.
{% endhint %}

{% hint style="info" %}
Reports will be found in the directory (C:\Program Files\HAMILTON\System)
{% endhint %}



### &#x20;           M. Shaker Orbit and Frequency for Hamilton Heater Shaker

1. Execute the 'Microlab STAR Verification 2' program.
2. Select the checkbox for the 'Shaker Verification' in the Start Dialog window. Then, click 'OK'.
3. Check the 'Track / Site-Position', 'Status', 'Expiry Date', and 'Remark'. Then, select the checkbox for the 'Hamilton Heater Shaker' and click 'OK'
4. Put the 'Environmental Conditions' measured by the 'Ambient Temperature and Humidity Measurement Tool' Then, click 'OK'
5. Place the 'Shaking Measurement Tool onto 'Hamilton Heater Shaker' which is located on Deck Position, 'track 24' / 'site 1'. Then, click 'OK'
6. Wait for the 'Shaker Verification' to be processed completely.
7.  Remove the 'Shacking Measurement Tool' at the end of the 'Shaker Verification'.&#x20;

    'Shaker Verification Report' will pop up automatically. Then, close it and click 'OK'.

{% hint style="danger" %}
At the end of the 'Shaker Verification', the surface can still be hot!
{% endhint %}

{% hint style="info" %}
Reports will be found in the directory (C:\Program Files\HAMILTON\System)
{% endhint %}





### &#x20;           N. Install the Hamilton Heater Shaker at position No. 16 by disassembling it from No. 22

1. If all the things need to be verified(i.e, 'Cover Safety', 'Barcode Reading', 'Positioning the channels and MPH', 'Volume Verification for channels and MPH', 'Temperature for HHS', 'Shaker Orbit and Frequency for HHS') are completely passed, disassemble the Hamilton Heater Shaker from the position No. 22.
2. Install the Hamilton Heater Shaker in position No. 16.



### &#x20;           O. Conduct the Teaching for the HHS, Position No. 16

1. Execute the Hamilton Method Editor.
2. Open the 'STARlet\_v6.1\_96Head.lay' file.
3.  Conduct the Teaching procedure at position No. 16 for both channels and 96 Probe Head.

    Please refer to the details about the procedure below.

<details>

<summary><mark style="color:blue;">No. 16 (DWP96_HHS_96Head)</mark></summary>

1. Place the Tip Plate that 1000 μLTips loaded in Position No. 2.
2.  Place the '96 Deep Well Plate' in position No. 16.

    <figure><img src="../../../../.gitbook/assets/image (309).png" alt=""><figcaption></figcaption></figure>


3.  Execute the STAR Service.

    &#x20;          ![](<../../../../.gitbook/assets/image (289).png>)


4.  Go to the Heater Shaker Control option.

    (Control tab -> Movements/Sensors -> Heater Shaker)
5.  Set the 'Heater Shaker Address' as 'T1'

    <figure><img src="../../../../.gitbook/assets/image (316).png" alt=""><figcaption></figcaption></figure>


6.  On the 'Plate lock-Drive' tab in the popped-up 'Heater Shaker' window,

    \*This step is for DWP to be positioned on the HHS correctly.

    1\) Click the 'Initialize' button.

    2\) Click the 'Plate locked' button.

    3\) Click the 'Plate free' button.

    <figure><img src="../../../../.gitbook/assets/image (347).png" alt=""><figcaption></figcaption></figure>


7. Find the 'DWP96\_HHS' and select it.
8. Right-click on the selected position. Then, click the 'Adjust Location...'.
9.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (341).png" alt=""><figcaption></figcaption></figure>


10. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
11. 'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (286).png" alt=""><figcaption></figcaption></figure>


12. 'Move Probe - Key Control' will be newly popped up. The 96 Probe Head(which is mounting the tips in position No. 2) will move to the No. 16 position automatically.

    Then, move the 96 Probe Head down to the 96 Deep Well Plate nearby.

    <figure><img src="../../../../.gitbook/assets/image (354).png" alt=""><figcaption></figcaption></figure>


13. Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (353).png" alt=""><figcaption></figcaption></figure>


14. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (275).png" alt=""><figcaption></figcaption></figure>


15. In advance to save and apply the adjusted position values(X, Y, & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
16. After that, to save and apply the adjusted position values(X, Y, & Z Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (300).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 16 (DWP96_HHS)</strong></mark></summary>

1.  Place the '96 Deep Well Plate' in position No. 16.

    <figure><img src="../../../../.gitbook/assets/image (327).png" alt=""><figcaption></figcaption></figure>


2.  Execute the STAR Service.

    ![](<../../../../.gitbook/assets/image (289).png>)


3.  Go to the Heater Shaker Control option.

    (Control tab -> Movements/Sensors -> Heater Shaker)
4.  Set the 'Heater Shaker Address' as 'T1'

    <figure><img src="../../../../.gitbook/assets/image (316).png" alt=""><figcaption></figcaption></figure>


5.  On the 'Plate lock-Drive' tab in the popped-up 'Heater Shaker' window,

    1\) Click the 'Initialize' button.

    2\) Click the 'Plate locked' button.

    3\) Click the 'Plate free' button.

    <figure><img src="../../../../.gitbook/assets/image (347).png" alt=""><figcaption></figcaption></figure>


6. Find the 'DWP96\_HHS' and select it.
7. Right-click on the selected position. Then, click the 'Adjust Location...'.
8.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (308).png" alt=""><figcaption></figcaption></figure>


9.  'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'

    <figure><img src="../../../../.gitbook/assets/image (304).png" alt=""><figcaption></figcaption></figure>


10. 'Move Probe - Key Control' will be newly popped up.&#x20;

    The independent channel will pick the teaching needle up and move to the No. 16 position automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the '96 Deep Well Plate' nearby.

    <figure><img src="../../../../.gitbook/assets/image (328).png" alt=""><figcaption></figcaption></figure>


11. Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (352).png" alt=""><figcaption></figcaption></figure>


12. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (362).png" alt=""><figcaption></figcaption></figure>


13. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
14. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (281).png" alt=""><figcaption></figcaption></figure>

</details>
