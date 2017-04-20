There is an [F-Droid](https://f-droid.org/repository/browse/?fdid=org.fdroid.fdroid) repo available, maintained by [@j2ghz](https://github.com/j2ghz).

Repo url: `https://fdroid.j2ghz.com/repo`

Archive url: `https://fdroid.j2ghz.com/archive`

You can test availability by checking https://fdroid.j2ghz.com/repo/index.xml (if you see XML it's working)

# How-to
1. Install [F-Droid](https://f-droid.org/repository/browse/?fdid=org.fdroid.fdroid) ([direct](https://f-droid.org/FDroid.apk))
2. Add `https://fdroid.j2ghz.com/repo` as repo to F-Droid (Three-dot menu > Repositories > Plus)

## Available apps
* `Tachiyomi (dev)` (app id `eu.kanade.tachiyomi.debug`) - Main app built from master branch
* `Tachiyomi: *` (app id `eu.kanade.tachiyomi.extension.*`) - Extension source (* is name of site, e.g. en.batoto)


# Announcements
* 07.01.2017 Up, you need to **re-add the repo** in fdroid (lost signing key), I also had to **reset versionCode** counter so you have to tap yes when asked to downgrade, if it doesn't work just download [tachiyomi-b28.apk](https://fdroid.j2ghz.com/repo/tachiyomi-b28.apk) or newer and install with `adb install -r -d .\tachiyomi-b28.apk`
* 18.12.2016 Down
* 29.09.2016 Up
* 28.09.2016 Down, router misconfiguration
* 23.06.2016 Up
* 11.06.2016 Going down for server upgrade