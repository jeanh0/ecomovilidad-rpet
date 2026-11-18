# EcoMovilidad PET: Ingeniería de Materiales y Hardware Abierto para Movilidad Asistida

## Eje Rector
Economía circular, ingeniería de polímeros reforzados, manufactura abierta descentralizada y autosustentabilidad social.

---

## Resumen Ejecutivo
El proyecto **EcoMovilidad PET** transforma el pasivo ambiental generado por el volumen masivo de residuos de tereftalato de polietileno (PET) en una materia prima de alto valor estratégico. Mediante una arquitectura de manufactura descentralizada y un modelo de doble flujo, el sistema produce dispositivos de movilidad ortopédica de alta resistencia (bastones y muletas) entregados a costo cero ($0 MXN) para sectores vulnerables, financiados mediante la comercialización de excedentes de pelet técnico en el mercado industrial.

---

## Módulo I: Ciencia de Materiales y Formulación del Compuesto
Para superar la baja rigidez y el fenómeno de *creep* (fluencia lenta) del rPET convencional bajo carga dinámica continua, se establece la formulación estandarizada del compuesto termoplástico propietario:
- **Matriz Polimérica (78% - 80%):** rPET (PET reciclado post-consumo acopiado localmente).
- **Refuerzo Estructural (20% - 30%):** Fibra de Vidrio Corta (*Short Glass Fiber - GF*) para elevar drásticamente el módulo elástico.
- **Compatibilizante (1% - 2%):** Anhídrido Maleico (MAh) como extensor de cadena para restaurar el peso molecular y garantizar la adhesión interfacial fibra-matriz.
- **Tratamiento Térmico de Curado (*Annealing*):** Ciclo posterior al moldeo entre $130^\circ\text{C}$ y $150^\circ\text{C}$ para elevar la cristalinidad a $\chi_c > 35\%$, otorgando estabilidad dimensional y resistencia a la fatiga térmica.

### Cuadro Comparativo de Rendimiento Mecánico
| Propiedad Mecánica | rPET Sin Modificar | Compuesto EcoMovilidad PET | Norma de Referencia |
| :--- | :--- | :--- | :--- |
| **Resistencia a la Tracción** | ~55 - 60 MPa | **135 - 150 MPa** (Estándar >120 MPa) | ASTM D638 / ISO 527 |
| **Módulo de Flexión (Rigidez)** | ~2.2 GPa | **8.5 - 9.8 GPa** (Estándar >7.0 GPa) | ASTM D790 / ISO 178 |
| **Resistencia al Impacto (Izod)** | ~3.5 kJ/m² | **9.0 - 11.5 kJ/m²** (Estándar >8.0 kJ/m²) | ASTM D256 / ISO 180 |

---

## Módulo II: Infraestructura Industrial y Proceso (Línea de Extrusión)
- **Maquinaria Base (Modelo TSE-75A):** Extrusora de doble husillo con motor de 132 kW y rendimiento de 500-800 kg/h, equipada con sistemas de desgasificación al vacío, alimentador lateral para fibra de vidrio y control PID de temperatura en zonas de fusión ($240^\circ\text{C} - 260^\circ\text{C}$).
- **Maquila de Amortización Acelerada:** Acuerdos estratégicos con plantas recicladoras locales con capacidad ociosa en corredores industriales del Estado de México (Ecatepec, Rústica Xalostoc, Tlalnepantla). Las mejoras tecnológicas instaladas (como tableros PID) se amortizan mediante descuentos directos sobre la tarifa por kilo procesado.
- **Respaldo Energético:** Sistema solar fotovoltaico híbrido/Off-Grid de **10 kWp** para garantizar continuidad operativa ante fluctuaciones eléctricas.

---

## Módulo III: Estudio Financiero y Modelo de Doble Flujo
- **Inversión Inicial (CAPEX):** Estimada en **~1.6 MDP** para infraestructura base, habilitación de planta y sistema solar fotovoltaico.
- **Estructura de Costos Unitarios:** Costo directo de fabricación de **~\$30.00 MXN** por bastón/muleta (~\$12.00 MXN de materia prima compuesta y ~\$18.00 MXN de energía y mano de obra), frente a los precios comerciales de \$150 - \$400+ MXN.
- **Modelo Económico (Meta de 25 Toneladas Mensuales):** 
  - Se procesan 25 toneladas de PET al mes.
  - Una fracción menor se destina a la línea de dispositivos ortopédicos.
  - La gran mayoría (**22.6 toneladas mensuales**) se comercializa como pelet técnico en el mercado industrial, generando el flujo de caja necesario para recuperar la inversión en **13 a 14 meses** y **subsidiar al 100% la producción mensual de 3,330 bastones/muletas entregados a costo cero (\$0 MXN)**.

---

## Módulo IV: Blindaje Legal, Normativo y Gobernanza
- **Cumplimiento Normativo Internacional:** Validación bajo las normas ISO 11199-1 / ISO 11199-2 para ayudas para caminar, respaldado por ensayos destructivos obligatorios de laboratorio por cada lote liberado para eliminar pasivos de responsabilidad civil.
- **Propiedad Intelectual y NDAs:** Contratos estrictos de confidencialidad y exclusividad sobre la formulación propietaria y los ciclos de curado térmico (*annealing*).
- **Transparencia Institucional:** Padrones de beneficiarios estrictamente auditados y supervisados por comités comunitarios independientes (tales como el **Club Rotario**), blindando la operación frente a sesgos políticos o clientelares.

---

## Módulo V: Logística Internacional y Exportación
- **Diseño Geométrico Modular:** Los dispositivos ortopédicos se diseñan en secciones ensamblables y desarmables, abatiendo drásticamente el volumen físico de embalaje ("evitar transportar aire") para hacer viable la exportación a gran escala hacia mercados de Norteamérica y Centroamérica.

---

## ⚖️ Licencia y Marco Legal
Este proyecto se rige bajo los estándares de código abierto y hardware abierto bajo la licencia **CERN-OHL-P / GPLv3**, garantizando la libre circulación de propuestas técnicas, diseños CAD, esquemas mecatrónicos y desarrollo comunitario no monetizado[cite: 2, 3].

---

## 🚦 Estado del Proyecto
- **Estado Actual:** `Fase de Prototipado y Validación Conceptual`
- **Versión:** `1.0.0`
- **Mantenimiento:** Abierto a colaboración, revisión de diseño de procesos e integración industrial.

---
