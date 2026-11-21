# HYPERZSCRIPT GUI
Hello Welcome To My Script Gui

# Load Gui

```
loadstring(game:HttpGet("https://raw.githubusercontent.com/Itskyanscripts/Ui/refs/heads/main/LoadMainUI"))()
```

#Window

```
local HyperZ = getgenv and getgenv().HyperZ or _G.HyperZ
local Window = HyperZ:CreateWindow({ Name = "+1GamesScript" })
```


# Tab

```
local Tab = Window:CreateTab("Main", "home")
```

# Section

```
Tab:CreateSection("Type Something Here")
```
# Button

```
Tab:CreateButton({
	Name = "Button",
	Callback = function()
	end,
})
```

# Toggle

```
Tab:CreateToggle({
	Name = "Toggle",
	CurrentValue = false,
	Callback = function(Value)
	end,
})
```

# DropDown

```
Tab:CreateDropdown({
	Name = "Dropdown",
	Options = {"Option 1"},
	CurrentOption = {"Option 1"},
	Callback = function(Option)
	end,
})
```

# Input

```
Tab:CreateInput({
	Name = "Input",
	CurrentValue = "value here",
	PlaceholderText = "Type here...",
	Callback = function(Text)
	end,
})

```

# Slider

```

Tab:CreateSlider({
	Name = "Slider",
	Range = {0, 100},
	CurrentValue = 50,
	Callback = function(Value)
	end,
})
```

# Keybind

```
Tab:CreateKeybind({
	Name = "Keybind",
	CurrentKeybind = "E",
	Callback = function(Key)
	end,
})

```

# Lebel

```
Tab:CreateLabel("This is a label")
```

# Paragraph

```

Tab:CreateParagraph({
	Title = "Title Here",
	Content = "Text Here"
})
```
