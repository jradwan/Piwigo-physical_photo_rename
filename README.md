# Physical Photo Rename
PPR is a [Piwigo](http://piwigo.org/) extension to rename a physical photo, video, or album (at the OS-level), preserving all metadata.

I don't use the [virtual albums](http://piwigo.org/doc/doku.php?id=user_documentation:albums_management) feature much as I prefer to have all of my photos stored in folders of my own hierarchical design rather than Piwigo's structure used by the upload mechanism (i.e., "./upload/year/month/day/randomfilename.jpg"). Occcasionally I want re-name the actual file (photo or video) or folder (outside of Piwigo). The problem with that, however, is that the next time I run Piwigo's synchronization process the original file (or folder) is deleted from the database and re-added, losing all of the metadata associated with the item (tags, description, etc.).

Similar to my PPM ([Physical Photo Move](https://github.com/jradwan/Piwigo-physical_photo_move)) extension, PPR (Physical Photo Rename) is an attempt to alleviate this inconvenience by allowing an existing physical file or folder (i.e., not in the upload folder and linked into a virtual album) to be renamed and keep all of the existing metadata in the database.

- - -
## Usage

After activating the plugin for your Piwigo site, there will be a "Rename" tab in the "Edit" area for any physical item (photo, video, or album).

### Renaming a Photo (or Video)

TODO

### Renaming an Album

TODO

- - -
## Disclaimer

***WARNING!*** PPR makes file system and database changes!  _Please_ make sure you have a backup of your Piwigo folder structure and database before trying this plugin for the first time. 

No program is without bugs and while I've tested the plugin extensively myself, there's always the possibility for something to go wrong. Use simulation mode and check the debugging messages closely before allowing the plugin to make actual changes for the first time. If you find a problem, please open an issue [here](https://github.com/jradwan/Piwigo-physical_photo_rename/issues) on Github or on the [Piwigo forums](http://piwigo.org/forum/) and let me know!

- - -
## To Do

- determine if doing this in Batch Manager is feasible/realistic
  
- - -
## Contact

Jeremy C. Radwan

- https://github.com/jradwan
- http://www.windracer.net/blog

- - -
## References

- [Piwigo](http://piwigo.org/)
- [Piwigo Extensions](http://piwigo.org/ext/)
