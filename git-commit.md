## Commit

### Format of a commit message

**git commit -m "[action](#action)(*functionality*): *files*"**

#### <a name="action">action</a>

* **Add**

  *One or more files added to the repository*
    
  example:
    
        git commit -m "Add(foo): bar"
        
* **Fix**

    *One or more files had bug(s) fixed*
    
    example:
    
        git commit -m "Fix(foo): bar"
        
* **Style**

    *One or more file have had a coding style correction*
    
    example:
    
        git commit -m "Style(foo): bar"
        
* **Refactory**

    *One or more files have undergone code refactoring*
    
    example:
    
        git commit -m "Refactory(foo): bar"
        
* **Remove**

    *One or more files have been deleted*
    
    example:
    
        git commit -m "Remove(foo): bar"
        
### Multiple actions

*You can also write a commit with multiple actions on multiple lines.*
    
example:
    
![[img] git commit on multiple lines](https://github.com/EpitechIT2020/B-CPE-101-BDX-1-1-bistromatic-victor.lair-henry/blob/master/doc/resources/git_commit_multiple_lines.png "git commit on multiple lines")