# API

Здесь вы можете увидеть как получать майнкрафт картинки с моего апи

## Получение по индетификатору
```
https://img.zaralx.ru/v1/minecraft/carrot
```
![Carrot](https://img.zaralx.ru/v1/minecraft/carrot "Carrot")

## Получение по категории

Категории:
- 1 armor
- 2 build_blocks
- 3 colored_blocks
- 4 eggs
- 5 food
- 6 functional_blocks
- 7 ingridients
- 8 tools
- 9 weapons
- 10 potions // Обратите внимание что цвет зелий указывается по порядковому номеру, например 10_splash_potion

Успешно:
```
https://img.zaralx.ru/v1/minecraft/armor/diamond_boots
```
![Diamond boots](https://img.zaralx.ru/v1/minecraft/armor/diamond_boots "Diamond boots")

Не успешно:
```
https://img.zaralx.ru/v1/minecraft/armor/carrot
```
![Carrot](https://img.zaralx.ru/v1/minecraft/armor/carrot "Carrot")

## JSON со всем.
```
https://img.zaralx.ru/v1/minecraft/list
```

Вид:
```json
{
  "minecraft_indentify": {
    "category_id": 1,
    "name": "Полное название предмета на русском"
  }
}
```
