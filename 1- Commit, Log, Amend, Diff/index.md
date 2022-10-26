- "git log" : commit listesini görebiliriz. (commitlerin idlerini görebiliriz, id ile işlemler yapıcaz)

- "git commit --amend" : yeni eklenen bir şeyi , gönderilmiş commite dahil etmemizi sağlar. 

- "git commit --amend -m 'atılan commitin mesajını bu sekilde degistirebiliriz'

# Buraya bi liste ekleyelim:
    - "git log -n 2" : son 2 commiti görmemizi sağlar.

    - "git revert silmekIstedigimizCommitinIdsi" : commiti id'si sayesinde silmemizi sağlar. (commiti geri alir ve bu olayı yaptıgını göstermek icinde yeni bir commit atar. ve revert isleminin de bir id si olacagı icin revertinde reverti olabilir.)

    - "git reset --hard gitmekİstenilenCommitinIdsi" : idsi yazılan commite gider ve o comitten sonraki commitleri SİLER.