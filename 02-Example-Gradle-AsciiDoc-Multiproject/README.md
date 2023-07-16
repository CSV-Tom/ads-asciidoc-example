# AsciiDoctor Gradle Multiproject

Dieses Repository ist ein Template-Projekt für die Erstellung von Dokumentationen in den Formaten EPUB, HTML und PDF mithilfe der AsciiDoctor-Syntax. Das Projekt ist als AsciiDoctor Gradle Multiproject strukturiert und enthält mehrere Subprojekte, die als Beispiele für Bücher und Artikel dienen.

## Inhalte

Das Template bietet eine vorbereitete Ordnerstruktur und Konfiguration, um das Erstellen von Dokumentationen mit AsciiDoctor und Gradle zu erleichtern. Die Hauptinhalte des Projekts sind:

- Vorlagen für Bücher und Artikel: Die Subprojekte dienen als Vorlagen, die du nutzen kannst, um deine eigenen Dokumentationen zu erstellen. Du kannst die vorhandenen Subprojekte als Ausgangspunkt nehmen und sie an deine spezifischen Anforderungen anpassen.

- Beispielinhalte: Die Subprojekte enthalten bereits Beispieldateien und -inhalte, um dir den Einstieg zu erleichtern. Du kannst diese Inhalte bearbeiten oder eigene Inhalte hinzufügen, um deine Dokumentation zu gestalten.

## Verwendung

Um das Template-Projekt zu nutzen, kannst du es klonen und die Inhalte anpassen, um deine eigene Dokumentation zu erstellen. Die vorhandenen Subprojekte dienen als Ausgangspunkt und können nach Bedarf erweitert oder angepasst werden. Du kannst auch neue Subprojekte hinzufügen, um weitere Dokumentationen zu erstellen.

## Bauen

Um das Projekt zu bauen, führe einen der folgenden Befehle aus:

```bash
./gradlew build --parallel
./gradlew build --continuous
```

Diese Befehle kompilieren das Projekt und generieren die Dokumentationen in den verschiedenen Formaten.

## Bereitstellung

Es gibt verschiedene Möglichkeiten, das Projekt bereitzustellen:

1. **Variante I**: Du kannst das Projekt mit dem Befehl `./gradlew build` kompilieren und die generierten Artefakte im `build`-Verzeichnis finden. Du kannst den `outputDir`-Parameter in der Konfiguration anpassen, um den Ausgabeort zu steuern.

2. **Variante II**: Der Befehl `./gradlew aggregateArtifacts` sammelt die Artefakte aller Subprojekte und legt sie an einem zentralen Ort ab. Du kannst den Zielordner für die aggregierten Artefakte in der Gradle-Konfiguration anpassen.

3. **Variante III**: Mit den Befehlen `./gradlew distTar`, `./gradlew distZip` und `./gradlew installDist` kannst du das Projekt als Distribution verpacken und bereitstellen. Diese Befehle erstellen Archive oder installieren das Projekt als Distribution.

## Kommunikation

Wir freuen uns über dein Interesse an diesem Projekt! Wenn du Fragen hast oder Verbesserungsvorschläge einbringen möchtest, kannst du gerne die Issues nutzen oder uns per E-Mail kontaktieren.

Lasst uns großartige Dokumentationen erstellen!

*Hinweis: Dieses README.md dient lediglich als Beispiel und kann entsprechend den Anforderungen und Besonderheiten deines eigenen Projekts angepasst werden.*

Quellen:
- AsciiDoctor-Dokumentation: [https://asciidoctor.org/docs/](https://asciidoctor.org/docs/)
- Gradle-Dokumentation: [https://docs.gradle.org/](https://docs.gradle.org/)