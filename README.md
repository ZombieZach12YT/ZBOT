local args = {
    [1] = game:GetService("Players").LocalPlayer.Character.M17,
    [2] = {
        ["VPunchBase"] = 5,
        ["BoltExtend"] = Vector3.new(0, 0, 0.22499999403953552),
        ["FocusOnSight"] = false,
        ["Chambered"] = false,
        ["Ammo"] = 17,
        ["FireRate"] = 550,
        ["Tracer"] = true,
        ["Mode"] = "Semi",
        ["PunchRecover"] = 0.2,
        ["BurstFireRate"] = 900,
        ["MinRecoilPower"] = 1,
        ["ReloadType"] = 1,
        ["MaxRecoilPower"] = 3,
        ["LeftPos"] = CFrame.new(0.8500000238418579, -0.15000000596046448, -1.5499999523162842) * CFrame.Angles(-2.094395160675049, 0.3490658402442932, -0.4363323450088501),
        ["TracerColor"] = nil --[[Color3]],
        ["BulletFlareColor"] = nil --[[Color3]],
        ["ChangeFOV"] = {
            [1] = 60,
            [2] = 60
        },
        ["BDrop"] = 0.25,
        ["MinSpread"] = 5,
        ["BulletFlare"] = false,
        ["ChamberWhileAim"] = false,
        ["IncludeChamberedBullet"] = true,
        ["HRecoil"] = {
            [1] = 1,
            [2] = 4
        },
        ["ServerGunPos"] = CFrame.new(-0.30000001192092896, -1, -0.4000000059604645) * CFrame.Angles(-1.5707963705062866, 0, -0),
        ["VRecoil"] = {
            [1] = 1,
            [2] = 1
        },
        ["AimRecover"] = 1,
        ["LeftArmPos"] = CFrame.new(1.149999976158142, -0.10000000149011612, -1.649999976158142) * CFrame.Angles(-2.094395160675049, 0.3490658402442932, -0.4363323450088501),
        ["RightArmPos"] = CFrame.new(-0.574999988079071, 0.6499999761581421, -1.184999942779541) * CFrame.Angles(-1.5707963705062866, 0, -0),
        ["BurstShot"] = 3,
        ["SlideExtend"] = Vector3.new(0, 0, 0.22499999403953552),
        ["RecoilPowerStepAmount"] = 0.5,
        ["BoltLock"] = false,
        ["RecoilPunch"] = 0.25,
        ["GunFOVReduction"] = 5,
        ["MaxSpread"] = 35,
        ["SlideLock"] = true,
        ["GunType"] = 0,
        ["AutoChamber"] = false,
        ["GunPos"] = CFrame.new(0.15000000596046448, -0.15000000596046448, 1) * CFrame.Angles(1.5707963705062866, 0, -0),
        ["BSpeed"] = 2000,
        ["GunSize"] = 1,
        ["HPunchBase"] = 1.75,
        ["FastReload"] = true,
        ["RightPos"] = CFrame.new(-0.4000000059604645, 0.6499999761581421, -1) * CFrame.Angles(-1.5707963705062866, 0, -0),
        ["MoveBolt"] = false,
        ["FocusOnSight2"] = false,
        ["Distance"] = 500,
        ["AimRecoilReduction"] = 1,
        ["SwayBase"] = 0.25,
        ["DamageMultiplier"] = 1,
        ["WalkMultiplier"] = 0,
        ["AimInaccuracyStepAmount"] = 2.5,
        ["FireModes"] = {
            ["Burst"] = false,
            ["Semi"] = true,
            ["Auto"] = false,
            ["ChangeFiremode"] = false,
            ["Explosive"] = false
        },
        ["DPunchBase"] = 1,
        ["Bullets"] = 1
    }
}

game:GetService("ReplicatedStorage").ACS_Engine.Events.Equip:FireServer(unpack(args))

