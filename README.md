A Unturned 3 localization files converted to a single JSON file.\
`localization` object can contain one or more objects where key specifies name of `Folder` or `File`\
`Folder` object can contain one or more objects being `Folders` or `Files`\
`File` object can contain one or more strings\
where keys can be `emptyLine_number`, `Hcomment_number`, `comment_number` or any string key that Unturned has in localization files.

# Structure
```JSON
{
  "metadata": {
    "version": "Parser version (Major.Minor.Patch) that created this JSON file, in case Major or Minor is different then localization JSON structure probably changed",
    "gameVersion": "Unturned game version"
  },
  "localization": {
    "folderName": {
      "folderName": {
        "fileName.dat": {
          "key": "string",
          "key": "string"
        },
        "fileName.dat": {
          "key": "string",
          "key": "string",
          "emptyLine_number": "String or empty string",
          "Hcomment_number": "String or empty string",
          "comment_number": "String or empty string"
        }
      },
      "fileName.dat": {
        "key": "string",
        "key": "string",
        "emptyLine_number": "String or empty string",
        "Hcomment_number": "String or empty string",
        "comment_number": "String or empty string"
      }
    },
    "fileName.dat": {
      "key": "string",
      "key": "string",
      "emptyLine_number": "String or empty string",
      "Hcomment_number": "String or empty string",
      "comment_number": "String or empty string"
    }
  }
}
```
