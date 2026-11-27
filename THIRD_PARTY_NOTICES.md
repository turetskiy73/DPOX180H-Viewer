# Сторонние материалы

Код программы (`DPOX180H Viewer.exe`, `read-dpox180h.ps1`, `DPOX180H_Viewer.cs`)
написан с нуля. Однако описание бинарного формата файлов FNIRSI DPOX180H
и калибровочная формула были изучены по следующим открытым проектам.

## Rav263/fnirsi-wave-decoder

- Ссылка: https://github.com/Rav263/fnirsi-wave-decoder
- Лицензия: MIT (указано в README проекта)
- Использовано: структура секций, карта полей заголовка, формула перевода
  ADC в напряжение, сведения о big-endian и порядке каналов.

## alessandrofrati/fnirsi-dpox180h-tools

- Ссылка: https://github.com/alessandrofrati/fnirsi-dpox180h-tools
- Лицензия: MIT
- Copyright (c) 2026 Alessandro Frati
- Использовано: уточнённая карта настроек DPOX180H, число отсчётов,
  частота дискретизации, масштаб времени, порядок блоков каналов.

## Текст лицензии MIT для указанных материалов

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Дисклеймер

DPOX180H Viewer — неофициальный инструмент. Он не связан с компанией FNIRSI
и не является официальным продуктом производителя.
