# Sonalia

Sonalia es un reproductor de musica homebrew para Nintendo Wii. Permite
escuchar archivos FLAC, MP3 y WAV almacenados en tarjeta SD o USB, con una
interfaz organizada por albumes que muestra caratulas y metadatos de cada
pista. Incluye busqueda, listas de reproduccion, dos modos de visualizacion,
temas de color y soporte para cuatro idiomas.

- Autor: surreal snake
- Plataforma: Nintendo Wii (Homebrew Channel)
- Codigo cerrado. Solo se distribuyen binarios.

---

## Especificaciones

- Formatos: FLAC, MP3, WAV
- Fuentes: SD (sd:/music) y USB (usb:/music)
- Lectura de metadatos: artista y duracion
- Caratulas embebidas
- Listas de reproduccion (.m3u)
- Busqueda con teclado en pantalla
- 2 interfaces: lista clasica y carrusel de caratulas
- 6 temas de color
- 4 idiomas: espanol, ingles, frances, ruso
- Fondos animados y visualizador de audio opcionales

---

## Instalacion

1. Descarga la ultima version desde la seccion Releases.
2. Copia la carpeta apps/sonalia a la raiz de la SD.
3. Crea una carpeta music en la raiz y coloca dentro tu musica.

```
SD:/
  apps/
    sonalia/
      boot.dol
      icon.png
      meta.xml
  music/
    (archivos .flac / .mp3 / .wav)
```

---

## Controles

Funciona con Wiimote en horizontal, Nunchuk, Classic Controller y mando de
GameCube.

    A                         Seleccionar / reproducir pista
    B                         Pausar / volver atras en los menus
    Cruceta arriba/abajo      Navegar por la lista de pistas
    Cruceta izquierda/derecha Retroceder / avanzar en la pista actual
                              (en el carrusel: cambiar de pista)
    +                         Subir volumen
    -                         Bajar volumen
    1 o boton MENU            Menu de acciones y ajustes
    2                         Aleatorio
    HOME / START              Salir al Homebrew Channel

El Wiimote tambien funciona como puntero para tocar la interfaz directamente.

---

## Notas

- La Wii no puede reproducir CD de audio. Su lectora es de tipo DVD y no
  admite CD-DA en ningun modelo. Para escuchar un CD, pasalo a FLAC o MP3
  en un ordenador y copialo a la carpeta music.
- El primer arranque con muchos archivos MP3 puede tardar unos segundos
  mientras se calculan las duraciones. Es un proceso unico con barra de
  progreso.

---

## Licencia

Todos los derechos reservados (c) surreal snake. No se permite descompilar,
modificar ni redistribuir la aplicacion sin autorizacion del autor.

## Creditos

Autor: surreal snake
Saludos a: offizzer gaming, antonius 1204, Mario mark, PEcarlos
