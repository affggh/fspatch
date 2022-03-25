# fspatch
if you are using mke2fs+e2fsdroid or mkfs.erofs repack android image

# Usage
if there have a vendor file
vendor-
        vendor-    
				......    
		config-    
				vendor_fs_config    
				vendor_file_context    
```shell
python fspatch.py ./vendor/vendor ./vendor/config/vendor_fs_config
```