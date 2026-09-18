# 📚 Análisis de Gestión Empresarial — Speak Up

> **Tema 1 · La gestión empresarial · 2º DAM**

---

## 🏫 Caso 12 — Academia de idiomas "Speak Up"

**Speak Up** es una academia de idiomas que ofrece clases tanto **presenciales como online**, permitiendo también trabajar con alumnado de otras ciudades.

La empresa cuenta actualmente con:

- 👨‍🏫 **8 profesores**
- 🧑‍💼 **1 recepcionista**

El principal problema detectado es que **cada profesor lleva su propio control de asistencia y progreso del alumnado mediante documentos personales**, por lo que Administración no dispone de una visión conjunta de toda la información.

---

## 🎯 Objetivo de la actividad

Analizar la situación de la empresa y proponer una solución desde el punto de vista de la **gestión empresarial y los sistemas de información**.

Para ello, se estudian los siguientes apartados:

| Apartado | Contenido |
|---|---|
| 🏢 Organización | Departamentos y funciones dentro de Speak Up |
| 🔎 Diagnóstico | Síntomas y causa raíz del problema |
| ⚙️ ERP / CRM | Sistemas necesarios y características |
| 🖥️ Arquitectura | Cliente-Servidor frente a SOA |
| 🔄 E-Business | Flujos B2B, B2C y B2E |
| ✅ Conclusión | Propuesta final aplicada al caso |

---

## 🏢 Organización de la empresa

Se analizan las principales funciones necesarias en Speak Up:

- **Dirección:** toma de decisiones y coordinación general.
- **Administración / Recepción:** atención al alumnado y gestión administrativa.
- **Profesores:** impartición de clases y seguimiento de asistencia y progreso.
- **Recursos Humanos:** gestión de los trabajadores.

Al tratarse de una empresa pequeña, algunas de estas funciones pueden ser realizadas por las mismas personas y no tienen por qué existir como departamentos independientes.

---

## 🔎 Diagnóstico

### Problema principal

> **Falta de integración y centralización de la información.**

Actualmente cada profesor utiliza sus propios documentos para registrar:

- 📋 Asistencia
- 📈 Progreso del alumnado

Esto provoca que la información esté **separada entre los diferentes profesores** y que Administración no pueda consultar fácilmente una visión global.

### Consecuencias

- ❌ Información dispersa
- ⏱️ Pérdida de tiempo
- ⚠️ Posibilidad de errores
- 🔄 Dificultad para compartir información
- 👀 Falta de una visión conjunta del alumnado

---

## ⚙️ Propuesta ERP + CRM

### 🗄️ ERP

El **ERP** permitiría centralizar la gestión interna de Speak Up.

Sus principales características aplicadas al caso serían:

- 🔗 **Integrado**
- 🧩 **Modular**
- 🗃️ **Base de datos centralizada**
- ⚙️ **Configurable**

Su principal función sería sustituir los documentos independientes por una **fuente de información común**.

### 👥 CRM

El **CRM** estaría orientado a la relación de Speak Up con sus alumnos y posibles clientes.

Permitiría trabajar aspectos como:

- 📞 Atención al alumnado
- 📢 Marketing
- 💼 Gestión comercial

### 💡 Solución propuesta

**ERP → Gestión interna**

**CRM → Relación con alumnado y clientes**

Ambos sistemas pueden complementarse para mejorar la gestión global de la academia.

---

## 🖥️ Arquitectura

### Cliente-Servidor ✅

Para la situación actual de Speak Up se propone una arquitectura **cliente-servidor**.

La información podría almacenarse en un servidor central y ser utilizada por los profesores y la administración desde sus equipos.

Esto permitiría que todos trabajasen con una **información centralizada**.

### ¿Por qué no SOA actualmente?

La academia indica que **no colabora con otras academias ni empresas externas**.

Por ello, actualmente no existe una necesidad de integrar diferentes sistemas empresariales mediante servicios web.

---

## 🔄 Flujos E-Business

| Flujo | Situación | Aplicación |
|---|---|---|
| 🏫 → 👤 **B2C** | ✅ Presente | Speak Up ofrece sus servicios directamente al alumnado |
| 🏫 → 👨‍🏫 **B2E** | ✅ Presente | Relación entre la academia y sus trabajadores |
| 🏢 → 🏢 **B2B** | ❌ Actualmente no | No existen colaboraciones con otras empresas |

---

## ✅ Conclusión

La principal necesidad de **Speak Up** es conseguir que la información deje de estar repartida en documentos individuales de cada profesor.

La implantación de un **ERP** permitiría centralizar la información y mejorar la gestión interna, mientras que un **CRM** ayudaría a gestionar la relación con el alumnado y posibles clientes.

Para la situación actual, la arquitectura **cliente-servidor** resulta adecuada, ya que la academia no trabaja actualmente con empresas externas. En caso de que esto cambiase en el futuro, podría plantearse una evolución hacia **SOA**.

De esta forma, Speak Up podría pasar de una gestión basada en documentos independientes a una gestión **más integrada, organizada y coordinada**.
