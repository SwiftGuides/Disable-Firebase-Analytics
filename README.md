# Disable-Firebase-Analytics
This is how to disable Firebase Analytics in your project .

Source :- https://stackoverflow.com/a/51719880/10422074

For 2019, your Info.plist will have entries like this(Disables Permanently):
```swift
<key>FIREBASE_ANALYTICS_COLLECTION_ENABLED</key>
<string>NO</string>
<key>FIREBASE_ANALYTICS_COLLECTION_DEACTIVATED</key>
<string>YES</string>
<key>FirebaseScreenReportingEnabled</key>
<false/>
```
Note :- It should be in Info.plist, NOT GoogleServices-Info.plist.


#### * To Re-enable Firebase Analytics delete/remove all the above lines from your info.plist.
