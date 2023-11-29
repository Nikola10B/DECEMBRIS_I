def faktorials(skaitlis):
    rezultats = 1
    for i in range(1, skaitlis + 1):
        rezultats *= i
    return rezultats

if sk1 == "faktorialais":
    ievaditais_skaitlis = int(input("Ievadiet skaitli, lai aprēķinātu faktoriālu: "))
    rezultats = faktorials(ievaditais_skaitlis)
    print(f"{ievaditais_skaitlis} faktoriāls ir: {rezultats}")
