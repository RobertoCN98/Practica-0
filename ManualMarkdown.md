# Título (Con un almohadilla)
## Subtitulo (Más almohadilla es más pequeño)
### Subtitulo más pequeño
**Cosas que escribo pa que estén en negrita**
*Esto está en cursiva*

Lista: (Ordenado)
1. Objeto 1.
2. Objeto 2.
3. Objeto 3.

Lista: (Viñetas)
- Objeto 1.
- Objeto 2.
- Objeto 3.

![Imagen al azar](forest-8371211_1280.jpg)

| Nombre  | Apellido | DNI |
|---------|----------|-----|
| Roberto | Cabrera  | 254 |
| Oliver  | Marcos   | 745 |
| Jose    | Valiente | 745 |
| David   | Sida     | 745 |

>Esto es una cita.

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
[Link Markdown](https://www.markdownguide.org/basic-syntax/)
      
