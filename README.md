# NTRBootHax Pack

A collection of files and GodMode9 scripts to easily install NTRBootHax onto a stock 2DS/3DS console without the need of a computer after initial setup of the microSD card.

### Requirements:
1. A NTRBootHax NDS flash cart
2. A microSD card
3. A #0 crosshead (+) screw driver or screw driver bit
4. A magnet for all models but 2DS
5. A microSD to SD adapter for 2DS and o3DS/XL

### Instructions:

##### Installing B9S:
1. Insert prepared microSD card with packed files into the target 2DS/3DS.
2. Insert NTRBootHax flash cart
3. Place magnet on target device so that the device sleeps without the lid being shut. On 2DS no magnet is needed, only the sleep switch set to the sleep position. Make sure device is powered off.
4. Hold `Start`+`Select`+`X` and then press and hold the power button until the power LED lights up. Let go of all four buttons.
5. GodMode9 should open. Decline making an essential backup. If the device starts up as normal, try again, check the magnet position or check that your NTRBootHax flash cart is properly made.
6. Press `A` on `[0:] SDCARD` and scroll down to `ntr.firm`.
7. Press `A` and select `FIRM image options > Boot FIRM`.
8. Input key combo to start SafeBoot9StrapInstaller.
9. Follow on-screen instructions to install B9S to target device.
10. After a successful install press `Start` to reboot back into GodMode9.

##### Move essential files to target SD:
11. Decline making an essential backup again. Press the Home button and go to `More > Scripts > 1-SD2RAM`
12. Confirm running the script.
13. After script is done, press `R`+`B` to unmount the prepared microSD card.
14. Insert target device's SD card, it will auto-mount in GodMode9.
15. Scroll down and press `A` on `[9:] RAMDRIVE`.
16. Navigate to `gm9 > scripts` and press `A` on `2-RAM2SD`. Confirm running the script.
17. After script is done, press Home and go to `More > Scripts > setup_ctrnand_luma3ds`
18. Confirm running the script.
19. Press `Start` to reboot the console into Luma3DS setup screen.
20. Select desired Luma3DS options and press `Start` to save and boot into the Home Menu.

##### Finalizing setup:
21. Open the Download Play app.
22. Press `L`+`Select`+`Down` to bring up the Rosalina menu.
23. Scroll to `Miscellaneous Options > Switch the hb. title to the current app`.
24. Press `A` to set Download Play as the Homebrew Launcher. Press `B` to exit Rosalina menu.
25. Press the Power button followed by the Home button and reopen Download Play.
26. Scroll down to FBI and open the FBI homebrew.
27. In FBI go to `SD > cia > homebrew`. Press `A` on `<current directory>` and choose `Install and delete all CIAs`.
28. When all CIAs have been installed close the FBI app and restart device.
29. Unwrap all your new Homebrew apps and run Luma Updater to ensure you're up to date.
30. You're done!
