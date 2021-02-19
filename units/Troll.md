---
title: "Великан Тор"
permalink: /units/Troll/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Тор наделен неимоверной силой. Он способен поднимать и бросать каменные глыбы во врагов, нанося ужасающие раны."
unitID: 409
last_modified_at: 2021-02-19
locale: ru
ref: "Великан Тор"
toc: true
---
**Warning** Information on this page is based on Chronicles! This unit is not released yet, provided information can be corrected later!
{: .notice--danger}

## General information
 **Описание:** Тор наделен неимоверной силой. Он способен поднимать и бросать каменные глыбы во врагов, нанося ужасающие раны.

 **Описание:** [Стрелковый](/units/Unit Class Стрелковый)

 **Описание Описание:** Чем дальше стрелковый отряд от цели, тем больше наносимый ими урон.

 **Faction:** [Цитадель](/units/Fraction Цитадель)

 **Race:** Хозяин зверей

 **Members:** [x1](/units/Unit Member x1)

 **Rank:** [Командующий](/units/Unit Rank Командующий)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 3)

 **Short description:** Single-target assault. Burst damage.

 **Position :** Single-target assault. Burst damage.

## Basic stats
 **Base HP: 9051.0**

 **Base ATK: 1018.3**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 509.15 | 7.5 | 6788.25 |
  | Синий | 1018.3 | 15.0 | 13576.5 |
  | Blue +1 | 1527.45 | 22.5 | 20364.75 |
  | Синий +2 | 2138.43 | 31.5 | 28510.65 |
  | Фиолетовый | 2749.41 | 40.5 | 36656.55 |
  | Фиолетовый +1 | 3360.39 | 49.5 | 44802.45 |
  | Фиолетовый +2 | 4073.2 | 60.0 | 54306.0 |
  | Фиолетовый +3 | 4786.01 | 70.5 | 63809.55 |
  | Оранжевый | 5498.82 | 81.0 | 73313.1 |
  | Оранжевый +1 | 6313.46 | 93.0 | 84174.3 |
  | Оранжевый +2 | 7128.1 | 105.0 | 95035.5 |
  | Orange +3 | 7942.74 | 117.0 | 105896.7 |
  | Оранжевый +4 | 8757.38 | 129.0 | 116757.9 |
  | Orange +5 | 9979.34 | 147.0 | 133049.7 |
  | Red | 11608.62 | 171.0 | 154772.1 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 142.562 | 0.24 | 4.3 | 1267.14 |
  | **4x** <i class="fas fa-star"/> | 162.928 | 0.25 | 4.95 | 1448.16 |
  | **5x** <i class="fas fa-star"/> | 183.294 | 0.26 | 5.6 | 1629.18 |
  | **6x** <i class="fas fa-star"/> | 203.66 | 0.28 | 6.25 | 1810.2 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Цепь из камней](/equipment/Цепь из камней/) | **АТК** | **DEF** | 
  | [Мощь владыки](/equipment/Мощь владыки/) | **ОЗ** | **DEF** | 
  | [Доспех павшего врага](/equipment/Доспех павшего врага/) | **АТК** | **DEF** | 
  | [Сапоги дозорного](/equipment/Сапоги дозорного/) | **ОЗ** | **DEF** | 

## Recommended Holy Emblems

* [Суд отцов](/Emblem/The Judgment of Fathers/) (Нейтральный)
* [Гордыня](/Emblem/Arrogance/) (Хаос)
* [Королевская беда](/Emblem/King's Calamity/) (Злой)

## Combination Info

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimate Skill: Мощь метеоритов
 **Описание:** <span style="color: #645252;font-size:20px">При каждой атаке Тор бросает в цели каменные глыбы: </span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">целям наносится урон в размере </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> атаки Тора и в </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от их макс. ОЗ.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Все вражеские отряды в большой области (кроме летающих) </span><span style="color: black"><span style="color: #48b946;font-size:20px">замедляются</span><span style="color: black"><span style="color: #645252;font-size:20px"> на 3 сек.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">У </span><span style="color: black"><span style="color: #48b946;font-size:20px">оглушенных</span><span style="color: black"><span style="color: #645252;font-size:20px"> вражеских отрядов в большой области на 20% снижаются защита и сопротивление урону. Эффект длится 5 сек.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Вражеским отрядам в большой области под действием </span><span style="color: black"><span style="color: #48b946;font-size:20px">сдерживания</span><span style="color: black"><span style="color: #645252;font-size:20px"> наносится урон в </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от атаки Тора.</span><span style="color: black">

### Regular Skill 1 : Каменные жилы
 **Описание:** <span style="color: #645252;font-size:20px">На Тора не действует </span><span style="color: black"><span style="color: #48b946;font-size:20px">сдерживание, истощение и низкий боевой дух</span><span style="color: black"><span style="color: #645252;font-size:20px">, его здоровье повышено на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">, а сопротивление урону - на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Эффект исцеления Тора снижен на 100%, но каждые 2 сек. у него восстанавливается здоровье на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от максимального.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Когда Тора атакуют вражеские отряды ближнего боя, на 2 сек. накладывается </span><span style="color: black"><span style="color: #48b946;font-size:20px">упадок сил</span><span style="color: black"><span style="color: #645252;font-size:20px">. </span><span style="color: black"><span style="color: #48b946;font-size:20px">Упадок сил</span><span style="color: black"><span style="color: #645252;font-size:20px"> активируется раз в 7 сек.</span><span style="color: black">

### Regular Skill 2 : Буйство
 **Описание:** <span style="color: #645252;font-size:20px">Troll increases Critical Hit by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">, and this effect is doubled when HP drops below 50%. Rampage is triggered the first time the Troll's HP drops below 60% or 4 friendly units are destroyed. After the rampage, Troll upgrades to Troll Warlord and &lt;Meteor's Might&gt; upgrades to &lt;Meteor Burst&gt;.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">&lt;Meteor Burst&gt;: </span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Deals damage equal to </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> of own ATK plus </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> of the target unit's Max HP to the target unit.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Deals damage equal to 15% of own ATK to 3 random enemy units.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">&lt;Meteor Burst&gt; is cast at a steady rate of once per second and is not affected by Attack Speed bonuses, crowd control skills, or range.</span><span style="color: black">

### Regular Skill 3 : Паника бога войны
 **Описание:** <span style="color: #645252;font-size:20px">У Тора на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str10"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> повышается атака и на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str11"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> - урон отряда. Если у его цели </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;упадок сил&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, она получает на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str12"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> больше урона отряда и на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str13"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> больше крит. урона. </span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">При каждой атаке Тора на его текущие цели на 0,1 сек. накладывается </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;окаменение&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, также игнорируется </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str14"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> защиты целей. </span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Каждый размещенный отряд Цитадели повышает отрядный урон Тора на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str15"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Faction Special Skill I : Фанатик сражений
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Цитадели умеют сражаться в свирепых длительных боях. Их скорость атаки будет увеличена на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str16"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> за каждые 15% потерянных ОЗ.</span><span style="color: black">

### Faction Special Skill II : Рост живучести
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Цитадели хорошо разбираются в лечении на поле боя, восстанавливая </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str17"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ОЗ каждые 3 сек. и получив </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str18"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к высасыванию жизни.</span><span style="color: black">

### Regular Skill 6 : Lord of the Wilderness
 **Описание:** <span style="color: #645252;font-size:20px">When 3 Stronghold units are deployed, increases own Unit DMG by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str19"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> and Critical Hit DMG by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str20"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">6s after the battle starts, the Troll forms a </span><span style="color: black"><span style="color: #F0F000;font-size:20px">&lt;Wilderness Deathtrap&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> domain, which expands as the skill levels up. The domain exists for 15s. The domain forms once every 30s after that.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str20 = "LEVEL*2+30"
    let str7 = "LEVEL*40+160"
    let str8 = "LEVEL*10+120"
    let str5 = "LEVEL*2+8"
    let str18 = "(LEVEL*0.3+1)"
    let str6 = "LEVEL*0.3+1.2"
    let str19 = "LEVEL*1+15"
    let str3 = "LEVEL*0.5+2.5"
    let str4 = "LEVEL*5+25"
    let str1 = "LEVEL*5+120"
    let str2 = "LEVEL*0.2+1"
    let str12 = "LEVEL*1+15"
    let str13 = "LEVEL*3+5"
    let str10 = "LEVEL*5+25"
    let str11 = "LEVEL*2+10"
    let str16 = "(LEVEL*0.3+0.5)"
    let str17 = "(LEVEL*300+1200)"
    let str9 = "LEVEL*0.2+1"
    let str14 = "LEVEL*2+10"
    let str15 = "LEVEL*0.3+1.5"
    let res="ERR";
    try {
     res = eval(str20); document.getElementById('str20').textContent = res;
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str18); document.getElementById('str18').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str19); document.getElementById('str19').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
     res = eval(str12); document.getElementById('str12').textContent = res;
     res = eval(str13); document.getElementById('str13').textContent = res;
     res = eval(str10); document.getElementById('str10').textContent = res;
     res = eval(str11); document.getElementById('str11').textContent = res;
     res = eval(str16); document.getElementById('str16').textContent = res;
     res = eval(str17); document.getElementById('str17').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
     res = eval(str14); document.getElementById('str14').textContent = res;
     res = eval(str15); document.getElementById('str15').textContent = res;
    } catch (e) { log.textContent = "Issue with calculation!";}
    if (event!=null)
      event.preventDefault();
  }
  const form = document.getElementById('form');
  const log = document.getElementById('log');
  form.addEventListener('submit', skillCalc);
  window.onload = skillCalc;
  </script>
## Relevance
### Roster Connection

* **Цитадель**  (Дозор отрядов Цитадели)
* **Стрелок**  (Дозор стрелковых отрядов)

### Hero Bonus
* [Kilgor](/heroes/Kilgor/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Джелу](/heroes/Gelu/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Crag Hack](/heroes/Crag Hack/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Критический удар отряда
* unit Damage


## Awaking
### Awaking Details
 **Is it possible right now?** NO

 **Awaking Name:** null

 **Awaking Description:** null

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 7.0

 **fly:** jushi

 **flyspeed:** 350

 **atkfly:** 5

 **Rush:** 3

 **Speedattack:** 120

 **Attack Show:** 9.0

 **Attack Area:** 420

 **Attack Range:** 460

 **Attack Speed Show:** 4.0

 **Defense Show:** 7.0

 **Score:** 1630

 **HP Show:** 9

 **disrdcvol:** 70

 **Dead Type:** 1

 **s:** 4

 **label1:** 5

 **speedmove:** 90

 **posclass:** 4

 **talk1:** Вы просто букашки!

 **talk2:** Вы что, решили, что я слеп?

 **talk3:** Интересно, далеко я заброшу этот камень?

