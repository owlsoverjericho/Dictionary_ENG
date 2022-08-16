# Dictionary-index of concepts with links

Attention! Links to videos on each topic are placed in the appropriate repos.
(vids are in rus btw)

/// TODO: redo links
Table of contents:
- [Essential concepts](https://github.com/owlsoverjericho/Dictionary_ENG#Essential-concepts)
- [Basic concepts](https://github.com/owlsoverjericho/Dictionary_ENG#Basic-concepts)
- [Additional topics](https://github.com/owlsoverjericho/Dictionary_ENG#Additional-topics)
- [Data structures](https://github.com/owlsoverjericho/Dictionary_ENG#Data-structures)
- [Extended concepts](https://github.com/owlsoverjericho/Dictionary_ENG#Extended-concepts)
- [Parallel programming](https://github.com/owlsoverjericho/Dictionary_ENG#Parallel-programming)
- [Asynchronous programming](https://github.com/owlsoverjericho/Dictionary_ENG#Asynchronous-programming)
- [Programming paradigms](https://github.com/owlsoverjericho/Dictionary_ENG#Programming-paradigms)

## Essential concepts

- [Abstraction](https://github.com/HowProgrammingWorks/Reusable)
this is a generalization, abstracted from specifics with the allocation of essential and cutting off non-essential properties and relationships. Abstraction - building abstractions or models, increases the reuse of algorithms and data structures.
  - Abstraction - generalized solution of the problem (as opposed to a specific solution),
  suitable for a wide range of tasks;
  - Abstraction - model of a real object (a set of objects), generalization
  of the set, approximation to reality, sufficient to solve the problem;
  - Abstraction - set of properties and relationships of an object related to a certain
  aspect of it necessary to solve the problem;
  - [Abstraction Layer](https://github.com/HowProgrammingWorks/AbstractionLayers)
- Programming Paradigm
  - The paradigm specifies a set of ideas and concepts, assumptions and restrictions, principles, postulates and programming techniques for solving problems on a computer;
  - The paradigm offers a problem solving model, a certain style, patterns
  (examples of good and bad decisions) used to write program code;
- Syntax - rules for constructing program code from symbols, but not
affecting the semantic (i.e. meaning) load of the code. The syntax defines
only the formal structure of the code.
- Value - written to a specific memory location in
in a certain format and representing data that can be manipulated by the program.
- Type - a set of values and operations that can be performed on these values. For example, in JavaScript, the `Boolean` type assumes two values `true` and `false` and logical operations on them, the `Null` type assumes one `null` value, and the `Number` type is a set of rational numbers with additional restrictions on the minimum and maximum value, as well as restrictions on precision and mathematical operations `+ - * ** / % ++ -- > < >= <= & | ~ ^ << >>`.
  - [Data Types](https://github.com/HowProgrammingWorks/DataTypes)
  - `[5, 'Kyiv', true, { city: 'Beijing' }, a => ++a ].map(x => typeof x);`
- Literal - a written value in the program code. For example: literals of numbers, booleans, null and undefined, strings, arrays, objects, functions.
Literals can have a variety of syntaxes, from very simple syntax for writing numbers to complex syntactic constructions for writing objects.
- Scalar / Primitive / Atomic value - the value of the primitive data type.
The scalar is copied on assignment and passed to the function by value.
- Reference points to a value of a reference type, i.e. not a scalar value, for JavaScript these are subtypes of `Object, Function, Array`.
  - [reference types](https://github.com/HowProgrammingWorks/DataTypes)
  - [code examples on arrays and objects](https://github.com/HowProgrammingWorks/DataStructures)
- Identifier - names of variables, constants, functions, methods,
arguments, classes, both internal and imported from other modules and global.
- [Variable](https://github.com/HowProgrammingWorks/DataTypes) -
a named memory area (identifier) that has a data type, address, and value. We can change the value of a variable, as opposed to a constant (and for some languages, the type): `let cityName = 'Beijing';`
- Assignment - binding a value and an identifier (for example, a variable). The assignment operator in many languages returns the assigned value (has the behavior of an expression).
- [Constant](https://github.com/HowProgrammingWorks/DataTypes) -
the identifier with which the immutable value is associated and the type:
`const WATCH_TIMEOUT = 5000;`
- [Composed types](https://github.com/HowProgrammingWorks/DataTypes) -
composite types or structures consist of several scalar values combined into one in such a way that a set of operations can be performed on this combined value, for example: object, array, set, tuple.
- [Enumerated types](https://github.com/HowProgrammingWorks/Enum)
- Flag - A boolean value that defines the state of something, for example, a sign that a connection is closed, a sign that a search has been completed by a data structure, etc. For example: 
`let flagName = false;` Sometimes flags can be called not logical, but enumerated types.
- Algorithm - this is a formal description of the order of computations for a certain class of problems in a finite time.
- Program - code and data combined to control the machine and perform computation.
- Engineering - extracting practical benefits from available resources with the help of science, technology, various methods, organizational structure, as well as techniques and knowledge.
- Software engineering - application of engineering to the software industry. Includes architecture, research, development, testing, deployment and support of software.
- Programming - it is the art and engineering of solving problems with the help of computers.
- Coding - writing the source code of the program using a specific syntax (language), style and paradigm according to the SRS (Software requirements specification).
- Software development - is a combination of programming and coding at all stages of the software life cycle: design, development, testing, debugging, support, maintenance and
modifications.
- Instruction - one step of a calculation algorithm, for example, a processor instruction is executed by the CPU.
- Statement - the smallest syntactic part of a programming language that is executed by an interpreter, runtime, or compiled into machine code.
- Command - atomic task for the shell.
- Expression - a syntax construct of a programming language designed to perform calculations. An expression consists of identifiers, values, operators, and function calls. Example:
`(len - 1) * f(x, INTERVAL)`
- Code block - a logically related group of instructions or statements.
Blocks create a scope. Blocks can be nested. Examples: `{}`,
`(+ a b)`, `begin end`, indentation in python.
- Procedure or Subroutine - a logically related group of instructions or statements that has a name. The procedure promotes code reuse and can be called from different parts of the program, many times and with different arguments. A procedure does not return a value, unlike a function, but in some languages (but not in JavaScript) it can modify its arguments. In many languages, a procedure is described using function syntax (for example, the void type).
- Function - value transformation abstraction. A function uniquely maps one set of values to another set of values. A function can be defined by a block of statements or by an expression. A function has a set of arguments. A function can be called by name or through a pointer. A function promotes code reuse and can be called from different parts of the program many times and with different arguments. In JavaScript, a function is described using function keyword or arrow syntax (lambda functions).
- Function signature - name (identifier), number of arguments and their types (and sometimes the names of arguments), result type.
- [Method](https://github.com/HowProgrammingWorks/Function)
  - a function or procedure associated with an object context or programming interface;
  - `{ a: 10, b: 10, sum() { return this.a + this.b; } }`
- [Loop](https://github.com/HowProgrammingWorks/Iteration)
  - multiple execution of a block of statements
- [Conditional statements](https://github.com/HowProgrammingWorks/Conditional)
  - a syntax construct that allows you to perform different actions or return different values (ternary operator) depending on a logical expression (returning true or false)
- [Recursion](https://github.com/HowProgrammingWorks/Recursion) -
setting an algorithm for calculating a function by calling it itself (directly or indirectly) or defining a function through itself.
  - Indirect recursion - when a function is defined or calls itself not directly, but through another or a chain of functions;
  - Tailed recursion is a special case where the recursive call is the last operation before returning a value, which can always be turned into a loop, even automatically. The non-tail can also be converted into a loop and optimized, but in a more complex way, usually manually.
- [String](https://github.com/HowProgrammingWorks/String)
  - a sequence of characters (in most languages, each character can be accessed via array access syntax, such as square brackets).
- [Collection](https://github.com/HowProgrammingWorks/Collections) -
a data structure that stores a set of values and provides access to them by index or key.
- Array - a collection of elements accessed by indexes. Example:
`const cities = ['Tehran', 'Yalta', 'Potsdam'];`
- Debug - the process of detecting and eliminating errors in software using the output of messages or tools: a debugger, a profiler, a decompiler, resource monitoring and logging systems, continuous integration and testing systems.
- CPU - central processing unit - a device that executes machine instructions.
- ALU - a CPU block that performs arithmetic and logical transformations on machine words representing integers, floating point numbers, memory addresses, strings, booleans.
- Component - several program objects (for example: functions, classes, monads, types) united and organized according to a common feature.
- Module - integral, functionally complete, independent component of a software system having a name, interface, implementation.
- [Modularity](https://github.com/HowProgrammingWorks/Modularity)
  - modularity increases code reuse, simplifies component integration, improves linking and testing of programs in parts;
  - restrictions: modules should not use global variables or modify base classes/prototypes/functions of the programming language, platform and/or framework; modules should be loosely coupled, and they should interact with each other through an external API (preferably) or an event bus (if the system is built on an event model, subscription).
- Library - collection of program objects (eg: functions, classes, monads, types) prepared for reuse (published frequently). A library is a larger logical piece of code than a component. Sometimes a library is used as a synonym for a module, and sometimes a library consists of several modules.
- Complexity
  - Computational complexity
  - Kolmogorov (descriptive) complexity
  - If there are no cycles, then descriptive correlates with computational

## Basic concepts

- [Объект или Экземпляр / Object or Instance](https://github.com/HowProgrammingWorks/DataTypes) -
структура данных, содержащая состояние и методы, связанные с этим состоянием.
Объект может быть создан как литерал `{}` или экземпляр класса `new ClassName()`
или как экземпляр прототипа `new PrototypeConstructor()` или возвращен из фабрики.
  - `const person = { name: 'Marcus', city: 'Roma', born: 121 };`
  - `const person = new Person('Marcus', 'Roma', 121);`
- [Класс / Class](https://github.com/HowProgrammingWorks/Prototype) -
программная абстракция, объединяющая состояние и поведение (свойства и методы)
своих экземпляров (инстансов).
  - `class Point { constructor(x, y) { this.x = x; this.y = y; } }`
  - `class Rect { move(x, y) { this.x += x; this.y += y; } }`
  - `class Square extends Rect { constructor(x, y, m) { super(x, y, m, m); } }`
  - `class Point { static from(point) { return new Point(this.x, this.y); } }`
- [Прототип / Prototype](https://github.com/HowProgrammingWorks/Prototype) -
специальный объект, на который ссылаются его экземпляры и наследники. Свойства
прототипа становятся видны у наследников, если эти свойства не переопределены у
наследников. Формируется цепочка прототипов, по которой происходит
последовательный поиск свойств, пока они не будут найдены или пока не будет
достигнут конец цепочки наследования. Иногда под прототипом понимается шаблон,
который клонируется во время инстанциирования (не для JavaScript).
- Инстанцирование / Instantiation - создание объекта (экземпляра) или выделение
памяти для структуры данных.
  - `const rect = new Rectangle(-50, -50, 100, 150);`
  - `const rect = { a: { x: -50, y: -50 }, b: { x: 100, y: 150 } };`
  - `const cities = new Array(1000);`
  - `const cities = ['Tehran', 'Kiev', 'Yalta', 'Beijing', 'Potsdam', 'London'];`
- Область видимости / Scope - часть кода, из которой "виден" идентификатор.
- Лексический контекст / Lexical environment - набор идентификаторов, связанных
с определенными значениями в рамках функции или блока кода (в том числе блоков
циклов, условий и т.д.).
- Объектный контекст функции - объект, связанный со служебным идентификатором
`this`. Все функции, кроме стрелочных, могут быть связаны с объектным контекстом.
Объект связан с `this` если функция является методом этого объекта, если функция
привязана к нему через `bind` или вызвана через `apply` и `call`.
- Глобальный контекст / Global context - глобальный объект-справочник. Если
идентификатор не находится ни в одном из вложенных лексических контекстов, то
будет выполнен его поиск в глобальном контексте (global, window, sandbox).
- Объявление функции / Function definition - способ объявления функции, который
виден из любого места в лексическом контексте, в котором объявлена функция,
пример: `function sum(a, b) { return a + b; }`
- Функциональное выражение / Function expression - связывание функции с
идентификатором при помощи присвоения, при котором значение будет доступно через
идентификатор не во всем лексическом контексте, а только после места присвоения.
Имеет несколько синтаксических вариантов:
  - функциональное выражение с именованной функцией / Named function expression
    - `const max = function max(a, b) { return a + b; };`
  - анонимное функциональное выражение / Anonymous function expression
    - `const max = function(a, b) { return a + b; };`
  - лямбда-функция / Lambda function
    - `const max = (a, b) => { return a + b; };`
  - лямбда-выражение, Функция-стрелка / Lambda expression, Arrow function
    - `const max = (a, b) => (a + b);`
- [Чистая функция / Pure Function](https://github.com/HowProgrammingWorks/Function)
  - функция, вычисляющая результат только на основе аргументов, не имеющая
  состояния и не обращающаяся к операциям ввода-вывода
  - функция, результат которой всегда детерминированный, т.е. для любого
  аргумента всегда будет один и тот же результат
  - функция, не имеющая побочных эффектов (см. побочный эффект)
- [Замыкание / Closure](https://github.com/HowProgrammingWorks/Closure)
  - если вернуть функцию `g` из функции `f`, то `g` будет видеть контекст
  функции `f`, так же, как и свои аргументы;
  - если `f` возвращает `g`, то говорят, что экземпляр `g` замкнул контекст `f`;
  - способ, позволяющий связать функцию с контекстом (с данными или
  переменными контекста);
  - замыкание является аналогом свойств в ООП, тоже связывающие свойства с
  методами через объект, по сути объект в ООП сам является контекстом
  связывания;
  - при помощи замыкания можно реализовать функциональное наследование;
  - `const add = a => b => a + b;`
  - `const hash = (data = {}) => (key, value) => (data[key] = value, data);`
- [Суперпозиция / Superposition](https://github.com/HowProgrammingWorks/Composition)
  - объединение вызова функций в выражения таким образом, что результат одних
  функций становится аргументами других функций;
  - `const expr2 = add(pow(mul(5, 8), 2), div(inc(sqrt(20)), log(2, 7)));`
- [Композиция / Composition](https://github.com/HowProgrammingWorks/Composition)
- Инструкция / Instruction - один шаг алгоритма вычислений, например инструкция процессора исполняется CPU.
- Оператор / Statement - наименьшая синтаксическая часть языка программирования, исполняемая интерпретатором, средой или компилируемая в машинный код.
- Команда / Command - атомарная задача для командного процессора.
- Выражение / Expression - синтаксическая конструкция языка программирования предназначенная для выполнения вычислений. Выражение состоит из идентификаторов, значений, операторов и вызова функций. Пример: `(len - 1) * f(x, INTERVAL)`
- Блок кода / Block - логически связанная группа инструкций или операторов. Блоки создают область видимости. Блоки могут быть вложенными. Примеры: `{}`, `(+ a b)`, `begin end`, отступы в Python.
- Процедура или подпрограмма / Procedure or Subroutine - логически связанная группа инструкций или операторов, имеющая имя. Процедура способствует повторному использованию кода и может быть вызвана из разных частей программы, много раз и с разными аргументами. Процедура не возвращает значений, в отличие от функций, но в некоторых языках (но не в JavaScript) может модифицировать свои аргументы. Во многих языках процедура описывается при помощи синтаксиса функций (например, типа void).
- Функция / Function - абстракция преобразования значений. Функция однозначно отображает одно множество значений в другое множество значений. Функция может быть задана блоком операторов или выражением. Функция имеет набор аргументов. Функция может быть вызвана по имени или через указатель. Функция способствует повторному использованию кода и может быть вызвана из разных частей программы, много раз и с разными аргументами. В JavaScript функция описывается при помощи function или синтаксиса стрелок (лямбда-функций).
Сигнатура функции / Function signature - имя (идентификатор), количество аргументов и их типы (а иногда и имена аргументов), тип результата.
- Метод / Method
функция или процедура, связанная с объектным контекстом или программным интерфейсом;
`{ a: 10, b: 10, sum() { return this.a + this.b; } }`
- Цикл / Loop - многократное исполнение блока операторов
- Условие / Conditional statements - синтаксическая конструкция, позволяющая выполнить разные действия или возвращающая разные значения (тернарный оператор) в зависимости от логического выражения (возвращающего true или false)
- Рекурсия / Recursion - задание алгоритма вычисления функции через вызов ее самой (прямой или непрямой) или определение функции, через нее саму.
- Косвенная (непрямая) рекурсия - когда функция определена или вызывает себя не напрямую, а через другую или цепочку функций;
- Хвостовая - частный случай, когда рекурсивный вызов является последней операцией перед возвратом значения, что всегда может быть преобразовано в цикл, даже автоматическим способом. Не хвостовая тоже может быть преобразована в цикл и оптимизирована, но более сложным способом, обычно вручную.
- Строка / String - последовательность символов (в большинстве языков к каждому символу можно обратиться через синтаксис доступа к элементам массива, например, квадратные скобки).
- Коллекция / Collection - структура данных, служащая для хранения набора значений и предоставляющая доступ к ним по индексам или ключам.
- Массив / Array - коллекция элементов, доступ к которым осуществляется по индексам. Пример: const cities = ['Tehran', 'Yalta', 'Potsdam'];
- Отладка / Debug - процесс обнаружения и устранения ошибок в программном обеспечении при помощи вывода сообщений или инструментов: отладчика, профилировщика, декомпилятора, систем мониторинга ресурсов и логирования, систем непрерывной интеграции и тестирования.
- ЦП / CPU - центральный процессор / central processing unit - устройство, выполняющее машинные инструкции.
- АЛУ / ALU - блок ЦП, выполняющий арифметические и логические преобразования над машинными словами, представляющими целые числа, числа с плавающей точкой, адресами памяти, строками, логическими величинами.
- Компонент / Component - несколько программных объектов (например: функций, классов, монад, типов) объединенных и организованных по общему признаку.
- Модуль / Module - целостный, функционально полный, независимый компонент программной системы имеющий имя, интерфейс, реализацию.)
  - `const compose = (f1, f2) => x => f2(f1(x));`
  - `const compose = (...funcs) => (...args) => (funcs.reduce((args, fn) => [fn(...args)], args));`
- [Частичное применение / Partial application](https://github.com/HowProgrammingWorks/PartialApplication)
  - `const partial = (fn, x) => (...args) => fn(x, ...args);`
- [Каррирование / Currying](https://github.com/HowProgrammingWorks/PartialApplication)
  - `const result = curry((a, b, c) => (a + b + c))(1, 2)(3);`
- [Побочные эффекты / Side effects](https://github.com/HowProgrammingWorks/Function)
- [Функция высшего порядка / Higher-order Function](https://github.com/HowProgrammingWorks/HigherOrderFunction)
  - если функция только в аргументах, то это колбек;
  - если функция только в результате, то это фабрика функций на замыканиях;
  - если возвращаемая функция имеет тот же смысл, что и получаемая в
  аргументах (+ дополнительное поведение), то это обертка;
  - очень редко бывает, что возвращаемая функция не связана с функцией из
  аргументов (но пока ни кто не нашел вразумительного примера, где это
  реально нужно);
  - если на выходе класс или функция-конструктор, то это фабрики классов и
  прототипов соответственно;
- Функциональное наследование / Functional Inheritance - при помощи замыканий,
частичного применения, каррирования, вложенных лямбд.
- [Обертка / Wrapper](https://github.com/HowProgrammingWorks/Wrapper)
  - функция, которая оборачивает другую функцию (иногда объект, интерфейс или
  функциональный объект), добавляя ему дополнительное поведение;
  - можно обернуть целый API интерфейс и даже асинхронную функцию вместе с
  колбеками (если известен контракт);
- [Дженерики / Generics](https://github.com/HowProgrammingWorks/Generics)
  - Обобщенное программирование - парадигма, позволяющая обобщенно описать
  алгоритмы и структуры данных, абстрагируясь от конкретных типов.
- Интерфейс / Interface
  - набор методов (функций) объединенных или общим объектным контекстом или
  применением к структурам данных одной предметной области т.е. смыслом (API);
  - способ определения (спецификации) контракта, по которому связаны
  программные компоненты;
  - Набор методов с их именами, аргументами и типами аргументов
- Программный интерфейс / Application Interface, API
  - интерфейс программных компонентов: модулей, слоев абстракции, приложений;
- [Синглтон / Singleton](https://github.com/HowProgrammingWorks/Singleton)
  - шаблон проектирования, предполагающий, что в одном пространстве имен
  (процессе, приложении, базе данных) будет только один экземпляр класса
  (или просто один подобный объект) к которому можно обратиться по определенному
  (известному) имени;
- [Функция обратного вызова, колбек / Callback](https://github.com/HowProgrammingWorks/Callbacks)
  - функция передаваемая в качестве аргумента в другую функцию (или метод)
  для того, чтобы быть вызванной для возврата значения, ошибки или уведомления;
  - функции обратного вызова имеют подтипы:
    - один раз вызываемые (чаще всего);
    - [Событие / Event](https://github.com/HowProgrammingWorks/Callbacks)
    - [Лисенер / Listener](https://github.com/HowProgrammingWorks/Callbacks)
- [Итерирование / Iteration](https://github.com/HowProgrammingWorks/Iteration) -
многократное повторение одного блока кода или одной функции над различными
данными: элементами массивов, множеств, списков, коллекций и различными
значениями переменной цикла.
- [Итератор / Iterator](https://github.com/HowProgrammingWorks/Iteration) -
интерфейс доступа к элементам коллекции: массива, множества, списка;
- [Файл / File](https://github.com/HowProgrammingWorks/Files)
- [Поток, Файловый поток / Stream, File Stream](https://github.com/HowProgrammingWorks/Streams)
- [Сокет / Socket](https://github.com/HowProgrammingWorks/Socket) -
программный интерфейс (или абстракция) для обмена данными между процессами.
- [Дескриптор / Handle](https://github.com/HowProgrammingWorks/Files) -
уникальный идентификатор программного объекта (чаще всего объекта операционной
системы): файла, сокета, окна, таймера, соединения и т.д.
- Состояние / State - совокупность данных программного компонента (переменных
и структур данных), определяющие его поведение и реакцию на операции с ним.
- Кэш / Cache - место временного хранения данных (буфер, коллекция, область
памяти) для быстрого доступа и оптимизации. Возможно кэширование операций
чтения, вычислений, операций записи (когда запись не может быть произведена
достаточно быстро) или упреждающее чтение в буфер (когда можно определить,
какие данные будут запрошены с наибольшей вероятностью).
- Хэширование / Hashing - преобразование данных произвольной длины (буфера,
массива, объекта или структуры данных) в последовательность битов определенной
длины (хеш) при помощи хеш-функции (при изменении хоть 1 бита в данных хеш
меняется существенно).
- [Функциональный объект](https://github.com/HowProgrammingWorks/Functor) -
объект функционального типа, который является функцией и объектом одновременно.
Другими словами, функциональный объект может быть вызван, как функция и может
иметь свойства и методы, как объект.
- [Функтор / Functor](https://github.com/HowProgrammingWorks/Functor) - это
функциональный объект, который является еще и рекурсивным замыканием. Функтор
хранит в замыкании защищенное значение и позволяющий отобразить это значение
в другой функтор через вызов функции (обычно `map`).
- [Аппликативный функтор](https://github.com/HowProgrammingWorks/Functor) -
функтор, который имеет метод `apply`.
- Монада / Monad - аппликативный функтор, который имеет метод `chain`.
- [Мемоизация / Memoization](https://github.com/HowProgrammingWorks/Memoization) -
обертка, сохраняющая результаты выполнения функции для предотвращения повторных
вычислений.
- [Примесь / Mixin](https://github.com/HowProgrammingWorks/Mixin) - добавление
свойств, методов или поведения к объекту после его инстанциирования. Пример:
`Object.assign(target, { field1, field2 }, { field3 });`
- Декоратор / Decorator - шаблон оборачивания объектов или функций для добавления
новой функциональности без наследования при помощи специального синтаксиса.
- [Наследование / Inheritance](https://github.com/HowProgrammingWorks/Inheritance)
- [Множественное наследование / Multiple Inheritance](https://github.com/HowProgrammingWorks/Inheritance)
- [Непрямое наследование / Indirect Inheritance](https://github.com/HowProgrammingWorks/Inheritance)
- [Генератор / Generator](https://github.com/HowProgrammingWorks/Generator)
- [Итератор / Iterable and Iterator](https://github.com/HowProgrammingWorks/Iterator)
- [Ввод/вывод / I/O, Input-output](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
  - операции, выходящие за рамки CPU и RAM (арифметико-логического устройства
  и памяти), т.е. операции с устройствами ввода вывода: сеть, диск, порты,
  консоль (клавиатура и экран), другие периферийные устройства (взаимодействие
  с которыми на порядки медленнее, чем внутренние операции в АЛУ и памяти);
- [EventEmitter](https://github.com/HowProgrammingWorks/EventEmitter)
  - универсальная абстракция для работы с событиями через подписку (subscription:
  addListener, on, once) и отправку (emit)
- [Чеининг / Chaining](https://github.com/HowProgrammingWorks/Chaining)
  - цепочный синтаксис вызова функций `total(april)(may)(july)` или методов
  `array.filter(f1).reduce(f2)`
- [Сериализация / Serialization](https://github.com/HowProgrammingWorks/Serialization) -
преобразование структуры данных (развернутой в памяти) в битовую
последовательность, обычно в последовательность байтов (бинарная сериализация)
или в строку (текстовая сериализация).
- [Десериализация / Deserialization](https://github.com/HowProgrammingWorks/Serialization) -
операция, обратная сериализации, т.е. восстановление структуры данных из
последовательности битов (чаще байтов или строки).
- Парсинг / Parsing - синтаксический анализ текста, результатом чего может являться:
  - для формальной грамматики - AST-дерево;
  - для слабоструктурированного документа - структура данных, имеющая
  четкую структуру, в которую частично перенесены данные из слабой структуры;
  - для других естественных или искусственных языков - информационные модели,
  им соответствующие;
- [Регулярные выражения / Regular Expressions](https://github.com/HowProgrammingWorks/RegExp) -
синтаксическая конструкция, паттерн, формальный язык, определяющий порядок
парсинга другой синтаксической конструкции.
- [Зависимость / Dependency](https://github.com/HowProgrammingWorks/Project) -
связанность программных компонентов, при которой один компонент (зависимый)
"знает" другой; это значит, что в нем помещен вызов метода (реализация которого
содержится в другом) или он слушает событие, которое генерирует другой или он
"знает" структуры данных, которые могут быть переданы из другого компонента.
- Декомпозиция / Decomposition - разделение программного компонента на части по
принципу функциональности, при этом, каждая часть будет решать подзадачу и
появится часть кода, которая определяет порядок связи всех частей (композицию).
- [Ленивость / Lazy](https://github.com/HowProgrammingWorks/Lazy)
- [Обработка ошибок / Error handling](https://github.com/HowProgrammingWorks/Errors)
- [Фабрика / Factory](https://github.com/HowProgrammingWorks/Factory) - функция
или метод для инстациирования объектов, функций, структур данных и любых других
программных абстракций, например, экземпляров класса в обход конструктора или
функциональных объектов.
- Объектный Пул / [Object Pool](https://github.com/HowProgrammingWorks/Pool) -
Множество заранее инстанциированных объектов (или массивов, сокетов, буферов,
структур данных и других программных абстракций) из которого мы можем их брать
инициализированные экземпляры (вместо инстанциирования новых) и отдавать их
после использования.
- [Таймеры / Timers](https://github.com/HowProgrammingWorks/Timers)
- [Адаптер / Adapter](https://github.com/HowProgrammingWorks/Adapter) -
Паттерн достижения совместимости, позволяющий обернуть класс, функцию или
другой программный компонент с несовместимым контрактом в программный
компонент с контрактом, который нам нужен.
- [Стратегия (Strategy)](https://github.com/HowProgrammingWorks/Strategy) -
Паттерн реализует выбор одного из совместимых и взаимозаменяемых классов,
которые содержат поведение (алгоритм), аналогичный по функциональности и
реализующий общий интерфейс. Актуален и для функционального программирования.
- [Фасад / Facade](https://github.com/HowProgrammingWorks/Facade) - Паттерн
для скрытия сложности. Фасад скрывает несколько инстансов разных классов в
своих свойствах (иногда приватных, но для JS этого пока нет) и предоставляет
общий (фасадный) интерфейс для управления ими. Для функционального
программирования возможен аналог фасада - функция обертка, скрывающая
инстансы в своем контексте и предоставляющая доступ к ним через возврат
функции (с замыканием) или другого инстанса (методы которого тоже имеют
доступ к скрываемым инстансам через замыкание).

## Additional-topics

- [Линтер / Linter](https://github.com/HowProgrammingWorks/Tools) - статический
анализатор кода (без запуска), который может определить и предложить
стилистические, грамматические или оптимизационное улучшение или просто выявить
проблему (а иногда и исправить ее автоматически).
- Система контроля версий
- Менеджер пакетов
- Непрерывная интеграция
- Тестирование

## Data structures

- [Запись или структура / Struct or Record](https://github.com/HowProgrammingWorks/DataStructures)
- [Массив / Array](https://github.com/HowProgrammingWorks/DataStructures)
- [Буфер / Buffer](https://github.com/HowProgrammingWorks/Buffers)
- [Список / List](https://github.com/HowProgrammingWorks/LinkedList)
  - Односвязный, двусвязный, кольцевой, развернутый список (список массивов)
  - Реализация на объектах, массивах и замыканиях
  - Реализация на синтаксисе прототипов, классов и фабрик
  - Реализация на замыканиях и функциональных объектах
  - Реализация на одной и двух категориях (только узел или список и узел)
- [Стек, очередь, дек](https://github.com/HowProgrammingWorks/Dequeue)
  - Стек / Stack - список, работающий по принципу LIFO;
  - Очередь / Queue - список, работающий по принципу FIFO;
  - Дек / Dequeue - двухсторонний список, работающий, как стек и очередь;
- [Дерево](https://github.com/HowProgrammingWorks/Trees)
- [Двоичное дерево](https://github.com/HowProgrammingWorks/Trees), поисковое
дерево, красно-черное дерево.
- Куча / Heap - древовидная структура данных или область памяти для динамического
распределения под хранение данных.
- [Граф / Graph](https://github.com/HowProgrammingWorks/Graph)
- [Буфер / Buffer](https://github.com/HowProgrammingWorks/Buffers) -
область памяти для хранения данных (обычно для операций ввода/вывода).
- Типизированные массивы
- [Коллекция / Collection](https://github.com/HowProgrammingWorks/Collections) -
структура данных, служащая для хранения набора значений и предоставляющая
доступ к ним по индексам или ключам.
- [Множество / Set](https://github.com/HowProgrammingWorks/Set)
  - структура данных, реализующая математическое "множество";
  - структура данных, служащая для хранения однородного набора значений, которые
  не имеют индексов или ключей (но внутри структуры данных они должны иметь
  порядок, например, индекс в массиве, однако, множество абстрагирует нас от
  этой особенности реализации).
- [Ключ-значение, Хешмап / Map, Key-value](https://github.com/HowProgrammingWorks/KeyValue)
  - [класс `Map`](https://github.com/HowProgrammingWorks/Map)

## Extended concepts

- [Сборка мусора / Garbage Collection](https://github.com/HowProgrammingWorks/GarbageCollection)
- [Прокси / Proxy](https://github.com/HowProgrammingWorks/Proxy)
- [Символ / Symbol](https://github.com/HowProgrammingWorks/Symbol)
- [Дифер / Deferred](https://github.com/HowProgrammingWorks/Callbacks)
- [Промис / Promise](https://github.com/HowProgrammingWorks/Promise)
- [Необработанные ошибки в промисах на Node.js](https://github.com/HowProgrammingWorks/PromiseError)
- [Фьючер / Future](https://github.com/HowProgrammingWorks/Callbacks)
- [Коллекторы данных / Data and Key Collectors](https://github.com/metarhia/metasync/blob/master/lib/collector.js)
- Неизменяемые данные / Immutable Data
- Изменяемые данные / Mutable Data
- Интроспекция / Introspection
- Рефлексия / Reflection
- Скаффолдинг / Scaffolding
- [Инверсия управления / IoC, Inversion of Control](https://github.com/HowProgrammingWorks/InversionOfControl)
- [Внедрение зависимостей / DI, Dependency Injection](https://github.com/HowProgrammingWorks/DependencyInjection)
- [Межпроцессовое взаимодействие / IPC, Interprocess Communication](https://github.com/HowProgrammingWorks/InterProcessCommunication)
- [Песочница / Sandbox](https://github.com/HowProgrammingWorks/Sandboxes)
- Архитектура / Architecture
- Слой доступа к данным / Data Access Layer
- Курсор / Cursor
- Объектно-реляционное отображение / ORM, Object-relational Mapping
- [Сервер / Server](https://github.com/HowProgrammingWorks/NodeServer)
  - [Приклеивание по IP или идентификатору сессии / IP or Session Sticky](https://github.com/HowProgrammingWorks/NodeServer/tree/master/ip-sticky)
  - Кластеризация / Cluster mode
    - При помощи [cluster](https://github.com/HowProgrammingWorks/NodeServer/tree/master/native-cluster)
    - при помощи [child_process](https://github.com/HowProgrammingWorks/NodeServer/tree/master/native-cp)
  - [Разработка API (клиент и сервер)](https://github.com/HowProgrammingWorks/API)
- Сервер приложений / Application Server
- Тонкий клиент и толстый клиент
- [Проекция данных / Projection](https://github.com/HowProgrammingWorks/Projection)
- [Измерение производительности / Benchmarking](https://github.com/HowProgrammingWorks/Benchmark)
- [Интерфейс командной строки / CLI, Command Line Interface and Console](https://github.com/HowProgrammingWorks/CommandLine)
- [Мониторинг файловой системы / File System Watching](https://github.com/HowProgrammingWorks/FilesystemWatch)
- [Транзакционные объекты/Transaction](https://github.com/HowProgrammingWorks/Transaction)
- [Метаданные / Metadata](https://github.com/HowProgrammingWorks/Metaprogramming)
- [Протокол / Protocol](https://github.com/metarhia/metacom)
- [Динамическая загрузка модулей / Live Code Reload](https://github.com/HowProgrammingWorks/LiveReload)
- Http Request (HTTP, XMLHttpRequest, fetch): [примеры](https://github.com/HowProgrammingWorks/HttpRequest)
- [Неблокирующие итерации](https://github.com/HowProgrammingWorks/NonBlocking)
- [Линзы - функциональные аналоги геттера и сеттера](https://github.com/HowProgrammingWorks/Lenses)

## Asynchronous programming

- Асинхронное программирование / Asynchronous Programming
- Неблокирующая операция / Non-blocking I/O
- Асинхронное итерирование / Asynchronous Iterable
- Асинхронный коллектор данных / Asynchronous data collector
- Промис / Promise
- Генератор / Generator Function
- Асинхронный генератор / Asynchronous Generator Function
- Итератор / Iterator
- Асинхронный итератор / Asynchronous Iterator
- Итерируемый объект / Iterable
- Асинхронная композиция функций / Asynchronous Function Composition
- Thenable
- async/await
- Асинхронная очередь / Asynchronous Queue
- Открытый конструктор / Revealing Constructor
- Фьючер / Future
- Дифер / Deferred
- Модель акторов / Actor Model
- Наблюдатель / Observer
- Поток событий / Event stream

## Parallel programming

- Состояние гонки / Race Condition - состояние в многопоточной или конкурентной
программной системе, когда несколько потоков исполнения конкурируя за общий
ресурс портят данные, приводят к непредусмотренному порядку исполнения,
зацикливаются, и т.д., что приводит к утечке ресурсов, непредсказуемому и
неправильному поведению, уязвимостям, нестабильности работы.
- Взаимная блокировка / Deadlock - состояние в многопроцессовой (распределенной)
системе, когда несколько процессов захватили ресурсы, необходимые для дальнейшей
работы друг друга, заблокировав, тем самым дальнейшую работу.
- Livelock - зацикленная блокировка, бесконечно изменяющая состояние, но не
выполняющая полезной работы.
- Ресурсный голод / Resource starvation - состояние в программной системе (обычно
многопоточной), когда она постоянно запрашивает доступ к ресурсам (обычно
разделяемым), и не может их получить.
- Критическая секция / Critical section - участок исполняемого кода, в котором
производится эксклюзивный доступ к разделяемому ресурсу.
- [Потоки / Threads](https://github.com/HowProgrammingWorks/Threads)
  - SharedArrayBuffer
  - worker_threads в Node.js
- [Атомарные операции / Atomics](https://github.com/HowProgrammingWorks/Atomics)
- [Семафор / Semaphore](https://github.com/HowProgrammingWorks/Semaphore)
- [Мьютекс / Mutex](https://github.com/HowProgrammingWorks/Mutex)

## Programming paradigms

- [Императивное программирование / Imperative Programming](https://github.com/HowProgrammingWorks/ImperativeProgramming)
  - Неструктурное программирование / Non-structured
  - Структурное программирование / Structured Programming
  - Процедурное программирование / Procedural Programming
  - [Object-oriented programming](https://github.com/HowProgrammingWorks/ObjectOrientedProgramming)
  - [Prototype-oriented programming](https://github.com/HowProgrammingWorks/PrototypeOrientedProgramming)
- [Функциональное программирование / Functional Programming](https://github.com/HowProgrammingWorks/FunctionalProgramming)
  - [примеры разных стилей функционального кода](https://github.com/HowProgrammingWorks/Abstractions)
- Логическое программирование / Logical Programming
- Декларативное программирование / Declarative Programming
- [Программирование управляемое данными / Data-driven Programming](https://github.com/HowProgrammingWorks/DataDrivenProgramming)
- Техники программирования
  - [Асинхронное программирование / Asynchronous Programming](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
  - Реактивное программирование / Reactive Programming
- [Событийное программирование / Event-driven Programming](https://github.com/HowProgrammingWorks/EventDrivenProgramming)
- [Метапрограммирование / Metaprogramming](https://github.com/HowProgrammingWorks/Metaprogramming)
