# Header ile alakalı branch actık ve header ile alakalı kodlar burada yer alacak

# Liste olusturalım: 
    -Button1
    -Button2
    -Button3

   " headerda bu degisiklikleri yaptık ama yapacagımız islem  daha bitmedi bu yüzden commit atamayız. Onun yerine geçici olarak kaydedebilecegimiz bir ortam var ona da 'stash' denir(***git log yaparsak commit olarak görmeyiz** bu bir commit degildir.) kullanmak için: "
- "git stash" kodunu kullanmamız gerekir.

- "git stash list" : stashte kaydettigimiz commitleri görmemizi saglar.

- "git stash clear" : stashteki commiti siler.

- "git stash pop" : stashin en üstündeki commiti getirmemizi sağlar ve stashten bunu siler

- "git stash apply stash@{0}" : stashteki işlemi geri getirir ama stashten bunu silmez. (stash@{0} yerine getirmek istedigimiz stash idsi yazılır.)


