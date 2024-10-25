# Biblioteca de operaciones matematicas basicas

## Descripcion
Esta biblioteca contiene las operaciones basicas de suma, resta, multiplicacion y division para el tipo double.
Esta biblioteca está diseñada para ser sencilla de integrar y utilizar en cualquier proyecto Java, proporcionando métodos estáticos que simplifican su uso sin necesidad de instanciar objetos.

## Por que Maven ?
Maven facilita la inclusión de dependencias externas. Simplemente se instalan en el repositorio local y se agregan en el archivo pom.xml y maven automáticamente se encarga de agregarlas al proyecto.
También facilita la creación y empaquetado de proyectos o nuevas librerias.

## Instalación

Para instalar la biblioteca
#### 1. Descargamos el jar en [releases](https://github.com/IrvinTM/operaciones/releases/tag/operaciones)

#### 2. Instalamos con maven

En este caso lo tengo en el directorio /home/irvin/Downloads/
```bash
mvn install:install-file -Dfile=/home/irvin/Downloads/operaciones-1.0-SNAPSHOT.jar
```
#### 3. Agregamos la dependencia en el archivo pom.xml
Ahora que ya tenemos la biblioteca instalada en nuestro repositorio local, podemos agregarla como dependencia en nuestro pom.xml en el apartado de dependencies.

```xml
<dependencies>
    <dependency>
        <groupId>com.irvin</groupId>
        <artifactId>operaciones</artifactId>
        <version>1.0-SNAPSHOT</version>
    </dependency>
</dependencies>
```
### 4. Instalamos en el proyecto
Hacemnos mvn install para que maven agregue la dependencia al proyecto.
```bash
mvn install
```
Listo ya tenemos la librería instalada en nuestro proyecto y podemos utilizarla.



