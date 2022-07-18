-- Gui to Lua
-- Version: 3.2

-- Instances:

local DarkReaper = Instance.new("ScreenGui")
local TopBar = Instance.new("Frame")
local container = Instance.new("Frame")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local MiniBar = Instance.new("Frame")
local DropShadowHolder_2 = Instance.new("Frame")
local DropShadow_2 = Instance.new("ImageLabel")
local homeIcon = Instance.new("ImageButton")
local settingsIcon = Instance.new("ImageButton")
local Sparator_1 = Instance.new("Frame")
local Sparator_2 = Instance.new("Frame")
local userIcon = Instance.new("ImageButton")
local Sparator_3 = Instance.new("Frame")
local scriptsIcon = Instance.new("ImageButton")
local homePanel = Instance.new("Frame")
local Sparator = Instance.new("Frame")
local welcome_Message = Instance.new("TextLabel")
local user_image = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local sparator = Instance.new("Frame")
local userId = Instance.new("TextLabel")
local game_id = Instance.new("TextLabel")
local coming_soon = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local DropShadowHolder_3 = Instance.new("Frame")
local DropShadow_3 = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local DropShadowHolder_4 = Instance.new("Frame")
local DropShadow_4 = Instance.new("ImageLabel")
local credits = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local DropShadowHolder_5 = Instance.new("Frame")
local DropShadow_5 = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local sparator_2 = Instance.new("Frame")
local DropShadowHolder_6 = Instance.new("Frame")
local DropShadow_6 = Instance.new("ImageLabel")
local title = Instance.new("TextLabel")
local closeImBtn = Instance.new("ImageButton")
local minimize = Instance.new("ImageButton")
local logo = Instance.new("ImageLabel")

--Properties:

DarkReaper.Name = "Dark Reaper"
DarkReaper.Parent = game.CoreGui
DarkReaper.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TopBar.Name = "TopBar"
TopBar.Parent = DarkReaper
TopBar.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
TopBar.BorderSizePixel = 0
TopBar.Position = UDim2.new(0.264150947, 0, 0.240847781, 0)
TopBar.Size = UDim2.new(0, 500, 0, 30)

container.Name = "container"
container.Parent = TopBar
container.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
container.BorderSizePixel = 0
container.Position = UDim2.new(0, 0, 0.999999881, 0)
container.Size = UDim2.new(0, 500, 0, 265)

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = container
DropShadowHolder.BackgroundTransparency = 1.000
DropShadowHolder.BorderSizePixel = 0
DropShadowHolder.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder.ZIndex = 0

DropShadow.Name = "DropShadow"
DropShadow.Parent = DropShadowHolder
DropShadow.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0.523500025, 0, 0.5, 0)
DropShadow.Size = UDim2.new(0.953000009, 47, 1, 47)
DropShadow.ZIndex = 0
DropShadow.Image = "rbxassetid://6015897843"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.500
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

MiniBar.Name = "MiniBar"
MiniBar.Parent = container
MiniBar.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
MiniBar.BorderSizePixel = 0
MiniBar.Size = UDim2.new(0, 40, 0, 265)

DropShadowHolder_2.Name = "DropShadowHolder"
DropShadowHolder_2.Parent = MiniBar
DropShadowHolder_2.BackgroundTransparency = 1.000
DropShadowHolder_2.BorderSizePixel = 0
DropShadowHolder_2.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder_2.ZIndex = 0

DropShadow_2.Name = "DropShadow"
DropShadow_2.Parent = DropShadowHolder_2
DropShadow_2.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow_2.BackgroundTransparency = 1.000
DropShadow_2.BorderSizePixel = 0
DropShadow_2.Position = UDim2.new(0.495834351, 0, 0.501886785, 0)
DropShadow_2.Size = UDim2.new(0.791666806, 47, 0.97358489, 47)
DropShadow_2.ZIndex = 0
DropShadow_2.Image = "rbxassetid://6015897843"
DropShadow_2.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow_2.ImageTransparency = 0.500
DropShadow_2.ScaleType = Enum.ScaleType.Slice
DropShadow_2.SliceCenter = Rect.new(49, 49, 450, 450)

homeIcon.Name = "homeIcon"
homeIcon.Parent = MiniBar
homeIcon.BackgroundColor3 = Color3.fromRGB(162, 134, 255)
homeIcon.BackgroundTransparency = 1.000
homeIcon.BorderSizePixel = 0
homeIcon.Position = UDim2.new(0.25, 0, 0.0415094197, 0)
homeIcon.Size = UDim2.new(0, 20, 0, 20)
homeIcon.Image = "rbxassetid://7072717697"

settingsIcon.Name = "settingsIcon"
settingsIcon.Parent = MiniBar
settingsIcon.BackgroundColor3 = Color3.fromRGB(162, 134, 255)
settingsIcon.BackgroundTransparency = 1.000
settingsIcon.BorderSizePixel = 0
settingsIcon.Position = UDim2.new(0.25, 0, 0.218867913, 0)
settingsIcon.Size = UDim2.new(0, 20, 0, 20)
settingsIcon.Image = "rbxassetid://7072721682"

Sparator_1.Name = "Sparator_1"
Sparator_1.Parent = MiniBar
Sparator_1.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Sparator_1.BorderSizePixel = 0
Sparator_1.Position = UDim2.new(0.174999997, 0, 0.166037738, 0)
Sparator_1.Size = UDim2.new(0, 25, 0, 1)

Sparator_2.Name = "Sparator_2"
Sparator_2.Parent = MiniBar
Sparator_2.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Sparator_2.BorderSizePixel = 0
Sparator_2.Position = UDim2.new(0.174999997, 0, 0.339622647, 0)
Sparator_2.Size = UDim2.new(0, 25, 0, 1)

userIcon.Name = "userIcon"
userIcon.Parent = MiniBar
userIcon.BackgroundColor3 = Color3.fromRGB(162, 134, 255)
userIcon.BackgroundTransparency = 1.000
userIcon.BorderSizePixel = 0
userIcon.Position = UDim2.new(0.25, 0, 0.894339621, 0)
userIcon.Size = UDim2.new(0, 20, 0, 20)
userIcon.Image = "rbxassetid://7072724538"

Sparator_3.Name = "Sparator_3"
Sparator_3.Parent = MiniBar
Sparator_3.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Sparator_3.BorderSizePixel = 0
Sparator_3.Position = UDim2.new(0.174999997, 0, 0.864151001, 0)
Sparator_3.Size = UDim2.new(0, 25, 0, 1)

scriptsIcon.Name = "scriptsIcon"
scriptsIcon.Parent = MiniBar
scriptsIcon.BackgroundColor3 = Color3.fromRGB(162, 134, 255)
scriptsIcon.BackgroundTransparency = 1.000
scriptsIcon.BorderSizePixel = 0
scriptsIcon.Position = UDim2.new(0.25, 0, 0.384905636, 0)
scriptsIcon.Size = UDim2.new(0, 20, 0, 20)
scriptsIcon.Image = "rbxassetid://2609397568"

homePanel.Name = "homePanel"
homePanel.Parent = container
homePanel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
homePanel.BackgroundTransparency = 1.000
homePanel.Position = UDim2.new(0.0799999982, 0, 0, 0)
homePanel.Size = UDim2.new(0, 460, 0, 265)

Sparator.Name = "Sparator"
Sparator.Parent = homePanel
Sparator.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Sparator.BorderSizePixel = 0
Sparator.Position = UDim2.new(0.0217391253, 0, 0.252830207, 0)
Sparator.Size = UDim2.new(0, 440, 0, 1)

welcome_Message.Name = "welcome_Message"
welcome_Message.Parent = homePanel
welcome_Message.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
welcome_Message.BackgroundTransparency = 1.000
welcome_Message.Position = UDim2.new(0.0217391402, 0, 0.0603773445, 0)
welcome_Message.Size = UDim2.new(0, 200, 0, 30)
welcome_Message.Font = Enum.Font.GothamMedium
welcome_Message.Text = "welcome label"
welcome_Message.TextColor3 = Color3.fromRGB(147, 147, 147)
welcome_Message.TextSize = 14.000

user_image.Name = "user_image"
user_image.Parent = homePanel
user_image.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
user_image.BackgroundTransparency = 1.000
user_image.Position = UDim2.new(0.564637661, 0, 0.0219426975, 0)
user_image.Size = UDim2.new(0, 50, 0, 50)
user_image.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner.CornerRadius = UDim.new(0, 300)
UICorner.Parent = user_image

sparator.Name = "sparator"
sparator.Parent = homePanel
sparator.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
sparator.BorderSizePixel = 0
sparator.Position = UDim2.new(0.697826087, 0, 0.0188679248, 0)
sparator.Size = UDim2.new(0, 1, 0, 55)

userId.Name = "userId"
userId.Parent = homePanel
userId.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
userId.BackgroundTransparency = 1.000
userId.Position = UDim2.new(0.699999988, 0, 0.0452830195, 0)
userId.Size = UDim2.new(0, 138, 0, 20)
userId.Font = Enum.Font.Gotham
userId.Text = "user id"
userId.TextColor3 = Color3.fromRGB(147, 147, 147)
userId.TextSize = 10.000

game_id.Name = "game_id"
game_id.Parent = homePanel
game_id.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
game_id.BackgroundTransparency = 1.000
game_id.Position = UDim2.new(0.699999988, 0, 0.120754719, 0)
game_id.Size = UDim2.new(0, 138, 0, 20)
game_id.Font = Enum.Font.Gotham
game_id.Text = "game id"
game_id.TextColor3 = Color3.fromRGB(147, 147, 147)
game_id.TextSize = 10.000

coming_soon.Name = "coming_soon"
coming_soon.Parent = homePanel
coming_soon.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
coming_soon.BorderSizePixel = 0
coming_soon.Position = UDim2.new(0.0413043462, 0, 0.294339627, 0)
coming_soon.Size = UDim2.new(0, 175, 0, 175)

UICorner_2.CornerRadius = UDim.new(0, 5)
UICorner_2.Parent = coming_soon

DropShadowHolder_3.Name = "DropShadowHolder"
DropShadowHolder_3.Parent = coming_soon
DropShadowHolder_3.BackgroundTransparency = 1.000
DropShadowHolder_3.BorderSizePixel = 0
DropShadowHolder_3.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder_3.ZIndex = 0

DropShadow_3.Name = "DropShadow"
DropShadow_3.Parent = DropShadowHolder_3
DropShadow_3.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow_3.BackgroundTransparency = 1.000
DropShadow_3.BorderSizePixel = 0
DropShadow_3.Position = UDim2.new(0.5, 0, 0.5, 0)
DropShadow_3.Size = UDim2.new(1, 47, 1, 47)
DropShadow_3.ZIndex = 0
DropShadow_3.Image = "rbxassetid://6015897843"
DropShadow_3.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow_3.ImageTransparency = 0.500
DropShadow_3.ScaleType = Enum.ScaleType.Slice
DropShadow_3.SliceCenter = Rect.new(49, 49, 450, 450)

TextLabel.Parent = coming_soon
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel.Size = UDim2.new(0, 175, 0, 25)
TextLabel.Font = Enum.Font.GothamBold
TextLabel.Text = "COMING SOON [V1]"
TextLabel.TextColor3 = Color3.fromRGB(102, 102, 102)
TextLabel.TextSize = 12.000

Frame.Parent = coming_soon
Frame.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0285714269, 0, 0.137142852, 0)
Frame.Size = UDim2.new(0, 165, 0, 1)

TextLabel_2.Parent = coming_soon
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0857142881, 0, 0.142857134, 0)
TextLabel_2.Size = UDim2.new(0, 145, 0, 109)
TextLabel_2.Font = Enum.Font.Gotham
TextLabel_2.Text = "- New Logo\\n- Updated ScriptHub\\n- Key system\\n- Auto Login  \\n- New paid subscription\\n(Ds. Premium)"
TextLabel_2.TextColor3 = Color3.fromRGB(149, 149, 149)
TextLabel_2.TextSize = 12.000
TextLabel_2.TextWrapped = true

TextButton.Parent = coming_soon
TextButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.125714302, 0, 0.777142942, 0)
TextButton.Size = UDim2.new(0, 130, 0, 30)
TextButton.Font = Enum.Font.GothamMedium
TextButton.Text = "MORE INFO"
TextButton.TextColor3 = Color3.fromRGB(179, 179, 179)
TextButton.TextSize = 12.000

DropShadowHolder_4.Name = "DropShadowHolder"
DropShadowHolder_4.Parent = TextButton
DropShadowHolder_4.BackgroundTransparency = 1.000
DropShadowHolder_4.BorderSizePixel = 0
DropShadowHolder_4.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder_4.ZIndex = 0

DropShadow_4.Name = "DropShadow"
DropShadow_4.Parent = DropShadowHolder_4
DropShadow_4.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow_4.BackgroundTransparency = 1.000
DropShadow_4.BorderSizePixel = 0
DropShadow_4.Position = UDim2.new(0.496153831, 0, 0.483333319, 0)
DropShadow_4.Size = UDim2.new(0.899999976, 47, 0.566666663, 47)
DropShadow_4.ZIndex = 0
DropShadow_4.Image = "rbxassetid://6015897843"
DropShadow_4.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow_4.ImageTransparency = 0.500
DropShadow_4.ScaleType = Enum.ScaleType.Slice
DropShadow_4.SliceCenter = Rect.new(49, 49, 450, 450)

credits.Name = "credits"
credits.Parent = homePanel
credits.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
credits.BorderSizePixel = 0
credits.Position = UDim2.new(0.578260899, 0, 0.294339627, 0)
credits.Size = UDim2.new(0, 175, 0, 175)

UICorner_3.CornerRadius = UDim.new(0, 5)
UICorner_3.Parent = credits

DropShadowHolder_5.Name = "DropShadowHolder"
DropShadowHolder_5.Parent = credits
DropShadowHolder_5.BackgroundTransparency = 1.000
DropShadowHolder_5.BorderSizePixel = 0
DropShadowHolder_5.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder_5.ZIndex = 0

DropShadow_5.Name = "DropShadow"
DropShadow_5.Parent = DropShadowHolder_5
DropShadow_5.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow_5.BackgroundTransparency = 1.000
DropShadow_5.BorderSizePixel = 0
DropShadow_5.Position = UDim2.new(0.5, 0, 0.5, 0)
DropShadow_5.Size = UDim2.new(1, 47, 1, 47)
DropShadow_5.ZIndex = 0
DropShadow_5.Image = "rbxassetid://6015897843"
DropShadow_5.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow_5.ImageTransparency = 0.500
DropShadow_5.ScaleType = Enum.ScaleType.Slice
DropShadow_5.SliceCenter = Rect.new(49, 49, 450, 450)

TextLabel_3.Parent = credits
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_3.Size = UDim2.new(0, 175, 0, 25)
TextLabel_3.Font = Enum.Font.GothamBold
TextLabel_3.Text = "CREDITS"
TextLabel_3.TextColor3 = Color3.fromRGB(102, 102, 102)
TextLabel_3.TextSize = 12.000

Frame_2.Parent = credits
Frame_2.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0285714269, 0, 0.137142852, 0)
Frame_2.Size = UDim2.new(0, 165, 0, 1)

TextLabel_4.Parent = credits
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_4.Position = UDim2.new(0, 0, 0.24000001, 0)
TextLabel_4.Size = UDim2.new(0, 175, 0, 25)
TextLabel_4.Font = Enum.Font.Gotham
TextLabel_4.Text = "User Interface: Realesses"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 170, 0)
TextLabel_4.TextSize = 12.000

TextLabel_5.Parent = credits
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_5.Position = UDim2.new(0, 0, 0.382857144, 0)
TextLabel_5.Size = UDim2.new(0, 175, 0, 25)
TextLabel_5.Font = Enum.Font.Gotham
TextLabel_5.Text = "Scripts: Bool, Realesses"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 170, 0)
TextLabel_5.TextSize = 12.000

TextLabel_6.Parent = credits
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_6.Position = UDim2.new(0, 0, 0.525714278, 0)
TextLabel_6.Size = UDim2.new(0, 175, 0, 25)
TextLabel_6.Font = Enum.Font.Gotham
TextLabel_6.Text = "Created by: Bool, Realesses"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 170, 0)
TextLabel_6.TextSize = 12.000

sparator_2.Name = "sparator"
sparator_2.Parent = homePanel
sparator_2.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
sparator_2.BorderSizePixel = 0
sparator_2.Position = UDim2.new(0.497826099, 0, 0.294339627, 0)
sparator_2.Size = UDim2.new(0, 1, 0, 175)

DropShadowHolder_6.Name = "DropShadowHolder"
DropShadowHolder_6.Parent = TopBar
DropShadowHolder_6.BackgroundTransparency = 1.000
DropShadowHolder_6.BorderSizePixel = 0
DropShadowHolder_6.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder_6.ZIndex = 0

DropShadow_6.Name = "DropShadow"
DropShadow_6.Parent = DropShadowHolder_6
DropShadow_6.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow_6.BackgroundTransparency = 1.000
DropShadow_6.BorderSizePixel = 0
DropShadow_6.Position = UDim2.new(0.5, 0, 0.466666669, 0)
DropShadow_6.Size = UDim2.new(0.976000011, 47, 0.600000024, 47)
DropShadow_6.ZIndex = 0
DropShadow_6.Image = "rbxassetid://6015897843"
DropShadow_6.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow_6.ImageTransparency = 0.500
DropShadow_6.ScaleType = Enum.ScaleType.Slice
DropShadow_6.SliceCenter = Rect.new(49, 49, 450, 450)

title.Name = "title"
title.Parent = TopBar
title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
title.BackgroundTransparency = 1.000
title.BorderSizePixel = 0
title.Position = UDim2.new(0.299999833, 0, 0, 0)
title.Size = UDim2.new(0, 200, 0, 30)
title.Font = Enum.Font.GothamBold
title.Text = "DARK REAPER - BETA"
title.TextColor3 = Color3.fromRGB(113, 113, 113)
title.TextSize = 12.000

closeImBtn.Name = "closeImBtn"
closeImBtn.Parent = TopBar
closeImBtn.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
closeImBtn.BackgroundTransparency = 1.000
closeImBtn.BorderSizePixel = 0
closeImBtn.Position = UDim2.new(0.949999988, 0, 0.200000092, 0)
closeImBtn.Size = UDim2.new(0, 15, 0, 15)
closeImBtn.Image = "rbxassetid://7072725342"
closeImBtn.MouseButton1Click:Connect(function()
	TopBar.Visible = not TopBar.Visible
end)

minimize.Name = "minimize"
minimize.Parent = TopBar
minimize.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
minimize.BackgroundTransparency = 1.000
minimize.Position = UDim2.new(0.896000028, 0, 0.199999839, 0)
minimize.Size = UDim2.new(0, 15, 0, 15)
minimize.Image = "rbxassetid://7072719338"
minimize.MouseButton1Click:Connect(function()
	container.Visible = not container.Visible
end)

logo.Name = "logo"
logo.Parent = TopBar
logo.BackgroundTransparency = 1.000
logo.Position = UDim2.new(0.0131697357, 0, 0.0699421167, 0)
logo.Rotation = 25.000
logo.Size = UDim2.new(0, 25, 0, 25)
logo.Image = "rbxassetid://7072715827"
logo.ImageColor3 = Color3.fromRGB(255, 51, 0)

-- Scripts:

local function ZUXHTVG_fake_script() -- welcome_Message.LocalScript 
	local script = Instance.new('LocalScript', welcome_Message)

	local User = game.Players.LocalPlayer.Name
	
	script.Parent.Text = "¡Welcome " ..User.. "!"
end
coroutine.wrap(ZUXHTVG_fake_script)()
local function BKAKLYZ_fake_script() -- user_image.LocalScript 
	local script = Instance.new('LocalScript', user_image)

	local image = script.Parent
	local player = game.Players.LocalPlayer
	
	image.Image = 'https://www.roblox.com/headshot-thumbnail/image?userId=' .. player.UserId .. '&width=420&height=420&format=png'
end
coroutine.wrap(BKAKLYZ_fake_script)()
local function WZODB_fake_script() -- userId.LocalScript 
	local script = Instance.new('LocalScript', userId)

	local User = game.Players.LocalPlayer.UserId
	
	script.Parent.Text = "USER ID: " ..User.. ""
end
coroutine.wrap(WZODB_fake_script)()
local function OXVGX_fake_script() -- game_id.LocalScript 
	local script = Instance.new('LocalScript', game_id)

	local GAMEID = game.PlaceId
	
	script.Parent.Text = "GAME ID: " ..GAMEID.. ""
end
coroutine.wrap(OXVGX_fake_script)()
local function DYTNXF_fake_script() -- minimize.LocalScript 
	local script = Instance.new('LocalScript', minimize)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Frame.container.Visible = not script.Parent.Parent.Parent.Frame.container.Visible
	end)
end
coroutine.wrap(DYTNXF_fake_script)()
local function FCCZMF_fake_script() -- TopBar.Dragify 
	local script = Instance.new('LocalScript', TopBar)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
		dragToggle = nil
		dragSpeed = 0.15
		dragInput = nil
		dragStart = nil
		dragPos = nil
		function updateInput(input)
			Delta = input.Position - dragStart
			Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
			game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.15), {Position = Position}):Play()
		end
		Frame.InputBegan:Connect(function(input)
			if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
				dragToggle = true
				dragStart = input.Position
				startPos = Frame.Position
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragToggle = false
					end
				end)
			end
		end)
		Frame.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if input == dragInput and dragToggle then
				updateInput(input)
			end
		end)
	end
	dragify(TopBar)
	
end
coroutine.wrap(FCCZMF_fake_script)()
