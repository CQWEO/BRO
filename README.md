game:GetService("Workspace").CurrentRooms.DescendantAdded:Connect(function(v)
    if not _G.IncreasedDistance then return end
    if v.IsA(v,"ProximityPrompt") then
       if _G.IncreasedDistance then
           v.MaxActivationDistance *= _G.IncreasedDistance and 2 or 0.5
       end
    end
end)
--<<>>-->
local v0=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/Gui%20Lib%20%5BLibrary%5D"))();local v1=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/Gui/main/Gui%20Lib%20%5BThemeManager%5D"))();local v2=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/Gui/main/Gui%20Lib%20%5BSaveManager%5D"))();local v3=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/Blackking%20%5BGuiNew!%5D"))();local v4=Instance.new("Sound");v4.Parent=game.SoundService;v4.SoundId="rbxassetid://4590657391";v4.Volume=5;v4.PlayOnRemove=true;v4:Destroy();v0:Notify("Loading...");v3:Introduction();wait(1999 -(1805 + 193) );v0:Notify("Loaded");local v10={"RushMoving","AmbushMoving","Snare","A60","A120","SeekMoving","JeffTheKiller","Eyes"};local v11={"Candle","Crucifix","SkeletonKey","Vitamins","Lockpick","Lighter","Flashlight"};local v12=game.Players.LocalPlayer;local v13=v12.Character or v12.CharacterAdded:Wait() ;local v14=v13:FindFirstChildOfClass("Humanoid") or v13:WaitForChild("Humanoid") ;if  not fireproximityprompt then local v226=Instance.new("Message",workspace);v226.Text="you have fireproximityprompt function bro get better executor";task.wait(12 -6 );v226:Destroy();error("no prox");end function esp(v63,v64,v65,v66)local v67=0 -0 ;local v68;local v69;local v70;local v71;while true do if (v67==(1 + 2)) then if (v65 and v66) then local v431=1690 -(1121 + 569) ;local v432;local v433;while true do if (v431==2) then v432.Size=UDim2.new(214 -(22 + 192) ,691 -(483 + 200) ,0,8);v432.Position=UDim2.new(1463.5 -(1404 + 59) ,0 -0 ,0.5,0 -0 );Instance.new("UICorner",v432).CornerRadius=UDim.new(1,765 -(468 + 297) );Instance.new("UIStroke",v432);v431=565 -(334 + 228) ;end if (v431==3) then v433=Instance.new("TextLabel",v69);v433.AnchorPoint=Vector2.new(0.5 -0 ,0.5 -0 );v433.BackgroundTransparency=1 -0 ;v433.BackgroundColor3=v64;v431=2 + 2 ;end if (5==v431) then v433.FontSize=Enum.FontSize.Size10;v433.Text=v66;Instance.new("UIStroke",v433);task.spawn(function()while v69 do if ((v69.Adornee==nil) or  not v69.Adornee:IsDescendantOf(workspace)) then local v882=236 -(141 + 95) ;while true do if (v882==(0 + 0)) then v69.Enabled=false;v69.Adornee=nil;v882=1;end if (v882==1) then v69:Destroy();break;end end end task.wait();end end);break;end if (v431==4) then v433.TextColor3=v64;v433.Size=UDim2.new(2 -1 ,0 -0 ,0 + 0 ,136 -86 );v433.Position=UDim2.new(0.5,0,0.6,0);v433.Font=Enum.Font.Gotham;v431=4 + 1 ;end if (1==v431) then v69.MaxDistance=1042 + 958 ;v432=Instance.new("Frame",v69);v432.AnchorPoint=Vector2.new(0.5 -0 ,0.5);v432.BackgroundColor3=v64;v431=2 + 0 ;end if ((163 -(92 + 71))==v431) then v69=Instance.new("BillboardGui",game.CoreGui);v69.AlwaysOnTop=true;v69.Size=UDim2.new(0,400,0 + 0 ,168 -68 );v69.Adornee=v65;v431=766 -(574 + 191) ;end end end v71={};v67=4 + 0 ;end if ((9 -5)==v67) then v71.delete=function()for v434,v435 in pairs(v70) do local v436=0 + 0 ;while true do if (v436==(849 -(254 + 595))) then v435.Adornee=nil;v435.Visible=false;v436=127 -(55 + 71) ;end if (v436==1) then v435:Destroy();break;end end end if v69 then local v505=0 -0 ;while true do if (v505==(1791 -(573 + 1217))) then v69:Destroy();break;end if (v505==0) then v69.Enabled=false;v69.Adornee=nil;v505=2 -1 ;end end end end;return v71;end if (v67==(1 + 1)) then for v363,v364 in pairs(v68) do if v364:IsA("BasePart") then table.insert(v70,box);task.spawn(function()while box do local v704=0 -0 ;while true do if (v704==(939 -(714 + 225))) then if ((box.Adornee==nil) or  not box.Adornee:IsDescendantOf(workspace)) then box.Adornee=nil;box.Visible=false;box:Destroy();end task.wait();break;end end end end);end end function hightlightoutboi(v365,v366)local v367;if v366:FindFirstChildOfClass("Highlight") then v367=v366:FindFirstChildOfClass("Highlight");v367.OutlineColor=v365;v367.OutlineTransparency=0 -0 ;v367.FillColor=v365;v367.FillTransparency=0.5 -0 ;else local v510=0 + 0 ;while true do if (v510==(2 -0)) then v367.FillTransparency=806.5 -(118 + 688) ;v367.OutlineColor=v365;v510=51 -(25 + 23) ;end if (v510==(0 + 0)) then v367=Instance.new("Highlight",v366);v367.Enabled=true;v510=1887 -(927 + 959) ;end if (v510==(3 -2)) then v367.Name="Esphihihi";v367.FillColor=v365;v510=734 -(16 + 716) ;end if (v510==(5 -2)) then v367.OutlineTransparency=0;break;end end end local v368={};v368.delete=function()v367:Destroy();end;return v368;end v67=100 -(11 + 86) ;end if (v67==(2 -1)) then v69=nil;v70={};v67=287 -(175 + 110) ;end if (v67==(0 -0)) then v68=nil;if (typeof(v63)=="Instance") then if v63:IsA("Model") then v68=v63:GetChildren();elseif v63:IsA("BasePart") then v68={v63,table.unpack(v63:GetChildren())};end elseif (typeof(v63)=="table") then v68=v63;end v67=1797 -(503 + 1293) ;end end end local v15=game.ReplicatedStorage:WaitForChild("EntityInfo");function message(v72)local v73=0 -0 ;local v74;while true do if (v73==1) then task.wait(4 + 1 );v74:Destroy();break;end if (v73==0) then v74=Instance.new("Message",workspace);v74.Text=tostring(v72);v73=1;end end end local v16={espdoors=false,espkeys=false,espitems=false,espbooks=false,esprush=false,espchest=false,esplocker=false,esphumans=false,espgold=false,goldespvalue=1061 -(810 + 251) ,hintrush=false,hintrushhee=false,light=false,instapp=false,noseek=false,nogates=false,nopuzzle=false,noa90=false,noskeledoors=false,noseekarmsfire=false,noscreech=false,nodupe=false,getcode=false,getcodet=false,roomsnolock=false,draweraura=false,autorooms=false,itemsaura=false,autopulllever=false,bookcollecter=false,breakercollecter=false};local v17={table.unpack(v16)};local v18={doors={},keys={},items={},books={},entity={},chests={},lockers={},people={},gold={}};local v19=CFrame.new;local v20=game:GetService("ReplicatedStorage").GameData.LatestRoom;local v21=game:GetService("ReplicatedStorage").GameData.ChaseStart;local v22;v22=hookmetamethod(game,"__namecall",function(v75,...)local v76=0 + 0 ;local v77;local v78;while true do if (v76==(0 + 0)) then v77={...};v78=getnamecallmethod();v76=534 -(43 + 490) ;end if (v76==(734 -(711 + 22))) then if ((tostring(v75)=="Screech") and (v78=="FireServer") and getgenv().avoidsc) then local v437=0;while true do if (v437==(0 -0)) then v77[860 -(240 + 619) ]=true;return v22(v75,unpack(v77));end end end if ((tostring(v75)=="ClutchHeartbeat") and (v78=="FireServer") and getgenv().winhb) then v77[2]=true;return v22(v75,unpack(v77));end v76=1 + 1 ;end if (v76==(2 -0)) then return v22(v75,...);end end end);workspace.ChildAdded:Connect(function(v79)task.wait();if ((v79.Name=="RushMoving") or (v79.Name=="AmbushMoving")) then while workspace:FindFirstChild(v79.Name) and getgenv().hxde  do task.wait();part=v79:WaitForChild("RushNew");game.Players.LocalPlayer.Character.Collision.CFrame=CFrame.new(part.Position + Vector3.new(0 + 0 ,1819 -(1344 + 400) ,0) );end end end);local v23=Instance.new("ScreenGui");local v24=Instance.new("Frame");local v25=Instance.new("TextButton");v23.Name="GodmodeMobile";v23.Parent=game:WaitForChild("CoreGui");v23.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;game:GetService("CoreGui").GodmodeMobile.Enabled=false;v24.Parent=v23;v24.BackgroundColor3=Color3.fromRGB(405 -(255 + 150) ,255,0 + 0 );v24.Position=UDim2.new(0.412993044,0,0.0562249012 + 0 ,0);v24.Size=UDim2.new(0 -0 ,645 -445 ,0,1785 -(404 + 1335) );v25.Parent=v24;v25.BackgroundColor3=Color3.fromRGB(661 -(183 + 223) ,0 -0 ,0 + 0 );v25.Position=UDim2.new(0.0350000001 + 0 ,0,0.0652173907,0);v25.Size=UDim2.new(337 -(10 + 327) ,187,0,40);v25.Font=Enum.Font.SourceSans;v25.Text="God Mode : off";v25.TextColor3=Color3.fromRGB(0 + 0 ,0,0);v25.TextSize=374 -(118 + 220) ;v25.MouseButton1Down:connect(function()if (_G.godkuy==true) then local v238=0;local v239;local v240;local v241;while true do if (v238==(1 + 1)) then v239=game.Players.LocalPlayer.Character:FindFirstChild("Collision");v239.Position=v239.Position + Vector3.new(449 -(108 + 341) ,5,0) ;v240=nil;v238=2 + 1 ;end if (v238==(21 -16)) then v241.Volume=1498 -(711 + 782) ;v241.PlayOnRemove=true;v241:Destroy();break;end if (v238==(5 -2)) then function v240(v511)firesignal(game.ReplicatedStorage.EntityInfo.Caption.OnClientEvent,v511);end v240("GodMode Disabled");v25.Text="God Mode : Off";v238=4;end if (v238==(473 -(270 + 199))) then v241=Instance.new("Sound");v241.Parent=game.SoundService;v241.SoundId="rbxassetid://4590657391";v238=2 + 3 ;end if (v238==0) then _G.godkuy=false;getgenv().colgod=false;for v512,v513 in next,game.Players.LocalPlayer.Character:GetDescendants() do if (v513.IsA(v513,"BasePart") and (getgenv().colgod==false)) then v513.CanCollide=true;end end v238=1820 -(580 + 1239) ;end if (v238==1) then v239=game.Players.LocalPlayer.Character:FindFirstChild("Collision");v239.Position=v239.Position + Vector3.new(0 -0 ,5 + 0 ,0 + 0 ) ;wait(0.5 + 0 );v238=4 -2 ;end end elseif (_G.godkuy==false) then local v370=0;local v371;local v372;local v373;while true do if (v370==2) then function v372(v707)firesignal(game.ReplicatedStorage.EntityInfo.Caption.OnClientEvent,v707);end v372("GodMode Enabled");v25.Text="God Mode : On";v373=Instance.new("Sound");v370=2 + 1 ;end if (v370==(1170 -(645 + 522))) then v373.Parent=game.SoundService;v373.SoundId="rbxassetid://4590657391";v373.Volume=1795 -(1010 + 780) ;v373.PlayOnRemove=true;v370=4 + 0 ;end if (v370==(19 -15)) then v373:Destroy();break;end if (v370==(0 -0)) then _G.godkuy=true;v371=game.Players.LocalPlayer.Character:FindFirstChild("Collision");v371.Position=v371.Position-Vector3.new(0,1841 -(1045 + 791) ,0 -0 ) ;wait(0.5 -0 );v370=506 -(351 + 154) ;end if (v370==(1575 -(1281 + 293))) then getgenv().colgod=true;v371=game.Players.LocalPlayer.Character:FindFirstChild("Collision");v371.Position=v371.Position-Vector3.new(266 -(28 + 238) ,10 -5 ,1559 -(1381 + 178) ) ;v372=nil;v370=2;end end end end);local v4=Instance.new("Sound");v4.Parent=game.SoundService;v4.SoundId="rbxassetid://4590657391";v4.Volume=5 + 0 ;v4.PlayOnRemove=true;v4:Destroy();local v44=v0:CreateWindow({Title="YOU HUB"});local v45={Main=v44:AddTab("Main")};local v46=v45.Main:AddLeftGroupbox(" ");game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.FullBright then local v315=0 + 0 ;while true do if (v315==1) then game:GetService("Lighting").ClockTime=47 -33 ;game:GetService("Lighting").GlobalShadows=false;v315=2;end if (v315==0) then game:GetService("Lighting").FogEnd=100000;game:GetService("Lighting").Brightness=3;v315=1;end if (v315==(1996 -(109 + 1885))) then game:GetService("Lighting").OutdoorAmbient=Color3.new(1,1,1);break;end end end end);end);v46:AddToggle("MyToggle",{Text="No Darkness Light On All",Default=false,Tooltip="No Darkness Light On All",Callback=function(v88)if v88 then _G.FullBright=true;else _G.FullBright=false;game:GetService("Lighting").FogEnd=11111111533265722 -(802 + 24) ;game:GetService("Lighting").Brightness=5 -2 ;game:GetService("Lighting").ClockTime=20;game:GetService("Lighting").GlobalShadows=false;game:GetService("Lighting").OutdoorAmbient=Color3.new(1,1,1);end end});v46:AddToggle("MyToggle",{Text="No Halt On Rooms",Default=false,Tooltip="Anti Halt",Callback=function(v122)local v123=0;while true do if (v123==(1480 -(641 + 839))) then _G.BypassHalte=v122;if (_G.BypassHalte==true) then local v472=913 -(910 + 3) ;local v473;while true do if (v472==(0 -0)) then v473=game:GetService("ReplicatedStorage").ClientModules.EntityModules.Shade;v473.Parent=game.Workspace;break;end end elseif (_G.BypassHalte==false) then local v642=1684 -(1466 + 218) ;local v643;while true do if (v642==(0 + 0)) then v643=game.Workspace.Shade;v643.Parent=game:GetService("ReplicatedStorage").ClientModules.EntityModules;break;end end end break;end end end});v46:AddToggle("MyToggle",{Text="No Glitch And Void JumpScare",Default=false,Tooltip="Anti Glitch & Void No JumpScares",Callback=function(v124)local v125=1148 -(556 + 592) ;while true do if (v125==(0 + 0)) then _G.GV=v124;if (_G.GV==true) then local v474=808 -(329 + 479) ;local v475;local v476;while true do if (v474==1) then v475.Parent=game.Workspace;v476.Parent=game.Workspace;break;end if (v474==(854 -(174 + 680))) then v475=game:GetService("ReplicatedStorage").ClientModules.EntityModules.Glitch;v476=game:GetService("ReplicatedStorage").ClientModules.EntityModules.Void;v474=3 -2 ;end end elseif (_G.GV==false) then local v644=0 -0 ;local v645;local v646;while true do if (v644==0) then v645=game.Workspace.Glitch;v646=game.Workspace.Void;v644=1 + 0 ;end if ((740 -(396 + 343))==v644) then v645.Parent=game:GetService("ReplicatedStorage").ClientModules.EntityModules;v646.Parent=game:GetService("ReplicatedStorage").ClientModules.EntityModules;break;end end end break;end end end});v46:AddToggle("MyToggle",{Text="No Screech In Current Rooms",Default=false,Tooltip="Screech No Damage",Callback=function(v126)getgenv(game:GetService("ReplicatedStorage").Entities.Screech:destroy()).avoidsc=v126;end});v46:AddToggle("MyToggle",{Text="LockPart Dupe Doors In Rooms",Default=false,Tooltip="Anti Dupe",Callback=function(v128)v16.nodupe=v128;if v128 then local v288;v288=game:GetService("ReplicatedStorage").GameData.LatestRoom:GetPropertyChangedSignal("Value"):Connect(function()task.wait();for v397,v398 in pairs(game:GetService("Workspace").CurrentRooms:GetDescendants()) do if (v398.Name=="DoorFake") then v398.Hidden.CanTouch=false;end end repeat task.wait();until  not v16.nodupe v288:Disconnect();end);end end});local v48=game.ReplicatedStorage:WaitForChild("EntityInfo"):WaitForChild("A90");v46:AddToggle("MyToggle",{Text="No A90 In Hotel And Rooms",Default=false,Tooltip="Bypass A-90 Use In The Rooms",Callback=function(v130)v16.noa90=v130;if v130 then local v289=0 + 0 ;local v290;while true do if (v289==(1477 -(29 + 1448))) then v290=v12.PlayerGui:WaitForChild("MainUI"):WaitForChild("Jumpscare"):FindFirstChild("Jumpscare_A90");if v290 then v290.Parent=nil;v48.Parent=nil;repeat task.wait();game.SoundService.Main.Volume=1390 -(135 + 1254) ;until  not v16.noa90 v290.Parent=v12.PlayerGui.MainUI.Jumpscare;v48.Parent=v15;end break;end end end end});game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.bypassSnare then for v399,v400 in pairs(game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):GetChildren()) do if (v400.Name=="Snare") then v400.Hitbox['TouchInterest']:Destroy();end end end end);end);v46:AddToggle("MyToggle",{Text="No Stomp On Trap",Default=false,Tooltip="Anti Snare",Callback=function(v132)_G.bypassSnare=v132;end});game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.Eyhasd then if workspace:FindFirstChild("Eyes") then game:GetService("ReplicatedStorage").EntityInfo.MotorReplication:FireServer(0,(_G.Eyhasd and  -(452 -332)) or (0 -0) ,0,false);end end end);end);v46:AddToggle("MyToggle",{Text="No Eyes Damage",Default=false,Tooltip="Eyes No Damage",Callback=function(v133)_G.Eyhasd=v133;end});local v49=getrawmetatable(game);local v50=v49.__namecall;setreadonly(v49,false);v49.__namecall=newcclosure(function(v134,...)args={...};if (DisableEyes and EyesOnMap) then if (tostring(v134)=="MotorReplication") then args[2 + 0 ]= -(1647 -(389 + 1138));end end return v50(v134,table.unpack(args));end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.SeekESe then if game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):FindFirstChild("Seek_Arm") then for v528,v529 in pairs(game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):GetChildren()) do if (v529.Name=="Seek_Arm") then v529.AnimatorPart.CanTouch=false;end end end end end);end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.SeekESe then if game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):FindFirstChild("ChandelierObstruction") then for v530,v531 in pairs(game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):GetChildren()) do if (v531.Name=="ChandelierObstruction") then v531.HurtPart.CanTouch=false;end end end end end);end);v46:AddToggle("MyToggle",{Text="No Seek Arms HitBox In Chase",Default=false,Tooltip="Remove Seek Arms HitBox From Seek Chase",Callback=function(v111)_G.SeekESe=v111;end});v46:AddToggle("MyToggle",{Text="No Fire Damage In Chase",Default=false,Tooltip="Remove Fire Damage From Seek Chase",Callback=function(v112)_G.SeekES=v112;end});game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.NoluckNoob then if game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:FindFirstChild("RoomsDoor_Entrance") then game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("RoomsDoor_Entrance").Chain1:Destroy();game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("RoomsDoor_Entrance").Chain2:Destroy();game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("RoomsDoor_Entrance").Model:Destroy();game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("RoomsDoor_Entrance").SkullLock:Destroy();game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("RoomsDoor_Entrance").Door.EnterPrompt.Enabled=true;end end end);end);v46:AddToggle("MyToggle",{Text="No Lock Door The Rooms",Default=false,Tooltip="A-000 No lock",Callback=function(v101)_G.NoluckNoob=v101;end});v46:AddToggle("MyToggle",{Text="No Have Skeleton Door",Default=false,Tooltip="Remove Skeleton Door",Callback=function(v113)v16.noskeledoors=v113;if v113 then local v276=0 + 0 ;local v277;while true do if ((0 -0)==v276) then v277=nil;v277=workspace.CurrentRooms.ChildAdded:Connect(function(v532)local v533=v532:WaitForChild("Wax_Door",2 + 0 );if v533 then v533.Door.Transparency=772 -(326 + 445) ;v533.SkullLock.Transparency=1;v533.Door.CanCollide=false;v533.SkullLock.CanCollide=false;end end);v276=4 -3 ;end if (v276==(4 -2)) then v277:Disconnect();break;end if ((2 -1)==v276) then spawn(function()local v534=workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Wax_Door",2);if v534 then v534.Door.Transparency=712 -(530 + 181) ;v534.SkullLock.Transparency=1;v534.Door.CanCollide=false;v534.SkullLock.CanCollide=false;end end);repeat task.wait();until  not v16.noskeledoors v276=2;end end end end});v46:AddToggle("MyToggle",{Text="No Has Gates In Doors Hotel",Default=false,Tooltip="Remove Gate Doors",Callback=function(v115)v16.nogates=v115;if v115 then spawn(function()for v390,v391 in pairs(workspace.CurrentRooms:GetChildren()) do local v392=0;local v393;while true do if ((881 -(614 + 267))==v392) then v393=v391:WaitForChild("Gate",34 -(19 + 13) );if v393 then local v798=v393:WaitForChild("ThingToOpen",2 -0 );if v798 then v798:Destroy();end end break;end end end end);local v278;v278=workspace.CurrentRooms.ChildAdded:Connect(function(v327)local v328=0 -0 ;local v329;while true do if (v328==(0 -0)) then v329=v327:WaitForChild("Gate",1 + 1 );if v329 then local v742=0 -0 ;local v743;while true do if (v742==(0 -0)) then v743=v329:WaitForChild("ThingToOpen",1814 -(1293 + 519) );if v743 then v743:Destroy();end break;end end end break;end end end);spawn(function()local v330=0 -0 ;local v331;while true do if ((0 -0)==v330) then v331=workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Gate",3 -1 );if v331 then local v744=0;local v745;while true do if (v744==(0 -0)) then v745=v331:WaitForChild("ThingToOpen",4 -2 );if v745 then v745:Destroy();end break;end end end break;end end end);repeat task.wait();until  not v16.nogates v278:Disconnect();end end});v46:AddToggle("MyToggle",{Text="No All Puzzle Doors Hotel",Default=false,Tooltip="Remove Puzzle Doors",Callback=function(v117)local v118=0 + 0 ;while true do if (v118==0) then v16.nopuzzle=v117;if v117 then spawn(function()for v634,v635 in pairs(workspace.CurrentRooms:GetChildren()) do local v636=0 + 0 ;local v637;local v638;while true do if (v636==(0 -0)) then v637=v635:WaitForChild("Assets");v638=v637:WaitForChild("Paintings",1 + 1 );v636=1 + 0 ;end if (v636==(1 + 0)) then if v638 then local v885=v638:WaitForChild("MovingDoor",1098 -(709 + 387) );if v885 then v885:Destroy();end end break;end end end end);local v466;v466=workspace.CurrentRooms.ChildAdded:Connect(function(v535)local v536=v535:WaitForChild("Assets");local v537=v536:WaitForChild("Paintings",1860 -(673 + 1185) );if v537 then local v746=0 -0 ;local v747;while true do if (v746==0) then v747=v537:WaitForChild("MovingDoor",6 -4 );if v747 then v747:Destroy();end break;end end end end);spawn(function()local v538=0;local v539;local v540;while true do if (v538==0) then v539=workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets");v540=v539:WaitForChild("Paintings",2);v538=1 -0 ;end if (v538==(1 + 0)) then if v540 then local v867=v540:WaitForChild("MovingDoor",2 + 0 );if v867 then v867:Destroy();end end break;end end end);repeat task.wait();until  not v16.nopuzzle v466:Disconnect();end break;end end end});v46:AddToggle("MyToggle",{Text="No Seek Trigger Collision Event",Default=false,Tooltip="Bypass Seek Chase",Callback=function(v119)v16.noseek=v119;if v119 then local v279;v279=workspace.CurrentRooms.ChildAdded:Connect(function(v333)local v334=0 -0 ;local v335;while true do if (v334==(0 + 0)) then v335=v333:WaitForChild("TriggerEventCollision",2);if v335 then v335:Destroy();end break;end end end);repeat task.wait();until  not v16.noseek v279:Disconnect();end end});game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.lasf then if game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):FindFirstChild("Chandelier") then game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets").Chandelier:Destroy();end end end);end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.lasf then if game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets"):FindFirstChild("Light_Fixtures") then game.workspace.CurrentRooms[tostring(game:GetService("ReplicatedStorage").GameData.LatestRoom.Value)]:WaitForChild("Assets").Light_Fixtures:Destroy();end end end);end);v46:AddToggle("MyToggle",{Text="No Has Lights In Rooms Hotel",Default=false,Tooltip="Anti Lag Light",Callback=function(v121)_G.lasf=v121;end});game:GetService("Workspace").CurrentRooms.DescendantAdded:Connect(function(v89)local v90=0 -0 ;while true do if (v90==(0 + 0)) then if  not _G.InstantInteract then return;end if v89.IsA(v89,"ProximityPrompt") then if _G.InstantInteract then local v622=0 + 0 ;while true do if (v622==(0 + 0)) then v89.HoldDuration=0 + 0 ;v89.Enabled=true;break;end end end end break;end end end);v46:AddToggle("MyToggle",{Text="No Hold In Hotel And Rooms",Default=false,Tooltip="Fast E",Callback=function(v91)local v92=0 -0 ;while true do if (v92==(0 -0)) then _G.InstantInteract=v91;if (_G.InstantInteract==true) then for v519,v520 in pairs(game:GetService("Workspace").CurrentRooms:GetDescendants()) do if v520:IsA("ProximityPrompt") then v520.HoldDuration=0 + 0 ;v520.Enabled=true;end end end break;end end end});game:GetService("Workspace").CurrentRooms.DescendantAdded:Connect(function(v94)if  not _G.InteractNoclip then return;end if v94.IsA(v94,"ProximityPrompt") then if _G.InteractNoclip then v94.RequiresLineOfSight=false;end end end);v46:AddToggle("MyToggle",{Text="Noclip Claim With Rooms",Default=false,Tooltip="Interact Noclip",Callback=function(v95)local v96=0 + 0 ;while true do if (v96==(0 + 0)) then _G.InteractNoclip=v95;if (_G.InteractNoclip==false) then for v521,v522 in pairs(game:GetService("Workspace").CurrentRooms:GetDescendants()) do if v522:IsA("ProximityPrompt") then v522.RequiresLineOfSight=true;end end elseif (_G.InteractNoclip==true) then for v726,v727 in pairs(game:GetService("Workspace").CurrentRooms:GetDescendants()) do if v727:IsA("ProximityPrompt") then v727.RequiresLineOfSight=false;end end end break;end end end});v46:AddToggle("MyToggle",{Text="No Heartbeat MiniGame",Default=false,Tooltip="Win Heartbeat MiniGame",Callback=function(v97)getgenv().winhb=v97;end});v46:AddToggle("MyToggle",{Text="No Animation AuraLoot",Default=false,Tooltip="Auto Loot",Callback=function(v99)v16.draweraura=v99;if v99 then local function v266(v317)local function v318(v377)if v377:IsA("Model") then if (v377.Name=="DrawerContainer") then local v728=0 + 0 ;local v729;while true do if (v728==(1433 -(797 + 636))) then v729=v377:WaitForChild("Knobs");if v729 then local v935=v729:WaitForChild("ActivateEventPrompt");local v936=v935:GetAttribute("Interactions");if  not v936 then task.spawn(function()repeat task.wait(0.1 -0 );if (v12:DistanceFromCharacter(v729.Position)<=12) then fireproximityprompt(v935);end until v935:GetAttribute("Interactions") or  not v16.draweraura  end);end end break;end end elseif (v377.Name=="GoldPile") then local v824=v377:WaitForChild("LootPrompt");local v825=v824:GetAttribute("Interactions");if  not v825 then task.spawn(function()repeat task.wait(0.1);if (v12:DistanceFromCharacter(v377.PrimaryPart.Position)<=(1631 -(1427 + 192))) then fireproximityprompt(v824);end until v824:GetAttribute("Interactions") or  not v16.draweraura  end);end elseif (v377.Name:sub(1,3 + 5 )=="ChestBox") then local v883=v377:WaitForChild("ActivateEventPrompt");local v884=v883:GetAttribute("Interactions");if  not v884 then task.spawn(function()repeat local v1011=0 -0 ;while true do if (v1011==(0 + 0)) then task.wait(0.1 + 0 );if (v12:DistanceFromCharacter(v377.PrimaryPart.Position)<=(338 -(192 + 134))) then fireproximityprompt(v883);end break;end end until v883:GetAttribute("Interactions") or  not v16.draweraura  end);end elseif (v377.Name=="RolltopContainer") then local v954=1276 -(316 + 960) ;local v955;local v956;while true do if (v954==(0 + 0)) then v955=v377:WaitForChild("ActivateEventPrompt");v956=v955:GetAttribute("Interactions");v954=1;end if (v954==(1 + 0)) then if  not v956 then task.spawn(function()repeat local v1062=0 + 0 ;while true do if (v1062==(0 -0)) then task.wait(0.1);if (v12:DistanceFromCharacter(v377.PrimaryPart.Position)<=(563 -(83 + 468))) then fireproximityprompt(v955);end break;end end until v955:GetAttribute("Interactions") or  not v16.draweraura  end);end break;end end end end end local v319;v319=v317.DescendantAdded:Connect(function(v378)v318(v378);end);for v379,v380 in pairs(v317:GetDescendants()) do v318(v380);end task.spawn(function()local v381=1806 -(1202 + 604) ;while true do if (v381==(0 -0)) then repeat task.wait();until  not v16.draweraura v319:Disconnect();break;end end end);end local v267;v267=workspace.CurrentRooms.ChildAdded:Connect(function(v320)v266(v320);end);for v321,v322 in pairs(workspace.CurrentRooms:GetChildren()) do if v322:FindFirstChild("Assets") then v266(v322);end end repeat task.wait();until  not v16.draweraura v267:Disconnect();end end});game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.AutoBreaker then game:GetService("ReplicatedStorage").EntityInfo.EBF:FireServer();end end);end);v46:AddToggle("MyToggle",{Text="No Breaker Elictro Prize",Default=false,Tooltip="Breaker Box Minigame So Ez",Callback=function(v102)_G.AutoBreaker=v102;end});v46:AddToggle("MyToggle",{Text="No Reached Range Near",Default=false,Tooltip="Press E Far",Callback=function(v93)_G.IncreasedDistance=v93;for v228,v229 in pairs(game:GetService("Workspace").CurrentRooms:GetDescendants()) do if v229:IsA("ProximityPrompt") then v229.MaxActivationDistance=7 + 8 ;end end end});local v46=v45.Main:AddRightGroupbox(" ");game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.speedkuys then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=_G.SelectBootst;end end);end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if (_G.SpeedHack and (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed==(35 + 0))) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=35;elseif (_G.SpeedHack and (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed==(9 + 26))) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=35;elseif (_G.SpeedHack and (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed==(0 +(34 + 1)))) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=2.5 + 33 ;elseif _G.SpeedHack then local v796=31 + 4 + game.Players.LocalPlayer.Character.Humanoid:GetAttribute("SpeedBoost") ;if (game.Players.LocalPlayer.Character.Humanoid.WalkSpeed<=v796) then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed+=_G.SelectBoots end end end);end);game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.FieldOfView then game:GetService("Workspace").Camera.FieldOfView=_G.FieldOfViewe;end end);end);v46:AddSlider("MySliderspeed",{Text="Speed Boots ",Default=1,Min=0 -0 ,Max=50,Rounding=1,Compact=true,Callback=function(v80)_G.SelectBoots=v80;end});v46:AddSlider("MySlider",{Text="Field of View ",Default=120,Min=1226 -(1074 + 82) ,Max=120,Rounding=0 -0 ,Compact=true,Callback=function(v81)_G.FieldOfViewe=v81;end});_G.SelectBoots=1790.5 -(214 + 1570) ;_G.FieldOfViewe=120;v46:AddToggle("MyToggle",{Text="Enable Speed Boots",Default=false,Tooltip="Speed Boots",Callback=function(v82)_G.SpeedHack=v82;if (_G.SpeedHack==false) then game:GetService("Players").LocalPlayer.PlayerGui.MainUI.MainFrame.Healthbar.Effects.SpeedBoost.Visible=false;elseif (_G.SpeedHack==true) then game:GetService("Players").LocalPlayer.PlayerGui.MainUI.MainFrame.Healthbar.Effects.SpeedBoost.Visible=true;end end});v46:AddToggle("MyToggle",{Text="Enable Field of View",Default=false,Tooltip="Field of View Hack",Callback=function(v83)local v84=1455 -(990 + 465) ;while true do if (0==v84) then if (v83==true) then local v449=0 + 0 ;local v450;while true do if (0==v449) then v450=game:GetService("TweenService");v450:Create(game.Workspace.CurrentCamera,TweenInfo.new(0.9),{FieldOfView=_G.FieldOfViewe}):Play();break;end end elseif (v83==false) then local v621=game:GetService("TweenService");v621:Create(game.Workspace.CurrentCamera,TweenInfo.new(0.9),{FieldOfView=31 + 39 }):Play();end wait(0.8 + 0 );v84=3 -2 ;end if (v84==1) then _G.FieldOfView=v83;break;end end end});v46:AddToggle("MyToggle",{Text="Bypass Speed Anti Cheat",Default=false,Tooltip="Bypass Speed Anti Cheat",Callback=function(v217)local v218=0 + 0 ;while true do if (v218==0) then _G.BypassSpeeds=v217;while _G.BypassSpeeds do local v429=17 -(12 + 5) ;while true do if (v429==0) then wait(0.2 + 0 );pcall(function()game.Players.LocalPlayer.Character.Collision.Size=Vector3.new(4 -2 ,1 + 1 ,1095 -(277 + 816) );wait(0.2);game.Players.LocalPlayer.Character.Collision.Size=Vector3.new(12 -9 ,4.5,1186 -(1058 + 125) );end);break;end end end break;end end end});local v54=v46:AddButton({Text="God Mode",Func=function()v0:Notify("Credit By Rechedmcvn");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/GODMODE/main/GodModeByMurder"))();end,Default=false,Tooltip="God mode"});local v54=v46:AddButton({Text="Noclip",Func=function()v0:Notify("Noclip Enable");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/NoclipScript/main/README.md"))();end,PressTwice=false,Tooltip="God mode"});

