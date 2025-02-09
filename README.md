local args = {
    [1] = {
        [1] = {
            [1] = "\3",
            [2] = "Teleport",
            [3] = "To",
            [4] = 6
        }
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("RemoteEvent"):FireServer(unpack(args))
