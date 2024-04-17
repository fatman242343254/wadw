-- Gui to Lua
-- Version: 3.6

-- Instances:

local Main = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Tabs = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Misc = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Catching = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Top = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local Details = Instance.new("Frame")
local main = Instance.new("Frame")
local Catching_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local Mags = Instance.new("TextButton")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UICorner_6 = Instance.new("UICorner")
local Misc_2 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")

-- Properties:

Main.Name = "Main"
Main.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Main.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0682043135, 0, 0.15953283, 0)
Frame.Size = UDim2.new(0, 498, 0, 302)
Frame.Active = true
Frame.Draggable = true

Tabs.Name = "Tabs"
Tabs.Parent = Frame
Tabs.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Tabs.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tabs.BorderSizePixel = 0
Tabs.Size = UDim2.new(0, 73, 0, 302)

UICorner.Parent = Tabs

Misc.Name = "Misc"
Misc.Parent = Tabs
Misc.BackgroundColor3 = Color3.fromRGB(200, 48, 48)
Misc.BorderColor3 = Color3.fromRGB(0, 0, 0)
Misc.BorderSizePixel = 0
Misc.Position = UDim2.new(0.0945945978, 0, 0.167852402, 0)
Misc.Size = UDim2.new(0, 79, 0, 21)
Misc.Font = Enum.Font.SourceSans
Misc.Text = "Misc"
Misc.TextColor3 = Color3.fromRGB(0, 0, 0)
Misc.TextSize = 14.000

UICorner_2.Parent = Misc

Catching.Name = "Catching"
Catching.Parent = Tabs
Catching.BackgroundColor3 = Color3.fromRGB(200, 48, 48)
Catching.BorderColor3 = Color3.fromRGB(0, 0, 0)
Catching.BorderSizePixel = 0
Catching.Position = UDim2.new(0.0945945978, 0, 0.0800354481, 0)
Catching.Size = UDim2.new(0, 79, 0, 21)
Catching.Font = Enum.Font.SourceSans
Catching.Text = "Main"
Catching.TextColor3 = Color3.fromRGB(0, 0, 0)
Catching.TextSize = 14.000

UICorner_3.Parent = Catching

Top.Name = "Top"
Top.Parent = Frame
Top.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Top.BorderColor3 = Color3.fromRGB(0, 0, 0)
Top.BorderSizePixel = 0
Top.Position = UDim2.new(3.06401375e-08, 0, -0.101487719, 0)
Top.Size = UDim2.new(0, 498, 0, 52)

UICorner_4.Parent = Top

Title.Name = "Title"
Title.Parent = Top
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.0853355825, 0, 0.17006126, 0)
Title.Size = UDim2.new(0, 104, 0, 32)
Title.Font = Enum.Font.Gotham
Title.Text = "Death Hub"
Title.TextColor3 = Color3.fromRGB(200, 48, 48)
Title.TextSize = 31.000

UICorner_5.Parent = Frame

Details.Name = "Details"
Details.Parent = Frame
Details.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Details.BorderColor3 = Color3.fromRGB(0, 0, 0)
Details.BorderSizePixel = 0
Details.Position = UDim2.new(0.191326857, 0, 0.0701204017, 0)
Details.Size = UDim2.new(0, -3, 0, 257)

main.Name = "main"
main.Parent = Frame
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.BackgroundTransparency = 1.000
main.BorderColor3 = Color3.fromRGB(0, 0, 0)
main.BorderSizePixel = 0
main.Position = UDim2.new(0.178826168, 0, 0.0643049851, 0)
main.Size = UDim2.new(0, 410, 0, 294)

Catching_2.Name = "Catching"
Catching_2.Parent = main
Catching_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Catching_2.BackgroundTransparency = 1.000
Catching_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Catching_2.BorderSizePixel = 0
Catching_2.Position = UDim2.new(-2.9773247e-07, 0, -0.0102038737, 0)
Catching_2.Size = UDim2.new(0, 410, 0, 268)

TextLabel.Parent = Catching_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.281153589, 0, 0.113051176, 0)
TextLabel.Size = UDim2.new(0, 59, 0, 28)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Mags "
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

Mags.Name = "Mags"
Mags.Parent = Catching_2
Mags.BackgroundColor3 = Color3.fromRGB(200, 48, 48)
Mags.BorderColor3 = Color3.fromRGB(0, 0, 0)
Mags.BorderSizePixel = 0
Mags.Position = UDim2.new(0.215425909, 0, 0.113051176, 0)
Mags.Size = UDim2.new(0, 28, 0, 28)
Mags.Font = Enum.Font.SourceSans
Mags.Text = ""
Mags.TextColor3 = Color3.fromRGB(0, 0, 0)
Mags.TextSize = 14.000

UIAspectRatioConstraint.Parent = Mags

UICorner_6.Parent = Mags

Misc_2.Name = "Misc"
Misc_2.Parent = main
Misc_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Misc_2.BackgroundTransparency = 1.000
Misc_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Misc_2.BorderSizePixel = 0
Misc_2.Position = UDim2.new(-3.14614198e-07, 0, 1.16479306e-07, 0)
Misc_2.Size = UDim2.new(0, 409, 0, 268)
Misc_2.Visible = false

TextLabel_2.Parent = Misc_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.214285716, 0, 0.119402982, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
TextLabel_2.Font = Enum.Font.Unknown
TextLabel_2.Text = "Coming Soon!"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 29.000

-- Scripts:

Mags.MouseButton1Down:connect(function()
	loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/fatman242343254/wada/main/README.md?token=GHSAT0AAAAAACQIKFZY6TIHMPZ7WLPSND2CZRAH3VQ"))()
end)
