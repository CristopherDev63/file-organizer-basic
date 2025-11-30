# file-organizer-basic
*Resolviendo problemas de organización dentro de archivo*

### [v0.1.0] - 2025-11-30

---
## Requerimientos 
1. El sistema debe de procesar todos los archivos de un carpeta raíz específica.
2. Clasificara a base de su extensión de archivos con el fin agregarlo a una categoría.
3. Si el sistema detecta que no existe una subcarpeta para una extensión, se tendrá que crear con el nombre de la extensión sin su respectivo punto en mayúsculas.
4. El sistema movera el archivo a su respectiva carpeta.
5. Se debe solo excluir a los archivos de tipo `.py` y de tip *log*.

---
## Requerimientos Tecnicos 
* Uso de librerías estándar de Python como `os`, `pathlib`.
* Se incluirá manejo de errores para fallos básicos.
* El sistema tendra un sistema de registros de tipo log en archivos de texto con un formato `[fecha y hora] - Archivo movido: [nombre antiguo] -> [carpeta destino]`.

---
## Instalación Rapida 
Primero debe de clonar el repositorio del proyecto.
```bash
git clone https://github.com/CristopherDev63/file-organizer-basic.git 
```
Dentro de del proyecto se debe de crear un entorno virtual y activarlo.
``` bash
python -m venv venv 
```
Y hay que activarlo.

**Windows:**
```bash
venv\Scripts\activate.bat
```
**Unix (Linux/MacOS):**
```bash
source venv/bin/activate
```
Ya después de haber activado el entorno virtual se debe de instalar las dependencias que se encuentran en el `requirements.txt`.
```bash
pip install -r requirements.txt
```
