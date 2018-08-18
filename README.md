gg.alert('비밀번호가 승인되었습니다.')

gg.alert(os.date("╔═══════════════════╗\n    Alpha SHOP VIP Script                     -----------------• Version 1.0•---------------     \n ---------------서버인증완료!----------------   \n╚═══════════════════╝\n   로그인일자 : %Y/%m/%d   로그인시각 : %H:%M:%S  \n                 ☆Alpha SHOP☆"))
gg.toast(os.date("즐거운 시간 되십시오."))
function ADISK29Menu()
  ADISK29 = gg.choice({
    "🎧_____ 그래픽메뉴 I _____🎧",
    "🎧_____ 그래픽메뉴 II _____🎧",
    "🎧_____ 로비메뉴 _____🎧",
    "🎧_____ 인기 추천메뉴 _____🎧",
    "🎧_____ 테스트메뉴 _____🎧",
    "🎧_____ 연락처 _____🎧",
    "                      🎧_____ 나가기 _____🎧"
  }, nil, "    Alpha SHOP VIP Script 1.0                                         { Auto Update }")
  if ADISK29 == 1 then
    WBS()
  end
  if ADISK29 == 2 then
    WBM()
  end
  if ADISK29 == 3 then
    FIL()
  end
  if ADISK29 == 4 then
    FITG()
  end
  if ADISK29 == 5 then
    informasiftb()
  end
  if ADISK29 == 6 then
    MYCK()
  end
  if ADISK29 == 7 then
    Exit()
  end
  ADISK29 = -1
end
function WBS()
  ADISK296 = gg.multiChoice({
    "✪ ESP V1〘로비전용〙",
    "✪ ESP V2〘로비전용〙",
    "✪ ESP Kirin V1〘로비전용〙",
    "✪ ESP { SD 425, 435 }〘로비전용〙",
    "✪ ESP { SD 625, 626 }〘로비전용〙",
    "✪ ESP { SD 835 }〘로비전용〙",
    "✪ ESP { SD 845 }〘로비전용〙",
    "✪ ESP Car〘로비전용〙 ",
    "✪ 전신 색깔 화이트 V1〘로비전용〙",
    "✪ 전신 색깔 화이트 V2〘로비전용〙",
    "✪ 전신 색깔 옐로우 V1〘로비전용〙 ",
    "✪ 전신 색깔 옐로우 V2〘로비전용〙",
    "✪ 전신 색깔 핑크 〘로비전용〙",
    "✪ 전신 색깔 그린 V1〘로비전용〙",
    "✪ 전신 색깔 그린 V2〘로비전용〙",
    "✪ 전신 색깔 블랙 V1〘로비전용〙",
    "✪ 전신 색깔 블랙 V2 〘로비전용〙",
    "✪ 전신 색깔 다이아블루〘로비전용〙",
    "✪ 전신 색깔 다이아레드〘로비전용〙",
    "✪ 전신 색깔 다이아그린〘로비전용〙",
    "✪ 전신 색깔 혼합 [ 옐로우, 핑크 ]〘로비전용〙",
    "✪ 전신 색깔 혼합 [ 그린, 크리스탈 ]〘로비전용〙",
    "✪ 전신 색깔 산성 V1〘로비전용〙",
    "✪ 전신 색깔 산성 V2〘로비전용〙",
    " 뒤로가기 "
  }, nil, "  Alpha SHOP VIP Script 1.0                                                   { Auto Update }")
  if ADISK296 == nil then
  else
    if ADISK296[1] == true then
      whal()
    end
    if ADISK296[2] == true then
      whal2()
    end
    if ADISK296[3] == true then
      whkirin()
    end
    if ADISK296[4] == true then
      wh435()
    end
    if ADISK296[5] == true then
      wh625()
    end
    if ADISK296[6] == true then
      wh835()
    end
    if ADISK296[7] == true then
      wh845()
    end
    if ADISK296[8] == true then
      whcar()
    end
    if ADISK296[9] == true then
      whitev1()
    end
    if ADISK296[10] == true then
      whitev2()
    end
    if ADISK296[11] == true then
      yellowv1()
    end
    if ADISK296[12] == true then
      yellowv2()
    end
    if ADISK296[13] == true then
      pink()
    end
    if ADISK296[14] == true then
      greenv1()
    end
    if ADISK296[15] == true then
      greenv2()
    end
    if ADISK296[16] == true then
      blackv1()
    end
    if ADISK296[17] == true then
      blackv1()
    end
    if ADISK296[18] == true then
      diamondblue()
    end
    if ADISK296[19] == true then
      diamondred()
    end
    if ADISK296[20] == true then
      diamondgreen()
    end
    if ADISK296[21] == true then
      mixyellowpink()
    end
    if ADISK296[22] == true then
      greencrystal()
    end
    if ADISK296[23] == true then
      acid1()
    end
    if ADISK296[24] == true then
      acid2()
    end
    if ADISK296[25] == true then
      ADISK29Menu()
    end
  end
  ADISK29 = 1
end
function WBM()
  ADISK296 = gg.multiChoice({
    "✪ ESP - 지형 V1〘로비전용〙",
    "✪ ESP - 지형 V2〘로비전용〙",
    "✪ 전신 색깔 화이트 V1〘로비전용〙",
    "✪ 전신 색깔 화이트 V2〘로비전용〙",
    "✪ 전신 색깔 화이트 V3〘로비전용〙",
    "✪ 전신 색깔 블랙 V1〘로비전용〙",
    "✪ 전신 색깔 블랙 V2〘로비전용〙",
    "✪ 전신 색깔 블랙 V3〘로비전용〙",
    " 뒤로가기"
  }, nil, "  Alpha SHOP VIP Script 1.0                                          { Auto Update } ")
  if ADISK296 == nil then
  else
    if ADISK296[1] == true then
      whmediatekv1()
    end
    if ADISK296[2] == true then
      whmediatekv2()
    end
    if ADISK296[3] == true then
      mwhitev1()
    end
    if ADISK296[4] == true then
      mwhitev2()
    end
    if ADISK296[5] == true then
      mwhitev3()
    end
    if ADISK296[6] == true then
      mblackv1()
    end
    if ADISK296[7] == true then
      mblackv2()
    end
    if ADISK296[8] == true then
      mblackv3()
    end
    if ADISK296[9] == true then
      ADISK29Menu()
    end
  end
  ADISK29 = 1
end
function FIL()
  ADISK296 = gg.multiChoice({
    "✪ 오토에임 Super V1〘로비전용〙",
    "✪ 오토에임 Super V2〘로비전용〙",
    "✪ 헤드 오토에임〘로비전용〙",
    "✪ 무반동〘로비전용〙",
    "✪ 반동저하〘로비전용〙",
    "✪ 바디샷 Super V1〘로비전용〙",
    "✪ 데미지 UP 〘로비전용〙",
    "✪ 바디샷 Super V2〘로비전용〙",
    "✪ 크로스헤어 Small 〘로비전용〙",
    " 뒤로가기"
  }, nil, " Alpha SHOP VIP Script 1.0                                          { Auto Update }  ")
  if ADISK296 == nil then
  else
    if ADISK296[1] == true then
      aimsuper()
    end
    if ADISK296[2] == true then
      aboutaim()
    end
    if ADISK296[3] == true then
      aimheadshot()
    end
    if ADISK296[4] == true then
      nor1()
    end
    if ADISK296[5] == true then
      ler()
    end
    if ADISK296[6] == true then
      mbh1()
    end
    if ADISK296[7] == true then
      mb1()
    end
    if ADISK296[8] == true then
      mb2()
    end
    if ADISK296[9] == true then
      sc()
    end
    if ADISK296[10] == true then
      ADISK29Menu()
    end
  end
  ADISK29 = 1
end
function FITG()
  ADISK296 = gg.multiChoice({
    "✪ 오토에임 V1〘로비전용〙",
    "✪ 오토에임 V2 〘로비전용〙",
    "✪ 오토에임 V3〘로비전용〙",
    "✪ 관통 V1〘로비전용〙",
    "✪ 유도탄〘로비전용〙",
    "✪ 타격데미지 증가〘로비전용〙",
    "✪ 수정중인 서비스〘로비전용〙",
    "✪ 수정중인 서비스〘로비전용〙",
    "✪ 수정중인 서비스〘로비전용〙",
    "✪ 수정중인 서비스〘로비전용〙",
    "✪ 잔디제거〘로비전용〙",
    "✪ 나무제거〘로비전용〙",
    "✪ 안테나 V1〘로비전용〙",
    "✪ 안테나 V2〘로비전용〙",
    "✪ 안테나 V3〘로비전용〙",
    "✪ 안테나 V4〘로비전용〙",
    "✪ 안테나 VIP〘로비전용〙",
    "✪ 아이템 안테나 [ 착용중인 Lv3 아이템 ]〘로비전용〙",
    "✪ 스코프 {앉기} ON〘로비전용〙 ",
    "✪ 스코프 {앉기} OFF〘로비전용〙",
    "✪ 4 배율 ON〘로비전용〙",
    "✪ 4 배율 OFF〘로비전용〙",
    "✪ 8 배율 ON〘로비전용〙",
    "✪ 8 배율 OFF〘로비전용〙 ",
    "✪ 12 배율 ON〘로비전용〙 ",
    "✪ 12 배율 OFF〘로비전용〙",
    "✪ 15 배율 ON〘로비전용〙",
    "✪ 15 배율 OFF〘로비전용〙 ",
    "✪ 16 배율 ON〘로비전용〙",
    "✪ 16 배율 OFF〘로비전용〙",
    "✪ 20 배율 ON〘로비전용〙",
    "✪ 20 베율 OFF〘로비전용〙",
    "✪ 캐릭터 크기 [ 소 ]〘로비전용〙",
    "✪ 캐릭터 크기 [ 대 ]〘로비전용〙",
    "✪ 어두운 하늘〘로비전용〙",
    "✪ 점프력 상승〘로비전용〙",
    "✪ 스피드 상승〘로비전용〙",
    "✪ 지프차 스피드 상승〘로비전용〙",
    "✪ 지프차 탑승시 물로〘로비전용〙",
    "✪ Kar98 바디샷〘로비전용〙 ",
    "✪ Kar98k 총알속도〘로비전용〙",
    "✪ AK47 총알속도〘로비전용〙",
    "✪ SCAR-L 총알속도〘로비전용〙",
    "✪ M416 총알속도〘로비전용〙",
    "✪ M16A4 총알속도〘로비전용〙",
    "✪ UZI 총알속도〘로비전용〙",
    "✪ GROZA 총알속도〘로비전용〙",
    "✪ M249 총알속도〘로비전용〙",
     "뒤로가기"
  }, nil, "  Alpha SHOP VIP Script 1.0                                           { Auto Update } ")
  if ADISK296 == nil then
  else
    if ADISK296[1] == true then
      aim1()
    end
    if ADISK296[2] == true then
      aim2()
    end
    if ADISK296[3] == true then
      aim3()
    end
    if ADISK296[4] == true then
      wallshotinfo()
    end
    if ADISK296[5] == true then
      bt()
    end
    if ADISK296[6] == true then
      gd()
    end
    if ADISK296[7] == true then
      broad6th()
    end
    if ADISK296[8] == true then
      broad9th()
    end
    if ADISK296[9] == true then
      broad12th()
    end
    if ADISK296[10] == true then
      broad15th()
    end
    if ADISK296[11] == true then
      NOGRASS()
    end
    if ADISK296[12] == true then
      NOTREE()
    end
    if ADISK296[13] == true then
      antsid1()
    end
    if ADISK296[14] == true then
      antsid2()
    end
    if ADISK296[15] == true then
      antup()
    end
    if ADISK296[16] == true then
      antbig()
    end
    if ADISK296[17] == true then
      antalways()
    end
    if ADISK296[18] == true then
      antitem()
    end
    if ADISK296[19] == true then
      sitscope1()
    end
    if ADISK296[20] == true then
      osc()
    end
    if ADISK296[21] == true then
      zoom4X()
    end
    if ADISK296[22] == true then
      zoom4XO()
    end
    if ADISK296[23] == true then
      zoom8X()
    end
    if ADISK296[24] == true then
      zoom8XO()
    end
    if ADISK296[25] == true then
      zoom12X()
    end
    if ADISK296[26] == true then
      zoom12XO()
    end
    if ADISK296[27] == true then
      zoom15X()
    end
    if ADISK296[28] == true then
      zoom15XO()
    end
    if ADISK296[29] == true then
      zoom16X()
    end
    if ADISK296[30] == true then
      zoom16XO()
    end
    if ADISK296[31] == true then
      zoom20X()
    end
    if ADISK296[32] == true then
      zoom20XO()
    end
    if ADISK296[33] == true then
      smallc()
    end
    if ADISK296[34] == true then
      bigc()
    end
    if ADISK296[35] == true then
      bs()
    end
    if ADISK296[36] == true then
      hjump()
    end
    if ADISK296[37] == true then
      speedhack1()
    end
    if ADISK296[38] == true then
      js()
    end
    if ADISK296[39] == true then
      jr()
    end
    if ADISK296[40] == true then
      ks()
    end
    if ADISK296[41] == true then
      aboutkar()
    end
    if ADISK296[42] == true then
      ak47()
    end
    if ADISK296[43] == true then
      scarl()
    end
    if ADISK296[44] == true then
      m416()
    end
    if ADISK296[45] == true then
      m16a4()
    end
    if ADISK296[46] == true then
      uzi()
    end
    if ADISK296[47] == true then
      groza()
    end
    if ADISK296[48] == true then
      m249()
    end
    if ADISK296[49] == true then
      ADISK29Menu()
    end
  end
  ADISK29 = 1
end
function FTB()
  ADISK296 = gg.multiChoice({
    "✪ 관통 V1〘로비전용〙",
    "✪ 헤드 오토에임 V1〘로비전용〙",
    "✪ 헤드 오토에임 V2〘로비전용〙",
    "✪ 오토에임 Super〘로비전용〙",
    "✪ 스코프 {앉기}〘로비전용〙 ",
    "✪ 반동저하 [ 대 ]〘로비전용〙",
    "✪ 반동저하 [ 중 ]〘로비전용〙",
    "✪ 반동저하 [ 소 ]〘로비전용〙",
    "✪ 무반동〘로비전용〙",
    "✪ 바디샷 [ 대 ]〘로비전용〙",
    " 뒤로가기"
  }, nil, "  Alpha SHOP VIP Script 1.0                                           { Auto Update }")
  if ADISK296 == nil then
  else
    if ADISK296[1] == true then
      wallshotinfo()
    end
    if ADISK296[2] == true then
      aimheadshot1()
    end
    if ADISK296[3] == true then
      aimheadshot2()
    end
    if ADISK296[4] == true then
      aimsuper()
    end
    if ADISK296[5] == true then
      sitscope1()
    end
    if ADISK296[6] == true then
      iwph()
    end
    if ADISK296[7] == true then
      iwpm()
    end
    if ADISK296[8] == true then
      iwpe()
    end
    if ADISK296[9] == true then
      nor1()
    end
    if ADISK296[10] == true then
      mbh1()
    end
    if ADISK296[11] == true then
      ADISK29Menu()
    end
  end
  ADISK29 = 1
end
function informasiftb()
  gg.alert([[
패치로그
[+] 헤드 오토에임
[+] 바디샷 [ 대 ]
[+] 유도탄]])
  FTB()
end
function aimheadshot1()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("-460", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("-560", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("1000", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function iwph()
  gg.clearResults()
  gg.searchNumber("1868784978;1850305641;28518", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1868784978", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100000)
  gg.editAll("9.999.999", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100000)
  gg.editAll("1.999.999.999", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function iwpm()
  gg.clearResults()
  gg.searchNumber("1868784978;1850305641;28518", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1868784978", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100000)
  gg.editAll("9.999.999", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100000)
  gg.editAll("1000000000", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function iwpe()
  gg.clearResults()
  gg.searchNumber("1868784978;1850305641;28518", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1868784978", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100000)
  gg.editAll("1868756429", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100000)
  gg.editAll("100000", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function aimheadshot2()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("-860", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("-960", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("1000", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function mb1()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("90.77570343018F;8.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(500)
  gg.editAll("-999999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function mbh()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1F;-8.6457681e12F;15F;28F;16F;26F;8F;18F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("15.0F;28.0F;16.0F;26.0F;8.0F;18.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(500)
  gg.editAll("92", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용시작")
end
function wallshotinfo()
  gg.alert("적용시작")
  wallshot()
end
function nor1()
  gg.alert("적용시작")
  nor()
end
function aboutkar()
  gg.alert("적용시작")
  FITG()
end
function broad15th()
  gg.alert("적용시작")
  FITG()
end
function sitscope1()
  gg.alert("적용시작")
  sitscope()
end
function aboutaim()
  gg.alert("적용시작")
  FIL()
end
function mbh1()
  gg.alert("적용시작")
  mbh()
end
function whal()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4.814603e21;3.5032462e-44;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.1848043e-44;-1.0285578e-38;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("304.00009155273;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function whkirin()
  gg.clearResults()
  gg.setRanges(131072)
  gg.searchNumber("4.7408155e21;2", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("2.25000190735;3.75055122375;2::", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(2)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("3.25000596046;2::", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("4.7408155e21;2", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(50)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("6.6121767e-39;1.1078259e-39;2", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(2)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("2.25000190735;3.75055122375;2::", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(50)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.toast("적용완료")
end
function whal2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.toast("적용완료")
  gg.clearResults()
end
function wh435()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4,141D;4.7408155e21;-5.5693206e-40;4.814603e21;3.7615819e-37;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(4)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-1.0285578e-38;3.7615819e-37;2;-1;1;-127::300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(4)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("304.00009155273;3.7615819e-37;2;-1;1;-127::240", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(4)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function wh835()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-1.0285578e-38;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("304.00009155273;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function wh845()
  gg.clearResults()
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function wh625()
  gg.clearResults()
  gg.setRanges(131072)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19::17", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(30)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.setRanges(131072)
  gg.searchNumber("-0.01000213623;2;-1;0;0.04000854492", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(30)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.setRanges(131072)
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(30)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.toast("적용완료")
end
function whitev1()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("76", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function whitev2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8.196D;256D;8204D;256D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("4001", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function yellowv1()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function yellowv2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8.196D;256D;8204D;256D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function pink()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("32,769;-2,134,900,722", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(15)
  gg.editAll("-50", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function greenv1()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("32,769;-2,134,900,722", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("32777", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function greenv2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("32,769;-2,134,900,722", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(15)
  gg.editAll("15", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function blackv1()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("-59", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function blackv2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("-59", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function diamondblue()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("62", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function diamondred()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("21", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function diamondgreen()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("358", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function mixyellowpink()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("23", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function greencrystal()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8196;256;8204;256;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("66.780", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function acid1()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("256;8200;16;15", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(180)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function acid2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("256;8200;16;15", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(180)
  gg.editAll("4", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function whmediatekv1()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("8E;2.5;6.0255834e-44::150", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("539,246,596;8200D;2.4903147e21F", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("8300", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("10000;0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("9", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function whmediatekv2()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("8E;2.5;6.0255834e-44::150", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("539,246,596;8200D;2.4903147e21F", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("8300", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("10000;0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("4,141D;4.7408155e21;-5.5693206e-40;4.814603e21;3.7615819e-37;2:", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-1.0285578e-38;3.7615819e-37;2;-1;1;-127::300", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(12)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function mwhitev1()
  gg.searchNumber(" 573.70306396484;0.05499718338;1 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5000)
  gg.editAll("999", gg.TYPE_FLOAT)
  gg.clearResults(5000)
  gg.clearResults()
  gg.toast("적용완료")
end
function mwhitev2()
  gg.searchNumber(" 573.70306396484;0.05499718338;1 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5000)
  gg.editAll("29", gg.TYPE_FLOAT)
  gg.clearResults(5000)
  gg.clearResults()
  gg.toast("적용완료")
end
function mwhitev3()
  gg.searchNumber(" 573.70306396484;0.05499718338;1 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5000)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.clearResults(5000)
  gg.clearResults()
  gg.toast("적용완료")
end
function mblackv1()
  gg.searchNumber(" 573.70306396484;0.05499718338;1 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(" 1.0 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1200)
  gg.editAll("-60", gg.TYPE_FLOAT)
  gg.clearResults(1200)
  gg.clearResults()
  gg.toast("적용완료")
end
function mblackv2()
  gg.searchNumber(" 573.70306396484;0.05499718338;1 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(" 1.0 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1200)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.clearResults(1200)
  gg.clearResults()
  gg.toast("적용완료")
end
function mblackv2()
  gg.searchNumber(" 573.70306396484;0.05499718338;1 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(" 1.0 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1200)
  gg.editAll("-9", gg.TYPE_FLOAT)
  gg.clearResults(1200)
  gg.clearResults()
  gg.toast("적용완료")
end
function mb2()
  gg.clearResults()
  gg.searchNumber("1,104,805,888D;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(250)
  gg.editAll("75", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("15;28;16;26;8;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(56)
  gg.editAll("111", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function nor()
  gg.clearResults()
  gg.searchNumber("1868784978;1850305641;28518", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1868784978", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("1868756421", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("100000", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function ler()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1.4012985e-45F;1F;1F;1F;1F;1000000F:100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function bt()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("88.15017700195;15:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("98", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("68", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("90.4850692749;27.25;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("27.25;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("88", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("1,104,805,888D;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(250)
  gg.editAll("111", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function aimsuper()
  gg.searchNumber("999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.5;1;200;20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("-1.0e10", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.5;1;200;20::959", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9999999999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
  gg.clearResults()
end
function aimheadshot()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("560", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("660", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
  gg.setVisible(false)
end
function aim1()
  gg.searchNumber("999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.clearResults()
  gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.5;1;200;20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("-1.0e10", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.clearResults()
  gg.searchNumber("8;16;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8;16;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("38.5", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function aim2()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("3.5;1;200;20::250 000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("9999999999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function aim3()
  gg.clearResults()
  gg.searchNumber("999", 16, false, 536870912, 0, -1)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("3.5;1;200;20::999", 16, false, 536870912, 0, -1)
  gg.searchNumber("3.5;1;200;20", 16, false, 536870912, 0, -1)
  gg.getResults(300)
  gg.editAll("-1.0e10", 16)
  gg.setRanges(32)
  gg.clearResults()
  gg.toast("적용완료")
end
function sc()
  gg.clearResults()
  gg.searchNumber("3.20000004768;1.09375", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function antsid1()
  gg.setRanges(32)
  gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F", 16, false, 536870912, 0, -1)
  gg.searchNumber("18.38613319397;0.53447723389;3.42665576935", 16, false, 536870912, 0, -1)
  gg.getResults(3)
  gg.editAll("99999", 16)
  gg.clearResults()
  gg.toast("적용완료")
end
function antup()
  gg.clearResults(850)
  gg.searchNumber("-0.08587168157F;7.13142681122F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("7.13142681122", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(850)
  print("Replaced: ", gg.editAll("9999", gg.TYPE_FLOAT))
  gg.clearResults()
  gg.toast("적용완료")
end
function antsid2()
  gg.clearResults()
  gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("9621", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("0.53446006775F;-1.68741035461F:501", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.68741035461", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function antalways()
  gg.clearResults()
  gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("9621", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("0.53446006775F;-1.68741035461F:501", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.68741035461", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function antbig()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18.38613319397;0.53447723389;3.42665576935", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("26666", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("96721", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("96721", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function antitem()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("7.1689529418945", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("999999999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("3.4779739379883;2.8345839977264;3.1967880725861;3.8841888904572;3.1528658866882::208", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.4779739379883", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("003,005,0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("7.4993133544922", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("7.4993133544922", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("0.73620933294296", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("999999999", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function NOGRASS()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("8.0F;1.20000004768F;0.80000001192F;1.5F;0.80000001192F;1.5F::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
  gg.clearResults()
end
function NOTREE()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("4.8883906e20", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function broad6th()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("220;178;15 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("438", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function broad9th()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("220;178;15 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("657", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function broad12th()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("220;178;15 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("876", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function sitscope()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1,092,081,726;1,003,658,240;923,795,456", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1,092,081,726", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("1,136,081,726", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function osc()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1,136,081,726;1,003,658,240;923,795,456", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1,255,181,826", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("1,092,081,726", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom4X()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;55;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("20", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom4XO()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;20;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("55", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom8X()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;55;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("15", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom8XO()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;15;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("55", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom12X()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;55;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("11", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom12XO()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;11;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("11", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("55", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom15X()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;55;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("9", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom15XO()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;9;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("55", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom16X()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;55;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("8", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function zoom16XO()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("60;8;1.9618179e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("55", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function bigc()
  gg.clearResults()
  gg.searchNumber("3.0828566e-44;88;88;1;1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_FLOAL, 0, -1)
  gg.getResults(50)
  gg.editAll("1.28", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function smallc()
  gg.clearResults()
  gg.searchNumber("3.0828566e-44;88;88;1;1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_FLOAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.5", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function wallshot()
  gg.searchNumber("869,711,765D;2;1::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("-25", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function bs()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
  gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function gd()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("90.775703430176;0;8;15;16;18;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("1000", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function speedhack1()
  gg.clearResults()
  gg.searchNumber("999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults()
  gg.setRanges(gg.REGION_CODE_APP)
  gg.searchNumber("10.90734863281;0.00999999978", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("10.9073486328", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("10.411", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function hjump()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1.0F; -0.70710676908F; 0.70710670948F; 64.0F; 1.793662e-43F;1.4012985e-45F; 1D; 1D ::512", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
  gg.searchNumber("1.4012985e-45", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("999.0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function jspeed()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("적용완료")
end
function jr()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("150;85;45;-129;-85", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(45, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("99996", gg.TYPE_FLOAT)
  gg.clearResults(1314520)
  gg.toast("적용완료")
end
function ak47()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04800000022", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function scarl()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04200000272", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function m416()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.001", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function uzi()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04800000022", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function m16a1()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04200000272", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function m249()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.001", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function groza()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04800000022", gg.TYPE_FLOAT)
  gg.toast("적용완료")
end
function ks()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("200000", gg.TYPE_FLOAT)
  gg.toast("적용완료")
  gg.clearResults()
end
function MYCK()
  CONTACT = gg.choice({
    "판매자 연락처",
    "개발자 연락처",
    "스크립트 버전",
    "개발자가 남기는 메시지",
    " 뒤로가기"
  }, nil, "Alpha SHOP VIP Script 1.0                                          { Auto Update }")
  if CONTACT == 1 then
    Em()
  end
  if CONTACT == 2 then
    YT()
  end
  if CONTACT == 3 then
    DC()
  end
  if CONTACT == 4 then
    DS()
  end
  if CONTACT == 5 then
    ADISK29Menu()
  end
  ADISK29 = -1
end
function Em()
  gg.alert("카카오톡 : star1926")
  MYCK()
end
function YT()
  gg.alert("카카오톡 : ruciper12345")
  MYCK()
end
function DC()
  gg.alert("Alpha SHOP VIP Script 1.0                                 가지각색의 기능들이 모여 제작된 VIP 오토업데이트 버전입니다. 로그인 전용 패스워드는 매주 일요일마다 변경되며, 구매자 채팅방에 패스워드 공지예정입니다.")
  MYCK()
end
function DS()
  gg.alert("구매 감사합니다. 구매하실때, 판매원에게 절반의 돈을, 나머지 절반을 개발자 카카오톡으로 보내주시면 됩니다. 판매원이 스크립트 값을 혼자 모두받았다면 개발자 카카오톡으로 연락주십시오.")
  MYCK()
end
function Exit()
  gg.alert("구매하실때, 판매원에게 절반의 돈을, 나머지 절반을 개발자 카카오톡으로 보내주시면 됩니다. 판매원이 스크립트 값을 혼자 모두받았다면 개발자 카카오톡으로 연락주십시오.")
  os.exit()
end
cs = "Adisk29"
while true do
  if gg.isVisible(true) then
    ADISK29 = 1
    gg.setVisible(false)
  end
  gg.clearResults()
  if ADISK29 == 1 then
    ADISK29Menu()
  end
end
