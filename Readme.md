##HTW Connect Programmierwettbewerb##

###�bersetzen des Programms###

Um das Programm zu �bersetzen muss [Maven][] auf dem System installiert sein.

1. Zum Quellcode navigieren:

		cd /path/to/src/folder

2. Das Projekt "bauen"
	
		mvn clean package

Maven l�dt nun die ben�tigten Bibliotheken herunter und generiert eine JAR-Datei mit dem Namen **encoder.jar**.

###Ausf�hren des Programms###

Das Programm kann nach dem kompilieren wie folgt ausgef�hrt werden:

	java -jar encoder.jar inputFile.txt outputFile.txt

###Hinweise###

* Die Unit-Tests k�nnen wie folgt gestartet werden:  

		cd /path/to/src/folder
		mvn test

* Als Eingabedatei k�nnen (mit Absicht) nur Dateien im ASCII-Format genutzt werden, da nur f�r diese eine Codierung vorgegeben wurde. 

###Kontakt###

Name: Andr� Schommer  
EMail: [andre.schommer@googlemail.com](mailto:andre.schommer@googlemail.com)

 [Maven]: <http://maven.apache.org/download.cgi> "Maven Download Page"