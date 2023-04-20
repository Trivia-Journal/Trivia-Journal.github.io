# MicroLAB Prep

## <mark style="color:blue;">1. FW & SW Release Note List</mark>

<details>

<summary><mark style="color:blue;">ML Prep FW &#x26; SW 3.0.2.00001 (Intergrated Type)</mark></summary>

*   <mark style="color:blue;">**Release Note:**</mark>

    &#x20;**- Changes:** \[Configuration] IP and Network&#x20;

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** Allow input/output to and from network locations

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Performance] Camera Scan Speed

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** Improve camera scan speed

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Operation] Reusing tips

    &#x20;**- Criterion:** Development

    &#x20;**- Details:** Add support for resuing tips across multiple steps in a protocol

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Operation] Reusing tips

    &#x20;**- Criterion:** Development

    &#x20;**- Details:** Add support for resuing tips across multiple steps in a protocol

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Operation] Partial Tip Racks

    &#x20;**- Criterion:** Improvement

    &#x20;**- Details:** Allow partial tip racks on the deck to be consumed before reload prompt

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Operation] Selecting tube rack

    &#x20;**- Criterion:** Development

    &#x20;**- Details:** Add support for explicitly selecting tube rack

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Operation] Disabling steps

    &#x20;**- Criterion:** Development

    &#x20;**- Details:** Add support for disabling steps

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Notice] Compatibility of protocol

    &#x20;**- Criterion:** Verification

    &#x20;**- Details:** All the existing protocols designed and distributed by Seegene Inc.,&#x20;

    &#x20;                verified and confirmed on the ML Prep FW & SW 3.0.2.0001.

    &#x20;**- Remark:** In the case of the protocol generated and exported&#x20;

    &#x20;                 on the ML Prep FW & SW 2. x,&#x20;

    &#x20;                 it won't be able to use it on the ML Prep FW & SW 3. x.

<!---->

*   <mark style="color:blue;">**Prerequisite:**</mark>

    * [x] Check the FW & SW version installed in MicroLAB Prep.
    * [x] Conduct the Database Backup maintenance to make a DB Backup file.


*   <mark style="color:blue;">**Preparation:**</mark>

    * [x] USB Drive
    *   [x] MLPrepUpdate\_3.0.2.00001.mlpi file

        \-> Able to download the file on the link below.

        [#3.-fw-and-sw-update-file-list](microlab-prep.md#3.-fw-and-sw-update-file-list "mention")


* <mark style="color:blue;">**Procedure:**</mark>
  1. **Place the ML Prep FW & SW 3.0.2.00001.mlpi file on a USB Drive**
  2.  **Insert the USB drive**

      \-> The ports are located on the left side of the Prep, near the bottom of the door.
  3.  **From the home page, tap the settings button.**

      \-> The settings button is located at the top-right corner and has a gear icon.
  4. **In the Software tab, tap Configuration, then open the Application tab**.
  5.  **Scroll down to the “Update and backup utility” setting and tap Launch.**

      \-> The Prep will reboot in a separate utility.
  6.  **In the Modify Software tab, tap Refresh.**&#x20;

      \-> The software version should appear in the update list (for example, “Upgrade MlPrepCore to 2.0.1.00002” with an Install button. Tap Details for a list of all changes in the package.
  7.  **Tap Install**

      \-> A dialog will appear to confirm that you want to install the update. Tap Yes to proceed.
  8.  **Wait for the upgrade to be installed.**

      \-> Do not turn off the Prep.
  9. **Tap OK in the dialog that appears after installation is complete**.
  10. **If the upgrade package contains firmware, tap Yes when asked to update it.**

      \-> After the update finishes installing, you may be prompted to physically restart the Prep. Press and hold the power button on the instrument if prompted.
  11. **Tap Exit to return to the normal Prep software**.

</details>

<details>

<summary><mark style="color:blue;">ML Prep FW &#x26; SW 2.1.5.00003 (Intergrated Type)</mark></summary>

*   <mark style="color:blue;">**Release Note:**</mark>

    &#x20;**- Changes:** \[Calibration] ‘Pressure Sensor Failure’ issue&#x20;

    &#x20;**- Criterion:** Debugging

    &#x20;**- Details:** ![](<../../../.gitbook/assets/image (47).png>)

    &#x20;**- Remark:** N/A



    &#x20;**- Changes:** \[Info] All the existing protocols designed by Seegene HQ are tested in this version without any issues

    &#x20;**- Criterion:** N/A

    &#x20;**- Details:** N/A

    &#x20;**- Remark:** Validated the compatibility



    &#x20;**- Changes:** \[Info] Recommend updating the SW version to V.2.1.5.00003 if your ML Prep version is less than

    &#x20;**- Criterion:** N/A

    &#x20;**- Details:** N/A

    &#x20;**- Remark:** Especially, Protocols designed & notified from Seegene HQ since 29th, March 2022 should be run in the version(V.2.1.5 00003)

<!---->

*   <mark style="color:blue;">**Prerequisite:**</mark>

    * [x] Check the FW & SW version installed in MicroLAB Prep.
    * [x] Conduct the Database Backup maintenance to make a DB Backup file.


*   <mark style="color:blue;">**Preparation:**</mark>

    * [x] USB Drive
    *   [x] MLPrepUpdate\_2.1.5.000103.mlpi file

        \-> Able to download the file on the link below.

        [#3.-fw-and-sw-update-file-list](microlab-prep.md#3.-fw-and-sw-update-file-list "mention")


* <mark style="color:blue;">**Procedure:**</mark>
  1. **Place the ML Prep FW & SW 2.1.5.00003.mlpi file on a USB Drive**
  2.  **Insert the USB drive**

      \-> The ports are located on the left side of the Prep, near the bottom of the door.
  3.  **From the home page, tap the settings button.**

      \-> The settings button is located at the top-right corner and has a gear icon.
  4. **In the Software tab, tap Configuration, then open the Application tab**.
  5.  **Scroll down to the “Update and backup utility” setting and tap Launch.**

      \-> The Prep will reboot in a separate utility.
  6.  **In the Modify Software tab, tap Refresh.**&#x20;

      \-> The software version should appear in the update list (for example, “Upgrade MlPrepCore to 2.0.1.00002” with an Install button. Tap Details for a list of all changes in the package.
  7.  **Tap Install**

      \-> A dialog will appear to confirm that you want to install the update. Tap Yes to proceed.
  8.  **Wait for the upgrade to be installed.**

      \-> Do not turn off the Prep.
  9. **Tap OK in the dialog that appears after installation is complete**.
  10. **If the upgrade package contains firmware, tap Yes when asked to update it.**

      \-> After the update finishes installing, you may be prompted to physically restart the Prep. Press and hold the power button on the instrument if prompted.
  11. **Tap Exit to return to the normal Prep software**.

</details>

<details>

<summary><mark style="color:blue;">ML Prep FW &#x26; SW 2.1.3.00011 (Intergrated Type)</mark></summary>

*   <mark style="color:blue;">**Release Note:**</mark>

    &#x20;**- Changes:** \[System] Modified the 'SW Bug' and changed 'System Configuration' related to the 'Account Setting'

    &#x20;**- Criterion:** Debugging, Changing the setting parameter to prevent the claim(Logging error)

    &#x20;**- Details:**

    <figure><img src="../../../.gitbook/assets/image (32).png" alt=""><figcaption><p>    <strong>- Remark:</strong> N/A</p></figcaption></figure>

    &#x20;**- Remark:** N/A





    &#x20;**- Changes:** \[Info] Recommend updating the SW version to V.2.1.3.00011 if your ML Prep version is less than

    &#x20;**- Criterion:** N/A

    &#x20;**- Details:** N/A

    &#x20;**- Remark:** Especially, Protocols designed & notified by Seegene HQ since 19th, November 2021 should be run in the version(V.2.1.3 00011)





    &#x20;**- Changes:** \[Info] All the existing protocols designed by Seegene HQ are tested in this version without any issues

    &#x20;**- Criterion:** N/A

    &#x20;**- Details:** N/A

    &#x20;**- Remark:** Validated the compatibility

<!---->

*   <mark style="color:blue;">**Prerequisite:**</mark>

    * [x] Check the FW & SW version installed in MicroLAB Prep.
    * [x] Conduct the Database Backup maintenance to make a DB Backup file.


*   <mark style="color:blue;">**Preparation:**</mark>

    * [x] USB Drive
    *   [x] MLPrepUpdate\_2.1.3.00011.mlpi file

        \-> Able to download the file on the link below.

        [#3.-fw-and-sw-update-file-list](microlab-prep.md#3.-fw-and-sw-update-file-list "mention")


* <mark style="color:blue;">**Procedure:**</mark>
  1. **Place the ML Prep FW & SW 2.1.3.00011.mlpi file on a USB Drive**
  2.  **Insert the USB drive**

      \-> The ports are located on the left side of the Prep, near the bottom of the door.
  3.  **From the home page, tap the settings button.**

      \-> The settings button is located at the top-right corner and has a gear icon.
  4. **In the Software tab, tap Configuration, then open the Application tab**.
  5.  **Scroll down to the “Update and backup utility” setting and tap Launch.**

      \-> The Prep will reboot in a separate utility.
  6.  **In the Modify Software tab, tap Refresh.**&#x20;

      \-> The software version should appear in the update list (for example, “Upgrade MlPrepCore to 2.0.1.00002” with an Install button. Tap Details for a list of all changes in the package.
  7.  **Tap Install**

      \-> A dialog will appear to confirm that you want to install the update. Tap Yes to proceed.
  8.  **Wait for the upgrade to be installed.**

      \-> Do not turn off the Prep.
  9. **Tap OK in the dialog that appears after installation is complete**.
  10. **If the upgrade package contains firmware, tap Yes when asked to update it.**

      \-> After the update finishes installing, you may be prompted to physically restart the Prep. Press and hold the power button on the instrument if prompted.
  11. **Tap Exit to return to the normal Prep software**.

</details>

### &#x20;   1-1. FW & SW Update File List

<details>

<summary>MLPrepUpdate_3.0.2.00001.mlpi file</summary>

*   Able to download it on the link below.



</details>

<details>

<summary>MLPrepUpdate_2.1.5.000103.mlpi file</summary>

*   Able to download it on the link below.



</details>

<details>

<summary>MLPrepUpdate_2.1.3.00011.mlpi file</summary>

*   Able to download it on the link below.



</details>

### &#x20;   1-2. FW & SW Update User Guide List

<details>

<summary></summary>



</details>

## <mark style="color:blue;">2. OS & INSTINCT V Release Note List</mark>

<details>

<summary></summary>



</details>

### &#x20;   2-1. OS & INSTINCT V Installer List

<details>

<summary></summary>



</details>

### &#x20;   2-2. OS & INSTINCT V  User Guide List

<details>

<summary></summary>



</details>

