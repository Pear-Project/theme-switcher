# Theme Switcher app for pearOS
This app is made to allow easy Lightmode- darkmode themes switching by the end-user, in pearOS ThiccSur.

## Screenshots :)
![Nice Screenshot](Screenshots/theme-switcher.png){:height="50%" width="50%"}


## Dependencies

   - install gambas3 package
   ```sh
   $ sudo apt-get install gambas3 -y
   ```

## Installation steps
 - From repository:
   - add the pear repository to your `sources.list` file:
   ```sh
   echo 'deb [trusted=yes] https://archive.pearos.xyz/ nicec0re/' | sudo tee -a /etc/apt/sources.list
   sudo apt update
   ```
   - install the theme switcher:
   ```sh
   sudo apt install theme-switcher
   ```

 - From Package:
   - Download the .deb package from `Releases` tab here, in GitHub
   - Install using gdebi/ dpkg
   ```sh
   $ sudo dpkg -i <path to downloaded deb file, or drag and drop>
   ```
   
   ## Usage
   - From Terminal:
     - Open a terminal and type `themesw`
   - From Application Daskboard:
     - Search for Theme Switcher with the nice icon made by Andrei Muntean. All rights reserved to him.


## Copyright
* This application is released under the Pear Public License v1. See LICENSE file for details
