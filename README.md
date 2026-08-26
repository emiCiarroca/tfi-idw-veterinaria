# 🐾 Veterinaria La Mary

Trabajo Final Integrador — Introducción al Desarrollo Web  
Facultad de Ciencias de la Administración — UNER  
Año: 2026

## 📋 Descripción

Desarrollo de una aplicación web para la gestión de la atención de mascotas de la clínica veterinaria **"Veterinaria La Mary"**.

El sistema permitirá gestionar:

- 🐕 Mascotas
- 👨‍⚕️ Veterinarios
- 📅 Turnos
- 🩺 Historia Clínica

Además, contará con una interfaz pública para los visitantes y un panel de administración para gestionar la información de la veterinaria.

---

## 🎯 Objetivos

El proyecto busca aplicar los conocimientos adquiridos durante la asignatura:

- HTML
- CSS
- Diseño Responsive
- Bootstrap
- JavaScript
- DOM
- LocalStorage
- Fetch
- Promesas
- Async/Await
- Consumo de API REST

---

## 👥 Integrantes

- Emanuel piriz
- Dalma Soldá
- Adriana Vallejos
- Jose Emiliano Ciarroca

| Integrante | Módulo principal | Rama |
|---|---|---|
| Nombre Apellido | Veterinarios | `feature/veterinarios` |
| Nombre Apellido | Mascotas | `feature/mascotas` |
| Nombre Apellido | Turnos | `feature/turnos` |
| Nombre Apellido | Historia Clínica | `feature/historia-clinica` |

---

## 📅 Fechas importantes

| Fecha | Entrega |
|---|---|
| **08/09/2026** | HTML y CSS |
| **29/09/2026** | CSS + RWD + Bootstrap |
| **20/10/2026** | JavaScript + DOM + LocalStorage |
| **29/10/2026** | Parcial |
| **05/11/2026** | Recuperatorio |
| **12/11/2026** | Entrega final: Fetch + Async/Await + Promesas |

---

# 🗂️ Estructura del proyecto

```text
veterinaria-la-mary/
│
├── index.html                   # Portada
├── institucional.html           # Info institucional
├── contacto.html                # Contacto
├── login.html                   # Acceso administrador
│
├── admin/
│   ├── veterinarios.html        # CRUD Veterinarios
│   ├── turnos.html              # CRUD Turnos
│   ├── mascotas.html            # CRUD Mascotas
│   └── historia-clinica.html    # Historia Clínica
│
├── css/
│   ├── styles.css                # Estilos generales/compartidos
│   └── admin.css                 # Estilos específicos del panel admin
│   
│
├── js/
│   ├── utils.js                  # Funciones compartidas: UID, LocalStorage helpers, validaciones (base común)
│   ├── auth.js                   # Login simulado y control de rol
│   ├── veterinarios.js           # Lógica CRUD Veterinarios 
│   ├── turnos.js                 # Lógica CRUD Turnos 
│   ├── mascotas.js               # Lógica CRUD Mascotas 
│   ├── historia-clinica.js       # Lógica Historia Clínica 
│   └── api.js                    # Consumo de la API REST externa vía fetch 
│
├── assets/