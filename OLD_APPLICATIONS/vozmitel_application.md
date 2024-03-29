# Возмитель Андрей - "Создание приложения "Решатель ЕГЭ 3000" "

# Группа: 10 - И - 4
# Электронная почта: vozmitel@yandex.ru
# VK: https://vk.com/id416391906

**[ НАЗВАНИЕ ПРОЕКТА ]**
Решатель ЕГЭ 3000

**[ ПРОБЛЕМНОЕ ПОЛЕ ]**
Проблема: В современные дни не у всех учеников находится время/желание для постоянной подготовки к ЕГЭ по выбранным предметам. Моё приложение поможет разобраться с самыми сложными заданиями/упражнениями (т.к. в большинстве своём ЕГЭ использует систему заданий, а также обращается к упражнениям по русскому как к заданиям, то я так же буду называть упражнения заданиями) ЕГЭ, укажет на основные слабости ученика в решении задач, поможет сохранить мотивацию для ежедневных/еженедельных тренировок по подготовке к ЕГЭ.

**[ ЗАКАЗЧИК / ПОТЕНЦИАЛЬНАЯ АУДИТОРИЯ ]**
Моё приложение как конечный продукт поможет множеству учеников подготовиться к ЕГЭ по русскому языку (с возможностью расширения для других предметов).

**[ АППАРАТНЫЕ ТРЕБОВАНИЯ ]** 
Моя программа будет максимально нетребовательной. Здесь указанны завышенные апаратные требования, на них стоит смотреть как на рекомендуемые.
* ОС: Windows 10
* Расширение экрана: 1920 x 1080 (в случае других расширений пользовательский интерфейс может работать некорректно)
* Процессор: Core i3
* Оперативная память: 1 GB ОЗУ
* Место на диске: 2 GB

**[ ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ ]**
Программный продукт будет предоставлять следующие возможности:
* Имплеменация входа/регистрации в аккаунт приложения
* Возможность изменения параметров игры (настройки)
* Возможность просмотра страниц других игроков
* Вкладка профиля в котором можно будет увидеть основные характеристики игрока (в чем он хорошо проявляет себя и над чем нужно поработать)
* Система "ачивок" (достижений)
* Имплементация уровней сложности для заданий
* Реализация системы выборов фонов
* Реализация системы кастомизации карточки игрока
* Система "анлоков" (открытие фонов/"аватарок" за выполнение заданий/внутриигровую валюту)
* Награды за ежедневный/еженедельный вход


**[ ПОХОЖИЕ / АНАЛОГИЧНЫЕ ПРОДУКТЫ ]**
https://yandex.ru/tutor/uroki/ege/russkij-yazyk/ - много задач для подготовки, но все задачи выполняются в браузере, нет возможности кастомизации, мало достижений, нельзя сравнить свой результат с остальными учениками
Castle Quiz https://clevver.me/#/subject/32 - интересное приложение выполненное в игровой форме. Однако в этом приложении есть два существенных недостатка: задания часто повторяются, что приводит к их заучиванию, для игры нужен еще один игрок, что не всегда возможно из-за низкой популярности сервиса, в нём нет обучающего материала, нет возможности кастомизации, мало достижений, нельзя сравнить свой результат с остальными учениками
Экзамер https://examer.ru - приложение котрое составляет личный план подготовки к ЕГЭ. Главная проблема - стоимость в 3299 рублей за предмет.



**[ ИНСТРУМЕНТЫ РАЗРАБОТКИ ]**
* Godot - Малопопулярный, но очень интересный своим функционалом игровой движок. На нём будет написана всё приложение
* Cyberglads - Аддон к godot. Облачный сервис, который позволит бесплатно интегрировать таблицу лидеров в моё приложение
* Photoshop - для отрисовки спрайтов приложения
* google sheets с аддоном на Json конвентер - за счет данного конвентера можно будет добавлять и изменять большое количество данных, легко просматривать все ключевые данные игроков
* Python - будет использоваться для получения данных для будущих заданий (для парсинга сайтов), которые потом будут редактироваться под формат json и загружаться в приложение

**[ ЭТАПЫ РАЗРАБОТКИ ]**
* Изучить основы движка "Godot"
* Поиск материалов по интересным способам решения задач
* Подключение парсера для получения данных
* Сортировка каждых заданий по уровням сложности
* Имплементирование регистрации в аккаунт приложения
* Реализация системы "ачивок"
* Реализация системы выборов фона/"аватарок"
* Добавление настроек
* Локализация
* Общая полировка и работа над чистотой UI
* Выдача продукта первым тестерам
* После получения обратной связи исправление ошибок для получения конечного продукта.

**[ ВОЗМОЖНЫЕ РИСКИ ]**
* Самые большие сложности будут лежать в работе над профилем аккаунта, он должен выглядеть одновременно ненагруженным и информативным.
* В случае недоступности беспланого сервера для проекта, сервером будет выступать мой компьютер, что в конечном итоге может вызвать некторые сложности с работой сервиса
* Процесс тестирования может затянуться, в таком случае проект не сможет достаточно точно определять среднее время решений заданий/ среднее количество ошибок, но это легко исправимо со временем, в момент защиты приложение уже сможет автоматически корректировать эти переменные с увеличением данных от игроков
