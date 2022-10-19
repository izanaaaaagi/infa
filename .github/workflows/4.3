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
    print("Введите желаемое действие\n [1 - Добавить,2 - Изменить, 3 - Удалить]:")
    action = int(input())
    #TODO while TRUE
    if action == 1:
        print("Введите строку, разделенную запятыми:\n")
        nl = input().split(",")
        note = {
        "id":len(notes)+1,
        "task":nl[0],
        "time":nl[1],
        "date":nl[2],
        "priority":nl[3],
        "status":nl[4]
        }
        notes.append(note)
    elif action == 2:
        print("Введите номер строки: \n")
        noteId = int(input())
        print("Введите поле и новое значение через запятую, которое хотите изменить: \n")
        noteField,fieldValue = input().split(",")
        notes[noteId-1][noteField]=fieldValue
    elif action == 3:
        print("Введите номер строки: \n")
        noteId = int(input())
        del notes[noteId-1] # Fix id/position bug
        for note in notes:
            if note['id']>noteId:
                note['id']-=1

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
tableprint(notes)
uiNoteInteraction()
tableprint(notes)
myfiles = []
