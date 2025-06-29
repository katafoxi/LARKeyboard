# LARKeyboard
![1750104831519](https://github.com/user-attachments/assets/b53b73be-e556-4599-bc34-2baae3e7fba7)

Кастомная механическая клавиатура с открытым исходным кодом.  

## **Характеристики**  
- **Прошивка:** ZMK 
- **Макет:** Split Dactyl Manuform
- **Микроконтроллер:** (NRF52840 Development Board )  
- **Кейкапы:** ( MX )  
- **Интерфейс:** (USB-C, Bluetooth)  
- **Особенности:** (интегрированный трекболл ProtoArc EM04 Wireless, функционирующий независимо от клавиатуры),  


## Hardware
### **Bill of Materials (BOM)**  
#### **Процесс сборки и время**

| Этап сборки                        |   L   |   R   | Компонент                                                                                                                                   |               Количество |
| ---------------------------------- | :---: | :---: | :------------------------------------------------------------------------------------------------------------------------------------------ | -----------------------: |
| 3D-печать                          |  мин  |  мин  | Филамент для 3D-печати                                                                                                                      |                   700 гр |
| Печать корпуса  L-левый            |   -   |   -   | [l_case.stp](hardware/3d_models_to_print/l_case.stp) + [l_case.jpg](hardware/3d_models_to_print/l_case.jpg)                                 |                     1 шт |
| Печать крышек и мелочи             |   -   |   -   | [l_cover.stp](hardware/3d_models_to_print/l_cover.stp) + [jpg](hardware/3d_models_to_print/l_cover.jpg)                                     |                     1 шт |
|                                    |   -   |   -   | [l_hexkey_holder.stp](hardware/3d_models_to_print/l_hexkey_holder.stp) + [jpg](hardware/3d_models_to_print/l_hexkey_holder.jpg)             |                     1 шт |
|                                    |   -   |   -   | [l_5pos_switch_mount.stp](hardware/3d_models_to_print/l_5pos_switch_mount.stp) + [jpg](hardware/3d_models_to_print/l_5pos_switch_mount.jpg) |                     1 шт |
|                                    |   -   |   -   | [l_led_mount.stp](hardware/3d_models_to_print/l_led_mount.stp) + [jpg](hardware/3d_models_to_print/l_led_mount.jpg)                         |                     1 шт |
|                                    |   -   |   -   | [l_nicenano_mount.stp](hardware/3d_models_to_print/l_nicenano_mount.stp) + [jpg](hardware/3d_models_to_print/l_nicenano_mount.jpg)          |                     1 шт |
|                                    |   -   |   -   | #заглушки                                                                                                                                   |                    30 шт |
|                                    |
| Печать корпуса  R-правый           |   -   |   -   | [r_case.stp](hardware/3d_models_to_print/r_case.stp) + [r_case.jpg](hardware/3d_models_to_print/r_case.jpg)                                 |                     1 шт |
| Печать крышек и мелочи             |   -   |   -   | [r_cover.stp](hardware/3d_models_to_print/r_cover.stp) + [jpg](hardware/3d_models_to_print/r_cover.jpg)                                     |                     1 шт |
|                                    |   -   |   -   | [r_pcb_strip_1.stp](hardware/3d_models_to_print/r_pcb_strip_1.stp) + [jpg](hardware/3d_models_to_print/r_pcb_strip_1.jpg)                   |                     1 шт |
|                                    |   -   |   -   | [r_pcb_strip_2.stp](hardware/3d_models_to_print/r_pcb_strip_2.stp) + [jpg](hardware/3d_models_to_print/r_pcb_strip_2.jpg)                   |                     1 шт |
|                                    |   -   |   -   | [r_5pos_switch_mount.stp](hardware/3d_models_to_print/r_5pos_switch_mount.stp) + [jpg](hardware/3d_models_to_print/r_5pos_switch_mount.jpg) |                     1 шт |
|                                    |   -   |   -   | [l_nicenano_mount.stp](hardware/3d_models_to_print/l_nicenano_mount.stp)                                                                    |                     1 шт |
|                                    |   -   |   -   | r_click_l <br>r_click_r<br>r_click_resolution<br>                                                                                           | 1 шт<br>1 шт<br>1 шт<br> |
|                                    |   -   |   -   | #заглушки                                                                                                                                   |                    29 шт |
| Удаление поддержек                 |  30   |  30   |                                                                                                                                             |                          |
| Установка заглушек                 |   5   |   5   | Заглушка в гнездо под покраску                                                                                                              |                    60 шт |
| Ошкуривание                        |  60   |  60   |                                                                                                                                             |                          |
| Покраска                           |  7.5  |  7.5  | Грунтовка + Эмаль                                                                                                                           |               1+1 баллон |
| Вытаскивание заглушек              |   5   |   5   |                                                                                                                                             |                          |
| Установка вплавляемых втулок       |  7.5  |  7.5  | Втулка вплавляемая М3х5                                                                                                                     |                    24 шт |
| Установка Hotswap коннекторов      |  15   |  15   | Коннектор Hotswap MX                                                                                                                        |                    59 шт |
| Пайка столбцов                     |  60   |  60   | Провод эмалированный                                                                                                                        |                    500 м |
| Пайка рядов из диодов              |  62   |  60   | Диод  1N4148                                                                                                                                |                    59 шт |
| Установка nice!nano_v2             |  120  |  99   | Плата NRF52840                                                                                                                              |                     2 шт |
| Обжим батарейного отсека           |   5   |   5   | Батарейный отсек UM-3x2                                                                                                                     |                     2 шт |
| Установка батареек                 |   1   |   1   | Аккумулятор 14500 АА Ni-Mh                                                                                                                  |                     4 шт |
| Установка движкового переключателя |  10   |  10   | Переключатель движковый KLS7                                                                                                                |                     2 шт |
| Установка тактильной кнопки        |  10   |  10   | Кнопка тактильная SWT-20-5                                                                                                                  |                     2 шт |
| Установка 5-позиционной кнопки     |  48   |  48   | 5-позиционные кнопки                                                                                                                        |                     2 шт |
| Установка наклеек под свитчи       |  15   |  20   | Наклейки шумоизолирующие                                                                                                                    |                    59 шт |
| Установка свитчей                  |  55   |  27   | Свитчи Cherry MX red/black                                                                                                                  |                    59 шт |
| Установка трекбола                 |   -   |  35   | Трекбол ProtoArc EM04 Wireless                                                                                                              |                     1 шт |
| Установка O-rings                  |   -   |   -   | Keyboard o-rings 8x5x1.5mm                                                                                                                  |                    59 шт |
| Установка кейкапов                 |  68   |  66   | Кейкапы                                                                                                                                     |                    59 шт |
| Установка крышек                   |   5   |   5   | Винт с потайной головкой М3х6                                                                                                               |                    24 шт |
| Установка держателя L-ключа        |   5   |   -   | КЛЮЧ 2-1-Х9 ГОСТ Р 57981-2017                                                                                                               |                     1 шт |


Общее время на сборку 21,7  часов.

### **Итого**
- **Общая стоимость компонентов:** ~ **11,500 руб** (без учета оптовых скидок)
- **Основные затраты:** корпус, свитчи, трекбол, электроника.

## **Сборка и прошивка**  
