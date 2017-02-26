# Known issues
* None. Please report them! Either a crash or something not working like it should.

# Catalog requests
Please place your request in the [extensions repository](https://github.com/inorichi/tachiyomi-extensions/issues).

# Too soon or not planned yet

* Global search. [#45](https://github.com/inorichi/tachiyomi/issues/45)
* Stream manga from computer. [#88](https://github.com/inorichi/tachiyomi/issues/88)
* Show scanlation groups. [#107](https://github.com/inorichi/tachoyomi/issues/107)
* Statistics. [#115](https://github.com/inorichi/tachiyomi/issues/115)
* Double page viewer. [#149](https://github.com/inorichi/tachiyomi/issues/149)
* Import bookmarks from Bato.to or Kissmanga. [#250](https://github.com/inorichi/tachiyomi/issues/250)

# Frequently Asked Questions
**Q: I lost everything, what now?**  
A: Tachiyomi is still in beta. Some design changes or unexpected errors may lead to data loss. While I try for them not to happen, sometimes is unavoidable.

**Q: Any way to have automatic updates?**  
A: You can enable automatic updates in the about section of the settings (release only). If you are in the stable release, you can also install it from [F-droid](https://f-droid.org/repository/browse/?fdid=eu.kanade.tachiyomi). If you want auto updates for the dev release, you can install the application following [these steps](https://github.com/inorichi/tachiyomi/wiki/FDroid-for-debug-versions).

**Q: Downloads are unstable.**  
A: Try to use only one simultaneous download. The more slots you use the more unstable it becomes. Be aware that it could be a network issue on your terminal or on the catalog you are trying to download from.

**Q: Why some images aren't displayed?**  
A: Aside from network issues, it could be because the images are too big or the decoder doesn't support that image. Try using another image decoder.

**Q: Some covers are white after restoring from backup.**   
A: The url to the cover has changed. To fix this, refresh the metadata of your library in Settings > Advanced.

**Q: I can't find a manga in MAL's search results.**  
A: You can search a manga from your MAL list like this: _my: \<manga\>_. [#65](https://github.com/inorichi/tachiyomi/issues/65)

**Q: Why do I get a key error when installing?**  
A: F-Droid uses a different signing key than my release, so you can't switch between them. Nevertheless, you can backup and restore the data between versions. [#230](https://github.com/inorichi/tachiyomi/issues/230)

**Q: Can you make it possible to store manga on both internal storage and external sd card?** 
<br>A: At the moment, no. You could try using symlinks