# 💵 Detector de Billetes Pro
## Sistema de Detección de Billetes Colombianos con IA

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)]()
[![ONNX Runtime](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)]()
[![YOLOv11](https://img.shields.io/badge/YOLOv11-00FFFF?style=flat&logo=yolo&logoColor=black)]()
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![PWA](https://img.shields.io/badge/PWA-Ready-blueviolet.svg)]()

---

## 🌐 Demo en Vivo
**🔗 Accede a la aplicación:** [https://miguel0827.github.io/DetectorBilletes/](https://miguel0827.github.io/DetectorBilletes/)

Experimenta con el detector de billetes directamente desde tu navegador. Detecta y cuenta billetes colombianos en tiempo real usando tu cámara o cargando imágenes.

---

## 📊 Descripción del Proyecto

**Detector de Billetes Pro** es una aplicación web progresiva (PWA) diseñada para la **detección automática y conteo inteligente de billetes colombianos** mediante modelos de visión por computadora basados en **YOLOv11**.

El sistema reconoce y cuantifica las siguientes denominaciones:
- 💵 **$50** | **$100** | **$200** | **$500**
- 💸 **$1,000** | **$2,000** | **$5,000** | **$10,000**
- 💰 **$20,000** | **$50,000** | **$100,000**

### 🎯 Objetivo

Ofrecer una herramienta web portátil y eficiente que permita:
- ✅ Detectar billetes colombianos en tiempo real mediante cámara
- ✅ Contar y calcular automáticamente el valor total
- ✅ Mantener un historial de conteos guardados
- ✅ Funcionar tanto en dispositivos móviles como en PC
- ✅ Operar de forma rápida con procesamiento local (sin servidor)
- ✅ Instalar como aplicación móvil (PWA)

---

## 🔧 Características Principales

- 📱 **PWA Instalable**: Funciona como app nativa en móviles y PC
- 🎥 **Detección en Tiempo Real**: Modo cámara con detección automática continua (PC)
- 📸 **Modo Captura**: Toma fotos y analiza (ideal para móviles)
- 🖼️ **Carga de Imágenes**: Analiza fotos desde tu galería
- 💾 **Historial Persistente**: Guarda tus conteos con localStorage
- 🔄 **Cambio de Cámara**: Alterna entre cámara frontal y trasera
- 📊 **Visualización Dinámica**: Overlay con resultados en tiempo real
- ⚙️ **Ajustes Personalizables**: Control de confianza de detección
- 🎨 **Interfaz Moderna**: Diseño glassmorphism con gradientes vibrantes
- ⚡ **Procesamiento Local**: Todo funciona en tu navegador (privacidad total)
- 🌐 **Sin Conexión**: Funciona offline una vez cargado

---

## 📦 Recursos del Proyecto

### 📊 Dataset Balanceado
El modelo fue entrenado con un dataset balanceado de billetes colombianos:
- **🔗 Descargar Dataset:** [Google Drive - Dataset Balanceado](https://drive.google.com/file/d/1uFbEFNNNgs6z7qcuK0EZNzunDUP1XRMi/view?usp=sharing)

### 🤖 Modelo Entrenado (YOLOv11)
Modelo YOLOv11 entrenado en formato PyTorch (.pt) y convertido a ONNX para ejecución en navegador:
- **🔗 Descargar Modelo:** [Google Drive - Modelo YOLOv11 (.pt)](https://drive.google.com/drive/folders/1tLYUr9TDe5gWNRUV846MuVUzzqPaXvlt?usp=sharing)

---

## 👥 Equipo de Desarrollo

| Nombre | Código |
|--------|--------|
| **Miguel Ángel Murillo de los Ríos** | 2220232041 |
| **Jonathan David Moya Patarroyo** | 2220222039 |

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura y semántica
- **CSS3** - Estilos modernos con gradientes y glassmorphism
- **JavaScript ES6+** - Lógica de aplicación

### IA y Procesamiento
- **YOLOv11** - Modelo de detección de objetos de última generación
- **ONNX Runtime Web** - Ejecución del modelo en navegador
- **Canvas API** - Procesamiento de imágenes
- **MediaDevices API** - Acceso a cámara

### PWA
- **Service Worker** - Funcionamiento offline
- **Web App Manifest** - Instalación como app nativa
- **localStorage** - Persistencia de datos local

---

## 📱 Modos de Operación

### 🖥️ Modo PC (Detección Automática)
- Detección continua en tiempo real
- Procesamiento automático del stream de video
- Ideal para conteos rápidos en escritorio

### 📱 Modo Móvil (Captura Manual)
- Captura fotográfica optimizada
- Análisis bajo demanda para ahorrar batería
- Cambio de cámara (frontal/trasera)

---

## 🎯 Funcionalidades Detalladas

### Detección y Conteo
- ✅ Reconocimiento de 11 denominaciones de billetes colombianos
- ✅ Cálculo automático del valor total
- ✅ Visualización de bounding boxes con confianza
- ✅ NMS (Non-Maximum Suppression) para eliminar duplicados

### Gestión de Historial
- 💾 Guardar conteos con fecha y hora
- 📊 Ver total acumulado histórico
- 🗑️ Eliminar registros individuales
- 🧹 Limpiar todo el historial

### Controles y Ajustes
- ⚙️ Ajuste de umbral de confianza (10-90%)
- 🔄 Cambio entre cámaras disponibles
- 🎨 Paneles laterales deslizables
- 📱 Interfaz adaptativa responsive

---

## 📝 Licencia

Este proyecto fue desarrollado con fines académicos como parte del curso de Inteligencia Artificial.

---

<p align="center">
  <strong>⭐ Si este proyecto te resulta útil, considera darle una estrella ⭐</strong>
</p>

<p align="center">
  <strong>💵 <a href="https://miguel0827.github.io/DetectorBilletes/">Prueba el Detector de Billetes en Vivo</a> 💵</strong>
</p>

<p align="center">
  <em>Desarrollado con ❤️ por el equipo de Inteligencia Artificial</em>
</p>
