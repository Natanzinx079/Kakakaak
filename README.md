tpTab:AddButton({
    Name = "Ir para o Castelo",
    Callback = function()
        teleportTo(Vector3.new(-500, 40, 250)) -- Ajuste essa posição conforme necessário
    end
})

tpTab:AddButton({
    Name = "Ir para o Tesla Lab",
    Callback = function()
        teleportTo(Vector3.new(340, 25, -120)) -- Tesla Lab
    end
})

tpTab:AddButton({
    Name = "Ir para a Estação de Trem",
    Callback = function()
        teleportTo(Vector3.new(75, 15, 10)) -- Estação Inicial
    end
})

tpTab:AddButton({
    Name = "Ir para a Área do Zumbi Gigante",
    Callback = function()
        teleportTo(Vector3.new(910, 28, 120)) -- Área de boss/zumbi gigante
    end
})

tpTab:AddButton({
    Name = "Ir para a Fortaleza de Ferro",
    Callback = function()
        teleportTo(Vector3.new(-820, 70, -280)) -- Base fortificada
    end
})
