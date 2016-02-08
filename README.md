# files_filter
ownCloud App https://apps.owncloud.com/content/show.php/files_filter?content=174667

#Changes in Core
Add this line to lib/private/files/filesystem.php:

```
static public function unlockFile($path,$type) {
		return self::$defaultInstance->unlockFile($path,$type);
}
```
