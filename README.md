# Laboratory-1
КАЛЬКУЛЯТОР:




what = input( "Что делаем? (+,-): " )

a = input("Введите первое число")
b = input("Введите второе число")

if what == "+":
    c = a + b

elif what == "-":
    c = a - b
    
else:
    print("Операция неверна!")

print("Результат: " + с)
ТАЙМЕР:




import NotImplemented

while True:
    i = 0 # секунды
    ii = 0 # минуты
    iii = 0 #часы
    time_user = int(input("Введите кол-во секунд: "))
    comment = str(input("Введите комментарий: "))
    for q in range(time_user):
        time.sleep(1)
        i += 1
        print("Прошло секунд:", i)
        if(i % 60) == 0:
            ii += 1
            print("Прошло минут:", ii)
        if(i % 3600) == 0:
            iii += 1
            print("Прошло часов:", iii)
            
    print("Время окончено!")
    print("Ваш комментарий:",)
    
Вопрос:

print('Как тебя зовут?')
name = input()
print('Привет' ,name, '!Твой первый вопрос!')
q = ['Москва-столица России?']
answer = ['да' , 'нет']
for i in q:
    print(i)
    answer1=str(input())
