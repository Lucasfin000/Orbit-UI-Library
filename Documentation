# Orbit UI Library v1.0 Latest Update

## Loading The Library
```lua
local lib = loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Lucasfin000/Orbit-UI-Library/main/Library", true))()
```



## Creating a Window
```lua
local window = lib:Window()
local wind = lib:Window(Color3.fromRGB(gradientcolor1), Color3.fromRGB(gradientcolor2), "Orbit UI Library")
```



## Creating a Tab
```lua
local tab = wind:NewTab("test", "")
```
## Creating Info
```lua
tab:Info("test info")
```
## Creating a Button
```lua
local btn = tab:Button("test button", function()
	print("text button")
end)
```

### Changing the value of an existing button
```lua
Button("TEXT", callbackfunc)
```


## Creating a Slider
```lua
tab:Slider("test slider", 1, 100, function(val)
	print(val)
end)
```

### Change Slider Value
```lua
Slider:Set(2)
```
Make sure you make your slider a variable (local CoolSlider = Tab:AddSlider...) for this to work.


## Creating a Label
```lua
tab:Label("test label")
```

### Changing the value of an existing label
```lua
Label("TEXT")
```

### Changing the value of an existing slider
```lua
Slider("TEXT", minimumvalue, maximumvalue, callbackfunc)
```

### Changing the value of an existing textbox
```lua
Textbox("TEXT", placeholdertext(optional), callbackfunc) -- user needs to press enter for callbackfunc to be fired, a ripple will show when enter is pressed
```

## Creating a Paragraph
```lua
tab:Paragraph("test paragraph")
```

### Changing an existing paragraph
```lua
Paragraph("TEXT")
```


## Creating an Textbox
```lua
tab:Textbox("test textbox", "test placeholder", function(text)
	print(text)
end)
```

