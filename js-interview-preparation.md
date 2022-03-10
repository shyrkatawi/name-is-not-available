# потом оформлю как нибудь
* адекватный видос к JS интервью<br>
  https://www.youtube.com/watch?v=H5wnkRJBfA8&ab_channel=ITVDN<br>
  список вопросов про которые он говорил<br>
  https://github.com/bmarvinb/software-engineer-interview-questions<br>
* какая то статья про асинхнонщину с хабра https://habr.com/ru/post/651037/ <br>
Сравниваем async/await и then/catch с примерами https://habr.com/ru/company/skillbox/blog/651781/ <br>
ну и видос в догонку https://www.youtube.com/watch?v=p0d8p9C2aYs <br>

# ответы для stage2 basic JS
сами вопросики https://github.com/rolling-scopes-school/tasks/blob/master/tasks/interview-basic-coreJS.md

Data types <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures <br>

Number methods <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Number  <br>

String methods <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/String  <br>

let var const - differences<br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/var <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/let <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/const <br>

ternary operator<br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Conditional_Operator <br>

switch case - examples, where it can be useful <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/switch <br>
(по поводу где это может быть полезно я даже боюсь представить... т.к. если мало проверок то можно обойтись if->return, а если много проверок, то лучше использовать объект где ключ это как бы case) <br>

type conversions <br>
https://www.w3schools.com/js/js_type_conversion.asp <br>

Be able to discover cases of implicit data types conversion into boolean, string, number <br>
вот хорошая статья с хабра, вот только понимать что получится при true + false... (получится ЛЮТЫЙ говнокод) <br>
https://habr.com/ru/company/ruvds/blog/347866/ <br>

Strict comparison and Object.is <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Equality_comparisons_and_sameness <br>

what is polyfills <br>
прочтения статьи и комментариев к ней вполне достаточно https://habr.com/ru/company/ruvds/blog/475248 <br>

Date object and Date methods, props <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Date <br>

Know how to use built-in methods(это методы объекта) <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects <br>

Know how to copy array and how to modify array <br>
димыч https://www.youtube.com/watch?v=6napu-MGQDo <br>
какой то чел, 7 методов клонирования объектов https://www.youtube.com/watch?v=82yxd9xbyAQ <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/assign <br>
ну и на доку loadash сыылка на всякий случай https://lodash.com/docs/4.17.15#clone <br>

Know how to sort Array and Know several method how to iterate Array elements <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array <br>

loops <br>
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration <br>
там внутри все виды <br>

про вопросы про браузер потом добавлю <br>
JavaScript in Browser:

Global object window

    Document

Events Basics

    Event Phases
    Event Listeners
    DOM Events
    Know basic Event types
    Mouse / Keyboard Events
    Form / Input Events

Timers

    setTimeout
    setInterval

Web Storage API & cookies

    LocalStorage
    SessionStorage


# ответы для stage2 core JS
сами вопросичи https://github.com/rolling-scopes-school/tasks/blob/master/tasks/interview-corejs.md <br>
 <br>
Hoisting <br>
https://medium.com/@stasonmars/%D1%80%D0%B0%D0%B7%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F-%D1%81-%D0%BF%D0%BE%D0%B4%D0%BD%D1%8F%D1%82%D0%B8%D0%B5%D0%BC-hoisting-%D0%B2-javascript-7d2d27bc51f1 <br>
 <br>
Temporal dead zone <br>
https://css-live.ru/articles/es6-let-const-i-vremennaya-myortvaya-zona-vmz-iznutri.html <br>
https://www.youtube.com/watch?v=OgE3P6kEPz4 <br>
 <br>
Know static Object methods <br>
https://learn.javascript.ru/static-properties-methods <br>
 <br>
Property flags & descriptors (student is able to set property via Object. defineProperty) <br>
https://www.youtube.com/watch?v=z5h-iQSB6Dw <br>
 <br>
Know how to create iterable objects, Symbol.iterator usage (optional) <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Iterators_and_Generators <br>
https://habr.com/ru/company/vk/blog/533822/ <br>
 <br>
Be able to loop through Object keys <br>
https://stackoverflow.com/questions/684672/how-do-i-loop-through-or-enumerate-a-javascript-object <br>
 <br>
Know how to copy array part and how to flatten nested array <br>
было тут https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array <br>
 <br>
Be able to custom sorting for Array <br>
https://habr.com/ru/post/559944/ <br>
при sort() не возвращается новый массив, а мутирует текущий https://www.youtube.com/watch?v=NJZp4rU-kqw <br>
 <br>
Be able to filter Array elements <br>
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/filter <br>


    Know global scope and functional scope
    Know variables visibility areas
    Understand nested scopes and able work with them


    Know how to define Function parameters
    Know difference between parameters passing by value and by reference
    Know how to handle dynamic amount of Function parameters


    Function default parameters
    ECMA script modules
    Know how to use spread operator for Function arguments
    Be able to compare arguments and rest parameters
    Spread operator for Array
    Understand and able to use spread operator for Array concatenation Destructuring assignment
    Be able to discover destructuring assignment concept
    Understand variables and Function arguments destructuring assignment
    String templates
    Know how for..of loop works (optional)


    this scope
    Reference Type & losing this
    Understand difference between function and method
    Understand how this works, realize this possible issues
    Manage this scope
    Be able to replace this scope
    Be able to use call and apply Function built-in methods


    Immediately invoked functional expression (IIFE) (optional)
    Know IIFE pattern (optional)
    Callback (Function as argument)
    Know callback pattern
    Understand callback limitations (callback hell) (optional)
    Binding, binding one function twice
    Know how to bind this scope to function
    Carrying and partial functions


    Fetch (with usage)
    XMLHTTPRequest (concept) (optional)
    WebSocket (concept) (optional)


    Web components, shadow DOM (concept) (optional)


    Timezones (optional)
    Internationalization js (Intl) (optional)


    Context (lexical environment)
    Understand function creation context (lexical environment)
    Be able to explain difference between scope and context
    Inner/outer lexical environment
    Understand lexical environment traversing mechanism
    Understand connection between function and lexical environment


    new keyword
    Understand how new keyword works
    Function constructor
    Know function constructor concept
    Able to create constructor functions
    Public, private, static members
    Know how to create public members
    Know how to create private members
    Know how to create static members
    Understand OOP emulation patterns and conventions


    __proto__ property
    Understand __proto__ object property
    Able to use [Object.create] and define __proto__ explicitly
    Able to set / get object prototype (optional)
    prototype property
    Know function prototype property
    Understand dependency between function constructor prototype and instance __proto__
    Able to create 'class' methods using function prototype property


    Class declaration
    Know class declaration syntax
    Understand difference between class and constructor function
    Getter/setter
    What does super() do and where we have to use it?


    Object keys/values
    Object calculated props
    Set/Map data types
    WeakSet/WeakMap data types


    try..catch statement
    Know how to handle errors
    Custom errors (optional)


    Garbage collector (concept) (optional)
    Promises
    Promise states
    Promise Chaining
    Promise static methods
    Be able to compare promise and callback patterns (optional)
    Be able to handle errors in promises
    event loop
    async/await
