-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Animal = Instance.new("ImageLabel")
local TooBar = Instance.new("Frame")
local SideBar = Instance.new("Frame")
local ScriptButton = Instance.new("TextButton")
local SettingsButton = Instance.new("TextButton")
local CreditsButton = Instance.new("TextButton")
local CreditsFrame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local ScriptsFrame = Instance.new("Frame")
local HUBASTRALButton = Instance.new("TextButton")
local ADMINButton = Instance.new("TextButton")
local RIVALSButton = Instance.new("TextButton")
local SettingsFrame = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_Roundify_12px = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Animal.Name = "Animal"
Animal.Parent = ScreenGui
Animal.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Animal.BackgroundTransparency = 1.000
Animal.BorderColor3 = Color3.fromRGB(27, 42, 53)
Animal.Position = UDim2.new(0.192249238, 0, 0.308999956, 0)
Animal.Size = UDim2.new(0, 472, 0, 266)
Animal.Visible = false
Animal.Image = "rbxassetid://3570695787"
Animal.ImageColor3 = Color3.fromRGB(40, 40, 40)
Animal.ScaleType = Enum.ScaleType.Slice
Animal.SliceCenter = Rect.new(100, 100, 100, 100)
Animal.SliceScale = 0.120

TooBar.Name = "TooBar"
TooBar.Parent = Animal
TooBar.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
TooBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
TooBar.BorderSizePixel = 0
TooBar.Size = UDim2.new(0, 472, 0, 40)

SideBar.Name = "SideBar"
SideBar.Parent = Animal
SideBar.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
SideBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideBar.BorderSizePixel = 0
SideBar.Size = UDim2.new(0, 112, 0, 266)

ScriptButton.Name = "ScriptButton"
ScriptButton.Parent = SideBar
ScriptButton.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
ScriptButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptButton.BorderSizePixel = 0
ScriptButton.Position = UDim2.new(0, 0, 0.150375932, 0)
ScriptButton.Size = UDim2.new(0, 112, 0, 35)
ScriptButton.Font = Enum.Font.SourceSans
ScriptButton.Text = "Scripts"
ScriptButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ScriptButton.TextScaled = true
ScriptButton.TextSize = 14.000
ScriptButton.TextStrokeColor3 = Color3.fromRGB(49, 49, 49)
ScriptButton.TextWrapped = true

SettingsButton.Name = "SettingsButton"
SettingsButton.Parent = SideBar
SettingsButton.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
SettingsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
SettingsButton.BorderSizePixel = 0
SettingsButton.Position = UDim2.new(0, 0, 0.413533837, 0)
SettingsButton.Size = UDim2.new(0, 112, 0, 35)
SettingsButton.Font = Enum.Font.SourceSans
SettingsButton.Text = "Settings"
SettingsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
SettingsButton.TextScaled = true
SettingsButton.TextSize = 14.000
SettingsButton.TextStrokeColor3 = Color3.fromRGB(49, 49, 49)
SettingsButton.TextWrapped = true

CreditsButton.Name = "CreditsButton"
CreditsButton.Parent = SideBar
CreditsButton.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
CreditsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.BorderSizePixel = 0
CreditsButton.Position = UDim2.new(0, 0, 0.281954885, 0)
CreditsButton.Size = UDim2.new(0, 112, 0, 35)
CreditsButton.Font = Enum.Font.SourceSans
CreditsButton.Text = "Credits"
CreditsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.TextScaled = true
CreditsButton.TextSize = 14.000
CreditsButton.TextStrokeColor3 = Color3.fromRGB(49, 49, 49)
CreditsButton.TextWrapped = true

CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = Animal
CreditsFrame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
CreditsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(0.237288132, 0, 0.150375932, 0)
CreditsFrame.Size = UDim2.new(0, 360, 0, 226)
CreditsFrame.Visible = false

TextLabel.Parent = CreditsFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0, 20, 0, 20)
TextLabel.Size = UDim2.new(0, 133, 0, 42)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "MADE BY ASTRAL:"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = CreditsFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 20, 0, 62)
TextLabel_2.Size = UDim2.new(0, 333, 0, 42)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "https://discord.gg/WAEkyKqted"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

ScriptsFrame.Name = "ScriptsFrame"
ScriptsFrame.Parent = Animal
ScriptsFrame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScriptsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsFrame.BorderSizePixel = 0
ScriptsFrame.Position = UDim2.new(0.237288132, 0, 0.150375932, 0)
ScriptsFrame.Size = UDim2.new(0, 360, 0, 226)
ScriptsFrame.Visible = false

HUBASTRALButton.Name = "HUBASTRALButton"
HUBASTRALButton.Parent = ScriptsFrame
HUBASTRALButton.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
HUBASTRALButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
HUBASTRALButton.BorderSizePixel = 0
HUBASTRALButton.Position = UDim2.new(0.0199999996, 0, 0.0199999996, 0)
HUBASTRALButton.Size = UDim2.new(0, 123, 0, 41)
HUBASTRALButton.Font = Enum.Font.SourceSans
HUBASTRALButton.Text = "ANIMAL SIMULATOR"
HUBASTRALButton.TextColor3 = Color3.fromRGB(0, 0, 0)
HUBASTRALButton.TextScaled = true
HUBASTRALButton.TextSize = 14.000
HUBASTRALButton.TextWrapped = true

ADMINButton.Name = "ADMINButton"
ADMINButton.Parent = ScriptsFrame
ADMINButton.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
ADMINButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ADMINButton.BorderSizePixel = 0
ADMINButton.Position = UDim2.new(0.428000003, 0, 0.0199999996, 0)
ADMINButton.Size = UDim2.new(0, 123, 0, 41)
ADMINButton.Font = Enum.Font.SourceSans
ADMINButton.Text = "ADMIN"
ADMINButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ADMINButton.TextScaled = true
ADMINButton.TextSize = 14.000
ADMINButton.TextWrapped = true

RIVALSButton.Name = "RIVALSButton"
RIVALSButton.Parent = ScriptsFrame
RIVALSButton.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
RIVALSButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
RIVALSButton.BorderSizePixel = 0
RIVALSButton.Position = UDim2.new(0.0200000331, 0, 0.307610571, 0)
RIVALSButton.Size = UDim2.new(0, 123, 0, 41)
RIVALSButton.Font = Enum.Font.SourceSans
RIVALSButton.Text = "RIVALS"
RIVALSButton.TextColor3 = Color3.fromRGB(0, 0, 0)
RIVALSButton.TextScaled = true
RIVALSButton.TextSize = 14.000
RIVALSButton.TextWrapped = true

SettingsFrame.Name = "SettingsFrame"
SettingsFrame.Parent = Animal
SettingsFrame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
SettingsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
SettingsFrame.BorderSizePixel = 0
SettingsFrame.Position = UDim2.new(0.237288132, 0, 0.150375932, 0)
SettingsFrame.Size = UDim2.new(0, 360, 0, 226)
SettingsFrame.Visible = false

TextLabel_3.Parent = SettingsFrame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Size = UDim2.new(0, 200, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Settings"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = Animal
TextLabel_4.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Size = UDim2.new(0, 200, 0, 40)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "GUI/ASTRAL"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton.BackgroundTransparency = 1.000
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0820668712, 0, 0.358208954, 0)
TextButton.Size = UDim2.new(0, 67, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "x"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

TextButton_Roundify_12px.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px.Parent = TextButton
TextButton_Roundify_12px.Active = true
TextButton_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px.BackgroundTransparency = 1.000
TextButton_Roundify_12px.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextButton_Roundify_12px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px.Selectable = true
TextButton_Roundify_12px.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px.ImageColor3 = Color3.fromRGB(40, 40, 40)
TextButton_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px.SliceScale = 0.120

-- Scripts:

local function GWHN_fake_script() -- ScriptButton.LocalScript 
	local script = Instance.new('LocalScript', ScriptButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
		script.Parent.Parent.Parent.SettingsFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = true
	end)
end
coroutine.wrap(GWHN_fake_script)()
local function GPGCOS_fake_script() -- SettingsButton.LocalScript 
	local script = Instance.new('LocalScript', SettingsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
		script.Parent.Parent.Parent.SettingsFrame.Visible = true
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
	end)
end
coroutine.wrap(GPGCOS_fake_script)()
local function IYYKE_fake_script() -- CreditsButton.LocalScript 
	local script = Instance.new('LocalScript', CreditsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.CreditsFrame.Visible = true
		script.Parent.Parent.Parent.SettingsFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
	end)
end
coroutine.wrap(IYYKE_fake_script)()
local function XUIZGX_fake_script() -- HUBASTRALButton.LocalScript 
	local script = Instance.new('LocalScript', HUBASTRALButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Kylan83728/V2/refs/heads/main/README.md"))()
	end)
end
coroutine.wrap(XUIZGX_fake_script)()
local function LLYUFC_fake_script() -- ADMINButton.LocalScript 
	local script = Instance.new('LocalScript', ADMINButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(LLYUFC_fake_script)()
local function DGSIY_fake_script() -- RIVALSButton.LocalScript 
	local script = Instance.new('LocalScript', RIVALSButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/zeynwq/main/main/rivals1"))()()
	end)
end
coroutine.wrap(DGSIY_fake_script)()
local function FCIPETX_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Animal.Visible = not script.Parent.Parent.Animal.Visible
	end)
end
coroutine.wrap(FCIPETX_fake_script)()
