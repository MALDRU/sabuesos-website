# Propuesta — Sitio web y renovación de marca · Sabuesos Pasto

**Concepto:** _“El olfato de un especialista, la calma de casa.”_
Una clínica 24/7 seria y médica en lo que importa (urgencias, diagnóstico, cirugía), con la calidez que ya muestran en Instagram.

Entregables en esta carpeta:
- `index.html` — propuesta del sitio (one-page, funcional).
- `logo.html` — presentación de la renovación de logo.
- `assets/isotipo.svg`, `assets/logo-horizontal.svg` — logo propuesto.
- Sección `#agendar` del sitio — módulo opcional **Agenda Bot** (ver punto 8).

---

## 1. Objetivo del sitio y CTA
- **Objetivo:** que un tutor en Pasto, desde el celular, encuentre a Sabuesos y **actúe en menos de 10 segundos**.
- **CTA primario:** _Agendar cita_ (agenda en línea de Agenda Bot; ver punto 8).
- **CTA de urgencia (siempre visible):** _Llamar ahora · 314 850 7581_ (barra superior fija + botón en hero + botón flotante de WhatsApp).
- **CTA secundario:** _Cómo llegar_ (Google Maps).

## 2. Mapa del sitio
**One-page** en esta fase: el negocio se explica en una sola pantalla larga, el usuario llega desde Instagram/Google con prisa y el contenido real todavía es limitado. Fase 2 (opcional): páginas por servicio (`/urgencias`, `/cirugia`, `/laboratorio`…) para SEO local, y un blog con los consejos que ya publican en redes.

## 3. Estructura del home
1. **Barra de urgencias** — “Urgencias 24 horas, todos los días” + llamar.
2. **Header** — logo nuevo, navegación, botón “Agendar cita”.
3. **Hero** — “Tu mascota, siempre en las mejores manos.” (su eslogan actual) + servicios clave + 2 CTA + foto real del equipo/fachada.
4. **Franja de confianza** — 24/7 · Perros y gatos · Laboratorio e imágenes propias · Especialistas.
5. **Servicios** — Urgencias, Hospitalización, Cirugía, Laboratorio clínico, Imágenes diagnósticas, Odontología, Medicina general.
6. **Especialidades** — Cardiología, Oncología, Ortopedia, Etología.
7. **¿Es una urgencia?** — señales de alarma + botón llamar (contenido útil que posiciona y convierte).
8. **Agenda en línea (Agenda Bot)** — agenda web/PWA, asistente de WhatsApp y bot de Telegram (próximamente) + 3 pasos.
9. **Pacientes que se fueron a casa** — historias reales (Mili, Merlin, Tobi, Ramona) con permiso de los tutores; retoma los “diplomas de alta” de Instagram.
10. **Preguntas frecuentes.**
11. **Ubicación y contacto** — mapa, dirección, horario, teléfono, redes.
12. **Footer.**

## 4. Dirección visual
| Token | Hex | Uso |
|---|---|---|
| Verde Sabuesos | `#0E6B4E` | Color principal, botones, títulos. Contraste 6.4:1 sobre crema |
| Verde hoja | `#3FA77A` | Acentos, íconos |
| Naranja oreja | `#F28C28` | Acento de marca, CTA de urgencia (texto marino encima, 6.9:1) |
| Naranja texto | `#A9520A` | Naranja cuando va como texto sobre claro (≥ 4.5:1) |
| Azul noche | `#12233D` | Texto principal, secciones oscuras (heredado del letrero) |
| Crema | `#FBF7F0` | Fondo cálido (evita el “blanco hospital”) |

- **Tipografías:** _Bricolage Grotesque_ (títulos: amigable pero firme) + _Figtree_ (texto: muy legible en móvil). Ambas Google Fonts.
- **Estilo de imagen:** fotos reales del equipo y pacientes, luz natural, encuadres cercanos; nada de bancos de imágenes genéricos.
- **Formas:** esquinas redondeadas generosas, la “oreja” naranja como recurso gráfico.

## 5. Renovación de logo (ver `logo.html`)
**Diagnóstico del logo actual**
- Incluye una **fotografía** dentro del logo: no se puede bordar, grabar ni imprimir en una sola tinta, y se pierde en tamaños pequeños (avatar de IG, favicon).
- Wordmark con relieve/sombra y letras irregulares: difícil de leer a distancia.
- El subtítulo dice “Odontológico” y la fachada “Centro Veterinario”: el nombre no es consistente entre piezas.
- Demasiados elementos compitiendo (foto + forma + texto + subtítulo).

**Propuesta**
- **Isotipo:** un sabueso de perfil, nariz al frente —el olfato, la intuición clínica— con la oreja larga en naranja y una cruz médica: **veterinaria + urgencias** en un símbolo que funciona de 16 px a una fachada.
- **Wordmark:** “sabuesos” en minúscula, Bricolage Grotesque ExtraBold; descriptor “Clínica Veterinaria · Pasto”.
- **Conserva la memoria de la marca** (verde + naranja + azul del letrero), así los clientes actuales la reconocen.
- Versiones: horizontal, vertical, isotipo solo, monocromo, negativo.

## 6. Copy clave
- **H1:** Tu mascota, siempre en las mejores manos.
- **Sub:** Clínica veterinaria para perros y gatos en Pasto. Urgencias 24 horas, hospitalización, cirugía, laboratorio e imágenes diagnósticas en un solo lugar.
- **CTA:** Agendar cita por WhatsApp · Urgencias: 314 850 7581
- **Urgencias:** “Si tu mascota no respira bien, convulsiona o tuvo un accidente, no esperes. Llámanos: estamos despiertos.”
- **Pacientes:** “Cada alta es una fiesta. Estos son algunos de los que volvieron a casa.”

## 7. SEO base
- **Title:** Sabuesos | Clínica Veterinaria 24 horas en Pasto
- **Meta description:** Urgencias veterinarias 24/7 en Pasto. Hospitalización, cirugía, laboratorio clínico, ecografía y especialistas para perros y gatos. Calle 18 #31-58, Parque Infantil.
- **Palabras clave:** veterinaria 24 horas Pasto, urgencias veterinarias Pasto, clínica veterinaria Pasto, veterinario de gatos Pasto, ecografía veterinaria Pasto, cirugía veterinaria Nariño.
- Schema.org `VeterinaryCare` con dirección, teléfono, horario 24/7 y redes.
- Acción paralela clave: **ficha de Google Business** optimizada (es donde busca la gente en una urgencia).

## 8. Adquisición opcional: Agenda Bot
Sistema de agendamiento de Marandev ([marandev.co/apps/agenda-bot](https://marandev.co/apps/agenda-bot/)) que el sitio ya integra. Hoy las citas dependen de que alguien conteste el teléfono; con Agenda Bot el tutor reserva solo, a cualquier hora, y la clínica recibe la agenda ordenada.

**Canales para Sabuesos**
| Canal | Estado | Acceso |
|---|---|---|
| Agenda web (instalable como app/PWA) | Listo, falta cargar servicios | [agenda-bot.marandev.co/sabuesos-clinica-veterinaria/agendar-cita](https://agenda-bot.marandev.co/sabuesos-clinica-veterinaria/agendar-cita) |
| Asistente de WhatsApp | Disponible | +57 316 079 7189 |
| Bot de Telegram | Próximamente | @SabuesosPastoBot (nombre propuesto) |

**Qué gana la clínica**
- Reservas 24/7 sin ocupar la línea de urgencias (314 850 7581 queda solo para emergencias y llamadas).
- Sin sobrecupos ni horarios cruzados: solo se ofrecen espacios realmente libres, por profesional o recurso (consultorio, ecógrafo, quirófano).
- Confirmaciones y recordatorios automáticos → menos inasistencias.
- El tutor no necesita crear cuenta; puede consultar o cancelar su cita.
- Panel con filtros por profesional, estado y origen de la cita; festivos de Colombia automáticos.

**Cómo se integra en el sitio:** botón “Agendar cita” en el header y el hero, sección `#agendar` con los tres canales, botón flotante de WhatsApp apuntando al asistente y preguntas frecuentes sobre cambiar o cancelar citas. Las urgencias siempre redirigen a llamar.

**Para activarlo:** cargar el catálogo de servicios y duraciones (consulta general, vacunación, control, especialidades, ecografía…), profesionales y horarios de atención con cita. Plan mensual en COP según condiciones comerciales.

## 9. Pendientes del cliente
Ver sección PENDIENTE de `brief.md`: confirmar WhatsApp, fotos reales, equipo médico, testimonios autorizados, dominio, aprobación del logo y, si toman Agenda Bot, servicios/horarios para configurarlo.
