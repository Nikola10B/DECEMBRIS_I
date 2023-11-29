def neparucipars(skaitlis):
    if skaitlis % 2 != 0:
        return True
    else:
        return False

if sk1 == "sk2":
    ievaditais_skaitlis = int(input("Ievadiet skaitli: "))
    
    if neparucipars(ievaditais_skaitlis):
        print(f"{ievaditais_skaitlis} ir nepāra skaitlis.")
    else:
        print(f"{ievaditais_skaitlis} ir pāra skaitlis.")
