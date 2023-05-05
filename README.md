<!-- <h1 align="center">Aleo Workshop</h1> -->
<img alt="workshop" width="1412" src="./.resources/readme.png">
<h3 align="center">📜 Посібник для початківців з побудови ZK-додатків 📜</h3>

<p align="center">
    <a href="https://twitter.com/AleoHQ"><img src="https://img.shields.io/twitter/url/https/twitter.com/AleoHQ.svg?style=social&label=Follow%20%40AleoHQ"></a>
    <a href="https://aleo.org/discord"><img src="https://img.shields.io/discord/700454073459015690?logo=discord"/></a>
</p>

## Зміст
- [Посібник зі збірки](#посібник-зі-збірки)
    - [Передумови](#передумови)
    - [Встановлення](#встановлення)
- [Підтримка IDE](#підтримка-ide)
    - [VSCode](#vscode-рекомендовано)
    - [Sublime Text](#sublime-text)
    - [IntelliJ IDEA](#intellij-idea)
- [Огляд додатків](#огляд-додатків)
    - [🏛️ Аукціон ](#-аукціон) ([Джерело коду](./auction/))
    - [🏦 Базовий банк](#-базовий-банк) ([Джерело коду](./basic_bank/))
    - [🛳️ Морський бій](#-морський-бій) ([Джерело коду](./battleship/))
    - [⭕ Хрестики-нулики](#-хрестики-нулики) ([Джерело коду](./tictactoe/))
    - [🪙 Токен](#-токен) ([Джерело коду](./token))
    - [🗳️ Голосування](#-голосування) ([Джерело коду](./vote/))

## Посібник зі збірки

Наступні кроки допоможуть встановити Aleo та Leo на вашому комп'ютері. Цей практикум сумісний з macOS, Linux та Windows машинами.

### Передумови

Для цього практикуму потрібні такі умови.

- Встановіть `git` за посиланням [bit.ly/start-git](https://bit.ly/start-git)
- Встановіть `Rust` за посиланням [bit.ly/start-rust](https://bit.ly/start-rust)

### Встановлення

Щоб встановити Aleo та Leo, виконайте:
```
./install.sh
```

## Підтримка IDE

Для цього воркшопу потрібне одне з наведених нижче середовищ розробки (IDE).
- [VSCode](https://bit.ly/start-vscode)
- [Sublime Text](https://bit.ly/start-sublime)
- [IntelliJ IDEA](https://bit.ly/start-intellij)

### VSCode (Рекомендовано)

Почніть з встановлення `VSCode` за посиланням [bit.ly/start-vscode](https://bit.ly/start-vscode).

#### Далі, у VSCode, відкрийте **VSCode Marketplace**, введіть **Leo** у поле пошуку та встановіть плагін Leo.
![Leo VSCode](./.resources/leo-vscode.png)

### Sublime Text

<details><summary>Кроки встановлення</summary>

Почніть з встановлення `Sublime Text` за посиланням [bit.ly/start-sublime](https://bit.ly/start-sublime).

#### Далі, у Sublime Text, встановіть [Package Control](https://packagecontrol.io):
- На  Windows/Linux: `ctrl + shift + p`, введіть **Install Package Control**, та натисніть **Enter**.
- На  macOS: `cmd + shift + p`, введіть **Install Package Control**, та натисніть **Enter**.

#### Далі, У Sublime Text, встановіть [LSP](https://packagecontrol.io/packages/LSP):
- На Windows/Linux: `ctrl + shift + p`, виберіть **Package Control: Install Package**, введіть **LSP**, and press **Enter**.
- На macOS: `cmd + shift + p`, виберіть **Package Control: Install Package**, введіть **LSP**, та натисніть **Enter**.

#### Нарешті, у Sublime Text, встановіть [LSP-leo](https://packagecontrol.io/packages/LSP-leo):
- На Windows/Linux: `ctrl + shift + p`, виберіть **Package Control: Install Package**, введіть **LSP-leo**, та натисніть **Enter**.
- На macOS: `cmd + shift + p`, виберіть **Package Control: Install Package**, введіть **LSP-leo**, та натисніть **Enter**.

</details>

### IntelliJ IDEA

<details><summary>Кроки встановлення</summary>

Почніть з встановлення `IntelliJ IDEA` за посиланням [bit.ly/start-intellij](https://bit.ly/start-intellij).

#### Далі, у IntelliJ IDEA, відкрийте **IntelliJ Marketplace** та виберіть `Plugins`:
- На Windows/Linux: `ctrl + ,` та виберіть `Plugins` у бічній панелі зліва
- На macOS: `cmd + ,` та виберіть `Plugins` у бічній панелі зліва
Наостанок, введіть **Leo** у поле пошуку та встановіть офіційний плагін Leo.
</details>

## Огляд додатків

У цьому воркшопі розглядаються такі програми:
- [Аукціон](./auction/) - Перша цінова аукціонна торгівля в Leo
- [Простий банківський рахунок](./basic_bank/) - Простий банківський рахунок зі ставкою відсотка в Leo
- [Морський бій](./battleship/)-  Гра для двох гравців "Морський бій" в Leo
- [Гра в хрестики-нулики](./tictactoe/) - Стандартна гра в хрестики-нулики в Leo
- [Токен](./token) - Прозорий і захищений користувацький токен в Leo
- [Голосування](./vote/) - Приклад голосування за бюлетенем в Leo

### 🏛️ Аукціон

Перша цінова аукціонна торгівля в Leo.

Щоб побачити приклад аукціону, виконайте:
```
cd auction && ./run.sh
```

### 🏦 Простий банківський рахунок

Простий банківський рахунок зі ставкою відсотка в Leo.

Щоб побачити приклад простого банку, виконайте:
```
cd basic_bank && ./run.sh
```

### 🛳️ Морський бій

Гра для двох гравців "Морський бій" в Leo.

Щоб побачити гру "Морський бій" між двома гравцями, виконайте:
```
cd battleship && ./run.sh
```

### ⭕ Гра в хрестики-нулики

Стандартна гра в хрестики-нулики в Leo.

Щоб побачити гру в хрестики-нулики між двома гравцями, виконайте:
```
cd tictactoe && ./run.sh
```

### 🪙 Токен

Прозорий і захищений користувацький токен в Leo.

Щоб побачити приклад створення та переказу токенів, виконайте:
```
cd token && ./run.sh
```

### 🗳️ Голосування

Приклад голосування за бюлетенем в Leo.

Щоб побачити приклад голосувального бюлетеня, виконайте:
```
cd vote && ./run.sh
```
