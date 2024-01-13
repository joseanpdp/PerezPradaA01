# FLUTTER

# Ejercicio 1

- **Autor**: José Antonio Pérez de Prada
- **Asignatura**: Acceso a Datos

## Enunciado

Deberás crear un proyecto correctamente nombrado y crear su repositorio en Github. La aplicación deberá parecerse al figma proporcionado. Como extra deberá poder hacer scroll en la pantalla.

## Resultado

![](recursosReadme\diseño.png)

(A pesar de que se requería un Scrollbar para el ejercicio, no ha sido posible implementarlo debido a que implicaría rehacer completamente el ejercicio desde 0)

La aplicación está estructurada mediante un widget Center que tiene como hijo un Column. La justificación de esta decisión está en que así toda la columna de contendores tendrá a sus hijos centrados.

Dentro de Column tenemos un array de hijos que son widgets de tipo Expanded para que los contenedores ocupen por completo la ventana horizontalmente.

Como se ha mencionado, cada Expanded tiene como hijo un Container. Cada uno tiene diferentes contenidos:

1. Un texto
2. Un widget Row con 3 Containers de colores anidados
3. Un widget Column con 3 Containers de colores anidados
4. Un widget Row con dos Expanded anidados que dentro tienen un Row con 3 Conatiners anidados y un Column con 3 Contianser anidados respectivamente.
5. Este se diferencia del anterior porque el primer Containser es más grande que el segundo con la propiedad flex.