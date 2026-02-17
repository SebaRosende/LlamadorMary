# 🔔 LlamadorResto - Sistema de Gestión de Turnos en Tiempo Real

LlamadorResto es una aplicación web diseñada para optimizar la atención al cliente en restaurantes o agencias. Permite gestionar una fila de espera de forma dinámica, mostrando en una pantalla pública el turno llamado y manteniendo la sincronización en tiempo real mediante Firebase.

---

## 🚀 Características

- **Gestión de Turnos:** Interfaz para que el personal administrativo llame al siguiente cliente o reinicie la cola.
- **Sincronización en Tiempo Real:** Uso de **Firebase Realtime Database** para que los cambios se reflejen instantáneamente en la pantalla del cliente.
- **Seguridad:** Reglas de base de datos configuradas para proteger la integridad de los datos.
- **Diseño Responsive:** Optimizado para tablets (uso administrativo) y pantallas grandes (vista al público).
- **Despliegue Continuo:** Alojado en **GitHub Pages** para un acceso rápido y gratuito.

## 🛠️ Tecnologías Utilizadas

- **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+).
- **Backend/Base de Datos:** Firebase Realtime Database.
- **Autenticación:** Firebase Auth (opcional para acceso administrativo).
- **Control de Versiones:** Git & GitHub.
- **Hosting:** GitHub Pages.

🖥️ Uso
Vista de Cliente: Los usuarios ven en una pantalla grande el número que está siendo atendido actualmente.

Panel Administrativo: El personal ingresa (mediante login) para presionar el botón "Siguiente" o "Llamar", lo que dispara una actualización visual y sonora en la pantalla principal.

Realizado con 💪 por Sebastian Rosende