---

# 🛠️ Minecraft Server Manager en Python 🎮  

Este proyecto permite descargar, instalar y ejecutar un servidor de Minecraft de forma automatizada dentro de un entorno virtual de Python. Detecta si Java no está instalado y lo descarga automáticamente. Además, solicita al usuario un nombre para la carpeta del servidor, permitiendo mayúsculas, números y símbolos para mayor practicidad.  

## 🚀 Características  
✅ **Ejecuta un servidor de Minecraft fácilmente** en un entorno virtual de Python.  
✅ **Instalación automática de Java** si no está presente en el sistema.  
✅ **Soporta múltiples versiones y tipos de servidor:** Vanilla, Forge, Fabric y Paper.  
✅ **Manejo de carpetas flexible:** El usuario puede definir un nombre con mayúsculas, números y símbolos.  
✅ **Requerimientos de memoria:** Se necesita un mínimo de 2 a 4 GB de RAM.  
✅ **Configuración manual:** No es necesario modificar el código, el usuario realiza la configuración manualmente.  

## 📌 Instalación  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/tuusuario/minecraft-server-manager.git
   cd minecraft-server-manager
   ```
2. Crea y activa un entorno virtual:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```
3. Instala las dependencias:  
   ```bash
   pip install -r requirements.txt
   ```
4. Ejecuta el script y sigue las instrucciones en pantalla:  
   ```bash
   python src/server.py
   ```
5. Configura manualmente el servidor de Minecraft según tus necesidades.  

## 📜 Licencia  
Este proyecto está bajo la licencia MIT. ¡Úsalo y modifícalo libremente!  

---
