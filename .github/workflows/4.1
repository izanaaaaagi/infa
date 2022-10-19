import os
from os import listdir
from os.path import isfile

notes = []

def tableprint(notes):
    print("{:<2} {:<16} {:<5} {:<10} {:<8} {:<6}".format('Id','Task','Time','Date','Priority','Status'))
    for note in notes:
        id,task,time,date,priority,status = note.values()
        print("{:<2} {:<16} {:<5} {:<10} {:<8} {:<6}".format(id,task,time,date,priority,status))

def byStatus(note):
    return note["status"]

def byPrior(note):
    return note["priority"]

def byPriority(note):
    if(note["priority"])=="Высокий":
        return 0
    elif(note["priority"])=="Средний":
        return 1
    elif(note["priority"])=="Низкий":
        return 2
    else:
        return 3

def uiNoteInteraction():
    print("Введите желаемое действие:")
    print("1 - Посмотреть список существующих блокнотов")
    print("2 - создать новый блокнот")
    print("3 - изменить существующий блокнот")
    print("4 - удалить существующий блокнот")
    action = int(input())
    #TODO while TRUE
    if action == 1:
        print("Блокноты сейчас существуют:")
        print("notebook2.csv")
        print()

    elif action == 2:
        name_new = input("Введите имя нового блокнота")
        f = open(name_new + ".csv", "x")
        print("Блокнот notebook3.csv успешно создан!")
        print()

    elif action == 3:
        print("Введите номер строки: \n")
        noteId = int(input())
        print("Введите поле и новое значение через запятую, которое хотите изменить: \n")
        noteField,fieldValue = input().split(",")
        notes[noteId-1][noteField]=fieldValue

    elif action == 4:
        os.remove("notebook2.csv")
        print("Блокнот успешно удалён!")

with open("notebook2.csv","r",encoding="Utf-8") as f:
    for line in f:
        l = line.split(",")
        note = {
        "id":int(l[0]),
        "task":l[1],
        "time":l[2],
        "date":l[3],
        "priority":l[4],
        "status":l[5][:-1]
        }
        notes.append(note)


#print(notes)
uiNoteInteraction()
print("Значения в блокноте notebook2:")
tableprint(notes)
myfiles = []
