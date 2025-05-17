-- Roblox LUA часть — вставь это в Executor
local fileContent = "E4
D#4
E4
D#4
E4
B3
D4
C4
A3
C3
E3
A3
B3
E3
G#3
B3
C4
E4
E4
D#4
E4
D#4
E4
B3
D4
C4
A3
C3
E3
A3
B3
E3
C4
B3
A3
G#3
F#3
E3
" -- Сюда вставишь содержимое файла
local notes = string.split(fileContent, "\n")
for i, note in ipairs(notes) do
    local virtualInput = game:GetService("VirtualInputManager")
    virtualInput:SendKeyEvent(true, note, false, game)
    virtualInput:SendKeyEvent(false, note, false, game)
    wait(0.1)
end
