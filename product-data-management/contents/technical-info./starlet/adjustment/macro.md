# Macro

## <mark style="color:blue;">1. Adjust\_Arm\_Z\_Using\_PIP</mark>

### &#x20;   1-1. Prerequisite & Summary

* This is to ensure the X-Arm is aligned parallel to the Deck surface.
* The adjustment is of a mechanical nature.
* The 'Adjust\_Arm\_Z\_Using\_PIP.mcr' macro program provides the measurement values and values for the corrective actions for the Z-Position of the Front Guide Bar.

### &#x20;   1-2. Procedure

1. Execute the 'STAR Service' and click the 'Adjust\_Arm\_Z\_Using\_PIP' button.
2. Click the 'Start(F5)' to conduct the macro.
3. Put the calibration tool(PN: 173960) on the No. 5 slot. Then, enter the '5' into the blank and click 'OK'.
4. If the result is passed, click 'No' (Correction value is within ±5) and conduct the macro, 'Check\_Arm\_X\_Diff'.
5.  If the result is failed, in advance to click 'Yes', the Adjustment for the Front Guide Bar must be performed.

    5-1. Slightly loosen all 5 fixing screws.

    5-2. In accordance with the adjustment values, move the Front Guide Bar up or down by turning the Adjustment Screw.

    &#x20;   \* Make very small movements (e.g. 1/8 turn) with the Adjustment Screw, then tighten the Fixing Screws.&#x20;

    5-3. After adjustment, click 'Yes'.
6. If the result is passed, click 'No' (Correction value is within ±5) and conduct the macro, 'Check\_Arm\_X\_Diff'.

{% hint style="warning" %}
Re-try the adjustment until the correction value is within ±5.
{% endhint %}



## <mark style="color:blue;">2. Check\_Arm\_X\_Diff\_PIP</mark>

### &#x20;   2-1. Prerequisite & Summary

* The X-Arm can be adjusted using the Channel Calibration Tool(PN: 173952) as a reference and the 'Check\_Arm\_X\_Diff.mcr' macro program from the 'STAR Service'.
* The 'Check\_Arm\_X\_Diff.mcr' macro program only provides the measurement values and helps you to align the X-Arm.
* The X-Arm is aligned when the rear and front of the X-Arm are on the same X Coordinate(s).

### &#x20;   2-2. Procedure

1. Execute the 'STAR Service' and click the 'Check\_Arm\_X\_Diff' button.
2. Put the calibration tool(PN: 173960) on the No. 5 slot. Then, enter the '5' into the blank and click 'OK'.
3. Click the 'Start(F5)' to conduct the macro.
4. Check if something interrupts the movement of the X-Arm on the X Coordinate(s) and clear it before proceeding with it. Then, click 'Yes'.
5. If the result is passed, click 'No' (Correction value is within ±10) and conduct the macro, 'Adjust\_PIP\_Manual'.
6.  If the result is failed, in advance to click 'Yes', the Adjustment for the X-Arm must be performed.

    6-1. To remove the X-Arm cover, loosen the secured 3 screws. Then, remove the X-Arm cover.

    6-2. Put two X-Arm Alignment Tools on both sides of the X-Arm.

    6-3. Gently, fix the tools with the Adjustment Screws.

    6-4. Loosen the X-Arm Fixing Screws (8ea, 4 are in front and the other are in rear).

    6-5. Seeing as the back of the X-Arm is connected to the Linear Slides as pivot points in the Z-Axis, the X-Arm may only pivot around the Z-Axis.

    &#x20;   \* X Correction value > 0 (Change to -)

    &#x20;       \- Adjustment Screw of the Left Tool -> Turn Clockwise

    &#x20;       \- Adjustment Screw of the Right Tool -> Turn Counter-Clockwise

    &#x20;   \*\* X Correction value < 0 (Change to +)

    &#x20;       \- Adjustment Screw of the Left Tool -> Turn Counter-Clockwise

    &#x20;       \- Adjustment Screw of the Right Tool -> Turn Clockwise

    6-6. After alignment, remove the X-Arm alignment tools from the rail to conduct the macro again.
7. If the result is passed, click 'No' (Correction value is within ±10) and conduct the macro, 'Adjust\_PIP\_Manual'.



## <mark style="color:blue;">3. Adjust\_PIP\_Manual</mark>

### &#x20;   3-1. Prerequisite & Summary

* Now that X-Arm with its Channels can be adjusted using the Channel Positioning Tool(PN: 182960) and the 'Adjust\_PIP\_Manual.mcr' macro program from the 'STAR Service'.
* The 'Adjust\_PIP\_Manual.mcr' macro program only provides the measurements and helps you to align the channels on the X-Arm.
* Never TOUCH the electrical part directly with bare hands. Channels can get damaged.

### &#x20;   3-2. Procedure

1. Execute the 'STAR Service' and click the 'Adjust\_PIP\_Manual' button.
2. Put the calibration tool(PN: 173960) on the No. 5 slot. Then, enter the '5' into the blank and click 'OK'.
3.  Click the 'Start(F5)' to conduct the macro.

    &#x20;\* For your information, all the existing adjustment values stored in the board will be set to default.

    \-> That means you have to select the 'Yes' for the question - "Would you like to set all adjustment values to default?" shown.
4. If the result is passed, click 'No' and conduct the macro, 'Adjust\_PIP'.
5.  If the result is failed, in advance to click 'Yes', the Adjustment for the misaligned channel(s)  must be performed.

    5-1. Type 'Channel number to be adjusted' and click 'OK'.

    &#x20;\* The program will recommend a channel to be adjusted automatically.

    5-2. The channel that needs adjustment will be separated automatically.

    5-3. Check the 'Channel Alignment Flowchart' and adjust the tilt for both coordinates(X & Y-Axis) and the Deviation for the X-Axis.

    &#x20;   **a.** [**Y-Tilt. Alignment**](macro.md#3-3.-y-tilt-alignment)

    &#x20;   **b.** [**X-Tilt. Alignment**](macro.md#3-4.-x-tilt-alignment)

    &#x20;   **c.** [**X-Deviation Alignment**](macro.md#3-5.-x-deviation-alignment)

    5-4. After alignment, remove the X-Tilt & Deviation alignment tools to conduct the macro again.
6. If the result is passed, click 'No' and conduct the macro, 'Adjust\_PIP'.

### &#x20;   3-3. Y-Tilt, Alignment

### &#x20;       3-3-1. Mechanism

*   If the Tilt in Y > 0 -> Corrective action: Pivot Counter Clockwise

    \*View from the left side of the Instrument
*   If the Tilt in Y < 0 -> Corrective action: Pivot Clockwise

    \*View from the left side of the instrument

### &#x20;       3-3-2. Procedure

1. Loosen the secured screws slightly, 4ea in total with the Y-Linear Guide Block.
2. Adjust the Y-TilT with the headless screws, 2ea in total.
   *   If the Tilt in Y > 0&#x20;

       \-> Left Headless screw: Turn the Clockwise.

       \-> Right Headless screw: Turn the Counter Clockwise
   *   If the Tilt in Y < 0

       \-> Left Headless screw: Turn the Counter Clockwise.

       \-> Right Headless screw: Turn the Clockwise
3. After then, re-tighten all the secured screws, 4ea in total with the Y-Linear Guide Block.
4. Repeat those steps above until the Tilt in Y is within tolerance.



### &#x20;   3-4. X-Tilt, Alignment

### &#x20;       3-4-1. Mechanism

*   If the Tilt in X > 0 -> Corrective action: Pivot Counter Clockwise

    \*View from the front of the instrument
*   If the Tilt in X < 0 -> Corrective action: Pivot Clockwise

    \*View from the front of the Instrument

### &#x20;       3-4-2. Procedure

1. Place the Channel Positioning Tool(PN: 182950) onto the Y-Linear Guides of the X-Arm.
2. Loosen the secured screws slightly, 2ea in total.
3. Release the Knurled screw and tighten or release 2 adjustment screws to adjust X-Tilt. After that, re-tighten the Knurled screw.
4. Repeat those steps above until the Tilt in X is within tolerance.

### &#x20;   3-5. X-Deviation Alignment

### &#x20;       3-5-1. Mechanism

*   If the Deviation of X-Position > 0 -> Corrective action: Shift Left

    \*View from the front of the instrument
*   If the Deviation of X-Position < 0 -> Corrective action: Shift Right

    \*View from the front of the Instrument

### &#x20;       3-5-2. Procedure

1. Place the Channel Positioning Tool(PN: 182950) onto the Y-Linear Guides of the X-Arm.
2. Loosen the secured screws slightly, 2ea in total.
3. Release the Knurled screw on the other side of the adjustment.
4. Tighten the adjustment screw to adjust X-Deviation.
5. After that, re-tighten the Knurled screw on the other side of the adjustment.
6. Repeat those steps above until the Deviation in X is within tolerance.

## <mark style="color:blue;">4. Adjust\_PIP</mark>

### &#x20;   4-1. Prerequisite & Summary

* Calibrates the X-Arm in the X-Axis and its Pipetting Channels in the Y-and Z-Axes, Dosing Drive hysteresis calibration, ADC parameter calibration, and Z-Drive parameter for touch-off.
* Uses the Channel Calibration Tool (PN 173960)

### &#x20;   4-2. Procedure

1. Execute the 'STAR Service' and click the 'Adjust\_PIP' button.
2.  Click the 'Start(F5)' to conduct the macro.

    2-1. Click 'No' (But if the Pipetting Channel is replaced, click 'Yes').

    2-2. Click 'No' (But if the Pipetting Head is replaced, click 'Yes').

    2-3. Click 'Yes' to perform the default adjustment procedure.
3. Enter '5' into the blank to choose a reachable position for adjustment on the left side. Then, click 'Ok'.
4. Enter '22' into the blank to choose a reachable position for adjustment on the right side. Then, click 'Ok'.
5. Put the calibration tool(PN: 173960) on the No. 22 slot. Then, click 'OK'.
6. Put the calibration tool(PN: 173960) on the No. 5 slot. Then, click 'OK'.

## <mark style="color:blue;">5. Check\_PIP</mark>

### &#x20;   5-1. Prerequisite & Summary

* Checks all calibration values of the X-Arm (X-Offset) and Channels (Y- and Z-Offsets)
* Uses the Channel Calibration Tool (PN 173960)

### &#x20;   5-2. Procedure

1. Execute the 'STAR Service' and click the 'Check\_PIP' button.
2. Click the 'Start(F5)' to conduct the macro.
3. Enter '5' into the blank to choose a reachable position for adjustment on the left side. Then, click 'Ok'.
4. Enter '22' into the blank to choose a reachable position for adjustment on the right side. Then, click 'Ok'.
5. Put the calibration tool(PN: 173960) on the No. 22 slot. Then, click 'OK'.
6. Put the calibration tool(PN: 173960) on the No. 5 slot. Then, click 'OK'.
7. If the result is passed, click 'Yes'. If not, try again the step from [**'Adjust\_PIP\_Manual'**](macro.md#3.-adjust\_pip\_manual).



## <mark style="color:blue;">6. Adjust\_Autoload</mark>

### &#x20;   6-1. Prerequisite & Summary

*   In advance, the 30T Loading Tray should be installed with aligning the leveling.

    \-> Make sure the leveling by adjusting the adjustment screws.

### &#x20;   6-2. Procedure for the Cog Wheel

1. Execute the 'STAR Service' and click the 'Adjust\_Autoload' button.
2. Click the 'Start(F5)' to conduct the macro.
3. To check the Part number & Revision # of the Autoload, remove the Protect Ribbon to see the inside. Then, enter them into the blank and click 'OK'.
4. Click 'Yes' to check the LED on the front door.
5. Click 'No' to skip the 'Setting up the barcode scanner parameters'.
6. Enter '1' into the blank to choose a slot position close to where the Deck is mounted. Then, click 'Ok'.
7. Enter one of the numbers(0 and 1) suitable for the type of adjustment tool(PN: 173981 or 182130) referring to the guide shown&#x20;
8. Enter one of the numbers(0 and 1) suitable for the type of adjustment tool(PN: 173980 or 185280) referring to the guide shown&#x20;
9. Click 'Yes' to start the adjustment of all autoload drives. Then, the Autoload system will be initialized automatically.
10. Move the Stop Hook Release mechanism all the way down! Then, click 'Ok'

    \*Note: X-Drive is off, you may move the Autoload manually to a convenient X-Position.
11. **To determine the Z-Drvie friction,** Position the 'Cog Wheel' to the middle of slot position 1 by moving the Autoload carefully in X. Then, click 'Ok'.

    \*ATTENTION!: The Stops Hooks get damaged if the Cog Wheel is not centered in the slot position!
12. **To determine the X-Offset,** place the adjustment tool(PN: 173981 or 182130) for the 'Cog Wheel' to slot position 1(from the back forwards) and click 'Ok'. After then, remove the adjustment tool and click 'Ok'.

    \*Ensure the 'Cog Wheel' runs in the adjustment tool groove!
13. **To determine the Y-Position for the loading carrier,** place the adjustment tool(PN: 173981 or 182130) for the 'Cog Wheel' to slot position 1(from the back forwards) and click 'Ok'. After then, remove the adjustment tool and click 'Ok'.
14. To access the Adjustment screws, choose a Slot Position between 5 and 28(for the Adjustment of the Stop Hook Release). Enter '5' into the blank and click 'Ok'.
15. Push the adjustment tool(PN: 173981 or 182130) for the 'Cog Wheel' down onto the Deck and Insertion Guides(Cograil facing down). If both criteria are OK click 'Yes', else click 'No' to continue with the adjustment.

    15-1. First, check for a gap between the Stop Hook and the Carrier(about 1mm)!

    15-2. Second, gently push down the Stop Hook and check for play(there must be a little play).

    \*Repeat this step - adjust the Stop Hook Release mechanism - until it is passed.
16. If the adjustment is passed, remove the adjustment tool(PN: 173981 or 182130) and keep following the guides shown ongoing for the Barcode system.

### &#x20;   6-3. Procedure for the Barcode system

1.  **To determine the Minimal Current of the Y-Drive,** place the Sensor Adjustment Carrier(PN: 173980 or 185280) on the loading tray slot position 1. Then, click 'OK'.

    \*If you see the warning message - "Shall the Y-Adjustment be repeated? by that Sensors Adjustment Carrier is probably worn out" -, click 'Yes' to repeat it.
2. **To determine the Y-Position for the unloading carrier,** keep the carrier pushed to the back.
3.  Click 'No'

    \*If the Barcode Scanner and Tube-Sensor need adjustment, click 'Yes' to start it.
4. Place the Sensor Adjustment Carrier(PN: 173980 or 185280) on the loading tray slot position 1. Then, click 'OK'.
5. If the Laser Adjustment Block and Vertical Target are inserted, remove them from the Carrier. Then, click 'OK'
6. Make sure that the Sensors Adjustment Carrier is pushed towards the Stop Hook.
7. If all barcodes are read successfully, see the message and click 'OK'.
8. Remove the Sensor Adjustment Carrier(PN: 173980 or 185280) and re-assemble the Ribbon. Then, click 'Ok'.

## <mark style="color:blue;">7. Check\_Autoload</mark>

### &#x20;   7-1. Prerequisite & Summary

*   In advance, the 30T Loading Tray should be installed with aligning the leveling.

    \-> Make sure the leveling by adjusting the adjustment screws.

### &#x20;   7-2. Procedure

1. Execute the 'STAR Service' and click the 'Check\_Autoload' button.
2. Click the 'Start(F5)' to conduct the macro.
3.  Place all Carriers to be tested anywhere on the loading trays.

    \*Slot positions '1', '15', and '30' are recommended.

    \*Push them to the Stop Hook
4.  Remove all Carriers from the loading trays.

    \*All Carriers must be back on the loading trays.
5. To start the Check/Adjustment of the Barcode Scanner and Tube-Sensor, click 'Yes'.
6. Enter one of the numbers(0 and 1) suitable for the type of adjustment tool(PN: 173980 or 185280) referring to the guide shown.
7. Place the Autoload Sensors Adjustment Tool with the Laser Adjustment Block onto the loading tray at the selected position, 01 - enter the '01' into the blank. Then, click 'OK'.
8.  Check if the red laser beam is adjusted within the two vertical adjustment lines.

    8-1. If needed, loosen the secured screws, 3ea in total to disassemble the outer cover.

    8-2. Then, adjust the vertical laser beam of the Barcode Scanner.
9.  Check if the cup sensor spot is adjusted to the intersection of the vertical and horizontal target lines.

    9-1. If the spot is in the correct position, click 'OK'. But if not, please follow the step ongoing below.

    9-2. Adjust the adjustment screws to adjust the cup sensor spot of the Barcode Scanner.
10. Check the sensitivity of the cup sensor.

    \*Be sure that the reflector is properly set.
11. Check if the red laser beam is adjusted to the horizontal target.

    11-1. If the laser is within two horizontal lines, click 'OK'. But if not, please follow the step ongoing below.

    11-2. Adjust the horizontal laser beam of the Barcode Scanner by tightening or loosening the headless screw.
12. Click 'No' for the message - "Would you like to repeat the scanner check?" -.
13. Remove the Laser Adjustment Block and Vertical Target Insert from the Carrier. Then, click 'OK'.
14. Make sure that the Sensors Adjustment Carrier is pushed towards the stop hook. Then, click 'OK' to test the recognition of the barcode.
15. If the result is passed, remove all tools and end the STAR Service Application.

    \*But if the result if failed, try again the 'Adjust\_Autoload.mcr' and 'Check\_Autoload.mcr' macros in a sequence.
