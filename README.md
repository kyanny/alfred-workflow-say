# alfred-workflow-say

Alfred workflow to run [`say`](https://ss64.com/osx/say.html) command with given argument.

# Installation

1. Download [Keyword to Run Script.alfredworkflow](https://github.com/kyanny/alfred-workflow-say/raw/main/Keyword%20to%20Run%20Script.alfredworkflow)
2. Open _"Keyword to Run Script.alfredworkflow"_ file
3. Click "Import" button

# Usage

![demo](https://raw.githubusercontent.com/kyanny/alfred-workflow-say/main/screenshot2.png)

# Workflow overview

![workflow overview](https://raw.githubusercontent.com/kyanny/alfred-workflow-say/main/screenshot.png)

# Run script content

```
query=$1

say $query
```
