# Проект "Шахматы" — PPPI

![chess2](https://github.com/user-attachments/assets/2a9f23c2-e42a-4bd6-9cdb-d5a6957d0be5)

**Шахматы** — это классическая настольная игра, адаптированная в цифровую форму для учебного курса по программированию и игровому дизайну (ПППИ). Проект направлен на создание интерактивной платформы для игры в шахматы с возможностью одиночной и многопользовательской игры.

## Модули проекта

### 1. **Интерфейс пользователя (UI)**
   - Разработка главного меню:
     - Кнопки: "Новая игра", "Продолжить", "Настройки", "Выход".
   - Создание игрового интерфейса:
     - Отображение доски и фигур.
     - Индикация доступных ходов.
     - Панель статуса: текущий игрок, количество ходов, таймер.
   - Настройка экрана паузы:
     - Возможность сохранения партии.
     - Изменение параметров игры (время, сложность AI).

### 2. **Система управления**
   - Реализация выбора фигуры и выполнения хода:
     - Выделение выбранной фигуры.
     - Подсветка доступных клеток для перемещения.
   - Обработка ввода:
     - Поддержка мыши и клавиатуры для ПК.
     - Адаптация под сенсорные экраны для мобильных устройств.
   - Анимация ходов:
     - Плавное перемещение фигур.
     - Эффекты при захвате противника.

### 3. **Правила игры**
   - Реализация базовых правил:
     - Правильные движения каждой фигуры.
     - Ограничения на движение (например, пешки не могут двигаться назад).
   - Добавление специальных правил:
     - Рокировка.
     - Превращение пешки.
     - Взятие на проходе.
   - Определение окончания партии:
     - Шах и мат.
     - Пат.
     - Ничья.

### 4. **Искусственный интеллект (AI)**
   - Разработка уровня сложности:
     - Легкий: простые ходы без глубокого анализа.
     - Средний: использование базовых стратегий.
     - Сложный: продвинутый анализ ходов.
   - Реализация системы оценки позиции:
     - Расчет материального преимущества.
     - Анализ контроля центральных клеток.
     - Учет угроз для короля.

### 5. **Многопользовательский режим**
   - Реализация онлайн-игры:
     - Поиск соперника через лобби.
     - Игра по сети с использованием протоколов (например, WebSocket).
   - Сохранение истории партий:
     - Возможность просмотра предыдущих игр.
     - Экспорт партии в формат PGN.

### 6. **Графика и анимация**
   - Создание различных тем доски и фигур:
     - Классическая тема.
     - Темы фэнтези, научной фантастики и другие.
   - Добавление визуальных эффектов:
     - Блеск при выборе фигуры.
     - Анимация при взятии фигур.
   - Адаптация разрешения под различные устройства.

### 7. **Звуковое сопровождение**
   - Звуки ходов и захвата фигур.
   - Музыкальное оформление:
     - Фоновая музыка для меню и игры.
     - Эффекты при завершении партии.

### 8. **Система обучения**
   - Разработка обучающих модулей:
     - Уроки основных правил.
     - Тренировочные задания по тактике и стратегии.
   - Создание уровней сложности для новичков:
     - Подсказки для начинающих игроков.
     - Автоматическое выделение лучших ходов.

### 9. **Статистика и прогресс**
   - Отображение статистики игрока:
     - Общее количество побед и поражений.
     - Процент успешных партий.
   - Лидерборды:
     - Глобальные и локальные рейтинги игроков.
     - Возможность сравнения результатов с друзьями.

### 10. **Мультиплатформенная поддержка**
   - Адаптация управления:
     - Для ПК, консолей и мобильных устройств.
   - Оптимизация графики:
     - Учет характеристик разных устройств.
   - Тестирование на различных платформах:
     - Windows, macOS, Linux, Android, iOS.

### 11. **Тестирование и отладка**
   - Поиск и исправление багов:
     - Проверка корректности правил.
     - Тестирование AI на всех уровнях сложности.
   - Оптимизация производительности:
     - Ускорение расчетов AI.
     - Снижение нагрузки на систему.
   - Сбор отзывов от тестеров:
     - Внесение изменений на основе обратной связи.
