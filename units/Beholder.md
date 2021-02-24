---
title: "Бехолдер"
permalink: /units/Beholder/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Эти многоглазые монстры весьма умны. Всех живых существ они считают своими слугами."
unitID: 703
last_modified_at: 2021-02-24
locale: ru
ref: "Бехолдер"
toc: true
---
## General information
 **Описание:** Эти многоглазые монстры весьма умны. Всех живых существ они считают своими слугами.

 **Класс:** [Заклинатель](/units/Unit Class Caster/)

 **Класс Описание:** Благодаря своим тайным знаниям, отряды заклинателей обладают повышенным сопротивлением магии.

 **Фракция: ** [Подземелье](/units/Faction Dungeon/)

 **Race:** Злой дух

 **Members:** [x9](/units/Unit Member x9/)

 **Rank:** [SR](/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 3/)

 **Unit description:** Управление разумом: обездвиживает врага и заставляет его постепенно терять здоровье

 **Short description:** Сильный взрыв в начале. Управление разумом.

 **Position :** Прекрасный вариант для начала боя. В начале боя ослабляет врага, приближая победу.

 **Recommend:** Существа с низким здоровьем и высокой атакой. Они будут чрезвычайно эффективны, если не забывать их вовремя лечить.

## Базовые параметры
 **Base HP: 744.0**

 **Base ATK: 115.8**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Зеленый | 57.9 | 3.75 | 558.0 |
  | Синий | 115.8 | 7.5 | 1116.0 |
  | Синий +1 | 173.7 | 11.25 | 1674.0 |
  | Синий +2 | 243.18 | 15.75 | 2343.6 |
  | Фиолетовый | 312.66 | 20.25 | 3013.2 |
  | Фиолетовый +1 | 382.14 | 24.75 | 3682.8 |
  | Фиолетовый +2 | 463.2 | 30.0 | 4464.0 |
  | Фиолетовый +3 | 544.26 | 35.25 | 5245.2 |
  | Оранжевый | 625.32 | 40.5 | 6026.4 |
  | Оранжевый +1 | 717.96 | 46.5 | 6919.2 |
  | Оранжевый +2 | 810.6 | 52.5 | 7812.0 |
  | Оранжевый +3 | 903.24 | 58.5 | 8704.8 |
  | Оранжевый +4 | 995.88 | 64.5 | 9597.6 |
  | Оранжевый +5 | 1134.84 | 73.5 | 10936.8 |
  | Красный | 1320.12 | 85.5 | 12722.4 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 16.212 | 0.45 | 2.65 | 104.16 |
  | **4x** <i class="fas fa-star"/> | 18.528 | 0.47 | 3.23 | 119.04 |
  | **5x** <i class="fas fa-star"/> | 20.844 | 0.49 | 3.8 | 133.92 |
  | **6x** <i class="fas fa-star"/> | 23.16 | 0.51 | 4.38 | 148.8 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Глаз богохульства](/equipment/Глаз богохульства/) | **АТК** | **ЗЩТ** | 
  | [Ученик смерти](/equipment/Ученик смерти/) | **ОЗ** | **ЗЩТ** | 
  | [Злой бивень](/equipment/Злой бивень/) | **АТК** | **ЗЩТ** | 
  | [Щупальца из Бездны](/equipment/Щупальца из Бездны/) | **ОЗ** | **ЗЩТ** | 

## Рекомендуемые эмблемы святости

* [Древний огонь](/Emblem/Ancient Fire/) (Порядок)
* [Тайна Неувядающего](/Emblem/Everlasting Secret/) (Порядок)
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
### Совершенное умение: Управление разумом
 **Описание:** <span style="color: #645252;font-size:20px">Бехолдеры контролируют 1 случайный вражеский отряд. Цель получает урон в размере </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от максимума ОЗ в секунду в течение 8 сек. Находясь под контролем, выбранный целью отряд не может атаковать, двигаться и использовать умения.</span><span style="color: black">

### Обычное умение 1 : Пробивание заклинания
 **Описание:** <span style="color: #645252;font-size:20px">Когда бехолдеры появляются на поле боя, они открывают 4 глаза смерти. Каждый глаз дает </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к урону отряда. С каждой убитой целью закрывается 1 глаз. Могут быть закрыты максимум 3 глаза.</span><span style="color: black">

### Обычное умение 2 : Бессилие
 **Описание:** <span style="color: #645252;font-size:20px">Когда бехолдеры на поле боя, исходная мана вражеских героев снижается на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">. Когда погибает вражеский отряд, мана вражеских героев снижается еще на 10.</span><span style="color: black">

### Обычное умение 3 : Сбор энергии
 **Описание:** <span style="color: #645252;font-size:20px">В начале боя бехолдеры повышают ОЗ у всех ваших отрядов в широком радиусе на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> в течение всего боя.</span><span style="color: black">

### Эксклюзивное умение фракции : Темный конфликт
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Подземелья мастерски используют рельеф, повышая урон отряда на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> в бою против отрядов не из Подземелья.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*1+5)"
    let str3 = "LEVEL*1.5+8.5"
    let str4 = "LEVEL*2+8"
    let str1 = "LEVEL*0.2+0.8"
    let str2 = "LEVEL*1+4"
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
## Значимость
### Связь дозора

* **Подземелье**  (Дозор отрядов Подземелья)
* **Заклинатель**  (Дозор отрядов заклинателей)

### Бонус героя
* [Дракон](/heroes/Dracon/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Мутара](/heroes/Mutare/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Дракон Мутара](/heroes/Dragon Mutare/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Урон отряда
* Сопротивление магии


## Awaking
### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Злобоглаз

 **Awaking Описание:** Взгляд этого злого создание неизвестного происхождения излучает непередаваемый страх. Око смерти видит хрупкость врагов и поглощает невидимую силу.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Используйте бехолдеров и хотя бы </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отряда Подземелья, чтобы добиться уровня «Чемпион» или выше в Утопии драконов один раз. (Набег не учитывается при выполнении этого задания).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> элемента снаряжения в Походе гильдии. </span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ злобоглазов на уровнях 17-2 и 17-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте бехолдеров и хотя бы </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отряда Подземелья, чтобы победить в 1 бою Дуэли заступников. (Набег не учитывается при выполнении этого задания).</span>

## Awaken Skills

### 1st Skill (or 2nd): Удар маны
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Лидерство&gt;</span><span style="color: #645252;font-size:18px">: бехолдер открывает еще 4 глаза. При убийстве 1 цели 2 глаза закрываются. Максимум закрывается 6 глаз</span>

### 2nd Skill (or 1st): В бездну
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Пробивание заклинания&gt;</span><span style="color: #645252;font-size:18px">: каждое око смерти дает по 3% к урону и по 3% к сопротивлению урону для союзных отрядов Подземелья. Для бехолдеров эффект удваивается</span>

### 3rd Skill (or 4th): Коллапс чар
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Бессилие&gt;</span><span style="color: #645252;font-size:18px">: восстановление маны вражеских героев уменьшается на 1 при гибели каждого вражеского отряда. Эффект может сработать 2 раза</span>

### 4th Skill (or 3rd): Чародейский грабеж
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Бессилие&gt;</span><span style="color: #645252;font-size:18px">: восстановление маны вражеских героев уменьшается на 10 при гибели каждого вражеского отряда.</span>

### 5th Skill (or 6th): Щит разрушителя магии
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Сбор энергии&gt;</span><span style="color: #645252;font-size:18px">: эффект умения усиливается до 150% от эффекта предыдущего умения. Сопротивление отряда урону повышается на 10%. Сопротивление магии и сопротивление урону для бехолдера повышаются на 10%, если вражеский герой применяет заклинание</span>

### 6th Skill (or 5th): Резонанс экзорцизма
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Сбор энергии&gt;</span><span style="color: #645252;font-size:18px">: эффект умения усиливается до 150% от эффекта предыдущего умения. Действует на союзные отряды. Сопротивление магии и сопротивление урону для бехолдера повышаются на 10%, если вражеский герой применяет заклинание</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 1.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 1236

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 2

 **label1:** 7

 **speedmove:** 80

 **posclass:** 5

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

