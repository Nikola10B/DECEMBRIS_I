import datetime

def noteikt_sveicienu():
    stunda = datetime.datetime.now().hour

    if 6 <= stunda < 12:
        return "Labrīt!"
    elif 12 <= stunda < 18:
        return "Labdien!"
    else:
        return "Labvakar!"

if sasveicinasanas == "stunda":
    sveiciens = noteikt_sveicienu()
    print(sveiciens)
