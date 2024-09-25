# AstroScript
## Программа для обработки данных наблюдения звезды к курсу "Общая Астрофизика".

### Сборка
Собрать проект можно через Makefile. Достаточно написать в консоли: `make`.

Чтобы отключить логгер необходимо в Makefile убрать флаг компиляции `-DLOGGER`.

### Устройство
В директории `data/` находятся как исходные данные, так и промежуточные данные,
обработанные программой.

В директории `plot/` находятся GNUPLOT скрипты для рисования графиков `plot/scripts/`,
данные для графиков `plot/data/` и сами графики.

### Результат
Для звезды *v603aql* фильтра *R* и даты 6 октября 1994 г.

#### Таблица для вычесления воздушной массы:
| Время | Ср солн время | Зв время | Час угол | Воз масса |
|-------|---------------|----------|----------|-----------|
| 19:57 | 18:42         | 19h 43m  | 00h 57m  | 1.416879  |
| 21:11 | 19:57         | 20h 58m  | 02h 12m  | 1.634094  |
| 21:34 | 20:20         | 21h 21m  | 02h 35m  | 1.755675  |
| 21:35 | 20:21         | 21h 22m  | 02h 36m  | 1.760245  |
| 21:53 | 20:39         | 21h 40m  | 02h 53m  | 1.882138  |
| 22:15 | 21:01         | 22h 02m  | 03h 16m  | 2.079793  |
| 22:16 | 21:02         | 22h 03m  | 03h 17m  | 2.093250  |
| 22:17 | 21:03         | 22h 04m  | 03h 18m  | 2.104473  |

#### График зависимости блеска звезды от воздушной массы:
<picture>
  <img
    title="График зависимости блеска звезды от воздушной массы."
    width="700"
    src="https://github.com/user-attachments/assets/526f7f11-4451-4183-87be-d7aad5223bf0"
  >
</picture>

#### График зависимости коэффициента экстинкции от времени:
<picture>
  <img
    title="График зависимости коэффциента экстинкции от времени."
    width="700"
    src="https://github.com/user-attachments/assets/c220d5f0-188a-4a3b-8a7e-379211b9904b"
  >
</picture>
