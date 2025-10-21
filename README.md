
# usb0_host_sbc_overlay
Overlay for some SBCs with the “Zero” form factor to force the OTG port into **host** mode.

## Copy the overlay → compile it

- If using Armbian (I do):

```bash
sudo armbian-add-overlay {your_overlay}.dts

# reboot for it to take effect
sudo reboot
```
