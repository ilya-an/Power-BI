# Power-BI
Traffic and source analysis
## Маркетплейс услуг.
Закупаем два разных вида трафика: 
1) Клиенты - заказы от клиентов, которые ищут специалистов. 
2) Специалисты - регистрации специалистов, которые предлагают свои услуги.
## Описание проекта.
Задача - проанализировать данные Statistics и сделать краткие выводы по трафику и источникам. 
Сделайте выводы только по источникам с большим объемом трафика. 
## Описание данных.
- ID	номер заказа	
- Click Time	время когда был клик	
- Action Time	время когда был оформлен лид*	
- Website ID	номер источника трафика	
- Action Name	название действия 	
- Status	1 - одобрили лид и заплатили за него ; 2 - отклонили лид и не платили. 	
- Total Payment to webmaster	сколько заплатили за лид	
- Revenue доход 		
- Click Country		
- Action Country		
## Выводы.
1) Количество ID и Wevsite ID у которых Revenue>0 руб. равняется 22943 пользователя и/или вебсайта, их количество одинаковое. Total Payment на привлечение этих пользователей в равной пропорции составляет по 130 и по 104 рубля на одного пользователя, общий расход равен 2689609 руб.
2) Большинство пользователей, приносящих прибыль, пользуется смартфонами - 70%, примерно 28% используют компьютеры. Наиболее популярные бренды смартфонов: Samsung, Apple, Xiaomi, Honor, соответственно наиболее популярная операционная система - Android, наиболее популярный браузер - Chrome.
3) В понедельник наибольшее количество, прибыльных пользователей, совершает Action, наименьшее количество в субботу. Время высокой активности с 9:00 до 0:00, в период с 17:00 до 19:00 активность снижается. Март - самый прибыльный месяц. Между Click и Action: среднее время примерно 7 часов, а медианное время 37 минут. 
