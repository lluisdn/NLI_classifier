# 📌 Clasificación de correos bancarios con Inferencia de Lenguaje Natural (NLI)

Este proyecto utiliza un modelo de **Inferencia de Lenguaje Natural (NLI)** para clasificar automáticamente correos electrónicos enviados a una entidad bancaria, determinando a qué categoría temática pertenecen, como por ejemplo: cláusula suelo, fraude bancario, tarjetas, etc.

---

## 🎯 Objetivo

A partir de correos redactados en lenguaje natural por clientes, el sistema identifica la categoría que mejor representa el contenido del mensaje utilizando un modelo de NLI. Esto permite automatizar la clasificación de incidencias, reclamaciones o solicitudes sin necesidad de entrenamiento adicional.

---

## 🧠 ¿Qué es NLI?

La inferencia de lenguaje natural (NLI) evalúa la relación entre dos textos:
- **Premisa**: el texto original (en este caso, el correo).
- **Hipótesis**: una afirmación que queremos comprobar si está implícita.

El modelo devuelve una probabilidad de que la **premisa implique** la hipótesis (*entailment*), sea neutral o la contradiga.

---

## 🛠 Requisitos

- Python 3.8+
- [Transformers](https://huggingface.co/transformers/) de Hugging Face
- PyTorch
- pandas

Instalación rápida:
```bash
pip install transformers torch pandas
