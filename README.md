# files_filter
ownCloud App


File: lib/private/files/filesystem.php
Add this  
```
static public function unlockFile($path,$type) {
		return self::$defaultInstance->unlockFile($path,$type);
}
```
