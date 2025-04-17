# Lil-Notiz
	Futtatás módja:

1.	Követelmények telepítése:
  a.	Töltsük le és telepítsük a Visual Studio 2022 vagy újabb verzióját.
  b.	Győződjünk meg róla, hogy a szükséges adatbázis-kezelő is elérhető.
2.	Projekt letöltése:
  a.	Klónozzuk a projektet Git-ről, vagy más módon másoljuk le a projekt mappát a gépre.
3.	Adatbázis inicializálása:
  a.	A backend alkalmazás első indításakor az Entity Framework Core automatikusan létrehozhatja az adatbázist (Migrations használatával).
4.	Projekt indítása:
  a.	Visual Studio-ban nyissuk meg a .sln fájlt.
  b.	Állítsuk be a backend projektet induló projektként, majd a blazort követketőnek.
  c.	Nyomjunk a Start gombra vagy használjuk a dotnet run parancsot a terminálban.
5.	Frontend elérés:
  a.	Először az API indul el, biztosítva az adatszolgáltatást, majd betöltődik a Blazor frontend a böngészőben. 
  b.	A felhasználó innen elérheti a webes felületet, bejelentkezhet, létrehozhat jegyzeteket, kategóriákat stb.
