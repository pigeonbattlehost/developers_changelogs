ZenithOS 3.2 Update Changelog
MAINTAINER: zntsproj
CONTRIBUTORS: pigeonbattlehost, zntsproj

-----------------------------------------

build/core/combo:
[zntsproj]: add legacy flags

build/target:
[zntsproj]: add required flags

external/chromium_org:
[zntsproj]: make legacy stubs so chromium_org will compile on newer hardware

frameworks/base/core:
[zntsproj]: bail out to the old version of Framework-res, localize some strings in strings.xml

frameworks/base/packages/Keyguard:
[zntsproj]: remove ugly key design in AVD emulation image

frameworks/base/packages/SystemUI:
[zntsproj]: put the statusbar clock position into the center

packages/apps/Calculator:
[zntsproj]: new app icon

packages/apps/Dialer:
[zntsproj]: new app icon

packages/apps/Email:
[zntsproj]: new app icon

packages/apps/ESFiles:
[zntsproj]: new app in AVD emulation

packages/apps/Mms:
[zntsproj]: new app icon

packages/apps/Settings:
[zntsproj]: add CPU architecture, model and frequency info in DeviceInfo
[zntsproj]: add experimental option to change statusbar clock position, isn't working properly yet
[zntsproj]: new app icon

packages/apps/Updater:
[zntsproj]: add Updater app
[zntsproj]: change mirrors from GitHub official repo to jsdelivr

packages/apps/ViaBrowser:
[zntsproj]: new app in AVD emulation
