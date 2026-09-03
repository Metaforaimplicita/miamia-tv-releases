# MiaMia TV — descargas

Este repositorio contiene **únicamente los archivos de instalación** publicados de MiaMia TV.
Las descargas están en la pestaña [Releases](../../releases).

Sitio oficial: **[metaforiclabs.cl](https://www.metaforiclabs.cl)**

---

## Qué es MiaMia TV

Un reproductor multimedia para Android TV, Google TV, teléfonos, tabletas y Windows. Toma tu
lista M3U o tu cuenta Xtream Codes y la organiza: canales en vivo por categoría, películas y
series con sus fichas, favoritos, y un historial que recuerda dónde quedaste.

> **MiaMia TV es un reproductor multimedia: no vende, aloja ni provee ningún contenido.**
> Necesitas tu propia lista de reproducción.

---

## Cómo instalar

### Android · Android TV · Google TV

1. Descarga el archivo `.apk` del release más reciente.
2. Si es la primera vez, tu dispositivo pedirá permiso para instalar aplicaciones desde esta
   fuente. Es un aviso normal de Android para todo lo que no viene de una tienda.
3. Abre el archivo descargado.

La aplicación va firmada con la clave de Metaforic Labs SpA. Android rechaza actualizar una
instalación existente con un archivo firmado por otra clave, así que una copia alterada no puede
reemplazar la tuya.

### Windows 10 y 11 (64 bits)

1. Descarga el archivo `.zip` del release más reciente.
2. Descomprímelo en la carpeta que prefieras.
3. Ejecuta `miamia_tv.exe`.

No requiere instalación. Windows mostrará una advertencia de SmartScreen la primera vez, porque
el ejecutable todavía no lleva firma de código; puedes continuar desde «Más información →
Ejecutar de todas formas». Si prefieres evitar ese aviso, la versión de la Microsoft Store no lo
muestra.

---

## Comprobar que el archivo es el correcto

Cada release incluye un archivo `SHA256SUMS.txt` con la huella de cada descarga. Si quieres
confirmar que lo que bajaste es exactamente lo que se publicó:

**Windows (PowerShell)**

```
Get-FileHash .\MiaMiaTV-1.0.0-android.apk -Algorithm SHA256
```

**Linux o macOS**

```
sha256sum MiaMiaTV-1.0.0-android.apk
```

El resultado tiene que coincidir, carácter por carácter, con la línea correspondiente de
`SHA256SUMS.txt`. Si no coincide, no lo instales y escríbenos.

---

## Requisitos

| | |
|---|---|
| Android | 7.0 o posterior · arm64-v8a, armeabi-v7a, x86_64 |
| Windows | 10 versión 1809 (compilación 17763) o posterior · 64 bits |
| Conexión | Obligatoria. El contenido se transmite desde el servidor de tu proveedor de lista |
| Espacio | Alrededor de 250 MB en Android, 300 MB en Windows |

---

## Soporte

**soporte@metaforiclabs.cl**

---

## Sobre este repositorio

Aquí solo se publican los archivos de instalación. **El código fuente de MiaMia TV no es
público** y no se distribuye.

MiaMia TV es software propietario de Metaforic Labs SpA (RUT 78.491.499-2), protegido por la Ley
N° 17.336 sobre Propiedad Intelectual. Descargar la aplicación otorga una licencia de uso en los
términos publicados en el sitio; no otorga derechos sobre el software.

© 2026 Metaforic Labs SpA. Todos los derechos reservados.
