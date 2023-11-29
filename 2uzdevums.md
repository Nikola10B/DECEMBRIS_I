def pirmais_skaitlis():
    skaitlis = 1
    while skaitlis**2 <= 1000:
        skaitlis += 1
    return skaitlis

if sk1 == "skaitlis":
    rezultats = pirmais_skaitlis()
    print(f"Pirmo skaitli, kura kvadrāts ir lielāks par 1000, ir: {rezultats}")
