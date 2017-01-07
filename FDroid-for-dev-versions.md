There is an [F-Droid](https://f-droid.org/repository/browse/?fdid=org.fdroid.fdroid) repo for dev versions available, maintained by [@j2ghz](https://github.com/j2ghz).

The repo url is `https://fdroid.j2ghz.com/repo`. If you want to see all versions, not just 3 latest, you can use `https://fdroid.j2ghz.com/archive` as well. Versions are named `[latest release].[commit count]`. You can test availability by checking https://fdroid.j2ghz.com/repo/index.xml

### TL;DR
1. Add `https://fdroid.j2ghz.com/repo` as repo to [F-Droid](https://f-droid.org/repository/browse/?fdid=org.fdroid.fdroid)
2. Install `Tachiyomi` from F-Droid (app id `eu.kanade.tachiyomi.debug`)

# Announcements
* 07.01.2017 Up, you need to **re-add the repo** in fdroid (lost signing key), I also had to **reset versionCode** counter so you have to tap yes when asked, if it doesn't work just download [tachiyomi-b28.apk](https://fdroid.j2ghz.com/repo/tachiyomi-b28.apk) or newer and install with `adb install -r -d .\tachiyomi-b28.apk`
* 18.12.2016 Down
* 29.09.2016 Up
* 28.09.2016 Down, router misconfiguration
* 23.06.2016 Up
* 11.06.2016 Going down for server upgrade