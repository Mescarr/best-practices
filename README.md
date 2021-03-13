# PROJECT_NAME

## Goal

PROJECT_DESCRIPTION

## Commit

### Format of a commit message

`git commit -m "action(functionality): description"`

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
        
* **Refactoring**

	>*One or more files have undergone code refactoring*
    
	`git commit -m "Refactoring(foo): bar"`
        
* **Remove**

	>*One or more files have been deleted*
    
	`git commit -m "Remove(foo): bar"`
        
### Multiple actions

>*You can also write a commit on multiple lines.*

```bash
 $ git commit -F - <<- END
 > Add(foo): general description
 > detailed description
 > on
 > multiple lines
 > END
```