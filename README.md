# t06veeb1
Veebileht Spring Boot'i abil

compile:
mvn package

eelmist commandi sisestades peab olema oma projekti "juurkaustas" ntx t06veeb1/ ja kindlasti mitte src, main vms

compile jaoks peab olema pom.xml ja vajalikud kaustad src/main/java/springalgus/Rakendus.java

target kaust luuakse compile käigus

esimene mvn package võib aega võtta, sest tõmmatakse vajalikud lisad

kui compile oli edukas on lõpus näha BUILD SUCCESS, aga kui failis siis BUILD FAIL

tööle panemine:
<b>java -jar -Dserver.port=MINGISUGUNEPORT target/boot3-1.0-SNAPSHOT.jar</b>

server port võiks olla kõigil kasutajatel erinev ehk suvaline port 1025-65535

see mis faili nimi pärast target/ osa on oleneb pom.xml failist

lehe nägemine:
ssh tunnel nagu alati aga url on <b>greeny.cs.tlu.ee:MINGISUGUNEPORT</b>
