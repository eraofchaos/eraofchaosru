---
title: "Фея"
permalink: /units/Sprite/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Прекрасная фея, существующая лишь в легендах и сказках. Тот, кто обращается с ней грубо, навлекает на себя гнев читателей и встречает очень неприятный финал."
unitID: 901
last_modified_at: 2021-03-02
locale: ru
ref: "Фея"
toc: true
---
## General information
 **Описание:** Прекрасная фея, существующая лишь в легендах и сказках. Тот, кто обращается с ней грубо, навлекает на себя гнев читателей и встречает очень неприятный финал.

 **Класс:** [Штурм](/units/Unit Class Charging/)

 **Класс Описание:** Штурмовые отряды атакуют задний ряд, нанося повышенный критический урон стрелковым отрядам и заклинателям.

 **Фракция:** [Гармония](/units/Faction Conflux/)

 **Race:** Хозяин зверей

 **Members:** [x4](/units/Unit Member x4/)

 **Rank:** [R](/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/units/Star 1/)

 **Short description:** Накладывает немоту. Улучшает заклинание в начале боя.

 **Position :** После гибели взрывается, вызывает немоту у цели, увеличивает начальную ману героя.

## Базовые параметры
 **Base HP: 993.0**

 **Base ATK: 69.5**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Зеленый | 34.75 | 3.75 | 744.75 |
  | Синий | 69.5 | 7.5 | 1489.5 |
  | Синий +1 | 104.25 | 11.25 | 2234.25 |
  | Синий +2 | 145.95 | 15.75 | 3127.95 |
  | Фиолетовый | 187.65 | 20.25 | 4021.65 |
  | Фиолетовый +1 | 229.35 | 24.75 | 4915.35 |
  | Фиолетовый +2 | 278.0 | 30.0 | 5958.0 |
  | Фиолетовый +3 | 326.65 | 35.25 | 7000.65 |
  | Оранжевый | 375.3 | 40.5 | 8043.3 |
  | Оранжевый +1 | 430.9 | 46.5 | 9234.9 |
  | Оранжевый +2 | 486.5 | 52.5 | 10426.5 |
  | Оранжевый +3 | 542.1 | 58.5 | 11618.1 |
  | Оранжевый +4 | 597.7 | 64.5 | 12809.7 |
  | Оранжевый +5 | 681.1 | 73.5 | 14597.1 |
  | Красный | 792.3 | 85.5 | 16980.3 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 6.95 | 0.48 | 1.5 | 99.3 |
  | **2x** <i class="fas fa-star"/> | 8.34 | 0.5 | 2.08 | 119.16 |
  | **3x** <i class="fas fa-star"/> | 9.73 | 0.53 | 2.65 | 139.02 |
  | **4x** <i class="fas fa-star"/> | 11.12 | 0.55 | 3.23 | 158.88 |
  | **5x** <i class="fas fa-star"/> | 12.51 | 0.58 | 3.8 | 178.74 |
  | **6x** <i class="fas fa-star"/> | 13.9 | 0.6 | 4.38 | 198.6 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Ароматный венок](/equipment/Ароматный венок/) | **АТК** | **ЗЩТ** | 
  | [Платье Луны и звезд](/equipment/Платье Луны и звезд/) | **ОЗ** | **ЗЩТ** | 
  | [Фосфоресцирующие крылья бабочки](/equipment/Фосфоресцирующие крылья бабочки/) | **АТК** | **ЗЩТ** | 
  | [Изумрудное обручье](/equipment/Изумрудное обручье/) | **ОЗ** | **ЗЩТ** | 

## Эксклюзив

 **Name:** [Почетный штурм](/Exclusive/Sprite Knight Pike/) 

 **Item to Повысить ранг :** -

 **Skin:** -


## Рекомендуемые эмблемы святости

* [Древний огонь](/Emblem/Ancient Fire/) (Порядок)
* [Тайна Неувядающего](/Emblem/Everlasting Secret/) (Порядок)
* [Гнев](/Emblem/Anger/) (Хаос)

## Информация о комбинации

* [Немота](/combination/Немота/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Совершенное умение: Энергетическое разбивание
 **Описание:** <span style="color: #645252;font-size:20px">Когда феи погибают, они наносят урон в размере </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от максимума ОЗ цели. Максимальный урон при этом равен 1000% от ее АТК.</span><span style="color: black">

### Обычное умение 1 : Благословение фей
 **Описание:** <span style="color: #645252;font-size:20px">Когда начинается бой, феи повышают сопротивление магии всех союзных отрядов на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">. Эффект также удваивается для фей.</span><span style="color: black">

### Обычное умение 2 : Вдохновение
 **Описание:** <span style="color: #645252;font-size:20px">Когда феи на поле боя, базовая мана союзных героев повышается на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Обычное умение 3 : Преданность
 **Описание:** <span style="color: #645252;font-size:20px">Когда феи погибают, они накладывают эффект </span><span style="color: black"><span style="color: #48b946;font-size:20px">немоты</span><span style="color: black"><span style="color: #645252;font-size:20px"> на выбранный отряд на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> сек.</span><span style="color: black">

### Эксклюзивное умение фракции I : Близость к элементалям
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Гармонии мастерски владеют таинственной магией Гармонии и повышают сопротивление магии у героев на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Эксклюзивное умение фракции II : Конфликт с элементалями
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Гармонии мастерски наносят урон Гармонии. В бою против отрядов не из Гармонии они получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"></span><span style="color: black"><span style="color: #645252;font-size:20px"> к урону.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*3+15)"
    let str6 = "(LEVEL*1+5)"
    let str3 = "LEVEL*1.5+0.2"
    let str4 = "LEVEL*0.15+1.85"
    let str1 = "LEVEL*0.25+2.75"
    let str2 = "(LEVEL*0.5+2.5)"
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
## Значимость
### Связь дозора

* **Гармония**  (Дозор отрядов Гармонии)
* **Штурм**  (Дозор штурмовых отрядов)

### Бонус героя
* [Мюллих](/heroes/Mullich/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Сиэль](/heroes/Ciele/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Урон отряда
* Сопротивление магии


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

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 2

 **Speedattack:** 160

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 546

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 11

 **speedmove:** 120

 **posclass:** 3

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

