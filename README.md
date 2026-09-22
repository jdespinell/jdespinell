<div align="center">

# Julián Espinel 👋

**Data Scientist & Quantitative Modeler | Ph.D. in Pure Mathematics**  
*Cientista de Dados e Modelador Quantitativo | Doutor em Matemática*  
*Científico de Datos y Modelador Cuantitativo | Doctor en Matemáticas*

**🌐 Idiomas / Languages:**  
[ 🇺🇸 English ](#-english)  • [ 🇧🇷 Português ](#-português)  • [ 🇪🇸 Español ](#-español)

---

</div>

<br>

<a id="-english"></a>
## 🇺🇸 English

Data Scientist and Quantitative Modeler with a solid academic background (**Ph.D. and M.Sc. in Pure Mathematics / Singularity Theory**) and practical experience building end-to-end analytical pipelines and software architectures.

My transition to Data Science and the Financial Sector (Banking, Insurance, and Capital Markets) merges the **rigorous analytical foundation of advanced mathematics** (algebra, convex geometry, statistical inference, and time series modeling) with **software engineering execution** (modular data pipelines, relational SQL modeling, REST APIs with FastAPI, Docker containerization, and Generative AI integration).

- 🛠️ **Core Stack:** Python (Pandas, Scikit-Learn, Statsmodels, SciPy, FastAPI, SQLAlchemy), SQL (PostgreSQL), Docker, Git.
- 📊 **Specialties:** Quantitative modeling, financial risk & fundamental rating models, time series analysis (structural trend & ETS models), clustering & dimensionality reduction (K-Means, PCA), mathematical optimization, and LLM integrations.
- 🎓 **Education:** Ph.D. and M.Sc. in Mathematics (research focused on geometry, algebra, and complex mathematical structures).
- 📍 Based in Brazil | Open to on-site and remote opportunities.

### 🚀 Featured Projects

#### 1. [Cluster_B3 — Quantitative Segmentation & Time Series Pipeline for Brazilian Equities (B3)](https://github.com/jdespinell/Cluster_B3)
- **Description:** End-to-end quantitative analysis and unsupervised Machine Learning system developed for data cleaning, temporal modeling, and fundamental segmentation of **372 companies listed on the Brazilian stock exchange (B3)** using 10 years of historical financial statements (2017–2026).
  - **Robust Data Preprocessing:** Intra-sector median imputation and 1%-99% winsorization to handle severe financial skews and market outliers.
  - **Time Series with Holt Damped ETS:** Structural level and smoothed trend extraction over 10-year historical series, filtering out short-term macroeconomic noise.
  - **Factor Engineering & Ratings:** Construction of 5 composite scores (Quality, Sector-relative Value multiples, Growth, Solvency/Financial Health, and Dividends).
  - **Clustering & Dimensionality Reduction:** Scaled via `RobustScaler`, dimensionality reduction via PCA, and optimal K-Means clustering ($k=5$) validated by Silhouette and Elbow methods to identify clear investment archetypes (*Quality Growth, Value, Dividend Aristocrats, etc.*).
  - **Executive Dashboards & Reporting:** Automated generation of correlation heatmaps, radar charts, sector boxplots, composite rankings, and an interactive HTML report.
- **Stack:** Python (Pandas, Scikit-Learn, Statsmodels, NumPy, Matplotlib, Seaborn), PCA, K-Means, Holt Damped ETS, HTML/CSS.
- [Explore repository →](https://github.com/jdespinell/Cluster_B3)

#### 2. [Biblioteca — SaaS Platform with Backend Architecture, SQL Modeling & GenAI](https://github.com/jdespinell/biblioteca)
- **Description:** Full-featured microservices-oriented web platform for intelligent catalog management with multilingual support (EN/ES/PT) and Multimodal Artificial Intelligence.
  - **Backend Architecture & Security:** FastAPI 0.115 and SQLAlchemy 2.0 backend structured in layered services, JWT authentication with `HttpOnly` cookies, row-level security (RLS), and Nginx reverse proxy with rate limiting and security headers.
  - **Relational Data Modeling:** PostgreSQL 16 database with automated schema migrations and versioning via Alembic.
  - **Generative AI & Metadata Extraction:** Integration with Google Gemini 1.5 Flash Vision API for book cover recognition, text extraction, and automated reconciliation with Open Library and Google Books APIs.
  - **DevOps & Testing:** Fully containerized setup with Docker Compose (backend, Next.js 14 frontend, PostgreSQL, Nginx, MinIO/S3), backed by automated unit/integration test suites with `pytest` and code coverage.
- **Stack:** Python (FastAPI, SQLAlchemy, Alembic, Pydantic, Pytest), PostgreSQL, Docker Compose, Nginx, Google Gemini API, Next.js 14, TypeScript.
- [Explore repository →](https://github.com/jdespinell/biblioteca)

#### 3. [Newton Polyhedron — Convex Optimization, 3D Geometry & Scientific Computing](https://github.com/jdespinell/Newton_polyhedro)
- **Description:** Scientific computing Python tool for metric analysis, calculation, and interactive 3D visualization of **Newton Polyhedra** and **Convex Hulls** in $\mathbb{R}^3$.
  - **Geometric Algorithms & Optimization:** Determines extreme vertices and triangular facets (*simplices*) from discrete point clouds via `scipy.spatial.ConvexHull`.
  - **Support Hyperplanes & Normal Vectors:** Computes inward-directed normal vectors for every facet — fundamental for support hyperplane analysis, valuations, and linear/convex optimization problems.
  - **Exact Spatial Metrics:** Analytical computation of Euclidean volume, surface area, and spatial coordinates.
  - **Interactive 3D Visualization:** Rendered with `matplotlib 3D` supporting interactive rotation and zoom.
- **Stack:** Python, SciPy (`scipy.spatial.ConvexHull`), NumPy, Matplotlib 3D.
- [Explore repository →](https://github.com/jdespinell/Newton_polyhedro)

#### 4. [MedFamilia — PWA App for Intelligent Health Data Extraction with AI](https://github.com/jdespinell/medfamilia)
- **Description:** Responsive mobile-first PWA application designed to centralize and track family medical routines, leveraging multimodal AI extraction agents.
  - **Computer Vision & OCR with Gemini:** Automated reading and structuring of printed/handwritten medical orders and exam results, turning complex medical jargon into clear summaries.
  - **Cloud Integrations:** Native synchronization with Google Calendar API and automated push notification services (Web Push / Service Worker).
  - **Containerization:** Containerized deployment with Docker Compose.
- **Stack:** Node.js, Express, React, TypeScript, Google Gemini API, Google Cloud APIs, Docker Compose.
- [Explore repository →](https://github.com/jdespinell/medfamilia)

#### 🎯 Financial Sector & Business Alignment
- **Credit Risk & Corporate Ratings:** The **Cluster_B3** project demonstrates end-to-end expertise working with financial statements, balance sheets, and solvency/leverage ratios to segment corporate entities into risk and quality profiles — methodology directly transferable to *Risk Rating* models for large corporations and securitization portfolios (FIDCs).
- **Forward-Looking Provisions:** Time series modeling with ETS smoothing isolates structural trends from cyclical fluctuations, a foundational concept for Expected Loss estimation and forward-looking provisions under economic forecasts.
- **Production-Ready Engineering:** Hands-on experience with **FastAPI, PostgreSQL, Docker, and clean Python pipelines** ensures machine learning and quantitative models are delivered as reliable microservices and production APIs ready for business consumption.

---

<br>

<a id="-português"></a>
## 🇧🇷 Português

Cientista de Dados e Modelador Quantitativo com sólida formação acadêmica (**Doutorado e Mestrado em Matemática Pura / Teoria de Singularidades**) e experiência prática no desenvolvimento de pipelines analíticos e arquitetura de software.

Minha transição para a Ciência de Dados e o Setor Financeiro (Bancos, Seguradoras e Mercado de Capitais) une o **rigor analítico da matemática avançada** (álgebra, geometria convexa, inferência e modelagem estatística) à **capacidade de engenharia de software** (criação de pipelines de dados modulares, modelagem relacional SQL, APIs com FastAPI, conteinerização com Docker e integração de soluções com Inteligência Artificial Generativa).

- 🛠️ **Stack principal:** Python (Pandas, Scikit-Learn, Statsmodels, SciPy, FastAPI, SQLAlchemy), SQL (PostgreSQL), Docker, Git.
- 📊 **Especialidades:** Modelagem quantitativa, análise de risco e ratings fundamentalistas, séries temporais (modelos ETS/tendência estrutural), clusterização e redução de dimensionalidade (K-Means, PCA), otimização matemática e LLMs.
- 🎓 **Formação:** Doutorado e Mestrado em Matemática (pesquisa com forte ênfase em geometria, álgebra e estruturas complexas).
- 📍 Baseado no Brasil | Disponível para atuação presencial ou remota.

### 🚀 Projetos em Destaque

#### 1. [Cluster_B3 — Pipeline Quantitativo de Segmentação e Modelagem Temporal de Empresas da B3](https://github.com/jdespinell/Cluster_B3)
- **Descrição:** Sistema end-to-end de análise quantitativa e Machine Learning não supervisionado desenvolvido para a limpeza, modelagem temporal e segmentação fundamentalista de **372 empresas listadas na bolsa brasileira (B3)** com base em seus balanços históricos (2017–2026).
  - **Tratamento Robusto de Dados:** Imputação setorial por mediana e winsorização (1%-99%) para tratamento de assimetrias e outliers de mercado.
  - **Séries Temporais com Holt Damped ETS:** Extração de nível estrutural e tendência suavizada de 10 anos de histórico, eliminando ruídos conjunturais de curto prazo.
  - **Engenharia de Fatores e Ratings:** Construção de 5 scores compostos (Qualidade, Valor/Múltiplos relativos ao setor, Crescimento, Saúde Financeira/Solvência e Dividendos).
  - **Clusterização e Redução de Dimensionalidade:** Normalização com `RobustScaler`, redução via PCA e segmentação ótima com K-Means ($k=5$), validada por métodos de Silhueta e Cotovelo, gerando arquetipos de investimento (*Quality Growth, Value, Dividend Aristocrats, etc.*).
  - **Resultados e Visualização:** Geração automatizada de matrizes de correlação, gráficos de radar, boxplots setoriais, rankings ponderados e relatório executivo interativo em HTML.
- **Stack:** Python (Pandas, Scikit-Learn, Statsmodels, NumPy, Matplotlib, Seaborn), PCA, K-Means, Holt Damped ETS, HTML/CSS.
- [Acessar repositório →](https://github.com/jdespinell/Cluster_B3)

#### 2. [Biblioteca — Plataforma SaaS com Arquitetura Backend, Modelagem SQL e IA](https://github.com/jdespinell/biblioteca)
- **Descrição:** Aplicação completa em arquitetura de microsserviços voltada para gerenciamento inteligente de acervos com suporte internacional (ES/EN/PT) e integração de Inteligência Artificial Multimodal.
  - **Arquitetura e Segurança:** Backend em FastAPI 0.115 e SQLAlchemy 2.0, estruturado em camadas de serviço, autenticação JWT com cookies `HttpOnly`, controle de acesso (RLS) e proxy reverso com Nginx (rate limiting e cabeçalhos de segurança).
  - **Modelagem Relacional de Dados:** Banco de dados PostgreSQL 16 com controle de versões de schema via migrações automáticas no Alembic.
  - **IA Generativa e Extração de Metadados:** Integração com a API Google Gemini 1.5 Flash Vision para reconhecimento automatizado de capas, extração de texto e reconciliação com Open Library / Google Books.
  - **Deploy & DevOps:** Ambiente totalmente conteinerizado com Docker Compose (backend, frontend Next.js 14, PostgreSQL, Nginx e MinIO/S3), incluindo bateria de testes automatizados com `pytest` e cobertura de código.
- **Stack:** Python (FastAPI, SQLAlchemy, Alembic, Pydantic, Pytest), PostgreSQL, Docker Compose, Nginx, Google Gemini API, Next.js 14, TypeScript.
- [Acessar repositório →](https://github.com/jdespinell/biblioteca)

#### 3. [Newton Polyhedron — Otimização Convexa, Geometria 3D e Computação Científica](https://github.com/jdespinell/Newton_polyhedro)
- **Descrição:** Ferramenta de computação científica desenvolvida em Python para cálculo, análise métrica e visualização tridimensional interativa de **Poliedros de Newton** e **Envoltórias Convexas (Convex Hulls)** em $\mathbb{R}^3$.
  - **Algoritmos Geométricos e Otimização:** Determinação de vértices extremos e faces triangulares (*simplices*) a partir de conjuntos discretos de pontos via `scipy.spatial.ConvexHull`.
  - **Hiperplanos de Suporte e Normais:** Cálculo vetorial das normais interiores direcionadas de cada faceta — base matemática essencial para análise de hiperplanos de suporte, valorações e problemas de otimização linear/convexa.
  - **Métricas Espaciais Exatas:** Determinação analítica de volume euclidiano, área de superfície e coordenadas espaciais.
  - **Visualização 3D Interativa:** Renderização com `matplotlib 3D` com manipulação interativa de rotação e zoom.
- **Stack:** Python, SciPy (`scipy.spatial.ConvexHull`), NumPy, Matplotlib 3D.
- [Acessar repositório →](https://github.com/jdespinell/Newton_polyhedro)

#### 4. [MedFamilia — Aplicação PWA de Gestão e Extração Inteligente com IA](https://github.com/jdespinell/medfamilia)
- **Descrição:** Aplicação web responsiva (PWA/Mobile-First) projetada para centralização e acompanhamento de rotinas médicas familiares, incorporando agentes de extração de dados e IA generativa.
  - **Visão Computacional e OCR com Gemini:** Leitura e estruturação automática de pedidos e laudos médicos a partir de imagens/PDFs, traduzindo resultados complexos em resumos acessíveis ao usuário.
  - **Integrações em Nuvem:** Sincronização automática com a API do Google Calendar e mensageria de notificações push nativas (Web Push / Service Worker).
  - **Conteinerização:** Deploy simplificado com Docker Compose.
- **Stack:** Node.js, Express, React, TypeScript, Google Gemini API, Google Cloud APIs, Docker Compose.
- [Acessar repositório →](https://github.com/jdespinell/medfamilia)

#### 🎯 Conexão com o Setor Financeiro e Soluções de Negócio
- **Risco de Crédito & Ratings Corporativos:** O projeto **Cluster_B3** ilustra a capacidade de trabalhar com múltiplos demonstrativos financeiros, balanços patrimoniais e índices de solvência/alavancagem para classificar empresas em arquetipos de qualidade e risco — metodologia diretamente transponível para modelos de *Risk Rating* de grandes empresas e carteiras de recebíveis (FIDCs).
- **Projeções e Forward-Looking:** A modelagem temporal com decomposição e suavização (ETS) permite antecipar tendências estruturais contra variações de ciclo, conceito chave para cálculo de perda esperada (*Expected Loss*) e provisões com perspectivas econômicas futuras.
- **Engenharia de Dados e Produção:** A experiência com **FastAPI, PostgreSQL, Docker e pipelines em Python** garante que os modelos analíticos não fiquem apenas em notebooks, mas sejam estruturados como microsserviços e APIs robustas, prontas para consumo por áreas de negócio e sistemas transacionais.

---

<br>

<a id="-español"></a>
## 🇪🇸 Español

Científico de Datos y Modelador Cuantitativo con sólida formación académica (**Doctorado y Maestría en Matemáticas Puras / Teoría de Singularidades**) y experiencia práctica en el desarrollo de pipelines analíticos y arquitectura de software.

Mi transición hacia la Ciencia de Datos y el Sector Financiero (Banca, Aseguradoras y Mercado de Capitales) une el **rigor analítico de la matemática avanzada** (álgebra, geometría convexa, inferencia y modelado estadístico) con la **capacidad de ingeniería de software** (creación de pipelines de datos modulares, modelado relacional SQL, APIs con FastAPI, contenerización con Docker e integración de soluciones con Inteligencia Artificial Generativa).

- 🛠️ **Stack principal:** Python (Pandas, Scikit-Learn, Statsmodels, SciPy, FastAPI, SQLAlchemy), SQL (PostgreSQL), Docker, Git.
- 📊 **Especialidades:** Modelado cuantitativo, análisis de riesgo y ratings fundamentalistas, series de tiempo (modelos ETS/tendencia estructural), clusterización y reducción de dimensionalidad (K-Means, PCA), optimización matemática y LLMs.
- 🎓 **Formación:** Doctorado y Maestría en Matemáticas (investigación con fuerte énfasis en geometría, álgebra y estructuras complejas).
- 📍 Basado en Brasil | Disponible para modalidad presencial o remota.

### 🚀 Proyectos Destacados

#### 1. [Cluster_B3 — Pipeline Cuantitativo de Segmentación y Modelado Temporal de Empresas de la B3](https://github.com/jdespinell/Cluster_B3)
- **Descripción:** Sistema end-to-end de análisis cuantitativo y Machine Learning no supervisado desarrollado para la limpieza, modelado temporal y segmentación fundamentalista de **372 empresas cotizadas en la bolsa brasileña (B3)** a partir de sus balances históricos (2017–2026).
  - **Tratamiento Robusto de Datos:** Imputación sectorial por mediana y winsorización (1%-99%) para mitigar asimetrías y valores atípicos del mercado.
  - **Series de Tiempo con Holt Damped ETS:** Extracción de nivel estructural y tendencia suavizada a lo largo de 10 años de histórico, eliminando ruidos coyunturales de corto plazo.
  - **Ingeniería de Factores y Ratings:** Construcción de 5 scores compuestos (Calidad, Valor/Múltiplos relativos a la industria, Crecimiento, Salud Financiera/Solvencia y Dividendos).
  - **Clusterización y Reducción de Dimensionalidad:** Escalado con `RobustScaler`, reducción con PCA y segmentación óptima con K-Means ($k=5$), validada por métodos de Silueta y Codo para identificar arquetipos de inversión (*Quality Growth, Value, Dividend Aristocrats, etc.*).
  - **Visualización y Reportes Ejecutivos:** Generación automatizada de matrices de correlación, gráficos de radar, boxplots sectoriales, rankings ponderados y reporte ejecutivo interactivo en HTML.
- **Stack:** Python (Pandas, Scikit-Learn, Statsmodels, NumPy, Matplotlib, Seaborn), PCA, K-Means, Holt Damped ETS, HTML/CSS.
- [Acceder al repositorio →](https://github.com/jdespinell/Cluster_B3)

#### 2. [Biblioteca — Plataforma SaaS con Arquitectura Backend, Modelado SQL e IA](https://github.com/jdespinell/biblioteca)
- **Descripción:** Aplicación completa en arquitectura de microservicios diseñada para la gestión inteligente de colecciones con soporte multilenguaje (ES/EN/PT) e integración de Inteligencia Artificial Multimodal.
  - **Arquitectura y Seguridad:** Backend en FastAPI 0.115 y SQLAlchemy 2.0 con diseño en capas, autenticación JWT con cookies `HttpOnly`, control de acceso (RLS) y proxy inverso con Nginx (rate limiting y cabeceras de seguridad).
  - **Modelado Relacional de Datos:** Base de datos PostgreSQL 16 con versionado y migraciones de esquema automáticas mediante Alembic.
  - **IA Generativa y Extracción de Metadatos:** Integración con la API Google Gemini 1.5 Flash Vision para reconocimiento visual de portadas, extracción de texto y conciliación automática con Open Library y Google Books.
  - **DevOps y Pruebas:** Entorno 100% contenerizado con Docker Compose (backend, frontend Next.js 14, PostgreSQL, Nginx, MinIO/S3) y suite de pruebas automatizadas con `pytest` y reporte de cobertura.
- **Stack:** Python (FastAPI, SQLAlchemy, Alembic, Pydantic, Pytest), PostgreSQL, Docker Compose, Nginx, Google Gemini API, Next.js 14, TypeScript.
- [Acceder al repositorio →](https://github.com/jdespinell/biblioteca)

#### 3. [Newton Polyhedron — Optimización Convexa, Geometría 3D y Computación Científica](https://github.com/jdespinell/Newton_polyhedro)
- **Descripción:** Herramienta de computación científica desarrollada en Python para cálculo métrico, análisis y visualización tridimensional interactiva de **Poliedros de Newton** y **Envolventes Convexas (Convex Hulls)** en $\mathbb{R}^3$.
  - **Algoritmos Geométricos y Optimización:** Determinación de vértices extremos y facetas triangulares (*simplices*) a partir de nubes de puntos mediante `scipy.spatial.ConvexHull`.
  - **Hiperplanos de Soporte y Normales:** Cálculo vectorial de las normales interiores directas de cada faceta — base matemática esencial para análisis de hiperplanos de soporte, valoraciones y problemas de optimización lineal y convexa.
  - **Métricas Espaciales Exactas:** Cálculo analítico de volumen euclidiano, área superficial y coordenadas espaciales.
  - **Visualización 3D Interactiva:** Renderizado con `matplotlib 3D` con rotación y zoom interactivos.
- **Stack:** Python, SciPy (`scipy.spatial.ConvexHull`), NumPy, Matplotlib 3D.
- [Acceder al repositorio →](https://github.com/jdespinell/Newton_polyhedro)

#### 4. [MedFamilia — Aplicación PWA de Gestión y Extracción Inteligente con IA](https://github.com/jdespinell/medfamilia)
- **Descripción:** Aplicación web responsiva (PWA/Mobile-First) para la centralización y seguimiento de citas médicas familiares, integrando agentes de extracción de datos con IA generativa.
  - **Visión Computacional y OCR con Gemini:** Lectura y estructuración automática de órdenes y resultados médicos desde imágenes/PDFs, traduciendo diagnósticos complejos a resúmenes comprensibles.
  - **Integraciones Cloud:** Sincronización automática con Google Calendar API y notificaciones push nativas para móviles (Web Push / Service Worker).
  - **Contenerización:** Despliegue simplificado mediante Docker Compose.
- **Stack:** Node.js, Express, React, TypeScript, Google Gemini API, Google Cloud APIs, Docker Compose.
- [Acceder al repositorio →](https://github.com/jdespinell/medfamilia)

#### 🎯 Conexión con el Sector Financiero y Soluciones de Negocio
- **Riesgo de Crédito y Ratings Corporativos:** El proyecto **Cluster_B3** demuestra capacidad para procesar múltiples estados contables, balances y ratios de apalancamiento/solvencia para clasificar empresas en perfiles de calidad y riesgo — metodología análoga a modelos de *Risk Rating* para grandes empresas y carteras de securitización (FIDCs).
- **Proyecciones y Metodologías Forward-Looking:** El modelado temporal con suavizado ETS aísla tendencias estructurales de fluctuaciones cíclicas, principio clave para la estimación de Pérdida Esperada (*Expected Loss*) y provisiones con perspectivas macroeconómicas futuras.
- **Ingeniería de Datos y Puesta en Producción:** El dominio de **FastAPI, PostgreSQL, Docker y pipelines modulares en Python** asegura que los modelos no se queden en libretas experimentales, sino que se desplieguen como microservicios robustos listos para el consumo de áreas de negocio.

---