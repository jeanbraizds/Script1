
--Game guardian detection
if gg.BUILD < 12270 then 
gg.alert('Você precisa da nova versão do GameGuardian para executar este script. É necessário pelo menos a versão 8.64.3.                                                                                                           ⒷⓎ: ⓅⒶⓉⓄⓁⒾⓃⓄ  ⒷⓇ') 
gg.toast('UPDATE YOUR GG')
gg.require('8.64.3')
end

gg.clearResults()
t = gg.getListItems()
gg.removeListItems(t)

gg.alert('♿[Checkbox Memory the Anonymous & Cb & Xa Only]♿')
gg.toast(' BY PATOLINO BR™             🔂v1.22.2                                                                                                                                                    ')
print(' 🛂Like.              🔂v1.22.2                                                                                                                                                   🎥Visite o Canal📺 : https://www.youtube.com/channel/UC68_VWZcV0-Rm7hJArp_WKw                                                                                                                                                  📨Contats g.p📩: https://chat.whatsapp.com/3oOJiye9bBK7nQkx9z599O  ')

while(true) do
if gg.isVisible(true) then
menuk = 1
gg.setVisible(false)
end

START = 1

function START()

menu = gg.choice({'⛔Fix Close✔','⛔Antena Menu💂','⛔Unlock Raqueada🎖','⛔Shots Menu🔫','⛔Ghost Mode Menu🛡','⛔Speed Hacks⚡','⛔Config. Game Menu🌎','⛔Medkit (3s)⏱','⛔Elevador Menu🛩','⛔Wall Hack🕋','⛔Paraquedas Menu🆙','                                   ❎SAIR❎'},nil,' BY PATOLINO BR™                                                                            ✭ᶠʳᵉᵉ ᶜʰᵉᵃᵗ ᴮᵃᵗᵗˡᵉᶠⁱᵉˡᵈ✭')
if menu == 1 then fixclose() end
if menu == 2 then antena() end
if menu == 3 then rakeada() end
if menu == 4 then hettso() end
if menu == 5 then ghostmod() end
if menu == 6 then speed() end
if menu == 7 then maphack1() end
if menu == 8 then mekit() end
if menu == 9 then elevador() end
if menu == 10 then wall() end
if menu == 11 then parak() end
if menu == 12 then sair() end
if menu == nil then noselect() end
menuk =-1
end

function fixclose()

gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_C_BSS |
gg.REGION_ANONYMOUS | gg.REGION_CODE_APP | gg.REGION_C_HEAP |
gg.REGION_BAD | gg.REGION_C_DATA | gg.REGION_CODE_SYS |
gg.REGION_JAVA_HEAP | gg.REGION_JAVA)
gg.searchNumber('1', gg.TYPE_AUTO, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Fix Close Active')
end

function antena()

menu1 = gg.multiChoice({'⛔Antenna 1💂','⛔Antenna 2💂','⛔Antenna 3💂','⛔Antenna 4💂','🔙VOLTA🔙'},nil,'ℹLocalização de adversários naℹ')
if menu1 == nil then noselect() else
if menu1[1] then at1() end
if menu1[2] then at2() end
if menu1[3] then at3() end
if menu1[4] then at4() end
if menu1[5] then START() end
menuk =-1
end
end

function at1()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.58~0.61', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("0.6", gg.TYPE_FLOAT, false, gg.SIGN_NOT_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10000)
gg.editAll('300', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Antenna 1 Active')
end

function at2()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.63~0.66', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.63~0.66', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.63", gg.TYPE_FLOAT, false, gg.SIGN_NOT_EQUAL, 0, -1)
gg.searchNumber("0.64", gg.TYPE_FLOAT, false, gg.SIGN_NOT_EQUAL, 0, -1)
gg.searchNumber("0.65", gg.TYPE_FLOAT, false, gg.SIGN_NOT_EQUAL, 0, -1)
gg.searchNumber("0.66", gg.TYPE_FLOAT, false, gg.SIGN_NOT_EQUAL, 0, -1)
gg.getResults(10000)
gg.editAll('300', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Antenna 2 Active')
end

function at3()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.73~0.76', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.75", gg.TYPE_FLOAT, false, gg.SIGN_NOT_EQUAL, 0, -1)
gg.getResults(10000)
gg.editAll('300', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Antenna 3 Active')
end

function at4()

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.99900001287;0.00100000005", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5000)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.99900001287;0.00100000005", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5000)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.99900001287;0.00100000005", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5000)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.99900001287;0.00100000005", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5000)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.64999997616", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5000)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.34999999404", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5000)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Antena 4 Active")
end

function ghostmod()

menu2 = gg.choice({'⛔Ghost Hack🛡','⛔White Boby🆙','⛔All Female🆙','⛔Underground🛤','🔙VOLTA🔙'},nil,'ℹSer invisível é fácilℹ')
if menu2 == 1 then ghosthk() end
if menu2 == 2 then white() end
if menu2 == 2 then female() end
if menu2 == 3 then underground() end
if menu2 == 4 then START() end
if menu2 == nil then noselect() end
menuk =-1
end

function ghosthk()

menu3 = gg.choice({'⛔Active🛡','⛔Disative🛡','🔙VOLTA🔙'},nil,'ℹModo invisível para adversárioℹ')
if menu3 == 1 then ghoston() end
if menu3 == 2 then ghostoff() end
if menu3 == 3 then START() end
if menu3 == nil then noselect() end
menuk =-1
end

function ghoston()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('1000;6.5757242e-38::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('100.51', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Ghost Active')
end

function ghostoff()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('100.51;6.5757242e-38::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('100.51', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('1000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Ghost Disactive')
end

function white()

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("16D;4::53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('4', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1000)
gg.editAll('999', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber('2.6344411e-43F;0.1::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll('300.51', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('White Boby Active')
end

function female()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-1.2278589e23;-2.0291021e20::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-1.2278589e23', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('-5.9029587e21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('All Female Active')
end

function underground() 

menu5 = gg.choice({'⛔Active🛤','⛔Disactive🛤','🔙VOLTA🔙'},nil,'ℹIr debaixo da terra. (Em Testes)ℹ                                                                                                     ❔Ativar na Partida❔')                                                                                                         
if menu5 == 1 then undergroundon() end
if menu5 == 2 then undergroundoff() end
if menu5 == 3 then START() end
if menu5 == nil then noselect() end
menuk =-1
end

function undergroundon() 

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber('0.75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('0.75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5000)
gg.editAll('1.9551', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Underground Active')
end

function undergroundoff() 

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber('1.9551', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1.9551', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5000)
gg.editAll('0.75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Underground Disactive')
end

function hettso() 

menu6 = gg.choice({'⛔Aimbot Semi🆙','⛔Aim Assystem 360°🆙','⛔Auto HeadShot🔫','⛔Hight Damage 35%🗡','⛔No Recoil⚙','⛔Unlimited Ammo⚒','⛔Damage Hack⚕','⛔Reload Fast♋','⛔No KnockDown🆙','🔙VOLTA🔙'},nil,'ℹVocê podera fazer mais Kill com essas opções.ℹ')
if menu6 == 1 then aimsemi() end
if menu6 == 2 then aimsys() end
if menu6 == 3 then hest() end
if menu6 == 4 then hightdmg() end
if menu6 == 5 then norecoil() end
if menu6 == 6 then unlimited() end
if menu6 == 7 then dmghk() end
if menu6 == 8 then noreload() end
if menu6 == 9 then knockdown() end
if menu6 == 10 then START() end
if menu6 == nil then noselect() end
menuk =-1
end

function aimsemi() 

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-7.5597027e22;-2.0291021e20;-8.5003137e22;-2.0291021e20::13', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-8.5003137e22', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(2)
gg.editAll('-3.6158841e21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
end

function aimsys() 

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('75;40::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('40', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('360', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.50499999523;0.50499999523::9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('50', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Aim Assystem 360° Active')
end

function hest() 

menu7 = gg.choice({'⛔Active🔫','⛔Disative🔫','🔙VOLTA🔙'},nil,'ℹLacrar a Mira no Centro, tendo só HeadShot em local Planos.ℹ')
if menu7 == 1 then hettso1() end
if menu7 == 2 then hettso2() end
if menu7 == 3 then START() end
if menu7 == nil then noselect() end
menuk =-1
end

function hettso1() 

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('75;40;360::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('40~360', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Heatshot Active')
end

function hettso2() 

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('75;-1::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('360', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Heatshot Disactive')
end

function norecoil()

menu8 = gg.multiChoice({'⛔M1012⚙','⛔M4A1⚙','⛔MP5⚙','⛔MP40⚙','⛔SCAR⚙','⛔AK⚙','⛔UMP⚙','⛔FAMAS⚙','⛔M249⚙','⛔SPAS12⚙','⛔GROZA⚙','⛔XM8⚙','🔙VOLTA🔙'},nil,'ℹRetirar o Recoil, Assim os tiros não espalha.ℹ                                                                          ❔Ativar na Partida, Com Arma na Mão e selecione o tipo, Reloil 90% Automático só retire o Pente.❔')
if menu8 == nil then noselect() else
if menu8[1] then arm1() end
if menu8[2] then arm2() end
if menu8[3] then arm3() end
if menu8[4] then arm4() end
if menu8[5] then arm5() end
if menu8[6] then arm6() end
if menu8[7] then arm7() end
if menu8[8] then arm8() end
if menu8[9] then arm9() end
if menu8[10] then arm10() end
if menu8[11] then arm11() end
if menu8[12] then arm12() end
if menu8[13] then START() end
menuk =-1
end
end

function arm1()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.40000000596;0.40000000596;15;5;10;1;1.5;1;0.44999998808;1D~6D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('M1012 Active')
gg.addListItems(t)
end 
end

function arm2()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.18000000715;0.18000000715;220~225;0.20000000298;1;0.55000001192;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('M4A1 ACTIVE')
gg.addListItems(t)
end
end

function arm3()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.1099999994;0.1099999994;220~225;0.15999999642;1;0.64999997616;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('MP5 ACTIVE')
gg.addListItems(t)
end
end

function arm4()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.0700000003;0.0700000003;220~225;0.15000000596;1;0.64999997616;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('MP40 ACTIVE')
gg.addListItems(t)
end
end

function arm5()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.15000000596;0.15000000596;220~225;0.25;1;0.55000001192;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('SCAR ACTIVE')
gg.addListItems(t)
end
end

function arm6()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.18000000715;0.18000000715;220~225;0.30000001192;1;0.55000001192;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('AK ACTIVE')
gg.addListItems(t)
end
end

function arm7()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.09000000358;0.09000000358;220~225;0.28000000119;1;0.64999997616;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('UMP ACTIVE')
gg.addListItems(t)
end
end

function arm8()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.11999999732;0.15000000596;220~225;0.20000000298;1;0.55000001192;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('FAMAS ACTIVE')
gg.addListItems(t)
end
end

function arm9()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.15999999642;0.15999999642;220~225;0.20000000298;1;0.30000001192;1D~100D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('M249 ACTIVE')
gg.addListItems(t)
end
end

function arm10()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.33000001311;0.33000001311;25;4;20;1.5;1;1D~5D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('SPAS12 ACTIVE')
gg.addListItems(t)
end
end

function arml11()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.31999999285;0.31999999285;220~225;60;80;2;1.14999997616;1;0.85000002384::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('M500 ACTIVE')
gg.addListItems(t)
end
end

function arm11()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('37D;0.18000000715;0.18000000715;220~225;0.20000000298;1;0.30000001192;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchAddress("???????4", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120) 
t = gg.getResults(20)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('GROZA ACTIVE')
gg.addListItems(t)
end
end

function arm12()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.19;.19;220~225;0.17000000179;1;0.55000001192;1D;1D~48D;0::117', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120)
t = gg.getResults(10)
for i, v in ipairs(t) do
    t[i].value = '0'
    t[i].freeze = true
gg.clearResults()
gg.toast('XM8 ACTIVE')
gg.addListItems(t)
end
end

function unlimited()

menu9 = gg.multiChoice({'⛔M1012⚒','⛔M4A1⚒','⛔MP5⚒','⛔MP40⚒','⛔SCAR⚒','⛔AK⚒','⛔UMP⚒','⛔FAMAS⚒','⛔M249⚒','⛔SPAS12⚒','🔙VOLTA🔙'},nil,'ℹRetira o limite de munição na Arma, Deixando ilimitada.ℹ                                                                          ❔Ativar no Lobby ou Partida, Não ative com o Reload Fast.❔')
if menu9 == nil then noselect() else
if menu9[1] then armk1() end
if menu9[2] then armk2() end
if menu9[3] then armk3() end
if menu9[4] then armk4() end
if menu9[5] then armk5() end
if menu9[6] then armk6() end
if menu9[7] then armk7() end
if menu9[8] then armk8() end
if menu9[9] then armk9() end
if menu9[10] then armk10() end
if menu9[11] then START() end
menuk =-1
end
end

function armk1()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('6D;0.40000000596;0.4000000059615;5;10::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('6', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('M1012 ACTIVE')
end

function armk2()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.18000000715;0.18000000715;220~225;40;90::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('AK ACTIVE')
end

function armk3()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.1099999994;0.1099999994;220~225;13;30::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('MP5 ACTIVE')
end

function armk4()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('20D;0.0700000003;0.0700000003;220~225;11;25::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('20', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('MP40 ACTIVE')
end

function armk5()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.15000000596;0.15000000596;220~225;30;70::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('SCAR ACTIVE')
end

function armk6()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.18000000715;0.18000000715;220~225;38;85::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('GROZA ACTIVE')
end

function armk7()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.09000000358;0.09000000358;220~225;16;34::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('UMP ACTIVE')
end

function armk8()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.11999999732;0.15000000596;220~225;38;80::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('FAMAS ACTIVE')
end

function armk9()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('100D;0.15999999642;0.15999999642;220~225;45;80::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('100', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('M249 ACTIVE')
end

function armk10()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('5D;0.33000001311;0.33000001311;25;4;20::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('5', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('SPAS12 ACTIVE')
end

function hightdmg()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('5.5;1.0;0.75::9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('1.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('5.5;0.75::9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('0.75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('1.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('High Damage Active')
end

function dmghk()

menu19 = gg.multiChoice({'⛔MP5⚕','⛔SCAR⚕','⛔AK⚕','⛔UMP⚕','⛔M4A1⚕','⛔SKS⚕','⛔VSS⚕','⛔GROZA⚕','⛔MP40⚕','⛔M1012⚕','⛔FAMAS⚕','⛔M249⚕','⛔SPAS12⚕','⛔M500⚕','⛔XM8⚕','🔙VOLTA🔙'},nil,'ℹAumentar em 37% o Dano, capaz de matar qualquer um com 7 tiros.ℹ                                                                          ❔Ativar no Lobby ou Partida.❔')
if menu19 == nil then noselect() else
if menu19[1] then arml1() end
if menu19[2] then arml2() end
if menu19[3] then arml3() end
if menu19[4] then arml4() end
if menu19[5] then arml5() end
if menu19[6] then arml6() end
if menu19[7] then arml7() end
if menu19[8] then arml8() end
if menu19[9] then arml9() end
if menu19[10] then arml10() end
if menu19[11] then arml11() end
if menu19[12] then arml12() end
if menu19[13] then arml13() end
if menu19[14] then arml14() end
if menu19[15] then arml15() end
if menu19[16] then START() end
menuk =-1
end
end

function arml1()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('23D;0.1099999994;0.1099999994;220~225;13;30;10D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('10', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('23', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack MP5 Active')
end

function arml2()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('28D;0.15000000596;0.15000000596;220~225;30;70;10D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('10', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('28', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack SCAR Active')
end

function arml3()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('37D;0.18000000715;0.18000000715;220~225;38;85;12D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('12', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('37', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack AK Active')
end

function arml4()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('23D;0.09000000358;0.09000000358;220~225;16;34;11D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('11', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('23', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack UMP Active')
end

function arml5()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('28D;0.18000000715;0.18000000715;220~225;40;90;11D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('11', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('28', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack M4A1 Active')
end

function arml6()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('68D;0.55000001192;0.55000001192;220~225;50;96;20D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('20', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('68', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack SKS Active')
end

function arml7()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('25D;0.25;0.25;220~225;50;90;14D::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('14', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('25', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack VSS Active')
end

function arml8()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('37D;0.18000000715;0.18000000715;220~225;40;90;11D;0.20000000298;1.20000004768;0.9;1;0.30000001192::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('11', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('37', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack GROZA Active')
end

function arml9()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('23D;0.0700000003;0.0700000003;220~225;11;25;10D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('10', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('23', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack MP40 Active')
end

function arml10()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('26D;0.40000000596;0.4000000059615;5;10;10D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('10', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('26', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack M1012 Active')
end

function arml11()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('28D;0.11999999732;0.15000000596;220~225;38;80;11D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('11', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('28', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack FAMAS Active')
end

function arml12()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('33D;0.15999999642;0.15999999642;220~225;45;80;15D::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('15', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('33', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack M249 Active')
end

function arml13()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('20D;0.33000001311;0.33000001311;25;4;20;6D::65', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('6', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('20', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack SPACE Active')
end

function arml14()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('45D;0.32;0.32;220~225;60;80;20D::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('20', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('45', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack M500 Active')
end

function arml15()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('30D;0.18999999762;0.18999999762;220~225;42;70;13D', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('13', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('30', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast('Damage Hack XM8 Active')
end

function noreload()

menu18 = gg.multiChoice({'⛔M1012♋','⛔M4A1♋','⛔MP5♋','⛔MP40♋','⛔SCAR♋','⛔AK♋','⛔UMP♋','⛔FAMAS♋','⛔SPAS12♋','⛔XM8♋','🔙VOLTA🔙'},nil,'ℹReload Fast faz que recarregar as munições em segundos.ℹ                                                                                                             ❔ Só pode ser Ativado no Lobby, Não ative com o Unlimited Ammo.❔')
if menu18 == nil then noselect() else
if menu18[1] then armd1() end
if menu18[2] then armd2() end
if menu18[3] then armd3() end
if menu18[4] then armd4() end
if menu18[5] then armd5() end
if menu18[6] then armd6() end
if menu18[7] then armd7() end
if menu18[8] then armd8() end
if menu18[9] then armd9() end
if menu18[10] then armd10() end
if menu18[11] then START() end
menuk =-1
end
end

function armd1()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.40000000596;0.4000000059615;5;10;1;1.5;0.5;1;0.44999998808::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('M1012 Active')
gg.addListItems(t)
end
end

function armd2()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.18000000715;0.18000000715;220~225;40;90;0.20000000298;1.20000004768;0.89999997616;1;0.55000001192::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('M4A1 ACTIVE')
gg.addListItems(t)
end
end

function armd3()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.1099999994;0.1099999994;220~225;13;30;0.15999999642;1.10000002384;1.10000002384;1;0.64999997616::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1;1::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('MP5 ACTIVE')
gg.addListItems(t)
end
end

function armd4()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.0700000003;0.0700000003;220~225;11;25;0.15000000596;1.10000002384;0.89999997616;1;0.64999997616::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('MP40 ACTIVE')
gg.addListItems(t)
end
end

function armd5()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.15000000596;0.15000000596;220~225;30;70;0.25;1.14999997616;0.80000001192;1;0.55000001192::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.8', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('SCAR ACTIVE')
gg.addListItems(t)
end
end

function armd6()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.18000000715;0.18000000715;220~225;38;85;0.30000001192;1.20000004768;0.80000001192;1;0.55000001192::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('.8', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('AK ACTIVE')
gg.addListItems(t)
end
end

function armd7()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.09000000358;0.09000000358;220~225;16;34;0.28000000119;1.25;1.10000002384;1;0.64999997616::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('UMP ACTIVE')
gg.addListItems(t)
end
end

function armd8()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.11999999732;0.15000000596;220~225;38;80;0.20000000298;1.20000004768;0.89999997616;1;0.55000001192::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('FAMAS ACTIVE')
gg.addListItems(t)
end
end

function armd9()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.33000001311;0.33000001311;25;4;20;1.5;1.5;0.69999998808;1;0.44999998808::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('.7', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.clearResults()
gg.toast('SPAS12')
gg.addListItems(t)
end
end

function armd10()

gg.setRanges(gg.REGION_C_BSS | gg.REGION_ANONYMOUS)
gg.searchNumber('0.18999999762;0.18999999762;220~225;42;70;0.17000000179;1.20000004768;0.89999997616;1;0.55000001192::75', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(8)
gg.editAll('2.9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
t = gg.getResults(1)
for i, v in ipairs(t) do
    t[i].value = '2.9'
    t[i].freeze = true
gg.addListItems(t)
gg.clearResults()
gg.toast('XM8 Active')
end
end

function knockdown()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-1,2278533e23;-2,0291021e20;-1,3094071e25;-1,3068388e21;-3,6951134e20;-9,3858043e22::21',gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-1,3068388e21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(2)
gg.editAll('-2,0291021e20', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('No KnockDown Active')
end 

function mekit()

gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber('75D;4D;5D;4::13', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.searchNumber('4', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('3', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Mekit 3s Active')
end

function speed()

menu10 = gg.multiChoice({'⛔Speed Hack⚡','⛔Continuar Correndo após Pular🕺','⛔Speed Force🏃','🔙VOLTA🔙'},nil,'ℹAtivando esses de baixo aumentará a velocidade X4.ℹ')
if menu10 == nil then noselect() else
if menu10[1] then speedhk() end
if menu10[2] then run() end
if menu10[3] then force() end
if menu10[4] then START() end
menuk =-1
end
end

function speedhk()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('3.25;1.40::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1.40', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Speed Hack Active')
end

function run()

gg.setRanges(gg.REGION_ANONYMOUS)	gg.searchNumber('1.34;3;0.7:13', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('3', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1)
gg.editAll('3333333', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Continuar Correndo Active')
end

function force()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.5;5;3::9",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("3",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.getResults(1)
gg.editAll("0.01",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.clearResults()
end

function nofall()
gg.toast('🛃Em Breve🛃')
end

function nofaqll()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-0.10000000149;-1.3005005e21:5',
gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-0.10000000149', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(2)
gg.editAll('-69', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('No Fall Active')
end 

function maphack1()

menu11 = gg.multiChoice({'⛔Night Mode✨','⛔No Fog🌁','⛔No Grass🌱','⛔No Land⛰','⛔No Tree🎄','⛔No Wall, No Tree & No Grass🆙','⛔View Mode📹','⛔View Eagle Crouching🦅','🔙VOLTA🔙'},nil,'ℹMude as Formas do Jogo.ℹ')
if menu11 == nil then noselect() else
if menu11[1] then night() end
if menu11[2] then nofog() end
if menu11[3] then nograss() end
if menu11[4] then noland() end
if menu11[5] then notree() end
if menu11[6] then nowall() end
if menu11[7] then viewmode() end
if menu11[8] then eagleview() end
if menu11[9] then START() end
menuk =-1
end
end

function night()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('.57735025883;.01;1.0e-6::9', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1.0e-6', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Night Mode Active')
end

function nofog()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('1.1617992e-38;-1.3092816e25::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1.1617992e-38', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('-5,9029581e21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('No Fog Active')
end

function nograss()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('6D;100;300::17', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.searchNumber('100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.getResults(10)
gg.editAll('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.clearResults()
gg.toast('No Grass Active')
end

function notree()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('1.3376235e-40;60::5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('60', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(10)
gg.editAll('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('No Tree Active')
end

function noland()

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber('100.00001525879;100.00001525879;1;98:100',
gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.getResults(200)
gg.editAll('-10.561', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.clearResults()
gg.toast('No Land Active')
end

function nowall()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('4.179737e-40;-1.3094514e25;-1.3068399e21;-3.3568098e27::13', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-1.3068399e21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(2)
gg.editAll('-2,0291021e20', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-7.1608877e24;-1.309396e25;-1.3068377e21;-3.6951134e20;-5.9052639e21;-5.8585922e26::21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-1.3068377e21', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(2)
gg.editAll('-2,0291021e20', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('No Wall, No Tree & No Grass Active')
end

function viewmode()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2.5;2;1.2::35", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(3)
gg.editAll("4", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('View Mode Active')
end

function eagleview()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.34;1::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(2)
gg.editAll("50", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Eagle View Crouching Active')
end

function elevador()

menu13 = gg.choice({'⛔Active⚖','⛔Disactive⚖','🔙VOLTA🔙'},nil,'ℹFaz que você ande no Ar.ℹ')
if menu13 == 1 then elevadoron() end
if menu13 == 2 then elevadoroff() end
if menu13 == 3 then START() end
if menu13 == nil then noselect() end
menuk =-1
end

function elevadoron()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.07999999821;0.30000001192::5",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("0.30000001192",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.getResults(1)
gg.editAll("1",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("2",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("3",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("4",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("5",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("6",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("7",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("8",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("9",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("10",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("11",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("12",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("13",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("14",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("15.3",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.clearResults()
end

function elevadoroff()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.07999999821;15.3::5",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("15.3",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.getResults(1)
gg.editAll("14",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("12",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("10",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("8",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("6",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("4",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll("2",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.editAll(".3",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.clearResults()
end

function parak()

menu14 = gg.choice({'⛔Paraquedas Fast🏂','⛔No Paraquedas⛷','⛔Sky Fly🆙','🔙VOLTA🔙'},nil,'ℹDescer do Paraquedas mais rapido que nunca.ℹ')
if menu14 == 1 then paraquedas1() end
if menu14 == 2 then paraquedas2() end
if menu14 == 3 then paraquedas3() end
if menu14 == 4 then START() end
if menu14 == nil then noselect() end
menuk =-1
end

function paraquedas1()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-6;-12;-4::45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x0, 0xffffffffffffffff)
gg.searchNumber("-6", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x0, 0xffffffffffffffff)
gg.getResults(5)
gg.editAll("-996", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Paraquedas Fast Active')
end

function paraquedas2()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-12;-4;-8::45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x0, 0xffffffffffffffff)
gg.searchNumber("-8", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x0, 0xffffffffffffffff)
gg.getResults(5)
gg.editAll("-99996", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('No Paraquedas Active')
end

function paraquedas3()

menu18 = gg.choice({'⛔Sky Fly Active🏂','⛔Sky Fly Disative⛷','🔙VOLTA🔙'},nil,'ℹVoar no ar de Paraquedas em toda a partida, Auto booyah.ℹ')
if menu18 == 1 then paraquedas4() end
if menu18 == 2 then paraquedas5() end
if menu18 == 3 then START() end
if menu18 == nil then noselect() end
menuk =-1
end

function paraquedas4()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-6;-12;-4::45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("-6", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll("-999996", gg.TYPE_FLOAT)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("0.0001;1000::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("1000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll("200", gg.TYPE_FLOAT, -1, false, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("3.3230392e-40;1000::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("1000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll('200', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1.4286518e-40;1000::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("1000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll('200', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Sky Fly Active')
end

function paraquedas5()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-999996;-12;-4::45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("-999996", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll("-6", gg.TYPE_FLOAT)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("0.0001;200::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll('1000', gg.TYPE_FLOAT, false,  gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("3.3230392e-40;200::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll('1000', gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1.4286518e-40;200::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber("200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(5)
gg.editAll('1000', gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Sky Fly Disactive')
end

function wall()

menu15 = gg.choice({'⛔Wall Hack Beta🕋','⛔Wall Hack Lite🏢','🔙VOLTA🔙'},nil,'ℹAtravesse Parede com o Wall Hack.ℹ')
if menu15 == 1 then wallhack1() end
if menu15 == 2 then wallhack2() end
if menu15 == 3 then START() end
if menu15 == nil then noselect() end
menuk =-1
end

function wallhack1()

menu16 = gg.choice({'⛔Active🕋','⛔Disactive🕋','🔙VOLTA🔙'},nil,'ℹAtravesse Parede com o Wall Hack, Desative para ativar.ℹ')
if menu16 == 1 then wallhackon() end
if menu16 == 2 then wallhackoff() end
if menu16 == 3 then START() end
if menu16 == nil then noselect() end
menuk =-1
end

function wallhackon()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-7.1602882e24;-2::100',
gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(80)
gg.editAll('-999', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast(' Wall hack Active ')
end

function wallhackoff()

gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-7.1602882e24;-999::100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('-999', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(80)
gg.editAll('-2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.clearResults()
gg.toast('Wall hack Disactive')
end

function wallhack2()

menu26 = gg.choice({'⛔Active🏢','⛔Disactive🏢','🔙VOLTA🔙'},nil,'ℹAtravesse Parede com o Wall Hack, não deixe ativando por muito tempo.ℹ')
if menu26 == 1 then wallhackon1() end
if menu26 == 2 then wallhackoff1() end
if menu26 == 3 then START() end
if menu26 == nil then noselect() end
menuk =-1
end

function wallhackon1()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('2;0;260;0.10000000149;3;4.2038954e-45;4.2038954e-45::30', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.searchNumber('2;0.10000000149;3;4.2038954e-45;4.2038954e-45', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.getResults(10)
gg.editAll('-99;-1;-999;1.3998972e-42;1.3998972e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.toast('Wall Hack Lite Active')
gg.clearResults()
end

function wallhackoff1()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-99;-1;-999;1.3998972e-42;1.3998972e-42::30', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.searchNumber('-99;-1;-999;1.3998972e-42;1.3998972e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.getResults(10)
gg.editAll('2;0;260;0.10000000149;3;4.2038954e-45;4.2038954e-45', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0x80000000, 0x8fffffff)
gg.toast('Wall Hack Lite Disactive')
gg.clearResults()
end

function rakeada()

gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0;0;1~9;2.8025969e-45F;9.8090893e-45F;86400::55', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.searchNumber('1~9', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
gg.getResults(1000)
gg.editAll('99', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0x90000000, 0x9fffffff)
t = gg.getResults(1)
t[1].value = '99'
t[1].freeze = true
t[1].freezeType = gg.FREEZE_NORMAL
gg.clearResults()
gg.toast('Ranqueada Unlock Active')
gg.addListItems(t)
end

function sair()
gg.clearResults()
t = gg.getListItems()
gg.removeListItems(t)
os.exit()
end

function noselect()
gg.toast('you did not press anything')
end

if menuk == 1 then START() end
end
