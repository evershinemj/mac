# how to configure default application for specific files
## steps
1. select the file
2. press `cmd + i` to `get info`
3. find the `open with` menu, and input the desired default application
4. click `change all`, to apply this change to this file type rather than this file alone
## effect
for instance, for markdown files, if the default application is not typora, then 
`open -a typora <foo.md>` needs to be used. now `open <foo.md>` is enough
