# 🐧 Comandos Kubuntu y KDE Plasma

Chuleta web, sencilla y minimalista, con los comandos más útiles de **Kubuntu** y **KDE Plasma** organizados por categoría. Cada comando tiene su descripción y un botón para copiarlo directamente.

🌐 **Demo:** https://TU-USUARIO.github.io/kubuntu-comandos/

## ✨ Características

- Buscador en vivo (apt, plasmashell, wifi, RAM…)
- Filtros por categoría, cada una con su color de borde
- Botón **Copiar** en cada comando
- Selector **Plasma 6 / Plasma 5** que ajusta los comandos (`kquitapp6`, `kwriteconfig6`…)
- Tema claro y oscuro
- Diseño responsive, funciona bien en móvil
- Un solo archivo HTML, sin dependencias ni conexión a internet

## 📚 Categorías

| Categoría | Qué incluye |
|---|---|
| Paquetes | APT, Snap y Flatpak |
| Archivos y navegación | Búsqueda, copias, compresión y permisos |
| Rendimiento y monitoreo | RAM, disco, temperaturas, arranque y logs |
| Plasma Shell | Reiniciar panel y KWin, ajustes con `kwriteconfig`, temas y capturas |
| Errores típicos y soluciones | Bloqueos de dpkg, paquetes rotos, audio, Wi-Fi, GRUB y drivers |
| Sistema, usuarios y servicios | systemd, usuarios, hardware y sesión X11/Wayland |
| Red | NetworkManager, puertos, firewall y SSH |
| Terminal pro | zoxide, fzf, timeshift, tmux y KDE Connect |

## 🚀 Uso

Abre `index.html` en tu navegador. No necesitas instalar nada.

Para publicarlo con GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.

## ✏️ Añadir tus propios comandos

Abre `index.html` y busca la lista `D` dentro del `<script>`. Cada comando es un par `["comando", "descripción"]` dentro de su categoría:

```js
["sudo apt install btop", "Monitor moderno de recursos"],
```

Usa `$V` dentro de un comando para que se cambie automáticamente entre `5` y `6` según el selector de Plasma.

## ⚠️ Aviso

Revisa siempre un comando antes de ejecutarlo, sobre todo los que usan `sudo` o `rm`. Algunos comandos de la categoría de errores modifican configuración del sistema.

## 📄 Licencia

Libre para usar, modificar y compartir.
