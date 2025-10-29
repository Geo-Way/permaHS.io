# permaHS.io
Visualización 3D de puntos calientes permanentes y plantas industriales con datos satelitales de la NASA
# 🌍 Cesium Hotspots Explorer

### Visualización 3D de puntos calientes permanentes y plantas industriales con datos satelitales de la NASA

---

## 🚀 Descripción general

**Cesium Hotspots Explorer** es una aplicación experimental desarrollada con **CesiumJS** que permite visualizar en 3D **puntos calientes permanentes (permanent hotspots)**, **plantas industriales** y **capas de fuegos activos** provenientes de fuentes oficiales como **NASA FIRMS** y **VIIRS**.  
El sistema integra modelos de terreno global, edificios 3D y trayectorias orbitales tipo dron para explorar de forma inmersiva regiones industriales de interés en **California**, **Australia** y **Europa**.

---

## 🛰️ Fuentes de datos

El proyecto utiliza servicios públicos de la NASA y Cesium ION:

- 🔥 **NASA FIRMS (Fire Information for Resource Management System)**  
  [https://firms.modaps.eosdis.nasa.gov/](https://firms.modaps.eosdis.nasa.gov/)  
  Proporciona detecciones térmicas de incendios y puntos calientes (MODIS y VIIRS).

- 🌡️ **MODIS (Moderate Resolution Imaging Spectroradiometer)**  
  [https://modis.gsfc.nasa.gov/data/](https://modis.gsfc.nasa.gov/data/)  
  Instrumento satelital usado para identificar anomalías térmicas globales.

- 🌍 **Cesium OSM Buildings**  
  [https://cesium.com/](https://cesium.com/)  
  Capa 3D global de edificios OpenStreetMap integrada en el visualizador.

---

## 🔬 Concepto de "Permanent Hotspots"

In an experimental geospatial context, **“permanent hotspots”** refer to recurring zones of thermal or energetic activity consistently detected over time.  
These areas often correspond to **industrial facilities, volcanic regions, or energy infrastructures** that show stable heat emissions across multiple satellite passes.

NASA’s MODIS and VIIRS sensors (accessible via [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov/) and [Earthdata](https://earthdata.nasa.gov/)) are commonly used to detect and validate such hotspots.  
Long-term datasets are analyzed to filter transient signals and identify **persistent emission sources**, enabling researchers to study **industrial energy stability**, **urban heat**, or **environmental risk zones**.

---

## 🧭 Funcionalidades principales

- 🌍 **Visualización 3D global** con terreno real y edificios OSM.  
- 🔥 **Capas de fuegos activos MODIS/VIIRS** integradas desde NASA FIRMS.  
- 🏭 **Puntos calientes industriales permanentes** (planta en EE.UU., Australia, Europa).  
- 🚁 **Modo de vuelo tipo dron**: órbita circular suave alrededor del punto seleccionado.  
- 🎥 **Tour automático** entre ubicaciones industriales clave.  
- 🧩 **Interfaz con menú deslizable** para elegir ejemplos y activar capas.  
- 🕶️ **Modo inmersivo** (pantalla completa) para experiencia 3D completa.  

---

## 📂 Estructura del proyecto


