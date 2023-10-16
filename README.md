# Hub Roxinha

---

#### Local

```lua
local DarkraiX = loadstring(game:HttpGet("", true))()
```

---

#### Window

```lua
local Library = DarkraiX:Window("Nome","Nome Do Jogo","Logo",Enum.KeyCode.RightControl);

--[[
Nome ~ O Nome Que Tu Quer Na Hub

Nome Do Jogo ~ O Nome Do Jogo Que Vai Aparece Do Lado Do Nome Da Hub( Se Você Não Colocar Nada No Nome Do Jogo, Ele Vai Automaticamente Vai Coloca O Nome Do Jogo Atual Que Você Está

Logo ~ A Logo Que Vai Aparece No Script Caso Você Tenha Uma Logo
);
]]
```

---

#### Tabs

```lua
Tab1 = Library:Tab("Nome")

--[[
Tab1 ~ A Indentificação Da Tab

Nome ~ O Nome Da Tab Que Você Quer
);
]]
```

---

#### Botões

```lua
Tab1:Button("Nome",function()
    print("bruh")
end)

--[[
Tab1 ~ A Indentificação Em Que O Botão Vai Fica Na Tab

Nome ~ O Nome Que Vai Aparece No Botão

print("bruh") ~ O Script Que Vai Executar Ao Clicar No Botão
);
]]
```

---
