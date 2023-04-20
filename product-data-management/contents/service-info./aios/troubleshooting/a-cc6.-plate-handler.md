# A-CC6. Plate Handler

## <mark style="color:blue;">1. Troubleshooting the cases related to the Plate Handler</mark>

### &#x20;   <mark style="color:blue;">1-1. Troubleshooting List based on the category</mark>

| Category                           | Page Link                                                                                                                   | Error code                                     |
| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| Elevator (X) Error                 | [#1-1-1.-elevator-x-error](a-cc6.-plate-handler.md#1-1-1.-elevator-x-error "mention")                                       | 1105, 1112, 1119. 1126, 1133, 1140, 1147, 1154 |
| Elevator (Z1) Error                | [#1-1-2.-elevator-z1-error](a-cc6.-plate-handler.md#1-1-2.-elevator-z1-error "mention")                                     | 1103, 1110, 1117, 1124, 1132, 1138, 1145, 1152 |
| Elevator (Z2) Error                | [#1-1-3.-elevator-z2-error](a-cc6.-plate-handler.md#1-1-3.-elevator-z2-error "mention")                                     | 1104, 1111, 1118, 1125, 1132, 1139, 1146, 1153 |
| Gripper (X) Error                  | [#1-1-4.-gripper-x-error](a-cc6.-plate-handler.md#1-1-4.-gripper-x-error "mention")                                         | 1100, 1107, 1114, 1121, 1128, 1135, 1142, 1149 |
| Gripper (Y) Error                  | [#1-1-5.-gripper-y-error](a-cc6.-plate-handler.md#1-1-5.-gripper-y-error "mention")                                         | 1101, 1108, 1115, 1122, 1129, 1136, 1143, 1150 |
| Gripper (Z) Error                  | [#1-1-6.-gripper-z-error](a-cc6.-plate-handler.md#1-1-6.-gripper-z-error "mention")                                         | 1102, 1109, 1116, 1123, 1130, 1137, 1144, 1151 |
| Gripper (T) Error                  | [#1-1-7.-gripper-t-error](a-cc6.-plate-handler.md#1-1-7.-gripper-t-error "mention")                                         | 1106, 1113, 1120, 1127, 1134, 1141, 1148, 1155 |
| Gripper (Open) Error               | [#1-1-8.-gripper-open-error](a-cc6.-plate-handler.md#1-1-8.-gripper-open-error "mention")                                   | 1156                                           |
| Gripper (Close) Error              | [#1-1-9.-gripper-close-error](a-cc6.-plate-handler.md#1-1-9.-gripper-close-error "mention")                                 | 1157                                           |
| Gripper Home Sensor Position Error | [#1-1-10.-gripper-home-sensor-position-error](a-cc6.-plate-handler.md#1-1-10.-gripper-home-sensor-position-error "mention") | 1158                                           |



### &#x20;       <mark style="color:blue;">1-1-1. Elevator (X) Error</mark>

<details>

<summary>Symptom: Occurrence of an error in the Plate Handler Initialization</summary>

1.  <mark style="color:blue;">**Case (Updated 27th, May 2022)**</mark>

    * **Root Cause Analysis(RCA):**&#x20;
      * [x] The cables shown below which were misaligned interfered with the movement of the Plate Holder on the X-Axis.

    &#x20;     ![](<../../../../../.gitbook/assets/image (11).png>)

    *   **Corrective Measure(CM):**&#x20;

        * [x] Re-route the cables. Then, properly arrange and tie up them.
        * [x] Check the movement of the Plate Holder on the X-Axis manually. Then, by software as well.

        ![](<../../../../../.gitbook/assets/image (61).png>)

</details>

<details>

<summary>Symptom: Occurrence of an error on the step that plate transferring from STARlet to Plate Holder</summary>

1.  <mark style="color:blue;">**Case (Updated 19th, August  2022)**</mark>

    *   **Root Cause Analysis(RCA):**

        * [x] The unknown tip which seemed already to be used as being on Elevator X Assy shown below. It interfered with the movement of the Plate Holder on the X-Axis.

        ![](<../../../../../.gitbook/assets/image (19).png>)
    * **Corrective Measure(CM):**&#x20;
      * [x] Check if there would be something obstacles to interfere with the movement of the Plate Holder on the X-Axis. Then, try to remove them.
      * [x] Check the movement of the Plate Holder on the X-Axis manually. Then, by software as well.
    *   **Reference:**

        \-> You would be wondering as "Why wasn't AIOS able to recognize the interference during initialization?" and "What about the Initialization order?".

        Refer to the details below.



    &#x20;                 <mark style="color:orange;"></mark><mark style="color:orange;">**\* Initialization Order:**</mark>&#x20;

    &#x20;                  Elevator X-Axis -> Elevator Z1-Axis -> Elevator Z2-Axis -> Gripper Z-Axis&#x20;

&#x20;                        \-> Gripper Theta-Axis -> Gripper Y-Axis -> Gripper X-Axis

&#x20;                       <mark style="color:orange;">**\* Initialization Movement Range on the Elevator X-Axis:**</mark>

&#x20;                             During the initialization movement, all the axis take small movement&#x20;

&#x20;                        going forward then back to home positions. ‘Successful initialization’

&#x20;                        means, all the axis motors & home sensors re possibly OK.

</details>

### &#x20;       <mark style="color:blue;">1-1-2. Elevator (Z1) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-3. Elevator (Z2) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-4. Gripper (X) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-5. Gripper (Y) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-6. Gripper (Z) Error</mark>

<details>

<summary>Symptom: Occurrence of an error on the step that plate transferring to &#x26; dropping down from Plate Holder to Sealer</summary>

1. <mark style="color:blue;">**Case (Updated 17th, June 2022)**</mark>
   *   **Root Cause Analysis(RCA):**

       * [x] Servo Motor was presumed to be overloaded by teaching values of the Loading Sealer(Y & Z-Axis) those were not met with actual placing plate location on the Sealer.

       ![](<../../../../../.gitbook/assets/image (107).png>)![](<../../../../../.gitbook/assets/image (56).png>)
   * **Corrective Measure(CM):**
     * [x] Conduct the adjustment for the teaching values of the Loading Sealer(Y & Z-Axis)
     * [x] Conduct the Manual Run & Dry Run Test to check if the issue is gone
   *   **Reference:**

       \-> Need to reboot the AIOS to make it the activation for the Servo Driver on the occurrence of the Gripper (Z) Error

</details>

### &#x20;       <mark style="color:blue;">1-1-7. Gripper (T) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-8. Gripper (Open) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-9. Gripper (Close) Error</mark>

### &#x20;       <mark style="color:blue;">1-1-10. Gripper Home Sensor Position Error</mark>

