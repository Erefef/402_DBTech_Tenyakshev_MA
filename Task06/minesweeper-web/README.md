# Minesweeper (Сапёр)

## Описание проекта

Это современная веб-версия игры "Сапёр" (Minesweeper), созданная на JavaScript с использованием базы данных **IndexedDB** для хранения результатов игр. Проект предоставляет возможность играть в "Сапёр" прямо в браузере, а также сохранять и просматривать историю партий.

Цель игры — открыть все ячейки, не содержащие мин. Если игрок откроет ячейку с миной, он проигрывает. Открытые безопасные ячейки отображают количество мин в соседних клетках.

---

## Правила игры

- Игрок выбирает ячейки на игровом поле, стараясь не открыть мину.
- Если мина открыта, игра завершится с поражением.
- Если мины нет, ячейка показывает количество соседних мин.
- Ячейки без соседних мин автоматически открывают область безопасных клеток.
- Победа достигается, когда все безопасные ячейки открыты.

---

## Возможности

1. **Настройка параметров игры**:  
   - Размеры поля и количество мин задаются перед началом игры.

2. **Сохранение данных**:  
   - Все игры автоматически сохраняются в IndexedDB (локальная база данных браузера).

3. **Просмотр истории игр**:  
   - Возможность увидеть список завершённых игр с датой, результатом и параметрами.

4. **Повтор игр**:  
   - Воспроизведение сохранённых партий для анализа ходов.

---

## Игровой процесс

### Начало игры

1. Введите имя игрока.
2. Настройте параметры игры: размеры поля (ширина и высота) и количество мин.
3. Нажмите "Start Game" для начала новой игры.

### Геймплей

- Щёлкайте по ячейкам, чтобы их открыть.
- Используйте правый клик для установки флага на подозрительную ячейку.
- Побеждайте, избегая мин и открывая безопасные клетки.

---

## Установка и запуск проекта

### Локальный запуск

1. **Склонируйте репозиторий**:
   ```bash
   git clone https://github.com/Erefef/minesweeper-web.git
   
2. **Перейдите в папку проекта**:

```bash
cd minesweeper
```
3. **Откройте файл index.html в вашем браузере**: 
    Просто откройте файл index.html, чтобы начать игру.

4. **Запуск через GitHub Pages**:
Проект доступен онлайн через GitHub Pages:
[Играть в Minesweeper](https://erefef.github.io/minesweeper-web/)

## Технические требования
- Современный браузер с поддержкой IndexedDB (например, Chrome, Firefox, Edge).
- Подключение к интернету не требуется после первой загрузки игры.
## Примечания
- Сохранённые игры остаются в вашем браузере, пока вы не очистите локальные данные.
- Для обновления проекта просто загрузите последнюю версию репозитория.
## Ссылки
[GitHub Репозиторий](https://github.com/Erefef/minesweeper-web)
[Играть через GitHub Pages](https://erefef.github.io/minesweeper-web/)
