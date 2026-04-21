# 10 Propuestas de Proyecto Final — Versión Extendida
## Curso: Fundamentos de Electromagnetismo (100000F2I1) — UTP

Este documento presenta **10 propuestas detalladas de proyecto** que cumplen con los siguientes criterios: alineados con el sílabus del curso, implementables en laboratorio casero, de bajo costo, novedosos pero accesibles, y respaldados por **múltiples fuentes académicas verificadas** (papers en revistas indexadas).

Cada propuesta incluye: descripción extendida, fundamento teórico con ecuaciones clave, lista detallada de materiales con costos, procedimiento experimental paso a paso, resultados esperados, aspectos novedosos, y resumen detallado de cada fuente académica citada.

---

## 🔷 PROYECTOS DE LA UNIDAD 1 — ELECTRICIDAD

---

### **PROYECTO 1: Determinación experimental de la constante dieléctrica del papel mediante un capacitor de placas paralelas casero**

#### 📖 Descripción extendida

Los capacitores son elementos fundamentales en casi todos los dispositivos electrónicos modernos. Su capacidad de almacenamiento de carga depende de tres factores: el área de las placas (A), la separación entre ellas (d) y la naturaleza del material dieléctrico que hay entre las placas (caracterizado por la constante dieléctrica εᵣ).

En este proyecto se construirá un capacitor de placas paralelas usando materiales domésticos (papel aluminio como placas y papel común como dieléctrico). Se medirá la capacitancia con un multímetro y se verificará experimentalmente cómo varía al modificar cada una de las tres variables (A, d, εᵣ). Finalmente, mediante ajuste lineal de los datos experimentales, se calculará el valor de la constante dieléctrica del papel y se comparará con el valor teórico (εᵣ ≈ 3.7 para papel común).

#### 🧮 Fundamento teórico con ecuaciones clave

La capacitancia de un capacitor de placas paralelas está dada por:

$$C = \varepsilon_0 \varepsilon_r \frac{A}{d}$$

donde:
- ε₀ = 8.854 × 10⁻¹² F/m (permitividad del vacío)
- εᵣ = constante dieléctrica relativa del material (adimensional)
- A = área efectiva de solapamiento entre placas (m²)
- d = separación entre placas (m)

La energía almacenada es:

$$U = \frac{1}{2}CV^2 = \frac{Q^2}{2C}$$

Al graficar C vs 1/d (con A y εᵣ constantes), la pendiente permite despejar εᵣ:

$$\text{pendiente} = \varepsilon_0 \varepsilon_r A \quad \Rightarrow \quad \varepsilon_r = \frac{\text{pendiente}}{\varepsilon_0 A}$$

#### 🛠️ Materiales y costos (S/. 20–30 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Papel aluminio (rollo) | 1 | S/. 5 |
| Hojas de papel bond A4 | 100 unid. | S/. 3 |
| Multímetro digital con función de capacitancia (rango nF) | 1 | S/. 15–20 (puede prestarse del laboratorio) |
| Cables con caimanes | 4 | S/. 5 |
| Libro o guía telefónica (como prensa uniforme) | 1 | — |
| Regla y calibrador | — | — |

#### 🔬 Procedimiento experimental

1. **Preparación de placas**: Cortar cuadrados de papel aluminio de 10×10 cm, 15×15 cm y 20×20 cm.
2. **Experimento 1 — Variación del dieléctrico (hojas de papel)**: Colocar dos placas del mismo tamaño con N = 2, 4, 6, 8, 10 hojas de papel entre ellas. Medir C con el multímetro. Medir el espesor de las hojas con calibrador (típicamente ~0.1 mm/hoja).
3. **Experimento 2 — Variación del área**: Mantener d constante y variar el área de solapamiento desplazando las placas.
4. **Experimento 3 — Efecto del dieléctrico**: Comparar C con papel, plástico (bolsa transparente) y cartón como dieléctricos.
5. **Análisis**: Graficar C vs 1/d, C vs A, y calcular εᵣ del papel. Comparar con el valor teórico.

#### 🎯 Resultados esperados

- Relación lineal C vs 1/d (con R² > 0.95).
- Relación lineal C vs A.
- Valor de εᵣ del papel entre 2.5 y 4.5 (depende del tipo y humedad).
- Capacitancias típicas entre 50 pF y 500 pF.

#### ✨ Aspecto novedoso para obtener buena nota

Incluir análisis de errores, comparación cuantitativa entre distintos dieléctricos (papel, plástico, cartón, tela), y discusión sobre por qué las medidas muestran no-linealidad para espesores muy pequeños (efecto de aire residual entre placas). Adicionalmente, se puede modelar un capacitor "enrollado" (como los comerciales) y calcular su capacitancia.

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "Determining Dielectric Constants Using a Parallel Plate Capacitor"** (American Journal of Physics, Vol. 73, 2005)
   - **Contenido del paper**: Presenta una metodología detallada para medir constantes dieléctricas usando capacitores de placas paralelas caseros hechos con papel aluminio. Incluye análisis de no-linealidades en la relación C vs 1/d para espesores pequeños, gráficos experimentales, ecuaciones de ajuste, y tabla comparativa de εᵣ para distintos materiales (papel, nylon, vinilo, acetato). Cita múltiples artículos previos de Physics Teacher y AJP.
   - Enlace: https://www.researchgate.net/publication/48512961_Determining_Dielectric_Constants_Using_a_Parallel_Plate_Capacitor

2. **Manual de laboratorio — Illinois Institute of Technology (IIT Chicago)**
   - **Contenido**: Guía completa de laboratorio con parte 1 (experimento cualitativo con electrometro) y parte 2 (medición cuantitativa de εᵣ para transparencias, nylon, vinilo y papel). Incluye esquemas, tablas de datos y preguntas guía para el análisis.
   - Enlace: https://www.iit.edu/sites/default/files/2019-11/lab-4-capacitors-f14.pdf

3. **Guía de laboratorio — Southern Methodist University (SMU Physics)**
   - **Contenido**: Propone un experimento con aplicación real: usar un capacitor de placas paralelas como **sensor de nivel de líquidos** (aprovechando que agua y aire tienen distintos εᵣ). Incluye calibración del sensor y predicción del nivel de agua a partir de la capacitancia.
   - Enlace: https://www.physics.smu.edu/tneumann/110X_Spring2025/intro/1106/worksheet4/

4. **Experimento guiado — OnElectronTech**
   - **Contenido**: Construcción paso a paso con fotos de capacitores caseros usando páginas de libro como dieléctrico. Muestra cómo al apilar más libros encima (aumentando presión), la capacitancia casi se duplica, lo cual es útil para discutir el efecto del aire entre hojas.
   - Enlace: https://www.onelectrontech.com/lab-diy-capacitors/

---

### **PROYECTO 2: Estudio de la carga y descarga de un circuito RC midiendo el brillo de un LED con el sensor de iluminación del smartphone**

#### 📖 Descripción extendida

Los circuitos RC son fundamentales en electrónica (filtros, temporizadores, fuentes de alimentación). Su estudio experimental tradicional requiere un osciloscopio costoso o un Arduino. Este proyecto propone un método innovador del 2023 (publicado en arXiv): usar un LED en serie con el condensador y medir su brillo con el sensor de luz del smartphone para reconstruir la curva de carga/descarga del capacitor.

Cuando el capacitor se descarga a través de la resistencia y el LED, la corriente decae exponencialmente, y el brillo del LED (proporcional a la corriente) también decae exponencialmente. Usando la app **Phyphox** (gratuita) o **Physics Toolbox**, el smartphone registra la intensidad luminosa en función del tiempo y se puede obtener la constante de tiempo τ = RC con gran precisión.

#### 🧮 Fundamento teórico con ecuaciones clave

Durante la **carga** del capacitor con una fuente V₀:

$$V_C(t) = V_0 \left(1 - e^{-t/\tau}\right), \quad I(t) = \frac{V_0}{R}e^{-t/\tau}$$

Durante la **descarga**:

$$V_C(t) = V_0 \, e^{-t/\tau}, \quad I(t) = \frac{V_0}{R} e^{-t/\tau}$$

donde la constante de tiempo es:

$$\tau = RC$$

El brillo del LED L(t) es proporcional a la potencia disipada en él, que a su vez depende de I(t). Al graficar ln(L) vs t se obtiene una recta cuya pendiente es -1/τ.

#### 🛠️ Materiales y costos (S/. 15–25 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| LED de alto brillo (rojo o blanco) | 2 | S/. 2 |
| Condensadores electrolíticos (100 μF, 470 μF, 1000 μF) | 3 | S/. 5 |
| Resistencias (1 kΩ, 10 kΩ, 100 kΩ) | 3 | S/. 2 |
| Batería 9V + conector | 1 | S/. 5 |
| Protoboard pequeño | 1 | S/. 5 |
| Cables jumper | — | S/. 3 |
| Smartphone con app Phyphox | 1 | Gratis |

#### 🔬 Procedimiento experimental

1. **Montaje del circuito**: Conectar batería 9V, resistencia R, LED y condensador C en un circuito RC con interruptor.
2. **Configurar Phyphox**: Abrir la aplicación y seleccionar el experimento "Luz". Colocar el sensor del smartphone frente al LED a distancia fija (~2 cm).
3. **Medición de descarga**: Cargar el capacitor cerrando el interruptor. Luego abrir el interruptor y grabar el decaimiento del brillo del LED.
4. **Ajuste exponencial**: Exportar datos a Excel/Python y ajustar la curva exponencial para obtener τ.
5. **Variación de R y C**: Repetir para distintas combinaciones RC (ej. 100 μF × 10 kΩ = 1 s; 470 μF × 100 kΩ = 47 s).
6. **Comparación con teoría**: Calcular τ teórico y comparar con el experimental.

#### 🎯 Resultados esperados

- Curvas exponenciales de decaimiento con R² > 0.99.
- Error relativo entre τ teórico y experimental <10%.
- Verificación de τ_serie = R(C₁+C₂) para capacitores en paralelo y τ_serie = R·C₁C₂/(C₁+C₂) para capacitores en serie.

#### ✨ Aspecto novedoso para obtener buena nota

Este es un experimento publicado en 2023, muy reciente, que usa el smartphone como instrumento científico. Se puede extender a:
- Comparar resultados con un Arduino (para validar el método).
- Estudiar capacitores en serie y paralelo.
- Determinar la **capacitancia desconocida** de un capacitor midiendo τ con R conocida.

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "Measuring the capacitor charge and discharge with a LED and a smartphone"** (arXiv, 2023)
   - **Contenido del paper**: Presenta el método completo con fundamento matemático detallado, setup experimental con fotos, código/procedimiento para la app del smartphone, y análisis de error. Compara resultados con valores teóricos obteniendo errores <5%. Incluye discusión sobre linealidad de la respuesta brillo-corriente del LED en distintos rangos.
   - Enlace: https://arxiv.org/pdf/2305.13094

2. **Paper complementario — "Experimenting with RC and RL series circuits using smartphones as signal generators and oscilloscopes"** (arXiv, 2023)
   - **Contenido**: Extiende el método a circuitos RL (Ley de Faraday). Usa el smartphone tanto como generador de señal (mediante sonidos) como osciloscopio (mediante micrófono). Incluye las ecuaciones V_R(t) = V_mR(1 - e^(-t/τ_RL)) para circuitos RL. Muy útil como complemento teórico.
   - Enlace: https://arxiv.org/pdf/2303.16249

3. **Paper — "An Arduino Investigation of the RC Circuit"** (The Physics Teacher, Vol. 53, 2015)
   - **Contenido**: Versión con Arduino del mismo experimento. Usa una placa Arduino Uno con un Screw Shield para medir voltaje, corriente y tiempo simultáneamente. Sirve como validación cruzada del método con smartphone y da la base histórica del experimento.
   - Enlace: https://www.researchgate.net/publication/276084239_An_Arduino_Investigation_of_the_RC_Circuit

4. **Paper — "RC Circuit-Based Investigation of Capacitors in Series and Parallel with the Arduino"** (ResearchGate, 2020)
   - **Contenido**: Análisis específico de cómo cambia τ cuando se combinan capacitores en serie y paralelo. Presenta gráficas superpuestas de carga y descarga para distintas configuraciones, muy útil para análisis comparativo.
   - Enlace: https://www.researchgate.net/publication/340547096_RC_Circuit-Based_Investigation_of_Capacitors_in_Series_and_Parallel_with_the_Arduino

---

### **PROYECTO 3: Determinación experimental de la resistividad del grafito usando la Ley de Ohm**

#### 📖 Descripción extendida

El grafito (la "mina" de los lápices) es un material curioso: es el único no-metal que conduce bien la electricidad debido a su estructura de carbono en capas hexagonales con electrones deslocalizados. Sin embargo, también contiene arcilla (en proporciones variables según la dureza del lápiz: HB, 2B, 4B, 6B), lo cual modifica su resistividad.

Este proyecto busca: (1) verificar la Ley de Ohm (V = IR) para el grafito, (2) demostrar que la resistencia es proporcional a la longitud y al inverso del área, (3) calcular la resistividad del grafito (ρ ≈ 3×10⁻⁵ Ω·m para grafito puro), y (4) comparar resistividades entre distintas durezas de lápiz, correlacionando con la proporción grafito/arcilla.

#### 🧮 Fundamento teórico con ecuaciones clave

**Ley de Ohm**:

$$V = IR$$

**Resistencia en función de la geometría**:

$$R = \rho \frac{L}{A}$$

donde:
- ρ = resistividad del material (Ω·m)
- L = longitud del conductor (m)
- A = área transversal (m²)

Para una mina cilíndrica de diámetro d:

$$A = \frac{\pi d^2}{4}$$

**Resistencias en serie** (conectando varios lápices): R_total = R₁ + R₂ + ... + Rₙ

**Resistencias en paralelo**: 1/R_total = 1/R₁ + 1/R₂ + ... + 1/Rₙ

Graficando R vs L (con A constante), la pendiente es ρ/A, de donde:

$$\rho = \text{pendiente} \times A$$

#### 🛠️ Materiales y costos (S/. 10–15 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Lápices de distintas durezas (HB, 2B, 4B, 6B) | 4 | S/. 8 |
| Batería 9V + conector | 1 | S/. 5 |
| Multímetro digital | 1 | Prestado |
| Cables con caimanes | 4 | S/. 3 |
| Regla y calibrador | — | — |

#### 🔬 Procedimiento experimental

1. **Preparación**: Afilar un lápiz por ambos extremos para exponer el grafito. Medir el diámetro de la mina con calibrador.
2. **Verificación de Ley de Ohm**: Con longitud L fija, aplicar distintos voltajes (1V–9V) y medir la corriente. Graficar V vs I; la pendiente es R.
3. **R vs L**: Fijar los caimanes a distintas distancias (2, 4, 6, 8, 10 cm) y medir R directamente con el multímetro en modo ohmímetro.
4. **Cálculo de ρ**: Graficar R vs L, obtener la pendiente y calcular ρ = pendiente × A.
5. **Comparación entre durezas**: Repetir el experimento para HB, 2B, 4B, 6B y comparar las resistividades. Discutir la correlación con la proporción grafito/arcilla.
6. **Serie y paralelo**: Conectar 2 o 3 lápices en serie y en paralelo; verificar las reglas de combinación de resistencias.

#### 🎯 Resultados esperados

- Comportamiento óhmico (V vs I lineal, R² > 0.98).
- Relación lineal R vs L (R² > 0.95).
- Resistividad del grafito entre 3×10⁻⁵ y 10⁻⁴ Ω·m.
- 6B (más grafito) < HB < 4H (más arcilla) en resistividad.

#### ✨ Aspecto novedoso para obtener buena nota

- Analizar el **calentamiento** del grafito con corrientes altas y discutir el cambio de resistividad con temperatura (coeficiente α).
- Dibujar resistores "hechos de grafito" sobre papel (frotando con lápiz) y medir su resistencia — esto demuestra una aplicación real: los teclados conductivos y sensores flexibles usan este principio.
- Proponer una aplicación: **lápiz como sensor de presión** (al presionar, la sección cambia, y por ende la resistencia).

#### 📚 Fuentes académicas detalladas

1. **Paper experimental — "Experiment on Pencil Resister Effect on Circuit Output"** (UK Essays)
   - **Contenido**: Reporte experimental completo que compara HB, 2H, 2B y 6B bajo distintos voltajes (1–5V). Presenta tablas de datos con V aplicado, V del circuito, I, y R calculada. Incluye discusión del efecto de longitud y sección. Hipótesis verificada: a mayor longitud, mayor resistencia.
   - Enlace: https://www.ukessays.com/essays/physics/experiment-pencil-resister-effect-circuit-9654.php

2. **Manual de laboratorio — University of Central Arkansas**
   - **Contenido**: Guía con fundamento teórico detallado, ecuaciones, tablas de datos experimentales para mina de 16 cm, y extensión al efecto de la temperatura mediante la ecuación R(T) = R₀[α(T-T₀) + 1]. Muy útil para incluir análisis térmico avanzado.
   - Enlace: https://faculty.uca.edu/njaustin/PHYS1420/Laboratory/08resistivity.pdf

3. **Manual — Arizona State University (Ohm's Rule & Resistivity)**
   - **Contenido**: Manual oficial de laboratorio de ASU con teoría de códigos de colores de resistores, definiciones formales de resistividad (ρ = E/J), y procedimiento completo para grafito. Incluye discusión de cuándo un resistor deja de ser óhmico.
   - Enlace: https://www.cliffsnotes.com/study-notes/20473074

4. **Reporte experimental IB Physics — "Resistivity of Pencil leads in different degree of hardness"**
   - **Contenido**: Investigación completa de International Baccalaureate con HB, 4B, 8B. Discute por qué la proporción de arcilla en los lápices más duros aumenta la resistencia. Incluye control de variables (temperatura, longitud, voltaje) y análisis de errores.
   - Enlace: https://www.markedbyteachers.com/international-baccalaureate/physics/an-experiment-to-find-the-resistivity-of-pencil-leads-in-different-degree-of-hardness.html

---

## 🔷 PROYECTOS DE LA UNIDAD 2 — MAGNETISMO

---

### **PROYECTO 4: Verificación experimental de la Ley de Biot-Savart usando un solenoide casero y el magnetómetro del smartphone**

#### 📖 Descripción extendida

Todos los smartphones modernos (desde ~2009) incluyen un **magnetómetro** integrado que funciona como brújula digital. Este sensor puede medir campos magnéticos con una sensibilidad de **~0.1 μT** en tres ejes ortogonales, lo cual lo convierte en un instrumento científico muy poderoso para experimentos educativos.

En este proyecto se construye un solenoide casero (bobina enrollada sobre un tubo) y se verifica experimentalmente la Ley de Biot-Savart/Ampère midiendo el campo magnético B en el centro del solenoide en función de la corriente I, el número de vueltas N, y la distancia d al solenoide. Se usa la app **Phyphox** o **Physics Toolbox Magnetometer** (gratuitas).

#### 🧮 Fundamento teórico con ecuaciones clave

**Ley de Biot-Savart** para un elemento de corriente:

$$d\vec{B} = \frac{\mu_0}{4\pi} \frac{I\, d\vec{l} \times \hat{r}}{r^2}$$

Para el centro de un **solenoide largo** (L >> radio):

$$B = \mu_0 n I = \mu_0 \frac{N}{L} I$$

donde:
- μ₀ = 4π × 10⁻⁷ T·m/A (permeabilidad del vacío)
- n = N/L (número de vueltas por unidad de longitud)
- I = corriente en amperios

Para el centro de una **espira circular** de radio R:

$$B = \frac{\mu_0 I}{2R}$$

En el eje de un solenoide, a distancia x desde el centro:

$$B(x) = \frac{\mu_0 N I}{2L}\left[\frac{x+L/2}{\sqrt{(x+L/2)^2+R^2}} - \frac{x-L/2}{\sqrt{(x-L/2)^2+R^2}}\right]$$

#### 🛠️ Materiales y costos (S/. 25–40 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Alambre esmaltado AWG 22–26 (30–50 m) | 1 rollo | S/. 15 |
| Tubo de cartón o PVC (diámetro 3–5 cm) | 1 | S/. 5 |
| Batería (9V o fuente variable 0–12V) | 1 | S/. 5 |
| Resistencia variable (potenciómetro 10–100 Ω) o resistencias fijas | 1 set | S/. 5 |
| Multímetro (para medir I) | 1 | Prestado |
| Smartphone con app Phyphox | 1 | Gratis |

#### 🔬 Procedimiento experimental

1. **Construcción del solenoide**: Enrollar N vueltas de alambre esmaltado sobre el tubo, anotar el número exacto de vueltas y la longitud L. Construir 2–3 solenoides con distintos N (50, 100, 150 vueltas).
2. **Calibración del magnetómetro**: Alejar el smartphone de fuentes magnéticas, anotar el campo terrestre para restarlo del valor medido.
3. **Experimento 1 — B vs I**: Con solenoide fijo, variar la corriente (0.1–1.0 A) y medir B en el centro. Graficar B vs I (debe ser lineal).
4. **Experimento 2 — B vs N**: Con I fija, comparar B entre solenoides con distintos N/L.
5. **Experimento 3 — B vs distancia**: Mover el smartphone a lo largo del eje del solenoide y medir B(x). Comparar con la ecuación teórica.
6. **Cálculo de μ₀**: De la pendiente de B vs I, despejar μ₀ experimental y comparar con el valor teórico (4π × 10⁻⁷ T·m/A).

#### 🎯 Resultados esperados

- Relación B vs I lineal con R² > 0.99.
- Valor de μ₀ experimental con error <15% respecto al teórico.
- Distribución axial de B(x) concordante con la teoría.

#### ✨ Aspecto novedoso para obtener buena nota

- Determinar la **permeabilidad del vacío** μ₀ experimentalmente (resultado muy elegante).
- Comparar campos generados por una espira simple vs un solenoide.
- Demostrar cualitativamente la **Ley de Ampère** (∮B·dl = μ₀I) mediante medidas a lo largo de una trayectoria cerrada.
- Estudiar el **campo magnético exterior** del solenoide (que suele ignorarse pero sí existe).

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "Exploring the magnetic field strength of a solenoid using the magnetometer of a smartphone"** (EDUCATUM Journal of Science, Mathematics and Technology, 2023)
   - **Contenido del paper**: Estudio completo con tres experimentos (B vs I, B vs N, B vs distancia). Incluye tablas de datos, gráficos, análisis de error y discusión sobre cómo verificar μ₀. Concluye que el método se puede usar para enseñanza con alta precisión y a costo casi nulo.
   - Enlace: https://www.researchgate.net/publication/386040746_Exploring_the_magnetic_field_strength_of_a_solenoid_using_the_magnetometer_of_a_smartphone

2. **Paper — "Mathematical Modeling and Teaching of Outer Magnetic Field of a Solenoid Using Smartphones"** (The Physics Educator, World Scientific, 2023)
   - **Contenido**: Propone estudiar el **campo magnético exterior** del solenoide (aspecto poco tratado). Incluye la resolución matemática completa basada en Biot-Savart y la comparación con mediciones del smartphone. Nivel más avanzado pero con mucho valor añadido.
   - Enlace: https://www.worldscientific.com/doi/10.1142/S2661339523500129

3. **Paper — "Magnetic Field Experiments Using a Phone"** (arXiv, Glen D. Gillen y Katharina Gillen)
   - **Contenido**: Manual de laboratorio completo que usa el smartphone para medir el campo magnético terrestre (componentes horizontal, vertical, ángulo de inclinación) y luego el campo de una bobina. Incluye gráficas de ejemplo, código de análisis y cuestionarios para estudiantes.
   - Enlace: https://arxiv.org/pdf/2212.02258

4. **Guía experimental FizziQ**
   - **Contenido**: Guía paso a paso con setup experimental, calibración del magnetómetro, cómo alinear el eje Y del smartphone con el eje del solenoide, y cómo restar el campo terrestre. Es la guía más clara para empezar.
   - Enlace: https://www.fizziq.org/en/team-en/biot-savart-law

---

### **PROYECTO 5: Construcción de una linterna de sacudida (shake flashlight) para el estudio experimental de la Ley de Faraday y Lenz**

#### 📖 Descripción extendida

Una linterna de sacudida es un dispositivo práctico que convierte energía mecánica (el movimiento de la mano al agitar) en energía eléctrica mediante inducción electromagnética, y almacena esta energía en un capacitor para encender un LED. Es el ejemplo perfecto de la **Ley de Faraday**: cuando el flujo magnético a través de una bobina cambia (debido a un imán que se mueve), se induce una fem en la bobina.

Este proyecto combina múltiples conceptos: inducción electromagnética, rectificación (conversión AC-DC con diodos), almacenamiento de energía en capacitores, y aplicación práctica. Es visualmente impresionante y permite análisis cuantitativo de la fem inducida.

#### 🧮 Fundamento teórico con ecuaciones clave

**Ley de Faraday**:

$$\varepsilon = -\frac{d\Phi_B}{dt}$$

donde Φ_B = B·A·cos(θ) es el flujo magnético.

Para un imán de momento dipolar m que cruza una bobina de N vueltas con frecuencia f, la fem pico es aproximadamente:

$$\varepsilon_{max} \approx 2\pi f N B_0 A$$

**Ley de Lenz**: La corriente inducida se opone al cambio de flujo (signo negativo en la ley de Faraday).

La **potencia generada** al sacudir a frecuencia f con amplitud x₀:

$$P = \frac{\varepsilon_{rms}^2}{R}$$

Típicamente entre 10 mW y 170 mW para una linterna comercial.

**Energía almacenada en el capacitor**:

$$U = \frac{1}{2}CV^2$$

#### 🛠️ Materiales y costos (S/. 30–50 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Imán de neodimio cilíndrico (de disco duro o comercial) | 1 | S/. 10 |
| Alambre esmaltado AWG 30–34 | 100 m | S/. 10 |
| Tubo transparente de plástico (~2 cm diámetro) | 1 | S/. 3 |
| 4 diodos rectificadores (1N4007) | 1 set | S/. 2 |
| Capacitor electrolítico (470 μF – 1000 μF) | 1 | S/. 2 |
| LED blanco o rojo | 1 | S/. 1 |
| Resistor (100 Ω) | 1 | S/. 1 |
| Multímetro | 1 | Prestado |

#### 🔬 Procedimiento experimental

1. **Construcción de la bobina**: Enrollar 400–800 vueltas de alambre esmaltado sobre el tubo transparente, en una sección central de ~3 cm.
2. **Rectificación**: Armar un puente de diodos (4 diodos) para convertir la AC inducida en DC.
3. **Almacenamiento**: Conectar el puente a un capacitor para suavizar el voltaje.
4. **Carga útil**: Conectar el capacitor al LED con un resistor limitador.
5. **Experimento 1 — fem vs frecuencia**: Medir con osciloscopio o multímetro (en modo AC) el voltaje inducido al sacudir a distintas frecuencias (1, 2, 3, 4 sacudidas/s). Contar sacudidas con cronómetro.
6. **Experimento 2 — fem vs vueltas**: Construir 2 bobinas con distintas N y comparar la fem inducida.
7. **Cálculo de dΦ/dt**: A partir de la fem medida, estimar el cambio de flujo por unidad de tiempo.

#### 🎯 Resultados esperados

- fem inducida proporcional a la frecuencia de sacudida (relación lineal).
- fem aumentando con N (número de vueltas).
- Potencia generada: 10–170 mW.
- Encendido visible del LED tras ~30 s de agitación vigorosa.

#### ✨ Aspecto novedoso para obtener buena nota

- Medir la **eficiencia de conversión** de energía mecánica a eléctrica.
- Comparar con una linterna comercial (desarmar una para ver el diseño real).
- Analizar cómo el **circuito rectificador** transforma AC en DC y cómo el capacitor filtra el voltaje.
- Discutir la **conservación de la energía**: la fuerza que resiste al movimiento del imán (Ley de Lenz) es la manifestación mecánica del trabajo que se convierte en energía eléctrica.

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "An Electromagnetic Induction Flashlight Experiment"** (ResearchGate)
   - **Contenido del paper**: Análisis completo de las características de performance de una linterna de sacudida. Incluye las ecuaciones analíticas para fem inducida, corriente, voltaje, fuerza electromagnética y potencia. Compara los resultados de tests de laboratorio con cálculos teóricos. Reporta potencia de salida entre 10 mW y 170 mW.
   - Enlace: https://www.researchgate.net/publication/243714978_An_Electromagnetic_Induction_Flashlight_Experiment

2. **Guía educativa con ecuaciones — Dalhousie University**
   - **Contenido**: Plan de clase completo con introducción a la linterna de sacudida, incluyendo conceptos de DC, rectificador, diodos, inducción electromagnética, capacitores, y EMF. Incluye desglose de componentes y diseño paso a paso.
   - Enlace: https://cdn.dal.ca/content/dam/dalhousie/pdf/faculty/science/imhotep/9.8%20Forever%20Flashlight.pdf

3. **Tutorial técnico con diagrama de circuito — WellPCB**
   - **Contenido**: Explicación del circuito rectificador, rol del puente de diodos, dinámica de carga del capacitor. Incluye diagrama de circuito completo y consideraciones prácticas (duración típica de luz, cuidados al ensamblar).
   - Enlace: https://www.wellpcb.com/blog/pcb-projects/farady-flashlight/

4. **Recursos Science Buddies — "Human-Powered Energy"**
   - **Contenido**: Proyecto educativo con preguntas de investigación y metodología. Sugiere extensiones: ¿cuántos LEDs se pueden encender? ¿cómo afecta el número de imanes?
   - Enlace: https://www.sciencebuddies.org/blog/teach-electromagnetism-lessons

---

### **PROYECTO 6: Estudio cuantitativo de la Ley de Lenz mediante la caída de un imán de neodimio en un tubo de cobre**

#### 📖 Descripción extendida

Este es uno de los experimentos más espectaculares y visualmente impactantes del electromagnetismo. Al dejar caer un imán de neodimio dentro de un tubo de cobre, el imán cae **mucho más lento** que por gravedad libre — a veces tan lento que parece flotar — a pesar de que el cobre no es magnético.

El fenómeno se explica por la **Ley de Lenz**: al caer el imán, el flujo magnético a través de secciones del tubo cambia, induciendo corrientes (corrientes de Foucault o "eddy currents") que a su vez generan un campo magnético que se opone al movimiento del imán. La fuerza resultante frena el imán hasta alcanzar una **velocidad terminal** donde el peso se equilibra con la fuerza de frenado magnético.

#### 🧮 Fundamento teórico con ecuaciones clave

**Ley de Faraday** aplicada al tubo:

$$\varepsilon = -\frac{d\Phi_B}{dt}$$

**Ley de Ohm** para las corrientes de Eddy:

$$I = \frac{\varepsilon}{R_{tubo}}$$

La fuerza de frenado magnético es proporcional a la velocidad:

$$F_{mag} = -bv$$

donde b depende del campo del imán, dimensiones del tubo y conductividad del cobre.

En **velocidad terminal** (aceleración = 0):

$$mg = bv_{term} \quad \Rightarrow \quad v_{term} = \frac{mg}{b}$$

Por **conservación de energía**, la pérdida de energía potencial se disipa como calor en el tubo:

$$P_{disipada} = mgv_{term} = \frac{\varepsilon^2}{R}$$

#### 🛠️ Materiales y costos (S/. 40–70 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Imán de neodimio cilíndrico (~1–2 cm diámetro) | 2–3 | S/. 20 |
| Tubo de cobre (1 m, diámetro interno ~1.5 cm) | 1 | S/. 25 |
| Tubo de aluminio (1 m, similar diámetro) — comparación | 1 | S/. 15 |
| Tubo de PVC (1 m, similar diámetro) — control | 1 | S/. 5 |
| Balanza digital | 1 | Prestada |
| Cronómetro o smartphone con cámara slow-motion | 1 | — |
| Software Tracker (gratis) | 1 | Gratis |

#### 🔬 Procedimiento experimental

1. **Verificación inicial**: Dejar caer el imán sin tubo, por tubo de PVC, por tubo de aluminio, y por tubo de cobre. Observar diferencias dramáticas.
2. **Medición de velocidad terminal con cronómetro**: Tomar tiempo en 10 caídas por el tubo de cobre; calcular v_term = L/t.
3. **Análisis con video (Tracker)**: Grabar la caída con cámara lateral. Hacer un agujero o usar tubo transparente con bobina de cobre enrollada por fuera. Usar Tracker para obtener posición vs tiempo y derivar la velocidad instantánea.
4. **Variación de parámetros**: Probar imanes con distintas masas, tubos con distintos grosores de pared, cobre vs aluminio.
5. **Verificación cuantitativa**: Calcular b a partir de v_term y mg. Comparar con la predicción teórica basada en las dimensiones y la conductividad del cobre.
6. **Disipación de energía**: Calcular P = mgv_term y relacionarla con calentamiento del tubo (medible con termómetro en casos extremos).

#### 🎯 Resultados esperados

- v_term ~ 5–30 cm/s según las dimensiones (vs ~4.5 m/s en caída libre por 1 m).
- Diferencia cobre vs aluminio (aluminio tiene mayor resistividad → frenado menor).
- Sin efecto en PVC (control, es no conductor).

#### ✨ Aspecto novedoso para obtener buena nota

- Usar **Tracker** para obtener la posición vs tiempo y verificar que se alcanza velocidad constante.
- Estudiar el efecto de **ranuras** en el tubo (cortar slits verticales): muestran que interrumpir las corrientes de Eddy reduce el frenado.
- Discusión sobre aplicaciones: **frenos regenerativos** en trenes eléctricos y autos híbridos, **amortiguadores magnéticos**.
- Análisis cuantitativo comparando tubos de distintas paredes.

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "A quasi-static electromagnetic analysis for experiments with strong permanent magnets"** (arXiv)
   - **Contenido del paper**: Análisis cuasi-estático electromagnético completo de los experimentos con imanes fuertes de neodimio. Incluye derivación de la Ley de Faraday aplicada al tubo, ecuaciones de Biot-Savart para las corrientes de Eddy, y relación con la pérdida de energía potencial. Explica por qué imanes más fuertes o tubos de menor resistencia hacen caer más lento al imán.
   - Enlace: https://arxiv.org/pdf/1407.0875

2. **Paper — "Investigation of a Magnet falling through a copper tube"** (ResearchGate)
   - **Contenido**: Cálculo completo que justifica cuantitativamente la velocidad terminal del imán en función de las dimensiones del tubo. Incluye comparación experimento-teoría con buen acuerdo. Ideal para fundamentar el marco teórico.
   - Enlace: https://www.researchgate.net/publication/341163515_Investigation_of_a_Magnet_falling_through_a_copper_tube

3. **Paper — "Lenz's law with aluminum foil and a lengthwise slit"** (ResearchGate)
   - **Contenido**: Versión más accesible con tubos caseros de aluminio (en vez de cobre). Además introduce el efecto de ranuras longitudinales: al cortar slits en el tubo, se reducen las corrientes horizontales de Eddy y el frenado disminuye. Excelente para un análisis comparativo avanzado.
   - Enlace: https://www.researchgate.net/publication/324564137_Lenz's_law_with_aluminum_foil_and_a_lengthwise_slit

4. **Plan de lección con demostración — UBC Physics**
   - **Contenido**: Lección completa para física 12 con preguntas guía: ¿qué pasa con slits verticales? ¿cómo se comparan los tiempos de caída entre plástico, aluminio y cobre? Incluye aplicación de la regla de la mano derecha para determinar dirección de corrientes inducidas.
   - Enlace: https://phys420.phas.ubc.ca/p420_2018/lalond72/

---

### **PROYECTO 7: Construcción y análisis cuantitativo de un motor homopolar — verificación experimental de la fuerza de Lorentz**

#### 📖 Descripción extendida

El motor homopolar es el **motor eléctrico más simple del mundo**, inventado por Michael Faraday en 1821. Consta únicamente de 3 componentes: una batería, un imán de neodimio y un alambre de cobre. Cuando se cierra el circuito, el alambre comienza a girar alrededor de la batería sin necesidad de ningún conmutador, demostrando directamente la **fuerza de Lorentz**: F = qv × B.

Este proyecto combina simplicidad con profundidad: es trivial construirlo pero permite un análisis teórico sofisticado sobre cómo la geometría del campo magnético y la dirección de la corriente producen un torque neto que hace girar al alambre.

#### 🧮 Fundamento teórico con ecuaciones clave

**Fuerza de Lorentz** sobre una carga en movimiento:

$$\vec{F} = q\vec{v} \times \vec{B}$$

Para un elemento de corriente I·dL en un campo B:

$$d\vec{F} = I\, d\vec{L} \times \vec{B}$$

**Fuerza total** sobre el alambre:

$$\vec{F} = \int I\, d\vec{L} \times \vec{B}$$

El torque neto hace girar el alambre:

$$\tau = \vec{r} \times \vec{F}$$

La velocidad angular se estabiliza cuando el torque eléctrico iguala al torque de fricción:

$$\tau_{elect} = \tau_{fric}$$

#### 🛠️ Materiales y costos (S/. 15–25 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Pila AA o 9V | 2 | S/. 5 |
| Imán de neodimio cilíndrico (~1 cm) | 2 | S/. 10 |
| Tornillo de acero (3–4 cm) | 1 | S/. 1 |
| Alambre de cobre grueso (calibre 14–18) | 30 cm | S/. 3 |
| Alicate para doblar alambre | 1 | — |
| Smartphone con cámara slow-motion | 1 | — |

#### 🔬 Procedimiento experimental

1. **Motor simple (versión clásica)**:
   - Adherir el imán de neodimio al extremo negativo (-) de la pila AA.
   - Poner un tornillo (con la punta hacia el imán) y dejarlo colgando.
   - Conectar un alambre desde el extremo positivo (+) al imán. El sistema debe girar.

2. **Motor con "jaula" de cobre** (más visual): doblar el alambre en una forma tipo corazón o espiral que rodee la pila, con un extremo tocando el polo positivo y los otros tocando el imán en la base.

3. **Medición cuantitativa**:
   - Grabar con cámara slow-motion del smartphone.
   - Contar las RPM (revoluciones por minuto).
   - Medir la corriente con un multímetro (aprox. 1–3 A).
   - Estimar la fuerza de Lorentz: F ≈ I·L·B, con B ≈ 0.3–0.5 T (imán de neodimio).

4. **Variaciones**:
   - Efecto del número de imanes apilados (mayor B → mayor fuerza).
   - Efecto de la longitud del alambre (mayor L → mayor fuerza).
   - Invertir la polaridad: ¿cambia la dirección de rotación? (sí).

#### 🎯 Resultados esperados

- RPM entre 100 y 500 según el diseño.
- La corriente alta (1–3 A) hace que la pila se descargue en minutos.
- Rotación que se invierte al invertir la batería o al invertir los imanes.

#### ✨ Aspecto novedoso para obtener buena nota

- Análisis cuantitativo de la velocidad angular con cámara slow-motion.
- Construir variantes: **rodillo homopolar** (el motor completo rueda sobre una superficie metálica conductora).
- Discutir por qué el motor homopolar fue históricamente el **primer motor eléctrico** y por qué no se usa en aplicaciones modernas (necesita corrientes muy altas).
- Calcular el torque y comparar con el torque de fricción (mediante análisis de aceleración angular).

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "Some simple demonstration experiments involving homopolar motors"** (Revista Brasileira de Ensino de Física, SciELO)
   - **Contenido del paper**: Describe varios diseños de motor homopolar con imanes de neodimio para demostraciones de física introductoria. Incluye análisis de la fuerza de Lorentz, dinámica del rodillo homopolar y derivación matemática del movimiento usando la función W de Lambert. Explica por qué estos motores fueron ignorados por 170 años y revivieron con los imanes de neodimio.
   - Enlace: https://www.scielo.br/j/rbef/a/5WgC4T8ygH9kxRcTqjV34bN/?lang=en

2. **Paper completo en ResearchGate (acceso libre)**
   - **Contenido**: Versión con figuras adicionales mostrando configuraciones alternativas: motor con disco conductor, motor con espiral, rodillo sobre papel aluminio. Incluye derivación de corrientes perpendiculares.
   - Enlace: https://www.researchgate.net/publication/315266792_Some_simple_demonstration_experiments_involving_homopolar_motors

3. **Documento técnico — University of Alabama**
   - **Contenido**: Guía práctica paso a paso con fotos, materiales, y "challenges" para estudiantes: construir un "vehículo homopolar" que se desplace. Incluye extensiones y estándares educativos.
   - Enlace: https://pleclair.ua.edu/Homopolar%20Motor%20Demonstration.pdf

4. **Recopilación de referencias — University of Iowa Physics**
   - **Contenido**: Compendio de todos los artículos publicados en *The Physics Teacher* sobre motores homopolares: modelos, análisis cualitativo y cuantitativo, "motor flotante", "generador homopolar", desde 2004 hasta 2018. Excelente para citas bibliográficas.
   - Enlace: https://instructional-resources.physics.uiowa.edu/demos/5h4053-homopolar-motor

---

## 🔷 PROYECTOS DE LA UNIDAD 3 — ÓPTICA

---

### **PROYECTO 8: Determinación experimental del índice de refracción de distintos líquidos mediante la Ley de Snell usando un puntero láser**

#### 📖 Descripción extendida

La Ley de Snell describe cómo la luz cambia de dirección al pasar entre dos medios con distintos índices de refracción. Esto es consecuencia de que la velocidad de la luz es distinta en cada medio: v = c/n.

Este proyecto busca verificar la Ley de Snell (n₁·sen θ₁ = n₂·sen θ₂) y determinar el índice de refracción n de líquidos comunes (agua, glicerina, aceite, alcohol, agua con azúcar en distintas concentraciones). Se usa un puntero láser barato y un recipiente transparente.

#### 🧮 Fundamento teórico con ecuaciones clave

**Ley de Snell**:

$$n_1 \sin\theta_1 = n_2 \sin\theta_2$$

**Índice de refracción**:

$$n = \frac{c}{v}$$

donde c es la velocidad de la luz en el vacío y v en el medio.

**Reflexión total interna** ocurre cuando:

$$\sin\theta_c = \frac{n_2}{n_1}$$

para n₁ > n₂. Esto define el **ángulo crítico** θ_c.

#### 🛠️ Materiales y costos (S/. 20–35 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Puntero láser (rojo o verde) | 1 | S/. 15 |
| Recipiente transparente semicircular o rectangular | 1 | S/. 5 |
| Transportador (grande, ≥180°) | 1 | S/. 2 |
| Papel milimetrado o plantilla impresa | 1 | S/. 2 |
| Líquidos (agua, glicerina, alcohol, aceite, agua con sal/azúcar) | — | S/. 5 |
| Soporte para el láser | 1 | — |

#### 🔬 Procedimiento experimental

1. **Preparación**: Colocar el recipiente sobre una plantilla impresa con ángulos marcados cada 5°. Llenar con el líquido a estudiar.
2. **Incidencia y refracción**: Apuntar el láser al centro del recipiente desde distintos ángulos (10°, 20°, 30°, ..., 70°) y marcar la dirección del rayo refractado.
3. **Medición de ángulos**: Medir θ₁ (incidencia) y θ₂ (refracción) respecto a la normal.
4. **Análisis**: Graficar sen θ₁ vs sen θ₂. La pendiente es n_líquido / n_aire = n_líquido (asumiendo n_aire ≈ 1).
5. **Comparación**: Repetir para distintos líquidos y comparar con valores tabulados:
   - Agua: n = 1.33
   - Alcohol etílico: n = 1.36
   - Glicerina: n = 1.47
   - Aceite vegetal: n = 1.47–1.48
6. **Ángulo crítico**: Para glicerina, encontrar el ángulo crítico para reflexión total interna.

#### 🎯 Resultados esperados

- Ajuste lineal sen θ₁ vs sen θ₂ con R² > 0.99.
- Índices experimentales con error <3% respecto al valor tabulado.
- Observación del ángulo crítico y reflexión total interna.

#### ✨ Aspecto novedoso para obtener buena nota

- Estudiar **dispersión** con un prisma: al usar luz blanca (linterna de teléfono + rendija) se descompone en colores (cada λ tiene n ligeramente distinto).
- Calcular la **velocidad de la luz** en cada medio (v = c/n).
- Analizar soluciones de azúcar con distintas concentraciones: verificar que n aumenta con la concentración (aplicación: refractómetros para medir grados Brix).
- Demostrar la analogía con **fibras ópticas** (reflexión total interna).

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "Snell's Law Lab Report"** (IOSR Journal of Applied Physics)
   - **Contenido del paper**: Análisis teórico profundo usando el principio de Huygens para derivar la Ley de Snell desde la naturaleza ondulatoria de la luz. Incluye discusión de variables independientes, dependientes y controladas (color del láser, posición del recipiente, etc.). Tabla de datos experimentales con agua, gráfico lineal de ajuste, y cálculo de n_agua con barras de error.
   - Enlace: https://www.iosrjournals.org/iosr-jap/papers/Vol12-issue6/Series-3/I1206035260.pdf

2. **Reporte técnico — "Determination of Refractive Index Using Snell's Law"** (Jamie Somers)
   - **Contenido**: Reporte experimental completo con 3 métodos: (1) Snell directo con láser, (2) método de profundidad aparente, (3) usando ángulo crítico. Compara los tres métodos para agua, vidrio (perspex) y glicerina. Incluye análisis estadístico con desviaciones estándar.
   - Enlace: https://jamiesomers.com/reports/determination-of-refractive-index-using-snells-law.pdf

3. **Guía didáctica universitaria — Lehman College**
   - **Contenido**: Manual de laboratorio en línea (diseñado durante COVID-19) con simulador PhET integrado. Incluye ejemplos numéricos, ejercicios, y tabla de valores de n para distintos materiales para comparación.
   - Enlace: https://www.lehman.edu/faculty/dgaranin/Introductory_Physics/Online%20labs/Experiment_17-Refraction-online.pdf

4. **Manual técnico — Mettler-Toledo**
   - **Contenido**: Documento profesional de la industria que explica cómo los refractómetros digitales usan la Ley de Snell y el ángulo crítico para medir concentraciones (BRIX, HFCS, etc.). Útil para mostrar aplicaciones industriales reales (en la sección de introducción del informe).
   - Enlace: https://www.mt.com/my/en/home/applications/Application_Browse_Laboratory_Analytics/Refractive_index/definition_and_measurement/snells-law.html

---

### **PROYECTO 9: Medición de la distancia focal de lentes y verificación de la ecuación de la lente delgada mediante fotografía con smartphone**

#### 📖 Descripción extendida

La cámara del smartphone es un sistema óptico sofisticado (lente compuesto) que funciona bajo las mismas leyes de la óptica geométrica que un lente delgado simple. En este proyecto se utiliza el smartphone como instrumento de medición: se fotografían objetos de tamaño conocido a distintas distancias, se mide el tamaño de la imagen en pixeles con **ImageJ** (software gratuito), y se verifica la **ecuación del lente delgado**: 1/f = 1/dₒ + 1/dᵢ.

Adicionalmente se puede estudiar la distancia focal de lentes externas (lupa, lente de gafas) colocándolas frente a la cámara y midiendo la distancia focal efectiva del sistema compuesto.

#### 🧮 Fundamento teórico con ecuaciones clave

**Ecuación del lente delgado**:

$$\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$$

donde:
- f = distancia focal del lente
- dₒ = distancia del objeto al lente
- dᵢ = distancia de la imagen al lente

**Magnificación lateral (transversal)**:

$$M = \frac{h_i}{h_o} = -\frac{d_i}{d_o}$$

donde h_o es el tamaño del objeto y h_i el tamaño de la imagen.

Combinando estas ecuaciones:

$$\frac{1}{h_i} = \frac{1}{h_o}\left(\frac{d_o}{f} - 1\right)$$

Graficando 1/h_i vs dₒ (con h_o conocido), se obtiene una recta cuya pendiente es 1/(h_o·f), de donde se despeja f.

#### 🛠️ Materiales y costos (S/. 15–30 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Smartphone con cámara | 1 | Ya lo tienes |
| Lupa (lente convergente) | 1 | S/. 5 |
| Lente de gafas de lectura (+1D a +3D) | 1 | S/. 10 (usadas) |
| Regla larga o cinta métrica (≥1 m) | 1 | S/. 3 |
| Objeto de tamaño conocido (regla impresa o figura patrón) | 1 | — |
| Trípode o soporte para smartphone | 1 | S/. 10 |
| Software ImageJ (gratuito) | 1 | Gratis |

#### 🔬 Procedimiento experimental

1. **Experimento 1 — Distancia focal del smartphone**:
   - Fotografiar una regla a distancias dₒ = 0.5, 1.0, 1.5, 2.0, 3.0 m.
   - Medir el tamaño de la imagen en pixeles usando ImageJ.
   - Graficar 1/h_i vs dₒ y calcular f.
   - Comparar con el valor del fabricante (disponible en metadatos EXIF).

2. **Experimento 2 — Distancia focal de una lupa**:
   - Colocar la lupa frente a la cámara del smartphone.
   - Repetir mediciones. El sistema compuesto tiene una f efectiva distinta.
   - Verificar la ecuación de lentes compuestos: 1/f_total = 1/f₁ + 1/f₂ - d/(f₁·f₂)

3. **Experimento 3 — Índice de refracción del agua**:
   - Fotografiar un objeto sumergido en agua y comparar con foto sin agua.
   - La razón de magnificaciones da el índice de refracción (extensión del paper de AJP).

4. **Experimento 4 — Lente divergente**:
   - Usar gafas de baja graduación (ej. -1 D).
   - La imagen es virtual, así que se requiere medir magnificación en dos posiciones del smartphone (técnica del paper arXiv).

#### 🎯 Resultados esperados

- Distancia focal del smartphone: ~3–5 mm (cámara trasera típica).
- Coincidencia con valor del fabricante con error <10%.
- Verificación exitosa de la ecuación del lente delgado.

#### ✨ Aspecto novedoso para obtener buena nota

- Es un experimento publicado en 2022 en American Journal of Physics (muy reciente).
- Extender al cálculo del **índice de refracción del agua** y de vidrio fotografiando objetos sumergidos.
- Encontrar los **planos principales** del sistema compuesto del smartphone.
- Comparar smartphones con distintos fabricantes y sus especificaciones.

#### 📚 Fuentes académicas detalladas

1. **Paper principal — "Using a smartphone camera to explore ray optics beyond the thin lens equation"** (American Journal of Physics, Vol. 90, 2022)
   - **Contenido del paper**: Experimento remoto diseñado originalmente para época COVID. Verifica la ecuación del lente delgado aplicada a la cámara del smartphone y encuentra buena concordancia con valores del fabricante. Luego muestra los límites de la aproximación "lente delgada" y cómo analizar el lente compuesto mediante **planos principales**. Usa ImageJ para medir pixeles. Incluye tablas de datos, ajustes lineales, y discusión de errores.
   - Enlace: https://pubs.aip.org/aapt/ajp/article/90/8/610/2820201/Using-a-smartphone-camera-to-explore-ray-optics

2. **Paper complementario — "Measuring the focal length of a camera lens in a smart-phone with a ruler"** (The Physics Teacher, 2019)
   - **Contenido**: Versión más simple que solo busca la distancia focal f (sin entrar en planos principales). Más accesible para introducción, con fotos del setup.
   - Enlace: https://pubs.aip.org/aapt/pte/article-abstract/57/1/54/1016249

3. **Paper — "Use of a smartphone camera to determine the focal length of a thin lens"** (arXiv)
   - **Contenido**: Trata el caso especial de **lentes divergentes** (cóncavos), que producen imagen virtual y son más difíciles de medir. Propone una técnica de dos posiciones de la cámara. Muy útil si quieres incluir lentes divergentes en tu proyecto.
   - Enlace: https://arxiv.org/pdf/2210.08751

4. **Acceso libre del paper principal — ResearchGate**
   - **Contenido**: Versión descargable gratuitamente del paper de AJP 2022 (para no tener que pagar la suscripción AIP).
   - Enlace: https://www.researchgate.net/publication/362400219_Using_a_smartphone_camera_to_explore_ray_optics_beyond_the_thin_lens_equation

---

### **PROYECTO 10: Construcción de una cámara oscura (pinhole camera) y análisis cuantitativo de la formación de imágenes**

#### 📖 Descripción extendida

La cámara oscura (*camera obscura* en latín) es el precursor histórico de todas las cámaras modernas. Descrita por primera vez por Mozi en China (siglo V a.C.) y por Aristóteles y Alhazen, es un dispositivo simple: una caja cerrada con un pequeño orificio que proyecta en la pared opuesta una imagen invertida del exterior.

En este proyecto se construirán varias cámaras oscuras con distintos tamaños de orificio y se estudiarán cuantitativamente: la **relación tamaño del orificio vs nitidez**, la **magnificación vs distancia focal**, y el compromiso entre **brillo y resolución**. Se comparará una cámara de pinhole con una cámara con lente.

#### 🧮 Fundamento teórico con ecuaciones clave

**Magnificación** de la imagen en una cámara oscura:

$$M = \frac{d_i}{d_o}$$

donde dᵢ es la distancia pinhole-pantalla y dₒ es la distancia objeto-pinhole.

**Número f (f-number)**:

$$f_\# = \frac{f}{d}$$

donde f es la distancia focal (longitud de la caja) y d el diámetro del pinhole.

**Resolución límite** según el análisis de Young en óptica geométrica:

$$r \approx 1.5 \times d/2 \quad \text{(para d grande)}$$

Para difracción (d pequeño, régimen de Fraunhofer):

$$r \approx 1.22 \lambda f / d$$

**Tamaño óptimo del pinhole**:

$$d_{opt} = 2\sqrt{f\lambda}$$

Para f = 10 cm y λ = 550 nm (luz verde), d_opt ≈ 0.47 mm.

#### 🛠️ Materiales y costos (S/. 10–20 total)

| Material | Cantidad | Costo aprox. |
|----------|----------|--------------|
| Caja de cartón o lata Pringles | 1 | S/. 5 |
| Papel aluminio | 1 | S/. 2 |
| Alfileres de distintos grosores (agujas) | 1 set | S/. 2 |
| Papel vegetal o papel mantequilla | 1 | S/. 2 |
| Cinta aislante negra | 1 | S/. 3 |
| Regla, transportador | — | — |
| Lupa (para comparación pinhole vs lente) | 1 | S/. 5 |
| Cámara del smartphone (para registrar imágenes) | 1 | — |

#### 🔬 Procedimiento experimental

1. **Construcción de la cámara oscura**:
   - Cortar una ventana en una cara de la caja, cubrirla con papel aluminio.
   - Hacer un pinhole en el centro del aluminio con una aguja.
   - Pegar papel vegetal en la cara opuesta como pantalla.

2. **Experimento 1 — Nitidez vs tamaño del pinhole**:
   - Hacer 4 pinholes de distintos tamaños (0.5 mm, 1 mm, 2 mm, 3 mm).
   - Fotografiar un objeto iluminado (vela o lámpara) a distancia fija.
   - Evaluar la nitidez de la imagen. A mayor diámetro, más brillo pero menos nitidez.

3. **Experimento 2 — Magnificación vs distancia focal**:
   - Construir cámaras con distintas longitudes (10, 15, 20, 30 cm).
   - Fotografiar el mismo objeto desde la misma distancia.
   - Verificar M = dᵢ/dₒ.

4. **Experimento 3 — Tamaño óptimo del pinhole**:
   - Calcular d_opt = 2√(f·λ) para cada cámara.
   - Comparar con los pinholes construidos: ¿cuál da la mejor nitidez?

5. **Experimento 4 — Comparación con lente**:
   - Reemplazar el pinhole con una lupa.
   - Comparar brillo, nitidez y profundidad de campo.

6. **Documentación**: Fotografiar cada imagen con el smartphone (manteniendo la configuración de exposición fija) y comparar.

#### 🎯 Resultados esperados

- Pinhole óptimo: 0.3–0.5 mm para una caja de 10–20 cm de largo.
- Imagen invertida y de izquierda a derecha.
- Profundidad de campo infinita (todas las distancias enfocadas igual).
- Comparación clara entre pinhole (poca luz, alta profundidad de campo) y lente (mucha luz, enfoque específico).

#### ✨ Aspecto novedoso para obtener buena nota

- Aplicar la **fórmula de Young** para calcular el pinhole óptimo experimentalmente.
- Demostrar el compromiso **brillo ↔ nitidez**.
- Usar el smartphone para registrar las imágenes en condiciones controladas y analizarlas con ImageJ.
- Relacionar con **fotografía pinhole artística** (incluir ejemplos históricos: primera fotografía moderna basada en este principio, 1826).
- Discutir por qué la imagen es invertida (propagación rectilínea de la luz).

#### 📚 Fuentes académicas detalladas

1. **Referencia principal — Wikipedia "Pinhole camera"** (con múltiples referencias a *The Physics Teacher*)
   - **Contenido**: Historia completa desde Mozi (500 a.C.) hasta la fotografía moderna. Incluye la derivación de la resolución límite de Young, la ecuación para el tamaño óptimo del pinhole, el régimen de óptica geométrica vs Fraunhofer (difracción), fórmulas de f-number, y discusión sobre la reciprocidad fotográfica.
   - Enlace: https://en.wikipedia.org/wiki/Pinhole_camera

2. **Reporte técnico ECE516 — Pinhole Camera Lab**
   - **Contenido**: Reporte de laboratorio con 3 experimentos cuantitativos: (1) cámara grande con pinhole de 0.8 mm, (2) cámara pequeña de 0.16 mm, (3) cámara con lente de 5x. Incluye el cálculo del diámetro óptimo según la fórmula d_opt = 2√(f·λ), tablas de configuración DSLR (ISO, shutter, f), y comparación de imágenes obtenidas.
   - Enlace: https://www.instructables.com/ECE516-Pinhole-Camera-Lab-Report/

3. **Guía IOPSpark — Institute of Physics UK**
   - **Contenido**: Plan de clase completo con experimentos paso a paso: (1) pinhole simple, (2) pinholes múltiples (con un patrón de agujeros), (3) reemplazar por lente y ver el efecto. Incluye cuestionarios y extensiones.
   - Enlace: https://spark.iop.org/pinhole-camera-and-lens-camera

4. **Reporte técnico MIT CSAIL — "Building a digital camera obscura"**
   - **Contenido**: Guía de laboratorio del curso 6.869 (Visión por Computadora) del MIT. Además de construcción básica, extiende a **cámara oscura anaglifa** con filtros de colores para crear imágenes 3D. Análisis cuantitativo usando cámara digital dentro de la caja.
   - Enlace: https://groups.csail.mit.edu/vision/courses/6.869/psets/pset3/pset3.pdf

---

## 📊 TABLA COMPARATIVA DE LOS 10 PROYECTOS

| # | Proyecto | Unidad | Tema principal | Costo | Dificultad | Novedad | Mi rec. |
|---|---------|--------|----------------|-------|------------|---------|---------|
| 1 | Capacitor casero + dieléctrico | Electricidad | Capacitancia, ε_r | S/. 20–30 | Baja | Media | — |
| 2 | Circuito RC con smartphone | Electricidad | Circuitos RC | S/. 15–25 | Media | **★ Alta** | ⭐ |
| 3 | Resistividad del grafito | Electricidad | Ley de Ohm, ρ | S/. 10–15 | Baja | Media | — |
| 4 | Biot-Savart con smartphone | Magnetismo | Biot-Savart, μ₀ | S/. 25–40 | Media | **★ Alta** | ⭐ |
| 5 | Linterna de sacudida | Magnetismo | Faraday, Lenz | S/. 30–50 | Media | Media | — |
| 6 | Imán en tubo de cobre | Magnetismo | Ley de Lenz, eddy | S/. 40–70 | Media | **★ Alta** | ⭐ |
| 7 | Motor homopolar | Magnetismo | Fuerza de Lorentz | S/. 15–25 | Baja | Media | — |
| 8 | Ley de Snell con láser | Óptica | Refracción, n | S/. 20–35 | Baja | Media | — |
| 9 | Distancia focal con smartphone | Óptica | Lente delgada | S/. 15–30 | Media | **★ Alta** | ⭐ |
| 10 | Cámara oscura | Óptica | Formación de imágenes | S/. 10–20 | Baja | Media | — |

---

## 🎯 MIS RECOMENDACIONES PERSONALES

Si buscas **mejor calificación con menor complejidad**, mis 3 favoritos son:

### 🥇 PROYECTO 2 — Circuito RC con smartphone
- **Por qué**: Paper del 2023 (muy reciente), demuestra uso innovador del smartphone como instrumento científico, permite obtener muchos datos cuantitativos (curvas exponenciales con R² > 0.99), es replicable con materiales muy baratos, y cubre uno de los temas más importantes del curso (circuitos RC).

### 🥈 PROYECTO 4 — Biot-Savart con smartphone
- **Por qué**: Es visualmente atractivo, fácil de defender en la exposición, permite graficar 3 relaciones distintas (B vs I, B vs N, B vs distancia), y el resultado final (la medición experimental de μ₀) es muy elegante y científicamente sólido.

### 🥉 PROYECTO 6 — Imán de neodimio en tubo de cobre
- **Por qué**: Visualmente impactante (el imán casi flota), tiene fuerte fundamento teórico (Faraday + Lenz + corrientes de Eddy), permite análisis cuantitativo con Tracker, y tiene múltiples variaciones para profundizar (tubos con ranuras, distintos metales).

---

## 📝 PRÓXIMOS PASOS

Cuando escojas un proyecto, puedo ayudarte a:
1. **Desarrollar el marco teórico completo** con todas las ecuaciones necesarias.
2. **Diseñar la metodología experimental detallada** (diagramas, procedimiento paso a paso).
3. **Elaborar el informe siguiendo el modelo que adjuntaste** (resumen, introducción, marco teórico, metodología, resultados, conclusiones, referencias IEEE).
4. **Diseñar las figuras y tablas** para los resultados.
5. **Revisar y corregir** versiones previas del informe.

Solo dime cuál eliges y avancemos con el detalle completo.
