---
title: "Гоблин"
permalink: /units/Goblin/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Goblins wear light armor and wield heavy weapons. These brutal and relentless warriors rapidly crush the defenses of their enemies."
unitID: 401
last_modified_at: 2021-02-19
locale: ru
ref: "Гоблин"
toc: true
---
## General information
 **Описание:** Goblins wear light armor and wield heavy weapons. These brutal and relentless warriors rapidly crush the defenses of their enemies.

 **Описание:** [Наступление](/units/Unit Class Наступление)

 **Описание Описание:** Атакующие отряды могут ослаблять броню противников. Этот эффект не суммируется.

 **Faction:** [Цитадель](/units/Fraction Цитадель)

 **Race:** Орк

 **Members:** [x9](/units/Unit Member x9)

 **Rank:** [R](/units/Unit Rank R)

 **Starts:** [<i class="fas fa-star"/>](/units/Star 1)

 **Unit description:** Боевой шторм: наносит урон 3 ближайшим вражеским отрядам.

 **Short description:** Стрелковая контратака. Высасывание жизни при критическом ударе.

 **Position :** Часто контратакует. Наносит высокий урон в ближнем бою. Чем ниже здоровье, тем выше показатель атаки.

 **Recommend:** Существа с низким здоровьем и высокой атакой. Они будут чрезвычайно эффективны, если не забывать их вовремя лечить.

## Basic stats
 **Base HP: 761.0**

 **Base ATK: 82.7**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 41.35 | 4.25 | 570.75 |
  | Синий | 82.7 | 8.5 | 1141.5 |
  | Blue +1 | 124.05 | 12.75 | 1712.25 |
  | Синий +2 | 173.67 | 17.85 | 2397.15 |
  | Фиолетовый | 223.29 | 22.95 | 3082.05 |
  | Фиолетовый +1 | 272.91 | 28.05 | 3766.95 |
  | Фиолетовый +2 | 330.8 | 34.0 | 4566.0 |
  | Фиолетовый +3 | 388.69 | 39.95 | 5365.05 |
  | Оранжевый | 446.58 | 45.9 | 6164.1 |
  | Оранжевый +1 | 512.74 | 52.7 | 7077.3 |
  | Оранжевый +2 | 578.9 | 59.5 | 7990.5 |
  | Orange +3 | 645.06 | 66.3 | 8903.7 |
  | Оранжевый +4 | 711.22 | 73.1 | 9816.9 |
  | Orange +5 | 810.46 | 83.3 | 11186.7 |
  | Red | 942.78 | 96.9 | 13013.1 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 8.27 | 0.49 | 1.7 | 76.1 |
  | **2x** <i class="fas fa-star"/> | 9.924 | 0.51 | 2.29 | 91.32 |
  | **3x** <i class="fas fa-star"/> | 11.578 | 0.54 | 2.87 | 106.54 |
  | **4x** <i class="fas fa-star"/> | 13.232 | 0.56 | 3.46 | 121.76 |
  | **5x** <i class="fas fa-star"/> | 14.886 | 0.59 | 4.04 | 136.98 |
  | **6x** <i class="fas fa-star"/> | 16.54 | 0.61 | 4.63 | 152.2 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Шипованная дубина](/equipment/Шипованная дубина/) | **АТК** | **DEF** | 
  | [Кожаный пояс](/equipment/Кожаный пояс/) | **ОЗ** | **DEF** | 
  | [Ожерелье из кости](/equipment/Ожерелье из кости/) | **АТК** | **DEF** | 
  | [Leather Pauldrons](/equipment/Leather Pauldrons/) | **ОЗ** | **DEF** | 

## Recommended Holy Emblems

* [Крылья грифона](/Emblem/Griffin Wings/) (Порядок)
* [Jealousy](/Emblem/Jealousy/) (Хаос)
* [Разбитое пророчество](/Emblem/Broken Prophecy/) (Злой)

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
### Ultimate Skill: Боевой шторм
 **Описание:** <span style="color: #645252;font-size:20px">При обычной атаке у гоблинов есть шанс нанести урон в размере </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> АТК трем вражеским отрядам.</span><span style="color: black">

### Regular Skill 1 : Rampage
 **Описание:** <span style="color: #645252;font-size:20px">Гоблины получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str2"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> к критическому удару. Эффект удваивается при ОЗ менее 35% и продолжает действовать при восстановлении ОЗ.</span><span style="color: black">

### Regular Skill 2 : Execution
 **Описание:** <span style="color: #645252;font-size:20px">В бою против отряда с менее 30% ОЗ гоблины получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к АТК.</span><span style="color: black">

### Regular Skill 3 : Жажда крови
 **Описание:** <span style="color: #645252;font-size:20px">Goblin's HP increased by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">. 2% of HP will be restored for every Crit Hit done.</span><span style="color: black">

### Faction Special Skill I : Фанатик сражений
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Цитадели умеют сражаться в свирепых длительных боях. Их скорость атаки будет увеличена на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> за каждые 15% потерянных ОЗ.</span><span style="color: black">

### Faction Special Skill II : Рост живучести
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Цитадели хорошо разбираются в лечении на поле боя, восстанавливая </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ОЗ каждые 3 сек. и получив </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к высасыванию жизни.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*0.3+1)"
    let str5 = "(LEVEL*0.3+0.5)"
    let str6 = "(LEVEL*300+1200)"
    let str3 = "LEVEL*4+26"
    let str4 = "LEVEL*3+12"
    let str1 = "LEVEL*8+52"
    let str2 = "LEVEL*40+160"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
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

* **Цитадель**  (Дозор отрядов Цитадели)
* **Offensive**  (Дозор атакующих отрядов)

### Hero Bonus
* [Crag Hack](/heroes/Crag Hack/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Kilgor](/heroes/Kilgor/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Kendal](/heroes/Kendal/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Скорость атаки
* Magic resistance


## Awaking
### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Hobgoblin

 **Awaking Description:** Хобгоблины не страшатся битвы, ведь жестокость и жажда убийств у них в крови, и чем сильнее льется кровь врагов, тем яростнее они становятся.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Deploy Goblin and at least </span><span style="color: #1ca216;font-size:18px">3 Stronghold Units to kill </span><span style="color: #3c2a1e;font-size:18px">1,000</span><span style="color: #1ca216;font-size:18px"> Dwarfs</span> <span style="color: #3c2a1e;font-size:18px">in the Dwarven Treasury a single time.</span>

 2. <span style="color: #3c2a1e;font-size:18px">Consume </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> Action points in Guild Adventure.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ гоблинов на уровнях 17-2 и 17-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Победите на Ристалище </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> раза, используя гоблинов.</span>

## Awaken Skills

### 1st Skill (or 2nd): Менталитет бойца
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Боевой шторм&gt;</span><span style="color: #645252;font-size:18px">: шанс срабатывания удваивается</span>

### 2nd Skill (or 1st): Инерция
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Боевой шторм&gt; </span><span style="color: #645252;font-size:18px">: комбо-атака (&lt;Боевой шторм&gt; срабатывает 2 раза)</span>

### 3rd Skill (or 4th): Из ножен
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Казнь&gt;</span><span style="color: #645252;font-size:18px">: АТК гоблинов повышается на 150%, если у противника осталось меньше 30% ОЗ.</span>

### 4th Skill (or 3rd): Unarmed Counter
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Казнь&gt;</span><span style="color: #645252;font-size:20px">: урон гоблинов повышается на 30%, если у противника осталось меньше 30% ОЗ</span>

### 5th Skill (or 6th): Кровожадный мастер
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Жажда крови&gt;</span><span style="color: #645252;font-size:18px">: при критическом ударе восстановление ОЗ повышается на 5%</span>

### 6th Skill (or 5th): Кровавая кувалда
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Жажда крови&gt;</span><span style="color: #645252;font-size:18px">: при каждом критическом ударе скорость АТК повышается на 2%. Эффект длится 10 сек., суммируется до 10 раз</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 3.0

 **Rush:** 1

 **Speedattack:** 120

 **Attack Show:** 6.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 3.0

 **Score:** 455

 **HP Show:** 5

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 5

 **speedmove:** 100

 **posclass:** 1

 **talk1:** Пожалуйста, не убивайте бедных гоблинов! Они так слабы, с вашей мощью им не сравниться!

 **talk2:** Ах, свежее мясо!

 **talk3:** Жалкие создания. Думаете, меня заботит ваша судьба?

