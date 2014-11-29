zadania na zaliczenie

MongoDB a Oracle
========
<p>Jak się okazało na zajęciach moje importy trwały dużo dłużej niż studentów, których projekty były przeglądane.</p>
<p>Prawie 14 godzin u mnie do kilkunastu minut a nawet kilku minut w przypadku bazy Oracle. W bazie Mongodb było nieco lepiej.</p>
<p>Pytanie - jaki był powód tak długiego importu? Jak widać na jednym z obrazków zużycie procesora było 100%</p>
<p>Pracowałam na systemie operacyjnym Linux Centos (maszynie wirtualnej). Może należałoby zmienić sprzęt :) ? Albo dostosować tak aby procesor był bardziej przyjazny </p>

 <p>Import do bazy Mongodb przy użyciu mongoimport</p>
 <img src="https://github.com/wardzinskaj/nosqlzal/blob/master/java_project/mongodb_import.png"> 
 <p>Statystyki systemu podczas importu - Mongodb</p>
 <img src="https://github.com/wardzinskaj/nosqlzal/blob/master/java_project/mongodb_system.png"> 
 
 <p>Zliczenie zaimportowanych rekordów w bazie Mongodb. </p>
 <img src="https://github.com/wardzinskaj/nosqlzal/blob/master/java_project/mongo_count.png"> 
 
 
 <p>Import do bazy Oracle przy użyciu sqlldr wraz ze statystykami systemu. </p>
 <img src="https://github.com/wardzinskaj/nosqlzal/blob/master/java_project/oracle_system.png">

<p>Zliczenie zaimportowanych rekordów w bazie Oracle. </p>
<img src="https://github.com/wardzinskaj/nosqlzal/blob/master/java_project/oracle_count.png">
<p></p>
<p>Czas importu do bazy Oracla wyniósł 13 godzin i 47 minut podczas gdy do bazy Mongodb tylko 27 minut.</p>
<p>Import do bazy Mongodb zużywał zdecydowanie mniej zasobów procesora oraz mniej pamięci RAM.</p>
<p>W przypadku importu do bazy Oracle obciążenie procesora jest przez większość czasu maksymalne</p>
