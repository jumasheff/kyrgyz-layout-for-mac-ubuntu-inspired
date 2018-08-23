# Kyrgyz keyboard layout for MAC users

Kyrgyz keyboard layout comes by default with Ubuntu-based systems. However it is not available by default for OS X. Here is a keyboard layout for you to install and be able to use additional 3 (ү, ө, ң) characters in kyrgyz language. Rest of the keyboard is same as the Russian one (except ё is now on `~` key (left from 1)).

### How to install
1. Download `kyrgyz-layout-for-mac-ubuntu-inspired-master.zip` to your computer.
2. Unpack the zip file. 
3. Navigate to newly created `kyrgyz-layout-for-mac-ubuntu-inspired-master` folder and copy KyrgyzLayout.bundle to **~/Library/Keyboard\ Layouts/**. In order to do this, go to `Finder`, hit `Shift + Command + g` simultaneously (you don't have to click on + sign, though).

If you are familiar with git you can run following command to download and move files.

```sh
git clone https://github.com/jumasheff/kyrgyz-layout-for-mac-ubuntu-inspired.git
cd kyrgyz-layout-for-mac-ubuntu-inspired/
sudo cp KyrgyzLayout.bundle /Library/Keyboard\ Layouts/
```

### How to add to keyboard 

1. Open **System Preferences**
2. Click on **input Sources** tab
3. Click **+** button
4. Select **Others** and you should see **Kyrgyz**
5. Choose it then click **Add**

### How to use
 - To type `ө` hit `minus` key and to type `Ө` hit Shift + `minus`.
 - To type `ү` hit `pipe/backslash` key and to type `Ү` hit Shift + `pipe/backslash`
 - To type `ң` hit `plus` key and to type `Ң` hit Shift `plus` 
See layout mapping screenshots:
1. Default state (0_default.png)
2. Shift key pressed (1_shift.png)
3. Option key pressed (2_option.png)
4. Option and Shift keys pressed (3_option_shift.png)
---
