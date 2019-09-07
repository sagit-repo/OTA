====================
     09-07-2019
====================


   * hardware/interfaces/
c74e29b5 Wifi: Syncronization on reading and writing ringbuffer

====================
     09-06-2019
====================


====================
     09-05-2019
====================


   * packages/apps/Longshot/
ff71ea5 Add edit action on notification
7135a5e Declare priv-app permission

====================
     09-04-2019
====================


   * packages/apps/HavocSettings/
cbca784 Settings: Add toggle for OP gestures haptic feedback [2/2]
256b26a Settings: Add Circle battery style from PA [2/2]
057578e Settings: Add 2 more date styles [2/2]
0923c58 Settings: Add more date styles [2/2]
9f1bd86 Lockscreen date styles [2/2]

   * packages/apps/Recorder/
25243f4 Automatic translation import

====================
     09-03-2019
====================


   * packages/apps/Recorder/
c74af6a overlay: Use dp instead of sp on timer tick
6586a41 Keep overlay always dark
e4765ae ScreencastService: Update notification immediately after recording started
5467cfc OverlayService: Hide when starting recording, if not overlay should not be displayed
a3ba553 Fix inline build
fc9f85b Revert "Android studio import"
c28df9e Android studio import
f9d51c4 Improve error handling and some code
acc6ec7 Prevent miss-clicks on views
fc01360 Fix lag when dragging overlay and updating timer
5b48203 Add alpha on floating window
16e3015 Cleanup config
a650176 Adjust internal audio recording params
1f56e9a Add timer into activity
5f33ba7 Revert "Open last recorded item on stop"
9778c93 Improve floating window
f04b85c Use accent from framework
54deb67 Don't hardcode font
4fc7b0f Fix black theme
54130d1 overlay: Add little spacing on the end of recording button
19386d1 Improve share notifications
263eac9 Disable qs tiles when locked
dd671a9 Open last recorded item on stop
aad89be Add listener on Settings activity
f33d5a3 Stop overlay service on record started
3a78d14 Add orientation preference
0e4e3a4 Pause recording when screen off to save resources

====================
     09-02-2019
====================


   * build/make/
480d6e34c More base_rules.mk optimizations
d1fbc5ce7 Skip much of aux_config.mk

   * packages/apps/Recorder/
db7264c Check before unregistering broadcast receiver
309b558 Always use H264
5d4f105 Hide some activities from recents
73f9d42 Add more preferences
dbb5dec Use reflection to collapse statusbar
1ede6d1 Improve transparent theme
02c298e Conditionally disable internal audio recording support
38c59b2 Import custom androidx preference library for better theming
fec3196 More theming improvements
c09bc90 Refactor settings UI
adbd547 Refactor recording methods
9511b58 Separate and improve strings
446ad5a Rename strings to custom_strings.xml
6574d90 Cleanup intents
9afc974 Remove from launcher
6e48d03 Update icon
8ff4d49 Change version
7004cc5 Implement qs tiles and refactor code
2885a4d Improve recording floating overlay
33ce278 Don't use shared prefs to store recording state
fccca20 UI redesign
55254ec Add system audio recording support [1/2]
e97bc73 Rebrand
1ad0339 Bump sdk

====================
     09-01-2019
====================


====================
     08-31-2019
====================


   * frameworks/av/
dd944d083 audiopolicy: Fixes for internal audio recording

   * packages/apps/HavocSettings/
8bf35ab Settings: Cleanup Screenrecord

   * vendor/havoc/
171b9a79 vendor: Build Recorder app
e431a980 overlay: Disable config_keyguardUserSwitcher on sw600dp

====================
     08-30-2019
====================


====================
     08-29-2019
====================


====================
     08-28-2019
====================


====================
     08-27-2019
====================


====================
     08-26-2019
====================


   * frameworks/base/
461b4439995 LiveDisplayTile: Remove tile if unavailable
53f60204018 LiveDisplayTile: Refresh state after livedisplay initialization
9e134a265b1 LiveDisplayTile: Enable for outdoor mode and skip night display on HWC2
46feef1f35e LiveDisplayService: Notify SystemUI after initialization finished
0e312ebbca3 LiveDisplayManager: Perform null check in getConfig()
df621436e36 OutdoorModeController: Unconditionally enable auto mode on HWC2
792198c2e38 OutdoorModeController: Advertise MODE_AUTO
a26a01ea477 LiveDisplayService: Properly disable ColorTemperature
4544b72c222 LiveDisplay: Cleanup
514f655948e FOD: Differentiate dreaming and pulse
3bcf4d1ad99 Initial support for in-display fingerprint sensors
f130c21dde5 Revert "Initial support for OnePlus in-display fingerprint sensor"
5b738d48ebe BatteryEstimates: Toggle without SystemUI restart
cea35a2469a SystemUI: Tiny expanding improvement
7193e18b05a NotificationColorUtil: Kill logspam
80896c176cd fwb: Port extended screenshot function from OOS
0f6ae90ab2c fwb: Add support for internal audio recording
c759d5e9c74 Remove uses of libcore.io DropBox and EventLogger
063d310bdeb SystemUI: Use matching data usage size formatting between QS and Settings
0c49cefe2f1 Update Xbox BT controller mapping to support upcoming controller firmware update
e71592a5ed8 Add keylayout for Xbox One USB controller
ac2d054ec64 Keylayout for xbox controllers
c7b33967e59 Added mapping files for DualShock3 and DualShock4
366e2f3323c Fallback BUTTON_MODE to HOME
fe193c50566 Remap PS key to BUTTON_MODE
ace4f3d9c8b Set default VR_MODE based on VR feature support
02b4be633fc fw/b: Add capability to allow tethering to use VPN upstreams
2c19d6d04d6 power: Respect global vibration setting for charging sounds
fc5d3c4018e Fix wrong locale causing reboot in recovery

   * packages/apps/HavocSettings/
f8def8f Add Redmi K20 Pro to devices

   * packages/apps/Recorder/
1ae9b37 Automatic translation import

   * packages/apps/Settings/
f4f72f2079 LiveDisplaySettings: Hide automatic outdoor mode preference on HWC2
89b80d7f50 LiveDisplaySettings: Reenable display mode preference for outdoor mode
9201a2df21 Settings: Don't index display mode and color temperature on HWC2
eaf7a73db1 LiveDisplay: Cleanup
22939a78de Revert "Settings: Restart SystemUI when toggling battery estimates"
47953ab5f2 Settings: Add hotspot setting to allow VPN upstreams

   * prebuilts/clang/host/linux-x86/
c10f4cc0 Update prebuilt Clang to r365631.

   * vendor/havoc/
f72285ff overlay: Remove config_screenshotEditor

====================
     08-25-2019
====================

   * art/
9872b03cef Stop verifying barrier count for thread dumping
f39e06e5e3 ART: Cache type index validity

   * device/havoc/sepolicy/
c582f9d sepolicy: Add hal_lineage_fod domain
b1a8f1c sepolicy: Add rules for Long screenshot service
dcd5a08 sepolicy: Guard neverallowed policy for system_file with userdebug/eng

   * hardware/havoc/interfaces/
3188b3b IFingerprintInscreen: Allow HALs to control position and size
633cc27 IFingerprintInscreen: Allow HALs to provide finger up/down callback
0c2a47a IFingerprintInscreen: Allow HALs to control dimming
8c64861 Introduce in-screen fingerprint scanner HAL

   * packages/apps/HavocSettings/
7e90e32 Settings: Remove haptic feedback duration for OP gestures

   * system/vold/
7a92952 Add "changepw" command to vdc.

   * vendor/havoc/
8537bfea vendor: Build Longshot app
2b82a010 backuptool_ab: Make copy_file preserve file/directory attrs
1bccec63 vendor: Add vendor.lineage.biometrics.fingerprint.inscreen permission
934b832d config: Use tether automatic upstream selection
9bd51a30 overlay: Remove config_wifi_wakeup_available




