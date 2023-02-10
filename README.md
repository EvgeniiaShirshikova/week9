# week13

### Вопросы 💎

1. Какие бывают варианты объявления переменных?
   \\\ var, let, const:
   var устаревший аналог let;
   let позволяет менять значение переменной по ходу кода;
   const не позволяет менять значение, это постоянная величина
2. Как можно вывести сообщение "Hello World" с помощью JavaScript?

alert('Hello World');

3. Что выведет этот скрипт?

три уведомления по очереди:
hello 1;
hello name;
hello Ilya;

\\\можешь объяснить, почему очередность 2 и 3 не совпадает с порядком в коде?

4. Какое значение будет в _z_?

7

5. Какими тремя способами можно подключить JavaScript код?

Внутри другого тэга, например, button onclick ...., команда указывается внутри открывающего тэга;
через тэг script;
через отдельный файл, который подключается в конце body

6. Есть ли какая-то разница между записями `typeof str` и `typeof(str)`?

нет

7. Что вернет код?

   ```jsx
   function showX(x) {
     return x;
   }
   console.log(showX(28));
   ```

Я не понимаю этот вопрос. В уроке такого не было, нагуглить не удалось. В консоли будет 28, но логического смысла выражения я не поняла.

8. Какой результат будет у выражений ниже?

   ```jsx
   "" + 1 + 0; будет 10
   "" - 1 + 0; будет -1
   true + false; будет 1
   6 / "3"; будет 2
   "2" * "3"; будет 6
   4 + 5 + "px"; будет 9px
   "$" + 4 + 5; будет $45
   "4" - 2; будет 2
   "4px" - 2; будет NaN
   7 / 0; будет Infinity
   "  -9  " + 5; будет -9 5
   "  -9  " - 5; будет -14
   null + 1; будет 1
   undefined + 1; будет NaN
   " \t \n" - 2; будет -2
   ```

Я это все проверила в консоли. Но больше половины выражений непонятно.

9. Что будет в x?

   ```jsx
   x = 5;
   x = 2;
   console.log(x);
   ```

   будет 2

10. Что будет в x?

x = 5;
x -= 2;
console.log(x);

будет 3
