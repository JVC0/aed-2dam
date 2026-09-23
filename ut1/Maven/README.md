Ejercicio
Guarda las tres salidas en tus notas y localiza la ruta de Java utilizada por Maven. Ejecuta la práctica de la lección anterior.
![alt text](/image2.png)

Ejercicio
Cambia únicamente artifactId, ejecuta mvn validate y devuelve el nombre a gestor-tareas para continuar la ruta.

#### Antes
![alt text](image1.png)

#### Despues
![alt text](image.png)


Ejercicio
Ejecuta mvn clean y comprueba que desaparece target/. Reconstruye con mvn compile y ejecuta de nuevo.

#### Antes
![alt text](image-1.png)

#### Despues
![alt text](image-2.png)


El nombre del usuario Linux, sin contraseñas.
La salida de java -version, javac -version y mvn -version con JDK 17.
La salida de las mismas órdenes con JDK 21.
El valor utilizado para JAVA_HOME en cada caso.
La evidencia de BUILD SUCCESS con JDK 21.
El error obtenido al intentar construir con JDK 17 y una explicación de su causa.
El comando utilizado para instalar la segunda versión del JDK.
![alt text](image-5.png)

![alt text](image-3.png)

![alt text](image-4.png)

```bash
sudo apt install curl zip unzip
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk install java 17.0.13-tem
```

Ejercicio
Cambia el título y recompila. Retira temporalmente la dependencia y observa el error de compilación; después restáurala.
![alt text](image-6.png)


Ejercicio
Localiza el POM de Gson y el POM de tu aplicación. Explica por qué mvn install no publica el proyecto para otras personas.
porque mvn install instala el arctefacot y el pom en repositorio local

Ejercicio
Ejecuta la comprobación con y sin -Prepositorio-publico. Explica qué cambia y por qué el proyecto puede seguir descargando desde Central por defecto.

Lo que cambia es que no aparece el repositorio publico
![alt text](image-7.png)

![alt text](image-8.png)

![alt text](image-9.png)

Ejercicio
Añade la activación por propiedad al perfil informe y comprueba su presencia con mvn -Dinforme=true help:active-profiles. Mantén distribucion como optativo.

![alt text](image-10.png)

Ejercicio
Retira la declaración directa de commons-lang3 y compara el árbol. Restaura y después retira ambas dependencias de práctica para conservar el proyecto con Gson.

![alt text](image-11.png)

![alt text](image-12.png)

Ejercicio
Identifica en el POM efectivo de dónde salen las versiones de Gson y JUnit. No copies el POM efectivo sobre el original: es un resultado de diagnóstico.

![alt text](image-13.png)
![alt text](image-14.png)
