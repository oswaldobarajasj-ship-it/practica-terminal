Resumen de avance: Curso Full Stack (CRM tipo Kanban)

Copia todo lo que sigue y pégalo al inicio de la nueva conversación.

Perfil del estudiante
Nombre: Oswaldo
Nivel: empieza de cero, quiere ir paso a paso sin descuidar conceptos ni detalles.
Dedicación: 2 horas diarias, 6 días a la semana (12 h semanales); el día 7 es descanso.
Meta: construir un CRM profesional tipo Kanban (tablero con embudo de ventas, contactos, empresas, notas, tareas, login con roles y dashboard).
Idioma: español.
Stack del proyecto
Frontend: HTML, CSS, JavaScript puro y luego React + Tailwind CSS
Backend: Node.js + Express (más adelante TypeScript)
Base de datos: PostgreSQL
Herramientas: Git/GitHub, VS Code, Postman o Thunder Client
Despliegue: Vercel (frontend) y Render o Railway (backend y base de datos)
Plan general (6 a 8 meses)
Fase	Duración aprox.
0. Preparación	1 semana
1. HTML, CSS y JavaScript	6 semanas
2. React + Tailwind	4-5 semanas
3. Node + Express	4 semanas
4. PostgreSQL	3-4 semanas
5. Autenticación y seguridad	3 semanas
6. Funcionalidades profesionales	5-6 semanas
7. Despliegue y calidad	3 semanas
Método de enseñanza acordado
Explicar cada concepto antes de usarlo, con analogías y ejemplos.
Dejar un ejercicio práctico y preguntas de comprobación en cada paso.
Oswaldo debe responder con sus propias palabras (no solo pegar la salida de la terminal).
Corregir y precisar sus respuestas con amabilidad, señalando lo que está bien y lo que se puede afinar.
Avanzar solo cuando el concepto quede claro.
No asumir que ya sabe algo: él pidió empezar de cero aunque ya tenga las herramientas instaladas.
Fase 0: COMPLETADA

Entorno: VS Code, Node.js, npm y Git instalados y verificados (node -v, npm -v, git --version). Cuenta de GitHub creada: oswaldobarajasj-ship-it.

Conceptos dominados:

Node.js: ejecuta JavaScript fuera del navegador; incluye npm.
Terminal: pwd, ls, cd, cd .. (sube un nivel a la carpeta padre), mkdir, ni/touch, cat, rm, cls. Usa PowerShell en Windows.
Git: init, status, add, commit, log, push. Entiende que add solo prepara y commit guarda la “foto”.
Estados de un archivo: untracked (Git no lo conoce), modified (conocido y cambiado), staged (preparado con add).
Git vs GitHub: Git lleva el historial local; GitHub es el sitio donde se respalda y comparte.
Remoto: origin es el nombre de la dirección remota; -u enlaza la rama local con la remota.
Web: cliente (inicia y pide) y servidor (escucha, procesa y responde), HTTP, petición y respuesta.
Métodos HTTP: GET (pedir), POST (crear), PUT (modificar), DELETE (borrar).
Códigos de estado: 200 (bien), 404 (no encontrado), 500 (error del servidor).
DevTools: pestaña Network (F12); vio que la primera petición fue GET con código 200.

Repositorio de práctica: https://github.com/oswaldobarajasj-ship-it/practica-terminal, con rama main y 3 commits subidos correctamente.

Puntos a reforzar (detectados)
Distinguir bien que git add prepara y git commit guarda.
Recordar que los comandos de Git solo funcionan dentro de la carpeta del repositorio.
Al escribir comandos, verificar que la ventana activa sea la terminal y no el chat.
Siguiente paso: Fase 1, HTML

Empezar por la estructura de una página HTML (etiquetas, <head> y <body>), y crear la carpeta del proyecto crm-kanban con su repositorio Git, un archivo PROGRESO.md y un primer index.html.