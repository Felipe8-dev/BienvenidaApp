Este proyecto es una aplicación de bienvenida creada con Jetpack Compose, el enfoque moderno y declarativo para construir interfaces de usuario en Android. El código describe la interfaz directamente en Kotlin, lo que hace el desarrollo más intuitivo y rápido.

Componentes Clave
1. Organización conColumn
El diseño se construyó usando una Column. Este componente apila todos los elementos verticalmente. Se usaron horizontalAlignment y verticalArrangement para centrar todo el contenido (la imagen y los textos) perfectamente en la pantalla.

2. La Imagen (Image)
La foto se agregó usando el componente Image. Para darle forma y estilo, se encadenaron varios modificadores:

.size(160.dp): Define el tamaño de la imagen.

.clip(CircleShape): Recorta la imagen para que sea un círculo perfecto.

contentScale = ContentScale.Fit: Asegura que la imagen se ajuste completamente dentro del círculo sin recortar ninguna parte.

3. Los Textos (Text)
Se usaron dos componentes Text para los mensajes de bienvenida. Se aplicaron estilos como fontWeight = FontWeight.Bold para negrita y textAlign = TextAlign.Center para centrar el texto. El mensaje de bienvenida usa un salto de línea (\n) para que se muestre en dos líneas.

4. Espaciado conSpacer
Para que el diseño no se viera amontonado, se agregó el componente Spacer entre la foto y los textos. Esto crea un espacio en blanco y mejora la lectura.

Vista previa en Android Studio
Al final del código, la función @Preview te permite ver cómo se verá la interfaz en tiempo real, sin necesidad de ejecutar la aplicación en un emulador o dispositivo físico.
