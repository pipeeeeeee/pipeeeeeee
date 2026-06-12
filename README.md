<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16,20,24&height=200&section=header&text=Cristian%20%Monsalve%20%7C%20pipeeeeeee&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineer%20%E2%80%A2%20Full%20Stack%20%E2%80%A2%20AI%20%2F%20Algorithms&descSize=18&descAlignY=55" width="100%"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&lines=Ingenier%C3%ADa+Civil+Inform%C3%A1tica+%40+UCM;Full+Stack+%26+Mobile+Developer;Algorithms+%26+Data+Structures;Building+TruckGO+%F0%9F%9A%9A" alt="Typing SVG"/>

<br/>

<img src="https://img.shields.io/badge/Universidad%20Cat%C3%B3lica%20del%20Maule-Ingenier%C3%ADa%20Civil%20Inform%C3%A1tica-6D28D9?style=for-the-badge&logo=googlescholar&logoColor=white"/>
<img src="https://img.shields.io/badge/%F0%9F%93%8D%20Talca,%20Chile-4C1D95?style=for-the-badge"/>

<br/><br/>

<a href="https://www.linkedin.com/in/cristian-felipe-monsalve-palma-a40488345/"><img src="https://img.shields.io/badge/LinkedIn-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:tu-email@ejemplo.com"><img src="https://img.shields.io/badge/Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/pipeeeeeee"><img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=pipeeeeeee&style=flat-square&color=8B5CF6&label=Profile+Views"/>
<img src="https://img.shields.io/github/followers/pipeeeeeee?style=flat-square&color=7C3AED&labelColor=1E1B2E&label=Followers"/>
<img src="https://img.shields.io/github/stars/pipeeeeeee?style=flat-square&color=6D28D9&labelColor=1E1B2E&label=Stars"/>

</div>

---

## 💼 Sobre mí

```typescript
const pipe = {
  role: "Software Engineer in training",
  education: "Ingeniería Civil Informática — Universidad Católica del Maule, Universidad de Cantabria (Pasantía)",
  focus: ["Full Stack Development", "Mobile Engineering", "Algorithms & AI"],
  currentlyBuilding: "TruckGO — freight marketplace for the Chilean market",
  mindset: "Product engineering: ship real solutions, measure real impact",
};
```

Ingeniero en formación con enfoque en **desarrollo full stack y mobile**, **algoritmos avanzados** y **búsqueda semántica con embeddings**. Experiencia construyendo productos end-to-end: desde la arquitectura del backend y la base de datos hasta la app móvil en producción, con CI/CD y notificaciones en tiempo real.

**🟣 Abierto a:** Prácticas profesionales · Proyectos freelance · Colaboración open source · Roles junior en ingeniería de software

---

## 🛠️ Tech Stack

<div align="center">

**Lenguajes**

<img src="https://skillicons.dev/icons?i=typescript,javascript,python,cpp,java&theme=dark"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,angular,html,css,materialui&theme=dark"/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nestjs,nodejs,postgresql,supabase&theme=dark"/>

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=githubactions,git,github,vscode,apple,latex,cmake&theme=dark"/>

</div>

---

## Experiencia en IA/ML y algoritmos

| Domain | Proficiency | Details |
|:-------|:-----------:|:--------|
| Semantic Search & Embeddings | ▰▰▰▰▱ | Vectores de 384 dimensiones con `llama.cpp` + `all-MiniLM-L6-v2`, comparación BallTree vs KDTree vs fuerza bruta |
| Algorithm Design & Analysis | ▰▰▰▰▱ | Divide & Conquer, programación dinámica, greedy, análisis de complejidad y curse of dimensionality |
| Graph Algorithms | ▰▰▰▰▱ | Dijkstra, Bellman-Ford, Prim, Kruskal, Floyd-Warshall, Union-Find en C++ y Python |
| Data Structures | ▰▰▰▰▱ | BallTree, KDTree, heaps (max-heap KNN), árboles de búsqueda espacial |
| Mobile + Realtime Systems | ▰▰▰▱▱ | Supabase Realtime, push notifications, gestión de estados de viaje |

---

## 🚀 Proyectos

<details>
<summary><b>🚚 TruckGO — Freight Marketplace App</b></summary>
<br/>

Marketplace móvil de fletes para el mercado chileno que conecta clientes con conductores de camiones, inspirado en el modelo de Uber/Cornershop.

| Aspect | Details |
|:-------|:--------|
| **Stack** | React Native · Expo SDK 54 · TypeScript · NestJS · PostgreSQL (Supabase) |
| **Scale** | Arquitectura por roles (cliente/conductor), mapas OSM, chat en tiempo real |
| **Performance** | Supabase Realtime para chat y estados de viaje con latencia mínima |
| **Security** | Supabase Auth con routing basado en roles y políticas RLS |
| **Impact** | Flujo completo: publicación → aceptación → viaje → notificaciones push |
| **Repository** | [github.com/pipeeeeeee/truckgo](https://github.com/pipeeeeeee/truckgo) |

App full stack en desarrollo activo con CI/CD vía Railway + GitHub Actions y documentación académica en LaTeX.

</details>

<details>
<summary><b>🔍 Semantic Search Engine — BallTree vs KDTree (C++)</b></summary>
<br/>

Motor de búsqueda semántica implementando **BallTree como estrategia Divide & Conquer**, comparado contra KDTree y fuerza bruta sobre embeddings reales.

| Aspect | Details |
|:-------|:--------|
| **Stack** | C++ · llama.cpp · all-MiniLM-L6-v2 (Q8_0) · CMake |
| **Scale** | Embeddings de 384 dimensiones, búsqueda KNN con max-heap |
| **Performance** | Análisis empírico del curse of dimensionality: KDTree superó a BallTree en velocidad a d=384 |
| **Security** | N/A — proyecto de investigación algorítmica |
| **Impact** | BallTree logró un uso de memoria significativamente menor; hallazgos documentados con análisis de complejidad |
| **Repository** | [github.com/pipeeeeeee/INF413_URIBE_FRANCISCO_URIBE_EFRAIN_MONSALVE_CRISTIAN](https://github.com/pipeeeeeee/INF413_URIBE_FRANCISCO_URIBE_EFRAIN_MONSALVE_CRISTIAN) |

Proyecto de equipo para Diseño y Análisis de Algoritmos con benchmarking riguroso de estructuras de búsqueda espacial.

</details>

<details>
<summary><b>🎓 TutorApp — Student Tutoring Platform</b></summary>
<br/>

Plataforma web de tutorías entre estudiantes construida en Angular, cubriendo el ciclo completo de desarrollo frontend.

| Aspect | Details |
|:-------|:--------|
| **Stack** | Angular · Angular Material · Reactive Forms · JSON Server |
| **Scale** | CRUD completo de tutorías, perfiles y agendamiento |
| **Performance** | Formularios reactivos con validación en tiempo real |
| **Security** | Route guards para protección de rutas por sesión |
| **Impact** | Proyecto de aprendizaje end-to-end desplegado en GitHub |
| **Repository** | [github.com/pipeeeeeee](https://github.com/pipeeeeeee) |

Desarrollo guiado paso a paso desde fundamentos hasta despliegue.

</details>

<details>
<summary><b>📊 Algorithms Lab — Graph & DP Implementations</b></summary>
<br/>

Colección de implementaciones de algoritmos clásicos en C++ y Python con casos de prueba y visualización de grafos.

| Aspect | Details |
|:-------|:--------|
| **Stack** | C++ · Python 3 · CMake · Graphviz (.dot) |
| **Scale** | Prim, Kruskal, Bellman-Ford, Dijkstra, Floyd-Warshall, LCS, knapsack |
| **Performance** | Trazas tabulares paso a paso y comparación contra salida esperada |
| **Security** | N/A |
| **Impact** | Base de estudio y referencia para análisis de algoritmos |
| **Repository** | [github.com/pipeeeeeee](https://github.com/pipeeeeeee) |

Código simple y legible, priorizando claridad sobre micro-optimización.

</details>

---

## 💼 Experiencia

**Desarrollador Full Stack (Proyecto Independiente)** · TruckGO
<sub>2025 — Presente</sub>

Diseño y desarrollo de un marketplace de fletes para Chile, liderando producto y tecnología de extremo a extremo.

- Arquitectura mobile-first con React Native + Expo y backend NestJS sobre Supabase
- Implementación de autenticación por roles, mapas, chat en tiempo real y push notifications
- Pipeline CI/CD con Railway y GitHub Actions

`React Native` `TypeScript` `NestJS` `PostgreSQL` `Supabase` `CI/CD`

---

## 🏆 Logros

<div align="center">

| Recognition | Details |
|:-----------:|:--------|
| 🥇 Proyecto destacado | Motor de búsqueda semántica con análisis comparativo de estructuras espaciales |
| 📱 Producto en desarrollo activo | TruckGO: app full stack con fases de auth, mapas, chat y notificaciones completadas |
| 📚 Investigación académica | Estudio correlacional sobre habilidades sociales y rendimiento académico/laboral en Talca |

</div>

---

## 📜 Certificaciones

**Universidad Católica del Maule**

<img src="https://img.shields.io/badge/Ingenier%C3%ADa%20Civil%20Inform%C3%A1tica-En%20curso-7C3AED?style=flat-square&logo=googlescholar&logoColor=white"/>

**Próximas certificaciones**

<img src="https://img.shields.io/badge/AWS-Planificada-4C1D95?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Cisco-Planificada-5B21B6?style=flat-square&logo=cisco&logoColor=white"/>

---

## 📈 Análisis de GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=pipeeeeeee&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=7C3AED" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=pipeeeeeee&theme=midnight-purple&hide_border=true&background=0D1117&ring=8B5CF6&fire=7C3AED&currStreakLabel=8B5CF6" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pipeeeeeee&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=8B5CF6" width="49%"/>

</div>

---


## 📊 Actividad de contribuciones

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=pipeeeeeee&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=8B5CF6&line=7C3AED&point=A78BFA" width="100%"/>

</div>

---

## 🐍 Serpiente de contribuciones

<div align="center">

<img src="https://raw.githubusercontent.com/pipeeeeeee/pipeeeeeee/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

---

## 🎯 Focos actuales

```yaml
Aprendiendo:
  - Diseño y Análisis de Algoritmos avanzados
  - Estructuras de búsqueda espacial y vectorial
  - Arquitectura de sistemas en tiempo real

Construyendo:
  - TruckGO: marketplace de fletes para Chile
  - Implementaciones de algoritmos de grafos en C++

Explorando:
  - Embeddings y búsqueda semántica a escala
  - Optimización de pipelines CI/CD

Abierto a:
  - Prácticas profesionales
  - Colaboración open source
  - Proyectos freelance
```

---

## 🤝 Enlaces

<div align="center">

<a href="mailto:pipemonsalve86@gmail.com"><img src="https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/cristian-felipe-monsalve-palma-a40488345/"><img src="https://img.shields.io/badge/LinkedIn-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/pipeeeeeee"><img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white"/></a>


</div>

---

<div align="center">

*"Haciendo lo mío, haciéndolo mío"*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16,20,24&height=120&section=footer" width="100%"/>

</div>
