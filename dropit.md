# Drop IT Arawa

## Suppression des fichiers expirés

Suppression du fichier passé par le hook.
Pour trouver le chemin du fichier indiqué dans le hook : 

https://github.com/nextcloud/server/blob/master/lib/private/Files/Cache/Cache.php

```php
/**
	 * get the path of a file on this storage by it's file id
	 *
	 * @param int $id the file id of the file or folder to search
	 * @return string|null the path of the file (relative to the storage) or null if a file with the given id does not exists within this cache
	 */
	public function getPathById($id) {
		$query = $this->getQueryBuilder();
		$query->select('path')
			->from('filecache')
			->whereStorageId()
			->whereFileId($id);

		$path = $query->execute()->fetchColumn();
		return $path === false ? null : $path;
	}
```
