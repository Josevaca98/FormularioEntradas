# Formulario de Entrada de Datos con Tkinter y Excel  

Este proyecto es una aplicación de escritorio desarrollada en Python con Tkinter para capturar información de usuarios y almacenarla en un archivo Excel.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/4470f2c5-434d-4bd2-a1db-1647eb8097e9" alt="Descripción de la imagen" />
</p>

## 📌 Características  
- ✅ Interfaz gráfica con `Tkinter`.  
- ✅ Validación de datos (correo electrónico, edad y teléfono).  
- ✅ Almacenamiento de datos en un archivo Excel (`openpyxl`).  
- ✅ Mensajes emergentes de confirmación y advertencia.  
- ✅ Uso de un entorno virtual para gestionar dependencias.  

## 🛠 Tecnologías utilizadas  
- Python  
- `tkinter`  
- `openpyxl`  
- `re` (Expresiones regulares)  
- `os`  

## 🚀 Cómo usar  
1. Clona este repositorio.  
2. Crea y activa un entorno virtual:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # En macOS/Linux
   venv\Scripts\activate  # En Windows
   ```
3. Instala las dependencias:  
   ```bash
   pip install -r requirements.txt
   ```
4. Ejecuta el script:  
   ```bash
   python main.py
   ```
5. Ingresa los datos en el formulario.  
6. Presiona el botón "Guardar" para almacenarlos en `datos.xlsx`.  
7. El archivo Excel se actualizará automáticamente con cada nuevo registro.  

## 📂 Estructura del Proyecto  
```
Proyecto_03_FormularioExcel/
│── venv/               # Entorno virtual de Python
│── main.py             # Script principal
│── datos.xlsx          # Archivo Excel con los registros (se genera automáticamente)
│── requirements.txt    # Archivo con las dependencias necesarias
```

## 📜 Licencia  
Este proyecto es de uso libre.  

---
👨‍💻 **Desarrollado por:** José María Vaca González  
📧 **Contacto:** [licjmvg98@gmail.com](mailto:licjmvg98@gmail.com)
