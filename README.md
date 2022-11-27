# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Еремин Егор Константинович
- РИ210940
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | # | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Реализовать перцептрон на Unity

## Задание 1
В проекте Unity реализовать перцептрон, который умеет производить вычисления:
OR, AND, NAND, XOR.

Ход работы:

1. Создаем объект perceprton и добавляем к нему скрипт перцептрона. Создаем 4 значения, которые может обрабатывать перцептрон.

![image](https://user-images.githubusercontent.com/102966721/204113979-77d36423-63d1-4f92-b9c3-7f156c2cd79d.png)

##Операция OR##

2. Заполняем элементы значениями, соответствующими операции OR:

![image](https://user-images.githubusercontent.com/102966721/204113830-ccb62307-861f-4583-930c-b2323c1323eb.png)


3.Задаем количество эпох и подбираем то, при котором перцептрон обучится работать с операцией: 

1 эпоха:
![image](https://user-images.githubusercontent.com/102966721/204113815-4cae8670-7f71-4287-972d-d72f2878cd9a.png)

2 эпохи:
![image](https://user-images.githubusercontent.com/102966721/204113935-3aa5f1a7-1fc9-4b36-ac45-3d50c7426a51.png)

4 эпохи:
![image](https://user-images.githubusercontent.com/102966721/204113948-169b323f-8d7a-4385-86ee-835d89f26ab6.png)

Вывод: перцептрон учится работать с операцией OR с 4 эпохи.

##Операция AND##

4. Заполняем элементы значениями, соответствующими операции AND:

![image](https://user-images.githubusercontent.com/102966721/204114044-651fd31d-f2c9-45d3-9ef5-dfd52cd302e1.png)

5. Задаем количество эпох и подбираем то, при котором перцептрон обучится работать с операцией:

1 эпоха:
![image](https://user-images.githubusercontent.com/102966721/204114059-3a7f355c-b53e-45bc-85cb-a29d12e08214.png)

2 эпохи:
![image](https://user-images.githubusercontent.com/102966721/204114081-c18dd47c-22ea-434c-8113-9a92dbd6daef.png)

6 эпох:

![image](https://user-images.githubusercontent.com/102966721/204114117-2f0c11c0-8213-4228-9f2a-4e7dd59a0f31.png)

Вывод: перцептрон учится работать с операцией AND с 6 эпохи.

##Операция NAND##

6.Заполняем элементы значениями, соответствующими операции NAND:

![image](https://user-images.githubusercontent.com/102966721/204114148-20aed3d7-38ce-462b-8ae3-fde46fbbeb3e.png)

7. Подбираем количество эпох для операции:

6 эпох:

![image](https://user-images.githubusercontent.com/102966721/204114175-80abdf4d-dd9b-413c-ba2d-91f8a9973021.png)

Вывод: перцептрон учится работать с операцией NAND с 6 эпохи.

##Операция XOR##
8.Заполняем элементы значениями, соответствующими операции XOR:

![image](https://user-images.githubusercontent.com/102966721/204114199-9c2efee0-4b4f-489d-9b45-3cecd5f42fb9.png)

9. Подбираем количество эпох для операции:

Операции XOR перцептрон не может обучиться даже с 100000 попытки, поэтому делаю вид, что перцептрон не обучаем данной операции.

![image](https://user-images.githubusercontent.com/102966721/204114682-51de1958-9dcd-4df6-805a-02d2b4405a7d.png)


Изучив информацию, я узнал,что проблема XOR не решаема однослойным персептроном, потому что нули и единицы XOR линейно не разделимы. Для этой операции требуется многослойный перцептрон. 

## Задание 2


## Задание 3
---

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
