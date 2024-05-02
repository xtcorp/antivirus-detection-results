![Windows Section](https://github.com/xtcorp/antivirus-detection-results/blob/main/images/AntivirusDetection.png)

Тестирование популярных на 2023-й год антивирусных программ. За основу теста была взята [коллекция малварей от Zusyaku](https://github.com/Zusyaku/Malware-Collection-Part-2) без больших вирусов. Коллекция в разархивированном виде имеет 1164 файла и 193 папки

## Когда было тестирование?
21 сентября 2023 года

## Условия
- Тестирование "из коробки" на стандартных настройках

## На чем тестировалось?
- Windows 10 Pro

## Информация
Коллекция содержит рекламный софт, софт-шутки, билдеры вирусов и просто нежелательный софт. По моему мнению, все эти программы должны так же обнаруживаться, так как они являются нежелательными для конечного пользователя в любом случае

## Результаты
| Антивирус | Обнаружено | Обнаружено % |
|          ---: |     :---:      |     :---:      |
| **KVRT** | **725** | **62%** |
| ESET NOD32 | 705 | 61% |
| 360 Total Security | 681 | 59% |
| Avast | 675 | 58% |
| AVG | 675 | 58% |
| MalwareBytes | 618 | 53% |
| Kaspersky Free | 599 | 51% |
| Dr Web CureIt | 496 | 43% |
| Microsoft Defender | 254 | 22% |
