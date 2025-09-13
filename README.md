# LARKeyboard
Кастомная механическая клавиатура с открытым исходным кодом и интегрированным трекболом.

![92](images/92.jpg) ![94](images/94.jpg) ![91](images/91.jpg) 

## **Характеристики**  
- **Прошивка:** ZMK 
- **Макет:** Split Dactyl Manuform
- **Микроконтроллер:** (NRF52840 Development Board )  
- **Кейкапы:** ( MX )  
- **Интерфейс:** (USB-C, Bluetooth)  
- **Особенности:** (интегрированный трекболл ProtoArc EM04 Wireless, функционирующий независимо от клавиатуры),  

## 🔗 Быстрые ссылки

- 📁 [Репозиторий с прошивкой](https://github.com/katafoxi/zmk-keyboard-lark)

- 📊 [Легенды клавиш и кеймап](https://docs.google.com/spreadsheets/d/1xXg7V_umpOhjsuPLZJ3ickMg2kA1LSvM3Gqmz-Sg8EQ/edit)


## 🛠️ Hardware
<details>
<summary>📦 Bill of Materials (BOM) (кликните, чтобы развернуть)</summary>

| Этап сборки                           | Компонент                                                        | Количество |
| ------------------------------------- | :--------------------------------------------------------------- | ---------: |
| 3D-печать                             | Филамент для 3D-печати                                           |     700 гр |
| Печать деталей левой половины         | [_left_print.stp](hardware\3d_models_to_print\_left_print.stp)   |       1 шт |
| Печать деталей правой половины        | [_right_print.stp](hardware\3d_models_to_print\_right_print.stp) |       1 шт |
| Удаление поддержек                    |                                                                  |            |
| Установка заглушек                    | Заглушка в гнездо под покраску                                   |      60 шт |
| Ошкуривание                           |                                                                  |            |
| Покраска                              | Грунтовка + Эмаль                                                | 1+1 баллон |
| Удаление  заглушек                    |                                                                  |            |
| Установка вплавляемых втулок          | Втулка вплавляемая М3х5                                          |      24 шт |
| Установка Hotswap коннекторов         | Коннектор Hotswap MX                                             |      59 шт |
| Пайка столбцов                        | Проволока красная медная эмалированная  QA-1/155R 2UEW ø0.2мм    |      500 м |
| Пайка рядов из диодов                 | Диод  1N4148                                                     |      59 шт |
| Пайка и установка nice!nano_v2        | Плата NRF52840                                                   |       2 шт |
| Обжим проводов для батарейного отсека | Отсек батарейный UM-3x2                                          |       2 шт |
| Установка аккумуляторов               | Аккумулятор 14500 АА Ni-Mh                                       |       4 шт |
| Установка движкового переключателя    | Переключатель движковый L-KLS7-SS03-12D02-EG03                   |       2 шт |
| Установка тактильной кнопки           | Кнопка тактильная SWT-20-5                                       |       3 шт |
| Установка 5-позиционной кнопки        | Кнопка DIP 5 Five way Switch Multi-direction                     |       2 шт |
| Установка наклеек под свитчи          | Наклейки шумоизолирующие                                         |      59 шт |
| Установка свитчей                     | Свитч Cherry MX                                                  |      59 шт |
| Установка трекбола                    | Трекбол ProtoArc EM04 Wireless                                   |       1 шт |
| Установка O-rings                     | Keyboard o-rings 8x5x1.5mm                                       |      59 шт |
| Установка кейкапов                    | Кейкапы                                                          |      59 шт |
| Установка крышек                      | Винт с потайной головкой М3х6                                    |      24 шт |
| Установка держателя L-ключа           | Ключ 2-1-Х9 ГОСТ Р 57981-2017                                    |       1 шт |
| Установка магнитов для L-ключа        | Магнитик неодимовый                                              |       2 шт |
| Сборка и пайка донгла                 |                                                                  |       1 шт |

</details> 


<details>
<summary> 🔧 Необходимые инструменты </summary><div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

- ✏️ Пинцет
- ✂️ Кусачки
- 🔪 Скальпель
- 🔌 Паяльник + Флюс
- 📏 Пилочка для ногтей
- 🔥 Зажигалка
- 🔧 Набор ключей шестигранных
- Наждачная сетка P180, P240, P600, P1000
![tools](images/tools.png)

</div> </details>

<div style="background-color: #d1e7dd; color: #0f5132; padding: 12px; border-radius: 5px; margin: 10px 0;">

**💡 Примечание:** На корпусах заглушены некоторые отверстия под покраску и аккуратное срезание после покраски.

</div>

<details> <summary>📐 Модели для печати</summary><div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

`hardware/_left_print.stp` 
![left_print](hardware/_left_print.png)

`hardware/_right_print.stp` 
![right_print](hardware/_right_print.png)

</div></details>


<details >
<summary>Исходная сборка </summary>

`hardware/_LARKeyboard_full_assambly.stp`
![_LARKeyboard_full_assambly](hardware/_LARKeyboard_full_assambly.png)
</details>


<details>
<summary>🎥 Видео последовательности сборки левой половинки</summary>

![build_left](images/_left_build.gif)
</details>

<details>
<summary>🎥Видео последовательности сборки правой половинки</summary>

![build_right](images/_right_build.gif)
</details>


## 📸 Фото последовательности сборки

<details>
<summary>🔄 Этап 1: Подготовка корпуса</summary>

<div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

**Процесс:**
- Печать
- Удаление поддержек
- Установка заглушек
- Ошкуривание

![Этап 1](images/a1.png)

</div>
</details>


<details>
<summary>🎨 Этап 2: Покраска</summary>

<div style="background-color: #fff3cd; color: #856404; padding: 15px; border-radius: 5px; margin: 10px 0;">

**Процесс покраски:**
1. Грунтовка + Эмаль
2. Ошкуривание P800-P1000
3. Покраска (Эмаль)
4. Удаление заглушек

![Этап 2](images/a2.png)

</div>
</details>


<details>
<summary>🔌 Этап 3: Электроника</summary>

<div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

**Процесс:**
- Установка hotswap
- Установка вплавляемых втулок
- Пайка столбцов
- Пайка строк
- Пайка платы NRF52840
- Пайка 5-позиционного переключателя

![Этап 3](images/a3.png)

</div>
</details>


### 📊 Схемы подключения

<div style="background-color: #cff4fc; color: #055160; padding: 12px; border-radius: 5px; margin: 10px 0;">

**Схема левой половинки** 
![left](images/_left.png)

**Схема правой половинки**
![right](images/_right.png)

</div>


<details>
<summary>💡 Этап 4: Световоды и трекбол</summary>

<div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

<div style="background-color: #d4edda; color: #155724; padding: 12px; border-radius: 5px; margin: 10px 0;">

**💡 Совет по световодам:**
В качестве световода можно использовать прозрачный PLA/PETG ø1.75мм или оптоволокно. 
Отрезаем 2 кусочка длиной 10 см, изгибаем под 90°, вставляем в отверстия в корпусе, 
потом вставляем в держатель платы, наживляем крепеж, обрезаем лишнее, шлифуем торцы пилочкой для ногтей.

</div>

**Процесс:**
- Установка светопроводов
- Установка Платы NRF52840
- Подрезка детали платы трекбола
- Установка платы трекбола
- Установка трекбола

![Этап 4](images/a4.png)

<div style="background-color: #fff3cd; color: #856404; padding: 12px; border-radius: 5px; margin: 10px 0;">

**⚠️ Важно:** Отверстие под шар специально сделано меньше. Острым ножом срезая пластик, 
добейтесь геометрии, при которой шар не выпадает, но легко извлекается для очистки.

</div>

</div>
</details>


<details>
<summary>🔋 Этап 5: Финальная сборка</summary>

<div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

**Процесс:**
- Обжим держателя батареек (мама)
- Установка держателя батареек (суперклей)
- Сборка крышек
- Сборка донгла
- Установка шумоизолирующих наклеек

![Этап 5](images/a5.png)

<div style="background-color: #d4edda; color: #155724; padding: 12px; border-radius: 5px; margin: 10px 0;">

**💡 Инструкция:** Обжать провода выводы B+ и В- от платы (папа), 
соединить с выводами от держателя батареек. Установить крышки.

</div>

</div>
</details>


<details>
<summary>⌨️ Этап 6: Установка свитчей и кейкапов</summary>
<div style="background-color: #f8f9fa; color: #212529; padding: 15px; border-radius: 5px; margin: 10px 0;">

При использовании сборных колпачков с прозрачной крышкой:
1. Распечатать [легенды](https://docs.google.com/spreadsheets/d/1xXg7V_umpOhjsuPLZJ3ickMg2kA1LSvM3Gqmz-Sg8EQ/edit)
2. Нарезать легенды
3. Собрать колпачки

![Установка клавиш](images/a6.png)
</div></details>

---

## 📚 Дополнительная информация

<div style="background-color: #e9ecef; color: #495057; padding: 15px; border-radius: 5px; margin: 10px 0;">

### 🔗 Полезные ссылки
- [📁 Репозиторий с прошивкой](https://github.com/katafoxi/zmk-keyboard-lark)
- [📊 Google Sheets с легендами](https://docs.google.com/spreadsheets/d/1xXg7V_umpOhjsuPLZJ3ickMg2kA1LSvM3Gqmz-Sg8EQ/edit)

</div>

---

## Firmware
[Процесс](https://zmk.dev/docs/user-setup#installing-the-firmware) прошивки сдандартный для ZMK.
[Репозиторий с прошивкой клавиатуры](https://github.com/katafoxi/zmk-keyboard-lark)


<div style="background-color: #d4edda; color: #155724; padding: 15px; border-radius: 5px; margin: 10px 0; text-align: center;">

**🎉 Поздравляем с завершением сборки LARKeyboard!**  
Наслаждайтесь использованием вашей кастомной клавиатуры с трекболом!

</div>