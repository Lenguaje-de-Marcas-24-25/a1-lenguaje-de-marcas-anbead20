# UD1 A1: Lenguajes de marcas

1. **Indica qué es un lenguaje de marcas**  
   Un lenguaje de marcas es un sistema de notación que utiliza etiquetas (o marcas) para definir y estructurar elementos dentro de un documento o conjunto de datos. Estas marcas proporcionan información sobre cómo debe ser presentado o interpretado el contenido. Los lenguajes de marcas son comúnmente utilizados en el ámbito del desarrollo web, la edición de documentos y la organización de información.
2. **Características generales de los lenguajes de marcas.**
    - Texto plano
    - Compactibilidad
    - Independencia del dispositivo final
    - Especialización
    - Flexibilidad
3. **Clasifica los lenguajes de marcas e identifica los más relevantes.**  
Normalmente los lenguajes de marcas se suelen clasificar en tres tipos, atendiendo al
tipo de marcas que utilizan:
   - De presentación
   - Descriptivo, estructural o semántico
   - Híbrido

    Lenguajes de marcas más relevantes a nivel general:
    - HTML: El lenguaje más importante en la web para estructurar contenido.
    - XML: Fundamental en el intercambio de datos estructurados en múltiples industrias.
    - Markdown: Popular en el ámbito de la escritura de documentación y contenido web ligero.
    - LaTeX: El estándar en la creación de documentos científicos y matemáticos.
    - JSON: A menudo se utiliza en lugar de XML para el intercambio de datos, especialmente en aplicaciones web.
 
4. **Indica los distintos ámbitos de aplicación de los lenguajes de marcas.**
   - Desarrollo web
   - Ámbito científico
   - Gráficos vectoriales
   - Metainformación 
   - Bases de datos
   - Intercambio de información
   - Mensajería
5. **Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:**
   1. HTML 
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>Mi primera página web</title>
    </head>
    <body>
        <h1>¡Hola, mundo!</h1>
        <p>Este es mi primer ejemplo de HTML básico.</p>
    </body>
    </html>
    ```
   2. iCalendar
    ```ical
    BEGIN:VCALENDAR
    VERSION:2.0
    PRODID:-//Mi Calendario Básico//ES
    BEGIN:VEVENT
    UID:12345678@example.com
    DTSTAMP:20231001T120000Z
    DTSTART:20231010T100000Z
    DTEND:20231010T110000Z
    SUMMARY:Reunión con el equipo
    DESCRIPTION:Reunión semanal para discutir el progreso del proyecto.
    LOCATION:Oficina 301
    END:VEVENT
    END:VCALENDAR
    ```
   3. vCard 
    ```vcf
    BEGIN:VCARD
    VERSION:3.0
    FN:Juan Pérez
    N:Pérez;Juan;;;
    ORG:Mi Empresa S.A.
    TEL;TYPE=WORK,VOICE:+34-123-456-789
    EMAIL:juan.perez@example.com
    ADR;TYPE=WORK:;;Calle Falsa 123;Madrid;;28000;España
    END:VCARD
    ```
   4. KML
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <kml xmlns="http://www.opengis.net/kml/2.2">
        <Placemark>
            <name>Mi ubicación</name>
            <description>Este es un lugar de interés.</description>
            <Point>
                <coordinates>-3.703790,40.416775,0</coordinates>
            </Point>
        </Placemark>
    </kml>
    ```
   5. RSS
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <rss version="2.0">
        <channel>
            <title>Mi Blog de Tecnología</title>
            <link>https://www.miblogdetechnologia.com</link>
            <description>Últimas novedades y artículos sobre tecnología.</description>
        <item>
            <title>Artículo 1: Introducción a la Inteligencia Artificial</title>
            <link>https://www.miblogdetechnologia.com/articulo1</link>
            <description>Un artículo que explora los conceptos básicos de la inteligencia artificial.</description>
            <pubDate>Tue, 01 Oct 2024 12:00:00 +0000</pubDate>
            <guid>https://www.miblogdetechnologia.com/articulo1</guid>
        </item>
        <item>
            <title>Artículo 2: Las Mejores Aplicaciones de 2024</title>
            <link>https://www.miblogdetechnologia.com/articulo2</link>
            <description>Una revisión de las mejores aplicaciones de este año.</description>
            <pubDate>Wed, 02 Oct 2024 12:00:00 +0000</pubDate>
            <guid>https://www.miblogdetechnologia.com/articulo2</guid>
        </item>
    </channel>
    </rss>
    ```