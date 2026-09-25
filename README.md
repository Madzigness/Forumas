# Forumas
T120B165 Saityno taikomųjų programų projektavimas Projektas „Forumas“ Github saugykla

2.	Sistemos paskirtis
Projekto tikslas – sukurti forumo tipo internetinę platformą, skirtą naudotojams bendrauti, dalintis informacija, kurti diskusijas bei keistis nuomonėmis įvairiomis temomis.

Veikimo principas – kuriamą platformą sudaro dvi pagrindinės dalys: internetinė aplikacija, kuria naudosis registruoti ir neregistruoti naudotojai bei administratorius, ir aplikacijų programavimo sąsaja (angl. Application Programming Interface, API), užtikrinanti duomenų apsikeitimą tarp aplikacijos ir serverio.

Neregistruotas naudotojas galės peržiūrėti viešai prieinamas forumo diskusijas ir kitą platformoje skelbiamą informaciją. Norėdamas aktyviai dalyvauti diskusijose, naudotojas turės užsiregistruoti ir prisijungti prie sistemos.

Registruoti naudotojai galės kurti naujas diskusijų temas, rašyti komentarus, atsakyti į kitų naudotojų pranešimus, redaguoti arba šalinti savo sukurtą turinį bei reaguoti į kitų naudotojų pranešimus. Naudotojai taip pat galės peržiūrėti kitų forumo dalyvių informaciją ir sekti vykstančias diskusijas.
Administratorius prižiūrės forumo veiklą, valdys naudotojų paskyras bei užtikrins, kad platformoje skelbiamas turinys atitiktų nustatytas taisykles. Administratorius galės šalinti netinkamą turinį, valdyti naudotojų paskyras bei atlikti kitus sistemos administravimo veiksmus.

4.	Funkciniai reikalavimai

Neregistruotas sistemos naudotojas galės:
  1.	Peržiūrėti platformos reprezentacinį puslapį;
  2.	Peržiūrėti viešai prieinamas forumo diskusijas;
  3.	Peržiūrėti diskusijų temas ir jų pranešimus;
  4.	Prisijungti prie internetinės aplikacijos;
  5.	Užsiregistruoti platformoje.

Registruotas sistemos naudotojas galės:
  1.	Prisijungti prie internetinės aplikacijos;
  2.	Atsijungti nuo internetinės aplikacijos;
  3.	Redaguoti savo profilio informaciją;
  4.	Kurti naują diskusijų temą;
  5.	Redaguoti savo sukurtas diskusijų temas;
  6.	Šalinti savo sukurtas diskusijų temas;
  7.	Rašyti pranešimus diskusijų temose;
  8.	Atsakyti į kitų naudotojų pranešimus;
  9.	Redaguoti savo pranešimus;
  10.	Šalinti savo pranešimus;
  11.	Reaguoti į kitų naudotojų pranešimus;
  12.	Peržiūrėti kitų registruotų naudotojų profilius;
  13.	Ieškoti diskusijų temų ir pranešimų;
  14.	Peržiūrėti kitų naudotojų sukurtas diskusijas;
  15.	Pranešti administratoriui apie netinkamą turinį.

Administratorius galės:
  1.	Peržiūrėti registruotų naudotojų informaciją;
  2.	Valdyti naudotojų paskyras;
  3.	Šalinti naudotojus;
  4.	Redaguoti arba šalinti netinkamas diskusijų temas;
  5.	Šalinti netinkamus naudotojų pranešimus;
  6.	Peržiūrėti naudotojų pateiktus pranešimus apie netinkamą turinį;
  7.	Valdyti forumo kategorijas;
  8.	Tvarkyti kitą su forumo veikimu susijusią informaciją.
  
4.	Sistemos architektūra
Sistemos sudedamosios dalys:
•	Kliento pusė (angl. Front-End) – interneto naršyklėje veikianti vartotojo sąsaja, sukurta naudojant HTML, CSS ir PHP; 
•	Serverio pusė (angl. Back-End) – naudojant PHP programavimo kalbą; 
•	Duomenų bazė – MySQL.

pav. 1 pavaizduota kuriamos forumo tipo svetainės diegimo diagrama.
Sistemos veikimui ir testavimui naudojama XAMPP serverio aplinka, kurioje veikia Apache žiniatinklio serveris ir MySQL duomenų bazė. Kiekviena sistemos dalis vykdoma tame pačiame kompiuteryje, naudojant XAMPP aplinką.
Internetinė aplikacija yra pasiekiama per HTTP protokolą. Vartotojas, naudodamasis interneto naršykle, siunčia užklausas į Apache serverį, kuris apdoroja PHP programos kodą ir grąžina sugeneruotą turinį vartotojui.
Sistemoje naudojama MySQL duomenų bazė, kurioje saugoma forumo informacija, tokia kaip vartotojų duomenys, forumo temos, pranešimai ir kita su sistemos veikimu susijusi informacija. Duomenų bazei administruoti naudojamas phpMyAdmin, kuris yra XAMPP aplinkos dalis. PHP programa sąveikauja su MySQL duomenų baze naudodama duomenų bazės prisijungimo ir užklausų mechanizmus.

 <img width="761" height="434" alt="Model" src="https://github.com/user-attachments/assets/f84e19ae-cb2b-4035-a912-2fe339c7283a" />
pav. 1 Sistemos Forumas diegimo diagrama

Projekto Github link: https://github.com/Madzigness/Forumas
