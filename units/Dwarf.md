---
title: "Гном"
permalink: /units/Dwarf/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Гномы от рождения умеют защищаться, останавливая врагов своей стальной волей. Они вспыльчивы, и звон их молотов вселит ужас в сердце каждого, кто осмелится выступить против них."
unitID: 202
last_modified_at: 2021-02-22
locale: ru
ref: "Гном"
toc: true
---
## General information
 **Описание:** Гномы от рождения умеют защищаться, останавливая врагов своей стальной волей. Они вспыльчивы, и звон их молотов вселит ужас в сердце каждого, кто осмелится выступить против них.

 **Класс:** [Защита](/units/Unit Class Defense/)

 **Класс Описание:** Оборонительные отряды могут дольше сопротивляться атаке и несут меньший урон.

 **Фракция: ** [Rampart](/units/Faction Rampart/)

 **Race:** Лес

 **Members:** [x9](/units/Unit Member x9/)

 **Rank:** [SR](/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 2/)

 **Unit description:** Гномий вой: увеличивает максимум здоровья отряда в начале боя.

 **Short description:** Значительно повышает здоровье. Волшебный щит.

 **Position :** Увеличивает здоровье всего отряда и уменьшает урон от магии, получаемый вашими отрядами в непосредственной близости.

 **Recommend:** Высокий максимальный уровень здоровья позволяет отрядам лучше сопротивляться атакам.

## Базовые параметры
 **Base HP: 1324.0**

 **Base ATK: 54.6**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 27.3 | 13.25 | 993.0 |
  | Синий | 54.6 | 26.5 | 1986.0 |
  | Blue +1 | 81.9 | 39.75 | 2979.0 |
  | Синий +2 | 114.66 | 55.65 | 4170.6 |
  | Фиолетовый | 147.42 | 71.55 | 5362.2 |
  | Фиолетовый +1 | 180.18 | 87.45 | 6553.8 |
  | Фиолетовый +2 | 218.4 | 106.0 | 7944.0 |
  | Фиолетовый +3 | 256.62 | 124.55 | 9334.2 |
  | Оранжевый | 294.84 | 143.1 | 10724.4 |
  | Оранжевый +1 | 338.52 | 164.3 | 12313.2 |
  | Оранжевый +2 | 382.2 | 185.5 | 13902.0 |
  | Orange +3 | 425.88 | 206.7 | 15490.8 |
  | Оранжевый +4 | 469.56 | 227.9 | 17079.6 |
  | Orange +5 | 535.08 | 259.7 | 19462.8 |
  | Red | 622.44 | 302.1 | 22640.4 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 6.552 | 0.34 | 6.07 | 158.88 |
  | **3x** <i class="fas fa-star"/> | 7.644 | 0.35 | 6.83 | 185.36 |
  | **4x** <i class="fas fa-star"/> | 8.736 | 0.37 | 7.6 | 211.84 |
  | **5x** <i class="fas fa-star"/> | 9.828 | 0.38 | 8.36 | 238.32 |
  | **6x** <i class="fas fa-star"/> | 10.92 | 0.4 | 9.13 | 264.8 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Мощный молот](/equipment/Мощный молот/) | **АТК** | **DEF** | 
  | [Horned Helmet](/equipment/Horned Helmet/) | **ОЗ** | **DEF** | 
  | [Рукавицы печного огня](/equipment/Рукавицы печного огня/) | **АТК** | **DEF** | 
  | [Наплечники печного огня](/equipment/Наплечники печного огня/) | **ОЗ** | **DEF** | 

## Рекомендуемые эмблемы святости

* [Тайна Неувядающего](/Emblem/Everlasting Secret/) (Порядок)
* [Ангел-хранитель](/Emblem/Guardian Angel/) (Добро)
* [Гнев](/Emblem/Anger/) (Хаос)

## Информация о комбинации

* [Оглушение](/combination/Оглушение/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Совершенное умение: Гномий вой
 **Описание:** <span style="color: #645252;font-size:20px">В начале боя гномы повышают ОЗ у всех ваших отрядов в широком радиусе на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> и получает </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к урону отряда и </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к ЗЩТ. Эффект длится в течение всего боя. </span><span style="color: black">

### Обычное умение 1 : Smite
 **Описание:** <span style="color: #645252;font-size:20px">При обычной атаке у гномов есть шанс нанести целям </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> урона и вызвать </span><span style="color: black"><span style="color: #48b946;font-size:20px">оглушение</span><span style="color: black"><span style="color: #645252;font-size:20px"> на 2 сек.</span><span style="color: black">

### Обычное умение 2 : Крик ярости
 **Описание:** <span style="color: #645252;font-size:20px">«Гномий вой» дает </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к ОЗ, </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к скорости АТК и </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к урону отряда. </span><span style="color: black">

### Обычное умение 3 : Сопротивление магии
 **Описание:** <span style="color: #645252;font-size:20px">Dwarves offer protection cover, increasing magic resistance by 30% for all friendly units in it for </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">s.</span><span style="color: black">

### Эксклюзивное умение фракции I : Calm Proliferation
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Бастиона мастерски ведут войну на поле боя. Длительность оглушения и окаменения, от которых они страдают, сокращается на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Эксклюзивное умение фракции II : Отметка ненависти
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Бастиона мастерски владеют тактическим преследованием, повышая КРИТ. УРН на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str10"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> в бою против отрядов, подвергшихся замедлению и кровотечению. Если цель страдает от 2 вышеупомянутых состояний, эффект удваивается.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "LEVEL*0.5+3"
    let str8 = "LEVEL*0.8+9.2"
    let str5 = "LEVEL*0.4+3.6"
    let str6 = "LEVEL*1+6"
    let str3 = "LEVEL*0.5+2.5"
    let str4 = "LEVEL*15+135"
    let str1 = "LEVEL*0.8+15.2"
    let str2 = "LEVEL*0.5+2.5"
    let str10 = "(LEVEL*0.9+2.4)"
    let str9 = "(LEVEL*1.5+7.5)"
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
     res = eval(str10); document.getElementById('str10').textContent = res;
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
## Значимость
### Связь дозора

* **Бастион**  (Дозор отрядов Бастиона)
* **Defensive**  (Дозор оборонительных отрядов)

### Бонус героя
* [Мефала](/heroes/Mephala/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Джем](/heroes/Gem/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Защита
* Magic resistance


## Awaking
### Awaking Details
 **Is it possible right now?** NO

 **Awaking Name:** null

 **Awaking Описание:** null

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

 **defshow:** 7.0

 **Rush:** 1

 **Speedattack:** 100

 **Attack Show:** 4.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 4.0

 **Defense Show:** 7.0

 **Score:** 761

 **HP Show:** 8

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 3

 **speedmove:** 90

 **posclass:** 2

 **talk1:** Горы стояли задолго до вашего рождения и будут стоять после вашей смерти.

 **talk2:** Не стоит недооценивать меня из-за моих размеров. У меня для вас плохие новости!

 **talk3:** Думаю, хороший удар по черепушке - то, что вам нужно.

