# SVN Commands

## Update
- svn update

## Status
- svn status

## Difference
- svn diff
 - agregando **-u** se muestran los documentos que fueron modificados en el ultimo commit

## Commit
### Status
- M: an existing file in the server has been modified
- ?: the file has been added to the workspace but not to the server
- !: The file has been deleted from the workspace but not from the server
- A: The file will be added to the server in the next commit
- D: The file will be deleted from the server in the next commit

### Commands
- svn add [file_name]
- svn delete [file_name]
- svn ci -m "comment" *
 - *  means that every available file will be commited
 
## Revert
- svn revert . -R
