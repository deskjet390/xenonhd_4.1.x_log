xenonhd_4.1.x_log
=================

Change log for XenonHD rom's based on 4.1.x

Change log:

15.7.2012

Browser:
New navbar buttons.
Added a menu item in Browser called Close other tabs.
Open in incognito tab option in menu.
Increased tab limit.


Miscellaneous:
Added volume rocker wake.
Added long press to skip tracks
Added SMS Split by encoding and counter at end of message with settings.
YouTube app added until I fix the compatibility issue.
Cron enabled to drop caches daily. 
Old voice search app removed.
Lot's of other bug fixes.

Contacts:
Added T9 dialer and all its stuff.
Fixed gradient in contact application.
Updated layout.

Toro:
Fixed t-CDMA showing instead of Verizon wireless.
Fixed tether.
Correct battery stats.
Fixed wifi caliberation and 5GHz FEM damage.
Correct battery capacity.

Maguro:
Fixed MMS receiving on T-Mobile.
Enable automatic backlight by default.

20.7.2012

Miscellaneous: 
Added ROM settings.
Added customizable power widgets.
Added clock settings.
Power reboot menu updated.
Fixed holo gradient.
Swap the volume keys around if the device is rotated 180 or 90 degrees.
Sound effects from Nexus 7 added.
Long press to skip tracks fixed.
Added 2G and LTE toggles.
Framework2 added.
T9 dialer landscape merges.
Lot's of bug fixes.
Etc

Messaging app:
Return to message list if the last message on thread is being deleted.

23.7.2012

New battery options in ROM settings:
Circle mod
Hidden
Normal with %
Centered % text

Fixed data toggle.
Fixed 24 hour clock.
Optimized boot animation.
Ability to change device host name.
Notification bar brightness slider. (turn off automatic brightness)
New superuser keys.
Little tweaking of holo gradient again.
Volume rocker can control cursor.
Wifi: Allow to define the idle timeout (5 mn to 3 hours)
New XenonHD wallpapers. (thanks to rickerbilly)
Things I forgot. :P

Messaging application:
SMS Templates
Custom Vibrations
Timestamp Options
Fix crash when vibrate preference is not set.
Remove SMS split preference and replace with config option
Fix SMS Split logic
Gestures

Toro
New Verizon wireless proprietary apps

29.7.2012

Updated to 4.1.1 JRO03H build.
Theme Chooser added and fully functional.
Customizable navigation bar targets. (Thanks to team kang)
Customizable navigation bar height and width.
Updated Apollo music player.
Updated DSP Manager.
Added phone ring delay feature.
Added Quiet hours.
Reverted reflective soft keys.
Fix screen stretch issue for NuPlayer.
New performance tweaks.
New media and picture quality tweaks.
I might be forgetting a few things.

05.08.2012

Added quick unlock.
Added menu unlock.
Added expandable volume overlay.
Added option to show battery percentage on lock screen.
Fixed theming of lock screen.
Fixed theming of reboot dialog.
Battery bar fixed for landscape.
Navigation bar themeable.
Made notification icon aligned with text.
Unknown sources ticked by default.
Reboot dialog fixed to appear on lock screen. 
Fixed data dialog activity not disappearing when wifi is on.
Fixed lag for crespo users.
Updated proprietaries for Crespo, Maguro and Toro.
Fixed some tweaks not working.
Etc

11.08.2012

Updated to 4.1.1 JRO03L
Added support for Grouper.
Added performance settings.
Added lock screen weather.
Added Bluetooth AVRCP 1.3!
Unlinked ringer and notification volume.
Added safe volume headset.
Added NFC polling settings.
Added prebuilt effects for camera.
Added color selection and alpha settings for notification toggles.
Added lockscreen wallpaper settings.
Added option to change navigation bar color and transparency.
Fixed bug in lockscreen battery percentage.
Added spare parts.
Somethings I forgot!

12.08.2012

Reboots fixed!!!!!!
Prevent IllegalArgumentException and fix music layout on lockscreen because of missing layout items and row span exceeding row count.
Fixed mediascanner wakelock issue (device not sleeping)
Media scanner fixed.
Busybox updated 1.20.2
Modified how lockscreen wallpaper setting to fill the screen! 
Fixed performance settings crashing on grouper (and other devices)
Etc

14.08.2012

Added lockscreen custom targets. (Settings > Security) 
Added screenshot option in power menu.
Added brightness slider widget.
Fixed AVRCP 1.3 and added new features.
Fixed bug of vibrate when ringing not sticking in sound settings.
Updated build prints for Crespo, Maguro, Toro and Grouper to official fingerprints.
New weather icons for lockscreen.
Adjusted the lockscreen clock a bit.
Removed Youtube app and fixed the issue which didn't let youtube app to be installed from Play Store.
Fixed SMS warning dialog.
Updated File Manager.
New torch app.
Updated Apex Launcher to the latest beta.
Added transparency to in call screen.
Etc

25.08.2012

Added notification LED settings with options for custom settings for different apps.
Added ability to limit notifications for apps.
Added option to toggle IME switcher in notification shade. (From XenonHD ICS)
Added option to disable boot animation for faster boot,
Ability to change clock color.
Added rotation lock button like in tablets for phone.
Battery icon update for tablets.
Centered lock screen clock.
NFC polling: Summary now shows the set value.
Fixed down button while keyboard is in use. (Doesn't play well with custom images.)
Fixed sync toggle icon.
Removed torch from grouper.
Removed bug mailer. 
Much more bug fixes. I'm lazy! 

Phone App:

End call to Home Screen Setting is back.
Ability to add "my phone number".
Fix centered layout for inbound call ring.

Contacts App:
T9 dialer searches through nickname and company.

01.09.2012

Added ability to turn off 180 degree rotation.
Added HSPA+ support.
Added kill all button to recent switcher.
Added back light settings from CM.
Added ability to turn off volume preference sound.
Added menu option to open url in browser.
Added option to share to clipboard.
Updated SuperSU and binary to v0.96!
Fixed custom images not sticking.
Fixed CPU speed falling down to 700 MHz.
Lockscreen : Update camera availability check.
Many more bug fixes, etc!

Mms app

Added SMS windows pop-ups.
Added emojis with custom android emojis as well.
Lots of other features added. (Not possible to write everything down!)

Camera
Added all camera resolutions.

08.09.2012

Added Wifi text option.
Added Signal text option.
Added option to hide signal bar.
Added LED brightness control.
Added option to let LED blink while the screen is on.
Added long press back to kill apps. (Development settings)
Added option to toggle navigation bar and enable navigation bar controls from power menu.
Added ability to change nav bar height and width without rebooting.
Added navigation bar battery locations for tablets.
Ability to theme contacts app through theme chooser.
Enabled up to 7 navigation bar targets for Galaxy Nexus and Nexus 7.
Updated toggles for tablets.
Fixed browser fc while trying to move text cursor.
Fixed navigation bar issue.
Fix for updating TCP buffer size when switching network type.
Fixed bug which was causing vibrate mode to switch to loud mode while inserting headphones.
Fixed Mms app not vibrating on new messages.
Prioritize and fix virtual LED for tuna devices.
Etc

Mms
Rearrange MMS notification actions.
Add 'Quick reply' notification action.
Other fixes and stuff.

15.09.2012

Added ability to customize navigation bar ring targets.
Added option to change DPI from UI settings.
Added option to force tablet UI.
Added alternate signal layout. (GB style)
Added option to set the color of the digital clock widget.
Added support for Quad-core devices in performance settings.
Added new boot animation by JaeKar99!
Updated DSPManager.
Updated Apollo music player.
Rewrote the XenonHD wallpapers apk.
Fixed a rare reboot issue that was caused by landscape UI.
Fixed rotation while navigation bar is disabled.
Fixed MMS notification.
Removed Apex Launcher.
Other miscellaneous bug fixes, etc.

Mms:

QuickMessage: Added theme, Smiley, Emoji, Strip unicode and date support.
Added dark theme to quick message.
Lots more.

29.09.2012

Updated to build JRO03R.
Ability to open/close notification shade through navigation bar.
Ability to set IME Toggler as NavBar target.
Ability to turn on rotation on lock screen.
Ability to theme Clock, WifitText & Signal Text.
Ability to take screenshot from navigation bar.
Added bootloader option to reboot menu.
Added Nexus 7 DPI value (213) to ROM Settings DPI changer.
Added landscape specific layout for Color Picker dialog.
Added xhdpi sysbar images and add correct size icons for other resolutions.
Fix signal text (dBm) not working.
New alternate style images and fixed bugs with it.
Fix a logging NPE problem.
Show 3G icon for CDMA/1xRTT.
Navring IME Switcher & Ring/Vib toggle.
NavRing: All icons look the same as the Google Now icon.
Fix NavBar ring's center layout on lowered DPIs.
Ported Bluetooth Message Access Profile (MAP) from CM9.
Fixed resizing of back key in landscape UI.
Fixed automatic brightness.
Fixed exchange/activesync heartbeat not incrementing properly.
Fixed avrcp quirks blacklist configuration support.
Fixed ROMSettings force closing while setting custom images for nav bar using apps other than gallery.
Fixed CPU steps in performance settings.
Updated DSPManager.
Updated Apollo.
Updated toro build fingerprint.
Updated toro binaries.
Updated default kernel for Toro and Maguro.
Added USB OTG support for Grouper.
Added 720p recording support for video camera for Grouper.
Added more butter.
Many more bug fixes and stuff.

Clock:
Added Stopwatch & Countdown from CM.
Fixed a few bugs.

Messaging:
Added the option to change the soft keyboard type when composing.
Allow full themeing of mms via theme chooser.
Etc

Phone:
Vibrate on Answer.
Vibrate every 45 seconds.
Vibrate on end.
Vibrate on Call Waiting.
Disable accelerometer sensor while in-call and screen UI is off.
Prevent immediate screen-off after call-answer.
New in call proximity sensor option.
Etc

Calculator
Graphs functions.
Graph, matrix panels in menu.
Calculate rationals in hex/bin.
Bar is draggable.
Plus complete overhaul of the app.
So many new features.

07.10.2012

Added ability to force dual panel at any DPI.
Added ability to add application shortcuts for torch & Navbar toggle.
Option to enable GB style default app picker.
Kill all button added to recents for TabletUI.
Fixes for nav ring accidental presses. (rasied phone too)
New layout for Navring on tabs and grouper while in TabletUI.
More height/width sizes for navbar.
NavRing: fix layouts.
Updated props and binaries for Grouper.
Fixed flicker and touch responsiveness issues.
Enabled tablet like browser on grouper.
Fixed fast charge option.
Fixed navbar custom icons option.
Fixed issues with setting the max cpu speed for tegra 3 devices.
Updated Apollo.
Etc.

Clock:

Added flip and shake features. Both the actions flipping the phone, and shaking the phone can do one of the following operations:
1. do nothing
2. snooze the alarm
3. dismiss the alarm

Messaging:

Make Quickmessage cursor visible in "light theme".
QuickMessage: Fix screen relocking on 'View' after auto unlock.
QuickMessage: Prevent the screen from locking while user is typing.

13.10.2012

Updated to JB 4.1.2 JZO54K
Ability to add widgets to navbar.
Added option to vibrate on notification expansion in notification panel.
Added the ability to show the Menu UI Overflow (3-dots) within apps.
Added button to open/close notifications to navbar.
Added new wallpapers by JaiThemes, wad3g and Dominik.
Single finger notification expansion in notification panel.
2G toggle now takes us to mobile network settings.
Removed reboot requirement for IME switcher.
Updated think free app.
Updated default kernel for Tuna, Crespo and Grouper.
Updated props for Tuna, Crespo and Grouper.
Updated build fingerprint for Grouper.
Fixed Media Server sleep issue.
Fix brightness bar on tabs.
Major improvements to performance and battery life.
DSPManager updated.
Much more changes and bug fixes from JB 4.1.2
Etc

Messaging:

Quick message performance tweaks.

23.10.2012

Added recents RAM bar.
Added CM battery circle and CM battery circle with %.
Added timeout and instant lock option to slide lock.
Added option to change lockscreen color.
Added additional dictionaries for AOSP keyboard.
Updated APNs.
Updated build fingerprints for Maguro and Crespo.
Update to remove hardcoded screen on/off.
Disabled dual-pane checked by default.
Ability to resize NavBar widgets.
App manager: Enabled fast thumb scrolling.
Made alt GB layout look like GB.
VPN Traffic Amount in Human Readable Format.
Fixed H+ and add new navbar widget icon.
Framework Track Control : Switch from broadcast to audio service.
Lockscreen VolCtrls : Don't raise volume on skipTrack.
Holo-fy navbar widgets.
NavBar Widgets sizing fix.
Removed tweak scripts from init.d.
More bug fixes, etc.

Camera:

Power Shutter key.
Volume key to zoom in/out.
Fix rotation issue.
VideoCamera: Do not use continuous autofocus in time-laspe mode.
Animate snapshot in later stages.
Etc

Mms:

Fix cropping on MMS inline thumbnails.
QuickMessage: Preserve reply text on "View" press.
CS translations.
Etc

Kernel:

Added Color Control version 4.
Added Sound Control version 1.
Added Custom Voltage version 3.
Added Vibrator Control version 1.
Added Simple I/O (SIO) scheduler.
Add BFQv5 scheduler.
Added FSync Control version 1.
Added FastCharge Patch by Chad0989.
Added Morfic's contrast control.
Added CPUfreq governor 'lazy'.
Added CPUfreq governor 'Wheatley'.
Added 1.3Ghz, 1.4Ghz, 1.5Ghz, 1.6Ghz, 1.8Ghz and 2.0Ghz steps.
Auto detects if its a charger in the OTG cable, if it is, charges.
Interactive: Always limit initial speed bump to hispeed.
Etc

03.11.2012

Added clickable actions for clock and date with option for custom apps too.
Allow "Vibrate on Touch" behavior for Slide unlock. (Settings>Security)
Option to make toggles hidable.
Added setting to allow haptic feedback on toggle press.
CircleBattery: Revamped charging animation.
Fixed NavRing inflate.
Fixed NFC Toggle not working if it was not ON at boot
Fixed multiple haptic feedback while switching Toggles
Fixed kill app on long pressing the back button.
Fixed widget color.
Boot info now shows more info in boot dialog.
Etc

Messaging:

Added group messaging.
Added new feature 'Add SMS to Calendar remind'.
Etc

Kernel: (Tuna only)

Built from scratch again.
Updated to 3.0.47
Built from latest linaro toolchain.
Added Color Control version 4.
Added Sound Control version 1. 
Added Simple I/O (SIO) scheduler. 
Added Fast Charge.
Added Trinity contrast control.
New colors.
Tweaked readahead.
Fixed random reboots, lags and hang ups. 
Etc