C.A.T is an alternative of cmd,with a little bit of improvments.Because in cmd,and powershhel there aren't aliases,but C.A.T has! You can modify it straight from the file!
And it cannot run on Unix-based systems(yet)

## Commands

Available commands:
- `goto` [path] - Change directory to the specified path.The .. works as well.
- `lst` - List directory contents.Works like the dir command in windows,or ls in unix-like systems.Use the `-struct` attribute for showing structure
- `commit` [message] - Commit changes to the git repository with the specified message.
- `search` [folder] [filename]  - Search for a file with the specified name in the specified folder.Use it with the `-all` atrirbute to search in all drives.
> Note: If you see the `search` with the `-all` attribute,failes,try to replace the function at line 146,to a list of your dirvers
> 
> Ex: ['C:','D:','E:']
- `execute` [command] - Run the specified command in the shell(windows).
- `copy` [path] [filepath] - Copy the file to the specified path.is xcopy from windows btw.
- `mkfol` or `ml` [name] - Creates a folder
- `rmFol` or `rl` [name] - Removes a folder. Use the -force atribute to delete everything is inside that folder
- `makeFile` or `mf ` [name] [filetype] - Makes a file with the desired file extension
- `openFile` or `opn` [name] - Openes a file with Notepad
        yea that's it for now
## Future features

- Full git bash support
    - Pushing
    - Branches
- Curl suport
- Wsl support
- Partial Linux suport
    - Basic commands
- Chocolately support
- A kit for web development (yarn + deno)
- Pip support
