---
title: "Ифрит"
permalink: /units/Efreeti/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Ифриты рождены в пламени Инферно. Они обладают магией Огня."
unitID: 506
last_modified_at: 2021-02-24
locale: ru
ref: "Ифрит"
toc: true
---
## General information
 **Описание:** Ифриты рождены в пламени Инферно. Они обладают магией Огня.

 **Класс:** [Заклинатель](/units/Unit Class Caster/)

 **Класс Описание:** Благодаря своим тайным знаниям, отряды заклинателей обладают повышенным сопротивлением магии.

 **Фракция: ** [Инферно](/units/Faction Inferno/)

 **Race:** Злой дух

 **Members:** [x4](/units/Unit Member x4/)

 **Rank:** [SR](/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 2/)

 **Unit description:** Огненный шар: наносит огромный урон врагам, поджигая их.

 **Short description:** Щит отражает урон. Вызывает горение.

 **Position :** Наносит магический урон и обладает щитом Огня. Основной отряд для отражения урона.

 **Recommend:** Существа с низким здоровьем и высокой атакой. Они будут чрезвычайно эффективны, если не забывать их вовремя лечить.

## Базовые параметры
 **Base HP: 1446.0**

 **Base ATK: 225.4**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/))

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Зеленый | 112.7 | 3.25 | 1084.5 |
  | Синий | 225.4 | 6.5 | 2169.0 |
  | Синий +1 | 338.1 | 9.75 | 3253.5 |
  | Синий +2 | 473.34 | 13.65 | 4554.9 |
  | Фиолетовый | 608.58 | 17.55 | 5856.3 |
  | Фиолетовый +1 | 743.82 | 21.45 | 7157.7 |
  | Фиолетовый +2 | 901.6 | 26.0 | 8676.0 |
  | Фиолетовый +3 | 1059.38 | 30.55 | 10194.3 |
  | Оранжевый | 1217.16 | 35.1 | 11712.6 |
  | Оранжевый +1 | 1397.48 | 40.3 | 13447.8 |
  | Оранжевый +2 | 1577.8 | 45.5 | 15183.0 |
  | Оранжевый +3 | 1758.12 | 50.7 | 16918.2 |
  | Оранжевый +4 | 1938.44 | 55.9 | 18653.4 |
  | Оранжевый +5 | 2208.92 | 63.7 | 21256.2 |
  | Красный | 2569.56 | 74.1 | 24726.6 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **2x** <i class="fas fa-star"/> | 27.048 | 0.48 | 1.87 | 173.52 |
  | **3x** <i class="fas fa-star"/> | 31.556 | 0.51 | 2.43 | 202.44 |
  | **4x** <i class="fas fa-star"/> | 36.064 | 0.53 | 3.0 | 231.36 |
  | **5x** <i class="fas fa-star"/> | 40.572 | 0.55 | 3.56 | 260.28 |
  | **6x** <i class="fas fa-star"/> | 45.08 | 0.58 | 4.13 | 289.2 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Шар пламени](/equipment/Шар пламени/) | **АТК** | **ЗЩТ** | 
  | [Легкая броня пламени](/equipment/Легкая броня пламени/) | **ОЗ** | **ЗЩТ** | 
  | [Браслеты пламени](/equipment/Браслеты пламени/) | **АТК** | **ЗЩТ** | 
  | [Наплечники пламени](/equipment/Наплечники пламени/) | **ОЗ** | **ЗЩТ** | 

## Рекомендуемые эмблемы святости

* [Тайна Неувядающего](/Emblem/Everlasting Secret/) (Порядок)
* [Гнев](/Emblem/Anger/) (Хаос)
* [Королевская беда](/Emblem/King's Calamity/) (Злой)

## Информация о комбинации

* [Горение](/combination/Горение/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Совершенное умение: Огненная буря
 **Описание:** <span style="color: #645252;font-size:20px">Ифриты применяют к выбранной области Огненную бурю, которая наносит </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> ед. урона всем вражеским войскам в этой области и вызывает </span><span style="color: black"><span style="color: #48b946;font-size:20px">горение</span><span style="color: black"><span style="color: #645252;font-size:20px"> на 15 сек. </span><span style="color: black">

### Обычное умение 1 : Пылающий щит
 **Описание:** <span style="color: #645252;font-size:20px">В начале боя ифриты создают для всех союзных отрядов Инферно &lt;Щит огня&gt;, который отражает 15% полученного урона в следующие </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> сек.</span><span style="color: black">

### Обычное умение 2 : Раскаление
 **Описание:** <span style="color: #645252;font-size:20px">&lt;Щит огня&gt; ифритов повышает сопротивление урону на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> и сопротивление магии на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Обычное умение 3 : Бог Огня
 **Описание:** <span style="color: #645252;font-size:20px">Ифриты получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к ОЗ и </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к сопротивлению отряда урону. </span><span style="color: black">

### Эксклюзивное умение фракции I : Обжигающий удар
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Инферно мастерски контролируют огонь, повышая критический удар на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> и КРИТ. УРН на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> в бою против горящих отрядов.</span><span style="color: black">

### Эксклюзивное умение фракции II : Резонанс антимагии
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Инферно мастерски владеют групповой обороной. За каждый выживший отряд они получают </span><span style="color: black"><span style="color: #48b946;font-size:20px">+<span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к сопротивлению магии.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*10+50)"
    let str8 = "(LEVEL*0.5+7.5)"
    let str5 = "LEVEL*3+12"
    let str6 = "LEVEL*1+4"
    let str3 = "LEVEL*1+4"
    let str4 = "LEVEL*1+4"
    let str1 = "(LEVEL*8+152)*0.01*ATK"
    let str2 = "(LEVEL*2+13)"
    let str9 = "(LEVEL*0.5+2.5)"
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
## Значимость
### Связь дозора

* **Инферно**  (Дозор отрядов Инферно)
* **Заклинатель**  (Дозор отрядов заклинателей)

### Бонус героя
* [Раска](/heroes/Rashka/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Ксерон](/heroes/Xeron/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Критический удар отряда
* Урон отряда


## Awaking
### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Султан ифритов

 **Awaking Описание:** Эти сильные духи появились из сосредоточенного пламени бездны. Они - сильнейшие союзники демонов Астрального мира Огня. И теперь они пришли в Эрафию, чтобы помочь Эофолу одержать окончательную победу.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Используйте ифритов и не менее </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> отрядов заклинателей, чтобы победить </span><span style="color: #1ca216;font-size:18px">14</span><span style="color: #3c2a1e;font-size:18px"> волн ходячих мертвецов в Склепе за один раз. (Набег не учитывается при выполнении этого задания).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> элемента снаряжения в Походе гильдии. </span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ султанов ифритов на уровнях 14-2 и 14-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте Раску и ифритов, чтобы победить в </span><span style="color: #1ca216;font-size:18px">12</span><span style="color: #3c2a1e;font-size:18px"> боях в кампании. (Набег не учитывается при выполнении этого задания).</span>

## Awaken Skills

### 1st Skill (or 2nd): Воздействие жара
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Огненная буря&gt;</span><span style="color: #645252;font-size:18px">: в начале боя все вражеские отряды получают горение на 20 сек.</span>

### 2nd Skill (or 1st): Пир пламени
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Огненная буря&gt;</span><span style="color: #645252;font-size:18px">: урон наносится целям и большому количеству врагов, стоящих за ними</span>

### 3rd Skill (or 4th): Бой в огне
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Пылающий щит&gt;</span><span style="color: #645252;font-size:18px">: урон отряда повышается на 15%. Длительность эффекта увеличена на 30 сек.</span>

### 4th Skill (or 3rd): Отражающая кожа
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Пылающий щит&gt;</span><span style="color: #645252;font-size:18px">: сопротивление отряда урону повышается еще на 15%. Длительность эффекта увеличена на 30 сек.</span>

### 5th Skill (or 6th): Страж Инферно
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Бог огня&gt;</span><span style="color: #645252;font-size:18px">: скорость атаки ифритов повышается на 5% за каждый отряд Инферно на поле боя</span>

### 6th Skill (or 5th): Волшебная ткань
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Бог огня&gt;</span><span style="color: #645252;font-size:18px">: скорость атаки ифритов повышается на 5% за каждый отряд заклинателей на поле боя</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **fly:** mofaqiu

 **flyspeed:** 300

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 9.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 7.0

 **Defense Show:** 4.0

 **Score:** 794

 **HP Show:** 4

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 51

 **label1:** 4

 **speedmove:** 80

 **posclass:** 5

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

