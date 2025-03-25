local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Workspace = game:GetService("Workspace")
local RunService = game:GetService("RunService")

-- Wait for the player to load
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Find the "Right Arm" part inside the player's character
local rightArm = character:WaitForChild("Right Arm")
if not rightArm then
    error("Right Arm part not found in player character")
end

-- Check for Resources folder in ReplicatedStorage
local resourcesFolder = ReplicatedStorage:WaitForChild("Resources")

-- Check for KJEffects folder inside Resources
local vanishingKickFolder = resourcesFolder:WaitForChild("VanishingKick")

-- Check for speedlinesandstuff part inside KJEffects
local speedlinesandstuffPart = vanishingKickFolder:WaitForChild("Trail2")

-- Duplicate the speedlinesandstuff part
local speedlinesandstuffClone = speedlinesandstuffPart:Clone()

-- Put the duplicate in Workspace
speedlinesandstuffClone.Parent = Workspace

-- Set the position to the Right Arm initially
speedlinesandstuffClone.CFrame = rightArm.CFrame

-- Function to enable all ParticleEmitters
local function enableParticleEmitters(parent)
    for _, descendant in ipairs(parent:GetDescendants()) do
        if descendant:IsA("ParticleEmitter") then
            descendant.Enabled = true
        end
    end
end

-- Update the clone's position every frame
RunService.RenderStepped:Connect(function()
    if character and rightArm then
        speedlinesandstuffClone.CFrame = rightArm.CFrame
    end
end)

-- Example usage after your dash effect completes
spawn(function()
    -- Simulating end of dash effect
    wait(0)  -- Adjust the wait time as needed

    -- Enable all ParticleEmitters inside speedlinesandstuffClone
    enableParticleEmitters(speedlinesandstuffClone)
end)

local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Workspace = game:GetService("Workspace")
local RunService = game:GetService("RunService")

-- Wait for the player to load
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Find the "Right Arm" part inside the player's character
local rightArm = character:WaitForChild("Left Arm")
if not rightArm then
    error("Right Arm part not found in player character")
end

-- Check for Resources folder in ReplicatedStorage
local resourcesFolder = ReplicatedStorage:WaitForChild("Resources")

-- Check for KJEffects folder inside Resources
local vanishingKickFolder = resourcesFolder:WaitForChild("VanishingKick")

-- Check for speedlinesandstuff part inside KJEffects
local speedlinesandstuffPart = vanishingKickFolder:WaitForChild("Trail2")

-- Duplicate the speedlinesandstuff part
local speedlinesandstuffClone = speedlinesandstuffPart:Clone()

-- Put the duplicate in Workspace
speedlinesandstuffClone.Parent = Workspace

-- Set the position to the Right Arm initially
speedlinesandstuffClone.CFrame = rightArm.CFrame

-- Function to enable all ParticleEmitters
local function enableParticleEmitters(parent)
    for _, descendant in ipairs(parent:GetDescendants()) do
        if descendant:IsA("ParticleEmitter") then
            descendant.Enabled = true
        end
    end
end

-- Update the clone's position every frame
RunService.RenderStepped:Connect(function()
    if character and rightArm then
        speedlinesandstuffClone.CFrame = rightArm.CFrame
    end
end)

-- Example usage after your dash effect completes
spawn(function()
    -- Simulating end of dash effect
    wait(0)  -- Adjust the wait time as needed

    -- Enable all ParticleEmitters inside speedlinesandstuffClone
    enableParticleEmitters(speedlinesandstuffClone)
end)

local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Workspace = game:GetService("Workspace")
local RunService = game:GetService("RunService")

-- Wait for the player to load
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Find the "Right Arm" part inside the player's character
local rightArm = character:WaitForChild("Right Leg")
if not rightArm then
    error("Right Arm part not found in player character")
end

-- Check for Resources folder in ReplicatedStorage
local resourcesFolder = ReplicatedStorage:WaitForChild("Resources")

-- Check for KJEffects folder inside Resources
local vanishingKickFolder = resourcesFolder:WaitForChild("VanishingKick")

-- Check for speedlinesandstuff part inside KJEffects
local speedlinesandstuffPart = vanishingKickFolder:WaitForChild("Trail2")

-- Duplicate the speedlinesandstuff part
local speedlinesandstuffClone = speedlinesandstuffPart:Clone()

-- Put the duplicate in Workspace
speedlinesandstuffClone.Parent = Workspace

-- Set the position to the Right Arm initially
speedlinesandstuffClone.CFrame = rightArm.CFrame

-- Function to enable all ParticleEmitters
local function enableParticleEmitters(parent)
    for _, descendant in ipairs(parent:GetDescendants()) do
        if descendant:IsA("ParticleEmitter") then
            descendant.Enabled = true
        end
    end
end

-- Update the clone's position every frame
RunService.RenderStepped:Connect(function()
    if character and rightArm then
        speedlinesandstuffClone.CFrame = rightArm.CFrame
    end
end)

-- Example usage after your dash effect completes
spawn(function()
    -- Simulating end of dash effect
    wait(0)  -- Adjust the wait time as needed

    -- Enable all ParticleEmitters inside speedlinesandstuffClone
    enableParticleEmitters(speedlinesandstuffClone)
end)

local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Workspace = game:GetService("Workspace")
local RunService = game:GetService("RunService")

-- Wait for the player to load
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Find the "Right Arm" part inside the player's character
local rightArm = character:WaitForChild("Left Leg")
if not rightArm then
    error("Right Arm part not found in player character")
end

-- Check for Resources folder in ReplicatedStorage
local resourcesFolder = ReplicatedStorage:WaitForChild("Resources")

-- Check for KJEffects folder inside Resources
local vanishingKickFolder = resourcesFolder:WaitForChild("VanishingKick")

-- Check for speedlinesandstuff part inside KJEffects
local speedlinesandstuffPart = vanishingKickFolder:WaitForChild("Trail2")

-- Duplicate the speedlinesandstuff part
local speedlinesandstuffClone = speedlinesandstuffPart:Clone()

-- Put the duplicate in Workspace
speedlinesandstuffClone.Parent = Workspace

-- Set the position to the Right Arm initially
speedlinesandstuffClone.CFrame = rightArm.CFrame

-- Function to enable all ParticleEmitters
local function enableParticleEmitters(parent)
    for _, descendant in ipairs(parent:GetDescendants()) do
        if descendant:IsA("ParticleEmitter") then
            descendant.Enabled = true
        end
    end
end

-- Update the clone's position every frame
RunService.RenderStepped:Connect(function()
    if character and rightArm then
        speedlinesandstuffClone.CFrame = rightArm.CFrame
    end
end)


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Galactic Slam"

local FillColor = Color3.fromRGB(175, 25, 255)
local DepthMode = "AlwaysOnTop"
local FillTransparency = 0.5
local OutlineColor = Color3.fromRGB(255, 255, 255)
local OutlineTransparency = 0

local CoreGui = game:FindService("CoreGui")
local Players = game:FindService("Players")
local lp = Players.LocalPlayer
local connections = {}

local Storage = Instance.new("Folder")
Storage.Parent = CoreGui
Storage.Name = "Highlight_Storage"

local function Highlight(plr)
    -- Skip highlighting the local player
    if plr == lp then
        return
    end
    
    local Highlight = Instance.new("Highlight")
    Highlight.Name = plr.Name
    Highlight.FillColor = FillColor
    Highlight.DepthMode = DepthMode
    Highlight.FillTransparency = FillTransparency
    Highlight.OutlineColor = OutlineColor
    Highlight.OutlineTransparency = 0
    Highlight.Parent = Storage
    
    local plrchar = plr.Character
    if plrchar then
        Highlight.Adornee = plrchar
    end

    connections[plr] = plr.CharacterAdded:Connect(function(char)
        Highlight.Adornee = char
    end)
end

Players.PlayerAdded:Connect(Highlight)
for i, v in next, Players:GetPlayers() do
    Highlight(v)
end

Players.PlayerRemoving:Connect(function(plr)
    local plrname = plr.Name
    if Storage[plrname] then
        Storage[plrname]:Destroy()
    end
    if connections[plr] then
        connections[plr]:Disconnect()
    end
end)


local targetAnimations = {
    [12342141464] = true
}

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:FindFirstChildOfClass("Animator")

local function onAnimationPlayed(track)
    if track and track.Animation then
        local animId = tonumber(track.Animation.AnimationId:match("%d+"))
        if targetAnimations[animId] then
            print("Target animation is playing:", animId)
            -- Add any action you want to trigger here

task.spawn(function()
wait(2.4)

_G.HackedWalkSpeed = 100

local Plrs = game:GetService("Players")

local MyPlr = Plrs.LocalPlayer
local MyChar = MyPlr.Character

if MyChar then
local Hum = MyChar.Humanoid
Hum.Changed:connect(function()
Hum.WalkSpeed = _G.HackedWalkSpeed
end)
Hum.WalkSpeed = _G.HackedWalkSpeed
end


MyPlr.CharacterAdded:connect(function(Char)
MyChar = Char
repeat wait() until Char:FindFirstChild("Humanoid")
local Hum = Char.Humanoid
Hum.Changed:connect(function()
Hum.WalkSpeed = _G.HackedWalkSpeed
end)
Hum.WalkSpeed = _G.HackedWalkSpeed
end)


local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local LocalPlayer = Players.LocalPlayer
local Character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()

local orangeColor = ColorSequence.new(Color3.fromRGB(255, 165, 0)) -- Orange color sequence

-- Function to apply particle effects
local function applyEffects(effect, parent)
    local clonedEffect = effect:Clone()
    clonedEffect.Parent = parent

    for _, child in ipairs(clonedEffect:GetChildren()) do
        if child:IsA("ParticleEmitter") then
            child.Color = orangeColor -- Apply orange color
            child:Emit(20) -- Emit particles
        end
    end
end

-- Apply effects to character limbs
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Right Arm"])
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Left Arm"])
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Right Leg"])
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Left Leg"])

-- Apply other special effects
local spin1 = ReplicatedStorage.Resources.WhirlwindDrop["CharFX"].Spin:Clone()
spin1.Parent = Character["Torso"]
for _, child in ipairs(spin1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = orangeColor
        child:Emit(1)
    end
end

local wow1 = ReplicatedStorage.Resources.Dragon["Complete"].Part.Debri:Clone()
wow1.Parent = Character["Torso"]
for _, child in ipairs(wow1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = orangeColor
        child:Emit(1)
    end
end

local wind1 = ReplicatedStorage.Resources.Dragon["Stretch"].Part.Attachment:Clone()
wind1.Parent = Character["Torso"]
for _, child in ipairs(wind1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = orangeColor
        child:Emit(1)
    end
end

local r = game:GetService("ReplicatedStorage")
local p = game:GetService("Players").LocalPlayer

local function m()
    local a = r:FindFirstChild("Resources")
    if not a then return end

    local b = a:FindFirstChild("KJEffects")
    if not b then return end

    local c = b:FindFirstChild("KJWallCombo")
    if not c then return end

    local d = c:FindFirstChild("UserAura")
    if not d or not d:IsA("Folder") then return end

    local e = p.Character:FindFirstChild("Torso")
    if not e then return end

    for _, f in pairs(d:GetChildren()) do
        if f:IsA("ParticleEmitter") then
            local g = f:Clone()
            g.Parent = e
            g.Enabled = true
            g.Rate = 50
            g.Color = ColorSequence.new(Color3.fromRGB(255, 255, 0), Color3.fromRGB(255, 0, 0)) -- Yellow to Red
            g:Emit(2)
        end
    end
end

m()

message = "LETS SEE HOW FAST YOU CAN REALLY GO!"
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(message, "All")

task.spawn(function()
    local player = game.Players.LocalPlayer
    local gui = player.PlayerGui
    local ulttext = gui.ScreenGui.MagicHealth.TextLabel
    
    local textToDisplay = "HOW FAST YOU REALLY GO!"
    ulttext.Text = ""
    
    local function typeText()
        for i = 1, #textToDisplay do
            ulttext.Text = string.sub(textToDisplay, 1, i)
            wait(0.08)
        end
    end
    
    typeText()
end)

local Players = game:GetService("Players")

local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:FindFirstChildOfClass("Humanoid")

local animation = Instance.new("Animation")
animation.AnimationId = "rbxassetid://107649573628906"

local animator = humanoid:FindFirstChildOfClass("Animator") or humanoid:WaitForChild("Animator")
local animationTrack = animator:LoadAnimation(animation)

animationTrack:Play()

local cutscene = {
    {
        ["Fov"] = 27.970972,
        ["Cf"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    },
    {
        ["Fov"] = 64.259003,
        ["Cf"] = CFrame.new(10.8081207, -0.502416134, -10.826313, -0.707994938, 0.129311532, 0.694277883, 0.00613992475, 0.984183669, -0.17704615, -0.706190944, -0.121084973, -0.697590947)
    },
    {
        ["Fov"] = 65.533081,
        ["Cf"] = CFrame.new(11.7703934, -0.673327446, -11.8103333, -0.708368421, 0.152597368, 0.689150453, 0.0167147536, 0.979703784, -0.19975321, -0.705645084, -0.129979879, -0.696541846)
    },
    {
        ["Fov"] = 67.304329,
        ["Cf"] = CFrame.new(12.6180573, -0.771639347, -12.6995583, -0.710067749, 0.168161497, 0.683758438, 0.0281375907, 0.977064669, -0.211076051, -0.703571081, -0.130639002, -0.698513746)
    },
    {
        ["Fov"] = 67.910591,
        ["Cf"] = CFrame.new(13.3650208, -0.856769562, -13.4971123, -0.712058544, 0.180501357, 0.678521812, 0.0399526581, 0.975240588, -0.217507526, -0.700982571, -0.127769366, -0.70164001)
    },
    {
        ["Fov"] = 68.580093,
        ["Cf"] = CFrame.new(13.9964142, -0.944493294, -14.2172775, -0.717524827, 0.190816239, 0.669886053, 0.054693751, 0.974208891, -0.218918949, -0.694382429, -0.120441221, -0.709455609)
    },
    {
        ["Fov"] = 69.041924,
        ["Cf"] = CFrame.new(14.5266571, -1.03716707, -14.8564072, -0.727027237, 0.202212915, 0.65615654, 0.0681833923, 0.97218734, -0.224058852, -0.683214843, -0.118157946, -0.720594466)
    },
    {
        ["Fov"] = 69.360504,
        ["Cf"] = CFrame.new(14.9791718, -1.10005665, -15.4269371, -0.738218963, 0.214151263, 0.639665604, 0.0811935812, 0.969583988, -0.230900258, -0.669657052, -0.118518226, -0.733152926)
    },
    {
        ["Fov"] = 69.580269,
        ["Cf"] = CFrame.new(15.3265305, -1.15132952, -15.90588, -0.751181901, 0.228688598, 0.619215071, 0.0960026532, 0.965944707, -0.240280077, -0.653076887, -0.121047743, -0.747554839)
    },
    {
        ["Fov"] = 69.731865,
        ["Cf"] = CFrame.new(15.5896454, -1.17020035, -16.2873535, -0.759589553, 0.246826231, 0.601748049, 0.116690576, 0.961898208, -0.247254372, -0.639849424, -0.117593527, -0.759450257)
    },
    {
        ["Fov"] = 69.836441,
        ["Cf"] = CFrame.new(15.7742462, -1.1828866, -16.5839424, -0.765350342, 0.266871601, 0.585677803, 0.140329689, 0.957282722, -0.252818555, -0.628129482, -0.111306779, -0.770106792)
    },
    {
        ["Fov"] = 69.908577,
        ["Cf"] = CFrame.new(15.8650742, -1.12548351, -16.7807426, -0.76652199, 0.292486131, 0.571748197, 0.171929389, 0.951233089, -0.256117523, -0.61877656, -0.0980194286, -0.779428005)
    },
    {
        ["Fov"] = 69.958336,
        ["Cf"] = CFrame.new(15.8203888, -1.08389187, -16.8257599, -0.766388535, 0.314291596, 0.560240448, 0.198658049, 0.945343316, -0.258574963, -0.610887527, -0.0868726522, -0.786936939)
    },
    {
        ["Fov"] = 69.992653,
        ["Cf"] = CFrame.new(15.563736, -1.25737619, -16.6189194, -0.769928813, 0.308262765, 0.558734119, 0.209005445, 0.9491027, -0.23562856, -0.602931559, -0.0646387339, -0.795170188)
    },
    {
        ["Fov"] = 69.230766,
        ["Cf"] = CFrame.new(15.2608414, -1.43158245, -16.3740654, -0.773820162, 0.301207811, 0.557203889, 0.220946908, 0.952800572, -0.208214328, -0.593620062, -0.0380080119, -0.803847551)
    },
    {
        ["Fov"] = 67.692307,
        ["Cf"] = CFrame.new(14.904007, -1.7115202, -15.9243965, -0.787560821, 0.231876522, 0.570947766, 0.17700012, 0.972583592, -0.150838509, -0.590270281, -0.0177366883, -0.807010889)
    },
    {
        ["Fov"] = 66.923080,
        ["Cf"] = CFrame.new(14.5469437, -2.00666881, -15.4749031, -0.795743763, 0.161347479, 0.583745539, 0.131958574, 0.986892581, -0.0928956866, -0.591082811, 0.00310906768, -0.806605041)
    },
    {
        ["Fov"] = 66.153854,
        ["Cf"] = CFrame.new(14.4835968, -2.00775814, -15.3614845, -0.79512006, 0.128433287, 0.592696369, 0.101816431, 0.991716385, -0.0783083811, -0.597844064, -0.00191833824, -0.801610231)
    },
    {
        ["Fov"] = 65.769234,
        ["Cf"] = CFrame.new(14.4096222, -2.01390457, -15.2292213, -0.792421997, 0.0901243389, 0.603278577, 0.0668043345, 0.995898366, -0.0610288642, -0.606304109, -0.00805898197, -0.795192182)
    },
    {
        ["Fov"] = 64.230774,
        ["Cf"] = CFrame.new(14.318512, -1.99183702, -15.0457153, -0.779327571, 0.0238237623, 0.62616384, 0.00313025899, 0.999412775, -0.0341288671, -0.626609147, -0.0246375203, -0.778944373)
    },
    {
        ["Fov"] = 63.461540,
        ["Cf"] = CFrame.new(14.4232559, -1.91543436, -15.0952148, -0.76957953, 0.00873400085, 0.638491273, -0.0184506848, 0.999184906, -0.0359067507, -0.638284445, -0.0394137055, -0.76879108)
    },
    {
        ["Fov"] = 62.307686,
        ["Cf"] = CFrame.new(14.6165695, -1.74282455, -15.1774673, -0.75162077, -0.0162743218, 0.65939486, -0.0550649613, 0.997753978, -0.0381413288, -0.6572932, -0.0649773777, -0.750828803)
    },
    {
        ["Fov"] = 60.769230,
        ["Cf"] = CFrame.new(14.8363495, -1.58736324, -15.2340126, -0.739448905, -0.0334731527, 0.67238003, -0.0807801187, 0.995958805, -0.0392559357, -0.66834867, -0.0833427235, -0.73916465)
    },
    {
        ["Fov"] = 60.000000,
        ["Cf"] = CFrame.new(14.8941498, -1.53058624, -15.2562637, -0.73821187, -0.0344858393, 0.673686862, -0.0823795348, 0.995826185, -0.0392936915, -0.66952008, -0.0845051035, -0.737971544)
    },
    {
        ["Fov"] = 59.230774,
        ["Cf"] = CFrame.new(14.952301, -1.45138931, -15.2782364, -0.73696965, -0.035495013, 0.674993336, -0.0839771479, 0.995691597, -0.0393285789, -0.670689166, -0.0856679901, -0.736775041)
    },
    {
        ["Fov"] = 58.076927,
        ["Cf"] = CFrame.new(14.9921951, -1.30545187, -15.3185616, -0.739975572, -0.0284916535, 0.672030091, -0.0736767501, 0.996523798, -0.0388768055, -0.668586612, -0.0782808959, -0.739502788)
    },
    {
        ["Fov"] = 56.538460,
        ["Cf"] = CFrame.new(14.6447754, -1.24066639, -15.1958199, -0.766976416, 0.00573092327, 0.641649842, -0.0415608063, 0.997416794, -0.0585869066, -0.640328169, -0.07160227, -0.764757037)
    },
    {
        ["Fov"] = 55.384617,
        ["Cf"] = CFrame.new(14.2674103, -1.15983582, -15.0803375, -0.799400985, 0.0358479396, 0.599727511, -0.00975623541, 0.99731195, -0.0726175234, -0.600718737, -0.0639016256, -0.796902657)
    },
    {
        ["Fov"] = 53.846153,
        ["Cf"] = CFrame.new(13.6104126, -1.06216145, -14.9520149, -0.866534591, 0.0683175027, 0.494419456, 0.0380673297, 0.996748686, -0.0710100234, -0.497663349, -0.0427114181, -0.866318166)
    },
    {
        ["Fov"] = 53.461540,
        ["Cf"] = CFrame.new(13.270462, -1.03200197, -14.8993874, -0.896949053, 0.0840258077, 0.434076101, 0.0615268126, 0.995943785, -0.0656533763, -0.437832087, -0.0321804248, -0.898480892)
    },
    {
        ["Fov"] = 52.692307,
        ["Cf"] = CFrame.new(12.6549835, -0.980675697, -14.8874626, -0.94923389, 0.0966441631, 0.299357742, 0.0892132521, 0.995270789, -0.0384252705, -0.30165574, -0.00976790674, -0.953367054)
    },
    {
        ["Fov"] = 51.153847,
        ["Cf"] = CFrame.new(11.5276794, -0.908441544, -14.6725883, -0.989604831, 0.128092095, -0.0653809905, 0.127225503, 0.991723537, 0.0172672756, 0.0670516491, 0.00876966119, -0.997711062)
    },
    {
        ["Fov"] = 50.384617,
        ["Cf"] = CFrame.new(11.0359344, -0.905107498, -14.3252411, -0.923796773, 0.136252612, -0.357819438, 0.132539645, 0.990559101, 0.0350081325, 0.359211385, -0.0150848925, -0.933134437)
    },
    {
        ["Fov"] = 50.006069,
        ["Cf"] = CFrame.new(10.0580215, -0.907943249, -13.5822868, -0.563391507, 0.130489916, -0.815820038, 0.129919007, 0.989155948, 0.0684950054, 0.815911174, -0.0674010441, -0.57423526)
    },
    {
        ["Fov"] = 50.011608,
        ["Cf"] = CFrame.new(9.5418396, -0.904420853, -12.798317, -0.338790387, 0.0783484429, -0.937594056, 0.0966827497, 0.994150221, 0.0481391139, 0.935881257, -0.0743401125, -0.344383597)
    },
    {
        ["Fov"] = 50.055172,
        ["Cf"] = CFrame.new(8.70063782, -0.446689606, -11.6049385, 0.00465261936, -0.000322766602, -0.999989152, 0.053229548, 0.998582304, -7.46585429e-05, 0.998571634, -0.0532286465, 0.00466316938)
    },
    {
        ["Fov"] = 50.090485,
        ["Cf"] = CFrame.new(8.85921478, -0.35545063, -11.7612648, 0.064419657, -0.052367419, -0.996547937, 0.00907399133, 0.998611629, -0.0518893078, 0.997881651, -0.00569998473, 0.0648053885)
    },
    {
        ["Fov"] = 50.142384,
        ["Cf"] = CFrame.new(8.88998413, -0.429722786, -11.7941322, 0.100163251, -0.0810249001, -0.991666436, -0.0163573846, 0.996409953, -0.0830646455, 0.994836688, 0.0245410949, 0.0984783471)
    },
    {
        ["Fov"] = 50.218662,
        ["Cf"] = CFrame.new(8.86323547, -0.539336681, -11.770359, 0.138256222, -0.103375904, -0.984986544, -0.0281046443, 0.993727624, -0.108238153, 0.989997804, 0.042647291, 0.134483725)
    },
    {
        ["Fov"] = 50.330769,
        ["Cf"] = CFrame.new(8.83392334, -0.596874714, -11.7425919, 0.156836182, -0.112997726, -0.981139183, -0.0209675916, 0.99282825, -0.117695659, 0.987402201, 0.0390310623, 0.153342038)
    },
    {
        ["Fov"] = 50.495537,
        ["Cf"] = CFrame.new(8.83354187, -0.623363018, -11.7429352, 0.167182237, -0.122420594, -0.978296161, 0.00232371036, 0.992307305, -0.123776793, 0.985923409, 0.0184199885, 0.16618067)
    },
    {
        ["Fov"] = 50.605000,
        ["Cf"] = CFrame.new(8.8227005, -0.616311073, -11.7318916, 0.173225254, -0.123523869, -0.977105498, 0.0113328341, 0.992288053, -0.123434097, 0.984817266, 0.0103085116, 0.17328915)
    },
    {
        ["Fov"] = 50.898582,
        ["Cf"] = CFrame.new(8.77226257, -0.575282097, -11.6802483, 0.192494482, -0.120549709, -0.973865271, 0.0328903049, 0.992660582, -0.116375163, 0.980746746, -0.00962915272, 0.195046604)
    },
    {
        ["Fov"] = 50.991417,
        ["Cf"] = CFrame.new(8.74682617, -0.568867683, -11.6546059, 0.202103168, -0.119213477, -0.972081482, 0.0436280183, 0.992674351, -0.112668321, 0.978392124, -0.0196393952, 0.20582363)
    },
    {
        ["Fov"] = 51.330074,
        ["Cf"] = CFrame.new(8.65605164, -0.5167799, -11.5509911, 0.235082895, -0.103684813, -0.966429293, 0.0562785715, 0.994077981, -0.092961438, 0.970344782, -0.0325356275, 0.239525974)
    },
    {
        ["Fov"] = 51.964252,
        ["Cf"] = CFrame.new(8.57545471, -0.483691216, -11.4547005, 0.26375699, -0.0892412141, -0.96045208, 0.0673537999, 0.994984686, -0.0739532933, 0.962234855, -0.0451844037, 0.268444926)
    },
    {
        ["Fov"] = 52.385559,
        ["Cf"] = CFrame.new(8.53800964, -0.491513252, -11.4027596, 0.276204497, -0.080991134, -0.957680225, 0.0729381815, 0.995335758, -0.0631395876, 0.958327293, -0.0524120517, 0.280823529)
    },
    {
        ["Fov"] = 53.191036,
        ["Cf"] = CFrame.new(8.46253967, -0.464580536, -11.2813835, 0.30467701, -0.064282082, -0.950284123, 0.084537439, 0.995607197, -0.0402438417, 0.948696733, -0.0680732056, 0.308772922)
    },
    {
        ["Fov"] = 54.699375,
        ["Cf"] = CFrame.new(8.41983032, -0.43081522, -11.0625, 0.363639802, -0.0614493117, -0.929510713, 0.0956103206, 0.99501425, -0.0283754002, 0.926620126, -0.0785524249, 0.367702007)
    },
    {
        ["Fov"] = 56.279606,
        ["Cf"] = CFrame.new(8.37979126, -0.394300461, -10.7631645, 0.443415672, -0.0636533797, -0.894053042, 0.10823565, 0.993978441, -0.0170870088, 0.889757156, -0.0891917795, 0.447635233)
    },
    {
        ["Fov"] = 56.916222,
        ["Cf"] = CFrame.new(8.37562561, -0.378537178, -10.6844749, 0.464304328, -0.0660569295, -0.883208871, 0.110954687, 0.993696809, -0.0159914922, 0.878698349, -0.0905712917, 0.468707025)
    },
    {
        ["Fov"] = 59.238747,
        ["Cf"] = CFrame.new(8.36036682, -0.309542179, -10.2803764, 0.545975327, -0.0703583807, -0.834841669, 0.116289929, 0.993185818, -0.00765115488, 0.829691291, -0.0929063708, 0.550436974)
    },
    {
        ["Fov"] = 62.338943,
        ["Cf"] = CFrame.new(8.34959412, -0.238850594, -9.7753067, 0.614286125, -0.0642548203, -0.786462903, 0.110811085, 0.993827105, 0.00535501633, 0.781264126, -0.0904383436, 0.617614388)
    },
    {
        ["Fov"] = 66.477211,
        ["Cf"] = CFrame.new(8.34422302, -0.162785053, -9.38744354, 0.65602982, -0.0559347011, -0.75265944, 0.102677561, 0.994592607, 0.0155811375, 0.747718096, -0.0875029415, 0.658225775)
    }
}
    local player = game.Players.LocalPlayer
    local camera = workspace.CurrentCamera
    camera.CameraType = Enum.CameraType.Scriptable
    local humanoidRootPart = player.Character.HumanoidRootPart
local e = humanoidRootPart.CFrame - humanoidRootPart.CFrame.LookVector * 25.5
local v2 = e * CFrame.Angles(0, math.rad(57), 0) * CFrame.new(10, 0, -3)
    for i, frame in ipairs(cutscene) do
        camera.CFrame = v2:ToWorldSpace(frame.Cf)
        camera.FieldOfView = frame.Fov
        wait(0.0099)
    end
    camera.CameraType = Enum.CameraType.Custom
end)

local highlight = Instance.new("Highlight")
highlight.FillColor = Color3.fromRGB(255, 66, 28)
highlight.OutlineColor = Color3.fromRGB(255, 44, 2)
highlight.FillTransparency = 0.5
highlight.OutlineTransparency = 0.6
highlight.DepthMode = Enum.HighlightDepthMode.Occluded

-- Apply to the character's body parts (e.g., Head, Torso, etc.)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Apply highlight to parts
for _, part in pairs(character:GetChildren()) do
    if part:IsA("BasePart") then
        local partHighlight = highlight:Clone()
        partHighlight.Parent = part

        -- Create and play the tween for the cloned highlight with 3.4 second duration
        local tweenService = game:GetService("TweenService")
        local tween = tweenService:Create(partHighlight, TweenInfo.new(3.4, Enum.EasingStyle.Cubic, Enum.EasingDirection.InOut), {
            FillTransparency = 1,
            OutlineTransparency = 1
        })

        tween:Play()
    end
end

task.spawn(function()
local l_char_32 = game.Players.LocalPlayer.Character

-- Additional initialization
local l_TweenService_18 = game:GetService("TweenService")
local l_FiveSeasonsFX_1 = game:GetService("ReplicatedStorage").Resources.FiveSeasonsFX
local l_Thrown_18 = workspace.Thrown
local l_LocalPlayer_0 = game.Players.LocalPlayer

local v10771 = l_FiveSeasonsFX_1.CharFX.BeamFX:Clone();
            v10771.Parent = l_char_32.Torso;
            for _, v10773 in pairs(v10771.Beams:GetDescendants()) do
                if v10773:IsA("Beam") then
                    v10773.Enabled = true;
                    v10773.TextureLength = v10773.TextureLength + Random.new():NextNumber(0.25, -0.25);
                end;
            end;
            task.wait(1.275);
            l_TweenService_18:Create(v10771, TweenInfo.new(0.85, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut), {
                Position = Vector3.new(0, 0, 1, 0)
            }):Play();
            for _, v10775 in pairs(v10771.Beams:GetDescendants()) do
                if v10775:IsA("Beam") then
                    l_TweenService_18:Create(v10775, TweenInfo.new(0.9, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut), {
                        Brightness = 0, 
                        Width0 = 0, 
                        Width1 = 0, 
                        CurveSize1 = 0, 
                        CurveSize0 = 0, 
                        TextureSpeed = v10775.TextureSpeed / 3
                    }):Play();
                    l_TweenService_18:Create(v10775, TweenInfo.new(0.8, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {
                        Brightness = 0
                    }):Play();
                end;
            end;
            for _, v10777 in pairs(v10771:GetDescendants()) do
                if v10777:IsA("Attachment") and v10777.Name == "tipat2" then
                    l_TweenService_18:Create(v10777, TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut), {
                        Position = Vector3.new(0, 0, -1.5, 0)
                    }):Play();
                end;
            end;
end)

local function GetGitSound(GithubSnd, SoundName)
    local url = GithubSnd
    if not isfile(SoundName .. ".mp3") then
        writefile(SoundName .. ".mp3", game:HttpGet(url))
    end
    local sound = Instance.new("Sound")
    sound.SoundId = (getcustomasset or getsynasset)(SoundName .. ".mp3")
    sound.Looped = false
    sound.Parent = workspace
    return sound
end

local Players = game:GetService("Players")
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

local SpeedTestSound = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/37a9a6fde6ae8af576298715b4fa47077e3349d5/Let's%20see%20how%20fast%20you%20can%20really%20go!%20%7C%20Fleetway%20Su%CC%81per%20Sonic%20Animation%20%7C%20Sergi0_2020%20%5B%20ezmp3.cc%20%5D.mp3?raw=true", "speed_test")

local FleetwayTheme = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/37a9a6fde6ae8af576298715b4fa47077e3349d5/VS.%20Fleetway%20Super%20Sonic%20Theme%20(Inescapable%20Terror)%20%5B%20ezmp3.cc%20%5D.mp3?raw=true", "fleetway_theme")

SpeedTestSound.Volume = 5
FleetwayTheme.Volume = 40

local function stopSounds()
    SpeedTestSound:Stop()
    FleetwayTheme:Stop()
end

humanoid.Died:Connect(stopSounds)

SpeedTestSound:Play()

local Players = game:GetService("Players")

local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:FindFirstChildOfClass("Humanoid")

local animation = Instance.new("Animation")
animation.AnimationId = "rbxassetid://119169968232874"

local animator = humanoid:FindFirstChildOfClass("Animator") or humanoid:WaitForChild("Animator")
local animationTrack = animator:LoadAnimation(animation)

animationTrack:Play()

SpeedTestSound.Ended:Connect(function()
    FleetwayTheme:Play()
end)

        end
    end
end

if animator then
    animator.AnimationPlayed:Connect(onAnimationPlayed)
end


local tool = Instance.new("Tool")
tool.Name = "KEEP UP!"
tool.RequiresHandle = false
tool.ToolTip = "ooh kick yes yes baby"
 
tool.Parent = game.Players.LocalPlayer.Backpack
 
local function onActivated()

message = "Your boring."
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(message, "All")

local player = game.Players.LocalPlayer
repeat wait() until player.Character.Humanoid
local humanoid = player.Character.Humanoid
local character = player.Character or player.CharacterAdded:Wait()
local UserInputService = game:GetService("UserInputService")

local anim = Instance.new("Animation")
anim.AnimationId = "rbxassetid://15283197429"

local playAnim = humanoid:LoadAnimation(anim)
playAnim:Play()
playAnim:AdjustSpeed(5)

local function GetGitSound(GithubSnd, SoundName)
    local url = GithubSnd
    if not isfile(SoundName..".mp3") then
        writefile(SoundName..".mp3", game:HttpGet(url))
    end
    local sound = Instance.new("Sound")
    sound.SoundId = (getcustomasset or getsynasset)(SoundName..".mp3")
    sound.Looped = false
    sound.Parent = workspace
    sound:Play()
end

-- URL for the sound you want to play
local soundUrl = "https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/a4d1d8e7994c554a3d65a80f3d442502b882bfcd/Fleetway%20Sonic%E2%80%99s%20laugh%20%5B%20ezmp3.cc%20%5D.mp3?raw=true"
local soundName = "FleetwaySonicLaugh"

-- Play the sound
GetGitSound(soundUrl, soundName)

-- Reference the particle effect to be duplicated
local particleEffect = game.ReplicatedStorage.Resources.FiveSeasonsFX.CharFX.TP

-- Clone the particle effect
local clonedEffect = particleEffect:Clone()

-- Parent the cloned effect to the player's HumanoidRootPart
clonedEffect.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart

-- Emit particles from all ParticleEmitters in the cloned effect
for _, child in ipairs(clonedEffect:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child:Emit(5) -- Emit particles
    end
end

-- Teleport the player 10 studs in front of their current position
local direction = character.HumanoidRootPart.CFrame.LookVector
local newPosition = character.HumanoidRootPart.Position + (direction * 60)
character.HumanoidRootPart.CFrame = CFrame.new(newPosition)

tool.Parent = game.Players.LocalPlayer.Backpack

local ToolNumber = 5
local cooldownTime = 5

local player = game.Players.LocalPlayer
local playerGui = player:WaitForChild("PlayerGui")
local hotbar = playerGui:WaitForChild("Hotbar")
local backpack = hotbar:WaitForChild("Backpack")
local localScript = backpack:WaitForChild("LocalScript")
local cooldown = localScript:WaitForChild("Cooldown")
local clonedCooldown = cooldown:Clone()
local hotbarSlot1 = hotbar:WaitForChild("Backpack"):WaitForChild("Hotbar"):WaitForChild(ToolNumber):WaitForChild("Base")

clonedCooldown.Parent = hotbarSlot1
clonedCooldown.BackgroundColor3 = Color3.fromRGB(139, 0, 0)  -- Dark red

local startSize = clonedCooldown.Size
local endSize = UDim2.new(startSize.X.Scale, startSize.X.Offset, 0, 0)

spawn(function()
    local startTime = tick()
    local initialSize = clonedCooldown.Size

    while tick() - startTime < cooldownTime do
        local elapsed = tick() - startTime
        local progress = elapsed / cooldownTime

        local newSize = UDim2.new(
            initialSize.X.Scale,
            initialSize.X.Offset,
            initialSize.Y.Scale * (1 - progress),
            initialSize.Y.Offset * (1 - progress)
        )

        clonedCooldown.Size = newSize
        wait()
    end

    clonedCooldown.Size = endSize
    clonedCooldown:Destroy()
end)
 
end
 
tool.Activated:Connect(onActivated)

message = "This should be fun…"
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(message, "All")

local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local LocalPlayer = Players.LocalPlayer
local Character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
local Humanoid = Character:FindFirstChildOfClass("Humanoid")
local AnimationToDetect = "rbxassetid://12447707844" -- The animation that triggers deletion

local cyanColor = ColorSequence.new(Color3.fromRGB(0, 255, 255)) -- Cyan color sequence
local activeEffects = {} -- Table to track applied effects

-- Function to apply particle effects
local function applyEffects(effect, parent)
    local clonedEffect = effect:Clone()
    clonedEffect.Parent = parent
    table.insert(activeEffects, clonedEffect) -- Track the effect for later deletion

    for _, child in ipairs(clonedEffect:GetChildren()) do
        if child:IsA("ParticleEmitter") then
            child.Color = cyanColor -- Apply cyan color
            child:Emit(20) -- Emit particles
        end
    end
end

-- Apply effects to character limbs
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Right Arm"])
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Left Arm"])
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Right Leg"])
applyEffects(ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, Character["Left Leg"])

-- Apply other special effects
local spin1 = ReplicatedStorage.Resources.WhirlwindDrop["CharFX"].Spin:Clone()
spin1.Parent = Character["Torso"]
table.insert(activeEffects, spin1)
for _, child in ipairs(spin1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = cyanColor
        child:Emit(1)
    end
end

local wow1 = ReplicatedStorage.Resources.Dragon["Complete"].Part.Debri:Clone()
wow1.Parent = Character["Torso"]
table.insert(activeEffects, wow1)
for _, child in ipairs(wow1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = cyanColor
        child:Emit(1)
    end
end

local wind1 = ReplicatedStorage.Resources.Dragon["Stretch"].Part.Attachment:Clone()
wind1.Parent = Character["Torso"]
table.insert(activeEffects, wind1)
for _, child in ipairs(wind1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = cyanColor
        child:Emit(1)
    end
end

-- Function to detect and delete effects when the animation is played
if Humanoid then
    Humanoid.AnimationPlayed:Connect(function(animationTrack)
        if animationTrack.Animation.AnimationId == AnimationToDetect then
            -- Destroy all active effects
            for _, effect in ipairs(activeEffects) do
                if effect then
                    effect:Destroy()
                end
            end
            activeEffects = {} -- Clear the table
        end
    end)
end


task.spawn(function()
    local Players = game:GetService("Players")
    local UserInputService = game:GetService("UserInputService")

    local player = Players.LocalPlayer

    local function getNearestPlayer()
        local character = player.Character
        if not character or not character:FindFirstChild("HumanoidRootPart") then return end

        local rootPart = character.HumanoidRootPart
        local closestPlayer = nil
        local shortestDistance = math.huge

        for _, otherPlayer in pairs(Players:GetPlayers()) do
            if otherPlayer ~= player and otherPlayer.Character and otherPlayer.Character:FindFirstChild("HumanoidRootPart") then
                local otherRoot = otherPlayer.Character.HumanoidRootPart
                local distance = (rootPart.Position - otherRoot.Position).Magnitude

                if distance < shortestDistance then
                    shortestDistance = distance
                    closestPlayer = otherPlayer
                end
            end
        end
        return closestPlayer
    end

    UserInputService.InputBegan:Connect(function(input, gameProcessed)
        if gameProcessed then return end
        if input.KeyCode == Enum.KeyCode.Q then
            task.wait(0.7) -- Wait 0.4 seconds before teleporting

            local nearestPlayer = getNearestPlayer()
            if nearestPlayer and nearestPlayer.Character and nearestPlayer.Character:FindFirstChild("HumanoidRootPart") then
                local rootPart = player.Character and player.Character:FindFirstChild("HumanoidRootPart")
                if rootPart then
                    rootPart.CFrame = nearestPlayer.Character.HumanoidRootPart.CFrame
                end
            end
        end
    end)
end)



local function GetGitSound(GithubSnd, SoundName)
    local url = GithubSnd
    if not isfile(SoundName .. ".mp3") then
        writefile(SoundName .. ".mp3", game:HttpGet(url))
    end
    local sound = Instance.new("Sound")
    sound.SoundId = (getcustomasset or getsynasset)(SoundName .. ".mp3")
    return sound
end

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local userInputService = game:GetService("UserInputService")

local function playTaunt()
    local animation = Instance.new("Animation")
    animation.AnimationId = "rbxassetid://14494902453"
    local animTrack = humanoid:LoadAnimation(animation)

    local Clock = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/d48e7b7c337d33c2fc3684b035b97ce79e7012be/You're%20too%20slow!%20%5B%20ezmp3.cc%20%5D.mp3?raw=true?raw=true", "hell no4060")

    Clock.Parent = workspace
    Clock.Volume = 5
    Clock.TimePosition = 0

    animTrack:Play()
    Clock:Play()
    game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("You really need to keep up!", "All")
end

userInputService.InputBegan:Connect(function(input, gameProcessed)
    if not gameProcessed and input.KeyCode == Enum.KeyCode.T then
        playTaunt()
    end
end)

local Player = game.Players.LocalPlayer
local PlayerGui = Player:WaitForChild("PlayerGui")
local ScreenGui = Instance.new("ScreenGui", PlayerGui)

-- Create the first image button
local imageButton1 = Instance.new("ImageButton")
imageButton1.Size = UDim2.new(0, 50, 0, 50)
imageButton1.Position = UDim2.new(0.5, 250, 0.5, -25) -- Adjusted to be left of the jump button
imageButton1.Image = "rbxassetid://14488863746"
imageButton1.BackgroundTransparency = 1
imageButton1.Parent = ScreenGui

-- Create the second image button
local imageButton2 = Instance.new("ImageButton")
imageButton2.Size = UDim2.new(0, 50, 0, 50)
imageButton2.Position = UDim2.new(0.5, 250, 0.5, -25) -- Adjusted to be right of the first image button
imageButton2.Image = "rbxassetid://6256840888"
imageButton2.BackgroundTransparency = 1
imageButton2.Parent = ScreenGui

-- Functionality for the first image button
imageButton1.MouseButton1Click:Connect(function()
-- THIS ONE IS NESSACARY TOO
    print("Image Button 1 clicked - custom action executed")
end)

-- Functionality for the second image button
imageButton2.MouseButton1Click:Connect(function()
-- THIS ONE IS NESSACARY

loadstring(game:HttpGet("https://pastebin.com/raw/bhXdgi4r"))() 
wait(15)

    print("Image Button 2 clicked - custom action executed")
end)

local UserInputService = game:GetService("UserInputService")
local cooldownTime = 15
local lastPressTime = 0

UserInputService.InputBegan:Connect(function(input, gameProcessed)
    if gameProcessed then return end
    if input.KeyCode == Enum.KeyCode.R then
        local currentTime = tick()
        if currentTime - lastPressTime >= cooldownTime then
            lastPressTime = currentTime
            loadstring(game:HttpGet("https://pastebin.com/raw/bhXdgi4r"))() 
        else
            local timeRemaining = cooldownTime - (currentTime - lastPressTime)
            print("You need to wait " .. math.ceil(timeRemaining) .. " more seconds.")
        end
    end
end)


local players = game:GetService("Players")
local erm = players.LocalPlayer
local bar = erm.PlayerGui.ScreenGui.MagicHealth.Health.Bar.Bar

-- Darker Blue
bar.ImageColor3 = Color3.fromRGB(0, 200, 200) -- Darker Blue


local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local blockedAnimationId = "rbxassetid://7815618175"

-- Function to immediately stop the blocked animation if it's played
local function onAnimationPlayed(animationTrack)
    if animationTrack.Animation.AnimationId == blockedAnimationId then
        animationTrack:Stop()
    end
end

-- Connect to the AnimationPlayed event
animator.AnimationPlayed:Connect(onAnimationPlayed)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://18897115785"
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

-- Initial check
onHumanoidChanged()


_G.HackedWalkSpeed = 85

local Plrs = game:GetService("Players")

local MyPlr = Plrs.LocalPlayer
local MyChar = MyPlr.Character

if MyChar then
local Hum = MyChar.Humanoid
Hum.Changed:connect(function()
Hum.WalkSpeed = _G.HackedWalkSpeed
end)
Hum.WalkSpeed = _G.HackedWalkSpeed
end


MyPlr.CharacterAdded:connect(function(Char)
MyChar = Char
repeat wait() until Char:FindFirstChild("Humanoid")
local Hum = Char.Humanoid
Hum.Changed:connect(function()
Hum.WalkSpeed = _G.HackedWalkSpeed
end)
Hum.WalkSpeed = _G.HackedWalkSpeed
end)

local Players = game:GetService("Players")
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

local animationIdsToStop = {
    [13532562418] = true,
    [13532600125] = true,
    [13532604085] = true,
    [13294471966] = true,
}

local replacementAnimations = {
    [13532562418] = "rbxassetid://17889458563",
    [13532600125] = "rbxassetid://17889461810",
    [13532604085] = "rbxassetid://17889471098",
    [13294471966] = "rbxassetid://17889290569",
}

local activeReplacement

local function stopAllAnimations()
    for _, track in ipairs(humanoid:GetPlayingAnimationTracks()) do
        track:Stop()
    end
end

local function playReplacementAnimation(animationId)
    if activeReplacement then
        activeReplacement:Stop() -- Stop any currently playing replacement animation
    end

    local replacementAnimationId = replacementAnimations[animationId]
    if replacementAnimationId then
        local animAnim = Instance.new("Animation")
        animAnim.AnimationId = replacementAnimationId
        local anim = humanoid:LoadAnimation(animAnim)
        activeReplacement = anim
        anim:Play()

        anim.Stopped:Connect(function()
            if activeReplacement == anim then
                activeReplacement = nil
            end
        end)
    end
end

local function onAnimationPlayed(animationTrack)
    local animationId = tonumber(animationTrack.Animation.AnimationId:match("%d+"))
    if animationIdsToStop[animationId] then
        stopAllAnimations() -- Ensure no overlapping animations
        animationTrack:Stop()
        playReplacementAnimation(animationId)
    end
end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local function onBodyVelocityAdded(bodyVelocity)
    if bodyVelocity:IsA("BodyVelocity") then
        bodyVelocity.Velocity = Vector3.new(bodyVelocity.Velocity.X, 0, bodyVelocity.Velocity.Z)
    end
end

character.DescendantAdded:Connect(onBodyVelocityAdded)

for _, descendant in pairs(character:GetDescendants()) do
    onBodyVelocityAdded(descendant)
end

player.CharacterAdded:Connect(function(newCharacter)
    character = newCharacter
    humanoid = character:WaitForChild("Humanoid")

    character.DescendantAdded:Connect(onBodyVelocityAdded)

    for _, descendant in pairs(character:GetDescendants()) do
        onBodyVelocityAdded(descendant)
    end
end)


local function GetGitSound(GithubSnd, SoundName)
    local url = GithubSnd
    if not isfile(SoundName..".mp3") then
        writefile(SoundName..".mp3", game:HttpGet(url))
    end
    local sound = Instance.new("Sound")
    sound.SoundId = (getcustomasset or getsynasset)(SoundName..".mp3")
    sound.Parent = workspace
    return sound
end

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

local jumpSound = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/d65d59cc108f7b245cf1b8e07c432c368648fc77/Sonic%20Jumping%20-%20Sound%20Effect%20%5B%20ezmp3.cc%20%5D.mp3?raw=true?raw=true", "hell no400")

jumpSound.Volume = 5
jumpSound.TimePosition = 0.3

local function playJumpSound()
    jumpSound.TimePosition = 0.3
    jumpSound:Play()
end

humanoid.Jumping:Connect(playJumpSound)

local cyanColor = ColorSequence.new(Color3.fromRGB(0, 255, 255)) -- Cyan color sequence

local function applyEffects(effect, parent)
    local clonedEffect = effect:Clone()
    clonedEffect.Parent = parent

    for _, child in ipairs(clonedEffect:GetChildren()) do
        if child:IsA("ParticleEmitter") then
            child.Color = cyanColor -- Apply cyan color
            child:Emit(20) -- Emit particles
        end
    end
end

local character = game.Players.LocalPlayer.Character

applyEffects(game.ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, character["Right Arm"])
applyEffects(game.ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, character["Left Arm"])
applyEffects(game.ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, character["Right Leg"])
applyEffects(game.ReplicatedStorage.Resources.HeadFirst["CharFX"].WindTrail, character["Left Leg"])

local spin1 = game.ReplicatedStorage.Resources.WhirlwindDrop["CharFX"].Spin:Clone()
spin1.Parent = character["Torso"]
for _, child in ipairs(spin1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = cyanColor -- Apply cyan color
        child:Emit(1)
    end
end

local wow1 = game.ReplicatedStorage.Resources.Dragon["Complete"].Part.Debri:Clone()
wow1.Parent = character["Torso"]
for _, child in ipairs(wow1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = cyanColor -- Apply cyan color
        child:Emit(1)
    end
end

local wind1 = game.ReplicatedStorage.Resources.Dragon["Stretch"].Part.Attachment:Clone()
wind1.Parent = character["Torso"]
for _, child in ipairs(wind1:GetChildren()) do
    if child:IsA("ParticleEmitter") then
        child.Color = cyanColor -- Apply cyan color
        child:Emit(1)
    end
end

local r = game:GetService("ReplicatedStorage")
local p = game:GetService("Players").LocalPlayer
local animationToDetect = "rbxassetid://12342141464" -- The animation ID to detect

-- Define cyan color sequence
local cyanColor = ColorSequence.new(Color3.fromRGB(0, 255, 255))

-- Function to handle the effects and animation
local function m()
    local a = r:FindFirstChild("Resources")
    if not a then return end

    local b = a:FindFirstChild("KJEffects")
    if not b then return end

    local c = b:FindFirstChild("KJWallCombo")
    if not c then return end

    local d = c:FindFirstChild("UserAura")
    if not d or not d:IsA("Folder") then return end

    local e = p.Character:FindFirstChild("Torso")
    if not e then return end

    -- Start particle effects
    local particleEmitters = {}
    for _, f in pairs(d:GetChildren()) do
        if f:IsA("ParticleEmitter") then
            local g = f:Clone()
            g.Parent = e
            g.Color = cyanColor -- Set color to cyan
            g.Enabled = true
            g.Rate = 30
            g:Emit(2)
            table.insert(particleEmitters, g)
        end
    end

    -- Detect animation being played
    local humanoid = p.Character:FindFirstChild("Humanoid")
    if humanoid then
        humanoid.AnimationPlayed:Connect(function(animationTrack)
            if animationTrack.Animation.AnimationId == animationToDetect then
                -- Destroy the particles when the specific animation is played
                for _, particle in ipairs(particleEmitters) do
                    particle:Destroy()
                end
                -- Stop the current animation when the specific animation is played
                animationTrack:Stop()
            end
        end)
    end
end

m()






task.spawn(function()
    local player = game.Players.LocalPlayer
    local gui = player.PlayerGui
    local ulttext = gui.ScreenGui.MagicHealth.TextLabel
    
    local textToDisplay = "GOTTA GO FAST!"
    ulttext.Text = ""
    
    local function typeText()
        for i = 1, #textToDisplay do
            ulttext.Text = string.sub(textToDisplay, 1, i)
            wait(0.08)
        end
    end
    
    typeText()
end)








local function addTrailToCharacter(character)
    local leftArm = character:FindFirstChild("Left Arm") or character:FindFirstChild("LeftHand")
    local rightArm = character:FindFirstChild("Right Arm") or character:FindFirstChild("RightHand")

    if not leftArm or not rightArm then
        return
    end

    local trail = Instance.new("Trail")
    trail.Color = ColorSequence.new(Color3.new(0, 0, 1), Color3.new(0, 1, 1))
    trail.Transparency = NumberSequence.new(0, 1)
    trail.Lifetime = 1
    trail.LightEmission = 1
    trail.Attachment0 = Instance.new("Attachment", leftArm)
    trail.Attachment1 = Instance.new("Attachment", rightArm)
    trail.Parent = character
end

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

addTrailToCharacter(character)

game.Lighting.TimeOfDay = "00:00:00"

local Vignette = true

local Lighting = game:GetService("Lighting")
local StarterGui = game:GetService("StarterGui")
local Bloom = Instance.new("BloomEffect")
local Blur = Instance.new("BlurEffect")
local ColorCor = Instance.new("ColorCorrectionEffect")
local SunRays = Instance.new("SunRaysEffect")
local Sky = Instance.new("Sky")
local Atm = Instance.new("Atmosphere")

for i, v in pairs(Lighting:GetChildren()) do
	if v then
		v:Destroy()
	end
end

Bloom.Parent = Lighting
Blur.Parent = Lighting
ColorCor.Parent = Lighting
SunRays.Parent = Lighting
Sky.Parent = Lighting
Atm.Parent = Lighting

if Vignette then
	local Gui = Instance.new("ScreenGui")
	Gui.Parent = StarterGui
	Gui.IgnoreGuiInset = true
	
	local ShadowFrame = Instance.new("ImageLabel")
	ShadowFrame.Parent = Gui
	ShadowFrame.AnchorPoint = Vector2.new(0.5,1)
	ShadowFrame.Position = UDim2.new(0.5,0,1,0)
	ShadowFrame.Size = UDim2.new(1,0,1.05,0)
	ShadowFrame.BackgroundTransparency = 1
	ShadowFrame.Image = "rbxassetid://4576475446"
	ShadowFrame.ImageTransparency = 0.4
	ShadowFrame.ZIndex = 10
end

Bloom.Intensity = 0.3
Bloom.Size = 10
Bloom.Threshold = 0.85

Blur.Size = 3

ColorCor.Brightness = 0.15
ColorCor.Contrast = 0.4
ColorCor.Saturation = -0.1
ColorCor.TintColor = Color3.fromRGB(245, 225, 200)

SunRays.Intensity = 0.1
SunRays.Spread = 0.85

Sky.SkyboxBk = "http://www.roblox.com/asset/?id=151165214"
Sky.SkyboxDn = "http://www.roblox.com/asset/?id=151165197"
Sky.SkyboxFt = "http://www.roblox.com/asset/?id=151165224"
Sky.SkyboxLf = "http://www.roblox.com/asset/?id=151165191"
Sky.SkyboxRt = "http://www.roblox.com/asset/?id=151165206"
Sky.SkyboxUp = "http://www.roblox.com/asset/?id=151165227"
Sky.SunAngularSize = 12

Lighting.Ambient = Color3.fromRGB(50, 50, 50)
Lighting.Brightness = 2.5
Lighting.ColorShift_Bottom = Color3.fromRGB(25, 25, 25)
Lighting.ColorShift_Top = Color3.fromRGB(50, 50, 50)
Lighting.EnvironmentDiffuseScale = 0.25
Lighting.EnvironmentSpecularScale = 0.25
Lighting.GlobalShadows = true
Lighting.OutdoorAmbient = Color3.fromRGB(60, 60, 60)
Lighting.ShadowSoftness = 0.25
Lighting.ClockTime = 16
Lighting.GeographicLatitude = 45
Lighting.ExposureCompensation = 0.6

Atm.Density = 0.25
Atm.Offset = 0.65
Atm.Color = Color3.fromRGB(210, 190, 180)
Atm.Decay = Color3.fromRGB(70, 60, 55)
Atm.Glare = 0.25
Atm.Haze = 1.4

script:Destroy()

local function GetGitSound(GithubSnd, SoundName)
    local url = GithubSnd
    if not isfile(SoundName .. ".mp3") then
        writefile(SoundName .. ".mp3", game:HttpGet(url))
    end
    local sound = Instance.new("Sound")
    sound.SoundId = (getcustomasset or getsynasset)(SoundName .. ".mp3")
    sound.Looped = false
    sound.Parent = workspace
    return sound
end

local Player = game.Players.LocalPlayer
local Character = Player.Character or Player.CharacterAdded:Wait()
local Humanoid = Character:WaitForChild("Humanoid")
local animationToDetect = "rbxassetid://12342141464" -- Animation ID to detect

-- Load sounds
local RobotnikTheme = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/ca1b4c8301657c1e8dbda94032031d2581af876d/Sonic%20The%20Hedgehog%20OST%20-%20Robotnik%20%5B%20ezmp3.cc%20%5D.mp3?raw=true", "robotnik_theme")
local GreenHillTheme = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/c84b2f62f8ae10a51b3354d76dbb089db7a3aaea/Sonic%20The%20Hedgehog%20OST%20-%20Green%20Hill%20Zone%20%5B%20ezmp3.cc%20%5D.mp3?raw=true", "green_hill_theme")
local SpringYardTheme = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/85604927dd6a1dba03d5e5527b8182db2dbfc134/Sonic%20The%20Hedgehog%20OST%20-%20Spring%20Yard%20Zone%20%5B%20ezmp3.cc%20%5D.mp3?raw=true", "spring_yard_theme")
local EscapeFromCityTheme = GetGitSound("https://github.com/Bigblackdick2a/That-s-the-way-I-like-it/blob/d2c437ac9fdcc4fd4729cf6e49a8813cec337a28/Escape%20From%20The%20City%20...%20for%20City%20Escape%20%5B%20ezmp3.cc%20%5D.mp3?raw=true", "escape_from_city_theme")

RobotnikTheme.Volume = 5
GreenHillTheme.Volume = 5
SpringYardTheme.Volume = 5
EscapeFromCityTheme.Volume = 5

-- Function to stop and restart music
local function PlayMusicLoop()
    if Humanoid.Health >= 50 then
        GreenHillTheme:Play()
        GreenHillTheme.Ended:Wait()
        SpringYardTheme:Play()
        SpringYardTheme.Ended:Wait()
        EscapeFromCityTheme:Play()
        EscapeFromCityTheme.Ended:Wait()
        PlayMusicLoop()
    end
end

local function UpdateMusic()
    -- Check if the specific animation is being played
    local isAnimationPlaying = false
    for _, track in pairs(Humanoid:GetPlayingAnimationTracks()) do
        if track.Animation.AnimationId == animationToDetect then
            isAnimationPlaying = true
            break
        end
    end
    
    -- If the animation is playing, stop the music and don't continue
    if isAnimationPlaying then
        RobotnikTheme:Stop()
        GreenHillTheme:Stop()
        SpringYardTheme:Stop()
        EscapeFromCityTheme:Stop()
        return
    end

    -- If health is less than 50, switch to Robotnik theme
    if Humanoid.Health < 50 then
        GreenHillTheme:Stop()
        SpringYardTheme:Stop()
        EscapeFromCityTheme:Stop()
        if not RobotnikTheme.IsPlaying then
            RobotnikTheme:Play()
        end
    else
        RobotnikTheme:Stop()
        if not GreenHillTheme.IsPlaying and not SpringYardTheme.IsPlaying and not EscapeFromCityTheme.IsPlaying then
            PlayMusicLoop()
        end
    end
end

Humanoid:GetPropertyChangedSignal("Health"):Connect(UpdateMusic)
Humanoid.Died:Connect(function()
    RobotnikTheme:Stop()
    GreenHillTheme:Stop()
    SpringYardTheme:Stop()
    EscapeFromCityTheme:Stop()
end)


-- Function to detect animation and destroy effects
local function m()
    local r = game:GetService("ReplicatedStorage")
    local a = r:FindFirstChild("Resources")
    if not a then return end

    local b = a:FindFirstChild("KJEffects")
    if not b then return end

    local c = b:FindFirstChild("KJWallCombo")
    if not c then return end

    local d = c:FindFirstChild("UserAura")
    if not d or not d:IsA("Folder") then return end

    local e = p.Character:FindFirstChild("Torso")
    if not e then return end

    -- Start particle effects
    local particleEmitters = {}
    for _, f in pairs(d:GetChildren()) do
        if f:IsA("ParticleEmitter") then
            local g = f:Clone()
            g.Parent = e
            g.Color = cyanColor -- Set color to cyan
            g.Enabled = true
            g.Rate = 30
            g:Emit(2)
            table.insert(particleEmitters, g)
        end
    end

    -- Detect animation being played
    local humanoid = p.Character:FindFirstChild("Humanoid")
    if humanoid then
        humanoid.AnimationPlayed:Connect(function(animationTrack)
            if animationTrack.Animation.AnimationId == animationToDetect then
                -- Stop music and destroy particles when the specific animation is played
                GreenHillTheme:Stop()
                SpringYardTheme:Stop()
                EscapeFromCityTheme:Stop()
                RobotnikTheme:Stop()

                for _, particle in ipairs(particleEmitters) do
                    particle:Destroy()
                end
            end
        end)
    end
end

m()

-- Start the initial music loop if health is 50 or above
if Humanoid.Health >= 50 then
    PlayMusicLoop()
end
