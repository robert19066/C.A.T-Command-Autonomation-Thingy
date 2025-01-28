**C.A.T** is an alternative of cmd,with a little bit of improvments.
Because in cmd,and powershhel there aren't aliases,but C.A.T has! You can modify it straight from the file!
And it ***cannot*** run on Unix-based systems(yet)

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
## ***Future features***

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

## Modifiing the aliases

1. Enter the main file
2. Go to line 15
3. You will se Aliases:
   - From line 17-44 you can change the aliases!
  
### The aliases segment:


```python
#Aliases:

change_directory_alias = 'goto' #done

list_directory_alias = 'lst' #done
list_directory_tree_alias_attrb = '-struct' #done

git_commit_alias = 'commit' #done

search_file_alias = 'search' #done
search_file_all_attirbute_alias = '-all' #done

run_command_alias = 'execute' #done
copy_file_alias = 'copy'#done
help_alias = 'help' #done
comand_insert_char = '>' #done
clear_alias = 'clear' #done

mkdir_alias = 'makeFol' #done
mkdir_alias2 = 'ml' #done

rmdir_force_alias_attrb = '-force' #done
rmdir_alias = 'removeFol' #done
rmdir_alias2 = 'rl' #done
```

## Dependencies:
*None!* every library use in this project is preinstalled with python,so you dont need to install anything! It works *staight out from the box!*

## Fun facts
- Fun fact: C.A.T's original name was K.I.T.T.Y(cli Kit for Ideas and Tricky Toes Y1 edition).it was so stupid
- C.A.T stands for Comandline Autonomation Tool
- It's real name is WinCAT or WinC.A.T
- It took 3 h
- It had an broken tkinter version

# I hope you like it :)
it tool 305 lines...
