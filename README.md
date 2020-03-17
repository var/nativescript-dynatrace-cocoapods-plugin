# nativescript-dynatrace-cocoapods-plugin

### Installation 

`tns plugin add nativescript-dynatrace-cocoapods-plugin`

### Configuration

You must generate application ID and beacon URL and add them to your project's `Info.plist` file so that your iOS mobile app can send monitoring data to your Dynatrace monitoring environment.

Add the configuration to your `Info.plist` in the following way:

`<key>DTXApplicationID</key>`  
`<string>xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx</string>`

`<key>DTXBeaconURL</key>`
`<string>https://xxxxxxxxxx.bf.dynatrace.com/mbeacon</string>`
