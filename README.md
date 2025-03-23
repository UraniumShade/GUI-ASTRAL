-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TopBar = Instance.new("Frame")
local SideBar = Instance.new("Frame")
local JeuxButton = Instance.new("TextButton")
local ScriptsButton = Instance.new("TextButton")
local CreditsButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local CreditsFrame = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local JeuxFrame = Instance.new("Frame")
local AnimalSimulator = Instance.new("TextButton")
local BladebBall = Instance.new("TextButton")
local CombatWarriors = Instance.new("TextButton")
local Strongestbattlground = Instance.new("TextButton")
local Rivals = Instance.new("TextButton")
local ScriptsFrame = Instance.new("Frame")
local Admin = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
Frame.BackgroundTransparency = 0.200
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.256449163, 0, 0.24378109, 0)
Frame.Size = UDim2.new(0, 642, 0, 400)
Frame.Visible = false

TopBar.Name = "TopBar"
TopBar.Parent = Frame
TopBar.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
TopBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
TopBar.BorderSizePixel = 0
TopBar.Position = UDim2.new(0.0529595017, 0, 0, 0)
TopBar.Size = UDim2.new(0, 608, 0, 56)

SideBar.Name = "SideBar"
SideBar.Parent = Frame
SideBar.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
SideBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideBar.BorderSizePixel = 0
SideBar.Size = UDim2.new(0, 162, 0, 400)

JeuxButton.Name = "JeuxButton"
JeuxButton.Parent = SideBar
JeuxButton.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
JeuxButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
JeuxButton.BorderSizePixel = 0
JeuxButton.Position = UDim2.new(0.00617283955, 0, 0.185000002, 0)
JeuxButton.Size = UDim2.new(0, 160, 0, 50)
JeuxButton.Font = Enum.Font.SourceSansBold
JeuxButton.Text = "Jeux"
JeuxButton.TextColor3 = Color3.fromRGB(0, 0, 0)
JeuxButton.TextSize = 14.000

ScriptsButton.Name = "ScriptsButton"
ScriptsButton.Parent = SideBar
ScriptsButton.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
ScriptsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsButton.BorderSizePixel = 0
ScriptsButton.Position = UDim2.new(0.00617283955, 0, 0.310000002, 0)
ScriptsButton.Size = UDim2.new(0, 160, 0, 50)
ScriptsButton.Font = Enum.Font.SourceSansBold
ScriptsButton.Text = "Scripts"
ScriptsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ScriptsButton.TextSize = 14.000

CreditsButton.Name = "CreditsButton"
CreditsButton.Parent = SideBar
CreditsButton.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
CreditsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.BorderSizePixel = 0
CreditsButton.Position = UDim2.new(0.00617283955, 0, 0.435000002, 0)
CreditsButton.Size = UDim2.new(0, 160, 0, 50)
CreditsButton.Font = Enum.Font.SourceSansBold
CreditsButton.Text = "Credits"
CreditsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.TextSize = 14.000

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.00155763235, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 291, 0, 56)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "Infernium | Rip v2"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = Frame
CreditsFrame.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
CreditsFrame.BackgroundTransparency = 1.000
CreditsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(0.250778824, 0, 0.140000001, 0)
CreditsFrame.Size = UDim2.new(0, 480, 0, 344)
CreditsFrame.Visible = false

TextLabel_2.Parent = CreditsFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0270833336, 0, 0.0523255803, 0)
TextLabel_2.Size = UDim2.new(0, 159, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "Made By ASTRAL"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

TextLabel_3.Parent = CreditsFrame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.0270833336, 0, 0.261627913, 0)
TextLabel_3.Size = UDim2.new(0, 244, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSansBold
TextLabel_3.Text = "Discord:   https://discord.gg/ZSHxuBxcYq"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

JeuxFrame.Name = "JeuxFrame"
JeuxFrame.Parent = Frame
JeuxFrame.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
JeuxFrame.BackgroundTransparency = 1.000
JeuxFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
JeuxFrame.BorderSizePixel = 0
JeuxFrame.Position = UDim2.new(0.250778824, 0, 0.140000001, 0)
JeuxFrame.Size = UDim2.new(0, 480, 0, 344)

AnimalSimulator.Name = "Animal Simulator"
AnimalSimulator.Parent = JeuxFrame
AnimalSimulator.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
AnimalSimulator.BorderColor3 = Color3.fromRGB(0, 0, 0)
AnimalSimulator.BorderSizePixel = 0
AnimalSimulator.Position = UDim2.new(0, 20, 0, 20)
AnimalSimulator.Size = UDim2.new(0, 159, 0, 50)
AnimalSimulator.Font = Enum.Font.SourceSansBold
AnimalSimulator.Text = "Animal SImulator"
AnimalSimulator.TextColor3 = Color3.fromRGB(0, 0, 0)
AnimalSimulator.TextSize = 14.000

BladebBall.Name = "Blade bBall"
BladebBall.Parent = JeuxFrame
BladebBall.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
BladebBall.BorderColor3 = Color3.fromRGB(0, 0, 0)
BladebBall.BorderSizePixel = 0
BladebBall.Position = UDim2.new(0.420833319, 0, 0.0581395365, 0)
BladebBall.Size = UDim2.new(0, 159, 0, 50)
BladebBall.Font = Enum.Font.SourceSansBold
BladebBall.Text = "Blade Ball"
BladebBall.TextColor3 = Color3.fromRGB(0, 0, 0)
BladebBall.TextSize = 14.000

CombatWarriors.Name = "Combat Warriors"
CombatWarriors.Parent = JeuxFrame
CombatWarriors.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
CombatWarriors.BorderColor3 = Color3.fromRGB(0, 0, 0)
CombatWarriors.BorderSizePixel = 0
CombatWarriors.Position = UDim2.new(0.0416666679, 0, 0.261627913, 0)
CombatWarriors.Size = UDim2.new(0, 159, 0, 50)
CombatWarriors.Font = Enum.Font.SourceSansBold
CombatWarriors.Text = "Combat Warriors"
CombatWarriors.TextColor3 = Color3.fromRGB(0, 0, 0)
CombatWarriors.TextSize = 14.000

Strongestbattlground.Name = "Strongest battlground"
Strongestbattlground.Parent = JeuxFrame
Strongestbattlground.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
Strongestbattlground.BorderColor3 = Color3.fromRGB(0, 0, 0)
Strongestbattlground.BorderSizePixel = 0
Strongestbattlground.Position = UDim2.new(0.420833319, 0, 0.261627913, 0)
Strongestbattlground.Size = UDim2.new(0, 159, 0, 50)
Strongestbattlground.Font = Enum.Font.SourceSansBold
Strongestbattlground.Text = "Strongest battlground"
Strongestbattlground.TextColor3 = Color3.fromRGB(0, 0, 0)
Strongestbattlground.TextSize = 14.000

Rivals.Name = "Rivals"
Rivals.Parent = JeuxFrame
Rivals.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
Rivals.BorderColor3 = Color3.fromRGB(0, 0, 0)
Rivals.BorderSizePixel = 0
Rivals.Position = UDim2.new(0.0416666679, 0, 0.46802327, 0)
Rivals.Size = UDim2.new(0, 159, 0, 50)
Rivals.Font = Enum.Font.SourceSansBold
Rivals.Text = "Rivals"
Rivals.TextColor3 = Color3.fromRGB(0, 0, 0)
Rivals.TextSize = 14.000

ScriptsFrame.Name = "ScriptsFrame"
ScriptsFrame.Parent = Frame
ScriptsFrame.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
ScriptsFrame.BackgroundTransparency = 1.000
ScriptsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsFrame.BorderSizePixel = 0
ScriptsFrame.Position = UDim2.new(0.250778824, 0, 0.140000001, 0)
ScriptsFrame.Size = UDim2.new(0, 480, 0, 344)
ScriptsFrame.Visible = false

Admin.Name = "Admin"
Admin.Parent = ScriptsFrame
Admin.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
Admin.BorderColor3 = Color3.fromRGB(0, 0, 0)
Admin.BorderSizePixel = 0
Admin.Position = UDim2.new(0, 20, 0, 20)
Admin.Size = UDim2.new(0, 159, 0, 50)
Admin.Font = Enum.Font.SourceSansBold
Admin.Text = "Admin"
Admin.TextColor3 = Color3.fromRGB(0, 0, 0)
Admin.TextSize = 14.000

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(113, 53, 202)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.487101674, 0, 0.0858208984, 0)
TextButton.Size = UDim2.new(0, 34, 0, 31)
TextButton.Font = Enum.Font.SourceSansBold
TextButton.Text = "Open"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

-- Scripts:

local function WWREZYX_fake_script() -- JeuxButton.LocalScript 
	local script = Instance.new('LocalScript', JeuxButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = true
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
	end)
end
coroutine.wrap(WWREZYX_fake_script)()
local function IWQXWB_fake_script() -- ScriptsButton.LocalScript 
	local script = Instance.new('LocalScript', ScriptsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = true
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
	end)
end
coroutine.wrap(IWQXWB_fake_script)()
local function XRMZWC_fake_script() -- CreditsButton.LocalScript 
	local script = Instance.new('LocalScript', CreditsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
		script.Parent.Parent.Parent.CreditsFrame.Visible = true
	end)
end
coroutine.wrap(XRMZWC_fake_script)()
local function IQMU_fake_script() -- AnimalSimulator.LocalScript 
	local script = Instance.new('LocalScript', AnimalSimulator)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Golddeathninja/af/refs/heads/main/a"))()
	end)
end
coroutine.wrap(IQMU_fake_script)()
local function HVVPG_fake_script() -- BladebBall.LocalScript 
	local script = Instance.new('LocalScript', BladebBall)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://infernium.xyz/Blade.lua",true))()
	end)
end
coroutine.wrap(HVVPG_fake_script)()
local function FJSEUI_fake_script() -- CombatWarriors.LocalScript 
	local script = Instance.new('LocalScript', CombatWarriors)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://infernium.xyz/cwfree.lua",true))()
	end)
end
coroutine.wrap(FJSEUI_fake_script)()
local function WIZY_fake_script() -- Strongestbattlground.LocalScript 
	local script = Instance.new('LocalScript', Strongestbattlground)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://infernium.xyz/tsb.lua",true))()
	end)
end
coroutine.wrap(WIZY_fake_script)()
local function HXYNS_fake_script() -- Rivals.LocalScript 
	local script = Instance.new('LocalScript', Rivals)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/zeynwq/main/main/rivals1"))()()
	end)
end
coroutine.wrap(HXYNS_fake_script)()
local function XPSMGPN_fake_script() -- Admin.LocalScript 
	local script = Instance.new('LocalScript', Admin)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(XPSMGPN_fake_script)()
local function LHDXL_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
			script.Parent.Parent.Frame.Visible = not script.Parent.Parent.Frame.Visible
	end)
end
coroutine.wrap(LHDXL_fake_script)()
