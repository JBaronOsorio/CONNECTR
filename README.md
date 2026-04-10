# CONNECTR — Guión de Pitch (12-13 min + Q&A)

> Cada quien lee su parte, la ensaya 2-3 veces y la hace suya. No lean textual — usen esto como guía.

---

## Distribución de tiempos

| Presentador | Tiempo | Temas |
|---|---|---|
| **Juan José** | ~4.5 min | Apertura, problema, solución, mercado |
| **Thomas** | ~4.5 min | Servicios, tech stack, competencia, equipo |
| **Felipe** | ~4 min | Finanzas, roadmap, ventaja, cierre |

---

## 🔵 JUAN JOSÉ — Apertura (Slides 1-3, 5)

### SLIDE 1 — Portada (0:45)

Buenos días/tardes, profesor y compañeros. Somos Felipe, Thomas y Juan José, y hoy les vamos a presentar **CONNECTR**.

Voy a empezar con un dato: **10 millones de colombianos no tienen acceso a Internet**. Pero el problema no es solo de infraestructura — Colombia ya está invirtiendo miles de millones en redes rurales. El problema es que **nadie puede ver si esas redes funcionan**. Los alcaldes no saben si la red que desplegaron está encendida. Los operadores no detectan fallos hasta que una comunidad se queda sin conexión por días. Y MinTIC necesita monitorear 1,123 municipios sin una herramienta centralizada.

Ahí es donde entra CONNECTR.

> 💡 Empieza con seguridad, haz contacto visual. El dato de los 10 millones genera impacto inmediato.

---

### SLIDE 2 — Problema (1:30)

Veamos los números. La conectividad rural en Colombia está en estado crítico: solo el **6% de conectividad en rural disperso**, cobertura 4G en zonas rurales de apenas **9.6%**, frente al 90% en áreas urbanas.

Pero el verdadero dolor no es la falta de redes — es la **falta de gestión**. Hoy los gobiernos locales manejan sus redes con procesos manuales, no saben el estado real de lo que desplegaron, y no pueden reportar resultados a MinTIC. Los operadores tienen redes dispersas que no pueden monitorear remotamente. Y las comunidades organizadas que operan cooperativas de conectividad no tienen herramientas profesionales.

¿Qué opciones hay hoy? Herramientas open source como Grafana y Prometheus que requieren un DevOps dedicado, o soluciones enterprise de Cisco que cuestan más de **10 mil dólares al mes**. Ninguna está adaptada a la realidad rural colombiana. **No existe una solución local**.

---

### SLIDE 3 — Solución (1:15)

CONNECTR es una **plataforma SaaS de monitoreo y gestión de redes de conectividad rural**.

Imaginen un dashboard donde un alcalde puede ver en un mapa interactivo el estado de cada antena, router y enlace de fibra de su municipio. En tiempo real: uptime, latencia, ancho de banda, usuarios conectados. Si algo falla, se genera una alerta automática y un ticket de mantenimiento.

Pero va más allá del monitoreo. CONNECTR gestiona el inventario de equipos, programa mantenimiento preventivo, genera reportes automáticos de cumplimiento para MinTIC, y da analytics para tomar decisiones basadas en datos — no en intuición.

Funciona con cualquier tecnología: fibra óptica, 4G, satelital, LoRaWAN. Y se integra mediante APIs abiertas con los sistemas que ya tengan.

---

### SLIDE 5 — Mercado (1:00)

Nuestro mercado objetivo se divide en tres segmentos. Primero, más de **500 municipios** con secretarías TIC que tienen presupuesto FUTIC dedicado a tecnología. Segundo, entre **50 y 100 operadores** de telecomunicaciones que manejan redes rurales. Y tercero, **32 gobernaciones** que necesitan visibilidad departamental.

Eso nos da un TAM de **25.4 millones de dólares al año** solo en Colombia. Nuestro SAM realista son 15 millones, y nuestro SOM para los primeros dos años es de **2 a 3 millones**. Y la expansión a LATAM — México, Perú, Ecuador, Bolivia — multiplica ese TAM entre 5 y 10 veces.

Ahora Thomas les va a explicar nuestro portafolio de servicios y la arquitectura técnica.

> 💡 Al pasar a Thomas, voltea a verlo y dale la palabra naturalmente.

---

## 🟢 THOMAS — Servicios, competencia, equipo (Slides 4, 8, 7)

### SLIDE 4 — Portafolio de servicios (1:30)

Gracias, Juan José. Tenemos **tres líneas de servicio** diseñadas para cada segmento.

La primera es **CONNECTR Monitor**, para municipios pequeños. Es el dashboard de monitoreo en tiempo real: mapa interactivo, alertas de fallos, métricas de uptime y latencia. Se implementa en 2 días y cuesta **15 mil dólares al año**. El stack es React, Node.js, AWS y PostgreSQL.

La segunda es **CONNECTR Pro**, para municipios medianos y operadores. Agrega gestión de infraestructura completa: inventario de equipos, mantenimiento preventivo, analytics avanzados y reportes automáticos a MinTIC. Se implementa en 5 días, con precios entre **35 y 75 mil dólares al año**. Acá usamos Python, Kubernetes y TimescaleDB para las series temporales.

Y la tercera es **CONNECTR Enterprise**, para gobernaciones y telcos grandes. SLA de 99.9%, soporte dedicado 24/7, integración API personalizada, capacitación extensiva. Desde **150 mil dólares al año** con equipo dedicado de customer success.

---

### SLIDE 8 — Competidores (1:15)

Analicemos la competencia. En el mercado global está **Cisco Prime y Meraki** — marca establecida, soporte global, pero con precios de más de 10 mil dólares al mes. Completamente fuera de alcance para un municipio colombiano, y no está adaptado a la realidad rural de acá.

La otra opción es la ruta open source: **Grafana más Prometheus**. Es gratis y flexible, pero necesitas un DevOps dedicado que te va a costar entre 3 y 5 mil dólares al mes de todas formas. No tiene features de gestión rural, ni soporte, ni onboarding.

Y ahí está nuestro diferenciador: **CONNECTR es local, asequible, en español**, adaptado a la regulación MinTIC, con onboarding hands-on y soporte 24/7. Desde 15 mil dólares al año versus más de 120 mil de las alternativas. No existe competencia directa en LATAM para el segmento rural.

---

### SLIDE 7 — Equipo (1:30)

El equipo fundador somos tres. **Juan José** lidera la apertura y la visión del problema y el mercado. **Felipe** está a cargo de las finanzas, el modelo de negocio y la estrategia de crecimiento. Y yo, **Thomas**, manejo la arquitectura técnica, el desarrollo de la plataforma, cloud y DevOps.

Para el Year 1 necesitamos 5 contrataciones adicionales: un lead backend developer con certificación AWS, un frontend developer para el dashboard y mapas, un DevOps engineer para infraestructura cloud, un perfil de business development para pilotos y partnerships, y un customer success para onboarding y soporte. El costo total del equipo Year 1 es de aproximadamente **400 mil dólares**.

Felipe les va a presentar las finanzas y nuestra hoja de ruta.

> 💡 Al mencionar a cada cofundador, señálalo o voltea a verlo. Genera cercanía.

---

## 🟡 FELIPE — Finanzas, roadmap, cierre (Slides 6, 9, 10, 11-12)

### SLIDE 6 — Modelo de negocio (1:00)

Gracias, Thomas. Nuestro modelo de ingresos es **70% SaaS recurring** con suscripciones anuales, 20% de implementación y onboarding, y 10% de servicios profesionales como integraciones custom y capacitación.

Los unit economics son sólidos: nuestro costo de adquisición de cliente es menor a **2 mil dólares** — porque vendemos directo a gobiernos, sin intermediarios. El valor de vida del cliente es de más de **30 mil dólares**, con contratos a 3 años y retención del 80%. Eso nos da un ratio LTV/CAC de **15 a 1**, que es excelente. Y el margen bruto es de 75 a 80%, estándar de SaaS.

---

### SLIDE 9 — Proyección financiera (1:15)

La proyección financiera a tres años es la siguiente. **Year 1**: 33 clientes, revenue de 1.08 millones, costos de 600 mil, net positivo de **480 mil dólares**. Somos rentables desde el primer año.

**Year 2**: escalamos a 120 clientes, revenue de 5.3 millones con un margen neto del 67%. **Year 3**: 315 clientes, revenue de 17.25 millones.

Corrimos la simulación financiera en FinProject. El VPN a 3 años con tasa de descuento del 15% nos da **12.3 millones de dólares positivos**. La TIR es del **258%**, muy por encima del WACC. El punto de equilibrio lo alcanzamos con **29 clientes**, que proyectamos tener entre el mes 5 y 6. Y el payback de la inversión inicial de 400 mil dólares se recupera en **10 meses**.

> 💡 Apunta a la gráfica cuando menciones Year 1, 2 y 3. Los números visuales refuerzan lo que dices.

---

### SLIDE 10 — Hoja de ruta (1:00)

Nuestra hoja de ruta está en 4 fases. **Q1**: lanzamos el MVP y validamos con 3 a 5 municipios piloto gratuitos o con descuento. El milestone es tener el producto deployed y el primer cliente pagando.

**Q2**: buscamos product-market fit con 10 municipios on-board, publicamos el primer case study y completamos la documentación de API. Meta: 30 a 50 mil dólares de MRR.

**Q3**: early growth — 20 a 30 municipios, 3 a 5 operadores, y cerramos partnerships con iNNpulsa y Ruta N.

**Q4**: escala — 50 a 70 clientes totales, primeras gobernaciones interesadas, y cerramos el seed round. Meta: más de 200 mil dólares de MRR.

---

### SLIDES 11-12 — Cierre (0:45)

¿Por qué es el momento para CONNECTR? Cuatro razones. **Primera**: la regulación está a favor — MinTIC tiene el Plan Nacional de Conectividad, hay fondos CAF y europeos, y la Ley FUTIC les da presupuesto a los municipios. **Segunda**: no dependemos de presupuesto privado para empezar — los gobiernos ya tienen el dinero asignado. **Tercera**: no existe competencia local — las big tech ignoran el mercado rural LATAM. Y **cuarta**: los network effects — más municipios en la plataforma significa más valor para todos.

**CONNECTR no es solo SaaS. Es una herramienta de equidad digital** que ayuda a cerrar la brecha entre la Colombia urbana y la Colombia rural. 25 millones de dólares de mercado en Colombia, rentable desde el Year 1, sin competencia directa, y con el timing perfecto.

Somos Felipe, Thomas y Juan José. Esto es CONNECTR. **Gracias, estamos abiertos a preguntas.**

> 💡 Termina con confianza. Sonrían. El cierre con "herramienta de equidad digital" es el mensaje que queda en la mente.

---

## ❓ PREGUNTAS PROBABLES DEL PROFESOR

### 1. ¿Qué 5 organizaciones colombianas tienen este problema?
Alcaldía de Buenaventura, Gobernación de Nariño, Gobernación del Chocó, operador ETB en zonas rurales de Boyacá, y cooperativas como ColNodo.
→ **Responde Juan José**

### 2. ¿Por qué usarían su producto y no Globant o una big tech?
Globant hace consultoría, no tiene producto SaaS de monitoreo rural. Cisco cuesta 10x más. Nosotros somos locales, en español, con precios para presupuestos municipales y compliance MinTIC incluido.
→ **Responde Thomas**

### 3. ¿Cómo llegaron al precio de $15K/año?
Benchmark contra Cisco ($120K+), validación con presupuestos FUTIC municipales ($15-50K para TIC), y target de margen bruto 75-80%.
→ **Responde Felipe**

### 4. ¿Qué stack tecnológico y certificaciones?
React + TypeScript frontend, Node.js/Python backend, PostgreSQL + TimescaleDB, AWS, Docker + Kubernetes, Terraform. Certs: AWS Solutions Architect, CKA, CISSP.
→ **Responde Thomas**

### 5. ¿Es escalable? ¿Si tienen 10x clientes, aguanta?
Sí. Cloud-native con auto-scaling en AWS. TimescaleDB para series temporales. Kubernetes para microservicios. Costo de infra por cliente baja con volumen.
→ **Responde Thomas**

### 6. ¿Qué normativa aplica?
Ley 1581/2012 (datos personales), CONPES 3975 (transformación digital), CONPES 3920 (datos abiertos), Ley FUTIC, guías MinTIC.
→ **Responde Juan José**

### 7. ¿Pueden aplicar a iNNpulsa o Ruta N?
Sí. Calificamos para Aldea de iNNpulsa, fondos Ruta N, Apps.co. Estamos en ecosistema EAFIT.
→ **Responde Juan José**

### 8. ¿Estrategia a 5 años?
Fase 1 bootstrapping + seed $300-500K. Fase 2 Series A $2-3M. Fase 3 expansión LATAM. Exit probable: adquisición por telco grande o player GovTech.
→ **Responde Felipe**

---

*Ensayen cada uno su parte 2-3 veces antes de presentar 🚀*
