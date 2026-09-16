# 🎙️ Amplificador para Micrófono Electret

Trabajo Práctico Final de **Electrónica I** — Universidad Católica "Nuestra Señora de la Asunción"
Facultad de Ciencias y Tecnología — Ingeniería Electrónica

---

## 📖 ¿Qué es?

Diseño e implementación de un **amplificador de audio para un micrófono electret**, con una ganancia de tensión total de **70 V/V** y una impedancia de carga de salida de **32 Ω** (resistencia de 10 Ω en serie con 22 Ω, simulando un parlante).

El amplificador está compuesto por **3 etapas en cascada** con transistores **2N2222** en configuración de **emisor común (clase A)**, diseñadas para amplificar gradualmente la señal y evitar deformaciones o recortes.

---

## 🎯 Objetivos

- Amplificar la señal de un micrófono electret con ganancia total de 70.
- Mantener una impedancia de entrada compatible con el micrófono.
- Entregar la señal amplificada a una carga de 32 Ω.
- Filtrar frecuencias indeseadas (rango audible, desde ~20 Hz).
- Diseñar y fabricar el PCB del circuito.

---

## ⚙️ ¿Qué se hace?

1. **Estudio del transductor:** análisis del micrófono electret y su circuito equivalente (conversor de impedancia FET).
2. **Diseño teórico:** cálculo de las 3 etapas en cascada mediante análisis DC y AC, con corriente de máxima excursión simétrica.
3. **Simulación:** uso de **SPICE** para verificar ganancias, tensiones nodales y respuesta en frecuencia. Incluye **simulación de Montecarlo** para tolerancias de componentes.
4. **Diseño de PCB:** layout en **EasyEDA** y fabricación casera mediante técnica del marcador.
5. **Montaje y mediciones:** verificación práctica con osciloscopio (Tektronix TDS 1012B), comparando valores calculados, simulados y medidos.

---

## 🧩 Componentes principales

| Componente | Descripción |
|---|---|
| **Micrófono electret** | Soberton EM-6050 (transductor de entrada) |
| **Transistor 2N2222** | 3 unidades, una por etapa (NPN, emisor común) |
| **Resistencias** | Polarización y cargas (valores calculados) |
| **Capacitores** | Acoplamiento y desacople (electrolíticos y cerámicos) |
| **Parlante 32 Ω** | Carga de salida (10 Ω + 22 Ω) |
| **Fuente Vcc = 12 V** | Alimentación del circuito |

---

## 🛠️ Tecnologías y herramientas

- **SPICE** — Simulación de circuitos
- **EasyEDA** — Diseño de PCB
- **Tektronix TDS 1012B** — Osciloscopio para mediciones
- **Fabricación casera de PCB** — Técnica del marcador + ácido

---

## 📁 Contenido del repositorio

- Código y esquemáticos del circuito
- Archivos de simulación SPICE
- Diseño de PCB (EasyEDA)
- Datasheets de los componentes
- Documento completo del trabajo

---

## 👥 Autores

- **Elías Álvarez** — Y24127
- **Tania Romero** — Y06343

---

## 🔗 Proyecto en EasyEDA

[https://oshwlab.com/eliasdavidalvarez/electronica1_tp](https://oshwlab.com/eliasdavidalvarez/electronica1_tp)
