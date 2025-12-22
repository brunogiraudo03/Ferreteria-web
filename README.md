# 🛠️ Sistema de Gestión Integral para Ferretería (PWA)



![Estado](https://img.shields.io/badge/Estado-Producción-success?style=flat-square)

![Stack](https://img.shields.io/badge/Stack-HTML_5_%7C_Bootstrap_%7C_Firebase-orange?style=flat-square)

![Tipo](https://img.shields.io/badge/App-PWA_Offline_First-blue?style=flat-square)



> **Solución digital a medida diseñada para optimizar la operativa diaria de un comercio minorista real, reemplazando la gestión manual en papel por una arquitectura en la nube.**



---



## 🚀 Demo en Vivo


Puedes probar la aplicación funcionando en tiempo real. Esta versión está conectada a una base de datos de prueba segura.


👉 **https://ferreteria-giraudo-demo.web.app**


### 🔐 Credenciales de Acceso

El sistema simula un entorno privado de negocio. Utiliza esta contraseña para ingresar:

* **Contraseña:** `ferreteria`



---



## 📖 Contexto del Proyecto



Este software no es un ejercicio teórico; resuelve una problemática real. Una ferretería de barrio gestionaba sus cuentas corrientes, stock monetario y cheques utilizando cuadernos. Esto generaba:

1.  Pérdida de datos y errores de cálculo.

2.  Lentitud en la atención al cliente.

3.  Falta de respaldo ante accidentes físicos.



**La Solución:** Una Web App Progresiva (PWA) rápida, intuitiva y tolerante a fallos de conexión, que permite al dueño tener el control total de su negocio desde cualquier dispositivo.



---



## ✨ Características Principales



### 1. 📶 Arquitectura Offline-First

Implementación robusta de **Firebase Persistence**.

* **El Problema:** La conexión a internet en la zona es inestable.

* **La Solución:** El sistema sigue operativo 100% sin internet (lectura y escritura). Los datos se sincronizan silenciosamente con la nube (Firestore) apenas vuelve la conexión.



### 2. 💰 Gestión de Caja Diaria

Tablero de control visual para el flujo de dinero:

* Balance en tiempo real desglosado por **Efectivo, Transferencias y Cheques**.

* Historial de movimientos inmutable localmente para auditoría rápida del día.

* UX optimizada para carga veloz mediante teclado.



### 3. 🤝 Cuentas Corrientes (Clientes y Proveedores)

El corazón del negocio ("El Fiado"):

* Indicadores visuales de estado de deuda (Rojo/Verde).

* **Calculadora de Bonificaciones Integrada:** Herramienta modal que permite negociar descuentos con proveedores y aplicar el monto final directamente al formulario de pago con un solo clic.



### 4. 🧾 Gestión de Valores y Presupuestos

* **Cartera de Cheques:** Seguimiento de estados (En cartera, Entregado, Depositado) para evitar vencimientos.

* **Generador de Presupuestos:** Módulo que genera vistas de impresión limpias (CSS Print Media) listas para entregar al cliente o guardar como PDF.



---



## 📘 Guía de Uso Rápida



El sistema está diseñado para la velocidad de mostrador.



### Flujo de Trabajo Recomendado

Para máxima eficiencia, se sugiere trabajar con pestañas dedicadas:

1.  **Pestaña 1 - Clientes:** Para cargar ventas a cuenta corriente rápidamente.

2.  **Pestaña 2 - Caja:** Para ventas rápidas de mostrador y gastos diarios.



### Cómo registrar operaciones

* **Agregar Deuda (Venta):** En el perfil del cliente, panel ROJO. Ingresar producto y precio. El sistema calcula el total y actualiza el saldo histórico.

* **Registrar Pago:** En el perfil del cliente, panel VERDE. Seleccionar método (Efvo/Transf/Cheque). El sistema descuenta la deuda.

* **Correcciones:** Todo movimiento tiene trazabilidad. Desde el historial (derecha) se pueden eliminar registros erróneos, recalculando el saldo automáticamente.



---



## 🛠 Tecnologías Utilizadas



* **Frontend:** HTML5 Semántico, CSS3 custom + Bootstrap 5.

* **Lógica:** JavaScript (Vanilla ES6+). Sin frameworks pesados para garantizar carga instantánea en hardware modesto.

* **Backend as a Service (BaaS):** Google Firebase (Firestore NoSQL).

* **Hosting:** Firebase Hosting (CDN Global).

* **Control de Versiones:** Git & GitHub.



---



## 👨‍💻 Autor



**Bruno Giraudo**

*Estudiante de Ingeniería en Sistemas*



Este proyecto demuestra la capacidad de transformar un requerimiento de negocio en una solución de software funcional, escalable y segura.



---

*© 2025 - Desarrollado para Ferretería de barrio.*
