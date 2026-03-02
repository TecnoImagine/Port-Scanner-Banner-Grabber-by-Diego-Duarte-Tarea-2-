# 🔎 Port Scanner & Banner Grabber – Tarea 2  
**Autor:** Diego Duarte  
**Curso:** Hacking Ético (ARACT)

Este proyecto es un escáner de puertos básico hecho en Python utilizando la librería `socket`.  
El script permite detectar puertos abiertos en una IP objetivo y obtener el banner del servicio que se esté ejecutando en cada puerto abierto.

---

## 📌 Requisitos
- Python 3.x  
- Linux / Windows / macOS  

---

## ▶️ Cómo ejecutar

```bash
python3 Tarea-2.py

#Puedes modificar la IP objetivo directamente en el archivo para escanear otro host.

```
🧪 Ejemplo de salida
Escaneando 127.0.0.1 de puerto 1 a 100...
```bash
--------------------------------------------------
Puerto 22: ABIERTO
Banner: SSH-2.0-OpenSSH_8.2p1
Puerto 80: ABIERTO
Banner: HTTP/1.1 200 OK
Puerto 443: ABIERTO
Banner: No disponible
--------------------------------------------------
Escaneo completado
