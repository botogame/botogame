# Программирование 

## Проект "Боевой континент 2 - схемокодер"

На заре цифровой эры, когда первые байты падали на землю подобно дождю, появился Схемокодер. Подобно мастерам боевых духов, каждый начинающий кодер должен был выбрать свой путь: слабые гибли в пустынных скриптах, другие навыки застревали в проклятом Notepad 6.66, где строки ломали разум, а отступы рвали душу.

Но истинные программисты кода знали: каждый модуль — это скилл, каждая библиотека — кольцо силы, которое нужно обуздать. Кто смог соединить их гармонией — поднимался выше, становясь Схемокодером.

![](./Картинки/bk2.png)

```python
# Боевой Кодекс Программиста python

class Programmer:
    def __init__(self, name):
        self.name = name
        self.skills = []
        self.rings = []
        self.level = 1

    def train_skill(self, skill):
        print(f"{self.name} постигает новый скилл: {skill}!")
        self.skills.append(skill)
        self.level += 1

    def absorb_ring(self, ring):
        print(f"{self.name} обуздал кольцо силы [{ring}]!")
        self.rings.append(ring)
        self.level += 2

    def status(self):
        print(f"⚔️ {self.name} | Уровень: {self.level}")
        print(f"Скиллы: {', '.join(self.skills) if self.skills else 'пусто'}")
        print(f"Кольца: {', '.join(self.rings) if self.rings else 'нет'}")

# Пример Пути
hero = Programmer("Тан Сань из IDE")
hero.train_skill("ООП")
hero.absorb_ring("NumPy")
hero.train_skill("Асинхронность")
hero.absorb_ring("TensorFlow")

hero.status()
```
⚡️ Каждая функция здесь — это медитация кода, каждое кольцо-библиотека даёт новые возможности, а слабые — сгорают, оставленные на дне ада редактора Notepad.

Настоящий программист знает: путь долог, но самосовершенствование в коде — это единственный способ достичь запределья Схемокодера.

-----------------------------------------------------------

Онлайн схемокодер реализовывается здесь: <a href="https://botogame.ru/circuit-coder/">https://botogame.ru/circuit-coder/</a>.

Пример составления html тэгов с вытавлением "class": <a href="https://www.youtube.com/watch?v=oW7JlXuVCf0" target="_blank">видос на ютуб</a>

Подписывайтесь на телеграмм <a href="https://t.me/pm_bdilka">https://t.me/pm_bdilka</a>

-----------------------------------------------------------

<h3>🐉 Первый скилл: «Память Массива» (PHP)</h3>

Описание:
Этот стиль программирования основан на том, что весь код хранится в одном массиве, который умеет "поглощать" новые переменные и использовать их. Программа больше не работает с обычными переменными напрямую — только через массив-память.

```php
<?php
// Создаем "кольцо памяти"
$program = [];

// Функция для записи переменной в память
function setVar(&$memory, $name, $value) {
    $memory[$name] = $value;
}

// Функция для чтения переменной
function getVar($memory, $name) {
    return $memory[$name] ?? null;
}

// Функция для "умения" — применение магии массива
function soulSkill(&$memory, $skill, $args = []) {
    switch ($skill) {
        case "add":
            return getVar($memory, $args[0]) + getVar($memory, $args[1]);
        case "multiply":
            return getVar($memory, $args[0]) * getVar($memory, $args[1]);
        case "concat":
            return getVar($memory, $args[0]) . getVar($memory, $args[1]);
        default:
            return "Неизвестное умение";
    }
}

// --- Демонстрация ---
// Загружаем переменные в массив-память (как души в кольца)
setVar($program, "x", 10);
setVar($program, "y", 7);
setVar($program, "msg", "Боевой континент ");

// Применяем навыки
echo "Сумма: " . soulSkill($program, "add", ["x", "y"]) . PHP_EOL;
echo "Произведение: " . soulSkill($program, "multiply", ["x", "y"]) . PHP_EOL;
echo "Слияние строк: " . soulSkill($program, "concat", ["msg", "y"]) . PHP_EOL;

```

