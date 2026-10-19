# Nebula Launcher: guía de uso

Nebula es un launcher para Minecraft: Java Edition. Desde aquí puedes iniciar sesión, crear instancias de juego, instalar mods y entrar a tus servidores favoritos.

Esta guía explica cómo moverte por el programa. Para las funciones con más detalle, consulta el [README técnico](nebula-launcher/README.md).

---

## 1. Primeros pasos

1. **Abre Nebula** y elige el idioma la primera vez. Si no está disponible el de tu sistema, se usa inglés. Puedes cambiarlo después en **Ajustes → Idioma y apariencia**.
2. **Añade una cuenta** con el botón de usuario de la barra lateral izquierda:
   - **Microsoft**: ventana oficial de Microsoft para iniciar sesión.
   - **Sin conexión**: solo para jugar en servidores que no comprueban la cuenta.
3. **Crea tu primera instancia** desde **Instancias → Nueva instancia**.
4. Pulsa **Jugar** en la instancia.

> Una instancia es una versión de Minecraft con sus propios mundos, mods y ajustes.

---

## 2. Estructura del programa

### Barra lateral izquierda

| Botón | Qué encuentras |
|---|---|
| **Inicio** | Lo que estabas jugando, tus últimos mundos (**Continuar jugando**), tus servidores favoritos y tus amigos. |
| **Instancias** | Todas tus instancias. Desde aquí creas, buscas y abres cada una. |
| **Registro** | El registro en directo del juego y del launcher, con filtros. Sirve para ver errores. |
| **Ajustes** | Configuración general de Nebula. |
| **Botón de cuenta** (abajo) | Cambiar de cuenta o añadir una nueva. |

### Pantalla de una instancia

Al abrir una instancia aparecen su nombre, su versión, su cargador (Vanilla, Fabric, Forge…) y los botones **Jugar**, **Abrir carpeta** y **Más opciones** (⋯).

Debajo hay pestañas:

- **Mods**: buscar, activar, desactivar o quitar mods. Si hay una versión nueva de un mod, aparece un punto en la pestaña y un icono para actualizarlo.
- **Packs y shaders**: instalar packs de recursos y shaders desde Modrinth.
- **Mundos**: entrar directamente, crear copias de seguridad y restaurarlas.
- **Capturas**: galería de capturas de pantalla de la instancia. Puedes copiarlas, abrirlas o borrarlas.
- **Ajustes**: nombre, versión, memoria, Java, ajustes gráficos del juego y otras opciones de esta instancia.

---

## 3. Tareas habituales

### Crear una instancia

**Instancias → Nueva instancia**. Eliges versión de Minecraft y cargador. Si quieres partir de un modpack, usa **Modpacks e importar** en la misma ventana.

### Instalar mods

1. Abre la instancia y ve a la pestaña **Mods**.
2. Usa el buscador para encontrar mods compatibles con la versión de la instancia.
3. Activa o desactiva un mod con su interruptor, o quítalo con el icono de papelera.

### Activar el pack de rendimiento

En la pestaña **Ajustes** de la instancia, activa **Pack de rendimiento**. Nebula instala mods de optimización compatibles con esa versión.

### Entrar a un servidor

En **Inicio** aparecen tus servidores favoritos con su estado en vivo (jugadores conectados y ping). Pulsa uno para entrar con la instancia que elijas.

Para que el juego entre directamente en un servidor al abrirlo, activa **Conectar al iniciar** en los ajustes de la instancia.

### Copias de seguridad de mundos

Nebula hace copias automáticas de tus mundos al cerrar el juego. Para hacer una a mano o restaurar una, ve a la pestaña **Mundos** de la instancia.

### Duplicar una instancia

Desde **Más opciones** (⋯) de la instancia, puedes duplicarla con o sin sus mundos.

### Cambiar la skin

En la cuenta de Microsoft, abre el editor de skins desde la pantalla de la cuenta. Puedes subir un PNG, elegir la capa o volver a la skin por defecto. Las skins que pruebas se guardan para volver a usarlas.

### Importar del launcher oficial

Si ya tienes perfiles en el launcher oficial de Minecraft, Nebula puede convertirlos en instancias. Tus archivos originales no se modifican.

---

## 4. Ajustes

**Ajustes** agrupa las opciones generales. Las principales:

- **Idioma y apariencia**: idioma de la interfaz.
- **Memoria y rendimiento**: memoria para el juego (automática o manual), tarjeta gráfica que usa Minecraft y prioridad del proceso.
- **Al jugar**: qué hace el launcher cuando abres el juego (por ejemplo, ocultarse).
- **Cuenta de Microsoft**: gestión de tus cuentas.
- **Discord**: muestra en tu perfil que estás en el launcher o jugando. Se puede desactivar.
- **Actualizaciones**: Nebula se actualiza solo. Aquí ves las novedades de cada versión y puedes buscar actualizaciones a mano.
- **Abrir con Windows**: Nebula se inicia al encender el PC.

Los cambios de **Memoria y rendimiento** en **Ajustes** se aplican a todas las instancias, salvo las que tengan ajustes propios.

---

## 5. Atajos de teclado

| Atajo | Acción |
|---|---|
| `Ctrl+K` | Buscador rápido: instancias, mundos, servidores y acciones |
| `Ctrl+Enter` | Jugar |
| `Ctrl+N` | Nueva instancia |
| `Ctrl+1` … `Ctrl+4` | Ir a Inicio, Instancias, Registro o Ajustes |
| `Ctrl+L` | Ir al registro |
| `F1` | Ver todos los atajos |
| `Esc` | Cerrar ventanas y buscadores |

En macOS se usa `⌘` en lugar de `Ctrl`.

---

## 6. Segundo plano y bandeja

- Al **cerrar la ventana**, Nebula se queda junto al reloj de Windows (la bandeja). Para cerrarlo del todo, usa el menú de la bandeja. Puedes cambiar este comportamiento en **Ajustes**.
- Mientras juegas, Nebula cierra su interfaz para dejar más memoria a Minecraft y vuelve a abrirse al instante cuando lo necesites.
- Desde la bandeja también puedes abrir una instancia directamente.

---

## 7. Problemas frecuentes

- **El juego no arranca**: abre **Registro** para ver el error. En la instancia, **Más opciones → Reparar archivos** vuelve a descargar los archivos dañados o que faltan.
- **Un mod no funciona**: revisa que sea compatible con la versión y el cargador de la instancia. Desactívalo con su interruptor para comprobar si era el causante.
- **No aparece Discord**: abre Discord en tu PC. Nebula intenta conectar cada 30 segundos.
- **No hay conexión a internet**: puedes jugar con lo que ya tienes instalado.

---

## Aviso

Nebula Launcher no es un producto oficial de Minecraft. No está aprobado ni asociado con Mojang ni con Microsoft. Minecraft es una marca de Mojang AB.
