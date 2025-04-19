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

local function FTNVAP_fake_script() -- JeuxButton.LocalScript 
	local script = Instance.new('LocalScript', JeuxButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = true
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
	end)
end
coroutine.wrap(FTNVAP_fake_script)()
local function HFILKZ_fake_script() -- ScriptsButton.LocalScript 
	local script = Instance.new('LocalScript', ScriptsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = false
		script.Parent.Parent.Parent.CreditsFrame.Visible = false
		script.Parent.Parent.Parent.ScriptsFrame.Visible = true
	end)
end
coroutine.wrap(HFILKZ_fake_script)()
local function JJWHEOW_fake_script() -- CreditsButton.LocalScript 
	local script = Instance.new('LocalScript', CreditsButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JeuxFrame.Visible = false
		script.Parent.Parent.Parent.CreditsFrame.Visible = true
		script.Parent.Parent.Parent.ScriptsFrame.Visible = false
	end)
end
coroutine.wrap(JJWHEOW_fake_script)()
local function TONRVCP_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(TONRVCP_fake_script)()
local function QMDQSAG_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		local arsenal = Instance.new("ScreenGui")
		local main = Instance.new("Frame")
		local arsenal_2 = Instance.new("TextLabel")
		local NoClip = Instance.new("TextButton")
		local UICorner = Instance.new("UICorner")
		local AimBot = Instance.new("TextButton")
		local UICorner_2 = Instance.new("UICorner")
		local ESP = Instance.new("TextButton")
		local UICorner_3 = Instance.new("UICorner")
	
		--Properties:
	
		arsenal.Name = "arsenal"
		arsenal.Parent = game.CoreGui
		arsenal.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
		main.Name = "main"
		main.Parent = arsenal
		main.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		main.BorderColor3 = Color3.fromRGB(0, 0, 0)
		main.BorderSizePixel = 0
		main.Position = UDim2.new(0.591141462, 0, 0, 0)
		main.Size = UDim2.new(0, 265, 0, 244)
		main.Active = true
		main.Draggable = true
	
		arsenal_2.Name = "arsenal"
		arsenal_2.Parent = main
		arsenal_2.BackgroundColor3 = Color3.fromRGB(61, 157, 20)
		arsenal_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
		arsenal_2.BorderSizePixel = 0
		arsenal_2.Size = UDim2.new(0, 265, 0, 50)
		arsenal_2.Font = Enum.Font.Unknown
		arsenal_2.Text = "Arsenal Script By Bone"
		arsenal_2.TextColor3 = Color3.fromRGB(0, 0, 0)
		arsenal_2.TextScaled = true
		arsenal_2.TextSize = 14.000
		arsenal_2.TextWrapped = true
	
		NoClip.Name = "NoClip"
		NoClip.Parent = main
		NoClip.BackgroundColor3 = Color3.fromRGB(58, 148, 19)
		NoClip.BorderColor3 = Color3.fromRGB(0, 0, 0)
		NoClip.BorderSizePixel = 0
		NoClip.Position = UDim2.new(0.120754719, 0, 0.247408062, 0)
		NoClip.Size = UDim2.new(0, 200, 0, 38)
		NoClip.Font = Enum.Font.FredokaOne
		NoClip.Text = "NoClip"
		NoClip.TextColor3 = Color3.fromRGB(0, 0, 0)
		NoClip.TextScaled = true
		NoClip.TextSize = 14.000
		NoClip.TextWrapped = true
		NoClip.MouseButton1Down:Connect(function()
			loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Noclip-Open-source-10442", true))() 
		end)
	
		UICorner.CornerRadius = UDim.new(0.200000003, 8)
		UICorner.Parent = NoClip
	
		AimBot.Name = "AimBot"
		AimBot.Parent = main
		AimBot.BackgroundColor3 = Color3.fromRGB(58, 148, 19)
		AimBot.BorderColor3 = Color3.fromRGB(0, 0, 0)
		AimBot.BorderSizePixel = 0
		AimBot.Position = UDim2.new(0.120754719, 0, 0.521998227, 0)
		AimBot.Size = UDim2.new(0, 200, 0, 38)
		AimBot.Font = Enum.Font.FredokaOne
		AimBot.Text = "Aimbot"
		AimBot.TextColor3 = Color3.fromRGB(0, 0, 0)
		AimBot.TextScaled = true
		AimBot.TextSize = 14.000
		AimBot.TextWrapped = true
		AimBot.MouseButton1Down:Connect(function()
			local teamCheck = false
			local fov = 150
			local smoothing = 1
	
			local RunService = game:GetService("RunService")
	
			local FOVring = Drawing.new("Circle")
			FOVring.Visible = true
			FOVring.Thickness = 1.5
			FOVring.Radius = fov
			FOVring.Transparency = 1
			FOVring.Color = Color3.fromRGB(255, 128, 128)
			FOVring.Position = workspace.CurrentCamera.ViewportSize/2
	
			local function getClosest(cframe)
				local ray = Ray.new(cframe.Position, cframe.LookVector).Unit
	
				local target = nil
				local mag = math.huge
	
				for i,v in pairs(game.Players:GetPlayers()) do
					if v.Character and v.Character:FindFirstChild("Head") and v.Character:FindFirstChild("Humanoid") and v.Character:FindFirstChild("HumanoidRootPart") and v ~= game.Players.LocalPlayer and (v.Team ~= game.Players.LocalPlayer.Team or (not teamCheck)) then
						local magBuf = (v.Character.Head.Position - ray:ClosestPoint(v.Character.Head.Position)).Magnitude
	
						if magBuf < mag then
							mag = magBuf
							target = v
						end
					end
				end
	
				return target
			end
	
			loop = RunService.RenderStepped:Connect(function()
				local UserInputService = game:GetService("UserInputService")
				local pressed = --[[UserInputService:IsKeyDown(Enum.KeyCode.E)]] UserInputService:IsMouseButtonPressed(Enum.UserInputType.MouseButton2) --Enum.UserInputType.MouseButton2
				local localPlay = game.Players.localPlayer.Character
				local cam = workspace.CurrentCamera
				local zz = workspace.CurrentCamera.ViewportSize/2
	
				if pressed then
					local Line = Drawing.new("Line")
					local curTar = getClosest(cam.CFrame)
					local ssHeadPoint = cam:WorldToScreenPoint(curTar.Character.Head.Position)
					ssHeadPoint = Vector2.new(ssHeadPoint.X, ssHeadPoint.Y)
					if (ssHeadPoint - zz).Magnitude < fov then
						workspace.CurrentCamera.CFrame = workspace.CurrentCamera.CFrame:Lerp(CFrame.new(cam.CFrame.Position, curTar.Character.Head.Position), smoothing)
					end
				end
	
				if UserInputService:IsKeyDown(Enum.KeyCode.Delete) then
					loop:Disconnect()
					FOVring:Remove()
				end
			end)
		end)
	
		UICorner_2.CornerRadius = UDim.new(0.200000003, 8)
		UICorner_2.Parent = AimBot
	
		ESP.Name = "ESP"
		ESP.Parent = main
		ESP.BackgroundColor3 = Color3.fromRGB(58, 148, 19)
		ESP.BorderColor3 = Color3.fromRGB(0, 0, 0)
		ESP.BorderSizePixel = 0
		ESP.Position = UDim2.new(0.098113209, 0, 0.776096582, 0)
		ESP.Size = UDim2.new(0, 200, 0, 38)
		ESP.Font = Enum.Font.FredokaOne
		ESP.Text = "ESP"
		ESP.TextColor3 = Color3.fromRGB(0, 0, 0)
		ESP.TextScaled = true
		ESP.TextSize = 14.000
		ESP.TextWrapped = true
		ESP.MouseButton1Down:Connect(function()
			local ESP = Instance.new("ScreenGui")
			local main = Instance.new("Frame")
			local ESPByBone = Instance.new("TextButton")
			local start = Instance.new("TextButton")
			local UICorner = Instance.new("UICorner")
	
			--Properties:
	
			ESP.Name = "ESP"
			ESP.Parent = game.CoreGui
	
			main.Name = "main"
			main.Parent = ESP
			main.BackgroundColor3 = Color3.fromRGB(159, 159, 159)
			main.BorderColor3 = Color3.fromRGB(0, 0, 0)
			main.BorderSizePixel = 0
			main.Position = UDim2.new(0.774011314, 0, 0.488188982, 0)
			main.Size = UDim2.new(0, 200, 0, 123)
			main.Active = true
			main.Draggable = true
	
			ESPByBone.Name = "ESP By Bone"
			ESPByBone.Parent = main
			ESPByBone.BackgroundColor3 = Color3.fromRGB(103, 103, 103)
			ESPByBone.BorderColor3 = Color3.fromRGB(0, 0, 0)
			ESPByBone.BorderSizePixel = 0
			ESPByBone.Position = UDim2.new(-0.000988464337, 0, -0.333813429, 0)
			ESPByBone.Size = UDim2.new(0, 200, 0, 50)
			ESPByBone.Font = Enum.Font.Unknown
			ESPByBone.Text = "ESP By Bone"
			ESPByBone.TextColor3 = Color3.fromRGB(0, 0, 0)
			ESPByBone.TextScaled = true
			ESPByBone.TextSize = 30.000
			ESPByBone.TextWrapped = true
	
			start.Name = "start"
			start.Parent = main
			start.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			start.BorderColor3 = Color3.fromRGB(0, 0, 0)
			start.BorderSizePixel = 0
			start.Position = UDim2.new(0.184954524, 0, 0.290762544, 0)
			start.Size = UDim2.new(0, 126, 0, 50)
			start.Font = Enum.Font.Unknown
			start.Text = "START"
			start.TextColor3 = Color3.fromRGB(0, 0, 0)
			start.TextScaled = true
			start.TextSize = 14.000
			start.TextWrapped = true
			start.MouseButton1Down:Connect(function()
				local color = BrickColor.new(50,0,250)
				local transparency = .8
	
				local Players = game:GetService("Players")
				local function _ESP(c)
					repeat wait() until c.PrimaryPart ~= nil
					for i,p in pairs(c:GetChildren()) do
						if p.ClassName == "Part" or p.ClassName == "MeshPart" then
							if p:FindFirstChild("shit") then p.shit:Destroy() end
							local a = Instance.new("BoxHandleAdornment",p)
							a.Name = "shit"
							a.Size = p.Size
							a.Color = color
							a.Transparency = transparency
							a.AlwaysOnTop = true    
							a.Visible = true    
							a.Adornee = p
							a.ZIndex = true    
	
						end
					end
				end
				local function ESP()
					for i,v in pairs(Players:GetChildren()) do
						if v ~= game.Players.LocalPlayer then
							if v.Character then
								_ESP(v.Character)
							end
							v.CharacterAdded:Connect(function(chr)
								_ESP(chr)
							end)
						end
					end
					Players.PlayerAdded:Connect(function(player)
						player.CharacterAdded:Connect(function(chr)
							_ESP(chr)
						end)  
					end)
				end
				ESP()
			end)
	
			UICorner.CornerRadius = UDim.new(0.200000003, 8)
			UICorner.Parent = start
	
		end)
	
		UICorner_3.CornerRadius = UDim.new(0.200000003, 8)
		UICorner_3.Parent = ESP
	
	end)
end
coroutine.wrap(QMDQSAG_fake_script)()
local function BSBPS_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Golddeathninja/af/refs/heads/main/a"))()
	end)
end
coroutine.wrap(BSBPS_fake_script)()
local function JSAU_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://infernium.xyz/cwfree.lua",true))()
	end)
end
coroutine.wrap(JSAU_fake_script)()
local function JUOKWHP_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/zeynwq/main/main/rivals1"))()()
	end)
end
coroutine.wrap(JUOKWHP_fake_script)()
local function JWJWZG_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.gui.Visible = not script.Parent.Parent.gui.Visible
	end)
end
coroutine.wrap(JWJWZG_fake_script)()
