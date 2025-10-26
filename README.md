# 🏦 Ahorrómetro — Objetivo Piso

**Ahorrómetro** es una pequeña aplicación web para gestionar tus finanzas personales de forma visual y motivadora.  
Te muestra en tiempo real cuánto dinero llevas “ganado” este mes, cuánto puedes gastar, y cómo vas respecto a tu objetivo principal: **ahorrar para tu piso 🏠**.

---

## 🚀 Características principales
- 💰 **Ingreso prorrateado hora a hora** (contador de lo que has “ganado” este mes).
- 📊 **Objetivo de ahorro** configurable (por defecto 150 000 €).
- 🗓️ **Fecha meta** (por ejemplo, dentro de 2,5 años).
- 💵 **Gastos fijos** + cálculo automático del ahorro mensual necesario.
- 📆 **Límite de gasto semanal y diario** ajustado dinámicamente.
- 🧾 **Registro rápido de gastos** con categorías.
- 📈 **Progreso visual** y mini-gráfico semanal.
- ☁️ **Todo local**, sin servidores ni cuentas (usa `localStorage`).
- 🔐 **Exportar/Importar JSON** para guardar o mover tus datos.
- 🧠 100 % offline, funciona incluso sin conexión.

---

## 🧩 Cómo usarlo

1. Abre la app desde GitHub Pages:  
   👉 **https://davcrelib.github.io/ahorrometro/**
2. Introduce tus datos:
   - Sueldo neto mensual  
   - Gastos fijos  
   - Ahorros actuales  
   - Objetivo (por ejemplo, 150 000 €)  
   - Fecha objetivo (por ejemplo, 26/04/2028)  
   - Horas trabajadas al mes
3. Pulsa **💾 Guardar plan**.
4. Cada vez que gastes algo, apúntalo en **“Añadir gasto”**.
5. Consulta tu **restante semanal** y el **progreso** hacia el objetivo.

---

## 📱 Instalarlo como app en el iPhone

1. Abre el enlace en **Safari**.  
2. Pulsa **Compartir → Añadir a pantalla de inicio**.  
3. Se instalará con su icono y se abrirá a pantalla completa.

---

## 💾 Exportar / Importar datos

- **Exportar:** genera un archivo `.json` con tus datos (guárdalo donde quieras).  
- **Importar:** selecciona el archivo para recuperar tu progreso en otro dispositivo.

---

## 🔧 Tecnologías
- HTML5 + CSS3 + JavaScript (sin frameworks)
- Almacenamiento local (`localStorage`)
- Canvas API para gráficos
- Responsive y ligero (menos de 200 KB)

---

## 🧭 Próximos pasos (roadmap)
- 🔐 Sincronización en la nube (Firebase/Supabase)
- 📱 Notificaciones semanales y recordatorios automáticos
- 🏦 Integración con bancos (open banking)
- 📈 Estadísticas y comparativas mensuales
- 💬 Multi-usuario / compartir objetivos

---

## 👤 Autor
**David Creus Librero**  
DevOps Engineer · Barcelona 🇪🇸  
💡 _Proyecto personal para aprender, motivarse y ahorrar con propósito._

---

## 🪪 Licencia
MIT — puedes usarlo, modificarlo y compartirlo libremente.
