<div align="center">

# 🎉 **WasaPass**
### Sistema de Información para Gestión de Eventos  
**Proyecto Final – Sistemas de Información**  
**Grupo: Chicas Superpoderosas y Marlon**  

<img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/QR_icon.svg" width="120"/>

---

</div>

## 🌟 **Descripción General**

WasaPass es un sistema de información creado para mejorar cómo **Wasa Wasa Bar (Chapinero, Bogotá)** maneja sus eventos.  
El proyecto digitaliza procesos que antes se hacían por WhatsApp o listas manuales, como:

- Listas free  
- Preventas  
- Ingreso con QR  
- Control de aforo  
- Estadísticas y dashboards  

El resultado es una plataforma moderna que permite tomar decisiones basadas en datos reales.

---

## 🎯 **Objetivos del Proyecto**

- Eliminar pérdidas causadas por registros manuales.  
- Aumentar el control del ingreso con códigos QR únicos.  
- Centralizar la gestión de eventos y roles.  
- Conectar la base de datos con Power BI para análisis real.  
- Ofrecer un flujo completo: creación → registro → ingreso → análisis.

---

## 🛠️ **Tecnologías Utilizadas**

### **Frontend**
- React + Vite  
- TailwindCSS  
- Axios  
- React Router  

### **Backend**
- Node.js  
- Express  
- JWT  
- Mongoose  

### **Base de Datos**
- MongoDB Atlas  
- MongoDB Atlas SQL (ODBC)  

### **Business Intelligence**
- Power BI Desktop  
- Power BI Service  
- ODBC Driver MongoDB SQL  

---

## 📂 **Estructura del Repositorio**

```plaintext

│
├── software/
│   ├── client/                  # Frontend
│   ├── server/                  # Backend
│   └── README.md                # Guía técnica interna
│
├── entregables/                 # PDF de la entrega final
│   ├── tercer_entregable.pdf
│   ├── segundo_entregable.pdf
│   └── primer_entregable.pdf
│
├── dashboards_powerbi/
│   ├── dashboard1.pbix
│   ├── dashboard2.pbix
│   └── dashboard1y2.txt
│
└── presentacion_final/
    ├── presentacion_final.pdf
    └── enlace_canva.txt
```
Cómo Ejecutar el Proyecto
📌 1. Clonar el repositorio
bash
Copiar código
git clone https://github.com/TU-USUARIO/codigo_tercerentregable.git
📌 2. Configurar y correr el backend
bash
Copiar código
cd software/server
npm install
npm start
Crear .env con:

ini
Copiar código
MONGO_URI=...
JWT_SECRET=...
PORT=3000
📌 3. Configurar y correr el frontend
bash
Copiar código
cd ../client
npm install
npm run dev
📊 Dashboards de Power BI
Los dashboards se conectan directo a la base de datos real usando MongoDB SQL Interface.

Incluyen:

Ventas por evento

Registros por tipo (preventa / free list)

Ocupación del aforo

Ranking de eventos

Análisis por mes, evento y tipo

Puedes abrirlos desde /dashboards_powerbi/.

🔍 Hallazgos Principales
⭐ 1. Los tardeos son los eventos más concurridos
Tienen más registros totales que los eventos nocturnos.
Recomendación: aumentar pauta, promociones y DJs invitados para tardeos.

⭐ 2. La ocupación global es baja (<35%)
La mayoría de eventos no alcanzan ni la mitad del aforo.
Recomendación: fortalecer difusión, usar campañas de fidelización y ajustar capacidad.

⭐ 3. Octubre generó más dinero que noviembre
Por Halloween, octubre tuvo ingresos muy superiores.
Recomendación: crear eventos temáticos mensuales para mantener picos de venta.

👩‍💻 Equipo de Desarrollo
Chicas Superpoderosas y Marlon
💖 Sofía Rodríguez

💥 Valentina Gutierrez

✨ Nicole Celemin 

🔥 Marlon Pabon

❤️ Agradecimientos
Al profe por el acompañamiento, y a los compañeros por el arduo trabajo.

<div align="center">
✨ WasaPass
Experiencias más rápidas. Eventos más inteligentes.

</div> ```
