# Hola, soy Ximena Ebertz (@xebertz)

Soy **desarrolladora Full‑Stack** enfocada en construir aplicaciones de negocio robustas, con especial interés en backend, diseño de APIs y bases de datos.

- 🇦🇷 Español nativo
- 🇺🇸 **Inglés** (comunicación técnica / documentación)

---

## Stack principal

- **Backend:** Java, Spring Boot, .NET Framework, .NET, Python
- **Bases de datos:** PostgreSQL, SQL Server, MongoDB
- **SQL:** modelado relacional, consultas, optimización
- **Contenedores:** Docker
- **APIs:** diseño REST, documentación y consumo
- **Testing:** pruebas unitarias / de integración (cuando aplica)

---

## Enfoque y buenas prácticas

- Arquitectura limpia y código mantenible
- Testing y calidad (cuando aplica)
- Documentación clara
- Soluciones simples, confiables y fáciles de operar

---

## Proyectos

### EntityObjectMapper

EntityObjectMapper es una librería en **C# (.NET Framework 4.8)** para simplificar el acceso a **SQL Server**, centralizando la ejecución de **queries** y **stored procedures** y ofreciendo **mapeo automático** de resultados a objetos fuertemente tipados mediante atributos (por ejemplo, `[ColumnName]`). Incluye soporte para parámetros, transacciones y distintos niveles de aislamiento.

- **URL** — [EntityObjectMapper](https://github.com/xebertz/EntityObjectMapper)

### TASkOcupado

TASkOcupado es una aplicación que permite crear y asignar tareas a miembros de un equipo. Fue desarrollado utilizando MVC, y cuenta con los siguientes repositorios:

- **[TASkOcupadoCore](https://github.com/pp2-ungs/TASkOcupadoCore)** — Modelo de dominio y lógica core de *TASkOcupado*, incluyendo patrón **Observer** y asignación/notificación de tareas.  
  
- **[TASkOcupadoUI](https://github.com/pp2-ungs/TASkOcupadoUI)** — Interfaz desktop + capa controller para *TASkOcupado*, con arquitectura **MVC** y actualizaciones en tiempo real vía Observer.  
  
- **[TASkOcupadoConfig](https://github.com/pp2-ungs/TASkOcupadoConfig)** — Módulo de configuración y extensibilidad para carga dinámica de recursos e integración con notifiers externos.  
  
- **[EmailNotifier](https://github.com/pp2-ungs/EmailNotifier)** — Notificador por **Email (SMTP)** para *TASkOcupado*, pensado para descubrimiento/carga dinámica e integración por Observer.  
  
- **[TelegramNotifier](https://github.com/pp2-ungs/TelegramNotifier)** — Notificador por **Telegram** para *TASkOcupado*, observando asignaciones para enviar alertas inmediatas.  
  
- **[AssignmentLogger](https://github.com/pp2-ungs/AssignmentLogger)** — Servicio externo de logging que se suscribe como Observer para registrar/persistir el historial de asignaciones.  
  
> Proyectos públicos de la organización **pp2-ungs**.

### PenTesAgent

PenTesAgent es un sistema experimental de **clasificación de vulnerabilidades** basado en **Machine Learning** a partir de **tráfico de red**. Incluye un pipeline para **generación de dataset** (captura con `tshark` + extracción de features con **CICFlowMeter**), **entrenamiento de modelos** (Random Forest y una red neuronal con **TensorFlow/Keras**) y un **agente autónomo** que realiza discovery/probing, captura flujos y clasifica objetivos con un modelo entrenado. En modo laboratorio, el agente puede además **realizar movimiento horizontal/lateral** de forma controlada, basándose en la clasificación/predicción del modelo de IA generado para decidir objetivos.

- **URL** — [PenTestAgent](https://github.com/xebertz/PenTestAgent)

### BIOS

BIOS es un proyecto en **Python** de **clasificación de imágenes médicas** para **detectar enfermedades mediante IA**, donde se desarrollaron **3 modelos de IA** para distintos diagnósticos. El repositorio incluye la documentación del proceso y la evolución del trabajo, que es parte de un proyecto mayor en el que se utiliza SAFe.

- **URL** — [BIOS](https://github.com/xebertz/BIOS)

---

## Contacto

- **Email:** <ebertz.xime@gmail.com>
- **LinkedIn:** <https://www.linkedin.com/in/ximena-ebertz>