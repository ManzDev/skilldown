# skilldown

Script para descargar skills específicos para opencode desde GitHub.

## Instalación

```bash
wget https://raw.githubusercontent.com/ManzDev/skilldown/main/skilldown
sudo mv skilldown /usr/local/bin
sudo chmod +x /usr/local/bin/skilldown
```

## Uso

```bash
# Descarga los skills en el proyecto actual
skilldown https://github.com/kajisho5/ffmpeg-skill

# Descarga skills especificos
skilldown https://github.com/addyosmani/agent-skills/tree/main/skills/performance-optimization

# Descarga los skills para todo el sistema
skilldown --global https://github.com/kajisho5/ffmpeg-skill

# Descarga los skills mostrando los ficheros que va descargando
skilldown --verbose https://github.com/kajisho5/ffmpeg-skill
```
