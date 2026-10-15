# EVCSE 3.0 — Mobile App Experience Platform
> **"Transformamos el tiempo de carga en tiempo de valor"**  
> *Tu vehículo carga. Tú avanzas.*

EVCSE 3.0 es la primera plataforma de centros de experiencia energética y movilidad eléctrica premium de Latinoamérica. Este repositorio contiene la aplicación móvil prototipo interactiva autocontenida de 17 pantallas basada en el **Manual de Marca Oficial 2.5** y la arquitectura de experiencia **"Tiempo de Valor™"**.

## 🚀 Características Principales

- **Identidad Oficial 2.5 (Calm Luxury & Premium Utility)**:
  - Base: `#07110D` (EVCSE Deep), Contenedores: `#063D2E` (EVCSE Forest) y `#242A27` (Graphite).
  - Acentos funcionales: `#00FF4C` (Energy Green) exclusivo para acciones, progreso en vivo y confirmaciones.
  - Tipografía: **Sora** (Display/Títulos) y **Inter** (UI/Cuerpo).
- **Vehículo de Ejemplo Configurado**: **Tesla Model E** (Batería 75.0 kWh Lithium-Ion, Placa `TSL-882`, compatibilidad ultra-rápida 240 kW DC CCS2 / NACS).
- **Simulador de Dispositivo Móvil**: Marco de **iPhone 15 Pro** con Dynamic Island viva, conmutador a **Vista Responsive** y simulador de baja conectividad.
- **Navegación de 5 Hubs Estratégicos**:
  1. **Inicio (Home)**: "Your Mobility Today" — Estado del Tesla Model E (52%, 294 km), selector de intenciones (*Work Lounge, Café de Especialidad, Relax, Salas Privadas, Pet Friendly, Gourmet*) y estación recomendada.
  2. **Explorar (Explore)**: Mapa interactivo y fichas de Hubs con datos operativos (240 kW DC) y amenidades de experiencia.
  3. **Cargar (Hero Action)**: Botón central con anillo funcional y acceso directo a Pre-Carga o al **Value Clock™** en vivo.
  4. **Actividad (Activity)**: Historial holístico con kWh, tiempo en Lounge y descarga de facturas electrónicas oficiales DIAN (PDF/XML).
  5. **Pass (Profile)**: Tarjeta digital EVCSE Pass (Elite Member, saldo prepago, token NFC/QR criptográfico y facturación).
- **Innovaciones Clave**:
  - **Value Clock™**: Componente exclusivo de doble anillo sincronizado (progreso energético del vehículo + minutos recuperados para el usuario).
  - **EVCSE Smart Planner**: Algoritmo de emparejamiento entre autonomía restante, tiempo disponible y experiencia preferida.
  - **EVCSE Assist**: Triaje técnico contextual con auto-vinculación de telemetría OCPP de la sesión activa y botón directo con ingenieros NOC 24/7.
  - **Modo Baja Señal**: Caché local segura con insignias de actualización ("hace 42 segundos").

## 💻 Uso

Abre directamente `index.html` en cualquier navegador web moderno o sirve la carpeta localmente:

```bash
# Servidor HTTP local con Python
python3 -m http.server 8000
```

Navega a `http://localhost:8000/evcse-app/index.html` para explorar la experiencia completa.
