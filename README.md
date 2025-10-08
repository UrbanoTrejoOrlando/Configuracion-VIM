# Configuracion-VIM

Este repositorio contiene archivos de configuración personal para **Vim / Neovim**, incluyendo ajustes, plugins, mapeos y personalización del entorno de edición.


---

## Qué incluye

- Ajustes de comportamiento (tabulaciones, sangrías, número de líneas, resaltado)  
- Mapeos personalizados (atajos para facilitar tu flujo de trabajo)  
- Configuración de plugins (por ejemplo, gestores de plugins, autocompletado, linting)  
- Temas de color personalizados  
- Funciones o scripts Vim adicionales en `autoload/`  

---

## Cómo usar esta configuración

1. Clona este repositorio:

   ```bash
   git clone https://github.com/UrbanoTrejoOrlando/Configuracion-VIM.git

2. Copia (o enlace simbólico) los archivos de configuración a tu directorio home:
   ```bash
    cp vimrc ~/.vimrc

3. Instala los plugins configurados (dependiendo del gestor que uses, por ejemplo, Vim-Plug, Pathogen, etc.):
    - Abre Vim y ejecuta el comando correspondiente (por ejemplo, :PlugInstall).
  
## Personalización

Puedes ajustar esta configuración a tu gusto:
  - Cambia el tema de color en **colors/**
  - Añade nuevos mapeos en vimrc o archivos .vim
  - Agrega o elimina plugins editando tu gestor de plugins
  - Crea funciones personalizadas en **autoload/**
