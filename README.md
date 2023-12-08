# Projects
Здесь собраны некоторые реализованные проекты

| #    | Наименование проекта                | Описание                                                     | Стек                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1.   | [Создание дашборда по пользовательским событиям для агрегатора новостей](https://github.com/Andiva-1/Projects/blob/main/Dashboard/dashboard.ipynb) | Выполнена на удаленной машине в сервисе Yandex.Cloud, написан скрипт пайплайна, который через crontab позволил автоматизировать сбор данных за определенный временной период. Визуализация осуществлена в Tableau. | python, SQL, pandas, sqlalchemy, Tableau |
| 2.   | [Сегментация потребителей интернет-магазина товаров для дома и быта](https://github.com/Andiva-1/Projects/blob/main/Consumers_segmentation/Consumers_segmentation.ipynb) | Выполнена в Jupyter Notebook, также применён Tableau для создания дашборда со статистикой покупок по дням. С применением методов KMeans, dendrogram, linkage выявлены сегменты потребителей и сформулированы выводы и базовые рекомендации по применению выявленных сегментов в подготовке предложений клиентам, методом ttest_ind проверены статистические гипотезы о разнице среднего чека у выявленных групп. Предварительно проведена предобработка данных, их анализ и категоризация товаров по категориям. | python, pandas, numpy, requests, urllib.parse, matplotlib, sklearn.preprocessing, scipy.cluster.hierarchy, sklearn.cluster, scipy, Tableau |
| 3.   | [Анализ причин убытков интернет-сервиса](https://github.com/Andiva-1/Projects/blob/main/Business_indicators/Business_indicators.ipynb) |  Выполнена в Jupyter Notebook. Проведен анализ данных. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы функции расчёта метрик. | python, pandas, matplotlib, seaborn |
| 4.   | [Продвижение товаров Nilambari на онлайн-платформе Wildberries](Nilambari_analisis/README.md) | Выполнена с привлечением Excel, Word, Acrobat Reader. Проведен анализ сформированного отчета. Предложены варианты возможных действий по увеличению продаж. | Excel |
| 5.   | [Анализ вакансий на LinkedIn](LinkedIn/LinkedIn.ipynb) | Выполнена в Jupyter Notebook и Power BI. Визуализирована информация о Европейском рынке вакансий для специалиста в области анализа данных на материале социальной сети LinkedIn. Данные приведены в пригодный для анализа формат путём распарсивания html содержимого csv файла с помощью BS 4 и создания необходимых признаков. [Ссылка на дашборд в формате файла .pbix](LinkedIn/dashboard_linkedIn.pbix). [Ссылка на скриншот дашборда](LinkedIn/README.md) | python, pandas, bs4, BeautifulSoup, re, datetime, lxml, Power BI |
| 6.   | [Расчёт аналога числа Эрдёша — Бэйкона применительно к хоккеистам КХЛ](/Lemtyugov/Lemtyugov.ipynb) | Выполнена в Jupyter Notebook. Рассчитан аналог числа Эрдёша — Бэйкона для хоккеистов КХЛ. [Построен отчет с графами, отображающими связи между хоккеистами](/Lemtyugov/Visualization_and_General_Findings.md). Проверены некоторые гипотезы. | python, pandas, numpy, datetime, functools, reduce, networkx, locale, phik, seaborn, matplotlib, scipy.stats, probplot, holoviews, bokeh.io, bundle_graph |
| 7.   | [Cоздание дашборда по продажам для компании “Bolid.Team”](https://datalens.yandex/did7afoqzuck2) | Выполнена в DataLens. Cоздан дашборд, который позволяет анализировать продажи услуг аркадных аттракционов - как верхнеуровнево, так и в разрезе объектов и аттракционов. В демонстрационном варианте реальные данные заменены на синтетические. | DataLens
