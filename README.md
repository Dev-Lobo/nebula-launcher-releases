# Nebula Launcher: guía de uso

Nebula es un launcher para Minecraft: Java Edition, para Windows y Linux. Desde aquí puedes iniciar sesión, crear instancias de juego, instalar mods y entrar a tus servidores favoritos.

---

## 1. Primeros pasos

1. **Instala Nebula**:
   - **Windows**: ejecuta `NebulaLauncher-Setup-<versión>.exe`.
   - **Linux**: el `.AppImage` funciona en cualquier distribución (dale permiso de ejecución con clic derecho → Propiedades → «Permitir ejecutar», o `chmod +x`). En Ubuntu, Debian y derivadas también puedes instalar el `.deb`.
2. **Abre Nebula**. Sale en el idioma de tu sistema (si no está disponible, en inglés). Puedes cambiarlo en **Ajustes → Idioma y apariencia**.
3. **Añade una cuenta** con el botón de cuenta de abajo a la izquierda:
   - **Microsoft**: ventana oficial de Microsoft para iniciar sesión.
   - **Sin conexión**: solo para jugar en servidores que no comprueban la cuenta.
4. **Crea tu primera instancia** desde **Instancias → Nueva instancia**.
5. Pulsa **Jugar** en la instancia.

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
| **Botón de cuenta** (abajo) | Cambiar de cuenta, añadir una nueva, quitarla o cambiar su skin. |

### Pantalla de una instancia

Al abrir una instancia aparecen su nombre, su versión, su cargador (Vanilla, Fabric, Forge…) y los botones **Jugar**, **Abrir carpeta** y **Más opciones** (⋯).

Debajo hay pestañas:

- **Mods**: el **pack de rendimiento** (arriba del todo) y buscar, activar, desactivar o quitar mods. Si hay una versión nueva de un mod, aparece un punto en la pestaña y un icono para actualizarlo.
- **Packs y shaders**: instalar packs de recursos y shaders desde Modrinth.
- **Mundos**: entrar directamente, crear copias de seguridad y restaurarlas.
- **Capturas**: galería de capturas de pantalla de la instancia. Puedes copiarlas, abrirlas o borrarlas.
- **Ajustes**: nombre, versión, memoria, Java, ajustes gráficos del juego y otras opciones de esta instancia.

---

## 3. Tareas habituales

### Crear una instancia

**Instancias → Nueva instancia**. Eliges versión de Minecraft y cargador. Para partir de otra cosa, usa las pestañas de arriba de esa misma ventana: **Modpack de Modrinth**, **Archivo .mrpack** o **Launcher oficial**. También están en la flecha que hay junto al botón **Nueva instancia**.

### Instalar mods

1. Abre la instancia y ve a la pestaña **Mods**.
2. Usa el buscador para encontrar mods compatibles con la versión de la instancia.
3. Activa o desactiva un mod con su interruptor, o quítalo con el icono de papelera.

### Activar el pack de rendimiento

En la pestaña **Mods** de la instancia, activa **Pack de rendimiento** (la tarjeta de arriba). Nebula instala mods de optimización compatibles con esa versión. Necesita un cargador de mods (Fabric, Quilt, Forge o NeoForge). También se puede marcar al crear la instancia.

### Entrar a un servidor

En **Inicio** aparecen tus servidores favoritos con su estado en vivo (jugadores conectados y ping). Pulsa el botón ▶ de uno para entrar. Para elegir con qué instancia se entra en cada servidor: su menú (⋯) → **Editar** → **Entrar con**.

Para que el juego entre directamente en un servidor al abrirlo, activa **Conectar al iniciar** en los ajustes de la instancia.

### Copias de seguridad de mundos

Nebula hace copias automáticas de tus mundos al cerrar el juego. Para hacer una a mano o restaurar una, ve a la pestaña **Mundos** de la instancia.

### Duplicar una instancia

Desde **Más opciones** (⋯) de la instancia, puedes duplicarla con o sin sus mundos.

### Cambiar la skin

Pulsa el botón de cuenta (abajo a la izquierda) y, en la cuenta de Microsoft, el icono de la camiseta. En el editor puedes subir un PNG, copiar la skin de otro jugador escribiendo su nombre, elegir la capa y volver a la skin por defecto. Las skins que usas o pruebas se guardan en **Tus skins** para volver a ponerlas con un clic. Las cuentas sin conexión no tienen skin.

### Amigos

En **Inicio**, la sección **Amigos** muestra tu lista de amigos de Minecraft (necesita una cuenta de Microsoft): quién está conectado, solicitudes y añadir amigos por su nombre de Java. Si tienes varias cuentas de Microsoft, se cambia de cuenta desde la propia lista. En el menú (⋯) de la sección puedes aparecer desconectado o dejar de recibir avisos cuando alguien se conecta; en el de cada amigo, probar su skin.

### Importar del launcher oficial

Si ya tienes perfiles en el launcher oficial de Minecraft, Nebula puede convertirlos en instancias. Tus archivos originales no se modifican.

---

## 4. Ajustes

**Ajustes** agrupa las opciones generales. Las principales:

- **Memoria y rendimiento**: memoria para el juego (automática o manual), tarjeta gráfica que usa Minecraft y prioridad del proceso (estas dos últimas, solo en Windows).
- **Al jugar**: qué hace el launcher cuando abres el juego (por ejemplo, ocultarse).
- **Segundo plano**: seguir junto al reloj al cerrar la ventana, y **Abrir con Windows** (en Linux, **Abrir al iniciar sesión**) para que Nebula arranque al encender el PC.
- **Discord**: muestra en tu perfil que estás en el launcher o jugando. Se puede desactivar.
- **Copias de seguridad**: copias automáticas de los mundos y cuántas se guardan.
- **Idioma y apariencia**: idioma, color y tamaño de la interfaz.
- **Cuenta de Microsoft (avanzado)**: solo para quien tenga su propia aplicación de Azure. Las cuentas se gestionan con el botón de cuenta de abajo a la izquierda.
- **Actualizaciones**: Nebula se actualiza solo. Aquí ves las novedades de cada versión y puedes buscar actualizaciones a mano.

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
| `Ctrl+,` | Ir a Ajustes |
| `F1` | Ver todos los atajos |
| `Esc` | Cerrar ventanas y buscadores |

---

## 6. Segundo plano y bandeja

- Al **cerrar la ventana**, Nebula se queda junto al reloj (la bandeja del sistema). Para cerrarlo del todo: clic derecho en su icono → **Salir**. Puedes cambiar este comportamiento en **Ajustes → Segundo plano**.
- En Linux con GNOME, el icono de la bandeja solo aparece con la extensión AppIndicator. Sin ella, vuelve a abrir Nebula desde el menú de aplicaciones y aparece la ventana.
- Mientras juegas, Nebula cierra su interfaz para dejar más memoria a Minecraft y vuelve a abrirse al instante cuando lo necesites.
- Desde la bandeja también puedes abrir una instancia directamente y, cuando hay una actualización lista, reiniciar para instalarla.

---

## 7. Problemas frecuentes

- **El juego no arranca**: abre **Registro** para ver el error. En la instancia, **Más opciones → Reparar archivos** vuelve a descargar los archivos dañados o que faltan.
- **Un mod no funciona**: revisa que sea compatible con la versión y el cargador de la instancia. Desactívalo con su interruptor para comprobar si era el causante.
- **No aparece Discord**: abre Discord en tu PC. Nebula intenta conectar cada 30 segundos.
- **No hay conexión a internet**: puedes jugar con lo que ya tienes instalado.
- **Linux te pide la contraseña al actualizar**: pasa con el `.deb`, porque instala en el sistema. El `.AppImage` se actualiza sin pedir nada.

---

## Aviso

Nebula Launcher no es un producto oficial de Minecraft. No está aprobado ni asociado con Mojang ni con Microsoft. Minecraft es una marca de Mojang AB.
