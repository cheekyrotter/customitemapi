# itemmanagerapi
A developer API for Skript, allowing you to store, edit and retrieve complex items, with lore, custom model data and more!

# Dependencies
-Skript (latest version is recommended)

-SkBee (future update)

-skript-gui (future update)

# Example
```
command /newitem <text> <item>:
  permission: item.create
  trigger:
    itemManager_new(arg-1, arg-2) #Creates a new item with the id "arg-1", and arg-2 as the item
```
    
See Usage.txt for a list of the functions, and how to use them (Gitbook coming soon!)
