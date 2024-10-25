<!--Con las almohadillas podemos poner títulos y subtítulos, a menos almohadillas más título es-->
# Título (Con un almohadilla)
## Subtitulo (Más almohadilla es más pequeño)
### Subtitulo más pequeño

<!--Con dos asteríscos para poner lo en negrita a los dos lados-->
***Cosas que escribo para que estén en negrita***

<!--Con un asterísco lo ponemos en cursiva-->
*Esto está en cursiva*

<!--Creamos listas ordenadas, con números romanos, por orden alfabético, etc.-->
Lista: (Ordenado)
1. Objeto 1.
2. Objeto 2.
3. Objeto 3.

<!--Creamos una lista si que importe el orden y pudes usar +, -, etc.-->
Lista: (Viñetas)
- Objeto 1.
- Objeto 2.
- Objeto 3.

<!--De esta manera combinamos los dos tipos de listas-->
Lista combinada:
1. objeto 1.
2. Objeto 2.
   - sub objeto 1.
   - sub objeto 2.
3. Objeto 3.

<!--Para poder subir una foto primero tenemos que guardarla dentro de github, y poner la ruta del propio porgrama-->
![Imagen al azar](forest-8371211_1280.jpg)

<!--De esta manera podemos hacer tablas en Markdown-->
| Nombre  | Apellido | DNI |
|---------|----------|-----|
| Roberto | Cabrera  | 254 |
| Oliver  | Marcos   | 745 |
| Jose    | Valiente | 745 |
| David   | Sida     | 745 |

<!--Es una manera de colocar información útil y que resalte.-->
>Esto es una cita.

<!--Sirve para poder enseñar código de una manera más elegante.-->
Mi código

      /**
       * @param args the command line arguments
       */
      public static void main(String[] args) {
          char[][] negroBlanco = new char[8][8];

          for (int i = 0; i < 8; i++) {
              for (int j = 0; j < 8; j++) {
                  if ((i + j) % 2 == 0) {
                      negroBlanco[i][j] = 'B';
                  } else {
                      negroBlanco[i][j] = 'N';
                  }
              }
          }

          for (int i = 0; i < 8; i++) {
              for (int j = 0; j < 8; j++) {
                  System.out.print(negroBlanco[i][j] + " ");
              }
          System.out.println("");
      }
<!--De esta manera podemos colocar links, a fuera de nuestra página.-->
[Link Markdown](https://www.markdownguide.org/basic-syntax/)
      
