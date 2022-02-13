# csv2md_by_template (csv2mdt.py)
- this script helps you to convert csv file to multiple md files by template, the filename of each comes from first column in your csv file.
- this idea came from [dicussion](https://github.com/Arrowyz01/csv2logseq_block/issues/1) with @candideu !

# Preparation
- python3
- pandas
- template.md
- filename.csv

# Caution
- the variables in template.md should be like $title, $name or $title_name (no blank in variables, please replace blank with '_' by yourself)
- the variables in template.md should match the first row (colume name) in data.csv
- but you don't need to replace the blank in column name in csv file by yourself. script will do that. So you can keep column name in csv file as "title name"

# Quick start
- download csv2mdt.py and put it in the same folder as template.md and filename.csv
- use shell and 'cd' to that folder
- use follow command
    > python csv2mdt.py filename.csv

- the output files will be automatically generated in the same folders
- you can use template.md and data.csv in this repo to play around!

# Video


https://user-images.githubusercontent.com/85311840/153748774-cc13906a-bbf5-479c-a5a8-0280dcb880ce.mp4

# Advanced
- you can edit the script somehow, such as the path to your template.md and the path to your csv file
- you can also put the script in $PATH, to make it easier to call
