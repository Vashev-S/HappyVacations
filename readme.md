# HappyVacations

Очень просто приложение для планирования отпусков в небольших командах.

----------------
Возможности:

* Календарь исключений праздничных и рабочих дней.

* Три вида дней отсутствия: Отпуск, донорские дни, отгул за свой счёт.

* Планирование в виде таблицы всей команды.

* Планирование индивидуальных отпусков на календаре.

* Подсчет отмеченных отпускных дней.

* Подсветка пересечений отпуска между сотрудниками одной роли\отдела.

* Расчет индекса зарплаты. См. описание ниже.

* Доступ по прямой ссылке без дополнительной авторизации.

-----

**Расчет индекса зарплаты**

Есть хитрости с тем, в какие месяца лучше не брать отпуск, чтобы не потерять в деньгах. Это зависит от того, как много рабочих и праздничных дней в том или ином месяце.

Общее правило такое: чем больше рабочих дней в месяце, тем выгоднее ходить в отпуск, вы не только не потеряете в общей оплате, а может даже и выиграете.

Давайте разберем на примере.

Предположим, что ваша зарплата составляет 1000 тугриков в месяц.

Возьмем за основу август 2023 года. В нем всего 31 день, из них 23 рабочих.

Подсчитаем стоимость одного рабочего дня - 1000 / 23 = 43,47 тугриков в день.

Предположим, вы решили взять отпуск на стандартные 2 недели (14 календарных дней), с 7 по 20 августа, значит вы отработаете в августе всего 13 дней.

Формула расчета ваших отпускных непростая, зависит от вашего среднего заработка за предшествующие 2 года, но для простоты мы будем считать, что вы не болели, зарплату вам не повышали и вы всегда получаете 1000 тугриков в месяц.

Стоимость одного дня отпуска считается по формуле Оклад / 29,3, значит вам выплатят отпускных 1000 / 29,3 * 14 = 487 тугрика.
Если у вас были повышения зарплаты, вы болели - тогда отпускные будут еще меньше. Если у вас были премии - тогда отпускные будут больше.

Зарплата за отработанные дни составит 1000 / 23 * 13 = 565 тугрика.

Суммарно за месяц вы получите 565 + 487 = 1053 тугрика.

Ваш заплатанный индекс = Суммарная выплата / оклад = 1053 / 1000 = 1,05. Индекс показывает, что взяв отпуск в августе, вы получите денег немного больше обычного.

Теперь возьмем месяц в котором мало рабочих дней, это январь 2023 года, в нем 31 календарный, но всего 17 рабочих.
Вы берете отпуск 14 календарных дней с 9 по 22 января, рабочих соответственно всего 7.

Отпускные - 1000 / 29,3 * 14 = 487 тугрика.

Зарплата - 1000 / 17 * 7 = 411 тугрика.

Суммарно за месяц вы получите 411 + 487 = 898 тугрика.

Ваш заплатанный индекс = Суммарная выплата / оклад = 898 / 1000 = 0,89. Здесь индекс показывает, что взяв отпуск в январе, вы получите существенно меньше обычного.

------

**Используемые компоненты, технологии, зависимости**

* https://www.fluentui-blazor.net/ - библиотека UI компонентов для Blazor

---------

**Запуск**

В консоли выполнить команду 

`dotnet run`

открыть браузер по адресу  http://localhost:5248/sdf323asdf/adacta