# hw8
Чтобы удалить все пустые строки, я использовала регулярное выражение: (\s?\r\n){2,} и заменила все вхождения на: \r\n
![вот так](https://github.com/spacemuminsh/hw8/blob/master/gram1.png)
Чтобы найти и подсчитать всех князей и города, имя которых кончается на "слав", я использовала регулярное выражение: [А-Я]{1}[а-яѣ]*(слав)[а-яѣ]* Всего имен нашла 592
![а это так](https://github.com/spacemuminsh/hw8/blob/master/gram2.png)
Чтобы найти и подсчитать все вариации названия Новгорода, я использовала регулярное выражение: Нов[а-яѣ]город[а-яѣ] Всего упоминаний я нашла 58
![alt text](url)
