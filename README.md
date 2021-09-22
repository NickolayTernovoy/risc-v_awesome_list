# В данном awesome list  собраны полезные и интересные материалы для изучения и работы с экосистемой RISC-V и архитектурой процессорных систем. 

## Симуляторы [ assembler and runtime simulator ]
* [**Jupiter**](https://github.com/andrescv/Jupiter) - симулятор для изучения ассемблера RISC-V.
* [**venus**](https://www.kvakil.me/venus/) - онлайн симулятор для изучения ассемблера RISC-V.
* [**Ripes**](https://github.com/mortbopet/Ripes) - графически симулятор для изучения ассемблера RISC-V, есть возможность программирования на языке С, потактовой симуляции программы с иллюстрацией обновления каждой стадии конвейера. Так же добавлен эмулятор cache памяти с настройкой архитектуры кэша, политик замещения. Если нет желания в ручную устанавливать [toolchain RISC-V](https://github.com/riscv-collab/riscv-gnu-toolchain), то можно скачать prebuilt toolchains c сайта [SiFive.](https://www.sifive.com/software)
* [**RARS RISC-V Assembler and Runtime Simulator**](https://github.com/TheThirdOne/rars) - переиздание симулятора [MARS](http://courses.missouristate.edu/kenvollmar/mars/) для архитектуры RISC-V.

## Opensource ядра на базе RISC-V
* [**schoolRISCV**](https://github.com/zhelnio/schoolRISCV) - простейшее академическое ядро на базе RISC-V. Реализована часть инструкций набора rv32i. Эффективно для обучения школьников, студентов принципам работы микропроцессора. В качестве упражнение рекомендуется описать управляющую логику для новых инструкций.  
* [**picorv32**](https://github.com/cliffordwolf/picorv32) - самое популярное ядро на базе RISC-V. Были выпущены ASIC с применением данного soft-core. picorv32 применяется в базовом проекте [Caravel](https://github.com/efabless/caravel) для выпуска чипов на базе [skywater](https://skywater-pdk.readthedocs.io/en/latest/).  Так же описана процедура установки компилятора RISC-V. Читабельные и хорошо оформленные Makefile и Linker Script.
* [**scr1**](https://github.com/syntacore/scr1) - младшее ядро модельного ряда [Syntacore](https://syntacore.com/page/products/processor-ip/scr1). Ядро регулярно обновляется и поддерживается разработчиками. Есть [вебинар](https://youtu.be/OxDkCw3BdCQ) с примером имплементации scr1 на базе отладочной платы [Arty.](https://digilent.com/arty-a7-artix-7-fpga-development-board/)
* [**SERV**](https://github.com/olofk/serv) - самое маленькое soft-core ядро. Реализовано по принципу bit-serial.

* [**RISC-V CORE LIST**](https://riscv.org/exchange/cores-socs/) -  список RISC-V Cores & SoCs.

## Лекционные материалы
* [**Архитектура процессорных систем**](https://www.youtube.com/c/%D0%90%D0%9F%D0%A1%D0%9F%D0%BE%D0%BF%D0%BE%D0%B2) - курс от института МПСУ НИУ МИЭТ посвященный основам архитектуры процессорных систем. В качестве базовой архитектуры рассматривается RISC-V. В дополнительных материалах к курсу можно найти лабораторные работы по проектированию однотактного процессора с набором команда RV32I. 
* [**Лекции от MIT курс 6.004**](https://www.youtube.com/channel/UC1DcxXg6GkAcp2zk2w7U6qQ) - лекции от преподавателей Массачусетского технологического института. Лекционные заметки можете найти [тут.](https://computationstructures.org/lectures/info/info.html)

## Литература 
* [**The RISC-V Reader: An Open Architecture Atlas**](http://riscvbook.com/) - книга от разработчиков архитектуры RISC-V. В книге представлены разъяснения к каждому из существующих (на момент выпуска книги) наборов команд.
* [**Computer Organization and Design The Hardware/Software Interface: RISC-V Edition**](http://home.ustc.edu.cn/~louwenqi/reference_books_tools/Computer%20Organization%20and%20Design%20RISC-V%20edition.pdf) - классический учебник от ветеранов индустрии процессоростроения Девида Паттерсона и Джона Хэннеси. 
* [**Digital Design and Computer Architecture RISC-V Edition**](https://www.elsevier.com/books/digital-design-and-computer-architecture/harris/978-0-12-820064-3) - переиздание [Цифровой схемотехники и архитектура компьютера](https://microelectronica.pro/wp-content/uploads/books/digital-design-and-computer-architecture-russian-translation.pdf). Учебник адаптирован под архитектуру RISC-V. 
## Дополнительные материалы
* [**Новый золотой век компьютерной архитектуры**](https://www.youtube.com/watch?v=Sdb0433lTrk&t=243s&ab_channel=YADRO) - лекция от Дэвида Паттерсона, почетного профессора компьютерных наук Калифорнийского университета в Беркли и заместителя председателя совета директоров RISC-V Foundation. Текстовый вариант лекции на русском языке можно найти - [тут.](https://habr.com/ru/post/440760/)
* [**Цифровая схемотехника и архитектура компьютера**](https://microelectronica.pro/wp-content/uploads/books/digital-design-and-computer-architecture-russian-translation.pdf) - классический учебник по цифровой схемотехники и архитектуре компьютера. В книге разбирается проектирование микропроцессора на базе архитектуры MIPS. Книга переведена на русский язык. Паралельно с прочтением 6-ой и 7-ой главы ознакомится с проектом [schoolMIPS.](https://github.com/MIPSfpga/schoolMIPS)
* [**Следующие шаги в черной магии процессоростроения после того, как вы освоили Харрис & Харрис**](https://habr.com/ru/post/336116/) - заметка с отличным подбором литературы, посвященной разработке цифровых схем на языках описания аппаратуры, устройству процессорных систем. 
* [**A Primer on Memory Consistency and Cache Coherence**](https://www.morganclaypool.com/doi/abs/10.2200/S00962ED2V01Y201910CAC049) - в книге рассказывается о иерархии памяти. Рассматриваются гетерогенные системы, поддержка когерентности и консистентности памяти. 
* [**RISC-V Specifications**](https://riscv.org/technical/specifications/) - здесь вы можете найти последнюю акутальную спецификацию ISA RISC-V.
