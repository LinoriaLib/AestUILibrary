local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "CustomLibraryUI"
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

local Frame = Instance.new("Frame")
Frame.Name = "MainFrame"
Frame.Position = UDim2.new(0.165799, 0, 0.19933, 0)
Frame.Size = UDim2.new(0, 713, 0, 358)
Frame.BackgroundColor3 = Color3.new(0, 0, 0)
Frame.BackgroundTransparency = 0.25
Frame.BorderSizePixel = 0
Frame.Parent = ScreenGui

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 8)
UICorner.Parent = Frame

local TitleBar = Instance.new("Frame")
TitleBar.Name = "TitleBar"
TitleBar.Position = UDim2.new(0, 0, 0, 0)
TitleBar.Size = UDim2.new(1, 0, 0, 25)
TitleBar.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
TitleBar.BackgroundTransparency = 0.25
TitleBar.BorderSizePixel = 0
TitleBar.Parent = Frame

local TitleBarCorner = Instance.new("UICorner")
TitleBarCorner.CornerRadius = UDim.new(0, 8)
TitleBarCorner.Parent = TitleBar

local CloseButton = Instance.new("TextButton")
CloseButton.Name = "CloseButton"
CloseButton.Position = UDim2.new(0.96, 0, 0, 0)
CloseButton.Size = UDim2.new(0, 26, 0, 25)
CloseButton.BackgroundTransparency = 1
CloseButton.Text = "X"
CloseButton.TextColor3 = Color3.new(1, 1, 1)
CloseButton.TextSize = 20
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Parent = TitleBar

CloseButton.MouseButton1Click:Connect(function()
    ScreenGui:Destroy()
end)
