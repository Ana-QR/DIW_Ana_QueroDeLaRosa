# DIW_QueroDeLaRosa_Ana

## Descripción
Este repositorio contiene el desarrollo de un sitio web completo utilizando **HTML, SASS y un flujo de trabajo moderno con Node y Parcel**. El proyecto sigue las directrices establecidas en clase y cumple con los requisitos mínimos indicados.

## Tecnologías utilizadas
- **HTML5**: Estructura semántica y bien organizada.
- **SASS**: Preprocesador de CSS que mejora la mantenibilidad y reutilización del código.
- **Flexbox & Grid**: Para el diseño y posicionamiento, evitando técnicas obsoletas.
- **Parcel**: Empaquetador de módulos para compilar, prefijar, minimizar y empaquetar el código.
- **Paquete de iconos**: Uso de **FontAwesome, Hero icons, Feather icons, Material icons, Iconify o flaticon** para mejorar la interfaz visual.

## Requisitos
El sitio web debe cumplir con las siguientes condiciones:

### 1. Diseño y estructura
- Debe ser **visualmente agradable**.
- Cumple con el **documento de especificaciones**.
- Organización clara del proyecto en directorios según su contenido.
- Nombres de archivos y recursos **indicativos** de su función.
- Código HTML estructurado con **etiquetas semánticas adecuadas**.
- Posicionamiento con **Flexbox o Grid** (no se permite el uso de tablas ni posicionamiento con márgenes excesivos).

### 2. Adaptabilidad
El sitio debe ser **responsive** y adaptarse a las siguientes resoluciones:
- **2560x1440**
- **1920x1080**
- **1536x864**
- **1280x800**
- **1024x1366**
- **768x1024**
- **414x896**
- **360x760**

Las imágenes deben ajustarse automáticamente a la resolución adecuada para **optimizar la carga y el rendimiento**.

### 3. Uso de SASS
El código SASS debe cumplir con:
- **Anidamiento de selectores**.
- **Uso de variables, listas y/o mapas**.
- **Estructuras de control** (bucles, condicionales).
- **Funciones personalizadas**.
- **Mixins para reutilización de estilos**.
- **Interpolación y herencia**.
- **Código limpio, eficiente y comentado**.
- Organización modular en directorios adecuados:
  - **Por funcionalidad** (botones, formularios, etc.).
  - **Por componentes** (header, footer, cards, etc.).
  - **Por disposición** (grid, flex, layouts generales).
  - **O combinando los enfoques anteriores**.

### 4. Flujo de trabajo con Node y Parcel
El desarrollo sigue un flujo de trabajo moderno con **Node.js y Parcel** para:
- **Compilación y optimización del código**.
- **Autoprefijado de CSS**.
- **Minificación de archivos para optimizar rendimiento**.
- **Empaquetado eficiente del código**.

## Instalación y configuración
### 1. Clonar el repositorio
```bash
git clone https://github.com/Ana-QR/DIW_QueroDeLaRosa_Ana.git
cd DIW_QueroDeLaRosa_Ana
```

### 2. Instalar dependencias
Asegúrate de tener **Node.js** instalado. Luego ejecuta:
```bash
npm install
```

### 3. Ejecutar el proyecto en modo desarrollo
```bash
npm run dev
```
Esto iniciará un servidor local con recarga en vivo.

### 4. Compilar para producción
```bash
npm run build
```
Esto generará los archivos optimizados en la carpeta `dist/` o como se haya llamado en el `package.json`.


## Autor
**Ana Quero De La Rosa**