# Maelstrom 9600

## <mark style="color:blue;">1.  FW(PLC) & SW(HMI) Release Note List</mark>

<details>

<summary><mark style="color:blue;">M9600 FW(PLC) &#x26; SW(HMI) 20210420 (which was released on April 21st 2021.)</mark></summary>

*   <mark style="color:blue;">**Release Note:**</mark>

    &#x20;**- Changes:** \[System] Optimize the turntable rotation logical control algorithm&#x20;

    &#x20;**- Criterion:** Debugging

    &#x20;**- Details:** <mark style="background-color:yellow;">To improve the change of system freezing in plate 2 while running a program(Protocol)</mark>

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Note] Important Note on updating the PLC FW and HMI SW

    &#x20;**- Criterion:** Note

    &#x20;**- Details:** <mark style="background-color:yellow;">In order to make the function and display normally, both PLC FW and HMI SW have to be updated to the latest version 20210420 simultaneously</mark>

    &#x20;**- Remark:** N/A

<!---->

* <mark style="color:blue;">**Prerequisite:**</mark>
  * [x] Check the FW & SW version installed in Maelstrom 9600
  * [x] Check the HMI Model name
  *   [x] <mark style="background-color:yellow;">You must recode things below</mark>

      \-> Protocols in Edit

      \-> The original Plate Offset degree (Ex: x.xxº) in Plate Setting of Factory Setting

      \-> The original parameter in Temp. of Setting:

      &#x20;    1\) Temp (Preset, SV/PV Diffe, TEMP.Offset)

      \-> The original parameter in Factory Setting:

      &#x20;    1\) Plate Setting

      &#x20;    2\) Mixing

      &#x20;    3\) Collect

      &#x20;    4\) Spin

      &#x20;    5\) Plate Name
*   <mark style="color:blue;">**Preparation:**</mark>

    * [x] PC: Laptop
    * [x] USB Cable: 2.0 Type / A-A Type
    *   [x] Program: GX Works2(For PLC), EU Editor2(For HMI)

        <mark style="background-color:yellow;">-> Able to download them on the link below.</mark>[#2.-fw-plc-and-sw-hmi-update-program-installer-and-driver-list](maelstrom-9600.md#2.-fw-plc-and-sw-hmi-update-program-installer-and-driver-list "mention")
    *   [x] FW & SW Files: 20210420.gxw (For PLC), 20210420.eu2(For HMI)

        <mark style="background-color:yellow;">-> Able to download them on the link below.</mark>[#3.-fw-plc-and-sw-hmi-update-file-list](maelstrom-9600.md#3.-fw-plc-and-sw-hmi-update-file-list "mention")
    *   [x] Driver: Serial Port Driver, FX3U-USB-BD Driver

        <mark style="background-color:yellow;">-> Able to download them on the link below.</mark>[#2.-fw-plc-and-sw-hmi-update-program-installer-and-driver-list](maelstrom-9600.md#2.-fw-plc-and-sw-hmi-update-program-installer-and-driver-list "mention")


* <mark style="color:blue;">**Procedure for FW(PLC):**</mark>
  1. **Install the 'GX Work2'**
  2.  **Check if the communication**&#x20;

      \-> Able to check the communication between PC and M9600 on the Device Manager in the PC
  3.  **Update the Driver**

      \-> Able to update the FX3U-USB-BD and USB Serial Port Driver on the Device Manager
  4.  **Update the Firmware**

      \-> Update the PLC Firmware to open the 20210420.gxw in the GX Work2
  5.  **Check if the PLC Firmware version is updated on the M9600**

      \-> Able to check it on the upper side of Setting UI



*   <mark style="color:blue;">**Procedure for SW(HMI):**</mark>

    1. **Install the 'EU Editor2'**
    2.  **Check if the communication**

        \-> Able to check the communication between PC and M9600 on the Device Manager in the PC
    3.  **Update the Software**

        \-> Update the HMI Software to open the 20210420.eu2 in the EU Editor2
    4.  **Check if the HMI Software version is updated on the M9600**

        \-> Able to check it on the right-upper side of Main UI
    5.  <mark style="background-color:yellow;">**Convert the original Plate Offset x.xxº into a pulse by x80**</mark>

        \-> Example, Plate Offset: 2.60º x 80 = 208 Pulse. Input 208 pulse in Plate Offset.
    6.  <mark style="background-color:yellow;">**Input the pulse value for each plate position**</mark>

        \-> Plate1: 25200 / Plate2: 0 / Plate3: 3600 / Plate4: 7200 / Plate5: 10800 / Plate 6: 14400 / Plate7: 18000 / Plate8: 21600
    7.  <mark style="background-color:yellow;">**Check if all the parameters are maintained**</mark>

        \-> Protocols, Temp. Plate Setting, Mixing, Collect, Spin, and Plate Name


* <mark style="color:blue;">**Reference:**</mark>&#x20;
  *   Please refer to the details for the procedure above by video clip on the link below

      <mark style="background-color:yellow;">**->**</mark> [#4.-fw-plc-and-sw-hmi-user-guide-list](maelstrom-9600.md#4.-fw-plc-and-sw-hmi-user-guide-list "mention")

</details>

### &#x20;   1-1. FW(PLC) & SW(HMI) Update Program Installer & Driver List

<details>

<summary>FW(PLC) Update Program - GX Work 2 (iQ Works Version 1.28E)</summary>

*   Able to download it as a '.zip' on the link below.



</details>

<details>

<summary>FW(PLC) Driver - fxusbdrv170</summary>

*   Able to download it as a '.zip' on the link below.



</details>

<details>

<summary>SW(HMI) Update Program - HMI EU Editor (2.9.8.7z)</summary>

*   Able to download it as a '.zip' on the link below.



</details>

### &#x20;   1-2. FW(PLC) & SW(HMI) Update File List

<details>

<summary>FW(PLC) - 20210420.gxw</summary>

*   Able to download it on the link below.



</details>

<details>

<summary>SW(HMI) - 20210420.eu2</summary>

* Able to download it on the link below.

</details>

### &#x20;   1-3. FW(PLC) & SW(HMI) User Guide List

<details>

<summary>[M9600] The way to upgrade the PLC FW &#x26; HMI SW_Criterion V_202104020_GATC(R0)-220331-001</summary>

*   \[Video Clip] Please refer to the link below to watch it.




*   \[Document] Please refer to the link below to see it.



</details>
