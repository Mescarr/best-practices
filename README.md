# PROJECT_NAME

## Goal

PROJECT_DESCRIPTION

## Commit

### Format of a commit message

`git commit -m "[action](#action)(*functionality*): *files*"`

#### <a name="action">action</a>

* **Add**

	>*One or more files added to the repository*
  
	`git commit -m "Add(foo): bar"`
        
* **Update**

	>*One or more files have had additions and / or deletions in their code*

	`git commit -m "Update(foo): bar"`
        
* **Fix**

	>*One or more files had bug(s) fixed*
    
	`git commit -m "Fix(foo): bar"`
        
* **Style**

	>*One or more file have had a coding style correction*

	`git commit -m "Style(foo): bar"`
        
* **Refactory**

	>*One or more files have undergone code refactoring*
    
	`git commit -m "Refactory(foo): bar"`
        
* **Remove**

	>*One or more files have been deleted*
    
	`git commit -m "Remove(foo): bar"`
        
### Multiple actions

>*You can also write a commit with multiple actions on multiple lines.*

```bash
 $ git commit -F - <<- END
 > Add(foo): file1 & file2 & file3
 > Style(foo): file4
 > Fix(foo): file7
 > END
```