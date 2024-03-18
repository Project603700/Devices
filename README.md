<a id="readme-top"></a>
## Пристрої проекту 603700:
  <ol>
    <li><a href="#Module149">Модуль 149 (польотний контролер F405)</a></li>
    <li><a href="#Module84">Модуль 84 (регулятор обертів 55A)</a></li>
    <li><a href="#Module135">Модуль 135 (плата ініціації FCAT v1.0)</a></li>
    <li><a href="#Module136">Модуль 136 (плата ініціації Херсон)</a></li>
  </ol>

<a id="Module149">

  ## Модуль 149  <a href="https://github.com/Project603700/Devices/tree/main/Module149"> (докладніше)</b> <br><p>
![149](https://github.com/Project603700/Devices/assets/158263587/adf59bf5-93d9-4381-b5f9-6ab40a3cb92d)



![betaflight](https://github.com/Project603700/Devices/assets/158263587/47dcc82f-291e-4830-8be2-143e6e9e31f7) <b>Файли прошивок Betaflight:  <a href="https://github.com/Project603700/Devices/tree/main/Module149/firmware/Betaflight">Завантажити</b> <br><p>


![inav](https://github.com/Project603700/Devices/assets/158263587/472ad80d-6fa1-4fb5-9af7-55e05c172fb3) <b>Файли прошивок INAV:  <a href="https://github.com/Project603700/Devices/tree/main/Module149/firmware/INAV">Завантажити</b> <br><p>

<p>
<br>
Мікроконтролер: STM32F405RGT6(168МГц)<br>
Гіроскоп/акселерометр: BMI270 (8кГц макс)<br>
OSD: Betaflight OSD на мікросхемі AT7456<br>
Барометр: DPS310<br>
Blackbox: 16Mb Flash (встановлюється за потреби)<br>
Розміри: 36х36мм<br>
Монтажні отвори: 30.5x30.5мм, M3<br>
Прошивка: Betaflight, INAV. <a href="https://github.com/Project603700/Devices/tree/main/Module149/firmware"><b>ФАЙЛИ ПРОШИВОК</b><br><p>
Інтерфейси: 2хUART, 1хSoftserial, 1хI2C, 2хАЦП (VBAT, Current), 1хSbus (з вбудованим інвертором, підключений до Rx6), 1хВихід для бузера<br>
Підключення: USB Type-C<br>
Живлення: 6-30В (2-6S LiIon/LiPo)<br>
Вхід датчику струму (CURR)<br>
Виходи для ESC: 4шт (М1-М4, PWM, DSHOT)<br>
Серво виходи: 2шт (S1,S2)<br>
BEC: 5V 3А (дозволяється живлення сервоприводу)<br>
<b>Монтаж приймача TBS Crossfire / ELRS прямо на плату</b><br>
Вібророзв'язка: силіконові демфери, входять до комплекту поставки<br>
<b>Докладніше за <a href="https://github.com/Project603700/Devices/tree/main/Module149">посиланням</b>

  <p align="right"><a href="#readme-top">Догори ↑</a></p>



<a id="Module84">

  ## Модуль 84  <a href="https://github.com/Project603700/Devices/tree/main/Module84"> (докладніше)</b> <br><p>
![84](https://github.com/Project603700/Devices/assets/158263587/0705f5b7-bf24-4af9-baa4-49b58aba299c)



<p>
<br>
Живлення: 3-6S LiIon/LiPo (9-26В)<br>
Струм: 55А (65А короткочасно)<br>
Датчик струму: так, до 132 А<br>
Прошивка: BLHeli_S, target: J_H_50<br>
Монтажні отвори: 30.5*30.5мм, M3<br>
Розміри: 45*45мм<br>
Монтажні отвори: 30.5x30.5мм, M3<br>
Протоколи роботи: DSHOT300/600</b><br>
Роз'єм для підключення: JST-SH 8 pin<br>
LOW ESR конденсатор: так, входить до комплекту<br>
Роз'єм живлення: ХТ-60, входить до комплекту<br>
BEC: ні<br>
<b>Докладніше за <a href="https://github.com/Project603700/Devices/tree/main/Module84">посиланням</b>
  
<p align="right"><a href="#readme-top">Догори ↑</a></p>

<a id="Module135">

  ## Модуль 135  <a href="https://github.com/Project603700/Devices/tree/main/Module135"> (докладніше)</b> <br><p>
![135](https://github.com/Project603700/Devices/assets/158263587/6be0d4b7-d376-456b-acde-8e70a58788e6)





<p>
<br>
Тип спрацювання: інерційне + спрацювання по PWM каналу + самознищення<br>
Запобіжник: механічний, ARM/DISARM по PWM каналу<br>
Напруга живлення: 5-12В<br>
Індикація ARM/DISARM: так<br>
Монтажні отвори: 30.5*30.5мм, M3 + 20*20мм М3<br>
Підключення детонатора: клемник<br>
Роз'єм для підключення до польотного контролеру: JST-SH 1.0 4pin (шлейф в комплекті поставки)<br>
Максимальний струм ініціації: 1500мА<br>
Таймер безпеки: 2 хв<br>
Таймер самознищення: 30 хв<br>
<b>Докладніше за <a href="https://github.com/Project603700/Devices/tree/main/Module135">посиланням</b>
  
<p align="right"><a href="#readme-top">Догори ↑</a></p>

<a id="Module136">

  ## Модуль 136  <a href="https://github.com/Project603700/Devices/tree/main/Module136"> (докладніше)</b> <br><p>
![136](https://github.com/Project603700/Devices/assets/158263587/674be56e-335b-43ff-8184-28e2e6c4cf97)



<p>
<br>
Тип спрацювання: інерційне + спрацювання по PWM каналу + самознищення<br>
Запобіжник: механічний (чека)<br>
Живлення: CR123A 3v 1500mAh (вбудована у пристрій)<br>
Увімкнення/вимкнення: кнопка<br>
Індикація стану: світлова, звукова<br>
Підключення детонатора: клемник<br>
Розміри: 72*47*25 мм<br>
Матеріал корпусу: пластик<br>
Роз'єм підключення до польотного контролеру: клемник<br>
Максимальний струм ініціації: 1500мА<br>
Таймер безпеки: після зняття механічного запобіжника 2 хв до активації<br>
Таймер самознищення: так, через 30 хв після зняття з запобіжника<br>
<b>Докладніше за <a href="https://github.com/Project603700/Devices/tree/main/Module136">посиланням</b>
  
<p align="right"><a href="#readme-top">Догори ↑</a></p>





