# 🛒 Servidor de Pedidos para Mesas con Python

Sistema web liviano desarrollado en Python utilizando únicamente librerías nativas (`http.server`, `socketserver`, etc.) diseñado para gestionar menús interactivos por mesas y un panel de administración en vivo.

## 🚀 Características
- **Servidores múltiples por hilos:** Levancia simultánea de servidores en los puertos `8081`, `8082` y `8083` para las mesas 1, 2 y 3.
- **Interfaz del Cliente:** Menú interactivo con contadores dinámicos y cálculo automático del total a pagar.
- **Panel de Administración Protegido:** Autenticación HTTP Basic con usuario y contraseña para ver los pedidos en vivo mediante actualización automática por AJAX cada 5 segundos.
- **Gestión de Menú en Caliente:** Permite agregar, editar precios o eliminar platos directamente desde el panel de administración.

## 🛠️ Requisitos
- Python 3.x instalado en tu equipo.

## ⚙️ Cómo ejecutarlo
1. Clona o descarga este repositorio.
2. Abre tu terminal en la carpeta del proyecto.
3. Ejecuta el siguiente comando:
   ```bash
   python servidor.py
