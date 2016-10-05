1) Run the following commands:

git clone https://github.com/marciot/phonegap-app-developer.git
cd phonegap-app-developer
npm install
npm run phonegap -- build ios

2) Add to platforms/ios/PhoneGap/Bridging-Header.h:
  #import "Plugins/cordova-plugin-iosrtc/cordova-plugin-iosrtc-Bridging-Header.h"

3) Open phonegap-app-developer/platforms/ios/PhoneGap.xcodeproj in XCode
4) Select "Later" when asked to upgrade syntax
5) Select team under "General"
6) Set "Use Legacy Swift Language Version" to "Yes" in "Build Settings"
7) Compile!
