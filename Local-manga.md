Since v0.5.0, Tachiyomi supports local manga.

You have to place your manga inside the folder `Tachiyomi/local` located in the root of your internal storage or external SD card, usually `/sdcard` and `/storage/18F5-2C11` (with different values).

After that, they will be shown in the catalogue as a new source. **Remember to give the app disk permissions on Android 6.0 and higher**. If you add more chapters later you'll have to manually refresh the chapter list (by pulling down the list).

Supported chapter formats are directories with pictures inside, ZIP/CBZ, RAR/CBR and EPUB. But expect better performance with directories and ZIP/CBZ.

You can also place your chapters or manga in both storages and Tachiyomi will merge them. For example, with

`/sdcard/Tachiyomi/local/my manga/ch1`

and

`/storage/18F5-2C11/Tachiyomi/local/my manga/ch2`

the app will see two chapters in a single manga.

The path to the folder (or archive) with images must contain both the manga title and the chapter name (as seen above).

You can then access the manga in Catalogues > Local manga.