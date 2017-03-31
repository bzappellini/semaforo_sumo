# Software para torneo de robótica

## Requisitos

- Python
- Kivy 1.9
- Adb (Android Debug Bridge)
  * https://dl.google.com/android/repository/platform-tools-latest-windows.zip
  * https://dl.google.com/android/repository/platform-tools-latest-linux.zip
  * https://dl.google.com/android/repository/platform-tools-latest-darwin.zip
- GNU Make
  * Viene incluido en Linux y Mac
  * https://sourceforge.net/projects/gnuwin32/files/make/3.81/make-3.81-bin.zip/download?use_mirror=ufpr&download=



## Ejecución local

```
make run
```


## Utilizando la aplicación Kivy Launcher

Kivy Launcher permite ejecutar proyectos Kivy sin necesidad de generar el APK.
Se descarga desde: https://play.google.com/store/apps/details?id=org.kivy.pygame&hl=es

### Copiando/Acutalizando el proyecto al dispositivo

```
make push
```

Una vez completado abrir Kivy Launcher y ejecutar la aplicación:

![SUMO](./doc/launcher.jpg)


## Otros comandos

```
make shell
```

Abre una consola en le teléfono