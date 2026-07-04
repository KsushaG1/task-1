# 🚁 Helicopter Fire Fighter

A terminal-based Python game — pilot a helicopter, extinguish fires, and rack up points!

---

## 🎮 How to Play

Launch the game and control your helicopter with the keyboard:

| Key | Action |
|-----|--------|
| `W` | Move Up |
| `S` | Move Down |
| `A` | Move Left |
| `D` | Move Right |

**Goal:** fly over the map, collect water from the river, and extinguish burning trees. The more fires you put out, the higher your score. Use your points to upgrade your water tank at the shop.

---

## 🗺️ Map Legend

| Symbol | Description |
|--------|-------------|
| 🟩 | Empty field |
| 🌳 | Tree |
| 💧 | River — refills your water tank |
| 🔥 | Fire — fly here with water to extinguish |
| 🏪 | Shop — upgrades your tank for 500 points |
| 🏩 | Hospital |
| 🚁 | Your helicopter |

---

## ⚙️ Game Mechanics

- The water tank refills when flying over the **river** 💧
- Extinguishing a fire costs 1 unit of water and grants **+100 points** 🏆
- Every 75 ticks the old fires die out and new ones ignite 🔥
- Every 50 ticks a new tree grows on the map 🌳
- The **shop** 🏪 increases your maximum tank capacity for 500 points

---

## 🛠️ Tech Stack

- **Python 3.13**
- **pynput** — real-time keyboard input handling

---

## 🚀 Getting Started

```bash
pip install pynput
python main.py
```

> The game runs in the terminal. A fullscreen terminal window is recommended for the best experience.

---

## 📁 Project Structure

```
├── main.py         # Entry point, game loop
├── map.py          # Map, forest/river/fire generation
├── helicopter.py   # Helicopter class, movement, stats
└── utils.py        # Helper functions (random, coordinates)
```


# 🚁 Helicopter Fire Fighter

Консольная игра на Python — управляй вертолётом, туши пожары и зарабатывай очки!

---

## 🎮 Как играть

Запусти игру и управляй вертолётом с клавиатуры:

| Клавиша | Действие |
|---------|----------|
| `W` | Вверх |
| `S` | Вниз |
| `A` | Влево |
| `D` | Вправо |

**Цель:** летать над картой, набирать воду на реке и тушить горящие деревья. Чем больше пожаров потушишь — тем выше счёт. На заработанные очки можно улучшить бак вертолёта в магазине.

---

## 🗺️ Легенда карты

| Символ | Что это |
|--------|---------|
| 🟩 | Пустое поле |
| 🌳 | Дерево |
| 💧 | Река — здесь пополняется бак |
| 🔥 | Пожар — лети сюда с водой, чтобы потушить |
| 🏪 | Магазин — улучшает бак за 500 очков |
| 🏩 | Госпиталь |
| 🚁 | Твой вертолёт |

---

## ⚙️ Механики

- Бак вертолёта заполняется при пролёте над **рекой** 💧
- Тушение пожара тратит 1 единицу воды и даёт **+100 очков** 🏆
- Каждые 75 тиков старые пожары гаснут и вспыхивают новые 🔥
- Каждые 50 тиков на карте появляется новое дерево 🌳
- В **магазине** 🏪 за 500 очков увеличивается максимальный объём бака

---

## 🛠️ Стек

- **Python 3.13**
- **pynput** — перехват нажатий клавиатуры в реальном времени

---

## 🚀 Запуск

```bash
pip install pynput
python main.py
```

> Игра запускается в терминале. Рекомендуется запускать в полноэкранном терминале для лучшего отображения.

---

## 📁 Структура проекта

```
├── main.py         # Точка входа, игровой цикл
├── map.py          # Карта, генерация леса, реки, пожаров
├── helicopter.py   # Класс вертолёта, движение, статистика
└── utils.py        # Вспомогательные функции (рандом, координаты)
```
