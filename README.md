local KeySystem = loadstring(game:HttpGet("https://raw.githubusercontent.com/OopssSorry/LuaU-Free-Key-System-UI/main/source.lua"))()
local KeyValid = false
local response = KeySystem:Init({
	Debug=false, -- <bool> Prints some output in console when true
	Title="ASTRAL | Key System", -- <string or nil> Title of key system
	Description=nil, -- <string or nil> Description of key system
	Link="", -- <string> String to get key
	Discord="https://discord.gg/gcMKRK2nSn", -- <string or nil> Button to join your discord server
	SaveKey=false, -- <bool or nil> Just auto save key
	Verify=function(key) -- <function> Verify is key valid
		if key=="PikgtGUHghyfgYg" then
      KeyValid=true
			return true
		else
			return false
		end
	end,
	GuiParent = game.CoreGui, -- <object or nil> :3
})

-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local gui = Instance.new("ImageLabel")
local SideBar = Instance.new("Frame")
local JeuxButton = Instance.new("TextButton")
local ScriptsButton = Instance.new("TextButton")
local CreditsButton = Instance.new("TextButton")
local TopBar = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local CreditsFrame = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local ScriptsFrame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local JeuxFrame = Instance.new("Frame")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local ImageButton = Instance.new("ImageButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

gui.Name = "gui"
gui.Parent = ScreenGui
gui.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gui.BackgroundTransparency = 1.000
gui.BorderColor3 = Color3.fromRGB(27, 42, 53)
gui.Position = UDim2.new(0.292867988, 0, 0.303482592, 0)
gui.Size = UDim2.new(0, 546, 0, 315)
gui.Visible = false
gui.Image = "rbxassetid://3570695787"
gui.ImageColor3 = Color3.fromRGB(70, 70, 70)
gui.ImageTransparency = 0.200
gui.ScaleType = Enum.ScaleType.Slice
gui.SliceCenter = Rect.new(100, 100, 100, 100)
gui.SliceScale = 0.120

SideBar.Name = "SideBar"
SideBar.Parent = gui
SideBar.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SideBar.BackgroundTransparency = 0.200
SideBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideBar.BorderSizePixel = 0
SideBar.Position = UDim2.new(0, 0, 0.158730164, 0)
SideBar.Size = UDim2.new(0, 546, 0, 40)

JeuxButton.Name = "JeuxButton"
JeuxButton.Parent = SideBar
JeuxButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JeuxButton.BackgroundTransparency = 1.000
JeuxButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
JeuxButton.BorderSizePixel = 0
JeuxButton.Size = UDim2.new(0, 88, 0, 40)
JeuxButton.Font = Enum.Font.SourceSans
JeuxButton.Text = "Jeux"
JeuxButton.TextColor3 = Color3.fromRGB(0, 0, 0)
JeuxButton.TextSize = 14.000

ScriptsButton.Name = "ScriptsButton"
ScriptsButton.Parent = SideBar
ScriptsButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScriptsButton.BackgroundTransparency = 1.000
ScriptsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsButton.BorderSizePixel = 0
ScriptsButton.Position = UDim2.new(0.161172166, 0, 0, 0)
ScriptsButton.Size = UDim2.new(0, 88, 0, 40)
ScriptsButton.Font = Enum.Font.SourceSans
ScriptsButton.Text = "Scripts"
ScriptsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ScriptsButton.TextSize = 14.000

CreditsButton.Name = "CreditsButton"
CreditsButton.Parent = SideBar
CreditsButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CreditsButton.BackgroundTransparency = 1.000
CreditsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.BorderSizePixel = 0
CreditsButton.Position = UDim2.new(0.322344333, 0, 0, 0)
CreditsButton.Size = UDim2.new(0, 88, 0, 40)
CreditsButton.Font = Enum.Font.SourceSans
CreditsButton.Text = "Credits"
CreditsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.TextSize = 14.000

TopBar.Name = "TopBar"
TopBar.Parent = gui
TopBar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopBar.BackgroundTransparency = 1.000
TopBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
TopBar.BorderSizePixel = 0
TopBar.Size = UDim2.new(0, 546, 0, 41)

TextLabel.Parent = gui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0366300382, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 133, 0, 50)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "AstraKalf"
TextLabel.TextColor3 = Color3.fromRGB(34, 34, 34)
TextLabel.TextSize = 14.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(63, 63, 63)
TextLabel.TextWrapped = true

CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = gui
CreditsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CreditsFrame.BackgroundTransparency = 1.000
CreditsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(0, 0, 0.285714298, 0)
CreditsFrame.Size = UDim2.new(0, 546, 0, 225)
CreditsFrame.Visible = false

TextLabel_2.Parent = CreditsFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Size = UDim2.new(0, 103, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "made by ASTRAL:"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

TextLabel_3.Parent = CreditsFrame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.161172166, 0, 0.142222226, 0)
TextLabel_3.Size = UDim2.new(0, 103, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Discord serveur link :    https://discord.gg/ZSHxuBxcYq"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

ScriptsFrame.Name = "ScriptsFrame"
ScriptsFrame.Parent = gui
ScriptsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScriptsFrame.BackgroundTransparency = 1.000
ScriptsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsFrame.BorderSizePixel = 0
ScriptsFrame.Position = UDim2.new(0, 0, 0.285714298, 0)
ScriptsFrame.Size = UDim2.new(0, 546, 0, 225)
ScriptsFrame.Visible = false

TextButton.Parent = ScriptsFrame
TextButton.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0, 0, 0.0897778347, 0)
TextButton.Size = UDim2.new(0, 88, 0, 38)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Admin"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_2.Parent = ScriptsFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.186813191, 0, 0.0897778347, 0)
TextButton_2.Size = UDim2.new(0, 88, 0, 38)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Aimbot/Esp"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

JeuxFrame.Name = "JeuxFrame"
JeuxFrame.Parent = gui
JeuxFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JeuxFrame.BackgroundTransparency = 1.000
JeuxFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
JeuxFrame.BorderSizePixel = 0
JeuxFrame.Position = UDim2.new(0, 0, 0.285714298, 0)
JeuxFrame.Size = UDim2.new(0, 546, 0, 225)
JeuxFrame.Visible = false

TextButton_3.Parent = JeuxFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.0109890113, 0, 0.102222219, 0)
TextButton_3.Size = UDim2.new(0, 88, 0, 38)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Animal Sim"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

TextButton_4.Parent = JeuxFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.214285716, 0, 0.102222219, 0)
TextButton_4.Size = UDim2.new(0, 88, 0, 38)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Combat Warriors"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000

TextButton_5.Parent = JeuxFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.419413924, 0, 0.102222219, 0)
TextButton_5.Size = UDim2.new(0, 88, 0, 38)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Rivals"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000

TextLabel_4.Parent = gui
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.833333313, 0, 0, 0)
TextLabel_4.Size = UDim2.new(0, 133, 0, 50)
TextLabel_4.Font = Enum.Font.SourceSansBold
TextLabel_4.Text = "1.0.0"
TextLabel_4.TextColor3 = Color3.fromRGB(34, 34, 34)
TextLabel_4.TextSize = 14.000
TextLabel_4.TextStrokeColor3 = Color3.fromRGB(63, 63, 63)
TextLabel_4.TextWrapped = true

ImageLabel.Parent = gui
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 58, 0, 50)
ImageLabel.Image = "http://www.roblox.com/asset/?id=79996104359280"

ImageButton.Parent = ScreenGui
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.473444611, 0, 0.055970151, 0)
ImageButton.Size = UDim2.new(0, 36, 0, 33)
ImageButton.Image = "http://www.roblox.com/asset/?id=79996104359280"

-- Scripts:

local function UFVUHPM_fake_script() -- JeuxButton.LocalScript 
	local script = Instance.new('LocalScript', JeuxButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = true
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
	end)
end
coroutine.wrap(UFVUHPM_fake_script)()
local function XURXG_fake_script() -- ScriptsButton.LocalScript 
	local script = Instance.new('LocalScript', ScriptsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = false
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = true
	end)
end
coroutine.wrap(XURXG_fake_script)()
local function SQQQ_fake_script() -- CreditsButton.LocalScript 
	local script = Instance.new('LocalScript', CreditsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = false
		script.Parent.Parent.Parent.CreditsFrame.Visible = true
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
	end)
end
coroutine.wrap(SQQQ_fake_script)()
local function FRFSKPS_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(FRFSKPS_fake_script)()
local function FXQRKS_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		local ESP_Color = Color3.fromRGB(128, 0, 128) -- Violet
		local function createESP(player)
			if player.Character then
				local highlight = Instance.new("Highlight")
				highlight.Parent = player.Character
				highlight.FillColor = ESP_Color
				highlight.FillTransparency = 0.5
				highlight.OutlineColor = Color3.new(1,1,1)
				highlight.OutlineTransparency = 0
			end
		end
	
		local function onPlayerAdded(player)
			createESP(player)
			player.CharacterAdded:Connect(function()
				createESP(player)
			end)
		end
	
		for _, player in pairs(game.Players:GetPlayers()) do
			createESP(player)
		end
	
		game.Players.PlayerAdded:Connect(onPlayerAdded)
	end)
end
coroutine.wrap(FXQRKS_fake_script)()
local function OOLX_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Golddeathninja/af/refs/heads/main/a"))()
	end)
end
coroutine.wrap(OOLX_fake_script)()
local function FJVMPK_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://infernium.xyz/cwfree.lua",true))()
	end)
end
coroutine.wrap(FJVMPK_fake_script)()
local function XHCS_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/zeynwq/main/main/rivals1"))()()
	end)
end
coroutine.wrap(XHCS_fake_script)()
local function YBHPCI_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.gui.Visible = not script.Parent.Parent.gui.Visible
	end)
end
coroutine.wrap(YBHPCI_fake_script)()
