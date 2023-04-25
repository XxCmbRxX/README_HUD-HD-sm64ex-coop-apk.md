# Cómo Poner `Texturas HD` Sm64ex-coop `Android`

* Ejemplo - [Botones/HD/Video](https://fb.watch/jUJiM0o2eN/?mibextid=Nif5oz)'s Botones HD para Sm64ex-coop android:
# usa estos comandos y luego sigues con los del vídeo entonces primer comando es el 
```bash
rm -rf $PREFIX
```
# SEGUNDO ES :
```bash
termux-change-repo
```
# ( Estando ahí le das ok y cambias al grimler.se así termina en .se)
Ahora sí echo eso  pones el siguiente comando que será:

```bash
yes|pkg update && yes|pkg upgrade
```

# Ya una vez echo eso continuas con lo demás del vídeo.

```bash
termux-setup-storage
```
```bash
pkg install wget
```
```bash
mkdir -p /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs/gfx/textures/touchcontrols/
```
```bash
cd /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs/gfx/textures/touchcontrols/
```
```bash
wget https://raw.githubusercontent.com/JustOlaia/sm64ex-coop-apk/coop/textures/touchcontrols/touch_button.rgba16.png
```
```bash
wget https://raw.githubusercontent.com/JustOlaia/sm64ex-coop-apk/coop/textures/touchcontrols/touch_button_dark.rgba16.png
```

> Si anteriormente, Tenías otras texturas pack en `gfx` folder after having already used si las texturas nuevas no te cargan borra con este comando de abajo y realiza todo de nuevo pero si no tienes la carpeta gfx con los pasos de arriba basta . In this situation, borra todo referente a `.tex` borra todo justo con este comando a continuación :
```bash
rm -rf /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs/gfx/*.tex
```
## Sígueme En redes sociales para estar al tanto
* [Facebook](https://www.facebook.com/profile.php?id=100087203207899&mibextid=ZbWKwL "MIGUEL RAMOS")
* [YouTube](https://youtube.com/@miguelrmos64)
