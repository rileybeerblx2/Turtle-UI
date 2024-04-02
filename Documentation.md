# Turtle UI
This documentation is for Turtle UI Credit To The Owner

## Booting the Turtle UI Library
```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/turtle"))()
```




## Creating a Turtle UI Window
```lua
local OwO = library:Window("Rawr")
```

## Creating a Button
```lua
OwO:Button("Button name", function()
   print("pressed button")
end)
```

## Creating a Toggle
```lua
OwO:Toggle("Example toggle", true, function(bool)
    print(bool) -- bool is true or false depending on the state of the toggle
end)
```

## Creating a Color Picker
```lua
OwO:ColorPicker("Color Picker", Color3.fromRGB(255, 255, 255), function(color)
   print(color)
end)
```

## Creating a Slider
```lua
OwO:Slider("Example Slider",0,100,20, function(value)
   print(value)
end)
```

## Creating a Label
```lua
OwO:Label("Credits to Intrer#0421", Color3.fromRGB(127, 143, 166))
```

## Creating a Textbox
```lua
OwO:Box("Walkspeed", function(text, focuslost)
   if focuslost then
   print(text)
   end
end)
```

## Creating a DropDown
```lua
local dropdown = OwO:Dropdown("Example dropdown", {"Button 1", "Button 2", "Third button"}, function(name)
   print(name)
end)
```

## Creating a Dropdown Button
```lua
dropdown:Button("New button")
```

## Creating a Remove Button
```lua
dropdown:Remove("Button")
```
