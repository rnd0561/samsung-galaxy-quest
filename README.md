# Galaxy Quest - Samsung Training Game

Интерактивная игра-бродилка для изучения устройств Samsung Galaxy.

## Как играть

1. **Управление:**
   - Клавиши ← → или A/D - ходить
   - E или Пробел - взаимодействовать
   - На мобильных - используйте кнопки на экране

2. **Цель:**
   - Собирайте 3 кристалла знаний на каждом уровне
   - Каждый кристалл раскрывает одну из 3 главных "фишек" устройства
   - Пройдите тест, правильно назвав все 3 фишки
   - Переходите к следующему устройству!

## Размещение онлайн (GitHub Pages)

### Шаг 1: Создайте репозиторий на GitHub
1. Зайдите на github.com
2. Нажмите "New repository"
3. Назовите его например `samsung-game`
4. Сделайте его Public

### Шаг 2: Загрузите файлы
```bash
cd /Users/edgarseripov/Documents/games/samsung-training-game
git remote add origin https://github.com/YOUR_USERNAME/samsung-game.git
git branch -M main
git commit -m "Initial commit"
git push -u origin main
```

### Шаг 3: Включите GitHub Pages
1. В репозитории зайдите в Settings → Pages
2. Source: Deploy from a branch
3. Branch: main, folder: / (root)
4. Save

### Шаг 4: Готово!
Через 1-2 минуты игра будет доступна по адресу:
`https://YOUR_USERNAME.github.io/samsung-game/`

## Устройства в игре

- Galaxy A56, A36, A26, A17, A07
- Galaxy S25, S25+, S25 Ultra, S25 FE
- Galaxy Z Fold7, Z Flip7, Z Flip7 FE
- Galaxy Buds3 FE, Buds Core
- Galaxy Watch 8, Watch 8 Classic
- Galaxy Tab S11, S11 Ultra, S10 FE, S10 FE+, S10 Lite, A11+, A11

## Технологии

- Чистый HTML/CSS/JavaScript
- Работает на любом устройстве без установки
- Сохранение прогресса в LocalStorage
