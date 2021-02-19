---
title: "Harpy"
permalink: /units/Harpy/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Наполовину человек, а наполовину - птица. Их пронзительный визг просто невыносим."
unitID: 702
last_modified_at: 2021-02-19
locale: ru
ref: "Harpy"
toc: true
---
## General information
 **Описание:** Наполовину человек, а наполовину - птица. Их пронзительный визг просто невыносим.

 **Описание:** [Штурм](/units/Unit Class Штурм)

 **Описание Описание:** Штурмовые отряды атакуют задний ряд, нанося повышенный критический урон стрелковым отрядам и заклинателям.

 **Faction:** [Dungeon](/units/Fraction Dungeon)

 **Race:** Войска Подземелья

 **Members:** [x9](/units/Unit Member x9)

 **Rank:** [SR](/units/Unit Rank SR)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 2)

 **Unit description:** Enchantress' Sharp Claw: It has a chance of causing damage to several enemies

 **Short description:** Поддержка. Сдерживание толпы.

 **Position :** Высокий УВС. Подавляет наземные отряды и создает возможности для атаки союзных отрядов.

 **Recommend:** Существа с низким здоровьем и высокой атакой. Они будут чрезвычайно эффективны, если не забывать их вовремя лечить.

## Basic stats
 **Base HP: 860.0**

 **Base ATK: 74.0**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 37.0 | 6.75 | 645.0 |
  | Синий | 74.0 | 13.5 | 1290.0 |
  | Blue +1 | 111.0 | 20.25 | 1935.0 |
  | Синий +2 | 155.4 | 28.35 | 2709.0 |
  | Фиолетовый | 199.8 | 36.45 | 3483.0 |
  | Фиолетовый +1 | 244.2 | 44.55 | 4257.0 |
  | Фиолетовый +2 | 296.0 | 54.0 | 5160.0 |
  | Фиолетовый +3 | 347.8 | 63.45 | 6063.0 |
  | Оранжевый | 399.6 | 72.9 | 6966.0 |
  | Оранжевый +1 | 458.8 | 83.7 | 7998.0 |
  | Оранжевый +2 | 518.0 | 94.5 | 9030.0 |
  | Orange +3 | 577.2 | 105.3 | 10062.0 |
  | Оранжевый +4 | 636.4 | 116.1 | 11094.0 |
  | Orange +5 | 725.2 | 132.3 | 12642.0 |
  | Red | 843.6 | 153.9 | 14706.0 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 8.88 | 0.53 | 3.34 | 103.2 |
  | **3x** <i class="fas fa-star"/> | 10.36 | 0.55 | 3.97 | 120.4 |
  | **4x** <i class="fas fa-star"/> | 11.84 | 0.58 | 4.61 | 137.6 |
  | **5x** <i class="fas fa-star"/> | 13.32 | 0.6 | 5.24 | 154.8 |
  | **6x** <i class="fas fa-star"/> | 14.8 | 0.63 | 5.88 | 172.0 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Heart Stab Dagger](/equipment/Heart Stab Dagger/) | **АТК** | **DEF** | 
  | [Мистическая броня](/equipment/Мистическая броня/) | **ОЗ** | **DEF** | 
  | [Когтистый убийца](/equipment/Когтистый убийца/) | **АТК** | **DEF** | 
  | [Наплечники чаровницы](/equipment/Наплечники чаровницы/) | **ОЗ** | **DEF** | 

## Recommended Holy Emblems

* [Ангел-хранитель](/Emblem/Guardian Angel/) (Добро)
* [Jealousy](/Emblem/Jealousy/) (Хаос)
* [Разбитое пророчество](/Emblem/Broken Prophecy/) (Злой)

## Combination Info

* [Оглушение](/combination/Оглушение/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimate Skill: Острый коготь гарпии
 **Описание:** <span style="color: #645252;font-size:20px">Когда гарпии подвергаются атаке, они получают шанс нанести </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> урон 3 отрядам. Шанс активации имеется и при обычной атаке.</span><span style="color: black">

### Regular Skill 1 : High Suppression
 **Описание:** <span style="color: #645252;font-size:20px">В бою против нелетающего отряда гарпии получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к АТК.</span><span style="color: black">

### Regular Skill 2 : Крик разрушителя магии
 **Описание:** <span style="color: #645252;font-size:20px">Whenever a hostile hero casts a spell, the Harpy decreases the unit damage reduction of the units in the same path by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> for 6s, up to 3 stacks.</span><span style="color: black">

### Regular Skill 3 : Aiming in Mid Air
 **Описание:** <span style="color: #645252;font-size:20px">Гарпии получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к КРИТ. УРН. Гарпии гарантированно выполняют критические удары по <span style="color: #48b946;font-size:20px">оглушенным</span><span style="color: black"><span style="color: #645252;font-size:20px"> целям.</span><span style="color: black">

### Faction Special Skill : Темный конфликт
 **Описание:** <span style="color: #645252;font-size:20px">Dungeon units are proficient at making use of terrain, increasing their unit's damage by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> when fighting against the non-Dungeon units</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*1+5)"
    let str3 = "LEVEL*0.5+3.9"
    let str4 = "LEVEL*5+25"
    let str1 = "LEVEL*9+141"
    let str2 = "LEVEL*6+24"
    let res="ERR";
    try {
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
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

* **Подземелье**  (Дозор отрядов Подземелья)
* **Charging**  (Дозор штурмовых отрядов)

### Hero Bonus
* [Mullich](/heroes/Mullich/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Mutare](/heroes/Mutare/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Dragon Mutare](/heroes/Dragon Mutare/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Скорость атаки
* Magic resistance


## Awaking
### Awaking Details
 **Is it possible right now?** NO

 **Awaking Name:** 

 **Awaking Description:** null

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Deploy Pikemen with at least </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> Castle units and kill </span><span style="color: #1ca216;font-size:18px">1,000</span><span style="color: #3c2a1e;font-size:18px"> dwarves in the Dwarven Treasury in a single battle. (Sweep does not count towards the mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Kill </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> monsters during a Guild adventure.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ алебардщиков на уровнях 14-2 и 14-4 Подземелья.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте копейщиков и не менее </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отрядов Замка, чтобы победить в </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> боях Дуэли заступников.</span>

## Awaken Skills

### 1st Skill (or 2nd): Лес копий: зачистка
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лес копий&gt;</span><span style="color: #645252;font-size:18px">: целью становятся более крупные отряды врага.</span>

### 2nd Skill (or 1st): Внезапный лес копий
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Spear Array&gt;</span><span style="color: #645252;font-size:18px"> damage increases to 150%, and stun effect is increased to 4.5 seconds</span>

### 3rd Skill (or 4th): Плотный строй
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Leadership&gt;</span><span style="color: #645252;font-size:18px">When in combat with \"High Morale\", increases unit's damage reduction by 30%, lasts for 10s</span>

### 4th Skill (or 3rd): Лукавый строй
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Leadership&gt;</span><span style="color: #645252;font-size:18px">When in combat, increases Magic resistance by 30% when in \"High Morale\", lasts for 10s</span>

### 5th Skill (or 6th): Infiltration Strategy
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Dragon Slaying&gt;</span><span style="color: #645252;font-size:18px">When facing 1-man or 4-man units, applies &lt;deterrence&gt; on the target. &lt;Deterrence&gt;: Decreases the target's Crit Hit by 300</span>

### 6th Skill (or 5th): Fatigue Attack
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Убийство драконов&gt;</span><span style="color: #645252;font-size:18px">: в бою с отрядом из 1 или 4 существ уклонение цели понижается на 300</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 2

 **Speedattack:** 160

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 280

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 728

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 7

 **speedmove:** 120

 **posclass:** 3

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

