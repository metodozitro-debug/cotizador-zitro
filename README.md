[README.md](https://github.com/user-attachments/files/26722534/README.md)
# 🧠 PRUEBA DE DIAGNÓSTICO INSTITUCIONAL VINH20institucional

Sistema desarrollado por **Método ZITRO** para la evaluación integral de instituciones educativas mediante análisis socioemocional, técnico y espiritual basado en el modelo **VINH**.

---

## 🚀 ¿Qué hace este sistema?

Este instrumento digital permite:

* 📊 Evaluar el estado socioemocional institucional en tiempo real
* 🧩 Aplicar el modelo **VINH (Vertical – Interno – Horizontal)**
* 🚦 Generar clasificación automática tipo **VINHTRIAGE (Verde, Amarillo, Rojo)**
* 📄 Crear informes PDF automáticos por evaluación
* 📬 Enviar resultados al correo del evaluador
* 🧾 Generar código único de cada evaluación
* 📈 Construir un dashboard institucional acumulativo
* 🔐 Custodiar la identidad del evaluador sin exposición directa

---

## 🏗️ Arquitectura del sistema

Este sistema funciona sobre **Google Apps Script**, integrando:

* Google Sheets → almacenamiento de datos
* Google Drive → generación de informes PDF
* MailApp → envío automático de resultados
* Web App → interfaz para evaluadores

---

## 📁 Estructura del proyecto

```bash
apps-script/
│
├── Code.gs            # Lógica backend (datos, cálculo, envío, PDF)
├── Index.html         # Interfaz principal del formulario
├── Styles.html        # Estilos visuales (UI/UX)
├── Scripts.html       # Lógica frontend (JS)
├── appsscript.json    # Configuración y permisos
```

---

## ⚙️ Funcionalidades principales

### 1. Formulario inteligente

* 20 preguntas tipo escala (1 a 5)
* Validación completa de respuestas
* Registro estructurado

### 2. Motor de análisis

* Promedio institucional
* Clasificación automática
* Activación de VINHTRIAGE

### 3. Dashboard en tiempo real

* Radar institucional
* Semáforo de estado
* Ranking
* Análisis por tipología

### 4. Reportes automáticos

* Generación de PDF por evaluación
* Consolidado institucional
* Envío automático por correo

---

## 🔐 Permisos requeridos

El sistema requiere los siguientes scopes:

```json
[
  "https://www.googleapis.com/auth/spreadsheets",
  "https://www.googleapis.com/auth/drive",
  "https://www.googleapis.com/auth/script.send_mail",
  "https://www.googleapis.com/auth/script.external_request"
]
```

---

## 🌐 Implementación

Este proyecto se ejecuta como **Web App de Google Apps Script**:

1. Ir a Apps Script
2. Click en **Implementar**
3. Seleccionar **Aplicación web**
4. Configurar:

   * Ejecutar como: **Yo**
   * Acceso: **Cualquiera con el enlace**

---

## 🔗 Uso del sistema

El enlace generado permitirá:

* Acceso al formulario
* Registro de evaluaciones
* Visualización de resultados
* Actualización del dashboard

---

## ⚠️ Importante

* GitHub **NO ejecuta** este sistema
* GitHub se usa únicamente como:

  * respaldo del código
  * control de versiones
  * documentación

La ejecución real ocurre en **Google Apps Script**.

---

## 🧩 Modelo conceptual

El sistema se basa en el modelo:

### VINH

* 🔼 Vertical → dimensión espiritual
* 🧠 Interno → emocional y cognitiva
* 🤝 Horizontal → conducta y convivencia

---

## 📌 Propiedad intelectual

© Método ZITRO
Todos los derechos reservados.

---

## 👨‍💻 Autor

**Director Alex Eduardo Silva Malaver**
Arquitecto · Diseñador de sistemas · Especialista en IA aplicada
Director General – Método ZITRO

---

## 📈 Estado del proyecto

✔ Sistema funcional
✔ Dashboard activo
✔ Generación de PDF
✔ Integración con Sheets
✔ Clasificación VINHTRIAGE

---

## 🚀 Próximas mejoras

* UI más avanzada
* Panel administrativo
* Exportación avanzada de datos
* Integración con plataformas educativas
* Automatización de seguimiento institucional

---

💡 *Este sistema no es un test tradicional. Es una herramienta de diagnóstico estructural para transformación institucional basada en ciencia, datos y cosmovisión aplicada.*
