Для анализа я выбрала гипотетическое лингвоспецифичное слово "печальный" и неспицифичное слово "шоколадный". Открыла параллельный корпус НКРЯ и англо-русский подкорус, чтобы посмотреть как выбранные мною слова переданы на английский язык: сколько моделей перевода, их частнотности и т.д. Все данные я заносила в таблицу excel, она загружена в репозиторий. Для наглядности некоторые данные я продублирую сюда.

Вот список моделей перевода слов "печальный" и "шоколадный"

### Печальный

| *_модель_* | *_частотность_* | 
|:------------- |:---------------:|
| sad/sad-looking/sadder | 18 | 
| mournful | 6 | 
| sorrowful/sorrow | 4| 
| melancholy | 4 |
| gloomily/gloom/gloomy | 4 | 
| dull | 2 | 
| misery | 1 | 
| triste | 1 | 
| unhappy | 1 | 
| dismal | 1 | 
| sullen | 1 | 
| dreary | 1 | 
| regretfully | 1 | 
| thoughtfully | 1 | 
| tearful | 1 | 
| deplorable | 1 | 
| wistful | 1 | 
| rueful | 1 | 
| painful | 1 | 
| plaintive | 1 | 
| dejected | 1 | 
| **_всего вхождений_** | **_53_** | 
| **_моделей_** |**_21_** | 

### Шоколадный

| *_Модель_*    | *_Частотность_*        | 
| :------------- |:------------------:| 
| Chocolate    | 13 | 
| **_вхождений_**    | **_13_** |   
| **_моделей_**      | **_1_**  |

![](https://github.com/MyNameIsMary/hw7/blob/master/%D0%BF%D0%B5%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D1%8B%D0%B9.PNG)
У слова печальный получилось 21 модель перевода. Слово "sad" и его однокоренные слова встречались наиболее часто, 18 раз. Это 34% от всех моделей перевода. На втором месте "mournful". Оно встретилось 6 раз. Разрыв между самой частотной моделью и второй по частотности довольно большой. Большинство моделей перевода встретилось лишь единожды. У слова "шоколадный" одна модель перевода -- "chocolate". 
 После того, как нашла все модели перевода, посчитала их частотность и количество вхождений, начала считать **_меры разброса моделей перевода_**. 
1. Отношение абсолютной частоты самой частотной модели перевода (F (Mmax)) к количеству различных моделей (NumM):
Печальный: 18 ( частотность слова sad)/21 (количество моделей) = 0,857142857
Шоколадный: 13/1= 13
***
2. средняя частота вхождений на одну модель (F (O)/NumM, где F (O) —  общее количество вхождений):
Печальный: 53 (вхождения)/21(модели)= 2,523809524
Шоколадный: 13/1= 13
***
3. Отношение абсолютной частоты самой частотной модели перевода к частоте второй (F (Mmax)/F (Msec)):
Печальный: 18( самая частотная модель)/ 6 ( вторая модель по частотности)= 3
У слова шоколадный одна модель перевода, эту формулу применить не могу.
***
4. Отношение абсолютной частоты самой частотной модели перевода к общему количеству вхождений (F (Mmax)/F (O)):
Печальный: 18(самая частотная модель)/53 (вхождения)= 0,339622642
Шоколадный: 13/13=1
***
## Вывод
Лингвоспецифичное слово -- слово, которое сложно перевести на другой язык. У этого слова существует несколько моделей перевода. Как правило, у лингвонеспецифичного слова одна модель перевода. В первой и второй формуле частотность и вхождения мы делим на количество моделей. Следовательо, чем больше моделей перевода, тем меньше получаетя результат. У лингвоспецифичного слова цифра будет меньше, чем у лингвонеспецифчного. Так, ответ в первой формуле у слова "печальный" 0,857142857, а у "шоколадный" -- 13. Вторая формула: 2,523809524 и 13 соответсвенно. Слово "шоколадный" -- лингвонеспецифичное слово. Его легко перевести, у него только одна модель. Как пишет Д. В. Сичинава, "Для  «лингвоспецифичного» слова (если  таковые  существуют) предполагается, что моделей перевода будет много, в среднем на каждую будет приходиться сравнительно немного контекстов, а частота самой частотной из них не будет  сильно  отличаться от остальных (и он будет занимать лишь небольшой процент от общего числа соответствий)." Для слова "печальный" моделей перевода действительно много (21), на одну в среднем приходится 2,5 контекста. Но самая частотная модель, слово "sad", занимает 34% от общего числа соответствий. Его частота 18, а частота следующего за ним слова -- 6, это не очень характерно для лингвоспецефичного слова, частота самой популярной модели не должна сильно разниться с остальными. Но все-таки слово "печальный" имеет больше совпадений с определением лингвоспецифичного слова, чем расхождений. Я также допускаю, что "печальный" может быть общим терминомм (umbrella term) для ряда наименований чувств, как у Сичинавы слово "страсть".
