[![Consultar a DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/MauricioCastro16/galaxian-arcade-pharo)

# Galaxian Arcade Pharo

[![Pharo](https://img.shields.io/badge/Pharo-11.0+-orange.svg)](https://pharo.org/)

Implementación clásica del juego arcade Galaxian desarrollada en Pharo/Smalltalk con interfaz gráfica Morphic y sistema de persistencia de puntuaciones. El proyecto recrea la experiencia arcade original utilizando patrones de programación orientada a objetos y un enfoque moderno de desarrollo.

## Características Principales

- Juego arcade completo con mecánicas clásicas de Galaxian
- Sistema de patrones de enemigos configurables mediante archivos CSV
- Persistencia de puntuaciones máximas en formato CSV
- Interfaz gráfica interactiva desarrollada con framework Morphic
- Arquitectura modular basada en objetos y eventos

## Stack Tecnológico

| Categoría | Tecnología |
|-----------|------------|
| Frontend | Morphic |
| Backend | Pharo/Smalltalk |
| Base de Datos | CSV |
| Herramientas | Pharo VM 11.0+ |

## Arquitectura

El sistema sigue una arquitectura orientada a objetos donde cada componente del juego (nave, fondo, puntaje) es una clase independiente. La interfaz Morphic gestiona los eventos de usuario mientras que los archivos CSV proporcionan persistencia de datos para configuraciones y puntuaciones. El motor de juego coordina las interacciones entre todos los componentes mediante patrones de observador y delegación de eventos.

## Instalación y Uso

### Prerrequisitos
- Pharo 11.0 o superior
- Sistema operativo Windows/Linux/macOS

### Clonar el repositorio
```bash
git clone https://github.com/MauricioCastro16/galaxian-arcade-pharo.git
cd galaxian-arcade-pharo
```

### Ejecutar el proyecto
```bash
# Descargar Pharo VM si no está instalado
wget https://files.pharo.org/get-files/110/pharo64-win.zip

# Descomprimir y ejecutar la imagen
unzip pharo64-win.zip
./Pharo.exe "Galaxian - Grupo 16 - 2023.image"
```

### Configurar archivos de datos
```bash
# Asegurar que los archivos CSV existan en el directorio de la imagen
touch Score.csv
touch Naves.csv
```
