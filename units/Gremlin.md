---
title: "Gremlin"
permalink: /units/Gremlin/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Gremlins have signed contracts of servitude with the Tower. They prefer to attack from afar with their enchanted chain balls."
unitID: 601
last_modified_at: 2021-02-22
locale: ru
ref: "Gremlin"
toc: true
---
## General information
 **Описание:** Gremlins have signed contracts of servitude with the Tower. They prefer to attack from afar with their enchanted chain balls.

 **Класс:** [Стрелковый](/units/Unit Class Ranged/)

 **Класс Описание:** Чем дальше стрелковый отряд от цели, тем больше наносимый ими урон.

 **Фракция: ** [Башня](/units/Faction Tower/)

 **Race:** Человек

 **Members:** [x9](/units/Unit Member x9/)

 **Rank:** [R](/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/units/Star 1/)

 **Unit description:** Магический железный шар железный шар: значительно усиливает атаку и скорость атаки.

 **Short description:** Усиленная магия и урон.

 **Position :** Вызывает оглушение на расстоянии и наносит взрывной урон. Заклинания героев приводят к срабатыванию усиления атаки.

 **Recommend:** Воин, маг и священник хорошо работают в команде.

## Базовые параметры
 **Base HP: 645.0**

 **Base ATK: 84.4**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Green | 40.5 | 7.5 | 350.7 |
  | Синий | 81.0 | 15.0 | 701.4 |
  | Blue +1 | 121.5 | 22.5 | 1052.1 |
  | Синий +2 | 170.1 | 31.5 | 1472.94 |
  | Фиолетовый | 218.7 | 40.5 | 1893.78 |
  | Фиолетовый +1 | 267.3 | 49.5 | 2314.62 |
  | Фиолетовый +2 | 324.0 | 60.0 | 2805.6 |
  | Фиолетовый +3 | 380.7 | 70.5 | 3296.58 |
  | Оранжевый | 437.4 | 81.0 | 3787.56 |
  | Оранжевый +1 | 502.2 | 93.0 | 4348.68 |
  | Оранжевый +2 | 567.0 | 105.0 | 4909.8 |
  | Orange +3 | 631.8 | 117.0 | 5470.92 |
  | Оранжевый +4 | 696.6 | 129.0 | 6032.04 |
  | Orange +5 | 793.8 | 147.0 | 6873.72 |
  | Red | 923.4 | 171.0 | 7995.96 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 8.1 | 0.54 | 3.0 | 46.76 |
  | **2x** <i class="fas fa-star"/> | 9.72 | 0.57 | 3.65 | 56.112 |
  | **3x** <i class="fas fa-star"/> | 11.34 | 0.59 | 4.3 | 65.464 |
  | **4x** <i class="fas fa-star"/> | 12.96 | 0.62 | 4.95 | 74.816 |
  | **5x** <i class="fas fa-star"/> | 14.58 | 0.65 | 5.6 | 84.168 |
  | **6x** <i class="fas fa-star"/> | 16.2 | 0.68 | 6.25 | 93.52 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Цеп молнии](/equipment/Цеп молнии/) | **АТК** | **DEF** | 
  | [Зачарованный капюшон](/equipment/Зачарованный капюшон/) | **ОЗ** | **DEF** | 
  | [Зачарованные перчатки](/equipment/Зачарованные перчатки/) | **АТК** | **DEF** | 
  | [Ветрозащитный плащ](/equipment/Ветрозащитный плащ/) | **ОЗ** | **DEF** | 

## Рекомендуемые эмблемы святости

* [Тайна Неувядающего](/Emblem/Everlasting Secret/) (Порядок)
* [Суд отцов](/Emblem/The Judgment of Fathers/) (Нейтральный)
* [Гнев](/Emblem/Anger/) (Хаос)

## Информация о комбинации

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Совершенное умение: Магический железный шар
 **Описание:** <span style="color: #645252;font-size:20px">Гремлины получают +100% к скорости атаки на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> сек.</span><span style="color: black">

### Обычное умение 1 : Убийство драконов
 **Описание:** <span style="color: #645252;font-size:20px">When facing 1-man or 4-man units, Gremlin's normal attack has a chance to </span><span style="color: black"><span style="color: #48b946;font-size:20px">\"stun\"</span><span style="color: black"><span style="color: #645252;font-size:20px"> the target for </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">s.</span><span style="color: black">

### Обычное умение 2 : Magic Will
 **Описание:** <span style="color: #645252;font-size:20px">Гремлины получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к ОЗ и </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к сопротивлению магии.</span><span style="color: black">

### Обычное умение 3 : Магическое пробуждение
 **Описание:** <span style="color: #645252;font-size:20px">When a Gremlin unit is enhanced by a friendly hero's support spell, its ATK is increased by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">. Effective throughout the entire battle, up to 10 stacks.</span><span style="color: black">

### Эксклюзивное умение фракции I : Трезвый ум
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Башни мастерски противостоят немоте. Длительность немоты сокращается на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black">

### Эксклюзивное умение фракции II : Энергетический динамит
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Башни мастерски владеют преобразованием энергии, повышая свой КРИТ. УРН на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1.5+4)"
    let str5 = "LEVEL*2+8"
    let str6 = "(LEVEL*2+10)"
    let str3 = "LEVEL*2+8"
    let str4 = "LEVEL*1+4"
    let str1 = "LEVEL*0.3+3.7"
    let str2 = "LEVEL*0.2+0.8"
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
## Значимость
### Связь дозора

* **Tower**  (Дозор отрядов Башни)
* **Стрелок**  (Дозор стрелковых отрядов)

### Бонус героя
* [Джелу](/heroes/Gelu/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Astral](/heroes/Astral/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Скорость атаки
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

 **defshow:** 5.0

 **fly:** dayaojing

 **flyspeed:** 300

 **atkfly:** 5

 **Rush:** 3

 **Speedattack:** 120

 **Attack Show:** 6.0

 **Attack Area:** 350

 **Attack Range:** 300

 **Attack Speed Show:** 5.0

 **Defense Show:** 5.0

 **Score:** 455

 **HP Show:** 4

 **disrdcvol:** -2147483648

 **Dead Type:** 1

 **s:** 1

 **label1:** 6

 **speedmove:** 90

 **posclass:** 4

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

