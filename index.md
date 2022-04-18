# MK90 & Co.
## Вся информация в одном месте. Работа в процессе.

🇬🇧 English version [here](https://yprits.github.io/MK90/indexEn.html) / Английская версия [здесь](https://yprits.github.io/MK90/indexEn.html) 🇬🇧

Дамп всего сайта Петра Пиатека *(3.2021, некоторая информация устарела)*:
[1](https://github.com/Yprits/MK90/raw/main/Pisi(3-E).rar)
[2](https://github.com/Yprits/MK90/raw/main/Pisi(f-k).rar)
[3](https://github.com/Yprits/MK90/raw/main/Pisi(l-o).rar)
[4](https://github.com/Yprits/MK90/raw/main/Pisi(p).rar)
[5](https://github.com/Yprits/MK90/raw/main/Pisi(s-w).rar)

Только "советская" [часть дампа](https://github.com/Yprits/MK90/blob/main/MKonly.rar)

_________________________________________
### MK90
![mk90](https://user-images.githubusercontent.com/102995285/163726257-f7cc0537-3b0c-461d-879c-11c3f9871fb6.jpg)
- [Руководство по эксплуатации к МК-90](https://github.com/Yprits/MK90/files/8507407/mk90.pdf), [каталог программ](https://github.com/Yprits/MK90/files/8507410/CatalogProg-mk90.zip), [руководство по эксплуатации к МК-92](http://electronika-5.ru/calc/doc/mk-92_ins.rar) и [описание Бейсика 2.1](http://electronika-5.ru/calc/doc/mk-92_bas.rar) (взято у [Инварианта](http://electronika-5.ru/))
- [Описание аппаратной части](https://yprits.github.io/MK90/rus/hwru.html)
- [Внутреннее представление данных](https://yprits.github.io/MK90/rus/foru.html)
- [Описание картриджа](https://yprits.github.io/MK90/rus/caru.html) и [его паспорт](http://electronika-5.ru/calc/doc/mk-90_smp.rar)
- [Карта памяти картриджа](https://yprits.github.io/MK90/rus/cameru.html)
- [Картридж памяти только для чтения](https://yprits.github.io/MK90/rus/rocaru.html)
- [Простой считыватель/программатор картриджей](https://yprits.github.io/MK90/rus/prgru.html)
- [Программирование МК90](https://yprits.github.io/MK90/rus/asmru.html)
- Частично прокомментированный дизассемблинг ПЗУ [BASIC version 2.0](https://github.com/Yprits/MK90/files/8502160/mk90ro20.2.zip) и [BASIC version 1.0](https://github.com/Yprits/MK90/blob/main/rom1.src)
- [Эмулятор МК90 для Windows](https://yprits.github.io/MK90/rus/emuru.html) (с исходниками)
- 
  - [Дамп картриджа СМП92-1 (ПЗУ)](https://github.com/Yprits/MK90/files/8505852/smp92-1.zip), содержащего игры и обучалки, которые можно запустить на эмуляторе (v.09+, BASIC 2.0) - предоставлено [Сергеем Фроловым](http://www.leningrad.su/museum/).
  - [Здесь](https://www.youtube.com/watch?v=48pmWw4TG1o) показано, как выглядят эти игры на настоящем компьютере.
  - [Игры, извлеченные из СМП92-1](https://github.com/Yprits/MK90/files/8505854/games_pack.zip), которые можно записать на обычные картриджи МПО-10 и играть на настоящем МК-90 с любой версией BASIC.
  - Частично прокомментированный [дизассемблированный листинг загрузчика и главного меню](https://github.com/Yprits/MK90/files/8505864/mainmenu.zip)
  - Игра «chess» представляет собой графическую надстройку к программе [chess.sav](http://www.ibiblio.org/pub/academic/computer-science/history/pdp-11/rt/games/) для операционной системы RT-11.

_________________________________________

### МК85
![mk85](https://user-images.githubusercontent.com/102995285/163860355-78e0b5bb-0a5a-49c2-9ae8-3fa19788c992.jpg)

Дизайн этого калькулятора, очевидно, основан на [Casio FX-700P](http://www.pisi.com.pl/piotr433/#fx700), но на самом деле это совершенно другой компьютер. В нем стоит 16-битный микропроцессор, совместимый с PDP-11, а также внешнее ОЗУ, программное ПЗУ и контроллер ЖК-дисплея. Такая открытая архитектура делает его интересным для хакинга.
- [Руководство по эксплуатации](https://github.com/Yprits/MK90/files/8507536/mk85_manual.pdf), [принципиальная схема](https://github.com/Yprits/MK90/files/8507538/mk85_sch.zip), печатная плата: [вид сверху](https://commons.wikimedia.org/wiki/File:PCB_main_1.png) и [вид снизу](https://commons.wikimedia.org/wiki/File:Elektronika_MK-85_PCB_main.png)
- Описание аппаратной части
- Внутреннее представление данных, структура BASIC-программы, карта памяти
- Алгоритмы
- Отличия от Casio FX-700P
- Недокументированные функции, особенности и ошибки
- Программирование в кодах
- Частично прокомментированный дизассемблинг ПЗУ
- Шрифт МК-85 для Windows
- Эмулятор МК-85 для Windows
- Модификация МК-85




_________________________________________

### MK87
![mk87](https://user-images.githubusercontent.com/102995285/163768441-190e5a9d-f441-432c-840d-f8ddf5491e15.jpg)

Дизайн этой электронной записной книжки вдохновлен аналогичной Casio PF-3000, но он создан на той же компонентной базе, что и МК85.
- [Эмулятор](https://github.com/Yprits/MK90/files/8504129/mk87emul.zip) v05
- [Исходники](https://github.com/Yprits/MK90/files/8504133/isxodnik.zip) v05
- [Более новая версия эмулятора](https://github.com/Yprits/MK90/files/8504247/mk87emex.zip) (v06, без исходников)
- [Сервисный пакет](https://github.com/Yprits/MK90/files/8504154/opisanie.zip) (содержит схемы, руководство пользователя и др.)
- **ПОИСК**
  - частично прокомментированного ПЗУ;
  - исходников v06;
  - эмулятора v07 и выше (если таковой был) и исходников к нему



Продолжение следует.
