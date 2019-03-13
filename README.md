# picons-rtrs

Picons for russian RTRS channels:
- 01 ПЕРВЫЙ КАНАЛ
- 02 РОССИЯ-1
- 03 МАТЧ!
- 04 НТВ
- 05 ПЯТЫЙ КАНАЛ
- 06 РОССИЯ-К
- 07 РОССИЯ-24
- 08 КАРУСЕЛЬ
- 09 ОТР
- 10 ТВ Центр
- 11 РЕН ТВ
- 12 Спас
- 13 СТС
- 14 Домашний
- 15 ТВ3
- 16 Пятница
- 17 Звезда
- 18 МИР
- 19 ТНТ
- 20 МУЗ ТВ
- ВЕСТИ ФМ
- МАЯК
- Радио России

## How to use

### Tvheadend server

#### for all channels

1. Configuration → General → Base → Channel icon path

    ```
    https://raw.githubusercontent.com/vattik/picons-rtrs/master/220x100/%U.png
    ```

2. Configuration → General → Image Cache

    Enabled: &#9745;

    Ignore invalid SSL certificate: &#9745;

#### for individual channel

1. Configuration → Channel / EPG → Channels → Edit → User icon

    ```
    https://raw.githubusercontent.com/vattik/picons-rtrs/master/220x100/15%20%D0%A2%D0%923.png
    ```
