## packwiz curseforge install

Install a project from a CurseForge URL, slug, ID or search

```
packwiz curseforge install [URL|slug|search] [flags]
```

### Options

```
      --addon-id uint32   The CurseForge project ID to use
      --category string   The category to add files from (slug, as stored in URLs); the category in the URL takes precedence
      --file-id uint32    The CurseForge file ID to use
      --game string       The game to add files from (slug, as stored in URLs); the game in the URL takes precedence (default "minecraft")
  -h, --help              help for install
```

### Options inherited from parent commands

```
      --cache string              The directory where packwiz will cache downloaded mods(default "C:\Users\vedvo\AppData\Local\packwiz\cache") (default "C:\\Users\\vedvo\\AppData\\Local\\packwiz\\cache")
      --config string             The config file to use (default "C:\Users\vedvo\AppData\Roaming\packwiz\.packwiz.toml")
      --meta-folder string        The folder in which new metadata files will be added, defaulting to a folder based on the category (mods, resourcepacks, etc; if the category is unknown the current directory is used)
      --meta-folder-base string   The base folder from which meta-folder will be resolved, defaulting to the current directory (so you can put all mods/etc in a subfolder while still using the default behaviour) (default ".")
      --pack-file string          The modpack metadata file to use (default "pack.toml")
```

### SEE ALSO

* [packwiz curseforge](packwiz_curseforge.md)	 - Manage curseforge-based mods

###### Auto generated by spf13/cobra on 20-Aug-2022
