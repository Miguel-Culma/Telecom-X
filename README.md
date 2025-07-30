# Telecom-X

# 📊 Proyecto Telecom X - Retención de Clientes

Bienvenido al análisis de datos realizado para **Telecom X**, una empresa de telecomunicaciones que enfrenta un aumento en la tasa de cancelación de sus servicios. Como parte del equipo de análisis, tu misión es identificar qué factores influyen en la decisión de un cliente de dejar la compañía.

Este estudio sirve como base para que el equipo de **Ciencia de Datos** pueda desarrollar modelos de predicción y tomar decisiones informadas que contribuyan a mejorar la fidelización de los usuarios.

---

## 🧾 Objetivo del Análisis

A través del uso de Python y bibliotecas especializadas, se realizó una exploración de datos centrada en detectar patrones relacionados con el abandono de clientes (churn). La meta principal es obtener insights útiles que respalden el diseño de estrategias de retención.

---

## 📁 Estructura del Dataset

El conjunto de datos contiene información detallada sobre los clientes, incluyendo características personales, servicios contratados, comportamiento de pago y estado de permanencia. Las columnas más relevantes incluyen:

- `Churn`: variable objetivo (abandono: sí o no)
- `tenure`: tiempo que el cliente ha estado con la empresa
- `Contract`, `PaymentMethod`, `PaperlessBilling`: condiciones contractuales
- `TechSupport`, `InternetService`, `OnlineSecurity`: servicios opcionales
- `Charges.Monthly`, `Charges.Total`: información financiera

---

## 🔍 Variables Clave Analizadas

Se estudiaron principalmente:

- Duración de la relación (`tenure`)
- Tipo de contrato (`Contract`)
- Servicios adicionales como soporte técnico (`TechSupport`)
- Factores de facturación (`PaperlessBilling`) y métodos de pago (`PaymentMethod`)
- Presencia o ausencia de servicios de internet (`InternetService`)

---

## 📈 Principales Descubrimientos

- **Relación temporal**: Los usuarios que han permanecido menos tiempo suelen ser los que más se dan de baja.

- **Tipo de contrato**: Los contratos de duración corta (mensuales) están más asociados al abandono que aquellos de largo plazo.

- **Soporte técnico**: No contar con soporte técnico incrementa la posibilidad de cancelación del servicio.

- **Internet**: Curiosamente, los clientes que no utilizan internet con la empresa tienden a mantenerse más tiempo.

- **Forma de pago**: Los pagos automatizados están relacionados con una mayor permanencia del cliente.

- **Facturación sin papel**: Este tipo de facturación se asocia con una mayor tasa de abandono.

---

## 📌 Síntesis y Reflexión

Los datos muestran que tanto el tipo de contrato como los servicios adicionales y la modalidad de pago tienen un impacto directo en la permanencia del cliente. La falta de soporte o seguridad en línea puede generar inseguridad o sensación de poco valor agregado. Además, los primeros meses son cruciales para construir una relación sólida con el usuario.

---

## ✅ Acciones Recomendadas

1. **Enfocar esfuerzos en la etapa inicial del cliente**, con experiencias positivas desde el primer contacto.

2. **Ofrecer incentivos para contratos de mayor duración**, como descuentos exclusivos o servicios incluidos.

3. **Incluir servicios como `TechSupport` en planes básicos**, o al menos mostrarlos como altamente recomendables.

4. **Estudiar el perfil de usuarios sin internet** para identificar oportunidades de expansión o retención diferenciada.

5. **Promocionar el pago automático** como un beneficio, destacando su comodidad y seguridad.

6. **Revisar la estrategia de comunicación digital**, especialmente con usuarios que reciben facturas electrónicas, para evitar desconexión o desinterés.

---

Este análisis es una base sólida para crear modelos predictivos y aplicar intervenciones preventivas que disminuyan la tasa de pérdida de clientes.
