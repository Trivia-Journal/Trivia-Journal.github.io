# Macro

## &#x20;   <mark style="color:blue;">1. Macro - Conduction of Alignment and Calibration for Mechanical Function Unit (MFU)</mark>

### &#x20;       1-1. Prerequisite

STARlet equipped with CO-RE 96 Modular ARM & Multi-Probe-Head II.

All system is a green condition under the default system config. & condition (which allows the 'Align. & Cal.' for the STARlet 96 Probe Head & 8 Independent Channels.) if these meet the following criteria:

* Configuration - Left Arm Option: 'Large Motor', 'CoRe 96 Head', and 'Pipetting Channel'
* Initialization - 'All detected components condition', and ' Mechanical Operation'

<figure><img src="../../../../../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

* Tool Required:
  * [x] Service Software 4.9.0.758 or higher
  * [x] Service Macro Package 4.9.0.758 or higher
  * [x] Adjust\_H0\_XY\_Tilt.zip
  * [x] Channel Calibration Tool (P/N 173960)
  * [x] CO-RE 96 Tilt Calibration Tool (P/N 6600023-01)
  * [x] CO-RE 96-Probe Head Adjustment Tool II (P/N 199153)
  * [x] M4 Stubby Allen Wrench (P/N TL-6600486-01 for Y/Z Drive)

{% hint style="info" %}
As for the apps - 'Service Software', 'Service Macro Package', and 'Adjust\_H0\_XY\_Tilt.zip' -, please refer to the section(Page Link) to download them.
{% endhint %}

{% hint style="info" %}
Refer to the figures below for the required tools.

* In order of the figures below,
  1. Channel Calibration Tool (P/N 173960)
  2. CO-RE 96 Tilt Calibration Tool (P/N 6600023-01)
  3. CO-RE 96-Probe Head Adjustment Tool II (P/N 199153)
  4.  M4 Stubby Allen Wrench (P/N TL-6600486-01 for Y/Z Drive)

      <figure><img src="../../../../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>
{% endhint %}

### &#x20;       1-2. Summary

&#x20; If all the prerequisite is met above, able to perform the following MACRO steps below:

* Arm (Marco) & 8 Independent Channels (Macro): 'Adjust\_Arm\_Z\_using\_PIP', 'Check\_Arm\_X\_Diff',  'Adjust\_PIP\_Manual', _<mark style="color:red;">**'Adjust\_PIP(Refer to the warning below)'**</mark>_, 'Check\_PIP'
* Autoload (Macro): 'Adjust\_Autoload', 'Check\_Autoload'
* 96 Probe Head (Macro): 'Adjust\_H0\_XY\_Tilt', 'Adjust\_H0', 'Check\_H0'

{% hint style="warning" %}
_<mark style="color:red;">**As for the 'Adjust\_PIP' Macro**</mark>_, on this macro, STARlet will determine the variant parameters, e.g., 'X-Offset for X-Arm', 'Y and Z-Offset for channels', and so on and write them to the PCB Assy(Main Processor) & each PCB Assy(Channel) to store them.&#x20;



<mark style="color:red;">**Namely, in the case of upgrading the CO-RE 96 Modular Arm to install the CO-RE 96 MPH, you have to conduct all the macros without missing or skipping.**</mark>
{% endhint %}

{% hint style="info" %}
As for 'Adjust\_H0\_XY\_Tilt' Macro as '.MCR,' you should paste it into the folder firsthand to set & execute it in the STAR service_._

Directory is _'C:\ProgramData\HAMILTON\STARServie\Macros\Adjust'._



*   The way to define the button for the Macro files('Adjust\_H0\_XY\_Tilt' & 'Adjust\_H0') refers to the figures below.

    Directory is _'C:\ProgramData\HAMILTON\STARServie\Macros\Adjust'._



    <figure><img src="../../../../../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>



    <figure><img src="../../../../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>


*   The way to define the button for the Macro file('Check\_H0') refers to the figures below.

    Directory is _'C:\ProgramData\HAMILTON\STARServie\Macros\Check'._



    <figure><img src="../../../../../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>
{% endhint %}

{% hint style="info" %}
As for 'Adjust\_X\_Using\_H0' & 'Adjust\_Arm\_Z\_Using\_H0' Macros as .MCR, need to run only if one of the following conditions applies. <mark style="color:blue;">**Namely, we don't need to run those Macros in the Seegene STARlet equipped with CO-RE 96 MPH because we did that on the step - 'Adjust\_Arm\_Z\_using\_PIP' and 'Check\_Arm\_X\_Diff' using 8 Independent Channels.**</mark>



*   Adjust\_X\_Using\_H0'

    * [x] If the Arm, on which the 1000µl CO-RE 96-Probe Head II is mounted, has no Channels and the Dual Processor Board has been replaced.
    * [x] If the Arm, on which the 1000µl CO-RE 96-Probe Head II is mounted, has no Channels and never has been adjusted before (e.g. new X-Arm is installed).


*   'Adjust\_Arm\_Z\_Using\_H0'

    * [x] If the Arm, on which the 1000µl CO-RE 96-Probe Head II is mounted, has no Channels, and observations of wrong Z-Positioning of the CO-RE 96-Probe Head indicate that the Front Guide Bar is misaligned
    * [x] If the Arm, on which the 1000µl CO-RE 96-Probe Head II is mounted, has no Channels, and a component on the X-Arm has been replaced

    \


    <figure><img src="../../../../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>
{% endhint %}

### &#x20;       1-3. Recommendation

In advance, perform the MACRO steps below.

* <mark style="color:red;">**Arm (Marco) & 8 Independent channels (Marco): 'Adjust\_Arm\_Z\_using\_PIP', 'Check\_Arm\_X\_Diff', 'Adjust\_PIP\_Manual', 'Adjust\_PIP', 'Check\_PIP'**</mark>
* (Optional) Autoload (Macro): 'Adjust\_Autoload', 'Check\_Autoload'

{% hint style="info" %}
As for the Arm (Marco) & 8 Independent channels (Marco), please refer to the details in this section (Link)
{% endhint %}

In order to successfully perform the MACRO steps of 96 Probe Head, follow the section - [#1-5.-procedure-for-the-align.-and-cal.-for-the-96-probe-head](macro.md#1-5.-procedure-for-the-align.-and-cal.-for-the-96-probe-head "mention")



### &#x20;       1-4. Part Information

| No. | Part Number (P/N) |         Part Name & Description        |
| :-: | :---------------: | :------------------------------------: |
|  1  |       173960      |        Channel Calibration Tool        |
|  2  |     6600023-01    |     CO-RE 96 Tilt Calibration Tool     |
|  3  |       199153      | CO-RE 96-Probe Head Adjustment Tool II |
|  4  |   TL-6600486-01   |  M4 Stubby Allen Wrench for Y/Z Drive  |



### &#x20;       **1-5. Procedure for the Align. & Cal. for the 96 Probe Head**

### &#x20;           A. 'Adjust\_H0\_XY\_Tilt'

### &#x20;               A-1. Execute the 'Adjust\_H0\_XY\_Tilt'

1. Execute the Hamilton Microlab STAR Service apps.
2.  Click the 'Adjust\_H0\_XY\_Tilt' icon.



    <figure><img src="../../../../../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

### &#x20;               A-2. Set the Channel Calibration Tool (P/N 173960)

1.  VARINPUT window will be popped up and place the Channel Calibration Tool (P/N 173960) at the 10th position of the deck.



    <figure><img src="../../../../../.gitbook/assets/image (208).png" alt=""><figcaption></figcaption></figure>
2.  Then, put '10' into the blank and click the 'OK' button.



    <figure><img src="../../../../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

### &#x20;               A-3. Set the CO-RE 96 Tilt Calibration Tool (P/N 6600023-01)

1. The guide will be popped up. At the same time, 96 Probe Head will be moved automatically to the attachment position of the CO-RE 96 Tilt Calibration Tool (P/N 6600023-01).
2.  Attach the CO-RE 96 Tilt Calibration Tool (P/N 6600023-01) referring to the guide shown below and maintain this condition until the 96 Probe Head grips it by squeezing.&#x20;

    Then, click 'OK'.



    <figure><img src="../../../../../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>
3.  Double-check if the CO-RE 96 Tilt Calibration Tool (P/N 6600023-01) is gripped correctly.&#x20;

    At the same time, the guide window will be popped up shown below.&#x20;

    Then, click 'Yes'.





    <figure><img src="../../../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

### &#x20;               A-4. Run the 'Adjust\_H0\_XY\_Tilt'

1. Wait for the processing of the 'Adjust\_H0\_XY\_Tilt' macro by STARlet.
2. After then, able to get the X/Y Tilt measurement.
3.  Check if both Tilt Differences are in the Tolerance(±0.20 mm).&#x20;

    If not, you have to align the CO-RE 96 MPH for the tilting condition (which was out of Tolerance(±0.20))
4.  Repeat to do the following steps above until you get the PASSED for the tilting alignment condition of both X & Y Coordinates.



    <figure><img src="../../../../../.gitbook/assets/image (249).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Do not pass this step by clicking 'No' until you get the PASSED for the tilting alignment condition of both X & Y Coordinates.
{% endhint %}

{% hint style="info" %}
As for the way to adjust the tilting alignment condition, please refer to each section [#a-5-1.-the-way-to-adjust-the-tilting-on-the-x-coordinate](macro.md#a-5-1.-the-way-to-adjust-the-tilting-on-the-x-coordinate "mention") [#a-5-2.-the-way-to-adjust-the-tilting-on-the-y-coordinate](macro.md#a-5-2.-the-way-to-adjust-the-tilting-on-the-y-coordinate "mention")
{% endhint %}



### &#x20;               A-5. Align the Mechanical Function Unit of 96 Probe Head for the Tilting condition on the X and Y coordinates

### &#x20;                   A-5-1. The way to adjust the tilting on the X coordinate

1.  Loosen the screws (4ea in total) slightly.

    <figure><img src="../../../../../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>
2.  Then, adjust the X-tilting condition of the 96 Probe Head with the set screw.&#x20;

    Refer to the 'Virtual-Tilting-Position Drawing' below for your understanding to see how makes it.



    <figure><img src="../../../../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>
3. After then, click 'Yes' to recheck the X-Tilting Condition.
4.  Repeat to perform the steps above until the X-Tilt Difference in the Tolerance(±0.20).



{% hint style="info" %}
To check and see the processing status text,

*   copy them via the point mentioned below by dragging.



    <figure><img src="../../../../../.gitbook/assets/image (253).png" alt=""><figcaption></figcaption></figure>
*   Then, paste them into the notepad.



    <figure><img src="../../../../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>
{% endhint %}



### &#x20;                   A-5-2. The way to adjust the tilting on the Y coordinate

1.  Loosen the screws (3ea in total) slightly.

    &#x20;

    <figure><img src="../../../../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>
2.  Then, adjust the Y-tilting condition of the 96 Probe Head with the set screw.&#x20;

    Refer to the 'Virtual-Tilting-Position Drawing' below for your understanding to see how makes it.



    <figure><img src="../../../../../.gitbook/assets/image (306).png" alt=""><figcaption></figcaption></figure>
3. After then, click 'Yes' to recheck the Y-Tilting Condition.
4. Repeat to perform the steps above until the Y-Tilt Difference in the Tolerance(±0.20).

{% hint style="info" %}
To check and see the processing status text,

*   copy them via the point mentioned below by dragging.

    <figure><img src="../../../../../.gitbook/assets/image (253).png" alt=""><figcaption></figcaption></figure>
*   Then, paste them into the notepad.

    <figure><img src="../../../../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>
{% endhint %}

{% hint style="warning" %}
Please hold the adjustment tool!

*   Will be able to see the message below popped up after finishing the step for 'Adjust\_H0\_XY\_Tilt'.



    <figure><img src="../../../../../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>
{% endhint %}





### &#x20;           B. 'Adjust\_H0'

### &#x20;               B-1. Execute the'Adjust\_H0'

1.  After completing the 'Adjust\_H0\_XY\_Tilt' Macro step successfully, able to execute the 'Adjust\_H0' Macro by clicking the 'Adjust\_H0' icon in the STAR Service.



    <figure><img src="../../../../../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The ADJUST\_H0.MCR Macro Program generates adjustment parameters for the 1000µl CO-RE 96-Probe Head II
{% endhint %}

{% hint style="warning" %}
If the Arm, on which the 1000µl 96 Probe Head is mounted, has Channels, make sure that the Adjustment Macro for 8 Independent Channels has been completed successfully before running the ADJUST\_H0.MCR Macro Program.&#x20;



Run the Macro Program only if one of the following conditions applies:

* During the installation of a new Instrument
* After the Replacement of the 1000µl 96 Probe Head
* If poor positioning of the 1000µl 96 Probe Head during pipetting indicates that the alignment is out
* After every new adjustment of the Channels
{% endhint %}

### &#x20;               B-2. Set the CO-RE 96-Probe Head Adjustment Tool II (P/N 199153)

1.  Click 'Yes' to enter the '96 Head PN', 'Rev', and 'SN'.



    <figure><img src="../../../../../.gitbook/assets/image (297).png" alt=""><figcaption></figcaption></figure>
2.  VARINPUT window will be popped up to enter the reachable track for 'Channel Calibration Tool (P/N: 173960)'.

    Enter the '5' into the blank and click the 'OK' button.

    Put the 'Channel Calibration Tool (P/N: 173960)' to slot position No. 5.



    <figure><img src="../../../../../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>
3. The guide will be popped up. At the same time, 96 Probe Head will be moved automatically to the attachment position of the CO-RE 96 Adjustment Tool (P/N 199153).
4.  Attach the CO-RE 96 Tilt Adjustment Tool (P/N 199153) referring to the guide shown below and maintain this condition until the 96 Probe Head grips it by squeezing for about 6 seconds.

    Then, click 'OK'.



    <figure><img src="../../../../../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>


5.  Double-check if the CO-RE 96 Adjustment Tool (P/N 199153) is gripped correctly.&#x20;

    At the same time, the guide window will be popped up shown below.&#x20;

    Then, click 'Yes'.



    <figure><img src="../../../../../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

### &#x20;               B-3. Run the 'Adjust\_H0'

1. Wait for the processing of the 'Adjust\_H0' macro by STARlet.

{% hint style="warning" %}
Please hold the adjustment tool!

*   Will be able to see the message below popped up after finishing the step for 'Adjust\_H0'.



    <figure><img src="../../../../../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>
{% endhint %}





### &#x20;           C. 'Check\_H0'

### &#x20;               C-1.  Preparation for the execution of the 'Check\_H0'&#x20;

1.  The following items are required for the 'Check\_H0' Macro. FYI, the macro allows you to choose the tip type.



    <figure><img src="../../../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>
2. The 96 Probe Head will pick up the Tips and eject them again back into the pick-up position. The check is of a visual and audial nature.

{% hint style="info" %}
* The Tip pick-up must be smooth, and no positioning offsets in X or Y must be observed.
* There must be no crackling noises during the Tip pick up.
{% endhint %}

### &#x20;               C-2. Execute 'Check\_H0'

1.  Execute the 'Check\_H0' Macro by clicking the 'Check\_H0' icon in the STAR Service.



    <figure><img src="../../../../../.gitbook/assets/image (260).png" alt=""><figcaption></figcaption></figure>

### &#x20;               C-3. Place the Tip Carrier on the deck

1.  Put the Tip Carrier on the deck, Track 1.&#x20;

    Then, place each tip type - High Volume, Standard Volume, and Low Volume Tip - on the Tip Carrier, TIPCAR480\_A00 (P/N 182085).



    <figure><img src="../../../../../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

### &#x20;               C-4. Run 'Check\_H0'

1. Run the 'Check\_H0' Macro following the guides shown on the poped-up window.
2.  Depending on the tip types of each carrier position(1 to 5), put the correct number defined for each tip type into the blank in the poped-up window.

    <figure><img src="../../../../../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>



    <figure><img src="../../../../../.gitbook/assets/image (334).png" alt=""><figcaption></figcaption></figure>
3.  Repeat Step 2 above 5 times in total, 'Check\_H0' macro will be finished.

    <figure><img src="../../../../../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>





