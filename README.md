# Java Project

Dieses Projekt ist ein Beispiel für ein Standard-Java-Projekt mit Maven. Es enthält eine einfache `Main`-Klasse, die "Hello, World!" ausgibt.

## Voraussetzungen

- Java 17 oder höher
- Maven

## Ausführung

1. Kompilieren Sie das Projekt:

   ```bash
   mvn compile
   ```

2. Führen Sie die Anwendung aus:
   ```bash
   mvn exec:java -Dexec.mainClass="com.example.Main"
   ```

## Tests

Führen Sie die Tests mit Maven aus:

```bash
mvn test
```
