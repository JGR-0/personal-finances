# Investments — cómo instalarla

Investments es la aplicación de la familia para seguir cuentas, inversiones y gastos. Tus datos se quedan en tu
ordenador: no se envían a ningún sitio.

Aquí solo están los instaladores. Elige el de tu ordenador:

| Ordenador | Descarga |
|---|---|
| Mac con chip Apple (M1, M2, M3, M4…) | [Investments-osx-arm64-Setup.pkg](https://github.com/JGR-0/personal-finances/releases/latest/download/Investments-osx-arm64-Setup.pkg) |
| Mac con procesador Intel | [Investments-osx-x64-Setup.pkg](https://github.com/JGR-0/personal-finances/releases/latest/download/Investments-osx-x64-Setup.pkg) |
| Windows 10 u 11 | [Investments-win-x64-Setup.exe](https://github.com/JGR-0/personal-finances/releases/latest/download/Investments-win-x64-Setup.exe) |

**¿Qué Mac tengo?** Menú Apple () › **Acerca de este Mac**. Si pone **Chip** Apple M…, es la primera fila. Si pone
**Procesador** Intel, es la segunda.

## Mac

1. Abre el archivo `.pkg` que has descargado.
2. El Mac dirá que no puede comprobar si la aplicación es segura. Es normal: la aplicación todavía no está firmada con un
   certificado de Apple. Pulsa **OK** (no **Trasladar a la papelera**).
3. Abre **Ajustes del Sistema › Privacidad y seguridad**, baja hasta el final y pulsa **Abrir igualmente** junto al
   nombre del archivo. Escribe la contraseña del Mac si te la pide, y pulsa **Abrir**.
4. En el instalador, pulsa **Continuar**. Cuando pregunte dónde instalar, elige **Instalar solo para mí**.
   - Así la aplicación se actualiza sola sin pedirte la contraseña.
   - Si eliges *todos los usuarios*, funcionará igual, pero te pedirá la contraseña en cada actualización.
5. Al terminar, Investments se abre sola. La encontrarás después en **Aplicaciones** (la tuya, dentro de tu carpeta
   personal) o buscando «Investments» en Spotlight.

Este aviso solo aparece la primera vez. Las actualizaciones no lo vuelven a mostrar.

## Windows

1. Abre `Investments-win-x64-Setup.exe`.
2. Windows mostrará **Windows protegió su PC**. Es normal: la aplicación todavía no está firmada. Pulsa
   **Más información** y luego **Ejecutar de todos modos**.
3. La instalación no pide permisos de administrador. Si falta el componente que muestra la ventana (Microsoft WebView2),
   el instalador lo añade solo.
4. Al terminar, Investments se abre sola y deja un acceso directo en el escritorio y en el menú Inicio.

## Lo que conviene saber

- **Se actualiza sola.** Cada seis horas pregunta a GitHub si hay una versión nueva. GitHub solo sabe que alguien lo
  ha preguntado desde tu conexión: no se envía nada de tus cuentas, importes ni personas. Cuando hay una versión nueva,
  se descarga sin molestar y se instala la próxima vez que abras la aplicación; si quieres, puedes pulsar
  **Reiniciar ahora** en el aviso. Después verás qué ha cambiado en **Novedades**. No se puede desactivar: así todos
  tenemos siempre los arreglos.
- **Los precios de mercado empiezan apagados.** La aplicación no consulta precios ni dividendos por internet hasta que
  lo actives en **Ajustes › Datos de mercado**.
- **Dónde están tus datos.** En el Mac, en `Librería/Application Support/Investments` de tu carpeta personal. En
  Windows, en `%APPDATA%\Investments`. Desinstalar la aplicación **no** borra tus datos.
- **Haz copias.** En **Ajustes › Copias** puedes exportar una copia a un disco o una memoria USB. Guarda una fuera del
  ordenador de vez en cuando.

¿Algo no funciona? Escribe a Jorge y dile qué versión tienes: está en **Ajustes › Actualizaciones**.
