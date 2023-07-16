# Gradle AsciiDoctor Example

## Build PDFs

Create PDF documents with Gradle and Java.

```
./gradlew build

```

## Open PDFs

Open the PDFs with a PDF viewer of your choice. I have used PDF-Viewer Okular.

```
okular ./build/docs/asciidocPdf/GraphExample.pdf
okular ./build/docs/asciidocPdf/BookExample.pdf
```

## Links

- https://asciidoctor.org/docs/
- https://asciidoctor.github.io/asciidoctor-gradle-plugin/development-3.x/user-guide/

# Notes

- Use Java Development Kit (JDK) in version 8, 11 or 14
- Use a gradle wrapper version before 7.0 (e.g. 6.9)
