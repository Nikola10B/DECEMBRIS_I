# skaitlis_kvadrats.py
def cipars():
    skaitlis = 1
    while skaitlis**2 <= 1000:
        skaitlis += 1
    return skaitlis

if __name__ == "__main__":
    rezultats = cipars()
    print(f"Pirmo skaitli, kura kvadrāts ir lielāks par 1000, ir: {rezultats}")
