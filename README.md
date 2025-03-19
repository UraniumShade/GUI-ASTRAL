-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local astral = Instance.new("Frame")
local TopBar = Instance.new("Frame")
local SideBar = Instance.new("Frame")
local ScriptsButton = Instance.new("TextButton")
local CreditsButton = Instance.new("TextButton")
local SettingsButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local CreditsFarme = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local ScriptsFarme = Instance.new("Frame")
local animals = Instance.new("TextButton")
local rivals = Instance.new("TextButton")
local admin = Instance.new("TextButton")
local SettingsFarme = Instance.new("Frame")
local TextLabel_4 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

astral.Name = "astral"
astral.Parent = ScreenGui
astral.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
astral.BorderColor3 = Color3.fromRGB(0, 0, 0)
astral.BorderSizePixel = 0
astral.Position = UDim2.new(0.237082064, 0, 0.24626866, 0)
astral.Size = UDim2.new(0, 691, 0, 377)
astral.Visible = false

TopBar.Name = "TopBar"
TopBar.Parent = astral
TopBar.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TopBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
TopBar.BorderSizePixel = 0
TopBar.Size = UDim2.new(0, 691, 0, 66)

SideBar.Name = "SideBar"
SideBar.Parent = astral
SideBar.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SideBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideBar.BorderSizePixel = 0
SideBar.Size = UDim2.new(0, 164, 0, 377)

ScriptsButton.Name = "ScriptsButton"
ScriptsButton.Parent = SideBar
ScriptsButton.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
ScriptsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsButton.BorderSizePixel = 0
ScriptsButton.Position = UDim2.new(0, 0, 0.175066307, 0)
ScriptsButton.Size = UDim2.new(0, 164, 0, 50)
ScriptsButton.Font = Enum.Font.SourceSansItalic
ScriptsButton.Text = "Scripts"
ScriptsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ScriptsButton.TextScaled = true
ScriptsButton.TextSize = 14.000
ScriptsButton.TextWrapped = true

CreditsButton.Name = "CreditsButton"
CreditsButton.Parent = SideBar
CreditsButton.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
CreditsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsButton.BorderSizePixel = 0
CreditsButton.Position = UDim2.new(0, 0, 0.307692319, 0)
CreditsButton.Size = UDim2.new(0, 164, 0, 50)
CreditsButton.Font = Enum.Font.SourceSansItalic
CreditsButton.Text = "Credits"
CreditsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CreditsButton.TextScaled = true
CreditsButton.TextSize = 14.000
CreditsButton.TextWrapped = true

SettingsButton.Name = "SettingsButton"
SettingsButton.Parent = SideBar
SettingsButton.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SettingsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
SettingsButton.BorderSizePixel = 0
SettingsButton.Position = UDim2.new(0, 0, 0.440318316, 0)
SettingsButton.Size = UDim2.new(0, 164, 0, 50)
SettingsButton.Font = Enum.Font.SourceSansItalic
SettingsButton.Text = "Settings"
SettingsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SettingsButton.TextScaled = true
SettingsButton.TextSize = 14.000
SettingsButton.TextWrapped = true

TextLabel.Parent = astral
TextLabel.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 184, 0, 66)
TextLabel.Font = Enum.Font.SourceSansItalic
TextLabel.Text = "GUI/ASTRAL"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

CreditsFarme.Name = "CreditsFarme"
CreditsFarme.Parent = astral
CreditsFarme.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
CreditsFarme.BorderColor3 = Color3.fromRGB(0, 0, 0)
CreditsFarme.BorderSizePixel = 0
CreditsFarme.Position = UDim2.new(0.237337187, 0, 0.175066307, 0)
CreditsFarme.Size = UDim2.new(0, 527, 0, 311)
CreditsFarme.Visible = false

TextLabel_2.Parent = CreditsFarme
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSansItalic
TextLabel_2.Text = "Made By ASTRAL:"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = CreditsFarme
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 0.192926049, 0)
TextLabel_3.Size = UDim2.new(0, 527, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSansItalic
TextLabel_3.Text = "https://discord.gg/WAEkyKqted"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

ScriptsFarme.Name = "ScriptsFarme"
ScriptsFarme.Parent = astral
ScriptsFarme.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
ScriptsFarme.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptsFarme.BorderSizePixel = 0
ScriptsFarme.Position = UDim2.new(0.237337187, 0, 0.175066307, 0)
ScriptsFarme.Size = UDim2.new(0, 527, 0, 311)
ScriptsFarme.Visible = false

animals.Name = "animals"
animals.Parent = ScriptsFarme
animals.BackgroundColor3 = Color3.fromRGB(112, 112, 112)
animals.BorderColor3 = Color3.fromRGB(0, 0, 0)
animals.BorderSizePixel = 0
animals.Position = UDim2.new(0, 20, 0, 20)
animals.Size = UDim2.new(0, 146, 0, 50)
animals.Font = Enum.Font.SourceSansItalic
animals.Text = "Animal Simulator"
animals.TextColor3 = Color3.fromRGB(255, 255, 255)
animals.TextScaled = true
animals.TextSize = 14.000
animals.TextWrapped = true

rivals.Name = "rivals"
rivals.Parent = ScriptsFarme
rivals.BackgroundColor3 = Color3.fromRGB(112, 112, 112)
rivals.BorderColor3 = Color3.fromRGB(0, 0, 0)
rivals.BorderSizePixel = 0
rivals.Position = UDim2.new(0, 190, 0, 20)
rivals.Size = UDim2.new(0, 146, 0, 50)
rivals.Font = Enum.Font.SourceSansItalic
rivals.Text = "Rivals"
rivals.TextColor3 = Color3.fromRGB(255, 255, 255)
rivals.TextScaled = true
rivals.TextSize = 14.000
rivals.TextWrapped = true

admin.Name = "admin"
admin.Parent = ScriptsFarme
admin.BackgroundColor3 = Color3.fromRGB(112, 112, 112)
admin.BorderColor3 = Color3.fromRGB(0, 0, 0)
admin.BorderSizePixel = 0
admin.Position = UDim2.new(0, 364, 0, 20)
admin.Size = UDim2.new(0, 146, 0, 50)
admin.Font = Enum.Font.SourceSansItalic
admin.Text = "Admin"
admin.TextColor3 = Color3.fromRGB(255, 255, 255)
admin.TextScaled = true
admin.TextSize = 14.000
admin.TextWrapped = true

SettingsFarme.Name = "SettingsFarme"
SettingsFarme.Parent = astral
SettingsFarme.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
SettingsFarme.BorderColor3 = Color3.fromRGB(0, 0, 0)
SettingsFarme.BorderSizePixel = 0
SettingsFarme.Position = UDim2.new(0.237337187, 0, 0.175066307, 0)
SettingsFarme.Size = UDim2.new(0, 527, 0, 311)
SettingsFarme.Visible = false

TextLabel_4.Parent = SettingsFarme
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Size = UDim2.new(0, 200, 0, 50)
TextLabel_4.Font = Enum.Font.SourceSansItalic
TextLabel_4.Text = "Settings:"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(189, 0, 0)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.00683890563, 0, 0.536069632, 0)
TextButton.Size = UDim2.new(0, 68, 0, 50)
TextButton.Font = Enum.Font.Unknown
TextButton.Text = "x"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

-- Scripts:

local function NCVQL_fake_script() -- ScriptsButton.LocalScript 
	local script = Instance.new('LocalScript', ScriptsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.CreditsFarme.Visible = false
		script.Parent.Parent.Parent.ScriptsFarme.Visible = true
		script.Parent.Parent.Parent.SettingsFarme.Visible = false
	end)
end
coroutine.wrap(NCVQL_fake_script)()
local function CUICOOE_fake_script() -- CreditsButton.LocalScript 
	local script = Instance.new('LocalScript', CreditsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.CreditsFarme.Visible = true
		script.Parent.Parent.Parent.ScriptsFarme.Visible = false
		script.Parent.Parent.Parent.SettingsFarme.Visible = false
	end)
end
coroutine.wrap(CUICOOE_fake_script)()
local function JQOQM_fake_script() -- SettingsButton.LocalScript 
	local script = Instance.new('LocalScript', SettingsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.CreditsFarme.Visible = false
		script.Parent.Parent.Parent.ScriptsFarme.Visible = false
		script.Parent.Parent.Parent.SettingsFarme.Visible = true
	end)
end
coroutine.wrap(JQOQM_fake_script)()
local function AUGWZNH_fake_script() -- animals.LocalScript 
	local script = Instance.new('LocalScript', animals)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Kylan83728/V2/refs/heads/main/README.md"))()
	end)
end
coroutine.wrap(AUGWZNH_fake_script)()
local function JWLEL_fake_script() -- rivals.LocalScript 
	local script = Instance.new('LocalScript', rivals)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/zeynwq/main/main/rivals1"))()()
	end)
end
coroutine.wrap(JWLEL_fake_script)()
local function KALQTQ_fake_script() -- admin.LocalScript 
	local script = Instance.new('LocalScript', admin)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(KALQTQ_fake_script)()
local function IIDAJ_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.astral.Visible = not script.Parent.Parent.astral.Visible
	end)
end
coroutine.wrap(IIDAJ_fake_script)()
