Nivēśa :: Āṅglā
===============

Āṅglā (आंग्ला) contains custom English keyboard layouts for [OS X](https://en.wikipedia.org/wiki/OS_X).

The standard English keyboard layouts in OS X are named after regions like U.S., British, Irish, etc. And when the input method is shown in the menubar, it displays the region's flag! If anyone outside these regions wants to use English, they are forced to select one of these keyboard layouts and cringe! Āṅglā fixes this issue :)

`English.bundle` is essentially a copy of `U.S.` keyboard layout with a cleaner name `English` and no US flag as icon.

`Aangla.bundle` is again a copy of `U.S.` keyboard layout with the Indian flag as icon (instead of US flag) and an Indic name `Aangla`.

Āṅglā keyboard layouts were created using [Ukelele](http://scripts.sil.org/ukelele).

## INSTALLATION

### __Install English keyboard layout__  

  1. Execute the following command:
  
        sudo cp -R English.bundle /Library/Keyboard\ Layouts/
         
  2. Restart OS X
  
  3. Add the new `English` keyboard layout via _System Preferences > Keyboard > Input Sources_
  
### __Install Aangla keyboard layout__
  
  1. Execute the following command: 
  
        sudo cp -R Aangla.bundle /Library/Keyboard\ Layouts/
         
  2. Restart OS X
  
  3. Add the `Aangla` keyboard layout in *System Preferences > Keyboard > Input Sources*
  
### __( OPTIONAL ) Change the default OS X keyboard layout__  
  
  __WARNING__: This will cause your OS X setup to run again. Existing user data is __not__ affected. However it may force you to re-enter your WiFi password and create a new user account.
  
  1. Execute the command: `sudo rm /var/db/.AppleSetupDone`
   
  2. Restart OS X
  
  3. Choose the `English` or `Aangla` keyboard layout in the setup process


## LICENSE

Āṅglā keyboard layouts are available under [MIT](http://opensource.org/licenses/MIT) license.
