---
title: "Жар-птица"
permalink: /units/Firebird/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Нет более могучих элементалей, чем жар-птицы. Они обитают в огне, дарующем им вечную жизнь. Ревущее пламя вокруг них выжигает любое зло."
unitID: 907
last_modified_at: 2021-02-19
locale: ru
ref: "Жар-птица"
toc: true
---
## General information
 **Описание:** Нет более могучих элементалей, чем жар-птицы. Они обитают в огне, дарующем им вечную жизнь. Ревущее пламя вокруг них выжигает любое зло.

 **Описание:** [Заклинатель](/units/Unit Class Заклинатель)

 **Описание Описание:** With their mastery of the secrets of magic, Caster units have higher magic resistance.

 **Faction:** [Conflux](/units/Fraction Conflux)

 **Race:** Единорог

 **Members:** [x4](/units/Unit Member x4)

 **Rank:** [SR](/units/Unit Rank SR)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 3)

 **Unit description:** Огненное дыхание: наносит урон всем вражеским отрядам на своем пути.

 **Short description:** Стрелковый УРН огнем. Возрождается при смерти.

 **Position :** Обладает способностью оживлять, наносит огромный урон огнем всем врагам на своем пути.

 **Unit extra description:** Жар-птицы особенно сильны, когда атакуют группой. Они могут возрождаться.

 **Recommend:** High burst damage, high attack damage and enhancement of fire skills.

## Basic stats
 **Base HP: 4525.0**

 **Base ATK: 848.5**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 424.25 | 3.75 | 3393.75 |
  | Синий | 848.5 | 7.5 | 6787.5 |
  | Blue +1 | 1272.75 | 11.25 | 10181.25 |
  | Синий +2 | 1781.85 | 15.75 | 14253.75 |
  | Фиолетовый | 2290.95 | 20.25 | 18326.25 |
  | Фиолетовый +1 | 2800.05 | 24.75 | 22398.75 |
  | Фиолетовый +2 | 3394.0 | 30.0 | 27150.0 |
  | Фиолетовый +3 | 3987.95 | 35.25 | 31901.25 |
  | Оранжевый | 4581.9 | 40.5 | 36652.5 |
  | Оранжевый +1 | 5260.7 | 46.5 | 42082.5 |
  | Оранжевый +2 | 5939.5 | 52.5 | 47512.5 |
  | Orange +3 | 6618.3 | 58.5 | 52942.5 |
  | Оранжевый +4 | 7297.1 | 64.5 | 58372.5 |
  | Orange +5 | 8315.3 | 73.5 | 66517.5 |
  | Red | 9672.9 | 85.5 | 77377.5 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 118.79 | 0.44 | 2.65 | 633.5 |
  | **4x** <i class="fas fa-star"/> | 135.76 | 0.46 | 3.23 | 724.0 |
  | **5x** <i class="fas fa-star"/> | 152.73 | 0.48 | 3.8 | 814.5 |
  | **6x** <i class="fas fa-star"/> | 169.7 | 0.5 | 4.38 | 905.0 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Клюв неистового пламени](/equipment/Клюв неистового пламени/) | **АТК** | **DEF** | 
  | [Rune of Resurrection](/equipment/Rune of Resurrection/) | **ОЗ** | **DEF** | 
  | [Claws of Raging Flame](/equipment/Claws of Raging Flame/) | **АТК** | **DEF** | 
  | [Радужные оперенные крылья](/equipment/Радужные оперенные крылья/) | **ОЗ** | **DEF** | 

## Recommended Holy Emblems

* [Древний огонь](/Emblem/Ancient Fire/) (Порядок)
* [Наследие Айронфиста](/Emblem/Ironfist's Legacy/) (Порядок)
* [Королевская беда](/Emblem/King's Calamity/) (Злой)

## Combination Info

* [Горение](/combination/Горение/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimate Skill: Огненное дыхание
 **Описание:** <span style="color: #645252;font-size:20px">Жар-птицы истребляют вражеские отряды в широком радиусе перед собой, нанося </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ед. урона. Критический удар по </span><span style="color: black"><span style="color: #48b946;font-size:20px">горящим</span><span style="color: black"><span style="color: #645252;font-size:20px"> отрядам повышается на 500.</span><span style="color: black">

### Regular Skill 1 : Огненный язык
 **Описание:** <span style="color: #645252;font-size:20px">В бою жар-птиц против отряда из 9 бойцов при обычной атаке наносится </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> урона по области по 3 вражеским целям.</span><span style="color: black">

### Regular Skill 2 : Воскрешение
 **Описание:** <span style="color: #645252;font-size:20px">Firebird revives 5s after its first death, restoring </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> of its HP.</span><span style="color: black">

### Regular Skill 3 : Огненное усиление
 **Описание:** <span style="color: #645252;font-size:20px">У жар-птиц иммунитет к </span><span style="color: black"><span style="color: #48b946;font-size:20px">горению</span><span style="color: black"><span style="color: #645252;font-size:20px"> и получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к КРИТ. УРН.</span><span style="color: black">

### Faction Special Skill I : Elemental Affinity
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Гармонии мастерски владеют таинственной магией Гармонии и повышают сопротивление магии у героев на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Faction Special Skill II : Конфликт с элементалями
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Гармонии мастерски наносят урон Гармонии. В бою против отрядов не из Гармонии они получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"></span><span style="color: black"><span style="color: #645252;font-size:20px"> к урону.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*3+15)"
    let str6 = "(LEVEL*1+5)"
    let str3 = "(LEVEL*3+27)"
    let str4 = "LEVEL*5+25"
    let str1 = "(LEVEL*2+38)*0.01*ATK"
    let str2 = "LEVEL*1+39"
    let res="ERR";
    try {
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
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

* **Гармония**  (Дозор отрядов Гармонии)
* **Caster**  (Дозор отрядов заклинателей)

### Hero Bonus
* [Luna](/heroes/Luna/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Дракон](/heroes/Dracon/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Критический удар отряда
* unit Damage


## Awaking
### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Феникс

 **Awaking Description:** The wheel of time rolls forward without stopping. The fire of life goes out and rekindles. Death breeds new life. You shall witness the birth of a new life in the fiery flames. The flames of its rebirth will turn all evil to ashes!

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Используйте жар-птиц и не менее </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> отрядов-магов, чтобы победить </span><span style="color: #1ca216;font-size:18px">14</span><span style="color: #3c2a1e;font-size:18px"> волн зомби в Склепе. (Набег не учитывается при выполнении этого задания).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> ресурсов в Походе гильдии. </span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ фениксов на уровнях 15-2 и 15-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте жар-птиц и не менее </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отрядов-магов, чтобы победить в </span><span style="color: #1ca216;font-size:18px">12</span><span style="color: #3c2a1e;font-size:18px"> боях в кампании.</span>

## Awaken Skills

### 1st Skill (or 2nd): Вечный огонь
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Воскрешение&gt;</span><span style="color: #645252;font-size:18px">: возрождается каждый раз после смерти (восстановление - 20 сек.)</span>

### 2nd Skill (or 1st): Бескрайняя буря
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Воскрешение&gt;</span><span style="color: #645252;font-size:18px">: после воскрешения все вражеские отряды получают урон, равный 8% от максимума здоровья, и получают горение на 15 сек.</span>

### 3rd Skill (or 4th): Взрывной крест
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Огненное дыхание&gt;</span><span style="color: #645252;font-size:18px">: врагам, стоящим в одном ряду с целью, наносится дополнительный урон (целям на пересечении - двойной урон)</span>

### 4th Skill (or 3rd): Lava Breath
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Огненное дыхание&gt;</span><span style="color: #645252;font-size:18px">: урон повышается до 200%</span>

### 5th Skill (or 6th): Бескрайняя ярость
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Огненное усиление&gt;</span><span style="color: #645252;font-size:18px">: урон отряда увеличивается на 30%</span>

### 6th Skill (or 5th): Растущее пламя
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Огненное усиление&gt;</span><span style="color: #645252;font-size:18px">: горящим целям гарантированно наносится КРИТ. УРН</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **fly:** huoshe

 **flyspeed:** 300

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 9.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 4.0

 **Score:** 1349

 **HP Show:** 5

 **disrdcvol:** 40

 **Dead Type:** 3

 **s:** 4

 **label1:** 11

 **speedmove:** 80

 **posclass:** 5

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

