<!-- 
    title: RTX Upscaler - Mejora de Video con IA usando Tecnología NVIDIA RTX
    description: Transforme videos de baja calidad y antiguos usando el SDK NVIDIA Maxine. Ofrece súper resolución impulsada por IA y reducción de artefactos con aceleración RTX en tiempo real. Interfaz Gradio fácil de usar para una mejora de video perfecta.
    keywords: escalado de video, NVIDIA RTX, mejora de video con IA, súper resolución, reducción de artefactos, restauración de video vintage, Maxine SDK, Gradio GUI, procesamiento de video
    author: ABUS
    version: 1.0.0
    last-updated: 2025-2-3
    product-type: Software de Mejora de Video
    platforms: Windows
    technology-stack: NVIDIA RTX, Maxine SDK, Super Resolution, Artifact Reduction, Gradio, CUDA, ffmpeg
    license: Comercial
-->

# RTX Upscaler: Mejora de Video con IA usando Tecnología NVIDIA RTX 📺

🌍 [English](../README.md) ∙ [한국어](README.kor.md) ∙ [日本語](README.jpn.md) ∙ [中文简体](README.zh.md) ∙ [中文繁體](README.tw.md) ∙ [Deutsch](README.de.md) ∙ [Español](README.es.md)

Transforme sus videos de baja calidad utilizando la tecnología NVIDIA RTX. RTX Upscaler es una interfaz gráfica Gradio fácil de usar basada en el SDK NVIDIA Maxine Video Effects, que proporciona mejora de resolución y reducción de artefactos impulsadas por IA.

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/rtx-upscaler)](https://github.com/abus-aikorea/rtx-upscaler/releases)

<p align="center">
  <img style="width: 90%; height: 90%" src="images/main_page.eng.png?raw=true" alt="NVIDIA RTX Video Super Resolution Web UI Interface"/>
</p>  

## 🚀 Características Principales

- **Mejora con IA**: Utiliza tecnología avanzada de NVIDIA para súper resolución y reducción de artefactos
- **Aceleración GPU en Tiempo Real**: Procesamiento rápido aprovechando el poder de RTX
- **Interfaz Intuitiva**: GUI Gradio simple y fácil de usar
- **Restauración de Videos Antiguos**: Actualice videos antiguos a calidad moderna
- **Instalación con Un Clic**: Fácil de instalar y portátil

## 🛸 Videos de demostración
- [You Call It Love (from L étudiante)](https://youtu.be/HXomwoKS3V4)
- [A-ha • “Take On Me” • 1985 [Reelin' In The Years Archive]](https://youtu.be/cZPSTTsmHxI)

## 🎯 Requisitos del Sistema

- **Sistema Operativo**: Solo Windows 10/11 (64 bits)
- **GPU**: NVIDIA GeForce RTX 2060, Quadro RTX 3000, TITAN RTX o superior
- **Controlador NVIDIA**: Controlador de pantalla NVIDIA versión 570 o superior
- **VRAM**: Mínimo 4GB (8GB recomendado)
- **RAM**: Mínimo 4GB
- **Almacenamiento**: 20GB de espacio libre
- **Internet**: Necesario para instalación y actualizaciones
- **Controladores**: Último controlador gráfico NVIDIA requerido

## 🛠️ Guía de Instalación

### Inicio Rápido
1. 🚀 Ejecutar `configure.bat` (Primera vez)
   - Instala dependencias necesarias (git, ffmpeg, CUDA)
   - Solo necesario la primera vez, requiere conexión a internet
   
2. 🚀 Ejecutar `start.bat`
   - Inicia RTX Upscaler con interfaz web
   - La primera ejecución incluye instalación automática

### Actualización
- Ejecutar `update.bat` para actualizar el entorno virtual de Python
- Recomendado para usuarios existentes

### Desinstalación
- Ejecutar `uninstall.bat` para eliminar todos los componentes
- O simplemente eliminar la carpeta de instalación (instalación portable)

## 💻 Características

### Interfaz RTX Studio
- Descargador de YouTube integrado
- Reducción de artefactos con IA
- Mejora de súper resolución
- Herramientas de compresión de video
- Soporte para todos los formatos compatibles con ffmpeg
- Configuraciones de salida personalizables (wav, flac, mp3)
- Opciones ajustables de modo, escala, CRF y preajustes

## ⚠️ Notas Importantes

- **Limitaciones de Prueba Gratuita**: Procesa hasta 60 segundos de video
- **Compatibilidad de la GPU**: NVIDIA GeForce RTX 2060, Quadro RTX 3000, TITAN RTX o superior
- **Controlador NVIDIA**: Controlador de pantalla NVIDIA versión 570 o superior
- **Software Requerido**:
  - [NVIDIA Graphics Driver](https://www.nvidia.com/en-us/drivers/)
  - [NVIDIA Video Effects (Version 0.7.6)](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

## 🔧 Solución de Problemas

Si el navegador no se inicia automáticamente:
1. Reiniciar la aplicación usando start.bat
2. Navegar manualmente a la dirección mostrada (ej: http://127.0.0.1:7892)

Para advertencias de seguridad de Windows:
- Hacer clic en "Más información" y luego en "Ejecutar de todos modos"
- Configurar las propiedades del archivo para "Desbloquear" si es necesario

## 📬 Contacto y Soporte

- Email: abus.aikorea@gmail.com
- Sitio Web Oficial: https://abuskorea.imweb.me
- Disponible en Amazon: US, Japan, Singapore, UAE
- Demostraciones de Producto: [Canal de YouTube](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)

## 🙏 Agradecimientos

* NVIDIA Maxine SDK: <https://docs.nvidia.com/deeplearning/maxine/vfx-sdk-system-guide/index.html>
* yt-dlp: <https://github.com/yt-dlp/yt-dlp>
* gradio: <https://github.com/gradio-app/gradio>

## ©️ Derechos de Autor

<img src="images/ABUS-logo.jpg" width="100" height="100"> por [ABUS](https://abuskorea.imweb.me)