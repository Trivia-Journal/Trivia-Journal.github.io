# SAHS

## <mark style="color:blue;">1. FW Release Note List</mark>

<details>

<summary><mark style="color:blue;">SAHS Firmware Version 1.0.9 / Relase Note</mark></summary>

*   <mark style="color:blue;">**Release Note:**</mark>

    &#x20;<mark style="color:blue;">**- Changes: \[Calibration] Auto Position Calibration**</mark>

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** Define the virtual map for Y & Z Axis using the film detectors on the initialization.

    <figure><img src="../../../.gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

    &#x20;**- Remark:** Y-Axis for the Bed Position, Z-Axis for the height from the Bed





    &#x20;<mark style="color:blue;">**- Changes: \[Calibration] Plate Sensing Calibration**</mark>

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** Define the best sensing distance between the feeder hand and the plate using the film detectors precisely

    <figure><img src="../../../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

    &#x20;**- Remark:** Do not need to run this every time. Recommend running this right after 'Auto Position Calibration' at your Installation

    &#x20;                  \-> Due to the minor variation in the plate bed's height and level among the instrument, this procedure aims to minimize the minor variation&#x20;





    &#x20;<mark style="color:blue;">**- Changes: \[Algorithms] Film Pick-up Detection on the Feeder Fans**</mark>

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** If the film is not properly picked up, Blow out Fans will start to rotate due to the air leak

    <figure><img src="../../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

    &#x20;**- Remark:** This will show up as '\[1713] Film suction failed / Check the film in film tray' on the AIOS





    &#x20;<mark style="color:blue;">**- Changes: \[Algorithms] Shifted film detection (Before the heat sealing)**</mark>

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** To check if the film is shifted correctly on the PCR Plate, detect the defined 4 spots

    <figure><img src="../../../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

    &#x20;**- Remark:** Among the 4 spots, having 3 or 4 feedback detected will go on for the heat sealing. Less than 3 spots will show up an alarm '\[1711] Film shift detected.'

    <figure><img src="../../../.gitbook/assets/image (210).png" alt=""><figcaption></figcaption></figure>





    &#x20;<mark style="color:blue;">**- Changes: \[Algorithms] Well open detection (After the heat sealing)**</mark>

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** To check if the film is sealed correctly on the PCR Plate, scan the row "G", 12 points

    <figure><img src="../../../.gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

    &#x20;**- Remark:** Any feedback missing among 12 points will show up an alarm '\[1712] Well-open plate detected after sealing'



*   <mark style="color:blue;">**Prerequisite:**</mark>

    * [x] In advance to update the Firmware to V 1.0.9,
      1. Initialize the SAHS.
      2.  Must conduct the adjustment of the origin for Z-Axis, Y-Axis, and Sensor.

          <mark style="color:red;">\*Refer to the details(Way to adjust the origin) in each section of the SAHS Replacement page - '</mark>[replacement.md](../service-info./sahs/replacement.md "mention")<mark style="color:red;">'.</mark>



          *   **Z-Axis (Feeder Z Motor Assy)**

              \-> Origin(=Alignment Gap): 7.5 mm (± 0.2 mm)
          *   **Y-Axis (Feeder Y Motor Assy)**

              \-> Origin(=Alignment Gap): 2.0 mm (± 0.2 mm)
          *   **Sensor (Contact Switch Assy)**

              \-> Origin(=Alignment Gap): 1.5 mm


* <mark style="color:blue;">**Preparation:**</mark>
  * [x] Laptop
  * [x] Cable (USB 2.0 Micro 5 pin)
  *   [x] Firmware Upgrade Program Installer(STM32Cube Programmer\_win64)

      \-> Able to download the installer on the link below.

      Click '[Link](sahs.md#sahs-firmware-update-program-installer-stm32cube-programmer\_win64)'
  *   [x] Firmware file(HSD\_REV1.0.9\_20221206.hex).

      \-> Able to download the file on the link below.

      Click '[Link](sahs.md#sahs-firmware-version-1.0.9\_update-file-hsd\_rev.1.0.9\_20221206.hex)'
  *   [x] Guide to updating the Firmware version 1.0.9

      \-> Able to download the guide as a PDF on the link below.

      Click '[Link](sahs.md#sahs-firmware-version-1.0.9\_guide-to-updating)'

<!---->

*   <mark style="color:blue;">**Procedure:**</mark>

    1. Install the Firmware Upgrade Program - STM32Cube Programmer.
    2. Connect the communication between Laptop and SAHS by the cable(USB 2.0 Micro 5 pin).
    3. Hold down the Enable Button and turn the sealer on. Able to hear the beep sound for about 5 sec.
    4. Execute the Firmware Upgrade Program - STM32Cube Programmer.
    5. Select the COM. Type as 'USB' in the Combobox of COM. Type.
    6. To check the COM. Connection, click the Refresh icon.
    7. To connect the COM., click the Connect icon.
    8. Click the '+' tab and 'Open file' in sequence. Then, select and open the firmware file on File Explorer will be popped up.
    9. Click the 'Download' icon.
    10. Able to see the 'Completed' message if the firmware would be updated successfully.
    11. Lastly, click the 'Disconnect' icon. Then, turn the SAHS off and on again.


* <mark style="color:blue;">**Check the FW Version:**</mark>
  1. Enter the 'Admin Setting' in AIOS UI.
  2. Put the admin password(_**seegene1!**_).
  3. Able to check if the SAHS Firmware is updated in the Instrument Serial Number box.

</details>

<details>

<summary><mark style="color:blue;">SAHS Firmware Version 1.0.8 / Relase Note</mark></summary>

*   <mark style="color:blue;">**Release Note:**</mark>

    &#x20;**- Changes: -**

    &#x20;**- Criterion: -**

    &#x20;**- Details: -**

    &#x20;**- Remark: -**

<!---->

*   <mark style="color:blue;">**Prerequisite:**</mark>

    * [x] In advance to update the Firmware to V 1.0.8,
      1. Initialize the SAHS.
      2.  Must conduct the adjustment of the origin for Z-Axis, Y-Axis, and Sensor.

          <mark style="color:red;">\*Refer to the details(Way to adjust the origin) in each section of the SAHS Replacement page - '</mark>[replacement.md](../service-info./sahs/replacement.md "mention")<mark style="color:red;">'.</mark>



          *   **Z-Axis (Feeder Z Motor Assy)**

              \-> Origin(=Alignment Gap): 7 mm (± 0.7 mm)
          *   **Y-Axis (Feeder Y Motor Assy)**

              \-> Origin(=Alignment Gap): 2 mm (± 0.5 mm)
          *   **Sensor (Contact Switch Assy)**

              \-> Origin(=Alignment Gap): 1.5 mm


* <mark style="color:blue;">**Preparation:**</mark>
  * [x] Laptop
  * [x] Cable (USB 2.0 Micro 5 pin)
  *   [x] Firmware Upgrade Program Installer(STM32Cube Programmer\_win64)

      \-> Able to download the installer on the link below.&#x20;

      Click '[Link](sahs.md#sahs-firmware-update-program-installer-stm32cube-programmer\_win64)'
  *   [x] Firmware file(HSD\_REV1.0.8\_beta.hex).

      \-> Able to download the file on the link below.

      Click '[Link](sahs.md#sahs-firmware-version-1.0.8\_update-file-hsd\_rev.1.0.8\_beta.hex)'
  *   [x] Guide to updating the Firmware version 1.0.8

      \-> Able to download the guide as a PDF on the link below.

      Click '[Link](sahs.md#sahs-firmware-version-1.0.8\_guide-to-updating)'

<!---->

*   <mark style="color:blue;">**Procedure:**</mark>

    1. Install the Firmware Upgrade Program - STM32Cube Programmer.
    2. Connect the communication between Laptop and SAHS by the cable(USB 2.0 Micro 5 pin).
    3. Hold down the Enable Button and turn the sealer on. Able to hear the beep sound for about 5 sec.
    4. Execute the Firmware Upgrade Program - STM32Cube Programmer.
    5. Select the COM. Type as 'USB' in the Combobox of COM. Type.
    6. To check the COM. Connection, click the Refresh icon.
    7. To connect the COM., click the Connect icon.
    8. Click the '+' tab and 'Open file' in sequence. Then, select and open the firmware file on File Explorer will be popped up.
    9. Click the 'Download' icon.
    10. Able to see the 'Completed' message if the firmware would be updated successfully.
    11. Lastly, click the 'Disconnect' icon. Then, turn the SAHS off and on again.


* <mark style="color:blue;">**Check the FW Version:**</mark>
  1. Enter the 'Admin Setting' in AIOS UI.
  2. Put the admin password(_**seegene1!**_).
  3. Able to check if the SAHS Firmware is updated in the Instrument Serial Number box.

</details>

### &#x20;   1-1. FW Update Program Installer List

<details>

<summary>SAHS Firmware Update Program Installer(STM32Cube Programmer_win64)</summary>

*   Able to download it on the link below.



</details>

### &#x20;   1-2. FW Update File List

<details>

<summary>SAHS Firmware Version 1.0.9_Update File(HSD_REV.1.0.9_20221206.hex)</summary>

*   Able to download it on the link below.



</details>

<details>

<summary>SAHS Firmware Version 1.0.8_Update File(HSD_REV.1.0.8_beta.hex)</summary>

*   Able to download it on the link below.





</details>

### &#x20;   1-3. FW Update User Guide List

<details>

<summary>SAHS Firmware Version 1.0.9_Guide to updating</summary>

*   \[Document] Able to see it on the link below.



</details>

<details>

<summary>SAHS Firmware Version 1.0.8_Guide to updating</summary>

*   \[Document] Able to see it on the link below.



</details>







