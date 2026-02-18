# Simulador de los Tres Cerebros – Barbershop

## Descripción del proyecto

Este proyecto es una herramienta educativa interactiva desarrollada para la asignatura **Semiótica de la Imagen**. Su objetivo es demostrar cómo la teoría de los tres cerebros de Paul MacLean –reptiliano, límbico y neocórtex– se aplica en el diseño de una pieza gráfica real: un flyer de barbería. El usuario puede explorar los elementos visuales del flyer, comprender qué mensajes subconscientes activa cada capa cerebral y poner a prueba sus conocimientos mediante un cuestionario.

La interfaz combina una presentación atractiva con madera oscura y detalles dorados, evocando el ambiente de una barbería clásica, mientras que la lógica de capas (imágenes superpuestas con transparencia) permite visualizar cómo cada cerebro procesa distintos estímulos.

## Funcionalidades principales

- **Flyer interactivo con capas**: el diseño se compone de cuatro imágenes PNG superpuestas:
  - `Limbico_2.png`: fondo con ambiente cálido (iluminación, textura de madera) – presente siempre.
  - `Reptiliano.png`: logo de barba y calaveras, que apela al instinto territorial.
  - `Limbico_1.png`: silla de cuero acolchada, que evoca confort y emociones.
  - `Neurocortex.png`: información racional (dirección, URL, año 1968).

- **Botones de selección de cerebro**: al hacer clic en *Reptiliano*, *Límbico* o *Neocórtex*, la capa correspondiente se vuelve nítida mientras las otras se desenfocan u ocultan, y el panel derecho muestra información detallada sobre ese cerebro.

- **Panel informático dinámico**: para cada cerebro se despliega:
  - Elemento gráfico asociado.
  - Mensaje subconsciente (p. ej., *“Este es tu territorio, afirma tu presencia”*).
  - Psicología subyacente.
  - Pregunta que responde (p. ej., *«¿Es seguro?»*).
  - Aplicación práctica en diseño de barbería.

- **Botón de vista completa**: situado en la parte inferior, permite visualizar el flyer sin ningún desenfoque, mostrando todas las capas nítidamente para apreciar el diseño global. Al activarlo, se restablece la vista integral y se puede luego volver a seleccionar cada cerebro para ver el efecto de enfoque/desenfoque.

- **Cuestionario interactivo**: cuatro preguntas de opción múltiple que evalúan la comprensión de la teoría aplicada al flyer. Al finalizar, se muestra el número de aciertos y un mensaje de retroalimentación.

- **Botón de contacto al docente**: un enlace de correo (`c12139@utp.edu.pe`) que abre el cliente de correo predeterminado para facilitar consultas académicas.

## Tecnologías utilizadas

- HTML5, CSS3 y JavaScript (ES6) puros, sin librerías externas.
- Diseño responsivo, adaptable a distintos tamaños de pantalla.
- Uso de imágenes PNG con transparencia para la superposición de capas.
- Estética de barbería con paleta de colores cálidos, sombras y texturas.

## Instrucciones de uso

1. **Abrir el archivo**: descargue o clone el repositorio y abra `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, etc.).
2. **Explorar las capas**:
   - Haga clic en los botones superiores (*Reptiliano*, *Límbico*, *Neocórtex*) o directamente sobre las imágenes del flyer.
   - Observe cómo se desenfocan las capas no seleccionadas y cómo cambia la información en el panel derecho.
3. **Activar vista completa**: pulse el botón **Vista completa** para ver todas las capas nítidas a la vez. A partir de ahí, puede volver a seleccionar cualquier cerebro para recuperar el efecto de enfoque selectivo.
4. **Responder el cuestionario**: marque una opción por cada pregunta y presione **Comprobar respuestas**. Recibirá un resultado inmediato.
5. **Contactar al docente**: si tiene dudas, use el botón **Enviar mensaje al docente** para escribir un correo electrónico.

## Notas importantes

- Las imágenes (`Reptiliano.png`, `Limbico_1.png`, `Limbico_2.png`, `Neurocortex.png`) deben ubicarse en la misma carpeta que el archivo `index.html`. Si faltan, se mostrará un patrón de fondo de respaldo.
- Se recomienda utilizar imágenes PNG con transparencia para garantizar la correcta superposición de las capas.

## Créditos

- **Docente**: Mg. Mario Quiroz  
- **Curso**: Semiótica de la Imagen · 2026 · Semana 7   
- Basado en la teoría de los tres cerebros de **Paul MacLean**.

## Licencia

Este proyecto es de uso educativo y libre distribución para fines académicos.
