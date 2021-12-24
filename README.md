# Forkable config repository for the tom60 PCB
How to use:

Instructions with images below.

1. Fork this repository using the "fork" button in the top right of this web page.
2. Head over to your fork of this repository.
3. Do desired keymap changes in config/tom60.keymap in accordance with https://zmk.dev/docs/codes  
4. Commit changes in the bottom of the web page.
5. Head over to the "Actions tab".
  * Wait for the build to finish.
6. Click on the build job and download the resulting firmware.zip under "artifacts".
7. Extract the uf2-file from the zip.
8. Reset the keyboard either by double pressing the reset button underneath the PCB or by hitting &boot (default MO(3) + B).
9. Copy the uf2-file to the keyboard.

## With images:

1. Fork this repository using the "fork" button in the top right of this web page.
![Fork](img/forkrepo.png)
2. Head over to your fork of this repository.
3. Do desired keymap changes in config/tom60.keymap in accordance with https://zmk.dev/docs/codes  
![Edit the keymap using the edit button here](img/editkeymap.png)
4. Commit changes in the bottom of the web page.
![Remember to commit in order to save and trigger a new firmware build](img/Commitchanges.png)
5. Head over to the "Actions tab".
![Actions tab is located here](img/actionstab.png)
  * Wait for the build to finish.
  ![Wait for the build job to complete. Feel free to click the build job now as well](img/waitforbuild.png)
6. Click on the build job and download the resulting firmware.zip under "artifacts".
![No images from this point on. Good luck soldier](img/firmware.png)
7. Extract the uf2-file from the zip.
8. Reset the keyboard either by double pressing the reset button underneath the PCB or by hitting &boot (default MO(3) + B).
9. Copy the uf2-file to the keyboard.
