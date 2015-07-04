Nivēśa :: Kāguṇita
==================

Kāguṇita (ಕಾಗುಣಿತ) is a collection of input methods for Kannada (ಕನ್ನಡ) for [OS X](https://en.wikipedia.org/wiki/OS_X) and [iOS](https://en.wikipedia.org/wiki/IOS) (coming soon).

## Kāguṇita (OS X)

The Kāguṇita `osx` directory contains a phonetic Kannada keyboard layout for OS X. Though OS X has an inbuilt `Kannada - QWERTY` keyboard which is also a phonetic keyboard, many characters can be entered only by pressing `alt` or `shift+alt`. Getting this right really slows down typing speed. Kāguṇita tries to address this issue.

Kāguṇita uses the OS X [character accent menu](https://support.apple.com/kb/PH18436?locale=en_US&viewlocale=en_US) to insert Kannada characters that phonetically map to the same English character. So to type ಟ, user can press and hold `t` (by default maps to ತ) and select ಟ from the accent menu. 

Kāguṇita (OS X) keyboard layout was created using [Ukelele](http://scripts.sil.org/ukelele).

### INSTALLATION

1. Execute the following commands:

       $ cp -R osx/Kagunita.bundle ~/Library/Keyboard\ Layouts/
       $ PRESS_HOLD=/System/Library/Input\ Methods/PressAndHold.app
       $ sudo cp Keyboard-kn.plist $PRESS_HOLD/Contents/Resources
       
2. Restart OS X

3. Add `Kagunita` keyboard layout via _System Preferences > Keyboard > Input Sources_

### LICENSE

Kāguṇita (OS X) keyboard layout is available under [MIT](http://opensource.org/licenses/MIT) license.


