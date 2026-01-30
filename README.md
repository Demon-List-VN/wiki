# wiki

## Naming
All files and folders is `kebab-case`. Example: `this-is-a-file-or-folder-name`

## Folder structure
All files should be under `/src/[locale]/`

## File structure
Each file should have structure like this
```md
# Wiki title. This line must have "# " at the beginning
Wiki description. This line can be blank

![image](image link here)

Lorem ispum dolor sit amet, ...
...
```

All commits will trigger sync to database workflow.

Wiki contents will be fetched from this repo as raw file

`title` is the first line of the file. Cannot be empty
`description` is the first line that isn't the first line and image. Can be empty
