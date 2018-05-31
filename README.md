# hw9
**1) Удалить все пустые строки.**

1.Чтобы удалить все пустые строки, я использовала регулярное выражение \n\r и заменила на \0.

![](https://github.com/nastyakost/hw9/blob/master/%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%B5.JPG)

2. Для оставшихся пустых строк использовала регулярное выражение  \s*$, заменила на \0 и удалила пустые строки, в которых содержались пробелы.

![](https://github.com/nastyakost/hw9/blob/master/%D0%B2%D1%82%D1%82%D0%BE%D1%80%D0%BE%D0%B5.JPG)

**2) Найти всех князей и города, имя и название которых оканчивается на "слав". В выдаче должны быть такие слова как "Ярославля, Ростиславъ, Ростиславу, Переяславлъ" и т.п. Но не должно быть "славу, выславше" и т.п.**

1.Я использовала регулярное выражение [А-Я]+\w+слав+\w* , чтобы найти имена князей и города,  которые оканчивается на "слав"". У меня получилось 592 вхождения. 

![](https://github.com/nastyakost/hw9/blob/master/%D0%BD%D0%BE%D0%BC%D0%B5%D1%803.jpg)

**3)Найти все упоминания Новгорода.В выдаче должны быть такие слова как "Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду".**

1.Я использовала регулярное выражение Нов(.)?город[а-я|ѣ|* , чтобы найти все упоминания Новгорода в летописи. Получилось 59 вхождений. 

![](https://github.com/nastyakost/hw9/blob/master/%D0%BD%D0%BE%D0%B2%D0%B3%D0%BE%D1%80%D0%BE%D0%B4.JPG)

**Бонусное задание**

1.Для того чтобы выполнить бонусное задание, я использовала регулярное выражение ([.,;:!?](?![.>])), заменила на  (\1 ).

![](https://github.com/nastyakost/hw9/blob/master/%D0%B1%D0%BE%D0%BD%D1%83%D1%81.JPG)
