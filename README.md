# Начинка для пирога: частота встречаемости ингредиентов в рецептах пирогов

![not loaded](http://brendkafe.ru/wp-content/uploads/c39fc5294aae326de0c7e3fdb37ba151.jpg)

  Пироги - одни из главный традиционных русских блюд. Издревле на Руси подчевали дорогих гостей разнообразными пирогами и пирожками - сладкими и солёными, закрытыми и открытыми, мясными и овощными. Впервые о пирогах в своих заметках упоминал известный немецкий путешественник Адам Олеарий. Он был поражен поразительным вкусом русских пирогов и их невероятным многообразием начинок.  Действительно, русская кухня отличается изобилием вкусов. Ни у одного народа не существует такого количества форм и вариантов пирогов, как в России. В начинку принято добавлять совершенно любые продукты, которыми только можно найти под рукой. 
  
  Опуская обширную предысторию развития и совершенствования рецептов пирогов, перейдём непосредственно к предмету проекта, коим является начинка. Преступая к выполнению проекты, мы задали себе вопросы, на которые вследствие пытались найти ответы: Какой ингредиент чаще всего встречается в рецептах? Какие сочетания продуктов самые популярные? Какие пироги наиболее распространёны в литературных произведениях? 
  
  Целью нашего проекта является сравнительный анализ начинок для пирогов и пирожков. Для работы мы использовали три иструмента: НКРЯ, Dephi, Voyant Tools.
  
**1.	Какой ингредиент чаще всего встречается в рецептах? (Voyant tools)**

Ссылка на работу: https://voyant-tools.org/?corpus=6641927f4db02a0cba71a2f4386dcad5

  В данной программе видно, что не одни яйца не являются самым распространенным продуктом: сахар встречается с такой же частотой (25 раз). Первые пять наиболее часто встречающихся в рецептах продуктов (сахар, яйца, сливочное масло, маргарин и корица) – это базовые продукты, обычно использующиеся для связывания основных ингредиентов начинки или усиления вкуса (т.е. приправы). Тоже самое можно наблюдать и в таблице коллокатов: самые часто встречающиеся пары продуктов – маргарин/сахар (20 раз), сахар/корица (14 раз), яйца/сахар (13 раз). Интересно, что в наименее часто встречающихся парах ингредиентов (1 раз) обязательным являются яйца, а вторые ингредиенты – обычно продукты, которые чаще едят как самостоятельное блюдо или которые бывают нечасто и не у всех.
  
**2.	Какие сочетания продуктов самые популярные? (Dephi)**

  На основе книги рецептов "Выпечка" нами было отобрано 67 рецептов пирогов и пирожков, после чего для были составлены "пары" - ингредиенты, встречающиеся в одном рецепте. Например, рецепт, влкючающий в себя ингредиенты «Капуста, яйца, масло сливочное» разбивался на три пары: капуста-яйца, капуста-масло сливочное, яйца-масло сливочное». Подобные пары выбирались из 67 рецептов, пары были подсчитаны, и на основе полученных данных был создан граф. Данный граф, представленный в другом репозитории (ссылка: https://guskovaas17.github.io/network_pirogi/), отражает связи между ингредиентами. 
  
  Можно заметить большую точку, к которой сходится большинство связей – самый частотный ингредиент – яйца. Они имеют 22 связи, то есть встречается в большинстве рецептов.
  
  Как отчетливо видно, на графе присутствуют разные цветовые группы: зеленая, синяя, серая, сиреневая, розовая, бирюзовая, оранжевая. Такое деление обусловлено связями между ингредиентами: группы отражают «ближайшее окружение», встречаемость в однотипных рецептах. Так, голубая и сиреневая группы представляет сладкие ингредиенты для пирогов, а зеленая и серая – несладкие. Иногда ингредиенты в рецептах сочетаются, поэтому видно, что при выявлении связей могут появляться ингредиенты из разных цветовых групп. 

**3.	Какие пироги наиболее распространёны в литературных произведениях? (НКРЯ)**



















проект делали: Гуськова Алена,Карпенюк Вероника, Солдатова Глафира

