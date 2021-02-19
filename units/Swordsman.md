---
title: "Мечник"
permalink: /units/Swordsman/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса В крестоносцы принимают только самых смелых, прославленных и опытных солдат. Об их военном мастерстве ходят легенды."
unitID: 104
last_modified_at: 2021-02-19
locale: ru
ref: "Мечник"
toc: true
---
## General information
 **Описание:** В крестоносцы принимают только самых смелых, прославленных и опытных солдат. Об их военном мастерстве ходят легенды.

 **Описание:** [Защита](/units/Unit Class Защита)

 **Описание Описание:** Оборонительные отряды могут дольше сопротивляться атаке и несут меньший урон.

 **Faction:** [Замок](/units/Fraction Замок)

 **Race:** Человек

 **Members:** [x4](/units/Unit Member x4)

 **Rank:** [SR](/units/Unit Rank SR)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 2)

 **Unit description:** Божественная защита снижает получаемый урон.

 **Short description:** Shield absorbs damage. Can self heal

 **Position :** В начале игры наносит огромный урон. Наносит двойной удар и может исцеляться.

 **Recommend:** Deals extra damage to any slowed enemies.

## Basic stats
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
  | **2x** <i class="fas fa-star"/> | 6.552 | 0.35 | 6.07 | 158.88 |
  | **3x** <i class="fas fa-star"/> | 7.644 | 0.36 | 6.83 | 185.36 |
  | **4x** <i class="fas fa-star"/> | 8.736 | 0.38 | 7.6 | 211.84 |
  | **5x** <i class="fas fa-star"/> | 9.828 | 0.4 | 8.36 | 238.32 |
  | **6x** <i class="fas fa-star"/> | 10.92 | 0.41 | 9.13 | 264.8 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Empire's Sword](/equipment/Empire's Sword/) | **АТК** | **DEF** | 
  | [Officer's Helmet](/equipment/Officer's Helmet/) | **ОЗ** | **DEF** | 
  | [Empire's Shield](/equipment/Empire's Shield/) | **АТК** | **DEF** | 
  | [Empire's Pauldrons](/equipment/Empire's Pauldrons/) | **ОЗ** | **DEF** | 

## Recommended Holy Emblems

* [Благословение](/Emblem/Queen's Blessing/) (Порядок)
* [Жетон Аксо](/Emblem/Aksoe Token/) (Нейтральный)
* [Алчность](/Emblem/Greed/) (Хаос)

## Combination Info

* [Высокий боевой дух](/combination/Высокий боевой дух/) 
* [Замедление](/combination/Замедление/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimate Skill: null
 **Описание:** 

### Regular Skill 1 : Воодушевление
 **Описание:** <span style="color: #645252;font-size:20px">The Swordsmen's unit's damage reduction is increased by </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">. The effect doubles under </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;High Morale&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Regular Skill 2 : Double Strike
 **Описание:** <span style="color: #645252;font-size:20px">При обычной атаке у мечников есть шанс </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> атаковать цель 2 раза. 2-я атака наносит </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> урона цели. В бою с </span><span style="color: black"><span style="color: #48b946;font-size:20px">замедленными</span><span style="color: black"><span style="color: #645252;font-size:20px"> целями шанс активировать &lt;Двойной удар&gt; возрастает до 100%.</span><span style="color: black">

### Regular Skill 3 : Salvation
 **Описание:** <span style="color: #645252;font-size:20px">The Swordsmen's normal attack has a high chance of restoring HP equal to </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> of Max HP.</span><span style="color: black">

### Faction Special Skill I : Siege Combat
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Замка мастерски умеют убивать драконов. В бою против отряда из одного существа их урон увеличивается на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Faction Special Skill II : Defense Resonance
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Замка мастерски владеют совместной обороной. За каждый выживший отряд они получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к ЗЩТ.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*1.5+2.5)"
    let str6 = "(LEVEL*0.5+2.5)"
    let str3 = "LEVEL*3+47"
    let str4 = "(LEVEL*0.4+3.6)"
    let str1 = "LEVEL*0.5+9.5"
    let str2 = "LEVEL*1+9"
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

* **Замок**  (Дозор отрядов Замка)
* **Defensive**  (Дозор оборонительных отрядов)

### Hero Bonus
* [Catherine](/heroes/Catherine/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Roland](/heroes/Roland/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/> 
* [Мефала](/heroes/Mephala/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Защита
* Magic resistance


## Awaking
### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Крестоносец

 **Awaking Description:** Герой, в тот миг, когда ты поднимаешь меч, ты становишься величайшей угрозой для врагов. Несокрушимая вера в твоем сердце - твое самое могучее оружие. Яркий символ щита в руке - несокрушимая сила.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Deploy Swordsman with at least </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> Castle units and complete Dragon Utopia </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> time at Ruthless level or higher. (Sweep does not count towards the mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Kill </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> monsters in Guild Adventure.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ крестоносцев на уровнях 15-2 и 15-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте мечников и не менее </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отрядов Замка, чтобы победить в </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> боях в кампании. (Набег не учитывается при выполнении этого задания).</span>

## Awaken Skills

### 1st Skill (or 2nd): Щит антимагии
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Божественная защита&gt;</span><span style="color: #645252;font-size:18px">: отряд получает сопротивление магическому урону</span>

### 2nd Skill (or 1st): Святая защита
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Божественная защита&gt;</span><span style="color: #645252;font-size:18px">: длительность эффекта увеличена на 10 сек.</span>

### 3rd Skill (or 4th): Вдохновение отважного
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лидерство&gt;</span><span style="color: #645252;font-size:18px">: иммунитет к состоянию низкого боевого духа. Эффект усиливается до 150% от эффекта предыдущего умения.</span>

### 4th Skill (or 3rd): Raise Me Up
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лидерство&gt;</span><span style="color: #645252;font-size:18px">: союзные отряды в большой области получают иммунитет к снижению боевого духа и получают высокий боевой дух, а их сопротивление урону повышается на 10%. Эффект длится 10 сек.</span>

### 5th Skill (or 6th): Свет спасения
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Спасение&gt;</span><span style="color: #645252;font-size:18px">: ОЗ восстанавливаются в размере 200% от базового значения умения</span>

### 6th Skill (or 5th): A Mighty Heart
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Спасение&gt;</span><span style="color: #645252;font-size:18px">: мечник получает иммунитет к немоте, оглушению и окаменению</span>

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

 **label1:** 2

 **speedmove:** 90

 **posclass:** 2

 **talk1:** That was just the warmup! When does the battle begin?

 **talk2:** Come to me, my brothers!

 **talk3:** Щитом и мечом я положу конец твоему безумию!

