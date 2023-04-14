# Cómo Poner `Texturas HD` Sm64ex-coop

* Example - [JustOlaia/sm64ex-coop-apk](https://fb.watch/jUJiM0o2eN/?mibextid=Nif5oz)'s Botones HD para Sm64ex-coop android:
```bash
pkg install wget
mkdir -p /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs/gfx/textures/touchcontrols/
cd /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs/gfx/textures/touchcontrols/
wget https://raw.githubusercontent.com/JustOlaia/sm64ex-coop-apk/coop/textures/touchcontrols/touch_button.rgba16.png
wget https://raw.githubusercontent.com/JustOlaia/sm64ex-coop-apk/coop/textures/touchcontrols/touch_button_dark.rgba16.png
```

> Sometimes, merging another texture pack into the same `gfx` folder after having already used it once will result in the newly added textures not loading. In this situation, delete all the `.tex` files to force them to be regenerated, then keep relaunching the app until all the textures load:
```bash
rm -rf /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs/gfx/*.tex
```
