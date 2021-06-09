# d43-RobertsKristiansMarkuns-sthenos

## Projekta apraksts

Šis ir PIKC "Rīgas Valsts tehnikums" kvalifikācijas darbs. Mans mērķis ir izveidot mobilo aplikāciju, kas palīdzēs cilvēkiem karantīnas laikā palikt aktīviem, kas  atrodoties mājas sēž pie datora visu dienu nekustās un nestaipās, kas var novest pie sliktas pašsajūtas un pat veselības problēmam. Ar aplikācijas palīdzibu lietotājs spēs palikt aktivs, kas uzlabos pašsajūtu un mazinās risku sabojāt savu fizisko veselību. Aplikācija var apskatīt vingrinājumus un ekipējumu, izveidot savu ToDo list, izmantot hronometru un vingrinājuma izpildes reižu skaita ģenerēšanu, kā arī uzstādīt atgādinājums/paziņojumus.

## Izmantotās tehnoloģijas
- Java
- PHP
- MySQL
- SQLite

## Izmantotie avoti
1.	Spraudņa repozitorija - https://github.com/Vincent-Loi/android-drawable-importer-intellij-plugin
2.	Spraudņa uzstādīšana - https://stackoverflow.com/questions/60412216/android-drawable-importer-plugin-not-working-in-android-studio-3-6/60795443
3.	Funkcijas, notikumi, metodes, uzskati utt. - https://developer.android.com/docs 
4.	Pogas ar apaļiem galiem veidošana pamācībā - https://medium.com/@addeeandra/androidstarter-1-i-want-a-round-button-636bc5553d6d 
5.	Gradienta veidošanas pamācībā - https://www.youtube.com/watch?v=v8fDkKB-Vz0 
6.	Pieslēgšanās ekrāna dizains pamācībā - https://www.youtube.com/watch?v=C_TEugAIMHA 
7.	Reģistrācijas ekrāna dizains pamācībā - https://www.youtube.com/watch?v=aU8dWySoMOU 
8.	Sākuma ekrāna dizaina pamācībā - https://www.youtube.com/watch?v=8oXGXefm4go 
9.	Navigāciju joslu pamācības – 
 9.1.	https://www.youtube.com/watch?v=HwYENW0RyY4
 9.2.	https://www.youtube.com/watch?v=m1RV0HPuBWo
 9.3.	https://www.youtube.com/watch?v=lt6xbth-yQo
10.	‘Splash screen’ veidošanas pamācība - https://www.youtube.com/watch?v=JLIFqqnSNmg
11.	Pārstrādātāj Skata režģa izkārtojuma - https://www.youtube.com/watch?v=cYjX6_TL_EA
12.	Hronometra veidošanas dizains - https://www.youtube.com/watch?v=gqn7HqTnOPA&t=607s
13.	Peldošas navigācijas joslas dizains - https://www.youtube.com/watch?v=ePEjNoH-Dlw
14.	Darāmo lietu saraksts veidošana – https://blog.frsarker.com/java/create-a-todo-task-app-using-java-in-android.html
15.	PHP - https://www.youtube.com/watch?v=X8oD4q3XtQQ’
16.	Atgādinājums veidošana un dizains – 
 16.1.	https://developer.android.com/jetpack/androidx
 16.2.	https://developer.android.com/reference/android/app/Notification.Builder
 16.3.	https://developer.android.com/reference/android/app/Notification
 16.4.	https://www.youtube.com/watch?v=yrpimdBRk5Q

## Uzstādīšanas instrukcijas
Uz datora ar emulatoru:

1. Jābut lejupielādētam Android Studio un XAMPP;
2. Jāparliecinas ka uz datora ir iespējota Virtualizācija(VTx),
to var pārbaudīt ar CMD vai run, CMD ierakstot 'systeminfo.exe' un run ierakstot 'msinfo32' pēc tam jāatrod sadaļa "Virtualization enabled in Firmware",
ja blakus ir "Yes" tālāk nekas nav jādara, ja ir "No" tad jāseko šai [Pamācibai](https://www.youtube.com/watch?v=MOuTxfzCvMY);
3. XAMPP jāpalaiž MySQL un Apache, ja ir aizņemts, kāds ports tad tos var nomainīt šādi:
- config(augšeja labajā stūri)->Service Port settings un tad nomaina Apache vai MySQL, ja kāds ir aizņemts;
4. XAMPP mapē 'htdocs' jāievieto mape 'SthenosPHP';
5. Tad Android studio atver mapi database,
kur LoginActivity.java(111 koda rinda) un SignUpActivity.java(122 koda rinda) jānomaina "IPv4Adress" pret savu IPv4 adresi,
kuru var atrast CMD ierakstot 'ipconfig';
6. phpMyAdmin jaievieto sthenos.sql, kas atrodas kods/MySQL.

Uz **Android** mobilās ierīces:
1. Lejupielādes [Links](https://drive.google.com/file/d/1psPFnzMi-HjviDeoUUrzyjiY--bD-Vpr/view?usp=sharing);
2. Lai tiktu aplikācija jānospiež Login ekrāna uz cilvēciņa logo.



