-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local FRAME = Instance.new("Frame")
local NAME = Instance.new("TextLabel")
local NFT = Instance.new("TextButton")
local MOQ = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

FRAME.Name = "FRAME"
FRAME.Parent = ScreenGui
FRAME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FRAME.BorderColor3 = Color3.fromRGB(0, 0, 0)
FRAME.BorderSizePixel = 0
FRAME.Position = UDim2.new(0.275080919, 0, 0.278925627, 0)
FRAME.Size = UDim2.new(0, 426, 0, 256)
FRAME.Active= true
FRAME.Draggable = true

NAME.Name = "NAME"
NAME.Parent = FRAME
NAME.BackgroundColor3 = Color3.fromRGB(34, 26, 255)
NAME.BorderColor3 = Color3.fromRGB(0, 0, 0)
NAME.BorderSizePixel = 0
NAME.Size = UDim2.new(0, 426, 0, 75)
NAME.Font = Enum.Font.SourceSansItalic
NAME.LineHeight = 1.080
NAME.Text = "AMONG US "
NAME.TextColor3 = Color3.fromRGB(0, 0, 0)
NAME.TextSize = 67.000

NFT.Name = "NFT"
NFT.Parent = FRAME
NFT.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
NFT.BorderColor3 = Color3.fromRGB(0, 0, 0)
NFT.BorderSizePixel = 0
NFT.Position = UDim2.new(0.0281690136, 0, 0.359375, 0)
NFT.Size = UDim2.new(0, 181, 0, 118)
NFT.Font = Enum.Font.Unknown
NFT.LineHeight = 0.920
NFT.Text = "MOBILE"
NFT.TextColor3 = Color3.fromRGB(0, 0, 0)
NFT.TextSize = 30.000
NFT.TextWrapped = true
NFT.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/onepicesenpai/onepicesenpai/main/onichanokaka'))()
end)

MOQ.Name = "MOQ"
MOQ.Parent = FRAME
MOQ.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
MOQ.BorderColor3 = Color3.fromRGB(0, 0, 0)
MOQ.BorderSizePixel = 0
MOQ.Position = UDim2.new(0.523474157, 0, 0.359375, 0)
MOQ.Size = UDim2.new(0, 181, 0, 118)
MOQ.Font = Enum.Font.Unknown
MOQ.Text = "PC"
MOQ.TextColor3 = Color3.fromRGB(0, 0, 0)
MOQ.TextSize = 56.000
MOQ.TextWrapped = true
MOQ.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/onepicesenpai/onepicesenpai/main/onichanokaka'))()
end)
