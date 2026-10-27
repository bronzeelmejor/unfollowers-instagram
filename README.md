<div align="center">

# ◈ ORPHIX NETWORK

### SOCIAL AUDIT · INSTAGRAM

**Tu comunidad. Sin ruido.**

Revisa quién no te sigue de vuelta, organiza tus conexiones y protege las cuentas que quieres conservar desde tu sesión de Instagram.

[![Abrir Instagram](https://img.shields.io/badge/ABRIR_INSTAGRAM-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/)
[![Empezar](https://img.shields.io/badge/EMPEZAR-A995FF?style=for-the-badge&logo=readme&logoColor=111222)](#-cómo-empezar)
[![Funciones](https://img.shields.io/badge/VER_FUNCIONES-58D5DB?style=for-the-badge&logoColor=111222)](#-funciones)
[![Privacidad](https://img.shields.io/badge/PRIVACIDAD-20283D?style=for-the-badge)](#-privacidad-y-datos)

**Español / English · Interfaz adaptable · Exportación JSON y CSV**

</div>

---

## ✦ Qué es Orphix Social Audit

Orphix Social Audit es una adaptación de InstagramUnfollowers con la identidad visual de **Orphix Network**. Su interfaz combina un fondo oscuro, acentos violeta y cian, un nuevo símbolo y paneles pensados para revisar tus conexiones con claridad.

La herramienta se ejecuta dentro de Instagram web, aprovechando la cuenta con la que ya has iniciado sesión. Permite analizar las relaciones de seguimiento, buscar perfiles y revisar los resultados antes de decidir cualquier acción.

> Detectar quién no te sigue de vuelta no demuestra quién te ha dejado de seguir recientemente. Para conocer cambios históricos haría falta comparar datos de distintas fechas.

## ⚡ Funciones

| Función | Qué permite hacer |
| --- | --- |
| Análisis de conexiones | Identificar las cuentas que sigues y que no te siguen de vuelta. |
| Resultados progresivos | Consultar los perfiles a medida que avanza el análisis. Espera a que termine para valorar el resultado completo. |
| Búsqueda y filtros | Localizar usuarios y ajustar los perfiles visibles. |
| Lista blanca | Proteger cuentas que deseas conservar y gestionar su importación o exportación. |
| Selección manual | Elegir los perfiles sobre los que quieres actuar. |
| Dejar de seguir | Ejecutar la acción sobre las cuentas que hayas seleccionado. |
| Exportación | Copiar la lista o descargar resultados en JSON y CSV. |
| Último análisis | Volver a abrir los resultados guardados localmente, cuando estén disponibles. |
| Ajustes | Configurar los tiempos de espera y cambiar entre español e inglés. |
| Diseño Orphix | Portada, tarjetas, controles y ajustes con una identidad visual renovada. |

## 🚀 Cómo empezar

### 1. Descarga los archivos

En la página del repositorio, pulsa **Code → Download ZIP** y extrae el contenido en tu ordenador.

Localiza **ABRIR_ORPHIX.html** en la carpeta del paquete. Si el repositorio contiene el archivo `Orphix_Network_Instagram.zip`, extráelo primero.

### 2. Copia el código

Abre **ABRIR_ORPHIX.html** con Chrome o Edge y pulsa **Copiar código**.

Para utilizar el paquete preparado no necesitas instalar Node.js ni ejecutar comandos.

### 3. Abre tu cuenta

Entra en [Instagram web](https://www.instagram.com/) e inicia sesión en la cuenta que quieres analizar.

### 4. Ejecuta la herramienta

1. Dentro de Instagram, pulsa **Ctrl + Mayús + J** en Windows para abrir la consola del navegador.
2. Revisa el código antes de ejecutarlo. La consola permite realizar acciones con tu sesión.
3. Pega el código y pulsa **Enter**. Si el navegador bloquea el pegado, lee su aviso de seguridad.
4. Cuando aparezca Orphix Network, pulsa **Analizar mi cuenta**.
5. Espera a que termine y revisa los resultados.

**Para cerrar la herramienta, recarga Instagram.** Para cargar una versión nueva, recarga antes de pegar el nuevo código.

## 🎛️ Guía de controles

| Control | Acción |
| --- | --- |
| Analizar mi cuenta | Inicia un nuevo análisis. |
| Abrir último análisis | Recupera los resultados guardados, si existen. |
| Buscar usuarios | Filtra los perfiles por su nombre de usuario. |
| Copiar lista | Copia la lista de resultados mostrada. |
| JSON / CSV | Descarga los resultados en el formato elegido. |
| ES / EN | Cambia el idioma de la interfaz. |
| Engranaje de ajustes | Abre la configuración y la gestión de la lista blanca. |
| Casillas de selección | Selecciona las cuentas sobre las que quieres actuar. |
| Foto de perfil | Permite añadir o retirar una cuenta de la lista blanca. |
| Logotipo Orphix | Permite volver desde la vista actual; durante un proceso, revisa su estado antes de salir. |

Algunos controles permanecen desactivados hasta que haya resultados o termine el análisis. Revisa siempre las cuentas seleccionadas antes de dejar de seguirlas.

## 🔒 Privacidad y datos

- El paquete no te solicita introducir tu contraseña: utiliza la sesión abierta en Instagram.
- Los resultados guardados, la lista blanca y los ajustes se almacenan en el navegador mediante `localStorage`.
- Las consultas y las acciones de seguimiento se envían a Instagram.
- La interfaz puede cargar fotos de perfil y avatares desde servicios externos, incluido DiceBear.
- Esta adaptación no incorpora un servidor propio que reciba tus listas ni un sistema de analítica añadido por Orphix.
- Borrar los datos del sitio puede eliminar los análisis y ajustes guardados. Exporta tu lista blanca si quieres conservar una copia.

## 🛠️ Solución de problemas

**La interfaz no aparece:** comprueba que ejecutas el código dentro de `www.instagram.com`, con la sesión iniciada. Recarga y vuelve a intentarlo con el código completo.

**El análisis se interrumpe:** no interpretes un resultado parcial como definitivo. Revisa el mensaje de error y espera antes de volver a intentarlo.

**Instagram muestra una restricción:** detén las acciones y respeta las indicaciones de Instagram. Los intervalos configurables no garantizan evitar bloqueos.

**Aparece el diseño anterior:** recarga Instagram y copia el código del paquete nuevo.

**El archivo HTML se ve como código en GitHub:** descarga los archivos y abre `ABRIR_ORPHIX.html` en tu ordenador. La vista de archivos de GitHub no ejecuta la herramienta.

## 💻 Desarrollo

Los fuentes se encuentran en `codigo_fuente` dentro del paquete preparado.

Abre PowerShell en esa carpeta y ejecuta:

```powershell
npm.cmd ci
npm.cmd run build
```

El código compilado se genera en **dist/dist.js**. Las dependencias solo son necesarias para modificar o recompilar el proyecto.

## 📌 Estado y compatibilidad

La versión Orphix compila correctamente. La revisión visual completa en navegador y la prueba con una cuenta real siguen pendientes.

La herramienta depende de interfaces internas de Instagram que pueden cambiar. No se garantiza compatibilidad permanente, ausencia de restricciones ni resultados completos si el análisis falla.

## 🤝 Créditos y licencia

Basado en [InstagramUnfollowers](https://github.com/davidarroyo1234/InstagramUnfollowers), de **davidarroyo1234**, distribuido bajo licencia MIT.

Identidad visual y personalización de esta adaptación: **Orphix Network**. Se conserva la licencia y la atribución del proyecto original; consulta el archivo `LICENSE` incluido en el paquete.

Este proyecto no está afiliado, autorizado ni respaldado por Instagram o Meta.

---

<div align="center">

**ORPHIX NETWORK · SOCIAL AUDIT**

Tú revisas. Tú seleccionas. Tú decides.

[Volver arriba ↑](#-orphix-network) · [Abrir Instagram ↗](https://www.instagram.com/) · [Proyecto original ↗](https://github.com/davidarroyo1234/InstagramUnfollowers)

</div>
