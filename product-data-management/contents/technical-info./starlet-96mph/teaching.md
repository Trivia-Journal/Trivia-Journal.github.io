# Teaching

## &#x20;   <mark style="color:blue;">1. Teaching - Conduction of precise adjustment for the position depending on the type of labware</mark>

### &#x20;       1-1. Prerequisite

STARlet equipped with 96 Modular ARM & 96 Probe Head <mark style="background-color:yellow;">**conducted with all the macros successfully in advance.**</mark>

{% hint style="warning" %}
In advance to conduct the teaching for the 96 Probe Head, in the case of needing to install/reinstall the Seegene Launcher in advance, please refer to the Seegene Launcher Installation section -[installation.md](../seegene-launcher/installation.md "mention").
{% endhint %}

### &#x20;       1-2. Summary

Must preemptively conduct the followings before the Teaching.

1. **Record** the <mark style="background-color:yellow;">**existing teaching value.**</mark> (If existing '.lay' file is 'STARlet\_v6.1\_96Head.lay')
2.  **Conduct** the <mark style="background-color:yellow;">**96 Probe Head Teaching**</mark> suitable for the STARMag S96H Kit or N kit.

    \-> Refer to the details for the Teaching Procedure  - [#2-5.-procedure-for-the-teaching](teaching.md#2-5.-procedure-for-the-teaching "mention")



### &#x20;       1-3. 96Head Teaching Layout & Labware

*   **STARMag S96H Kit / STARlet for 96Head (32 or 24 Sample Carrier)**

    &#x20;               ![](<../../../../.gitbook/assets/image (92).png>)

    **-Position No. 1** : Core96\_TipSupport\_HTF\_L\_0001, Core96\_TipSupport\_ST\_L\_0001

    **-Position No. 2, 3, 4, 5, 6, 7, 22, 23**: 1000μL Tip

    **-Position No. 8, 9, 10, 24**: 300μL Tip

    **-Position No. 11, 12, 13, 14, 15**: Buffer\_DWP96\_0001, 0002, 0003, 0004, 0005

    **-Position No. 16**: DWP96\_HHS\_96Head, DWP96\_HHS

    **-Position No. 17**: DWP96\_Magnet\_96Head, DWP96\_Magnet

    **-Position No. 18**: DWP96, Plate\_Biorad\_0001, Plate\_Biorad\_0002, Plate\_BioPlastics\_0001, Plate\_BioPlastics\_0002

    **-Position No. 19, 20**: PCR Reagent Vial

    **-Position No. 21 (32 Sample Carrier - Track 21 to 23)**: 1.5mL Microtube, 2mL Tube, 12 mm Primary Tube

    **-Position No. 21 (24 Sample Carrier - Track 21 to 24)**: 16mm Primary Tube

    **-Position No. 25, 26**: PCR Plate, PCR Tube

    **-Position No. 27**: Waste Chute



*   **STARMag S96H N Kit / STARlet for 96Head (32 or 24 Sample Carrier)**

    &#x20;               ![](<../../../../.gitbook/assets/image (155).png>)

    **-Position No. 1** : Core96\_TipSupport\_HTF\_L\_0001, Core96\_TipSupport\_ST\_L\_0001

    **-Position No. 2, 3, 4, 5, 6, 7, 22, 23**: 1000μL Tip

    **-Position No. 8, 9, 24**: 300μL Tip

    **-Position No. 10, 11, 12, 13, 14, 15**: Buffer\_DWP96\_0001, 0002, 0003, 0004, 0005, 0006

    **-Position No. 16**: DWP96\_HHS\_96Head, DWP96\_HHS

    **-Position No. 17**: DWP96\_Magnet\_96Head, DWP96\_Magnet

    **-Position No. 18**: DWP96, Plate\_Biorad\_0001, Plate\_Biorad\_0002, Plate\_BioPlastics\_0001, Plate\_BioPlastics\_0002

    **-Position No. 19, 20**: PCR Reagent Vial

    **-Position No. 21 (32 Sample Carrier - Track 21 to 23)**: 1.5mL Microtube, 2mL Tube, 12 mm Primary Tube

    **-Position No. 21 (24 Sample Carrier - Track 21 to 24)**: 16mm Primary Tube

    **-Position No. 25, 26**: PCR Plate, PCR Tube

    **-Position No. 27**: Waste Chute

### &#x20;       1-4. Part Information

| No. | Part Number (P/N) | Part Name & Description |
| --- | ----------------- | ----------------------- |
| -   | -                 | -                       |

### &#x20;       **1-5. Procedure for the Teaching**

### &#x20;           A. S96H Kit, STARMag

### &#x20;               A-1. Preparation for the Teaching

1. Install the Hamilton Heater Shaker in position No. 16.
2. Execute the Hamilton Method Editor.
3. Open the 'STARlet\_v6.1\_96Head.lay' file.
4. Disable the 'Load carriers' function.
5.  Prepare the required labware for the Teaching and be ready to put them into the designated position.

    For details about the required labware for each designated position, refer to the section - [#2-3.-96head-teaching-layout-and-labware](teaching.md#2-3.-96head-teaching-layout-and-labware "mention")
6. Place all the carriers on the deck refers to the Layout



### &#x20;               A-2. 96 Probe Head

1. As for the position which needs to adjust for the 96 Probe Head, Position No. 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, and 27 in total.

<details>

<summary><mark style="color:blue;">No. 1 (Core96_TipSupport_HTF_L_0001 &#x26; Core96_TipSupport_ST_L_0001<strong>)</strong></mark></summary>



</details>

<details>

<summary><mark style="color:blue;">No. 2 (1000 <strong>μL Tip)</strong></mark></summary>

1.  Do not place the Tip Plate that 1000 μLTips loaded in position No. 2.

    <figure><img src="../../../../.gitbook/assets/image (283).png" alt=""><figcaption></figcaption></figure>


2. Find the 'htf\_I\_0001' and select it.
3.  Right-click on the selected position. Then, click the 'Adjust Location...'.

    <figure><img src="../../../../.gitbook/assets/image (264).png" alt=""><figcaption></figcaption></figure>


4. 'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'
5.  'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (284).png" alt=""><figcaption></figcaption></figure>


6.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (301).png" alt=""><figcaption></figcaption></figure>


7.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head will move to the No. 2 position automatically and perform the process of mounting the tips.

    <figure><img src="../../../../.gitbook/assets/image (344).png" alt=""><figcaption></figcaption></figure>


8.  Place the Tip Plate that 1000 μLTips loaded in position No. 2.

    Then, move the 96 Probe Head down to the tips nearby.

    <figure><img src="../../../../.gitbook/assets/image (331).png" alt=""><figcaption></figcaption></figure>


9.  Make sure the teaching position on the X and Y Coordinates only.

    The way to confirm the correct position is by matching the 96 Probe Head Stop Disk position with the holes of 1000 μL Tips like both positions on the same vertical line.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (335).png" alt=""><figcaption></figcaption></figure>


10. In advance to save and apply the adjusted position values(X & Y axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
11. After that, to save and apply the adjusted position values(X & Y axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (358).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;">No. 3, 4, 5, 6, 7 (1000 <strong>μL Tip)</strong></mark></summary>

1.  Do not place the Tip Plate that 1000 μLTips loaded in position No. 2.

    <figure><img src="../../../../.gitbook/assets/image (283).png" alt=""><figcaption></figcaption></figure>


2. Place the Tip Plate that 1000 μLTips loaded in position No. 3 (No.4 \~ 7).
3. Find the 'hft\_l\_0002' and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (325).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (274).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head will move to the No. 3 (No.4 \~ 7) position automatically after performing the process of mounting the tips at Position No. 2.

    <figure><img src="../../../../.gitbook/assets/image (361).png" alt=""><figcaption></figcaption></figure>


9.  Then, move the 96 Probe Head down to the tips nearby.

    <figure><img src="../../../../.gitbook/assets/image (268).png" alt=""><figcaption></figcaption></figure>


10. Make sure the teaching position on the X and Y Coordinates only.

    The way to confirm the correct position is by matching the 96 Probe Head Stop Disk position with the holes of 1000 μL Tips like both positions on the same vertical line.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (273).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X & Y axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X & Y Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (349).png" alt=""><figcaption></figcaption></figure>


13. Repeat steps 1 to 12 for No. 4('htf\_l\_0003'), 5('htf\_l\_0004'), 6('htf\_l\_0005'), and 7('htf\_l\_0006') in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (346).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;">No. 8, 9, 10 (300 <strong>μL Tip)</strong></mark></summary>

1.  Do not place the Tip Plate that 1000 μLTips loaded in position No. 2.

    <figure><img src="../../../../.gitbook/assets/image (283).png" alt=""><figcaption></figcaption></figure>


2. Place the Tip Plate that 300 μLTips loaded in position No. 8 (No.9 & 10).
3. Find the 'STF\_L\_0002' and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (342).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (312).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head will move to the No. 8 (No.9 & 10) position automatically after performing the process of mounting the tips at Position No. 2.

    <figure><img src="../../../../.gitbook/assets/image (288).png" alt=""><figcaption></figcaption></figure>


9.  Then, move the 96 Probe Head down to the tips nearby.

    <figure><img src="../../../../.gitbook/assets/image (287).png" alt=""><figcaption></figcaption></figure>


10. Make sure the teaching position on the X and Y Coordinates only.

    The way to confirm the correct position is by matching the 96 Probe Head Stop Disk position with the holes of 300 μL Tips like both positions on the same vertical line.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (278).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X & Y axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X & Y Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (350).png" alt=""><figcaption></figcaption></figure>


13. Repeat steps 1 to 10 for No. 9('STF\_L\_0003') and 10('STF\_L\_0004') in a sequence.

</details>

<details>

<summary><mark style="color:blue;">No. 11, 12, 13, 14, 15 (Buffer_DWP96_0002, 0003, 0004, 0005, 0006<strong>)</strong></mark></summary>

1. Place the Tip Plate that 1000 μLTips loaded in Position No. 2.
2.  Place the 96 Deep Well Plate in  Position No. 11 (No. 12 \~ 15).

    <figure><img src="../../../../.gitbook/assets/image (311).png" alt=""><figcaption></figcaption></figure>


3. Find the 'Buffer\_DWP96\_0002'('Buffer\_DWP96\_0003 \~ 0006') and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (271).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (317).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head(which is mounting the tips in position No. 2) will move to the No. 11 position automatically.

    Then, move the 96 Probe Head down to the 96 Deep Well Plate nearby.

    <figure><img src="../../../../.gitbook/assets/image (333).png" alt=""><figcaption></figcaption></figure>


9.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (314).png" alt=""><figcaption></figcaption></figure>


10. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (343).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X, Y, & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X, Y, & Z Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (332).png" alt=""><figcaption></figcaption></figure>


13. Repeat steps 1 to 12 for No. 12('Buffer\_DWP96\_0003'), 13('Buffer\_DWP96\_0004'), 14('Buffer\_DWP96\_0005'), and 15('Buffer\_DWP96\_0006') in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (269).png" alt=""><figcaption></figcaption></figure>

</details>

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

<summary><mark style="color:blue;">No. 17 (DWP96_Magnet_96Head)</mark></summary>

1. Place the Tip Plate that 1000 μLTips loaded in Position No. 2.
2.  Place the '96 Deep Well Plate' in position No. 17.



    <figure><img src="../../../../.gitbook/assets/image (298).png" alt=""><figcaption></figcaption></figure>


3. Find the 'DWP96\_Magnet\_96Head' and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (265).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (303).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head(which is mounting the tips in position No. 2) will move to the No. 17 position automatically.

    Then, move the 96 Probe Head down to the 96 Deep Well Plate nearby.

    <figure><img src="../../../../.gitbook/assets/image (285).png" alt=""><figcaption></figcaption></figure>


9.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (280).png" alt=""><figcaption></figcaption></figure>


10. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (360).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X, Y, & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X, Y, & Z Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (302).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;">No. 18 (DWP96)</mark></summary>

1. Place the Tip Plate that 1000 μLTips loaded in Position No. 2.
2.  Place the '96 Deep Well Plate' in position No. 18.

    <figure><img src="../../../../.gitbook/assets/image (356).png" alt=""><figcaption></figcaption></figure>


3. Find the 'DWP96' and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (272).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (318).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head(which is mounting the tips in position No. 2) will move to the No. 18 position automatically.

    Then, move the 96 Probe Head down to the 96 Deep Well Plate nearby.

    <figure><img src="../../../../.gitbook/assets/image (290).png" alt=""><figcaption></figcaption></figure>


9.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (266).png" alt=""><figcaption></figcaption></figure>


10. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (329).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X, Y, & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X, Y, & Z Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (355).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;">No. 18 (Plate_Biorad_0001, Plate_Biorad_0002, Plate_BioPlastics_0001, and  Plate_BioPlastics_0002)</mark></summary>

1. Place the Tip Plate that 300 μLTips loaded in Position No. 7.
2.  Place the 'Biorad PCR Plate' ('BioPlastics PCR Plate') in position No. 18.

    <figure><img src="../../../../.gitbook/assets/image (348).png" alt=""><figcaption></figcaption></figure>


3. Find the 'Plate\_Biorad\_0001' ('Plate\_Biorad\_0002', 'Plate\_BioPlastics\_0001', and 'Plate\_BioPlastics\_0002') and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (359).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'MIStar300 μlTip\_96Head ' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (340).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head(which is mounting the tips in position No. 7) will move to the No. 18 position automatically.

    Then, move the 96 Probe Head down to the 96 Deep Well Plate nearby.

    <figure><img src="../../../../.gitbook/assets/image (319).png" alt=""><figcaption></figcaption></figure>


9.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (320).png" alt=""><figcaption></figcaption></figure>


10. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (296).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X, Y, & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X, Y, & Z Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (313).png" alt=""><figcaption></figcaption></figure>


13. Put the adjusted position values(X, Y, and Z Axis) the same into the 'Plate\_Biorad\_0002'.

    <figure><img src="../../../../.gitbook/assets/image (315).png" alt=""><figcaption></figcaption></figure>


14. Repeat steps 1 to 13 for No. 18('Plate\_BioPlastics\_0001' and 'Plate\_BioPlastics\_0002') using the 'BioPlastics PCR Plate' in sequence.

</details>

<details>

<summary><mark style="color:blue;">No. 27 (Waste Chute) / Optional for Tip Eject issue</mark></summary>



</details>

{% hint style="info" %}
As for the way to control the movement of 96 Probe Head and 8 Independent Channels in the 'Move Probe -Key Control', refer to the figure below.

&#x20;                                     ![](<../../../../.gitbook/assets/image (158).png>)
{% endhint %}



### &#x20;               A-3. Independent Channels <a href="#a-2.-teaching-for-independent-channels" id="a-2.-teaching-for-independent-channels"></a>

1. As for the position which needs to adjust for the Independent Channels, the Position No. 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, and 26 in total.

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

<details>

<summary><mark style="color:blue;"><strong>No. 17 (DWP96_Magnet)</strong></mark></summary>

1.  Place the '96 Deep Well Plate' in position No. 17.

    <figure><img src="../../../../.gitbook/assets/image (336).png" alt=""><figcaption></figcaption></figure>


2. Find the 'DWP96\_Magnet' and select it.
3. Right-click on the selected position. Then, click the 'Adjust Location...'.
4.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'.

    <figure><img src="../../../../.gitbook/assets/image (295).png" alt=""><figcaption></figcaption></figure>


5.  'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'

    <figure><img src="../../../../.gitbook/assets/image (277).png" alt=""><figcaption></figcaption></figure>


6.  'Move Probe - Key Control' will be newly popped up.&#x20;

    The independent channel will pick the teaching needle up and move to the No. 17 position automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the '96 Deep Well Plate' nearby.

    <figure><img src="../../../../.gitbook/assets/image (345).png" alt=""><figcaption></figcaption></figure>


7.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (322).png" alt=""><figcaption></figcaption></figure>


8.  If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (270).png" alt=""><figcaption></figcaption></figure>


9. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (330).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 18 (DWP96)</strong></mark></summary>

1.  Place the '96 Deep Well Plate' in position No. 18.

    <figure><img src="../../../../.gitbook/assets/image (363).png" alt=""><figcaption></figcaption></figure>


2. Find the 'DWP96' and select it.
3. Right-click on the selected position. Then, click the 'Adjust Location...'.
4.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'.

    <figure><img src="../../../../.gitbook/assets/image (338).png" alt=""><figcaption></figcaption></figure>


5.  'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'

    <figure><img src="../../../../.gitbook/assets/image (276).png" alt=""><figcaption></figcaption></figure>


6.  'Move Probe - Key Control' will be newly popped up.&#x20;

    The independent channel will pick the teaching needle up and move to the No. 18 position automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the '96 Deep Well Plate' nearby.

    <figure><img src="../../../../.gitbook/assets/image (279).png" alt=""><figcaption></figcaption></figure>


7.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (324).png" alt=""><figcaption></figcaption></figure>


8.  If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (292).png" alt=""><figcaption></figcaption></figure>


9. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (293).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 19 (PCR Reagent Vial)</strong></mark></summary>

1. Find the 'Adapter\_PCR1\_RevA\_0001' ('Adapter\_PCR3\_RevA\_0001') and select it.
2. Right-click on the selected position. Then, click the 'Adjust Location...'.
3.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (321).png" alt=""><figcaption></figcaption></figure>


4. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'
5.  'Move Probe - Key Control' will be newly popped up.

    <figure><img src="../../../../.gitbook/assets/image (357).png" alt=""><figcaption></figcaption></figure>


6.  The independent channel will mount the teaching needle and move to position No. 19 automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.


7.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.


8.  If the teaching position for X and Y coordinates would be finished successfully, place the PCR Reagent 1.5ml EP Tube (PCR Reagent 2ml Tube) in position No. 20.

    Then, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.


9. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (267).png" alt=""><figcaption></figcaption></figure>


11. Repeat steps 1 to 10 for No.19('Adapter\_PCR3\_RevA\_0001'), PCR Reagent 2ml tube.

    <figure><img src="../../../../.gitbook/assets/image (305).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 20 (PCR Reagent Vial)</strong></mark></summary>

1. Find the 'Adapter\_PCR1\_RevA\_0002' ('Adapter\_PCR3\_RevA\_0002') and select it.
2. Right-click on the selected position. Then, click the 'Adjust Location...'.
3.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>


4. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'
5.  'Move Probe - Key Control' will be newly popped up.&#x20;

    <figure><img src="../../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>


6.  The independent channel will mount the teaching needle and move to position No. 20 automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.


7.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.


8.  If the teaching position for X and Y coordinates would be finished successfully, place the PCR Reagent 1.5ml EP Tube (PCR Reagent 2ml Tube) in position No. 20.

    Then, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.


9. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>


11. Repeat steps 1 to 10 for No.20('Adapter\_PCR3\_RevA\_0002'), PCR Reagent 2ml tube.

    <figure><img src="../../../../.gitbook/assets/image (254).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 21 (32 Sample Carrier - '1.5 mL Microtube', '2 mL Tube', '12 mm Primary Tube')</strong></mark></summary>

1.  Find the 'SMP\_CAR\_32\_Vials\_0001' and select it.

    * 32 Sample carrier is loaded on the deck, 3ea in total.
    * 3 tube types are loaded on the 32 Sample carrier.
    *   Please refer to the Labware depending on the 'Location of sample carrier' & 'Tube type'.

        \*1.5mL Microtube: 'SMP\_CAR\_32\_Vials\_0001 \~ 0003'

        \*2mL Tube: 'SMP\_CAR\_2ml\_0001 \~ 0003'

        \*12mm Primary Tube: 'SMP\_CAR\_32\_Copan12mm\_0001 \~ 0003'


2. Right-click on the selected position. Then, click the 'Adjust Location...'.
3.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'


4. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'
5.  'Move Probe - Key Control' will be newly popped up.


6.  The independent channel will mount the teaching needle and move to position No. 21 automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.


7.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.


8.  If the teaching position for X and Y coordinates would be finished successfully, place the 1.5ml EP Tube in the 32 Sample Carrier.

    Then, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.


9. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.


11. Repeat steps 1 to 10 for others.
    * 32 Sample carrier is loaded on the deck, 3ea in total.
    * 3 tube types are loaded on the 32 Sample carrier.
    *   Please refer to the Labware depending on the 'Location of sample carrier' & 'Tube type'.

        \*1.5mL Microtube: 'SMP\_CAR\_32\_Vials\_0001 \~ 0003'

        \*2mL Tube: 'SMP\_CAR\_2ml\_0001 \~ 0003'

        \*12mm Primary Tube: 'SMP\_CAR\_32\_Copan12mm\_0001 \~ 0003'

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 21 (24 Sample Carrier - '16mm Primary Tube')</strong></mark></summary>

1.  Find the 'SMP\_CAR\_24\_16mm\_0001' and select it.

    * 24 Sample carriers are on the deck, 4ea in total.
    *   Please refer to the Labware depending on the 'Location of sample carrier'.

        \*16mm Primary Tube: 'SMP\_CAR\_24\_16mm\_0001 \~ 0004'


2. Right-click on the selected position. Then, click the 'Adjust Location...'.
3.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'


4. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'
5.  'Move Probe - Key Control' will be newly popped up.


6.  The independent channel will mount the teaching needle and move to position No. 21 automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.


7.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.


8.  If the teaching position for X and Y coordinates would be finished successfully, place the 16mm Primary Tube in the 24 Sample Carrier.

    Then, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.


9. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.


11. Repeat steps 1 to 10 for others.
    * 24 Sample carriers are on the deck, 4ea in total.
    *   Please refer to the Labware depending on the 'Location of sample carrier'.

        \*16mm Primary Tube: 'SMP\_CAR\_24\_16mm\_0001 \~ 0004'

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 22, 23 (1000 μL Tip)</strong></mark></summary>

1.  Place the Tip Plate that 1000 μLTips loaded in position No. 22 (No. 23).

    <figure><img src="../../../../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>


2. Find the 'htf\_I\_0007' ('htf\_I\_0008') and select it.
3. Right-click on the selected position. Then, click the 'Adjust Location...'.
4.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>


5. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'
6.  'Move Probe - Key Control' will be newly popped up.&#x20;

    <figure><img src="../../../../.gitbook/assets/image (211).png" alt=""><figcaption></figcaption></figure>


7.  The independent channel will pick the teaching needle up and move to the No. 22 (No. 23) position automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.

    <figure><img src="../../../../.gitbook/assets/image (263).png" alt=""><figcaption></figcaption></figure>
8.  Make sure the teaching position on the X and Y Coordinates only.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (240).png" alt=""><figcaption></figcaption></figure>


9. In advance to save and apply the adjusted position values(X & Y axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X & Y axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>


11. Repeat the steps above for No. 23('hft\_I\_0008') as well.

    <figure><img src="../../../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 24 (300 μL Tip)</strong></mark></summary>

1.  Place the Tip Plate that 300 μLTips loaded in position No. 24.

    <figure><img src="../../../../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>


2. Find the 'STF\_L\_0005' and select it.
3. Right-click on the selected position. Then, click the 'Adjust Location...'.
4.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (251).png" alt=""><figcaption></figcaption></figure>


5. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'.
6.  'Move Probe - Key Control' will be newly popped up.

    <figure><img src="../../../../.gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>


7.  The independent channel will pick the teaching needle up and move to the No. 24 position automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.

    <figure><img src="../../../../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>


8.  Make sure the teaching position on the X and Y Coordinates only.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>


9. In advance to save and apply the adjusted position values(X & Y axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
10. After that, to save and apply the adjusted position values(X & Y axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:blue;"><strong>No. 25, 26 (PCR Plate &#x26; PCR Tube)</strong></mark></summary>

1.  Place the PCR Plate (PCR Tube) in position No. 25 (No. 26).


2. Find the 'PCR\_Plate96\_0001' and select it.
3. Right-click on the selected position. Then, click the 'Adjust Location...'.
4.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>


5. 'Teaching tool' will be newly popped up. Then, select the '1000μL Channel' and click 'OK'.
6.  'Move Probe - Key Control' will be newly popped up.

    <figure><img src="../../../../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>


7.  The independent channel will pick the teaching needle up and move to the No. 25 (No. 26) position automatically.

    Then, move the independent channel(which is mounting the teaching needle) down to the tips nearby.


8.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.


9.  If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    Repeat this step for the PCR tube for getting the value of the Z coordinate as well.


10. In advance to save and apply the adjusted position values(X, Y & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
11. After that, to save and apply the adjusted position values(X, Y & Z axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (209).png" alt=""><figcaption></figcaption></figure>


12. Repeat steps 1 to 11 for No.26('PCR\_Plate96\_0002'), PCR Plate & Tube.

    <figure><img src="../../../../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

</details>

{% hint style="info" %}
As for the way to control the movement of 96 Probe Head and 8 Independent Channels in the 'Move Probe -Key Control', refer to the figure below.

&#x20;                                      ![](<../../../../.gitbook/assets/image (158).png>)
{% endhint %}



### &#x20;           B. S96H N Kit, STARMag&#x20;

### &#x20;               B-1. Preparation for the Teaching

1. Execute the Hamilton Method Editor.
2. Open the 'STARlet\_v6.1\_96Head.lay' file.
3. Disable the 'Load carriers' function.
4.  Prepare the required labware for the Teaching and be ready to put them into the designated position.

    For details about the required labware for each designated position, refer to the section - [#2-3.-96head-teaching-layout-and-labware](teaching.md#2-3.-96head-teaching-layout-and-labware "mention")
5. Place all the carriers on the deck refers to the Layout

### &#x20;               B-2. 96 Probe Head

1.  As for the position which needs to adjust for the 96 Probe Head, Position No. 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, and 27 in total.

    \-> Procedure is the same as STARMag S96H Kit except the Position No. 10.

    \*Please refer to the section - [#a-2.-96-probe-head](teaching.md#a-2.-96-probe-head "mention")
2.  As for position No. 10 in the STARMag S96H N Kit, it is for the Extraction Reagent, not for the 300 μL tip.

    \-> Please refer to the procedure below.

<details>

<summary><mark style="color:blue;">No.</mark> <mark style="color:red;">10, 11, 12, 13, 14, 15 (Buffer_DWP96_0001, 0002, 0003, 0004, 0005, 0006<strong>)</strong></mark></summary>

1. Place the Tip Plate that 1000 μLTips loaded in Position No. 2.
2.  Place the 96 Deep Well Plate in  Position No. 10 (No. 11 \~ 15).

    <figure><img src="../../../../.gitbook/assets/image (310).png" alt=""><figcaption></figcaption></figure>


3. Find the 'Buffer\_DWP96\_0001'('Buffer\_DWP96\_0002 \~ 0006') and select it.
4. Right-click on the selected position. Then, click the 'Adjust Location...'.
5.  'Adjust Labware Position' will be newly popped up. Then, click the 'Move Probe...'

    <figure><img src="../../../../.gitbook/assets/image (351).png" alt=""><figcaption></figcaption></figure>


6. 'Teaching tool' will be newly popped up. Then, select the 'CO-RE 96 Head' and click 'OK'.
7.  'Teaching with CO-RE 96 Head' will be newly popped up. Then, select the 'Check\_Tip' and click 'OK'.

    <figure><img src="../../../../.gitbook/assets/image (326).png" alt=""><figcaption></figcaption></figure>


8.  'Move Probe - Key Control' will be newly popped up. The 96 Probe Head(which is mounting the tips in position No. 2) will move to the No. 10 position automatically.

    Then, move the 96 Probe Head down to the 96 Deep Well Plate nearby.

    <figure><img src="../../../../.gitbook/assets/image (323).png" alt=""><figcaption></figcaption></figure>


9.  Make sure the teaching position for the X and Y Coordinates first.

    For the key controlling, please refer to the Note at the end of this section.

    <figure><img src="../../../../.gitbook/assets/image (291).png" alt=""><figcaption></figcaption></figure>


10. If the teaching position for X and Y coordinates would be finished successfully, make sure the teaching position for the Z Coordinate.

    The teaching position for the Z Coordinates is about 0.2 \~ 0.3mm from reaching the inner bottom.

    <figure><img src="../../../../.gitbook/assets/image (307).png" alt=""><figcaption></figcaption></figure>


11. In advance to save and apply the adjusted position values(X, Y, & Z axis), recommend you to write down the existing values and adjusted values on the Notepad or something whatever you want.
12. After that, to save and apply the adjusted position values(X, Y, & Z Axis), click the 'Ok' button in the 'Move Probe - Key Control' & 'Adjust Labware Position' in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (339).png" alt=""><figcaption></figcaption></figure>


13. Repeat steps 1 to 12 for No. 11('Buffer\_DWP96\_0002'), 12('Buffer\_DWP96\_0003'), 13('Buffer\_DWP96\_0004'), 14('Buffer\_DWP96\_0005'), and 15('Buffer\_DWP96\_0006') in a sequence.

    <figure><img src="../../../../.gitbook/assets/image (337).png" alt=""><figcaption></figcaption></figure>

</details>

{% hint style="info" %}
As for the way to control the movement of 96 Probe Head and 8 Independent Channels in the 'Move Probe -Key Control', refer to the figure below.

&#x20;                                       ![](<../../../../.gitbook/assets/image (158).png>)
{% endhint %}



### &#x20;               B-3. Independent Channels

1.  As for the position which needs to adjust for the Independent Channels, the Position No. 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, and 26 in total.

    \-> Procedure is the same as STARMag S96H Kit.&#x20;

    \*Please refer to the section - [#a-2.-teaching-for-independent-channels](teaching.md#a-2.-teaching-for-independent-channels "mention")

