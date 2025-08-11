<p align="center">
	<img src="../public/img/header-animated.svg" alt="ASDU header" width="100%" />
</p>

<div align="center" style="display:flex;justify-content:center;">
	<!-- Tarjeta del logo con borde, radio y sombra sutil -->
		<div style="background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0)); border:1px solid rgba(250,204,21,0.22); padding:18px 28px; border-radius:18px; box-shadow:0 12px 24px rgba(234,179,8,0.10), 0 0 14px rgba(250,204,21,0.18), 0 0 26px rgba(245,158,11,0.12); display:inline-block;">
			<div style="position:relative; width:210px; height:210px;">
			<!-- Anillo animado debajo -->
				<img src="../public/img/asdu-logo-bounce.svg" alt="Anillo animado" style="position:absolute; inset:0; width:210px; height:210px; z-index:1; opacity:.95;" />
			<!-- Logo original encima -->
				<!-- Logo con glow amarillo y latido suave usando filtro SVG -->
				<svg width="136" height="136" viewBox="0 0 136 136" style="position:absolute; top:50%; left:50%; transform:translate(-50%, -50%); z-index:2;">
					<defs>
						<filter id="pulseGlow" x="-40%" y="-40%" width="180%" height="180%">
							<!-- sombra sutil para relieve -->
							<feDropShadow dx="0" dy="1" stdDeviation="0.7" flood-color="#000000" flood-opacity="0.32" result="shadow"/>
							<!-- blur del alfa del logo -->
							<feGaussianBlur in="SourceAlpha" stdDeviation="2" result="blur">
								<animate attributeName="stdDeviation" values="2;3.2;2" dur="3s" repeatCount="indefinite"/>
							</feGaussianBlur>
							<!-- color amarillo aplicado al blur -->
							<feFlood flood-color="#FACC15" flood-opacity="0.22" result="flood">
								<animate attributeName="flood-opacity" values="0.18;0.30;0.18" dur="3s" repeatCount="indefinite"/>
							</feFlood>
							<feComposite in="flood" in2="blur" operator="in" result="coloredBlur"/>
							<!-- mezcla: sombra + glow + original -->
							<feMerge>
								<feMergeNode in="shadow"/>
								<feMergeNode in="coloredBlur"/>
								<feMergeNode in="SourceGraphic"/>
							</feMerge>
						</filter>
					</defs>
					<image href="../public/img/asdunewlogo.png" x="0" y="0" width="136" height="136" style="image-rendering:auto;" filter="url(#pulseGlow)"/>
				</svg>
		</div>
	</div>
</div>

<p align="center">
	<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=2800&pause=900&color=36BCF7&center=true&vCenter=true&width=620&lines=Aprende%2C+construye+y+colabora;Software%2C+Datos%2C+IA+y+Cloud;Comunidad+abierta+y+orientada+a+proyectos" alt="ASDU typing" />
</p>

<p align="center" style="margin-top:8px;">
	<img alt="PRs welcome" src="https://img.shields.io/badge/PRs-welcome-10b981?style=for-the-badge&logo=github" />
	<img alt="Open Source" src="https://img.shields.io/badge/Hecho%20en-Comunidad-3b82f6?style=for-the-badge" />
	<img alt="Project Based" src="https://img.shields.io/badge/Aprendizaje-por%20proyectos-ec4899?style=for-the-badge" />
</p>

---

## ¿Qué es ASDU?

Somos un círculo de estudios donde aprendemos haciendo: pequeños retos, talleres prácticos, y proyectos colaborativos en tecnologías de software, datos, IA y cloud. Nuestro foco es que te lleves algo útil y publicable en cada sesión.

### Lo que hacemos
- Talleres prácticos y katas técnicas con mentores de la comunidad.
- Proyectos open-source guiados (desde idea hasta deploy).
- Reading groups y discusiones de papers/blogs.
- Charlas relámpago (lightning talks) y demos.

---

## Áreas de estudio

- Web y APIs (JavaScript/TypeScript, React, Node.js)
- Datos y BI (Python, SQL, Pandas, Power BI)
- IA/ML (scikit-learn, PyTorch/TensorFlow, MLOps)
- DevOps y Cloud (Docker, Kubernetes, CI/CD, AWS/Azure/GCP)

<div align="center" style="display:flex; gap:8px; flex-wrap:wrap; justify-content:center;">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=for-the-badge" />
	<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=for-the-badge" />
	<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge" />
	<img src="https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=fff&style=for-the-badge" />
	<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=for-the-badge" />
	<img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=for-the-badge" />
	<img src="https://img.shields.io/badge/Cloud-AWS%20%7C%20Azure%20%7C%20GCP-333?logo=cloudflare&logoColor=fff&style=for-the-badge" />
</div>

---

## Cómo participar

1) Explora los repos de la organización y mira los issues etiquetados como `good first issue` o `help wanted`.

2) Únete a una sesión de estudio: practicamos en vivo con problemas reales y code reviews.

3) Propón un tema o proyecto: abre un issue en el repo correspondiente y cuéntanos el objetivo y alcance.

4) Comparte tu demo o aprendizaje: un gist, un PR o una mini charla.

> No necesitas permiso para empezar. Haz un fork, crea una rama y envía tu PR. ¡Te ayudamos en el camino!

---

## Repositorios y proyectos destacados
<p align="center" style="margin:-6px 0 10px 0;">
	<img src="../public/img/section-underline.svg" alt="underline" width="600" />
</p>

<p align="center">
	<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=16&duration=2600&pause=1200&color=7C4DFF&center=true&vCenter=true&width=500&lines=Explora%20repos%20activos;Contribuye%20con%20un%20%22good%20first%20issue%22;Presenta%20tu%20demo%20en%20ASDU" alt="Projects CTA" />
</p>

<details open style="max-width: 460px; margin: 0 auto 12px;">
	<summary>
		🗂️ Noticias_Tech_ASDU — noticias y tendencias tecnológicas
			<span style="margin-left:8px;">
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" height="16" style="vertical-align:middle; filter:brightness(1.2);"/>
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-plain.svg" alt="GitHub Actions" height="16" style="vertical-align:middle; filter:invert(1) brightness(2);"/>
		</span>
	</summary>
	<div align="center" style="margin:10px 0 4px; display:inline-block; width:min(100%, 420px);">
		<a href="https://github.com/ASDU0/Noticias_Tech_ASDU" title="Noticias_Tech_ASDU" style="display:block;">
			<svg viewBox="0 0 420 236.25" width="100%" role="img" aria-label="OG Noticias_Tech_ASDU con marco" xmlns="http://www.w3.org/2000/svg">
				<defs>
					<linearGradient id="g1" x1="0%" y1="0%" x2="100%" y2="0%">
						<stop offset="0%" stop-color="#36BCF7"/>
						<stop offset="50%" stop-color="#7C4DFF"/>
						<stop offset="100%" stop-color="#36BCF7"/>
					</linearGradient>
					<clipPath id="clip1">
						<rect x="6" y="6" width="408" height="224.25" rx="14" ry="14"/>
					</clipPath>
					<filter id="glow1" x="-20%" y="-20%" width="140%" height="140%">
						<feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#36BCF7" flood-opacity="0.35"/>
					</filter>
					<filter id="glow1soft" x="-20%" y="-20%" width="140%" height="140%">
						<feDropShadow dx="0" dy="0" stdDeviation="4" flood-color="#7C4DFF" flood-opacity="0.35"/>
					</filter>
					<style>
						.preview{transition:transform .25s ease, filter .25s ease; transform-box:fill-box; transform-origin:50% 50%;}
						.frame{transition:filter .25s ease, opacity .25s ease;}
						svg:hover .preview{transform:scale(1.02); filter:url(#glow1);}
						svg:hover .frame{filter:url(#glow1soft); opacity:.98;}
					</style>
				</defs>
				<rect x="1.5" y="1.5" width="417" height="233.25" rx="16" ry="16" fill="rgba(0,0,0,0.15)" stroke="url(#g1)" stroke-width="2.5" stroke-dasharray="12 8" class="frame"/>
				<image href="https://opengraph.githubassets.com/1/ASDU0/Noticias_Tech_ASDU" x="6" y="6" width="408" height="224.25" clip-path="url(#clip1)" class="preview"/>
				<rect x="6" y="6" width="408" height="224.25" rx="14" ry="14" fill="none" stroke="url(#g1)" stroke-width="1.2" class="frame"/>
			</svg>
		</a>
	</div>
	<p align="center" style="margin:6px 0 2px;">
		<img src="https://img.shields.io/github/languages/top/ASDU0/Noticias_Tech_ASDU?style=flat-square" />
		<img src="https://img.shields.io/github/issues/ASDU0/Noticias_Tech_ASDU?style=flat-square" />
		<img src="https://img.shields.io/github/last-commit/ASDU0/Noticias_Tech_ASDU?style=flat-square" />
		<img src="https://img.shields.io/github/issues-search?query=repo%3AASDU0/Noticias_Tech_ASDU+is%3Aissue+is%3Aopen+label%3A%22good%20first%20issue%22&label=good%20first%20issues&style=flat-square" />
	</p>
	<p align="center" style="margin:2px 0 10px;">
		<img src="https://img.shields.io/badge/Stack-Python%20%7C%20Scraping%20%7C%20Automation-7C4DFF?style=flat-square" />
	</p>
	<p align="center" style="margin:4px 0 8px;">
		<img src="https://contrib.rocks/image?repo=ASDU0/Noticias_Tech_ASDU" alt="Contribuidores" style="max-width:100%; height:auto; border-radius:8px;" />
	</p>
</details>

<details open style="max-width: 460px; margin: 0 auto 12px;">
	<summary>
		📅 schedule-project — planificación de sesiones
			<span style="margin-left:8px;">
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" height="16" style="vertical-align:middle; filter:brightness(1.2);"/>
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" height="16" style="vertical-align:middle; filter:invert(1) brightness(2);"/>
		</span>
	</summary>
	<div align="center" style="margin:10px 0 4px; display:inline-block; width:min(100%, 420px);">
		<a href="https://github.com/ASDU0/schedule-project" title="schedule-project" style="display:block;">
			<svg viewBox="0 0 420 236.25" width="100%" role="img" aria-label="OG schedule-project con marco" xmlns="http://www.w3.org/2000/svg">
				<defs>
					<linearGradient id="g2" x1="0%" y1="0%" x2="100%" y2="0%">
						<stop offset="0%" stop-color="#36BCF7"/>
						<stop offset="50%" stop-color="#7C4DFF"/>
						<stop offset="100%" stop-color="#36BCF7"/>
					</linearGradient>
					<clipPath id="clip2">
						<rect x="6" y="6" width="408" height="224.25" rx="14" ry="14"/>
					</clipPath>
					<filter id="glow2" x="-20%" y="-20%" width="140%" height="140%">
						<feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#36BCF7" flood-opacity="0.35"/>
					</filter>
					<filter id="glow2soft" x="-20%" y="-20%" width="140%" height="140%">
						<feDropShadow dx="0" dy="0" stdDeviation="4" flood-color="#7C4DFF" flood-opacity="0.35"/>
					</filter>
					<style>
						.preview{transition:transform .25s ease, filter .25s ease; transform-box:fill-box; transform-origin:50% 50%;}
						.frame{transition:filter .25s ease, opacity .25s ease;}
						svg:hover .preview{transform:scale(1.02); filter:url(#glow2);}
						svg:hover .frame{filter:url(#glow2soft); opacity:.98;}
					</style>
				</defs>
				<rect x="1.5" y="1.5" width="417" height="233.25" rx="16" ry="16" fill="rgba(0,0,0,0.15)" stroke="url(#g2)" stroke-width="2.5" stroke-dasharray="12 8" class="frame"/>
				<image href="https://opengraph.githubassets.com/1/ASDU0/schedule-project" x="6" y="6" width="408" height="224.25" clip-path="url(#clip2)" class="preview"/>
				<rect x="6" y="6" width="408" height="224.25" rx="14" ry="14" fill="none" stroke="url(#g2)" stroke-width="1.2" class="frame"/>
			</svg>
		</a>
	</div>
	<p align="center" style="margin:6px 0 2px;">
		<img src="https://img.shields.io/github/languages/top/ASDU0/schedule-project?style=flat-square" />
		<img src="https://img.shields.io/github/issues/ASDU0/schedule-project?style=flat-square" />
		<img src="https://img.shields.io/github/last-commit/ASDU0/schedule-project?style=flat-square" />
		<img src="https://img.shields.io/github/issues-search?query=repo%3AASDU0/schedule-project+is%3Aissue+is%3Aopen+label%3A%22good%20first%20issue%22&label=good%20first%20issues&style=flat-square" />
	</p>
	<p align="center" style="margin:2px 0 10px;">
		<img src="https://img.shields.io/badge/Stack-TypeScript%20%7C%20Node.js%20%7C%20API-36BCF7?style=flat-square" />
	</p>
	<p align="center" style="margin:4px 0 8px;">
		<img src="https://contrib.rocks/image?repo=ASDU0/schedule-project" alt="Contribuidores" style="max-width:100%; height:auto; border-radius:8px;" />
	</p>
</details>

<details open style="max-width: 460px; margin: 0 auto 12px;">
	<summary>
		🌐 New-Web-Page-ASDU — nueva web de la comunidad
			<span style="margin-left:8px;">
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" height="16" style="vertical-align:middle; filter:invert(1) brightness(2);"/>
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="TailwindCSS" height="16" style="vertical-align:middle;"/>
				<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-plain.svg" alt="CI/CD" height="16" style="vertical-align:middle; filter:invert(1) brightness(2);"/>
		</span>
	</summary>
	<div align="center" style="margin:10px 0 4px; display:inline-block; width:min(100%, 420px);">
		<a href="https://github.com/ASDU0/New-Web-Page-ASDU" title="New-Web-Page-ASDU" style="display:block;">
			<svg viewBox="0 0 420 236.25" width="100%" role="img" aria-label="OG New-Web-Page-ASDU con marco" xmlns="http://www.w3.org/2000/svg">
				<defs>
					<linearGradient id="g3" x1="0%" y1="0%" x2="100%" y2="0%">
						<stop offset="0%" stop-color="#36BCF7"/>
						<stop offset="50%" stop-color="#7C4DFF"/>
						<stop offset="100%" stop-color="#36BCF7"/>
					</linearGradient>
					<clipPath id="clip3">
						<rect x="6" y="6" width="408" height="224.25" rx="14" ry="14"/>
					</clipPath>
					<filter id="glow3" x="-20%" y="-20%" width="140%" height="140%">
						<feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#36BCF7" flood-opacity="0.35"/>
					</filter>
					<filter id="glow3soft" x="-20%" y="-20%" width="140%" height="140%">
						<feDropShadow dx="0" dy="0" stdDeviation="4" flood-color="#7C4DFF" flood-opacity="0.35"/>
					</filter>
					<style>
						.preview{transition:transform .25s ease, filter .25s ease; transform-box:fill-box; transform-origin:50% 50%;}
						.frame{transition:filter .25s ease, opacity .25s ease;}
						svg:hover .preview{transform:scale(1.02); filter:url(#glow3);}
						svg:hover .frame{filter:url(#glow3soft); opacity:.98;}
					</style>
				</defs>
				<rect x="1.5" y="1.5" width="417" height="233.25" rx="16" ry="16" fill="rgba(0,0,0,0.15)" stroke="url(#g3)" stroke-width="2.5" stroke-dasharray="12 8" class="frame"/>
				<image href="https://opengraph.githubassets.com/1/ASDU0/New-Web-Page-ASDU" x="6" y="6" width="408" height="224.25" clip-path="url(#clip3)" class="preview"/>
				<rect x="6" y="6" width="408" height="224.25" rx="14" ry="14" fill="none" stroke="url(#g3)" stroke-width="1.2" class="frame"/>
			</svg>
		</a>
	</div>
	<p align="center" style="margin:6px 0 2px;">
		<img src="https://img.shields.io/github/languages/top/ASDU0/New-Web-Page-ASDU?style=flat-square" />
		<img src="https://img.shields.io/github/issues/ASDU0/New-Web-Page-ASDU?style=flat-square" />
		<img src="https://img.shields.io/github/last-commit/ASDU0/New-Web-Page-ASDU?style=flat-square" />
		<img src="https://img.shields.io/github/issues-search?query=repo%3AASDU0/New-Web-Page-ASDU+is%3Aissue+is%3Aopen+label%3A%22good%20first%20issue%22&label=good%20first%20issues&style=flat-square" />
	</p>
	<p align="center" style="margin:2px 0 10px;">
		<img src="https://img.shields.io/badge/Stack-Next.js%20%7C%20Tailwind%20%7C%20CI%2FCD-3b82f6?style=flat-square" />
	</p>
	<p align="center" style="margin:4px 0 8px;">
		<img src="https://contrib.rocks/image?repo=ASDU0/New-Web-Page-ASDU" alt="Contribuidores" style="max-width:100%; height:auto; border-radius:8px;" />
	</p>
</details>

<p align="center" style="margin-top:6px;">
	<img src="https://img.shields.io/github/stars/ASDU0/.github?style=flat-square" alt="stars" />
	<img src="https://img.shields.io/github/issues/ASDU0/.github?style=flat-square" alt="issues" />
	<img src="https://img.shields.io/github/last-commit/ASDU0/.github?style=flat-square" alt="last commit" />
</p>

<!-- sección de logros eliminada a petición -->

## Recursos útiles

- Guía de Markdown en GitHub: https://docs.github.com/es/markdown
- Flujo de trabajo con Pull Requests: https://docs.github.com/es/pull-requests
- Buenas prácticas de issues: https://docs.github.com/es/issues/tracking-your-work-with-issues/about-issues

- Guía de contribución: ./../CONTRIBUTING.md
- Código de conducta: ./../CODE_OF_CONDUCT.md

---

<p align="center">
	<!-- Separador tipo ola -->
	<svg width="100%" height="90" viewBox="0 0 1200 90" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" role="img" aria-label="decorative wave">
		<path d="M0,60 C150,20 350,20 500,60 C650,100 850,100 1000,60 C1100,30 1150,30 1200,60 L1200,90 L0,90 Z" fill="#36BCF7" fill-opacity="0.15"></path>
		<path d="M0,70 C200,40 300,40 500,70 C700,100 900,100 1200,70 L1200,90 L0,90 Z" fill="#36BCF7" fill-opacity="0.10"></path>
		<path d="M0,80 C250,60 350,60 600,80 C850,100 950,100 1200,80 L1200,90 L0,90 Z" fill="#36BCF7" fill-opacity="0.08"></path>
	</svg>
	<br/>
	<sub>Hecho con ❤️ por la comunidad <strong>ASDU</strong>. ¿Ideas? Abre un issue y conversemos.</sub>
</p>