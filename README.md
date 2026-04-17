# 🧰 ElevenToolbox — Optimiza, limpia y personaliza Windows 11

**ElevenToolbox** es una herramienta todo‑en‑uno diseñada para mejorar el rendimiento, estabilidad y experiencia de Windows 11 mediante una interfaz moderna, intuitiva y totalmente personalizable.  
Incluye utilidades avanzadas para optimizar el sistema, gestionar servicios, controlar el arranque, instalar aplicaciones esenciales y aplicar configuraciones con un solo clic.

---

## 📸 Capturas de pantalla
![screen-install](https://raw.githubusercontent.com/pcastroc08/ElevenToolbox/main/assets/ventana-principal.png)
- `img/apps.png`  
- `img/arranque.png`  
- `img/info.png`  

---

## ✨ Características principales

### ⚡ Optimizador avanzado
- Más de **30 tweaks** organizados por categorías (Esencial, Avanzado, Extra…)  
- Ajustes de rendimiento, privacidad, servicios, red, energía y más  
- Descripciones detalladas al pasar el ratón  
- **Perfiles personalizados** (guardar/cargar)  
- Modo automático mediante atajo de teclado  

### 🎨 Interfaz moderna
- **Tema claro y oscuro automático** según Windows  
- Cambio manual mediante toggle visual  
- Diseño limpio, minimalista y fácil de usar  
- Contadores dinámicos de elementos seleccionados  
- Scroll suave y paneles organizados  

### 📦 Instalador de aplicaciones (Winget)
- Catálogo ampliado con más de **50 aplicaciones**, organizadas por categorías:
  - Navegadores  
  - Utilidades  
  - Multimedia  
  - Diseño y 3D  
  - Desarrollo  
  - Gaming  
  - Documentos  
  - Instituto  
  - Red / Seguridad  
- Instalación silenciosa con un clic  
- Registro de instalación en tiempo real  
- Barra de progreso integrada  

### 🚀 Gestor de arranque
- Lista completa de programas que inician con Windows  
- Tarjetas visuales con nombre, ruta y origen  
- Botón para deshabilitar cada elemento  
- Buscador integrado  
- Compatible con HKCU, HKLM y carpeta Startup  

### 🖥 Información del sistema
- Datos en tiempo real de:
  - CPU  
  - RAM  
  - GPU  
  - Red  
  - Almacenamiento  
- Presentación clara y accesible  

### 🔐 Activación HWID (opcional)
- Lanza el activador en una ventana separada  
- No modifica archivos internos del programa  

### 🛡 Elevación automática
- El script se reinicia como administrador si es necesario  
- Compatible con `.ps1` y `.exe`

---

## 🧩 Arquitectura del proyecto

ElevenToolbox está construido en **PowerShell + WinForms**, con una estructura modular:
- /UI → Interfaz gráfica
- /Tweaks → Scripts de optimización
- /Apps → Catálogo de aplicaciones
- /Startup → Gestión de arranque
- /SystemInfo → Lectura de hardware y rendimiento
- /Themes → Sistema de tema claro/oscuro

Esto facilita el mantenimiento y la expansión del proyecto.

---

## 📥 Instalación

### Método 1 — Ejecutar el `.exe`
1. Descarga la última versión desde **Releases**  
2. Ejecuta `ElevenToolbox.exe`  
3. El programa se elevará automáticamente a administrador  

### Método 2 — Ejecutar el `.ps1`
1. Descarga `ElevenToolbox.ps1`  
2. Clic derecho → *Ejecutar con PowerShell*  
3. El script se reiniciará como administrador si es necesario  

---

## 🧑‍💻 Uso

### Optimizador
1. Marca los tweaks que quieras aplicar  
2. Guarda un perfil si quieres reutilizarlo  
3. Pulsa **Ejecutar seleccionados**  

### Instalador de aplicaciones
1. Busca o navega por categorías  
2. Marca las apps que quieras instalar  
3. Pulsa **Instalar seleccionadas**  

### Gestor de arranque
1. Revisa los programas que inician con Windows  
2. Deshabilita los que no necesites  
3. Usa el buscador para filtrar  

### Tema claro/oscuro
- Se adapta automáticamente al tema de Windows  
- Puedes cambiarlo manualmente con el toggle  

---

## ⌨️ Atajos de teclado

- **Ctrl + Shift + S** → Guardar perfil  
- **Ctrl + Shift + L** → Cargar perfil  
- **Ctrl + Shift + A** → Modo automático de optimización  

---

## ❓ Preguntas frecuentes (FAQ)

### ¿Es seguro usar ElevenToolbox?
Sí. Todos los tweaks están diseñados para ser **seguros y reversibles**.  
No se eliminan servicios críticos ni se aplican cambios destructivos.

### ¿Necesito conocimientos avanzados?
No. La interfaz está pensada para usuarios de cualquier nivel.

### ¿Puedo romper Windows?
No si usas los tweaks recomendados.  
Los ajustes avanzados están claramente marcados.

### ¿Puedo añadir mis propias apps?
Sí. El catálogo es totalmente editable.

### ¿Funciona en Windows 10?
No está diseñado para ello, pero algunos módulos podrían funcionar.

---

## 🧱 Roadmap

- [ ] Añadir modo “Gaming Boost”  
- [ ] Añadir modo “Productividad”  
- [ ] Añadir restauración completa de tweaks  
- [ ] Añadir más categorías de aplicaciones  
- [ ] Añadir soporte para plugins externos  
- [ ] Añadir estadísticas de uso  

---

## ❤️ Contribuciones

Cualquier sugerencia, mejora o reporte de errores es bienvenida.  
Puedes abrir un **Issue** o enviar un **Pull Request**.

---

## 📜 Licencia

Este proyecto se distribuye bajo licencia **MIT**.  
Si necesitas el archivo `LICENSE`, puedo generarlo.

