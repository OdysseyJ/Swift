## Settings URL schemes:

> Note: < i=OS 5.1 use `prefs:`. > 5.1 use `app-settings:`

- app-settings:root=General&path=About
- app-settings:root=General&path=ACCESSIBILITY
- app-settings:root=AIRPLANE_MODE
- app-settings:root=General&path=AUTOLOCK
- app-settings:root=General&path=USAGE/CELLULAR_USAGE
- app-settings:root=Brightness
- app-settings:root=General&path=Bluetooth
- app-settings:root=General&path=DATE_AND_TIME
- app-settings:root=FACETIME
- app-settings:root=General
- app-settings:root=General&path=Keyboard
- app-settings:root=CASTLE
- app-settings:root=CASTLE&path=STORAGE_AND_BACKUP
- app-settings:root=General&path=INTERNATIONAL
- app-settings:root=LOCATION_SERVICES
- app-settings:root=ACCOUNT_SETTINGS
- app-settings:root=MUSIC
- app-settings:root=MUSIC&path=EQ
- app-settings:root=MUSIC&path=VolumeLimit
- app-settings:root=General&path=Network
- app-settings:root=NIKE_PLUS_IPOD
- app-settings:root=NOTES
- app-settings:root=NOTIFICATIONS_ID
- app-settings:root=Phone
- app-settings:root=Photos
- app-settings:root=General&path=ManagedConfigurationList
- app-settings:root=General&path=Reset
- app-settings:root=Sounds&path=Ringtone
- app-settings:root=Safari
- app-settings:root=General&path=Assistant
- app-settings:root=Sounds
- app-settings:root=General&path=SOFTWARE_UPDATE_LINK
- app-settings:root=STORE
- app-settings:root=TWITTER
- app-settings:root=General&path=USAGE
- app-settings:root=VIDEO
- app-settings:root=General&path=Network/VPN
- app-settings:root=Wallpaper
- app-settings:root=WIFI
- app-settings:root=INTERNET_TETHERING

## Implementation

`Titanium`

```
  Ti.Platform.openURL("app-settings:root=General&path=About");
```

`Swift`

```
UIApplication.sharedApplication().openURL(NSURL(string:"prefs:root=General&path=Keyboard")!)
```

`Objective-C`

```
[[UIApplication sharedApplication] openURL:[NSURL URLWithString:@"prefs:root=General&path=Keyboard"]];
```
