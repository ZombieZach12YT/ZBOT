local args = {
    [1] = game:GetService("Players").LocalPlayer.Character.M4A1,
    [2] = workspace.Tycoon.Tycoons.Echo.PurchasedObjects:FindFirstChild("Shooting Range").Target2.Hitmaker,
    [3] = Vector3.new(3097.051513671875, 67.68191528320312, -1695.3983154296875),
    [4] = {
        [1] = {
            [1] = Vector3.new(3085.31787109375, 68.11261749267578, -1692.830810546875),
            [2] = Vector3.new(0.9762578010559082, -0.03583516925573349, -0.2136271446943283),
            [3] = 3.421067953109741
        },
        [2] = {} --[[DUPLICATE]]
    },
    [5] = Vector3.new(-1, -9.380573260386882e-07, 2.605150370982301e-07),
    [6] = {
        ["Mode"] = "Auto",
        ["MaxSpread"] = 35,
        ["MaxRecoilPower"] = 3.5,
        ["Distance"] = 3200,
        ["BSpeed"] = 2200,
        ["FireRate"] = 650
    }
}

args[4][2] = args[4][1]
game:GetService("ReplicatedStorage").BulletFireSystem.BulletHit:FireServer(unpack(args))
