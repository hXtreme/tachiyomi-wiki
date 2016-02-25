There is a repo for debug versions available, maintained by [@j2ghz](https://github.com/j2ghz).

The repo url is `https://fdroid.j2ghz.com/repo`. If you want to see all versions, not just 3 latest, you can use `https://fdroid.j2ghz.com/archive` as well. You can test availability by checking https://fdroid.j2ghz.com/repo/index.xml

Example packages:

| App id                           | App name         | Explanation             |
|----------------------------------|------------------|-------------------------|
| eu.kanade.tachiyomi.debug        | Tachiyomi        | Builds of master branch |
| eu.kanade.tachiyomi.backup.debug | Tachiyomi backup | Builds of backup branch |
| eu.kanade.tachiyomi.v0.1.0       | Tachiyomi v0.1.0 | Builds of tag v0.1.0    |

| Version    | Version explanation             |
|------------|---------------------------------|
| 0.1.4.498  | [latest release].[commit count] |
| backup.623 | [branch].[build number]         |
| v0.1.0.448 | [tag].[build number]            |

I was also building pull requests, but since I didn't use it, I disabled it. If someone is interested in them, I can enable it.

### TL;DR
1. Add `https://fdroid.j2ghz.com/repo` as repo to fdroid
2. Install `Tachiyomi` from F-Droid (app id `eu.kanade.tachiyomi.debug`)