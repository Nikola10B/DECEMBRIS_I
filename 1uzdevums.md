def saskaitisana(skaitlis):
    summa = 0
    for i in range(1, skaitlis + 1):
        summa += i
    return summa

if sk1== "saskaitisies":
    ievaditais_skaitlis = int(input("Ievadiet skaitli: "))
    rezultats = saskaitisana(ievaditais_skaitlis)
    print(f"Saskaitot no 1 līdz {ievaditais_skaitlis}, rezultāts ir: {rezultats}")
