cat > README.md <<'EOF'
# Cybersecurity Labs

Este repositorio es un registro personal de los laboratorios que voy realizando mientras avanzo en mi formación en ciberseguridad.

Actualmente estaré resolviendo y documentando los ejercicios de **PortSwigger Web Security Academy**, principalmente enfocados en seguridad web, análisis de requests y responses, uso de Burp Suite y comprensión práctica de vulnerabilidades.

La idea no es solo llegar al resultado, sino dejar registro del proceso: qué probé, qué respuesta obtuve, qué significaba técnicamente, cómo se podría prevenir la vulnerabilidad y qué aprendí en cada ejercicio.

## Mi objetivo

Mantener un historial claro de mi avance práctico y construir un portafolio técnico que refleje mi forma de analizar, probar y documentar laboratorios de ciberseguridad web.

No busco que esto sea solo una lista de respuestas, sino una bitácora técnica donde pueda ver mi progreso, corregir errores, mejorar mis explicaciones y demostrar práctica real con herramientas como Burp Suite.

## Plataforma principal

Por ahora, el foco principal de este repositorio será:

- **PortSwigger Web Security Academy**

La idea es ir resolviendo sus laboratorios de forma progresiva y documentar cada ejercicio con mi propio análisis.

## Laboratorios documentados

| Plataforma | Categoría | Laboratorio |
|---|---|---|
| PortSwigger Web Security Academy | SQL Injection | [Lab 01 - Login Bypass](portswigger-academy/SQLI/Lab1/01-login-bypass.md) |

## Temas que iré documentando

- SQL Injection
- Authentication bypass
- Uso de Burp Suite
- Burp Repeater
- Análisis de tráfico HTTP
- Requests y responses
- Códigos de estado HTTP
- Cookies y sesiones
- Vulnerabilidades web
- Evidencias de laboratorio
- Mitigaciones y buenas prácticas defensivas

## Estructura del repositorio

```text
cybersecurity-labs/
├── README.md
└── portswigger-academy/
    └── SQLI/
        └── Lab1/
            ├── 01-login-bypass.md
            └── images/
                └── response_302_admin.png
