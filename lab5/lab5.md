# Лабораторная работа №5. Выделение признаков символов

## Вариант 9: Сингальский алфавит

#### Генерация эталонных изображений символов

**Параметры генерации:**
- Цвет символа: чёрный (0, 0, 0, 255)
- Фон: прозрачный (255, 255, 255, 0)

---

### 1. Эталонные изображения символов (полный список)

| № | Символ | Название | Unicode | Размер (px) | Изображение |
|:-:|:------:|:---------|:-------:|:-----------:|:-----------:|
| 1 | අ | Ayanna | U+0D85 | 95×139 | ![අ](sinhala_chars/0D85_අ.png) |
| 2 | ආ | Aayanna | U+0D86 | 156×139 | ![ආ](sinhala_chars/0D86_ආ.png) |
| 3 | ඇ | Aeyanna | U+0D87 | 155×139 | ![ඇ](sinhala_chars/0D87_ඇ.png) |
| 4 | ඈ | Aeeyanna | U+0D88 | 155×139 | ![ඈ](sinhala_chars/0D88_ඈ.png) |
| 5 | ඉ | Iyanna | U+0D89 | 100×119 | ![ඉ](sinhala_chars/0D89_ඉ.png) |
| 6 | ඊ | Iiyanna | U+0D8A | 95×135 | ![ඊ](sinhala_chars/0D8A_ඊ.png) |
| 7 | උ | Uyanna | U+0D8B | 120×119 | ![උ](sinhala_chars/0D8B_උ.png) |
| 8 | ඌ | Uuyanna | U+0D8C | 183×113 | ![ඌ](sinhala_chars/0D8C_ඌ.png) |
| 9 | ඍ | Iruyanna | U+0D8D | 172×87 | ![ඍ](sinhala_chars/0D8D_ඍ.png) |
| 10 | ඎ | Iruuyanna | U+0D8E | 176×66 | ![ඎ](sinhala_chars/0D8E_ඎ.png) |
| 11 | ඏ | Iluyanna | U+0D8F | 127×87 | ![ඏ](sinhala_chars/0D8F_ඏ.png) |
| 12 | ඐ | Iluuyanna | U+0D90 | 177×74 | ![ඐ](sinhala_chars/0D90_ඐ.png) |
| 13 | එ | Eyanna | U+0D91 | 103×119 | ![එ](sinhala_chars/0D91_එ.png) |
| 14 | ඒ | Eeyanna | U+0D92 | 118×135 | ![ඒ](sinhala_chars/0D92_ඒ.png) |
| 15 | ඓ | Aiyanna | U+0D93 | 177×96 | ![ඓ](sinhala_chars/0D93_ඓ.png) |
| 16 | ඔ | Oyanna | U+0D94 | 111×119 | ![ඔ](sinhala_chars/0D94_ඔ.png) |
| 17 | ඕ | Ooyanna | U+0D95 | 111×119 | ![ඕ](sinhala_chars/0D95_ඕ.png) |
| 18 | ඖ | Auyanna | U+0D96 | 182×113 | ![ඖ](sinhala_chars/0D96_ඖ.png) |
| 19 | ක | Alpapraana Kayanna | U+0D9A | 142×87 | ![ක](sinhala_chars/0D9A_ක.png) |
| 20 | ඛ | Mahaapraana Kayanna | U+0D9B | 111×125 | ![ඛ](sinhala_chars/0D9B_ඛ.png) |
| 21 | ග | Alpapraana Gayanna | U+0D9C | 110×87 | ![ග](sinhala_chars/0D9C_ග.png) |
| 22 | ඝ | Mahaapraana Gayanna | U+0D9D | 113×87 | ![ඝ](sinhala_chars/0D9D_ඝ.png) |
| 23 | ඞ | Kantaja Naasikyaya | U+0D9E | 115×119 | ![ඞ](sinhala_chars/0D9E_ඞ.png) |
| 24 | ඟ | Sanyaka Gayanna | U+0D9F | 124×87 | ![ඟ](sinhala_chars/0D9F_ඟ.png) |
| 25 | ච | Alpapraana Cayanna | U+0DA0 | 103×119 | ![ච](sinhala_chars/0DA0_ච.png) |
| 26 | ඡ | Mahaapraana Cayanna | U+0DA1 | 105×119 | ![ඡ](sinhala_chars/0DA1_ඡ.png) |
| 27 | ජ | Alpapraana Jayanna | U+0DA2 | 106×120 | ![ජ](sinhala_chars/0DA2_ජ.png) |
| 28 | ඣ | Mahaapraana Jayanna | U+0DA3 | 176×101 | ![ඣ](sinhala_chars/0DA3_ඣ.png) |
| 29 | ඤ | Taaluja Naasikyaya | U+0DA4 | 179×136 | ![ඤ](sinhala_chars/0DA4_ඤ.png) |
| 30 | ට | Alpapraana Ttayanna | U+0DA7 | 104×119 | ![ට](sinhala_chars/0DA7_ට.png) |
| 31 | ඨ | Mahaapraana Ttayanna | U+0DA8 | 111×119 | ![ඨ](sinhala_chars/0DA8_ඨ.png) |
| 32 | ඩ | Alpapraana Ddayanna | U+0DA9 | 114×119 | ![ඩ](sinhala_chars/0DA9_ඩ.png) |
| 33 | ඪ | Mahaapraana Ddayanna | U+0DAA | 114×119 | ![ඪ](sinhala_chars/0DAA_ඪ.png) |
| 34 | ණ | Muurdhaja Nayanna | U+0DAB | 172×102 | ![ණ](sinhala_chars/0DAB_ණ.png) |
| 35 | ඬ | Sanyaka Ddayanna | U+0DAC | 111×119 | ![ඬ](sinhala_chars/0DAC_ඬ.png) |
| 36 | ත | Alpapraana Tayanna | U+0DAD | 120×87 | ![ත](sinhala_chars/0DAD_ත.png) |
| 37 | ථ | Mahaapraana Tayanna | U+0DAE | 111×119 | ![ථ](sinhala_chars/0DAE_ථ.png) |
| 38 | ද | Alpapraana Dayanna | U+0DAF | 70×136 | ![ද](sinhala_chars/0DAF_ද.png) |
| 39 | ධ | Mahaapraana Dayanna | U+0DB0 | 111×119 | ![ධ](sinhala_chars/0DB0_ධ.png) |
| 40 | න | Dantaja Nayanna | U+0DB1 | 147×87 | ![න](sinhala_chars/0DB1_න.png) |
| 41 | ඳ | Sanyaka Dayanna | U+0DB3 | 90×136 | ![ඳ](sinhala_chars/0DB3_ඳ.png) |
| 42 | ප | Alpapraana Payanna | U+0DB4 | 100×87 | ![ප](sinhala_chars/0DB4_ප.png) |
| 43 | ඵ | Mahaapraana Payanna | U+0DB5 | 100×119 | ![ඵ](sinhala_chars/0DB5_ඵ.png) |
| 44 | බ | Alpapraana Bayanna | U+0DB6 | 111×119 | ![බ](sinhala_chars/0DB6_බ.png) |
| 45 | භ | Mahaapraana Bayanna | U+0DB7 | 115×87 | ![භ](sinhala_chars/0DB7_භ.png) |
| 46 | ම | Mayanna | U+0DB8 | 111×119 | ![ම](sinhala_chars/0DB8_ම.png) |
| 47 | ඹ | Amba Bayanna | U+0DB9 | 110×119 | ![ඹ](sinhala_chars/0DB9_ඹ.png) |
| 48 | ය | Yayanna | U+0DBA | 110×87 | ![ය](sinhala_chars/0DBA_ය.png) |
| 49 | ර | Rayanna | U+0DBB | 97×123 | ![ර](sinhala_chars/0DBB_ර.png) |
| 50 | ල | Dantaja Layanna | U+0DBD | 121×119 | ![ල](sinhala_chars/0DBD_ල.png) |
| 51 | ව | Vayanna | U+0DC0 | 100×119 | ![ව](sinhala_chars/0DC0_ව.png) |
| 52 | ළ | Muurdhaja Layanna | U+0DC5 | 121×119 | ![ළ](sinhala_chars/0DC5_ළ.png) |
| 53 | ශ | Taaluja Sayanna | U+0DC1 | 110×87 | ![ශ](sinhala_chars/0DC1_ශ.png) |
| 54 | ෂ | Muurdhaja Sayanna | U+0DC2 | 100×87 | ![ෂ](sinhala_chars/0DC2_ෂ.png) |
| 55 | ස | Dantaja Sayanna | U+0DC3 | 113×87 | ![ස](sinhala_chars/0DC3_ස.png) |
| 56 | හ | Hayanna | U+0DC4 | 114×87 | ![හ](sinhala_chars/0DC4_හ.png) |
| 57 | ෆ | Fayanna | U+0DC6 | 110×78 | ![ෆ](sinhala_chars/0DC6_ෆ.png) |
| 58 | ් | Ал-лакуна | U+0DCA | 33×66 | ![්](sinhala_chars/0DCA_්.png) |
| 59 | ා | Аела-пилла | U+0DCF | 54×75 | ![ා](sinhala_chars/0DCF_ා.png) |
| 60 | ැ | Кетти аеда-пилла | U+0DD0 | 57×93 | ![ැ](sinhala_chars/0DD0_ැ.png) |
| 61 | ෑ | Дига аеда-пилла | U+0DD1 | 57×94 | ![ෑ](sinhala_chars/0DD1_ෑ.png) |
| 62 | ි | Кетти ис-пилла | U+0DD2 | 97×51 | ![ි](sinhala_chars/0DD2_ි.png) |
| 63 | ී | Дига ис-пилла | U+0DD3 | 98×53 | ![ී](sinhala_chars/0DD3_ී.png) |
| 64 | ු | Кетти паа-пилла | U+0DD4 | 109×75 | ![ු](sinhala_chars/0DD4_ු.png) |
| 65 | ූ | Дига паа-пилла | U+0DD6 | 109×77 | ![ූ](sinhala_chars/0DD6_ූ.png) |
| 66 | ෘ | Гаетта-пилла | U+0DD8 | 54×75 | ![ෘ](sinhala_chars/0DD8_ෘ.png) |
| 67 | ෙ | Комбува | U+0DD9 | 109×87 | ![ෙ](sinhala_chars/0DD9_ෙ.png) |
| 68 | ේ | Дига комбува | U+0DDA | 163×135 | ![ේ](sinhala_chars/0DDA_ේ.png) |
| 69 | ෛ | Комбу дека | U+0DDB | 185×70 | ![ෛ](sinhala_chars/0DDB_ෛ.png) |
| 70 | ො | Комбува хаа аела-пилла | U+0DDC | 169×87 | ![ො](sinhala_chars/0DDC_ො.png) |
| 71 | ෝ | Комбува хаа дига аела-пилла | U+0DDD | 183×122 | ![ෝ](sinhala_chars/0DDD_ෝ.png) |
| 72 | ෞ | Комбува хаа гаянутитта | U+0DDE | 176×79 | ![ෞ](sinhala_chars/0DDE_ෞ.png) |
| 73 | ෟ | Гаянуктитта | U+0DDF | 74×76 | ![ෟ](sinhala_chars/0DDF_ෟ.png) |
| 74 | ෲ | Дига гаетта-пилла | U+0DF2 | 116×75 | ![ෲ](sinhala_chars/0DF2_ෲ.png) |
| 75 | ෳ | Дига гаяануктитта | U+0DF3 | 74×76 | ![ෳ](sinhala_chars/0DF3_ෳ.png) |
| 76 | ෴ | Кунддалия | U+0DF4 | 172×66 | ![෴](sinhala_chars/0DF4_෴.png) |

---

### 2. Рассчитанные признаки

Для каждого символа рассчитываются следующие признаки:

#### 2.1. Вес чёрного каждой четверти

Изображение символа делится на 4 равные четверти, для каждой вычисляется сумма чёрных пикселей.

#### 2.2. Удельный вес четвертей

Вес каждой четверти нормируется на площадь четверти:

$$\text{weight}_{rel} = \frac{\text{weight}_{quarter}}{\text{area}_{quarter}}$$

#### 2.3. Координаты центра тяжести

Абсолютные координаты центра тяжести символа:

$$\bar{x} = \frac{1}{W}\sum_{x=0}^{W-1}\sum_{y=0}^{H-1} x \cdot f(x,y) \quad \bar{y} = \frac{1}{W}\sum_{x=0}^{W-1}\sum_{y=0}^{H-1} y \cdot f(x,y)$$

где $f(x,y)$ — бинарная функция яркости (1 — чёрный, 0 — белый).

#### 2.4. Нормированные координаты центра тяжести

$$cx_{rel} = \frac{cx}{W} \quad cy_{rel} = \frac{cy}{H}$$

#### 2.5. Осевые моменты инерции

$$I_x = \sum_{x=0}^{W-1}\sum_{y=0}^{H-1} (y - \bar{y})^2 \cdot f(x,y)$$

$$I_y = \sum_{x=0}^{W-1}\sum_{y=0}^{H-1} (x - \bar{x})^2 \cdot f(x,y)$$

#### 2.6. Нормированные осевые моменты инерции

$$I_x^{norm} = \frac{I_x}{W \cdot H} \quad I_y^{norm} = \frac{I_y}{W \cdot H}$$

#### 2.7. Профили X и Y

Вертикальный профиль (проекция на X):

$$Proj_X[y] = \sum_{x=0}^{W-1} f(x, y)$$

Горизонтальный профиль (проекция на Y):

$$Proj_Y[x] = \sum_{y=0}^{H-1} f(x, y)$$

---

### 3. Пример рассчитанных признаков

#### Символ: අ (U+0D85)

| Признак | Значение |
|:--------|---------:|
| Размер изображения | 95 × 139 px |
| **Вес четвертей:** | |
| Q1 (верхний левый) | 1235 |
| Q2 (верхний правый) | 1225 |
| Q3 (нижний левый) | 527 |
| Q4 (нижний правый) | 829 |
| **Удельный вес четвертей:** | |
| Q1_rel | 0.3808 |
| Q2_rel | 0.3777 |
| Q3_rel | 0.1625 |
| Q4_rel | 0.2556 |
| **Центр тяжести:** | |
| cx | 46.94 |
| cy | 51.80 |
| **Нормированный центр тяжести:** | |
| cx_rel | 0.4941 |
| cy_rel | 0.3727 |
| **Осевые моменты инерции:** | |
| Ix | 4,045,981.6 |
| Iy | 2,689,725.5 |
| **Нормированные моменты:** | |
| Ix_norm | 306.40 |
| Iy_norm | 203.69 |

---

### 4. Профили символов

Профили представлены в виде столбчатых диаграмм с целыми числами на осях.

#### Символ: අ (U+0D85)

| Вертикальный профиль (проекция на X) | Горизонтальный профиль (проекция на Y) |
|:-----------------------------------:|:-------------------------------------:|
| ![profile_U+0D85](sinhala_chars/profiles/0D85_profile.png) | ![profile_U+0D85](sinhala_chars/profiles/0D85_profile.png) |

#### Символ: ක (U+0D9A)

| Вертикальный профиль (проекция на X) | Горизонтальный профиль (проекция на Y) |
|:-----------------------------------:|:-------------------------------------:|
| ![profile_U+0D9A](sinhala_chars/profiles/0D9A_profile.png) | ![profile_U+0D9A](sinhala_chars/profiles/0D9A_profile.png) |

#### Символ: ම (U+0DB8)

| Вертикальный профиль (проекция на X) | Горизонтальный профиль (проекция на Y) |
|:-----------------------------------:|:-------------------------------------:|
| ![profile_U+0DB8](sinhala_chars/profiles/0DB8_profile.png) | ![profile_U+0DB8](sinhala_chars/profiles/0DB8_profile.png) |

---

### Заключение

В ходе лабораторной работы №5 выполнены следующие задачи:

1. **Генерация эталонных изображений** 76 символов сингальского алфавита с прозрачным фоном
2. **Расчёт скалярных признаков** для каждого символа:
   - Вес чёрного каждой четверти
   - Удельный вес четвертей
   - Координаты центра тяжести (абсолютные и нормированные)
   - Осевые моменты инерции (абсолютные и нормированные)
3. **Сохранение признаков** в CSV-файл (разделитель «точка с запятой»)
4. **Построение профилей X и Y** в виде столбчатых диаграмм с целыми числами на осях

**Результаты сохранены в папке:** `sinhala_chars/`
- Изображения символов: `*.png`
- Скалярные признаки: `features.csv`
- Профили: `profiles/*.png`