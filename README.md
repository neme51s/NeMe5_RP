# NeMe5 Resource Pack (Minecraft 26.3, LabPBR)

Четыре версии одного пака — выбирайте по мощности ПК:

| Папка | Разрешение | Размер |
|---|---|---|
| NeMe5_512 | 512x | ~930 МБ |
| NeMe5_256 | 256x | ~335 МБ |
| NeMe5_128 | 128x | ~120 МБ |
| NeMe5_64  | 64x  | ~70 МБ |

Minecraft видит паки только прямо в `resourcepacks`, поэтому репозиторий клонируется рядом,
а папки подключаются ссылками (Windows, cmd):

```
cd %APPDATA%\.minecraft
git clone https://github.com/neme51s/NeMe5_RP.git NeMe5_RP
mklink /J resourcepacks\NeMe5_512 NeMe5_RP\NeMe5_512
mklink /J resourcepacks\NeMe5_256 NeMe5_RP\NeMe5_256
mklink /J resourcepacks\NeMe5_128 NeMe5_RP\NeMe5_128
mklink /J resourcepacks\NeMe5_64  NeMe5_RP\NeMe5_64
```

Обновление: `cd %APPDATA%\.minecraft\NeMe5_RP && git pull`, затем F3+T в игре.
Нужны Iris + шейдер с LabPBR (Complementary), EMF/ETF для моделей мобов.
