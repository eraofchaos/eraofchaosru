---
title: "Behemoth"
permalink: /units/Behemoth/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Behemoths are one of the few primal creatures. Their origins date back to the time before dragons. Their huge bodies ignore their enemy's attacks."
unitID: 407
last_modified_at: 2021-02-19
locale: ru
ref: "Behemoth"
toc: true
---
## General information
 **Описание:** Behemoths are one of the few primal creatures. Their origins date back to the time before dragons. Their huge bodies ignore their enemy's attacks.

 **Описание:** [Защита](/units/Unit Class Защита)

 **Описание Описание:** Оборонительные отряды могут дольше сопротивляться атаке и несут меньший урон.

 **Faction:** [Цитадель](/units/Fraction Цитадель)

 **Race:** Единорог

 **Members:** [x1](/units/Unit Member x1)

 **Rank:** [SSR](/units/Unit Rank SSR)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 3)

 **Unit description:** Дикий рев: резко ослабляет атаку противника, вызывая оглушение.

 **Short description:** Высасывает жизнь из убитых врагов.

 **Position :** Лучший оборонительный отряд. Лучший вариант для обороны уязвимых к урону отрядов и контроля на поле боя.

 **Recommend:** Существа с низким здоровьем и высокой атакой. Они будут чрезвычайно эффективны, если не забывать их вовремя лечить.

## Basic stats
 **Base HP: 10182.0**

 **Base ATK: 407.3**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 203.65 | 15.0 | 7636.5 |
  | Синий | 407.3 | 30.0 | 15273.0 |
  | Blue +1 | 610.95 | 45.0 | 22909.5 |
  | Синий +2 | 855.33 | 63.0 | 32073.3 |
  | Фиолетовый | 1099.71 | 81.0 | 41237.1 |
  | Фиолетовый +1 | 1344.09 | 99.0 | 50400.9 |
  | Фиолетовый +2 | 1629.2 | 120.0 | 61092.0 |
  | Фиолетовый +3 | 1914.31 | 141.0 | 71783.1 |
  | Оранжевый | 2199.42 | 162.0 | 82474.2 |
  | Оранжевый +1 | 2525.26 | 186.0 | 94692.6 |
  | Оранжевый +2 | 2851.1 | 210.0 | 106911.0 |
  | Orange +3 | 3176.94 | 234.0 | 119129.4 |
  | Оранжевый +4 | 3502.78 | 258.0 | 131347.8 |
  | Orange +5 | 3991.54 | 294.0 | 149675.4 |
  | Red | 4643.22 | 342.0 | 174112.2 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 57.022 | 0.35 | 7.6 | 1425.48 |
  | **4x** <i class="fas fa-star"/> | 65.168 | 0.37 | 8.4 | 1629.12 |
  | **5x** <i class="fas fa-star"/> | 73.314 | 0.38 | 9.2 | 1832.76 |
  | **6x** <i class="fas fa-star"/> | 81.46 | 0.4 | 10.0 | 2036.4 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Свирепые когти](/equipment/Свирепые когти/) | **АТК** | **DEF** | 
  | [Ironclad Skin](/equipment/Ironclad Skin/) | **ОЗ** | **DEF** | 
  | [Ferocious Fangs](/equipment/Ferocious Fangs/) | **АТК** | **DEF** | 
  | [Толстая меховая шкура](/equipment/Толстая меховая шкура/) | **ОЗ** | **DEF** | 

## Recommended Holy Emblems

* [Благословение](/Emblem/Queen's Blessing/) (Порядок)
* [Снаряжение времени](/Emblem/Gear of Time/) (Добро)
* [Похоть](/Emblem/Lust/) (Хаос)

## Combination Info

* [Кровотечение](/combination/Кровотечение/) 
* [Оглушение](/combination/Оглушение/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimate Skill: Wild Roar
 **Описание:** <span style="color: #645252;font-size:20px">Behemoth deals damage equal to </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> of its Attack to surrounding enemy units within a large range, inflicting </span><span style="color: black"><span style="color: #48b946;font-size:20px"> &lt;stun&gt; </span><span style="color: black"><span style="color: #645252;font-size:20px"> on them for 6s, and reducing their attack by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">and damage reduction by</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> for 20s.</span><span style="color: black">

### Regular Skill 1 : Разрывание когтями
 **Описание:** <span style="color: #645252;font-size:20px">Чудища наносят </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ед. урона своей цели каждые 20 сек. и вызывают у нее </span><span style="color: black"><span style="color: #48b946;font-size:20px">кровотечение</span><span style="color: black"><span style="color: #645252;font-size:20px"> на 6 сек.</span><span style="color: black">

### Regular Skill 2 : Rampage
 **Описание:** <span style="color: #645252;font-size:20px">Чудища получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">% к сопротивлению урону. Эффект удваивается при ОЗ менее 35% и продолжает действовать при восстановлении ОЗ.</span><span style="color: black">

### Regular Skill 3 : Бешенство
 **Описание:** <span style="color: #645252;font-size:20px">За гибель каждого вражеского отряда чудища восстанавливают ОЗ в размере </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от максимума ОЗ и получают +10% к урону отряда на 10 сек. </span><span style="color: black">

### Faction Special Skill I : Фанатик сражений
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Цитадели умеют сражаться в свирепых длительных боях. Их скорость атаки будет увеличена на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> за каждые 15% потерянных ОЗ.</span><span style="color: black">

### Faction Special Skill II : Рост живучести
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Цитадели хорошо разбираются в лечении на поле боя, восстанавливая </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ОЗ каждые 3 сек. и получив </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к высасыванию жизни.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*0.3+0.5)"
    let str8 = "(LEVEL*300+1200)"
    let str5 = "LEVEL*1+9"
    let str6 = "LEVEL*0.5+4.5"
    let str3 = "LEVEL*0.5+2.5"
    let str4 = "(LEVEL*2+38)*0.01*ATK"
    let str1 = "LEVEL*5+35"
    let str2 = "LEVEL*3+17"
    let str9 = "(LEVEL*0.3+1)"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
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
* **Defensive**  (Дозор оборонительных отрядов)

### Hero Bonus
* [Мефала](/heroes/Mephala/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Crag Hack](/heroes/Crag Hack/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Kilgor](/heroes/Kilgor/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Защита
* unit DMG Reduction


## Awaking
### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Ancient Behemoth

 **Awaking Description:** It's the leader among many wild creatures, and there is nothing as terrifying as it that walks the earth. Great creatures mean nothing to him. Any strong creatures are decadent in its eyes. The mountains will also give their offerings, and it's the king in the cruel wilderness.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Используйте чудищ и хотя бы </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> отрядов Цитадели, чтобы </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> раз добиться уровня «Чемпион» или выше в Утопии драконов. (Набег не учитывается при выполнении этого задания).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Убейте </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> монстров в Походе гильдии.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ древних чудищ на уровнях 17-2 и 17-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Победите в Дуэли заступников </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> раз, используя чудищ.</span>

## Awaken Skills

### 1st Skill (or 2nd): Древний рев
 **Описание:**  <span style="color: #48b946;font-size:18px">&lt;Дикий рев&gt;</span><span style="color: #645252;font-size:18px">: после применения &lt;Дикого рева&gt; сопротивление магии и урону всех союзных отрядов Цитадели увеличивается на 30%. Эффект длится 10 сек.</span>

### 2nd Skill (or 1st): Жестокий рев
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Дикий рев&gt;</span><span style="color: #645252;font-size:18px">: оглушение распространяется на все вражеские отряды ближнего боя</span>

### 3rd Skill (or 4th): Гнев дебрей
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Буйство&gt;</span><span style="color: #645252;font-size:18px">: эффект усиливается на 50%. При срабатывании буйства урон всех союзных отрядов Цитадели увеличивается на 10% на 20 сек.</span>

### 4th Skill (or 3rd): Буйство жажды крови
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Буйство&gt;</span><span style="color: #645252;font-size:18px">: эффект усиливается на 50%. При срабатывании буйства сопротивление урону всех союзных отрядов Цитадели усиливается на 10% на 20 сек.</span>

### 5th Skill (or 6th): Древняя ярость
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Бешенство&gt;</span><span style="color: #645252;font-size:18px">: эффект исцеления повышается на 50%. Приобретается иммунитет к болезням</span>

### 6th Skill (or 5th): Unyielding Anger
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Бешенство&gt;</span><span style="color: #645252;font-size:18px">: сопротивление отряда урону увеличивается до конца боя. Суммируется до 5 раз</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 9.0

 **Rush:** 1

 **Speedattack:** 100

 **Attack Show:** 5.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 5.0

 **Defense Show:** 9.0

 **Score:** 1574

 **HP Show:** 9

 **disrdcvol:** 70

 **Dead Type:** 1

 **s:** 4

 **label1:** 5

 **speedmove:** 90

 **posclass:** 2

 **talk1:** Однажды я брошу вызов самим драконам!

 **talk2:** Я слежу за этой землей и защищаю ее.

 **talk3:** Когда я впадаю в ярость, я сам себя боюсь.

