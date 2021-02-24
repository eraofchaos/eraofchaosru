---
title: "Демон"
permalink: /units/Demon/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Демона легко узнать по острым рогам на голове. Этим грозным оружием он с легкостью пронзает доспехи и раздирает плоть своих врагов."
unitID: 504
last_modified_at: 2021-02-24
locale: ru
ref: "Демон"
toc: true
---
## General information
 **Описание:** Демона легко узнать по острым рогам на голове. Этим грозным оружием он с легкостью пронзает доспехи и раздирает плоть своих врагов.

 **Класс:** [Защита](/units/Unit Class Defense/)

 **Класс Описание:** Оборонительные отряды могут дольше сопротивляться атаке и несут меньший урон.

 **Фракция: ** [Инферно](/units/Faction Inferno/)

 **Race:** Одержимый

 **Members:** [x4](/units/Unit Member x4/)

 **Rank:** [SR](/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 2/)

 **Unit description:** Ошпаривающий удар: наносит огромный урон вражеским войскам.

 **Short description:** Щит, усиливающий уклонение. Восстанавливает здоровье.

 **Position :** Щит с высоким значением уклонения. Восстанавливает здоровье после успешного уклонения. Может получить усиление от порождения зла.

 **Recommend:** Существа с низким здоровьем и высокой атакой. Они будут чрезвычайно эффективны, если не забывать их вовремя лечить.

## Базовые параметры
 **Base HP: 2489.0**

 **Base ATK: 114.4**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Зеленый | 57.2 | 15.0 | 1866.75 |
  | Синий | 114.4 | 30.0 | 3733.5 |
  | Синий +1 | 171.6 | 45.0 | 5600.25 |
  | Синий +2 | 240.24 | 63.0 | 7840.35 |
  | Фиолетовый | 308.88 | 81.0 | 10080.45 |
  | Фиолетовый +1 | 377.52 | 99.0 | 12320.55 |
  | Фиолетовый +2 | 457.6 | 120.0 | 14934.0 |
  | Фиолетовый +3 | 537.68 | 141.0 | 17547.45 |
  | Оранжевый | 617.76 | 162.0 | 20160.9 |
  | Оранжевый +1 | 709.28 | 186.0 | 23147.7 |
  | Оранжевый +2 | 800.8 | 210.0 | 26134.5 |
  | Оранжевый +3 | 892.32 | 234.0 | 29121.3 |
  | Оранжевый +4 | 983.84 | 258.0 | 32108.1 |
  | Оранжевый +5 | 1121.12 | 294.0 | 36588.3 |
  | Красный | 1304.16 | 342.0 | 42561.9 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 13.728 | 0.34 | 6.8 | 298.68 |
  | **3x** <i class="fas fa-star"/> | 16.016 | 0.35 | 7.6 | 348.46 |
  | **4x** <i class="fas fa-star"/> | 18.304 | 0.37 | 8.4 | 398.24 |
  | **5x** <i class="fas fa-star"/> | 20.592 | 0.38 | 9.2 | 448.02 |
  | **6x** <i class="fas fa-star"/> | 22.88 | 0.4 | 10.0 | 497.8 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Рожок опаления](/equipment/Рожок опаления/) | **АТК** | **ЗЩТ** | 
  | [Стальное ожерелье](/equipment/Стальное ожерелье/) | **ОЗ** | **ЗЩТ** | 
  | [Ошпаривающие когти](/equipment/Ошпаривающие когти/) | **АТК** | **ЗЩТ** | 
  | [Зубчатые браслеты](/equipment/Зубчатые браслеты/) | **ОЗ** | **ЗЩТ** | 

## Рекомендуемые эмблемы святости

* [Алчность](/Emblem/Greed/) (Хаос)
* [Похоть](/Emblem/Lust/) (Хаос)
* [Зловещий знак](/Emblem/Ominous Sign/) (Злой)

## Информация о комбинации

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Совершенное умение: Ошпаривающий удар
 **Описание:** <span style="color: #645252;font-size:20px">Демоны случайным образом наносят </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ед. урона 1 вражескому отряду в широком радиусе и получают +300 к уклонению на 12 сек.</span><span style="color: black">

### Обычное умение 1 : Ожоги
 **Описание:** <span style="color: #645252;font-size:20px">Демоны восстанавливают <span style="color: #48b946;font-size:20px">+<span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от максимума ОЗ за каждое уклонение.</span><span style="color: black">

### Обычное умение 2 : Слуга Инферно
 **Описание:** <span style="color: #645252;font-size:20px">Демоны получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к ОЗ. Исцеление повышается на 30%.</span><span style="color: black">

### Обычное умение 3 : Отряд Огня
 **Описание:** <span style="color: #645252;font-size:20px">Демоны получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> к уклонению. Также их уклонение повышается на 40 за каждый участвующий в бою отряд Инферно.</span><span style="color: black">

### Эксклюзивное умение фракции I : Обжигающий удар
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Инферно мастерски контролируют огонь, повышая критический удар на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> и КРИТ. УРН на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> в бою против горящих отрядов.</span><span style="color: black">

### Эксклюзивное умение фракции II : Резонанс антимагии
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Инферно мастерски владеют групповой обороной. За каждый выживший отряд они получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к сопротивлению магии.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*0.5+2.5)"
    let str5 = "(LEVEL*10+50)"
    let str6 = "(LEVEL*0.5+7.5)"
    let str3 = "(LEVEL*3+12)"
    let str4 = "LEVEL*20+80"
    let str1 = "(LEVEL*20+230)*0.01*ATK"
    let str2 = "LEVEL*0.5+4.5"
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

* **Инферно**  (Дозор отрядов Инферно)
* **Защита**  (Дозор оборонительных отрядов)

### Бонус героя
* [Мефала](/heroes/Mephala/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Ксерон](/heroes/Xeron/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Защита
* Уклонение отряда


## Awaking
### Awaking Details
 **Is it possible right now?** NO

 **Awaking Name:** 

 **Awaking Описание:** null

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Используйте копейщиков и не менее </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отрядов Замка, чтобы убить </span><span style="color: #1ca216;font-size:18px">1000</span><span style="color: #3c2a1e;font-size:18px"> гномов в Сокровищнице гномов за одну атаку. (Набег не учитывается при выполнении этого задания).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Убейте </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> монстров в Походе гильдии. </span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ алебардщиков на уровнях 14-2 и 14-4 Подземелья.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте копейщиков и не менее </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отрядов Замка, чтобы победить в </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> боях Дуэли заступников.</span>

## Awaken Skills

### 1st Skill (or 2nd): Лес копий: зачистка
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лес копий&gt;</span><span style="color: #645252;font-size:18px">: целью становятся более крупные отряды врага.</span>

### 2nd Skill (or 1st): Внезапный лес копий
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лес копий&gt;</span><span style="color: #645252;font-size:18px">: урон повышается до 150%, оглушение продлевается до 4,5 сек.</span>

### 3rd Skill (or 4th): Плотный строй
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лидерство&gt;</span><span style="color: #645252;font-size:18px">: при высоком боевом духе сопротивление отряда урону в бою повышается на 30%. Эффект длится 10 сек.</span>

### 4th Skill (or 3rd): Лукавый строй
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лидерство&gt;</span><span style="color: #645252;font-size:18px">: при высоком боевом духе сопротивление магии в бою повышается на 30% на 10 сек.</span>

### 5th Skill (or 6th): Стратегия проникновения
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Убийство драконов&gt;</span><span style="color: #645252;font-size:18px">: в бою с отрядом из 1 или 4 существ цель получает сдерживание. Сдерживание: снижает критический удар цели на 300</span>

### 6th Skill (or 5th): Атака усталостью
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Убийство драконов&gt;</span><span style="color: #645252;font-size:18px">: в бою с отрядом из 1 или 4 существ уклонение цели понижается на 300</span>

## Technical info
 **runart:** 1

 **summon:** 2

 **defshow:** 7.0

 **Rush:** 1

 **Speedattack:** 100

 **Attack Show:** 3.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 4.0

 **Defense Show:** 7.0

 **Score:** 728

 **HP Show:** 8

 **disrdcvol:** 40

 **Dead Type:** 2

 **s:** 51

 **label1:** 4

 **speedmove:** 90

 **posclass:** 2

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

