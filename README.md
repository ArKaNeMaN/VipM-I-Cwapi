# [VipM-I] Cwapi

Кастомное оружие из плагина [Custom Weapons API](https://github.com/ArKaNeMaN/amxx-CustomWeaponsAPI).

_Для работы требуется Custom Weapons API._

## Пример

```jsonc
{
    "Type": "Cwapi",

    "Name": "Vip_Ak47",
    "GiveType": "Replace"
}
```

## Параметры

- `Name`
  - Название оружия из CWAPI.
- `GiveType`
  - Тип выдачи оружия.
  - Доступные типы:
    - `Smart` - Для ножей заменить, для гранат добавить, для остального выбросить     текущее и выдать новое
    - `Append` или `Add` - Добавить к текущему в соответствующем слоте
    - `Replace` - Заменить оружие из соответствующего слота на новое
    - `Drop` - Выбросить текущее в соответствующем слоте и выдать новое
