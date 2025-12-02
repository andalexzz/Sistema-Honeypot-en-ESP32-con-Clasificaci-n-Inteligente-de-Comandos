# Sistema-Honeypot-en-ESP32-con-Clasificaci-n-Inteligente-de-Comandos

# Proyecto: Proyecto de un Honeypot con ESP32 para dispositivos IoT, que monitorea y analiza comandos recibidos. Utiliza IA para clasificar acciones legítimas y maliciosas, permitiendo estudiar ataques y mejorar la seguridad de entornos IoT de manera segura y en tiempo real.

## 1. Resumen Ejecutivo
Este proyecto desarrolla un honeypot IoT basado en un ESP32 capaz de recibir, registrar y analizar comandos enviados por atacantes o dispositivos de red. El sistema captura tráfico sospechoso y lo clasifica mediante un modelo de Inteligencia Artificial para distinguir entre acciones legítimas y maliciosas. De este modo permite estudiar ciberataques en tiempo real de manera controlada y segura.

## 2. Objetivos del Proyecto
- Diseñar un honeypot IoT funcional con ESP32.
- Registrar y almacenar comandos y tráfico entrante.
- Aplicar modelos de IA/ML para clasificar comportamientos.
- Analizar patrones de ataque y generar métricas.
- Proveer una arquitectura reproducible para investigación académica.

## 3. Arquitectura General del Sistema
La arquitectura consiste en:
- **ESP32 Honeypot:** recibe comandos vía WiFi.
- **Servidor Flask / Python:** almacena tráfico, entrena modelos y ejecuta IA.
- **Modelo de ML:** clasifica acciones en legítimas o maliciosas.
- **Dataset:** comandos anonimizados recolectados del honeypot.
- **Dashboard Web:** visualiza logs, métricas y resultados.

![Arquitectura](assets/.png)

## 4. Componentes del Repositorio
