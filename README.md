# Yandex-Data-Analysis
Курс обучения (6 мес) "Аналитик данных (Data Analyst)" by Yandex.ru (https://praktikum.yandex.ru/data-analyst/)
<hr>
1. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B8%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9_%D0%BE_%D0%BF%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B5_%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80.ipynb" target="blank" rel="noreferrer">Исследование объявлений о продаже квартир</a>

**Задача:** провести анализ рынка недвижимости Санкт-Петербурга, установить параметры, которые влияют на стоимость квартир. Результаты исследования будут использованы при разработке автоматизированной системы мониторинга аномалий и мошеннической деятельности.
<br>
**Исходные  данные:** архив объявлений сервиса Яндекс.Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Посчитаны значения параметров, которые могут влиять на стоимость квартир</li>
  <li>Проведен исследовательский анализ данных: изучены распределения значений параметров, построены диаграммы, матрицы корреляций</li>
  <li>Проанализировано влияние различных параметров на стоимость квартир</li>
  <li>Отдельно проведен анализ по объявлениям центральной части СПБ, сравнение с другими районами города</li>
  <li>Сформулированы выводы по результатам анализа</li>
</ul>
<hr>
2. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B8%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%BE%D0%B2_%D0%B4%D0%BB%D1%8F_%D1%82%D0%B5%D0%BB%D0%B5%D0%BA%D0%BE%D0%BC_%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8.ipynb" target="blank" rel="noreferrer">Определение перспективного тарифа для телеком компании</a>

**Задача:** заказчик анализа, федеральный оператор сотовой связи, хочет провести сравнительный анализ двух тарифных планов и выяснить, какой тариф более прибыльный. По результатам анализа планируется скорректировать рекламный бюджет.
<br>
Необходимо провести анализ на выборке клиентов. По данным 500 пользователей определить: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.
<br>
**Исходные  данные:** описание тарифных планов, данные пользователей, статистика по совершенным звонкам, отправленным sms сообщениям и информация о мобильном интернет трафике пользователей.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Посчитаны метрики для пользователей двух тарифных планов: число звонков, расход минут в месяц, число сообщений, объем трафика, выручка с пользователя</li>
  <li>Проведен исследовательский анализ данных: выявлены паттерны поведения пользователей разных тарифов, расчитаны стат. величины для метрик, построены диаграммы</li>
  <li>Сформулированы портреты типовых пользователей каждого из тарифов</li>
  <li>Статистическими методами проверены гипотезы  о различии выручки (ARPU) на разных тарифах и различии выручки с пользователей из разных регионов</li>
  <li>Сформулированы выводы и рекомендации по результатам анализа</li>
</ul>
<hr>
3. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B8%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D1%80%D1%8B%D0%BD%D0%BA%D0%B0_%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D1%85_%D0%B8%D0%B3%D1%80.ipynb" target="blank" rel="noreferrer">Определение закономерностей определяющих успешность компьютерной игры</a>

**Задача:** интернет-магазин, который продаёт по всему миру компьютерные игры, заказал исследование закономерностей определяющих успешность компьютерных игр. Анализ необходимо провести на данных из открытых источников: исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Также необходимо отработать алгоритмы работы с данными, которые позволят заказчику сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
<br>
**Исходные  данные:** статистика продаж компьютерных игр с 1980 года, оценки критиков, оценки игроков.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Проведен исследовательский анализ данных: определен период времени, на основе которого имеет смысл строить прогноз на будущие периоды, определена динамика изменения продаж игр для различных игровых платформ, выявлены паттерны поведения игроков, определены консоли/жанры - лидеры продаж.</li>
  <li>Для каждого региона составлен портрет типового покупателя</li>
  <li>Статистическими методами проверены гипотезы  о равенстве пользовательских рейтингов различных платформ, рейтингов игр различных жанров</li>
  <li>Сформулированы выводы и рекомендации по результатам анализа</li>
</ul>
<hr>

4. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0_%D0%B0%D0%B2%D0%B8%D0%B0%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8.ipynb" target="blank" rel="noreferrer">Аналитика в авиакомпании</a>

**Задача:** для авиакомпании выполняющей внутренние пассажирские авиаперевозки выполнить анализ выборки данных по полетам совершенным за период. Рассчитать требуемые метрики, выявить наиболее популярные маршруты и модели самолетов.
<br>
**Исходные  данные:** выборка по городам и рейсам авиакомпании за период, выборка по моделям самолетов из парка авиакомпании.  
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Рассчитаны метрики: число рейсов по городам, число рейсов по моделям самолетов</li>
  <li>Проведен исследовательский анализ данных: выявлены наиболее популярные маршруты и модели самолетов. Построены диаграммы. Выявлены зависимости, сформулированы предположения о возможных причинах появления таких зависимостей</li>
  <li>Сформулированы выводы и рекомендации по результатам анализа</li>
</ul>
<hr>

5. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0_%D0%B4%D0%BB%D1%8F_%D1%8F%D0%BD%D0%B4%D0%B5%D0%BA%D1%81_%D0%B0%D1%84%D0%B8%D1%88%D0%B8.ipynb" target="blank" rel="noreferrer">Аналитика в Яндекс.Афише</a>

**Задача:** провести анализ пользовательской активности, изучить unit-экономику, изучить расходы на маркетинг и окупаемость расходов (ROI). Сформулировать рекомендации по использованию каналов привлечения пользователей и планированию маркетинговых бюджетов.
<br>
**Исходные  данные:** логи посещения сайта, выборка по заказам, выборка по расходам на маркетинг.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Выполнено изучение продукта и пользовательской активности. Рассчитаны метрики описывающие использование продукта пользователями и паттерны поведения пользователей. Построены сравнительные диаграммы и распределения</li>
  <li>Построены когорты пользователей, рассчитаны метрики для когорт. Построены диаграммы</li>
  <li>Выполнены расчеты unit-экономики пользователей, рассчитан LTV</li>
  <li>Изучены расходы на привлечение пользователей в разрезе каналов привлечения, рассчитан ROMI для каналов и когорт пользователей,  построены диаграммы</li>
  <li>Сформулированы выводы и рекомендации по результатам анализа</li>
</ul>
<hr>
6. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%BF%D1%80%D0%B8%D0%BE%D1%80%D0%B8%D1%82%D0%B5%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_%D0%B3%D0%B8%D0%BF%D0%BE%D1%82%D0%B5%D0%B7.ipynb" target="blank" rel="noreferrer">Приоритезация гипотез и анализ A/B теста</a>

**Задача:** автоматизировать приоритезацию задач бэклога по методологиям ICE, RICE. Проверить результаты A/B теста для интернет-магазина, сформулировать выводы.
<br>
**Исходные  данные:** выборки по заказам и посетителям сайта магазина за период проведения теста.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Релизован алгоритм оценки и сортировки бэклога задач методами ICE, RICE. Проведено сравнение двух методов</li>
  <li>Выполнен анализ результата A/B теста: построены графики кумулятивной выручки, среднего чека и конверсии по группам покупателей из теста, посчитаны относительные изменения куммулятивных метрик по группам,  </li>
  <li>Посчитана статистическая значимость различий метрик по группам теста</li>  
  <li>Сформулированы выводы по результатам A/B теста</li>
</ul>
<hr>
7. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0_%D1%80%D1%8B%D0%BD%D0%BE%D0%BA_%D0%BE%D0%B1%D1%89%D0%B5%D0%BF%D0%B8%D1%82%D0%B0_%D0%BC%D0%BE%D1%81%D0%BA%D0%B2%D1%8B.ipynb" target="blank" rel="noreferrer">Рынок заведений общественного питания Москвы</a>

**Задача:** исследовать рынок общественного питания Москвы. Определить локации в городе с наибольшим/наименьшим числом объектов питания. Сформулировать рекомендации по формату и выбору места (района) в городе для открытия нового кафе.  
<br>
**Исходные  данные:** открытые данные о заведениях общественного питания в Москве, адресная информация из открытых источников.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Для заведений общепита определен район города, в котором находится заведение, для дальнейшего анализа в разрезе районов города</li>
  <li>Проведен сравнительный анализ: по типам объектов питания, по числу посадочных мест. Построены графики</li>
  <li>Выявлены характерные отличия сетевых заведений</li>
  <li>Проведен анализ локаций, выявлены наиболее/наименее популяные районы и улицы города. Выявлены характерные особенности заведений в популярных локациях</li>
  <li>Сформулированы выводы и рекомендации по формату, числу посадочных мест и расположению нового кафе</li>
</ul>

<hr>
8. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0_%D1%81%D1%82%D0%B0%D1%80%D1%82%D0%B0%D0%BF_%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D1%8B_%D0%BF%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D1%8F.ipynb" target="blank" rel="noreferrer">Стартап по продаже продуктов питания</a>

**Задача:**  сервис по доставке продуктов питания заказал исследование поведения пользователей мобильного приложения.
<br>
**Исходные  данные:** лог действий пользователей приложения
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Построена воронка событий, выполнен анализ, рассчитаны конверсии по шагам воронки. Построена визуализация воронки</li>
  <li>Выполнен анализ результата A/A/B теста. По результатам A/A теста проверен механизм проведения теста</li>
  <li>По результатам A/B теста посчитана статистическая значимость различий метрик по группам теста. Сделан вывод о влиянии изменений на конверсию по шагам воронки</li>
  <li>Сформулированы выводы и рекомендации по результатам анализа</li>
</ul>
<hr>
9. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0_%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2_%D1%81%D0%B5%D1%82%D0%B8_%D1%84%D0%B8%D1%82%D0%BD%D0%B5%D1%81_%D0%BA%D0%BB%D1%83%D0%B1%D0%BE%D0%B2.ipynb" target="blank" rel="noreferrer">Прогнозироание оттока клиентов сети фитнес-клубов</a>

**Задача:** разработать модель предсказания оттока клиентов сети фитнес-клубов. Сформировать портреты типовых клиентов, выявить характерные признаки. Выявить признаки влияющие на отток наиболее сильно. Сформировать целевые группы клиентов, предложить меры по снижению оттока в каждой из групп.
<br>
**Исходные  данные:** выборка по клиентам, истории оттока за предыдущие периоды, лог посещений фитнес-клубов, история покупок клиентов.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Проведен исследовательский анализ данных: выявлены признаки клиентов для модели прогнозирования, изучены распределения значений признаков и взаимосвязи признаков (матрица корреляции). Построены гистограммы</li>
  <li>Построена модель бинарной классификации клиентов с целевым признаком - отток. Выполнено сравнение нескольких моделей, выбрана оптимальная</li>
  <li>Выполнена кластеризация пользователей, построена дендрограмма, определено целевое число кластеров</li>
  <li>Выявлены характерные черты каждого из кластеров</li>
  <li>Предложены рекомендации по работе с каждым из кластеров</li>
  <li>Сформулированы выводы и рекомендации по результатам анализа</li>
</ul>
<hr>
10. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7_%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0_%D1%87%D1%82%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BA%D0%BD%D0%B8%D0%B3_%D0%BF%D0%BE_%D0%BF%D0%BE%D0%B4%D0%BF%D0%B8%D1%81%D0%BA%D0%B5.ipynb" target="blank" rel="noreferrer">SQL. Анализ базы данных сервиса для чтения книг по подписке</a>

**Задача:** Проанализировать базу данных сервиса для чтения книг по подписке - информацию о книгах, издательствах, авторах, а также пользовательские обзоры книг.
<br>
**Результаты исследования:** написаны sql запросы для получения выборок согласно условиям задачи.
<hr>
11. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B0_ab_%D1%82%D0%B5%D1%81%D1%82%D0%B0.ipynb" target="blank" rel="noreferrer">Финальный проект. A/B тест. Проверка результатов теста</a>

**Задача:** Оценить корректность проведения теста включая время проведения теста и аудиторию теста. Провести анализ результатов теста.
<br>
**Исходные  данные:** лог регистрации пользователей, лог действий пользователей, календарь маркетинговых активностей, выборка по участникам теста.
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Проведен исследовательский анализ данных: проверка корректности распределения участников на группы, проверка распределения событий в контрольной и тестовой группе, построены диаграммы</li>
  <li>Построена воронка, посчитана конверсия (абсолютная, относительная)</li>
  <li>Статистическими методами проверена гипотеза о равенстве долей для этапов воронки</li>
  <li>Сформулированы выводы о корректности проведения теста и результатах A/B теста</li>
</ul>
<hr>
12. <a href="https://github.com/kolevatov/Yandex-Data-Analysis/blob/main/%D0%B2%D1%8B%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D0%B5%D0%B9_%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_ecomm.ipynb" target="blank" rel="noreferrer">Финальный проект. E-commerce — Выявление профилей потребления</a>

**Задача:** выделить метрики, которые описывают поведение покупателей и профили потребления. Провести анализ метрик, построить диаграммы. Выполнить сегментацию покупателей для проведения маркетинговых активностей, сформулировать выводы и рекомендации.
<br>
**Исходные  данные:** выборка по заказам за период
<br>
**Результаты исследования:**
<ul>
  <li>Выполнена предобработка данных: удаление некорректных данных, проверка на дубликаты, исключение выбросов, обработка пропусков в данных</li>
  <li>Проведен исследовательский анализ данных: выделены метрики описывающие поведение отдельного покупателя и метрики описывающие продажи магазина в целом. Проведен анализ распределения значений метрик, построены диаграммы. Проведен первичный анализ unit-экономики магазина</li>
  <li>Выделены признаки для дальнейшей сегментации покупателей, проверены распределения значений признаков, построена матрица корреляций признаков. Определено оптимальное число сегментов</li>
  <li>Выполнена сегментация покупателей</li>
  <li>Статистическими методами проверены гипотезы о поведении покупателей</li>
  <li>Сформулированы выводы: паттерны поведения покупателей и профили потребления. Описаны сегменты и рекомендации по работе с сегментами. Выводы по результатам проверки гипотез</li>
</ul>
<hr>
