# Pruebas Caja Blanca
Este repositorio contiene ejemplos y ejercicios prácticos relacionados con pruebas de caja blanca en aplicaciones de software. Las pruebas de caja blanca son un enfoque de testing donde se verifica el funcionamiento interno del software, incluyendo estructura del código, flujos de control, y lógica interna.

## Contenido
El repositorio está organizado en las siguientes carpetas y archivos:

- src/: Contiene el código fuente de las aplicaciones sobre las que se realizan las pruebas.
- tests/: Contiene los scripts de pruebas unitarias y de integración.
- docs/: Documentación adicional y ejemplos teóricos sobre pruebas de caja blanca.
- README.md: Este archivo con la descripción del proyecto.

## Requisitos
Para ejecutar el código y las pruebas incluidas en este repositorio, es necesario contar con las siguientes herramientas:

- Python 3.x
- pytest (para ejecutar las pruebas)
- Git (para clonar el repositorio)

Puedes instalar las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

## Ejecución de Pruebas
Para ejecutar las pruebas de caja blanca, sigue estos pasos:

Clona este repositorio:

```bash
git clone https://github.com/jlborrego/Pruebas-caja-blanca.git
cd Pruebas-caja-blanca
```
Asegúrate de tener instaladas todas las dependencias necesarias:
```bash
pip install -r requirements.txt
```
Ejecuta las pruebas:
```bash
Copiar código
pytest tests/
```

## Ejecutar Todos los test
```bash
mvn test
```
## Ejecutar test de los métodos con tag add
```bash
mvn test -Dgroups="add"
```
## Ejecutar los test de una clase, por ejemplo la clase AddTest
```bash
mvn test -Dtest=AddTest test
```

## Estructura de Código
El código fuente en el directorio src/ sigue una estructura modular que facilita la creación y mantenimiento de las pruebas de caja blanca. Se recomienda revisar los scripts dentro de tests/ para comprender cómo se implementan las pruebas sobre las diferentes partes del código.


