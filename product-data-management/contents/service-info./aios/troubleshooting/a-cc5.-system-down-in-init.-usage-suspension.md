# A-CC5. System Down in Init. (Usage Suspension)

## <mark style="color:blue;">1. Troubleshooting the cases related to the System Down in Init. (Usage Suspension)</mark>

### &#x20;   <mark style="color:blue;">1-1. Troubleshooting List based on the category</mark>

| Category                                               | Page Link                                                                                                                                                                             | Error code |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Usage Suspension - Booting Failed                      | [#1-1-1.-usage-suspension-booting-failed](a-cc5.-system-down-in-init.-usage-suspension.md#1-1-1.-usage-suspension-booting-failed "mention")                                           |            |
| Usage Suspension - Initialization Failed               | [#1-1-2.-usage-suspension-equipment-initialization-failed](a-cc5.-system-down-in-init.-usage-suspension.md#1-1-2.-usage-suspension-equipment-initialization-failed "mention")         |            |
| Usage Suspension - Plate Handler Initialization Failed | [#1-1-3.-usage-suspension-plate-handler-initialization-failed](a-cc5.-system-down-in-init.-usage-suspension.md#1-1-3.-usage-suspension-plate-handler-initialization-failed "mention") |            |



### &#x20;       <mark style="color:blue;">1-1-1. Usage Suspension - Booting Failed</mark>

<details>

<summary>Symptom: Motor Driver Activation Failed</summary>

1. <mark style="color:blue;">**Case (Updated 1st, June 2022)**</mark>
   * **Root Cause Analysis(RCA):**
     * [x] For the Data Corruption in the iolist.xml (Directory -> D:\release\resourse\iolist.xml).
   * **Corrective Measure(CM):**
     *   [x] Restored the iolist.xml using the backed-up files.

         \-> Copy and paste the backed-up iolist.xml into the resource folder to replace the existing iolist.xml.
     * [x] Checked if AIOS is operating normally.

</details>

### &#x20;       <mark style="color:blue;">1-1-2. Usage Suspension - Equipment Initialization Failed</mark>

### &#x20;       <mark style="color:blue;">1-1-3. Usage Suspension - Plate Handler Initialization Failed</mark>
