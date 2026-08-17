# didi_sistema_AF1_2169673
ACTIVIDAD U1-F01. ANÁLISIS DE UN SISTEMA REAL 2169673 
Sistema Seleccionado: DiDi (Plataforma de Movilidad y Transporte)  
Arquitectura de 3 Capas (Análisis Conceptual):
Capa de Presentación:
App Pasajero: Interfaz móvil (iOS/Android) donde el usuario ingresa origen/destino, visualiza tarifas estimadas, selecciona método de pago, monitorea la ruta en mapa GPS y califica el viaje.App 
Conductor: Interfaz para recibir solicitudes de viaje, aceptar/rechazar ofertas, navegación GPS integrada, panel de ganancias y cambio de estado (Conectado/Desconectado).
Capa de Lógica de Negocio:
Algoritmo de asignación y matching en tiempo real entre pasajeros y conductores cercanos.Motor de precios dinámicos (ajuste por oferta, demanda, clima y tráfico).
Verificación de requerimientos de seguridad (cálculo de tiempo de cancelación, saldo del conductor, validación de PIN).Procesamiento de cobros y dispersión de pagos.
Capa de Datos:
Base de datos relacional y geoespacial para almacenar perfiles de usuarios, conductores, historial de viajes, pagos, métricas de calificaciones y estado de la flota en tiempo real.
