# Barcelona Alimenta
**Dashboard de acceso a alimentación sostenible y de proximidad en los barrios de Barcelona**

**Enfoque:** Barcelona (ciudad, 73 barrios) · **Tema:** alimentación urbana

**Asignatura:** Gestión de Proyectos (UAB 2026/27) · **Grupo:** 8 — Oriol Carbó Molera (1795282) · Xavier Vara Anido (1795681) · Hèctor Villanueva Azuara (1790820) · Pol Raurich Barba (1795396)

---

## 1. Reto

No todos los barrios de Barcelona tienen el mismo acceso a alimentos frescos y de proximidad (mercados municipales, huertos urbanos, mercados al aire libre). Esa desigualdad se cruza con la renta y la densidad de población, y no hemos localizado una visión sencilla y pública que permita verla barrio a barrio.

**Pregunta guía:** ¿qué barrios tienen menos acceso a alimentación de proximidad, y qué proyectos urbanos podrían reducir esa brecha dentro de un modelo de ciudad justa, circular y regenerativa?

**Cómo medimos el acceso:** el indicador principal es el acceso físico a puntos de alimentación de proximidad (por ejemplo, puntos por 10.000 habitantes en cada barrio). Aquí «sostenible» se refiere a la proximidad y a los circuitos cortos, no a la certificación de lo que se vende, porque los datos abiertos no la recogen.

**Beneficiarios**
- Vecinas y vecinos de los barrios con menor acceso a alimentación de proximidad (beneficiarios directos).
- El Ajuntament de Barcelona y sus servicios de comercio, salud y Agenda 2030, que dispondrían de una herramienta para priorizar actuaciones.
- Entidades de huertos comunitarios, mercados y comercio de proximidad, que ganarían visibilidad y argumentos para su actividad.

## 2. Objetivos y finalidad

**Objetivo general:** diseñar y planificar un proyecto que haga visible y ayude a reducir las desigualdades de acceso a alimentación de proximidad en Barcelona, apoyado en datos abiertos.

**Objetivos específicos**
1. Mapear los puntos de alimentación de proximidad en los 73 barrios de la ciudad: mercados municipales, huertos urbanos y, si los datos lo permiten, mercados y ferias al aire libre, con datos de Open Data BCN.
2. Cruzar esa oferta con población y renta para construir un indicador de acceso por barrio, con al menos 3 indicadores en el dashboard.
3. Identificar los barrios prioritarios y proponer 2 o 3 intervenciones concretas, por ejemplo nuevos huertos comunitarios (con compostaje de residuos orgánicos para cerrar el ciclo), circuitos cortos de venta o mercados itinerantes.
4. Publicar un dashboard online como prototipo que comunique los resultados a la ciudadanía y a los responsables públicos.
5. Completar el diseño de gestión del proyecto: plan, costes, riesgos, impacto, stakeholders y gobernanza.

**Finalidad:** contribuir a una transformación urbana inteligente, sostenible, circular y justa, y demostrar coherencia entre el reto, las actividades, los recursos, los impactos y los riesgos.

## 3. Criterios mínimos de éxito

- [x] Enfoque, tema y reto definidos y recogidos en este README.
- [ ] Propuesta escrita completa: reto, plan de gestión, costes, riesgos, impacto, stakeholders y gobernanza.
- [ ] Prototipo: dashboard online publicado en GitHub Pages, con al menos 3 indicadores por barrio, un mapa y una página «Sobre» con fuentes, método y licencia.
- [ ] WBS, PERT y Gantt elaborados; tablero Kanban actualizado semanalmente (versión inicial ya publicada).
- [ ] Matriz de riesgos y Teoría del Cambio con indicadores de impacto.
- [ ] Roles asumidos y cumplidos según la matriz RACI.
- [ ] Presentación oral defendida por todo el grupo.
- [ ] Uso de IA declarado, con análisis y reflexión propios del grupo.

## 4. Roles

| Persona | Rol principal | Responsabilidades | Apoyo en |
|---|---|---|---|
| Oriol Carbó Molera | Coordinación y planificación | Repositorio, README, WBS, PERT, Gantt, tablero Kanban, reuniones y entregas | Redacción de la propuesta |
| Xavier Vara Anido | Impacto, costes y redacción | Costes y financiación, matriz de riesgos, Teoría del Cambio, indicadores y propuesta escrita | Análisis de datos |
| Hèctor Villanueva Azuara | Datos y prototipo | Datasets de Open Data BCN, limpieza, dashboard, GitHub Pages y `sobre.html` | Presentación oral |
| Pol Raurich Barba | Stakeholders y comunicación | Mapa de actores, gobernanza, estrategia de comunicación y guion de la presentación oral | Diseño visual del dashboard |

Todos los miembros revisan los entregables y participan en la presentación oral. La matriz RACI inicial está en [`docs/plan.md`](docs/plan.md#6-matriz-raci-inicial) y se revisa en la tarea E. Cada tarea del tablero tiene una etiqueta con su responsable.

## 5. Planificación

- **Plan completo** (WBS, PERT, Gantt, Kanban, riesgos y RACI): [`docs/plan.md`](docs/plan.md)
- **Cálculo PERT en Excel** (ruta crítica, holguras, fechas y probabilidad de plazo): [`docs/pert.xlsx`](docs/pert.xlsx)
- **Tablero Kanban y Roadmap** (GitHub Projects): [Kanban](https://github.com/users/polraurich1-stack/projects/1/views/1) · [Tabla](https://github.com/users/polraurich1-stack/projects/1/views/2) · [Roadmap (Gantt)](https://github.com/users/polraurich1-stack/projects/1/views/3)
- **Calendario:** inicio el 22/10/2026 y fin previsto el 18/01/2027, sin trabajo planificado en las vacaciones de Navidad (23/12–06/01). Ruta crítica: A → C → D → K → L → M → O (≈ 10,7 semanas).

## 6. Estructura del repositorio

`index.html`, `sobre.html` y `data/` se añadirán cuando se desarrolle el prototipo (tareas L y M).

```
barcelona-alimenta-grupo8/
├─ README.md
├─ LICENSE             (CC BY 4.0)
├─ index.html          (dashboard, raíz del sitio) · pendiente
├─ sobre.html          (fuentes, método y licencia) · pendiente
├─ docs/
│  ├─ plan.md          (WBS, PERT, Gantt, Kanban, riesgos, RACI)
│  └─ pert.xlsx        (cálculo PERT)
└─ data/               (datasets limpios) · pendiente
```

## 7. Datos y licencias

Fuente principal: Open Data BCN (Ajuntament de Barcelona), con licencia Creative Commons Attribution 4.0. Datasets previstos (localizados en el portal; falta validar su uso en la tarea B):

- Mercados municipales de la ciudad de Barcelona (CSV, actualización semanal)
- Huertos urbanos de la ciudad de Barcelona (CSV y JSON)
- Mercados y ferias al aire libre de la ciudad de Barcelona (localizado en el portal; pendiente de validar)
- Renta disponible de los hogares por persona, por secciones censales (CSV); habrá que agregarla a barrios
- Población por barrio (pendiente de seleccionar el dataset concreto)

Los datasets definitivos y su fecha de actualización se documentarán en `sobre.html`. Licencia del repositorio: [CC BY 4.0](LICENSE).

## 8. Uso de herramientas de IA

Se emplean herramientas de IA como apoyo (exploración de datos, generación de código del dashboard, revisión). El análisis, la interpretación y las decisiones son del grupo, y cada uso significativo se documenta.
