# Volume-Shadow-Copies

Repository contains volume shadow copies image and descriptions.

* "Description of data creation": describes what happened to the file system and at what points the shadow copies were commited.

* "Image": contains NTFS image.

* "Manually changed files": contains files modified between NTFS states

* "View of reconstructed FS": contains an example of what the restored NTFS states look like when deduplication is enabled in the Belkasoft X product

* "Volume shadow copy store in hex". You can view NTFS with Volume Shadow Copies.e01 image by FTK Imager program. See screenshot with example of view: Volume shadow copy store in hex\Blocks for oldest shapshot.png (it shows that the store of the shadow copy contains the saved modified data of the resident file). Snapshot is the NTFS-state to which the data from the shadow copy was applied.