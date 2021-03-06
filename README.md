## Тестовое задание Mагнит

### Датафреймы. Получить необходимые данные из датасета.

Источник данных: https://pastebin.com/b3QGeJ8f


Описание: Требуется скачать по ссылке предложенный датасет, загрузить его в датафрейм, подготовить и получить следующие данные:

1) Страны с максимальной и минимальной плотностью населения и их плотность
2) Число стран без береговой линии (coastline) и процент таких стран от общего числа стран
3) Регион, где меньше всего людей владеют телефонами (phones_per_1000 - количество людей, владеющих телефонами, на 1000 человек)
4) Список стран, у которых отсутствует показатель грамотности (literacy), и при этом численность населения страны (population) более 1млн человек
5) Топ 5 стран с самым низким показателем рождаемости (birthrate) по отношению к показателю смертности (deathrate)
6) Страны, в которых преобладает сельское хозяйство (agriculture) над промышленностью (industry) и сферой обслуживания (service) и при этом средний показатель миграции (net migration) по региону положительный

Результат выполнения: Jupyter Notebook с отображением результата каждого из пунктов

Основные библиотеки:
•	pandas – для работы с данными

Датасет скачал и преобразовал в формат `csv`. Файл `world_countries.csv`

### Установка

Установите Jupyter Notebook удобным для вас способом

#### Запуск

Для запуска и просмотра кода используйте файл `magnit.ipynb`.

Для удобства чтение и отображения результата добавил строки с выводом данных