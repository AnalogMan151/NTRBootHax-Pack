# NTRBootHax Pack

A collection of files and GodMode9 scripts to easily install NTRBootHax onto a stock 2DS/3DS console without the need of a computer after initial setup of the microSD card.

### Requirements:
1. A NTRBootHax NDS flash cart
2. A microSD card
3. A #0 crosshead (+) screw driver or screw driver bit
4. A magnet for all models but 2DS
5. A microSD to SD adapter for 2DS and o3DS/XL

### Setup:
Copy the `pack`, `gm9`, & `boot9strap` folders, and `boot.firm` file to the root of your setup SD card.

### Instructions:

##### Installing B9S:
1. Insert prepared microSD card with packed files into the target 2DS/3DS.
2. Insert NTRBootHax flash cart
3. Place magnet on target device so that the device sleeps without the lid being shut. On 2DS no magnet is needed, only the sleep switch set to the sleep position. Make sure device is powered off.
4. Hold `Start`+`Select`+`X` and then press and hold the power button until the power LED lights up. Let go of all four buttons.
5. GodMode9 should open. Decline making an essential backup. If the device starts up as normal, try again, check the magnet position or check that your NTRBootHax flash cart is properly made.
6. Press the Home button and go to `Scripts... > Setup`

##### Move essential files to target SD and sysNAND:
7. Confirm unlocking SysNAND lvl 3 write permissions by inputting button combo.
8. Swap SD cards when prompted & press `A` to confirm SD card swap.
9. Press `A` to finish and restart console.
10. Select desired Luma3DS options and press `Start` to save and boot into the Home Menu.

##### Finalizing setup:
11. Open the Download Play app.
12. Press `L`+`Select`+`Down` to bring up the Rosalina menu.
13. Scroll to `Miscellaneous Options > Switch the hb. title to the current app`.
14. Press `A` to set Download Play as the Homebrew Launcher. Press `B` three times to exit Rosalina menu.
15. Press the Power button followed by the Home button and reopen Download Play.
16. Scroll down to FBI and open the FBI homebrew.
17. In FBI go to `SD > cia > homebrew`. Press `A` on `<current directory>` and choose `Install and delete all CIAs`.
18. When all CIAs have been installed restart the console.
19. Unwrap all your new Homebrew apps and run Luma Updater to ensure you're up to date.
