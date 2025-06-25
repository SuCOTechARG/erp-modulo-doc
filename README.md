# README.md

## ERP - Módulo de Gestión de Documentos

Este repositorio contiene el módulo de **Gestión de Documentos** del ERP para PyMEs, desarrollado con **Django** para el backend y **Vue 3 + Vite** para el frontend. Permite gestionar:

- Órdenes de Venta
- Órdenes de Compra
- Órdenes de Producción
- Facturas

### 🚀 Tecnologías
- Backend: Django + Django REST Framework
- Frontend: Vue 3 + Vite + TailwindCSS
- Base de datos: PostgreSQL
- Contenedores: Docker + docker-compose

---

## 🔧 Requisitos
- Docker y Docker Compose instalados
- (Opcional) Python 3.10+ y Node 18+ si trabajás fuera de contenedores

---

## 🧪 Configuración Rápida (modo desarrollo)

1. Clonar el repositorio:
```bash
git clone https://github.com/tu-usuario/erp-gestion-documentos.git
cd erp-gestion-documentos
```

2. Crear el archivo `.env`:
```bash
cp backend/.env.template backend/.env
# Editar las variables necesarias si es requerido
```

3. Levantar todo con Docker Compose:
```bash
docker-compose up --build
```

4. Acceder a la app:
- Frontend: http://localhost:5173
- Backend API: http://localhost:8000/api/

---

## 📁 Estructura del Proyecto

```
erp-gestion-documentos/
├── backend/         # Proyecto Django
│   └── documentos/  # App del módulo
├── frontend/        # Proyecto Vue 3 + Tailwind + Vite
├── docs/            # Documentación técnica
```

---

## 📚 Documentación
Ver `/docs/Modulo_Gestion_Documentos.md` para la documentación completa del módulo.

---

## ✍️ Autores
- Adrián Grzybowski
- Con asistencia de ChatGPT

---

## 📝 Licencia
MIT - libre para usar, modificar y distribuir.
