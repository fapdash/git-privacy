### pyGitPrivacy

Config Example:

put this in your `$repo/.git/config`:

```
[privacy]
        password = 123456
        mode = simple #simple,reduce
        pattern = "h,s" #"y,M,d,h,m,s"
        limit = 8-18
        database_path = /home/grotax/git/gitData.db
[advice]
        ignoredHook = false
```