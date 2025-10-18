# AstralMeter ⚡

<p align="right">
  <a href="README.md">English</a> · <a href="README.pt-BR.md">Português</a> · <strong>Español</strong>
</p>

<div align="center">

[![GitHub](https://img.shields.io/github/downloads/Spyu-dev/AstralMeter/total?style=for-the-badge&color=%23280137)](https://github.com/spyu-dev/AstralMeter/releases/latest)

![Version](https://img.shields.io/badge/version-1.0.1-purple)
![License](https://img.shields.io/badge/license-AGPL--3.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-brightgreen)

[!["Ko-fi"](https://storage.ko-fi.com/cdn/kofi4.png?v=6)](https://ko-fi.com/spyudev)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png)](https://www.buymeacoffee.com/spyu)

**Overlay profesional de DPS/HPS para Star Resonance**

Monitorea tus estadísticas de combate en tiempo real con una interfaz moderna y personalizable.

[📥 Instalación](#-instalación) • [✨ Funciones](#-funciones) • [⚙️ Configuración](#-configuración) • [🎮 Cómo Usar](#-cómo-usar)

</div>

---

## 📋 Requisitos Previos

> ⚠️ IMPORTANTE: Instala Npcap antes de iniciar AstralMeter.

### Instalación de Npcap

AstralMeter depende de Npcap para capturar los paquetes de red del juego.

- Descarga oficial: https://npcap.com/#download
- Ejecuta el instalador como Administrador
- Marca "Install Npcap in WinPcap API-compatible Mode"
- Completa la instalación y reinicia Windows

---

## 🚀 Instalación

<p align="center">
<a href="https://github.com/Spyu-dev/AstralMeter/releases/tag/1.0.1"><strong>[HAZ CLIC AQUÍ PARA DESCARGAR EL MEDIDOR]</strong></a>
</p>

1. Confirma que Npcap está instalado (ver arriba)
2. Descarga la última versión de AstralMeter usando el botón en las Notas de Lanzamiento
3. Extrae el `.zip` en la carpeta de tu preferencia
4. Ejecuta `AstralMeter.exe`

---

## ✨ Funciones

### 🎯 Monitoreo en Tiempo Real
- DPS (Damage Per Second)
- HPS (Healing Per Second)
- Estadísticas totales y ranking de jugadores
- Alta tasa de actualización (aprox. cada 100 ms)

### 🎨 Interfaz Moderna
- Tema glassmorphism con identidad morada
- Transparencia ajustable (opacidad)
- Diseño compacto con desplazamiento suave

### 🎨 Temas y Colores
- Selector de temas disponible directamente en Configuración
- Temas disponibles: Purple, Blue, Red, Orange, Cyan, Gray y Rainbow
- El tema Rainbow asigna colores por subclase automáticamente

### 🎭 Iconos de Clase
- Iconos dedicados para cada especialización (subclase)
- Identificación visual inmediata alineada al tema activo

### ⚡ Modos de Vista
- Modo Daño (DPS)
- Modo Curación (HPS)
- Cambio rápido mediante atajo o conmutador en pantalla

### 🧩 Modo Compacto
- Reduce la altura de las barras, márgenes y grosor de la barra de desplazamiento
- Atajo rápido: `Ctrl + M` (también disponible en Configuración)
- Perfecto para raids con muchos jugadores visibles

### 🌐 Idiomas
- Idiomas soportados: Portugués (pt), Inglés (en) y Español (es)
- Cambia instantáneamente desde Configuración

### 🎛️ Configuración
- Control de opacidad de la ventana
- Mostrar porcentaje de contribución
- Limpiar al cambiar de servidor
- Atajos de teclado personalizables

### ⌨️ Atajos Predeterminados
- `Ctrl + ←` — Modo Daño (DPS)
- `Ctrl + →` — Modo Curación (HPS)
- `Ctrl + End` — Limpiar estadísticas
- `Alt` — Interactuar (activar/desactivar click-through)
- `Ctrl + ↑` — Desplazar hacia arriba
- `Ctrl + ↓` — Desplazar hacia abajo

Todos los atajos pueden personalizarse en la pantalla de Configuración.

---

## ⚙️ Configuración

Abre Configuración mediante el ícono de engranaje (⚙️) en la esquina superior derecha.

### Apariencia
- Opacidad de la ventana del 30% al 100%
- Temas: Purple, Blue, Red, Orange, Cyan, Gray, Rainbow
- Activar o desactivar el Modo Compacto

### Comportamiento
- Limpiar al cambiar de servidor
- Mostrar porcentaje de contribución

### Idioma
- Elige entre pt, en, es (aplicación inmediata)

### Atajos de Teclado
- Define combinaciones personalizadas para cada acción (DPS, HPS, limpiar, click-through, desplazamiento)

Cómo reasignar un atajo:
1. Haz clic en el campo del atajo
2. Presiona la combinación deseada (ej.: `Ctrl + K`)
3. Haz clic en Guardar

---

## 🎮 Cómo Usar

### Primera Vez
1. Inicia AstralMeter
2. Posiciona la ventana (el click-through está desactivado al inicio)
3. La posición se guarda automáticamente
4. Entra en combate en el juego para llenar el medidor

### Uso Diario
1. Abre AstralMeter (se abre en la posición guardada)
2. Usa `Alt` para alternar el click-through cuando necesites interactuar
3. Aprovecha los atajos para cambiar modos y navegar por la lista

---

## 🔧 Tecnología
- Electron (aplicación de escritorio)
- Node.js
- Npcap (captura de paquetes)
- Protocol Buffers (decodificación)
- Zstd (descompresión)

---

## 📝 Licencia

AGPL-3.0 — consulta el archivo LICENSE para más detalles.

---

## 🆘 Soporte
- Abre un Issue para reportar errores o solicitar mejoras
- Comentarios y preguntas siempre son bienvenidos

---

## 🙌 Colaboradores

Gracias a quienes contribuyen a este proyecto:

- [Spyu](https://github.com/Spyu-dev)
- [Doufa](https://github.com/DoufaDev)
