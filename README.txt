Setup:

1. Lade junit-platform-console-standalone.jar herunter
2. Lege es in dieses Verzeichnis

Kompilieren:
javac -cp .:junit-platform-console-standalone.jar *.java

Ausführen:
java -jar junit-platform-console-standalone.jar --class-path . --scan-class-path
