# Generador De Informes Automatizados
Este proyecto es una aplicación en Python y Streamlit que permite a los usuarios crear informes personalizados, plantillas y archivos Excel de manera automatizada. La herramienta está diseñada para facilitar la creación de documentos, gestionando datos de manera flexible y profesional. Ideal para informes de gastos, presupuestos o cualquier tipo de documento que requiera formatos personalizados.

## Características
- **Generación de Informes Personalizados**: El usuario puede crear informes en formato Word con encabezado, contenido principal y pie de página personalizados.
- **Plantilla a Medida**: Permite configurar el estilo, márgenes y contenido de documentos que pueden ser reutilizados.
- **Exportación a Excel**: Facilita la creación de archivos Excel para presupuestos o gastos, permitiendo seleccionar monedas y configurar columnas.
- **Exportación a PDF**: La funcionalidad permite convertir el contenido del informe en formato PDF.

## Tecnologías Utilizadas
- **Python**
- **Streamlit**
- **Docx** para generación de documentos Word
- **Pandas** para manipulación de datos
- **PDFKit** para exportación a PDF
- **OpenPyXL** para exportación de datos a Excel
- **BytesIO** para manipulación de archivos en memoria

## Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/ezequiel-dev93/informes_automatizados.git
2. Navega al directorio del proyecto:
   ```bash
   cd informes_automatizados

3. Crea un entorno virtual (opcional pero recomendado):
   - Si no tienes instalado virtualenv, instálalo primero:
     ```bash
     pip install virtualenv
    - Crea el entorno virtual: 
      ```bash
      virtualenv venv
     - Activa el entorno virtual:
       - Windows:
         ```bash
         venv\Scripts\activate
        - macOS/Linux:
          ```bash
          source venv/bin/activate
4. Instala los paquetes requeridos:
   ```bash
   pip install -r requirements.txt
5. Ejecuta la aplicación:
   ```bash
   streamlit run App.py

~~~ 
Nota: Instalación adicional de pdfkit
Para exportar a PDF, pdfkit necesita que tengas instalado wkhtmltopdf, un programa externo.
Aquí tienes cómo instalarlo:

1. Windows :
* Descarga el instalador de wkhtmltopdf para Windows.
* Instálalo y añade la ruta de wkhtmltopdf.exe al PATH del sistema para que pdfkit lo reconozca.

2. MacOS: brew install wkhtmltopdf

3. Linux: sudo apt-get install wkhtmltopdf
~~~

## Uso
Al iniciar la aplicación, el usuario puede seleccionar entre tres opciones principales:
* Generar Informe: Crea un documento Word con formato personalizado.
* Crear Plantilla: Permite crear y guardar plantillas para informes.
* Crear Excel: Genera un archivo Excel con columnas definidas por el usuario y opciones de moneda.

## Contribución
Este proyecto es de código abierto. Las contribuciones son bienvenidas.
Para proponer cambios, realiza un fork del repositorio y envía una solicitud de extracción (PR).

¡Espero que esta herramienta te sea útil! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o contactarme.
