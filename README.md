# my-snippets
Random stuff that I never remember, but need to use from time to time.

## Shell

Move all the files with a certain ext from one dir to another dir. All the files will lose their og dir structure and will be 'flattened' at the destiny dir.

`find "/Users/carantesk/development/shell-stuff" -type f -name "*.sh" -exec mv -v {} "/Volumes/Seagate Backup Plus Drive/development/shell-stuff" \;`
