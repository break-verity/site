# break verity

a fan-made horror puzzle game. your friend horizon installed an ai helper called verity, and now verity won't let anyone near him. remote into horizon's pc, dig through his files, and get verity uninstalled.

six days. each one needs a real skill: image metadata, plus either lua deobfuscation or ciphers (you pick at the start).

**fan-made.** verity is from thatmob's minecraft arg. this project isn't affiliated with thatmob.

## privacy

verity only knows what your browser already tells every website.

- your browser, os, screen size, time zone and battery level stay on your device. the server never sees them.
- your ip and rough city are read by the server and sent straight back to the page. not logged, not stored.
- chat messages go to an ai provider so verity can reply. your ip never does. don't type personal info.

check it yourself: open devtools, go to the network tab, and watch every request.

## credits

lua files obfuscated with prometheus.
Based on Prometheus by Elias Oelschner, https://github.com/prometheus-lua/Prometheus

## layout

```
public/
  index.html          the whole game ui
  assets/verity.glb   verity's 3d model (all faces)
  files/lua/          lua path puzzle files
  files/cipher/       cipher path puzzle files
```
