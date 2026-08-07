```markdown
# 🎨 tac-utils

**Утилиты для консольных приложений от TAC (The Azda Company).**

Простой и удобный набор инструментов для создания красивых консольных приложений на Python.  
Цвета, стили, фоны, очистка экрана и пауза — всё в одном месте.

---

## 🚀 Установка

```bash
pip install tac-utils
```

---

## 📖 Использование

```python
from tac_utils import color

print(color.red("Ошибка!"))
print(color.green("Успешно!"))
print(color.bold_cyan("Жирный циан"))
print(color.bg_yellow("Жёлтый фон"))
```

---

## 🎨 Доступные цвета и стили

### Цвета текста
- `red`, `green`, `yellow`, `blue`, `magenta`, `cyan`, `white`

### Стили
- `bold` — жирный
- `italic` — курсив
- `underline` — подчёркнутый

### Фоны
- `bg_red`, `bg_green`, `bg_yellow`, `bg_blue`, `bg_magenta`, `bg_cyan`, `bg_white`

### Комбинации
- `bold_red`, `bold_green`, `bold_blue`, `bold_cyan` и т.д.
- `italic_red`, `italic_green`, `italic_blue` и т.д.
- `underline_red`, `underline_green`, `underline_blue` и т.д.

---

## 🧰 Дополнительные функции

```python
from tac_utils import clear, pause

clear()              # очищает экран терминала
pause()              # ожидает нажатия Enter
```

---

## 📝 Пример

```python
from tac_utils import color, clear, pause

clear()
print(color.bold_green("Добро пожаловать в TAC!"))
print(color.cyan("Это пример использования библиотеки tac-utils."))
print(color.yellow("Можно комбинировать стили и цвета."))
pause()
```

---

## 📄 Лицензия

Проект распространяется под лицензией **MIT**.  
Автор: **TheAzdaCode (TAC)**

---

## 🌐 Ссылки

- [Репозиторий на GitHub](https://github.com/TheAzdaCode/tac-utils)
- [Сайт TAC](https://theazdacompany.tilda.ws)
- [Автор на GitHub](https://github.com/TheAzdaCode)

---

**Сделано с ❤️ командой TAC**  
*The Azda Company — мы создаём, потому что нам интересно.*
```
