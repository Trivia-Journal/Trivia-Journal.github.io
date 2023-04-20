# A-CC14. SAHS in AIOS

## <mark style="color:blue;">1. Troubleshooting the cases related to the SAHS in AIOS</mark>

### &#x20;   <mark style="color:blue;">1-1. Troubleshooting List based on the category</mark>

| Category                               | Page Link                                                                                                                           | Error code |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Plate Presence                         | [#1-1-1.-plate-presence](a-cc14.-sahs-in-aios.md#1-1-1.-plate-presence "mention")                                                   | 1618       |
| Sealing Failed                         | [#1-1-2.-sealing-failed](a-cc14.-sahs-in-aios.md#1-1-2.-sealing-failed "mention")                                                   | 1700       |
| FAN Error                              | [#1-1-3.-fan-error](a-cc14.-sahs-in-aios.md#1-1-3.-fan-error "mention")                                                             | 1701       |
| Sensor Error                           | [#1-1-4.-sensor-error](a-cc14.-sahs-in-aios.md#1-1-4.-sensor-error "mention")                                                       | 1702       |
| Motor Error                            | [#1-1-5.-motor-error](a-cc14.-sahs-in-aios.md#1-1-5.-motor-error "mention")                                                         | 1703       |
| Paper box is full                      | [#1-1-6.-paper-box-is-full](a-cc14.-sahs-in-aios.md#1-1-6.-paper-box-is-full "mention")                                             | 1704       |
| Film tray not deteccted                | [#1-1-7.-film-tray-not-detected](a-cc14.-sahs-in-aios.md#1-1-7.-film-tray-not-detected "mention")                                   | 1705       |
| Film tray is empty                     | [#1-1-8.-film-tray-is-empty](a-cc14.-sahs-in-aios.md#1-1-8.-film-tray-is-empty "mention")                                           | 1706       |
| Instrument clearance required          | [#1-1-9.-instrument-clearance-required](a-cc14.-sahs-in-aios.md#1-1-9.-instrument-clearance-required "mention")                     | 1707       |
| Abnormal condition of sealing the film | [#1-1-10.-abnormal-condition-of-sealing-the-film](a-cc14.-sahs-in-aios.md#1-1-10.-abnormal-condition-of-sealing-the-film "mention") |            |
| Device Error                           | [#1-1-11.-device-error](a-cc14.-sahs-in-aios.md#1-1-11.-device-error "mention")                                                     | 1300       |



### &#x20;       <mark style="color:blue;">1-1-1. Plate Presence</mark>

<details>

<summary>Symptom: Occurrence of a Plate Presence error even though no plate on the 96 Plate Bed</summary>

1.  <mark style="color:blue;">**Case (Updated 13th, June 2022)**</mark>

    *   **Root Cause Analysis(RCA):**

        * [x] The Sensing Sensitivity of the Plate Presence Sensor(CX-419) was roughly presumed to be high rather than standard.

        ![](<../../../../../.gitbook/assets/image (34).png>)![](<../../../../../.gitbook/assets/image (122).png>)
    * **Corrective Measure(CM):**
      * [x] Adjusted the Sensing Sensitivity of the Plate Presence Sensor(CX-491) from the 'Dark' level to the 'Light' level by rotating the knob of the variable resistor(VR) type.

    &#x20;     ![](<../../../../../.gitbook/assets/image (22).png>)![](<../../../../../.gitbook/assets/image (59).png>)

</details>

### &#x20;       <mark style="color:blue;">1-1-2. Sealing Failed</mark>

<details>

<summary>Symptom: Occurrence of a Sealing Failed error</summary>

1.  <mark style="color:blue;">**Case (Updated 15th, June 2022)**</mark>

    *   **Root Cause Analysis(RCA):**&#x20;

        * [x] Untiered condition of the film placed into the Film Tray.

        &#x20;                     ![](<../../../../../.gitbook/assets/image (98).png>)
    * **Corrective Measure(CM):**
      * [x] Placed all the film back into the Film Tray correctly referring to the guide in the Manual.
      * [x] Conducted the sealing several times to check if the issue was gone.
    *   **Reference:**

        \-> If there would be a partial remainder of the film on the Heater Plate,&#x20;

        &#x20;   conduct the sealing several times using the new films until all remainders&#x20;

        &#x20;   are removed.

        &#x20;                     ![](<../../../../../.gitbook/assets/image (159).png>)



    &#x20;     \-> Refer to the abnormal sealing condition cases below(that might be been&#x20;

    &#x20;         by processing the sealing step with an uncertain abnormal condition)

    &#x20;                             ![](<../../../../../.gitbook/assets/image (30).png>)
2. <mark style="color:blue;">**Case (Updated 30th, June 2022)**</mark>
   *   **Root Cause Analysis(RCA):**

       * [x] Presumed that a partial film remainder(that might be been by processing the sealing step with an uncertain abnormal condition) on the Heater Plate was involved with the Sealing failed error.

       ![](<../../../../../.gitbook/assets/image (98).png>)![](<../../../../../.gitbook/assets/image (20).png>)
   * **Corrective Measure(CM):**
     *   [x] Conducted the sealing several times using the new films until all remainders are removed.

         &#x20;               ![](<../../../../../.gitbook/assets/image (159).png>)
     * [x] Conducted the sealing several times to check if the issue was gone.

</details>

### &#x20;       <mark style="color:blue;">1-1-3. FAN Error</mark>

### &#x20;       <mark style="color:blue;">1-1-4. Sensor Error</mark>

### &#x20;       <mark style="color:blue;">1-1-5. Motor Error</mark>

### &#x20;       <mark style="color:blue;">1-1-6. Paper box is full</mark>

### &#x20;       <mark style="color:blue;">1-1-7. Film tray not detected</mark>

### &#x20;       <mark style="color:blue;">1-1-8. Film tray is empty</mark>

### &#x20;       <mark style="color:blue;">1-1-9. Instrument clearance required</mark>

### &#x20;       <mark style="color:blue;">1-1-10. Abnormal condition of sealing the film</mark>

### &#x20;       <mark style="color:blue;">1-1-11. Device Error</mark>

<details>

<summary>Symptom: SAHS condition wasn't being 'Ready' with 'Device Error' warning on the panel</summary>

1.  <mark style="color:blue;">**Case (Updated 8th, June 2022)**</mark>

    *   **Root Cause Analysis(RCA):**

        * [x] In the step that SAHS condition should have been as 'Ready', the sensors(which are set as Emitting & Detecting) were warning the sensing condition by an unknown paper attached to the detect sensor hole.

        ![](<../../../../../.gitbook/assets/image (138).png>)![](<../../../../../.gitbook/assets/image (36).png>)
    *   **Corrective Measure(CM):**

        * [x] Took the unknown paper off on the detect sensor location.




2.  <mark style="color:blue;">**Case (Updated 14th, June 2022)**</mark>

    *   **Root Cause Analysis(RCA):**

        * [ ] Unknown: Need to check and analyze
        * [x] Presumption:

        &#x20;      1\) An unknown film(that might be been by processing the sealing step with&#x20;

    &#x20;                an uncertain abnormal condition) was located around the heater.

    &#x20;            2\) The Temp. sensor attached to the FPCB HEATER would be taken off.

    &#x20;                \-> This issue often occurred by the temperature sensor was soldering by

    &#x20;                     200 degrees Celcius in the First Article.

    &#x20;                \-> As a result of analyzing it by SAHS Manufacturer, it was a defective&#x20;

    &#x20;                     soldering case and improved.

    ![](<../../../../../.gitbook/assets/image (35).png>)![](<../../../../../.gitbook/assets/image (55).png>)

    * **Corrective Measure(CM):**
      * [x] Remove the unknown film mentioned above.
      * [x] Replace the FPCB HEATER with a new one.

    ![](<../../../../../.gitbook/assets/image (27).png>)![](<../../../../../.gitbook/assets/image (65).png>)

</details>
