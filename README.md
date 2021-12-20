# Forkable config repository for the tom60 PCB
How to use:
* Fork this repository using the "fork" button in the top right of this web page.
![Fork](img/forkrepo.png)
* Head over to your fork of this repository.
* Do desired keymap changes in config/tom60.keymap in accordance with https://zmk.dev/docs/codes  
![Edit the keymap using the edit button here](img/editkeymap.png)
* Commit changes in the bottom of the web page.
![Remember to commit in order to save and trigger a new firmware build](img/Commitchanges.png)
* Head over to the "Actions tab".
![Actions tab is located here](actionstab.png)
  * Wait for the build to finish.
  ![Wait for the build job to complete. Feel free to click the build job now as well](img/waitforbuild.png)
* Click on the build job and download the resulting firmware.zip under "artifacts".
![No images from this point on. Good luck soldier](img/firmware.png)
* Extract the uf2-file from the zip.
* Reset the keyboard either by double pressing the reset button or hitting &reset (default MO(3) + R).
* Copy the uf2-file to the keyboard.
