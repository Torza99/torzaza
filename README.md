while wait() do
    game:GetService("ReplicatedStorage").Remote.Weapon.TakeDamage:FireServer()
end
