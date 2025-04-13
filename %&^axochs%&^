local Rayfield = loadstring(game:HttpGet('https://raw.githubusercontent.com/madmad7070/gui/refs/heads/main/gui'))()

local Window = Rayfield:CreateWindow({
   Name = "니미 허브 1.2v",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "로딩중",
   LoadingSubtitle = "by chs",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("메인😊", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "칼로 다죽이기(칼 꺼내기 Z,X,C,V)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/regentcon/kill/refs/heads/main/QAWD"))()
end,
})

local Button = Tab:CreateButton({
   Name = "AK47",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/sinret/rbxscript.com-scripts-reuploads-/main/ak47", true))()
end,
})

local Button = Tab:CreateButton({
   Name = "검 모드",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/regentcon/awdawdasd/refs/heads/main/awdasdawdasd"))()
end,
})

local Button = Tab:CreateButton({
   Name = "모든 아이템 가져오기",
   Callback = function()
local toolFolder = workspace:FindFirstChild("Tools")
if toolFolder then
    for _, tool in pairs(toolFolder:GetChildren()) do
        if tool:IsA("Tool") then
            tool.Parent = game.Players.LocalPlayer.Backpack
        end
    end
end

end,
})

local Button = Tab:CreateButton({
   Name = "오토 슬랩",
   Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Slap-Tower-Slap-Tower-Works-Other-Slap-Gamep*-Games-too-34092"))()

end,
})

local Button = Tab:CreateButton({
   Name = "무적(E홀드)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/mujck/refs/heads/main/da"))()

end,
})

local Button = Tab:CreateButton({
   Name = "올 폴링",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/allfling/refs/heads/main/allfling"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "터치? 플링",
   Callback = function()
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local RunService = game:GetService("RunService")
local Players = game:GetService("Players")

local hiddenfling = true

-- 챗지피티 나이스!
if not ReplicatedStorage:FindFirstChild("juisdfj0i32i0eidsuf0iok") then
	local detection = Instance.new("Decal")
	detection.Name = "juisdfj0i32i0eidsuf0iok"
	detection.Parent = ReplicatedStorage
end

-- fling 함수 정의
local function fling()
	local hrp, c, vel, movel = nil, nil, nil, 0.1
	local lp = Players.LocalPlayer

	while true do
		RunService.Heartbeat:Wait()

		if hiddenfling then
			while hiddenfling and not (c and c.Parent and hrp and hrp.Parent) do
				RunService.Heartbeat:Wait()
				c = lp.Character
				hrp = c and c:FindFirstChild("HumanoidRootPart")
			end

			if hiddenfling then
				vel = hrp.Velocity
				hrp.Velocity = vel * 10000 + Vector3.new(0, 10000, 0)
				RunService.RenderStepped:Wait()
				if c and c.Parent and hrp and hrp.Parent then
					hrp.Velocity = vel
				end
				RunService.Stepped:Wait()
				if c and c.Parent and hrp and hrp.Parent then
					hrp.Velocity = vel + Vector3.new(0, movel, 0)
					movel = movel * -1
				end
			end
		end
	end
end

-- fling 코루틴 실행
coroutine.wrap(fling)()

   end,
})

local Button = Tab:CreateButton({
   Name = "노무허브 콜라보(베스트)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/RuMinGay/nomu-hub523/refs/heads/main/nomu%20hub523"))()
   end,
})

local Toggle = Tab:CreateToggle({
    Name = "자동 채팅🗣️",
    CurrentValue = false,
    Callback = function(state)
        _G.padrip = state

        task.spawn(function()
            while _G.padrip do
                local texts = {
                    ":                                                                                                                                      시스템 : 버그로인하여 곧 셧다운됩니다.",
                    ": 레벨이 밥 먹여주디?",
                    ": 로블에 박혀있는 찐;;특 나오노 ㅋ",
                    ": ㅂ;;ㅅ ㅋㅋㅋㅋ 말;;빨 검나 딸리네",
                    ": ㅂ;;ㅅ 니 가;;;;족 마냥 아무것도 모타죠?? ㅋ",
                    ": ㅂㄷㅂㄷ?? 긁? 긁혔노 이 ;; 기 야 ㅋㅋ"
                }

                for _, text in ipairs(texts) do
                    if not _G.padrip then break end
                    game:GetService("TextChatService").ChatInputBarConfiguration.TargetTextChannel:SendAsync(""..string.rep("\r",1)..text)
                    task.wait(_G.ChatDelay) -- ✅ 슬라이더에서 설정된 값으로 딜레이 적용
                end
            end
        end)
    end
})


-- 기본 딜레이 값 설정
_G.ChatDelay = 1 -- 기본 1초

-- 슬라이더 추가
local Slider = Tab:CreateSlider({
    Name = "채팅 딜레이 (초)",
    Range = {0.1, 50}, -- 0.1초 ~ 5초 사이 조절 가능
    Increment = 0.1,
    Suffix = "초",
    CurrentValue = 1,
    Callback = function(Value)
        _G.ChatDelay = Value
    end,
})


local Tab = Window:CreateTab("어드민👑", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

Rayfield:Notify({
   Title = "인젝됨",
   Content = "즐겨",
   Duration = 6.5,
   Image = 4483362458,
})

local Button = Tab:CreateButton({
   Name = "SituationAdmin👑",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Teemsploit/SituationAdmin.lua/main/admin.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "백도어 어드민👑",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/admin/refs/heads/main/admin"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "인피니티 야드👑",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

local Tab = Window:CreateTab("타워🏢", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "칼타워 전용 올킬",
   Callback = function()
-- .gg/localx
-- 백팩에 칼 있는 상태에서 K 눌러야 작동합니다
local sword = "ClassicSword"
-- "" <- 여기 안에 칼 이름 쓰시면 됩니다.
local Players = game:GetService('Players')
local UserInputService = game:GetService('UserInputService')
local client = Players.LocalPlayer

local function dbug(txt)
print(`[LocalX]: {txt}`)
end

-- 칼 있는지 확인
_G.have_sword = false
if client.Character:FindFirstChild(sword) then
    dbug('칼이 존재합니다!')
    client.Character:FindFirstChild(sword).Parent = client.Backpack
elseif client.Backpack:FindFirstChild(sword) then
    dbug('칼이 존재합니다!')
else

    dbug('칼을 구하는 중입니다...')
    local search_sword = workspace.ChildAdded:Connect(function(obj)
    
    if obj:IsA('Tool') and obj.Name == sword and obj:FindFirstChild('Handle') then
    client.Character.Humanoid:EquipTool(obj)
    task.wait(.2)
    obj.Parent = client.Backpack
    dbug('칼을 성공적으로 얻었습니다!')
    _G.have_sword = true
    end
    end)

    repeat wait(.1) until _G.have_sword
    print('aaa')
    search_sword:Disconnect()
end

if not _G.Sword_Exploit_Executed then
    _G.Sword_Exploit_Executed = true
    _G.Sword_Exploit = false

    UserInputService.InputBegan:Connect(function(input, ...)
        if input.KeyCode == Enum.KeyCode.K then
            assert(client.Character:FindFirstChild(sword), '칼을 착용 후 다시 시도하세요.')
            _G.Sword_Exploit = not _G.Sword_Exploit
            print(_G.Sword_Exploit)
            if _G.Sword_Exploit then

                repeat
                    task.wait()

                    for _, plr in pairs(Players:GetPlayers()) do
                        if plr ~= client then
                            pcall(function()
                                firetouchinterest(client.Character:FindFirstChild(sword).Handle, plr.Character:FindFirstChild('HumanoidRootPart'), 0)
                                task.wait()
                                firetouchinterest(client.Character:FindFirstChild(sword).Handle, plr.Character:FindFirstChild('HumanoidRootPart'), 1)
                            end)
                        end
                    end
                until not _G.Sword_Exploit or not client.Character:FindFirstChild(sword)
                dbug('end')
                _G.Sword_Exploit = false
            end

        end
    end)
end

print(_G.Sword_Exploit_Executed)
   end,
})

local Button = Tab:CreateButton({
   Name = "월홉🏢(Q)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/wallhop/refs/heads/main/wallhop"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "빡종타 전용 트롤구간 아예없애버리기🏢",
   Callback = function()
-- .gg/localx
-- 건드리면 에러 남
local poss = {
    Vector3.new(29, 260.5, 112.04998779296875),
    Vector3.new(29, 260.5, 107.94999694824219),
    Vector3.new(29, 260.5, 104.04999542236328),
    Vector3.new(29, 260.5, 96.99998474121094),
    Vector3.new(29, 260.5, 92.99998474121094),
    Vector3.new(29, 260.5, 85.99998474121094),
    Vector3.new(29, 260.5, 81.99998474121094),
    Vector3.new(29, 260.5, 74.99998474121094),
    Vector3.new(29, 260.5, 70.99998474121094)
}

_G.Parts = {}

for _, part in ipairs(workspace:GetChildren()) do
    if part:IsA('BasePart') and table.find(poss, part.Position) then
        warn(part)
        table.insert(_G.Parts, part)
    end
end
print('done!!')
table.foreach(_G.Parts, print)


while task.wait() do
for _, part in ipairs(_G.Parts) do
firetouchinterest(game.Players.LocalPlayer.Character.Head, part, 0)
task.wait()
firetouchinterest(game.Players.LocalPlayer.Character.Head, part, 1)
end
end
   end,
})

local Tab = Window:CreateTab("가강전✊", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "무적(E홀드)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/mujck/refs/heads/main/da"))()

end,
})

local Button = Tab:CreateButton({
   Name = "올 폴링",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/allfling/refs/heads/main/allfling"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "원하는 사람 폴링",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/fling/refs/heads/main/fling"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "가로우 전용 1번 즉사(크래딧:크아)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/firstkill/refs/heads/main/firstkill"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "진격의거인",
   Callback = function()
   loadstring(game:HttpGet("https://paste.ee/r/fxY03"))()
   end, 
})

local Button = Tab:CreateButton({
   Name = "블랙피규어(KJ)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/fartmaggot445/KYR/refs/heads/main/kj"))()
   end,
})


local Button = Tab:CreateButton({
   Name = "무한 쓰레기통(크래딧:크아)",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/yes1nt/yes/refs/heads/main/Trashcan%20Man", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "이거 좋음",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DiosDi/VexonHub/refs/heads/main/VexonHub"))()   end,
})

local Tab = Window:CreateTab("라이벌🔫", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "무적(E홀드)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/mujck/refs/heads/main/da"))()

end,
})

local Button = Tab:CreateButton({
   Name = "너검마 스크",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubRivals"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "autowin",
   Callback = function()
   loadstring(game:HttpGet(('https://raw.githubusercontent.com/venoxhh/universalscripts/main/rivals/autowin.lua')))()
   end, 
})

local Button = Tab:CreateButton({
   Name = "이거 스무스 올리면 ㄹㅇ 고트",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/bast-hack-exporoit-ronix-/refs/heads/main/bastaimbot"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "슬라이언트가 ㄹㅇ 고트",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/4lf0rkz/refs/heads/main/4lf0rkz"))()
   end,
})



local Button = Tab:CreateButton({
   Name = "하앙 기무찌",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/ThunderScriptSolutions/Misc/refs/heads/main/RivalsSilentAim'))()
   end,
})


local Button = Tab:CreateButton({
   Name = "8bit",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/8bit/refs/heads/main/8bit"))()
   end,
})

local Tab = Window:CreateTab("FE🎸", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "딸1딸이👌👈",
   Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Jerk-off-29302"))()
   end,
})


local Button = Tab:CreateButton({
   Name = "FE커스텀 툴",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/inkdupe/hat-scripts/refs/heads/main/customtools.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "FE가짜 vr(모자잇어야됨)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/randomstring0/Qwerty/refs/heads/main/qwerty45.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "FE자2지(ㅈㄴ큼 ㅈㄴ웃김 ㅅㅂㅋㅋㅋ 모자잇어야 작동 ㅇㅇ)",
   Callback = function()
loadstring(game:HttpGet("https://paste.ee/r/ZYsvl5qS/0", true))()
   end,
})

local Tab = Window:CreateTab("한머🤣", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "베스트 ㅇㅇ",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/koreamadher/refs/heads/main/gksrnrajej"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "esp",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/minute124/RH-666-/refs/heads/main/ee454504248d2435.lua'))()
   end, 
})

local Tab = Window:CreateTab("암보결🖤", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "힛박 키우기",
   Callback = function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Update-script-hitbox-9326"))()
   end,
})

local Tab = Window:CreateTab("베드워즈🍕", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

 local Button = Tab:CreateButton({
   Name = "배드워즈 vape",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
   end,
})

local Tab = Window:CreateTab("프리즌라이프🤩", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "프리즌 라이프 어드민",
   Callback = function()
   loadstring(game:HttpGet("https://scriptblox.com/raw/Prison-Life-Prizz-Admin-14511"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "낫베드",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))()
   end,
})

local Tab = Window:CreateTab("아스널🧤", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "킬올 있음",
   Callback = function()
   loadstring(game:HttpGet('https://api.luarmor.net/files/v3/loaders/b95e8fecdf824e41f4a030044b055add.lua'))()
   end, 
})

local Tab = Window:CreateTab("부대테러😶‍🌫️", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "키 FLY",
   Callback = function()
   loadstring(game:HttpGet(('https://raw.githubusercontent.com/SinEunByeol/DGHub/refs/heads/main/NoObfuscator')))()
   end, 
})

local Tab = Window:CreateTab("블레이드 피구⚔️", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "블피-키-vortex42244",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Jayson24244/Vortex/refs/heads/main/Bloxfruit", true))()
   end, 
})

local Button = Tab:CreateButton({
   Name = "오토팜가능",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/CheemsNhuChiAl/Sotringhuhu/main/StrawberryHubBeta1.35"))()
   end, 
})

local Button = Tab:CreateButton({
   Name = "헙",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
   end, 
})

local Button = Tab:CreateButton({
   Name = "레벨업",
   Callback = function()
   loadstring(game:HttpGet("https://bonkhubloader.netlify.app",true))()
   end, 
})

local Tab = Window:CreateTab("머더2❤️", nil) -- Title, Image
local Section = Tab:CreateSection("메인")

local Button = Tab:CreateButton({
   Name = "머더2",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/vertex-peak/vertex/refs/heads/main/loadstring"))()
   end, 
})

local Button = Tab:CreateButton({
   Name = "스껄",
   Callback = function()
   loadstring(game:HttpGet(("https://raw.githubusercontent.com/Yousuck780/mm2/main/mm2"), true))()
   end, 
})

