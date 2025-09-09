# Verziókezelés git

- helyi repo létrehozása:
    
    > git init 
    
- ellenőrzés: milyen fájlok változtak(az előző verzióhoz képest)
    >git status
- Előkészítjük(stage=színpad) az új verziót, minden fájlt amiben történt módosulás:
    >git add .
- ellenőrzünk:
    > git status
- felhasználó név beállítása:
    >git config user.name kdani921
- emailcím beállítása:
    > git config user.email "kdani921@gmail.com"
- az új verzió megszületése:
    > git comit -m "first commit"
- távoli repo létrehozása(Github)