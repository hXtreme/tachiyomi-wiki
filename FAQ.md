# Known issues
* None

# Planned to do
* Hummingbird support. [#66](https://github.com/inorichi/tachiyomi/issues/66)
* AniList support. [#312](https://github.com/inorichi/tachiyomi/issues/312)
# Requested catalogs
* Tumangaonline! [#274](https://github.com/inorichi/tachiyomi/issues/274)
* Mangastream [#220](https://github.com/inorichi/tachiyomi/issues/220)
* MangaTraders [#145](https://github.com/inorichi/tachiyomi/issues/145)
* Madokami [#140](https://github.com/inorichi/tachiyomi/issues/140)
* Japscan [#29](https://github.com/inorichi/tachiyomi/issues/29)

# Too soon or not planned yet

* Global search. [#45](https://github.com/inorichi/tachiyomi/issues/45)
* Latest manga updates. [#61](https://github.com/inorichi/tachiyomi/issues/61)
* Sort by last updated. [#70](https://github.com/inorichi/tachiyomi/issues/70)
* Stream manga from computer. [#88](https://github.com/inorichi/tachiyomi/issues/88)
* Bookmarking chapters. [#89](https://github.com/inorichi/tachiyomi/issues/89)
* Show scanlation groups. [#107](https://github.com/inorichi/tachiyomi/issues/107)
* Statistics. [#115](https://github.com/inorichi/tachiyomi/issues/115)
* Download new chapters automatically. [#116](https://github.com/inorichi/tachiyomi/issues/116)
* Double page viewer. [#149](https://github.com/inorichi/tachiyomi/issues/149)
* Autodetect image's borders. [#219](https://github.com/inorichi/tachiyomi/issues/219)
* Import bookmarks from Bato.to or Kissmanga. [#250](https://github.com/inorichi/tachiyomi/issues/250)

# Frequently Asked Questions
**Q: I lost everything, what now?**  
A: Tachiyomi is still in beta. Some design changes or unexpected errors may lead to data loss. While I try for them not to happen, sometimes is unavoidable.

**Q: Any way to have automatic updates?**  
A: If you are in the stable release, you can install it from [F-droid](https://f-droid.org/repository/browse/?fdid=eu.kanade.tachiyomi), an updater for the github version could be added later. If you want auto updates for the dev release, you can install the application following [these steps](https://github.com/inorichi/tachiyomi/wiki/FDroid-for-debug-versions).

**Q: Downloads are unstable.**  
A: Try to use only one simultaneous download. The more slots you use the more unstable it becomes. Be aware that it could be a network issue on your terminal or on the catalog you are trying to download from.

**Q: Why some images aren't displayed?**  
A: Aside from network issues, it could be because the images are too big. Try to enable "_Reencode images_" on "_Settings > Advanced_" and select "_Skia_" on "_Settings > Reader > Image decoder_". You will have to clear the cache or redownload the chapter.

**Q: I can't find a manga in MAL's search results.**  
A: You can search a manga from your MAL list like this: _my: \<manga\>_. [#65](https://github.com/inorichi/tachiyomi/issues/65)

**Q: Why do I get a key error when installing?**  
A: F-Droid uses a different signing key than my release, so you can't switch between them. Nevertheless, you can backup and restore the data between versions. [#230](https://github.com/inorichi/tachiyomi/issues/230)

**Q:Can you make it possible to store manga on both internal storage and external sd card?** 
<br>A: At the moment, no. You could try using symlinks