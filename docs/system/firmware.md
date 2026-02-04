# Firmware Updates

Keep your PGB-1 up to date with the latest features and improvements.

## Checking Your Version

1. Press ++menu++
2. Navigate to **System Info**
3. Press ++a++ to view
4. Note your current firmware version

## Getting Updates

Check for new firmware at:

- [weenoisemakers.com/pgb-1](https://weenoisemakers.com/pgb-1)
- Discord server: [discord.gg/EAmAgsmV5V](https://discord.gg/EAmAgsmV5V)
- Social media: @weenoisemakers

## Standard Update Procedure

### Prerequisites

- Good quality USB cable
- Computer that won't restart during update
- Latest firmware .uf2 file downloaded

!!! danger "Critical"
    Never turn off the PGB-1 or unplug the USB cable during a firmware update. This may leave the device in an invalid state.

### Step 1: Connect and Enter Update Mode

1. Connect PGB-1 to your computer via USB
2. Turn on the device
3. Press ++menu++
4. Navigate to **Update Mode**
5. Press ++a++ to enter
6. Press ++right++ then ++a++ to confirm

The device reboots into update mode. The LEDs display "UP".

### Step 2: Transfer the Firmware

1. A USB drive named **RPI-RP2** appears on your computer
2. Drag and drop the `.uf2` firmware file into this drive
3. Wait for the transfer to complete
4. The PGB-1 automatically reboots when finished

### Step 3: Verify

1. Press ++menu++ → **System Info**
2. Confirm the new version number

## User Data

!!! info "Data Preserved"
    Firmware updates do not erase your projects or samples. Your data remains intact after updating.

## Forced Firmware Update Procedure

If the normal update fails or the device is unresponsive, use this recovery procedure.

### When to Use

- Device won't boot normally
- Standard update procedure fails
- Device is stuck or frozen

### Prerequisites

1. Make sure the device is **off** (power switch to right, cyan LED off)
2. If the device won't turn off, use the [Reset Procedure](#reset-procedure) first
3. Have USB cable and firmware file ready

### Procedure

1. Connect PGB-1 to computer via USB
2. **Hold the Boot button** (rightmost hole on bottom, use a paperclip)
3. While holding Boot, turn on the device (power switch left)
4. Release the Boot button
5. The **RPI-RP2** drive should appear
6. Drag and drop the firmware file
7. Wait for reboot

## Reset Procedure

Use when the device is unresponsive or won't turn off.

1. Locate the Reset button (leftmost hole on the bottom edge)
2. Use a paperclip to press the button
3. The device will restart

!!! warning "Unsaved Changes"
    Changes to the current project will not be saved when resetting.

## Troubleshooting Updates

### RPI-RP2 Drive Doesn't Appear

- Try a different USB cable
- Try a different USB port
- Ensure you're in Update Mode (LEDs show "UP")
- Try the Forced Update procedure

### Update Seems Stuck

- Wait at least 30 seconds
- Do not unplug the cable
- If nothing happens, use Reset then try Forced Update

### Version Doesn't Change After Update

- Verify you used the correct .uf2 file
- Check the file wasn't corrupted during download
- Try downloading the firmware again
- Try the update procedure again

### Device Won't Start After Failed Update

Use the [Forced Firmware Update Procedure](#forced-firmware-update-procedure) to recover.

## Best Practices

1. **Don't interrupt**: Let the update complete fully
2. **Use good cables**: Poor cables cause failed transfers
3. **Check power**: Ensure laptop is plugged in or has good battery
4. **Close applications**: Minimize computer activity during update
5. **Read release notes**: Know what's new before updating
