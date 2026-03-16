**MedBook – Sistem de programări la medici**

MedBook este o aplicație dezvoltată în C# , concepută pentru gestionarea programărilor la medici. Proiectul implementează un **REST API** care permite administrarea utilizatorilor (pacienți, medici), gestionarea specialităților medicale și crearea, modificarea sau anularea programărilor. Persistența datelor este realizată printr-o bază de date SQL, iar întregul sistem este configurat să ruleze în containere Docker folosind **docker-compose** (serviciu API + serviciu DB).

Funcționalitățile principale includ:

* Gestionarea medicilor, pacienților și specialităților (CRUD complet)
* Căutarea medicilor după specialitate
* Crearea și administrarea programărilor
* Validarea sloturilor orare și evitarea suprapunerilor
* Expunerea datelor prin DTO-uri și servicii dedicate
* Documentație API accesibilă prin Swagger

Proiectul respectă principiile arhitecturale cerute: separare pe straturi (Controllers, Services, Data, DTO), precum și implementarea unei arhitecturi scalabile bazate pe microservicii (API + DB).
