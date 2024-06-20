# New Life Lib
This is a small project of mine (wip) This is a documentation for New Life Library 

## Loading The Lib
```lua
local NewLifeUI = loadstring(game:HttpGet("https://pastebin.com/raw/iaaKBLy4"))()
```

## Adding The Themes
```lua
local selectedTheme = "Black"
--Theres Two Themes Black & Ocean--
```

## Creating The Window
```lua
local ui = NewLifeUI:CreateWindow("New Life UI", selectedTheme)
```

## Creating The Tabs
```lua
local homeTab = ui:CreateTab("Home", selectedTheme)
```

## Creating The Buttons
```lua
ui:CreateButton(homeTab, "Click Me", function()
    print("Home Button Clicked!")
end, selectedTheme)
```

## Creating The Textbox
```lua
ui:CreateTextbox(homeTab, "Enter Text", function(text)
    print("Text entered:", text)
end, selectedTheme)
```

## Creating The Label
```lua
ui:CreateLabel(homeTab, "Welcome to New Life UI", selectedTheme)

-- Label Is Known As Sections --
```

## Creating Toggles
```lua
ui:CreateToggle(homeTab, "Toggle Option", function(state)
    print("Toggle state:", state)
end, selectedTheme)
```

## Importants
# You need to add a name for every tab so it doesn't get problems 
*Example*
```
       ↓↓ You Can Replace This "Home" to any names you want

local homeTab = ui:CreateTab("Home", selectedTheme)

you can replace the home tab as any names you want and make sure when you make the elements add the new name to every elements too
```
