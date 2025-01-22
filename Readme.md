# Изучение Python


#### Я разделю на важны моменты которые хорошо подойдут для изучении базы и буду это дополнять 


Все ссылки на скрипты будут в этом репозитории: [Ссылка](https://github.com/phancyn/learn-py)

Надо хотяб базу знания про python, а именно:
Что такое: print, input, переменные 

#### Первый материал: Числа, Слова и их работа
```

#Цифры которые будут использоваться в изучении x y z 
x = 10  
y = 20  
z = 5  
  
  
w = x + z   
  
if w == 15:  
    print("Great!")  
elif w != 15:  
    print("Not!")

```
Эта команда считает числа x и z 
x в этом случае равняется 10 а z = 5 

если сложить в голове x+z=10+5=15 

*Высшая математика разумеется* 

Получается если w равняется 15 то пишется Great! 
Если не равняется то Not!

Прописать равняется и не равняется так 

	== - Равняется 
	!= - Не равняется

x, y, z - это переменные которые могут быть как и слова 

```
#Слова которые будут использоваться в изучении x y z 
x = "Nice"  
y = "Bread"  
z = "Dick"  
  
  
w = (x + " " + z)   
  
if w == "Nice" " " "Dick":  
    print("Great!")  
elif w != "Nice" " " "Dick":  
    print("Not!")  
  
  
print(w)
```
*Правильный ответ ~~Nice Dick~~ - Даже хоть какой там перевод то что в голову пришло то и сделал. КМХ. Дальше* 

Мы узнали то что в переменные можно вставлять Как слова так и цифры 


#### 2 Материал. Input
`print("Тебе надо вести числа которые будут плючоваться и должно получится число 15")`  
  
`a = int(input("Первое число:"))`  
`b = int(input("Второе число:"))`  
  
`x = a + b`   
  
`if x == 15:`  
    `print("Ты молодец!")`  
`elif x != 15:`  
    `print("У тебя не получилось")`

Так что я тут ввёл.
Этот код для принятья 2 чисел которые между собой плюсуется и тут же я использовал так же как и в первом материале. Взятие чисел также плюсуется и получаем ответ 15
Уже на Русском языке тут всё написано 

Теперь давай со словом. На маленькой команде 

```
a = input("Введите текст или число:")  
  
print(a)

```

Вот так легко мы получим получения слова и вывод его в терминал

#### 3 Материал. Функция

```
def Low():  
    a = ("123")  
    b = (" ")  
    c = ("231")  
    print(a + b + c)  
  
def High():  
    a = ("321")  
    b = (" ")  
    c = ("421")  
    print(a + b + c)  
      
Low()  
High()
```

Вот так вводится функция: def и название функции не забудьте про () и : они обязательные атрибуты

```
Получается что то такого: def Name():
```

```
Так что у нас выводится в терминале: 
123 231
321 421
```
Всё правильно.

Я специально ввёл одинаковые переменные для того чтоб показать вам то что не будет браться из той функции а только в пределах своей 



Продолжение следует
