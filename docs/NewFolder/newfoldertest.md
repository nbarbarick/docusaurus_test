---
sidebar_position: 1
---
# Testing a new doc, new folder, new sidebar

To create a new folder structure:

1. Add a new folder to `/docs`.
2. Add a `_category_.json` file.
3. Add this to the file:
```
  {
  "label": "New Folder",
  "position": 1,
  "link": {
    "type": "generated-index",
    "description": "Creating a new folder then adding a _category_.json file with some config."
  }

  ```

  You can also set the default page when you click on **Read Our Docs** by modifying the config file.

  ```
    {
      type: 'doc',
      docId: 'NewFolder/newfoldertest',
      position: 'left',
      label: 'Read Our Docs',
    },
  ```