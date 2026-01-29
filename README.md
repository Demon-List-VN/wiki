# wiki
## Folder structore
All files should be under `/src/[locale]/`

## File structure
Each file should have structure like this
```md
# Wiki title. This line must have "# " at the beginning
Wiki description. This line can be blank

Content
...
```

All commits will trigger sync work flow to database to index wiki file.

Wiki content will be fetched from this repo as raw file

First line will be used for `title` column, second line will be used for `description` column in the database

`description` can be empty, `title` can not be empty
