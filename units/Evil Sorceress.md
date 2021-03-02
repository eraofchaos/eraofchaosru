---
title: "Злая ведьма"
permalink: /units/Evil Sorceress/
excerpt: "Эра хаоса Отряды. Отряды. Эра хаоса Чародейка из Храма Баа. Все ее лицо покрыто магическими знаками. Обладает ужасной демонической мощью."
unitID: 709
last_modified_at: 2021-03-02
locale: ru
ref: "Злая ведьма"
toc: true
---
**Warning** This unit is not released yet, provided information can be changed later or may contain inconsistency!
{: .notice--danger}

## General information
 **Описание:** Чародейка из Храма Баа. Все ее лицо покрыто магическими знаками. Обладает ужасной демонической мощью.

 **Класс:** [Штурм](/units/Unit Class Charging/)

 **Класс Описание:** Штурмовые отряды атакуют задний ряд, нанося повышенный критический урон стрелковым отрядам и заклинателям.

 **Фракция:** [Подземелье](/units/Faction Dungeon/)

 **Race:** Войска Подземелья

 **Members:** [x1](/units/Unit Member x1/)

 **Rank:** [Командующий](/units/Unit Rank Commander/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/units/Star 3/)

 **Short description:** Отражение заклинаний, усиление по области

 **Position :** Отражение заклинаний, усиление по области

## Базовые параметры
 **Base HP: 5770.0**

 **Base ATK: 633.6**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Зеленый | 316.8 | 12.0 | 4327.5 |
  | Синий | 633.6 | 24.0 | 8655.0 |
  | Синий +1 | 950.4 | 36.0 | 12982.5 |
  | Синий +2 | 1330.56 | 50.4 | 18175.5 |
  | Фиолетовый | 1710.72 | 64.8 | 23368.5 |
  | Фиолетовый +1 | 2090.88 | 79.2 | 28561.5 |
  | Фиолетовый +2 | 2534.4 | 96.0 | 34620.0 |
  | Фиолетовый +3 | 2977.92 | 112.8 | 40678.5 |
  | Оранжевый | 3421.44 | 129.6 | 46737.0 |
  | Оранжевый +1 | 3928.32 | 148.8 | 53661.0 |
  | Оранжевый +2 | 4435.2 | 168.0 | 60585.0 |
  | Оранжевый +3 | 4942.08 | 187.2 | 67509.0 |
  | Оранжевый +4 | 5448.96 | 206.4 | 74433.0 |
  | Оранжевый +5 | 6209.28 | 235.2 | 84819.0 |
  | Красный | 7223.04 | 273.6 | 98667.0 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 88.704 | 0.55 | 6.28 | 807.8 |
  | **4x** <i class="fas fa-star"/> | 101.376 | 0.58 | 7.02 | 923.2 |
  | **5x** <i class="fas fa-star"/> | 114.048 | 0.6 | 7.76 | 1038.6 |
  | **6x** <i class="fas fa-star"/> | 126.72 | 0.63 | 8.5 | 1154.0 |

## Снаряжение

  |  Снаряжение  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [UnknownEquipment_7091](/equipment/UnknownEquipment_7091/) | **АТК** | **ЗЩТ** | 
  | [UnknownEquipment_7092](/equipment/UnknownEquipment_7092/) | **ОЗ** | **ЗЩТ** | 
  | [UnknownEquipment_7093](/equipment/UnknownEquipment_7093/) | **АТК** | **ЗЩТ** | 
  | [UnknownEquipment_7094](/equipment/UnknownEquipment_7094/) | **ОЗ** | **ЗЩТ** | 

## Эксклюзив


## Рекомендуемые эмблемы святости

* [Древний огонь](/Emblem/Ancient Fire/) (Порядок)
* [Тайна Неувядающего](/Emblem/Everlasting Secret/) (Порядок)
* [Гнев](/Emblem/Anger/) (Хаос)

## Информация о комбинации

* [Горение](/combination/Горение/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Совершенное умение: Разрыв душ
 **Описание:** <span style="color: #645252;font-size:20px">Каждые 18 сек. 2 отрядам в определенном радиусе вокруг цели наносится урон в </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от АТК +</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от макс. ОЗ, с шансом 30% накладывается </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;интоксикация&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">. Одному вражескому отряду заклинателей наносится урон в </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от макс. ОЗ злой ведьмы, накладывается </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;интоксикация&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">. Эффект </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;интоксикации&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> действует 2 сек. При обычной атаке игнорируется 300 защиты врага.</span><span style="color: black">

### Обычное умение 1 : Волшебное зеркало
 **Описание:** <span style="color: #645252;font-size:20px">У злой ведьмы иммунитет к </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;немоте&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, своим присутствием в бою она повышает базовую ману союзных героев на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">. В начале боя боец накладывает на себя и 1 некрупный союзный отряд эффект &lt;Волшебное зеркало&gt;, который действует до конца боя. В бою с отрядами дальнего боя сопротивление урону злых ведьм повышено на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Обычное умение 2 : Посох антимагии
 **Описание:** <span style="color: #645252;font-size:20px">Отрядный урон злой ведьмы повышен на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">. Когда вражеский герой применяет заклинание, злая ведьма наносит врагам в определенном радиусе вокруг цели урон в </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от АКТ +</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от макс. ОЗ. Всем вражеским отрядам наносится урон в 1,5% от макс. ОЗ, бойцы под действием </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;отравления&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> дополнительно </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;оглушаются&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> на 4 сек., а </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;горящие&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> бойцы получают дополнительный урон в </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> от макс. ОЗ. Отрядам Башни злая ведьма наносит на 50% больше урона отряда.</span><span style="color: black">

### Обычное умение 3 : Телепортация
 **Описание:** <span style="color: #645252;font-size:20px">Скорость атаки повышается на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str10"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">. Штурмовые отряды Подземелья с шансом 5% при обычной атаке оглушают </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;отравленные&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> цели на 2 сек. Через 4 сек. после начала боя Злая ведьма ускоряет атаку союзных штурмовиков на 15%, эффект длится </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str11"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> сек. Злая ведьма перемещается между миром теней и реальностью. Когда она в мире теней, у нее иммунитет к урону, но ее нельзя лечить. Длительность 2 сек. Перезарядка 5 сек.</span><span style="color: black">

### Эксклюзивное умение фракции : Темный конфликт
 **Описание:** <span style="color: #645252;font-size:20px">Отряды Подземелья мастерски используют рельеф, повышая урон отряда на </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str12"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> в бою против отрядов не из Подземелья.</span><span style="color: black">

### Обычное умение 6 : Алые катакомбы
 **Описание:** <span style="color: #645252;font-size:20px">Размещение 3 отрядов Подземелья дает +</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str13"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к урону отряда +</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str14"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> к сопротивлению урону. При активации «Разрыва душ» появляется область действия </span><span style="color: black"><span style="color: #F0F000;font-size:20px">&lt;Алых катакомб&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"></span><span style="color: black"><span style="color: #645252;font-size:20px">, которая расширяется по мере повышения уровня умения. Область существует 15 сек. Перезарядка 30 сек.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "LEVEL*3+11"
    let str8 = "LEVEL*0.1+0.9"
    let str5 = "LEVEL*2+20"
    let str6 = "LEVEL*1+2"
    let str3 = "LEVEL*0.1+2.6"
    let str4 = "LEVEL*1+2"
    let str1 = "LEVEL*10+150"
    let str2 = "LEVEL*0.3+2.5"
    let str12 = "(LEVEL*1+5)"
    let str13 = "LEVEL*1+15"
    let str10 = "LEVEL*1+10"
    let str11 = "(LEVEL*1+15)"
    let str9 = "LEVEL*0.1+3.5"
    let str14 = "LEVEL*1+15"
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
     res = eval(str12); document.getElementById('str12').textContent = res;
     res = eval(str13); document.getElementById('str13').textContent = res;
     res = eval(str10); document.getElementById('str10').textContent = res;
     res = eval(str11); document.getElementById('str11').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
     res = eval(str14); document.getElementById('str14').textContent = res;
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
* **Штурм**  (Дозор штурмовых отрядов)

### Бонус героя
* [Мюллих](/heroes/Mullich/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Мутара](/heroes/Mutare/)  ->   Способность:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Дракон Мутара](/heroes/Dragon Mutare/)  ->   Способность:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Талант

* Атака
* ОЗ
* Скорость атаки
* Урон отряда


## Awaking
### Awaking Details
 **Is it possible right now?** NO

 **Awaking Name:** null

 **Awaking Описание:** Гнев Скорпикоры сокрушает горы, ее вид вселяет ужас, а рев - подчиняет волю.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Используйте мантикору и хотя бы </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отряда Подземелья, чтобы добиться уровня «Чемпион» или выше в Утопии драконов один раз. (Набег не учитывается при выполнении этого задания).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> элемента снаряжения в Походе гильдии. </span>

 3. <span style="color: #3c2a1e;font-size:18px">Соберите </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> душ скорпикор на уровнях 17-2 и 17-4 в Подземелье.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Используйте мантикору и хотя бы </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> отряда Подземелья, чтобы победить в 1 бою Дуэли заступников. (Набег не учитывается при выполнении этого задания).</span>

## Awaken Skills

### 1st Skill (or 2nd): Разбитый строй
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Тактическое решение&gt;</span><span style="color: #645252;font-size:18px">: шанс срабатывания при обычной атаке повышается на 50%. Отряды ближнего боя получают -60 к стойкости и -2% к защите. Этот эффект не может быть рассеян. Длится 6 сек., суммируется до 5 раз.</span>

### 2nd Skill (or 1st): Стратегия набега
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Тактическое решение&gt;</span><span style="color: #645252;font-size:18px">: шанс срабатывания при обычной атаке повышается на 50%. Стрелковые отряды/заклинатели получают +4% к урону и критическому урону. Этот эффект не может быть рассеян. Длится 6 сек., суммируется до 5 раз.</span>

### 3rd Skill (or 4th): Клич к отступлению
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Вой разрушителя магии&gt;</span><span style="color: #645252;font-size:18px">: когда враг применяет магию Земли, его оборонительные отряды получают -20% к исцелению; когда враг применяет магию Воды, его стрелковые отряды получают -20% к скорости атаки; когда враг применяет магию Огня, его атакующие отряды получают -20% к урону; когда враг применяет магию Воздуха, его отряды заклинателей получают немоту на 1,5 сек.</span>

### 4th Skill (or 3rd): Сила разрушителя магии
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Вой разрушителя магии&gt;</span><span style="color: #645252;font-size:18px">: когда враг применяет магию Земли, оборонительные отряды (ваши и союзников) получают +15% к исцелению. Когда враг применяет магию Воды, скорость стрелковых отрядов (ваших и союзников) повышается на 15%. Когда враг применяет магию Огня, УРН атакующих отрядов (ваших и союзников) повышается на 15%. Когда враг применяет магию Воздуха, вы и союзные отряды получаете иммунитет к немоте на 2 сек.</span>

### 5th Skill (or 6th): Пронизывающая ядовитая кровь
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Брызги ядовитой крови&gt;</span><span style="color: #645252;font-size:18px">: эффект срабатывает, когда цель повержена. Возможно до 3 срабатываний. Эффект брызг ядовитой крови гарантированно срабатывает раз в 30 сек.</span>

### 6th Skill (or 5th): Брызги яда
 **Описание:** <span style="color: #48b946;font-size:18px">&lt;Брызги ядовитой крови&gt;</span><span style="color: #645252;font-size:18px">: снижают ЗЩТ на 50%. Возможно до 3 срабатываний при гибели цели. Может сработать еще раз через 15 сек.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 2

 **Speedattack:** 140

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 280

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 1630

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 2

 **label1:** 7

 **speedmove:** 120

 **posclass:** 3

 **talk1:** Мое копье не сломается!

 **talk2:** Предо мной лишь трупы!

 **talk3:** Я стою на защите своего дома и своей родины!

