# Cybersecurity Labs

Este repositorio es mi registro personal de laboratorios prácticos mientras avanzo en ciberseguridad.

La idea es documentar los ejercicios que voy resolviendo, especialmente de **PortSwigger Web Security Academy**, dejando claro qué probé, qué respuesta obtuve, cómo interpreté el resultado y qué aprendí en el proceso.

No quiero que esto sea solo una lista de soluciones, sino una bitácora técnica para ordenar mi aprendizaje y construir un portafolio con evidencia real de práctica.

## Objetivo

Mantener un historial claro de mi progreso práctico en seguridad web, usando herramientas como **Burp Suite** para analizar requests, responses, sesiones, cookies, códigos HTTP y vulnerabilidades web.

## Plataforma principal

Por ahora, el foco principal será:

- **PortSwigger Web Security Academy**

Iré resolviendo y documentando sus laboratorios de forma progresiva.

## Laboratorios documentados

| Plataforma | Categoría | Laboratorio |
|---|---|---|
| PortSwigger Web Security Academy | SQL Injection | [Lab 01 - Login Bypass](portswigger-academy/SQLI/Lab1/01-login-bypass.md) |

## Temas que iré trabajando

- SQL Injection
- Authentication bypass
- Burp Suite
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
```

## Formato de documentación

Cada laboratorio intentará seguir una estructura similar:

- Objetivo del ejercicio.
- Plataforma utilizada.
- Herramientas usadas.
- Contexto de la vulnerabilidad.
- Request original.
- Payload o prueba realizada.
- Request modificada.
- Respuesta obtenida.
- Evidencia con capturas.
- Explicación técnica.
- Resultado.
- Mitigación.
- Qué aprendí.

## Nota

Este repositorio irá creciendo a medida que complete nuevos laboratorios y mejore mis apuntes.

El foco principal es aprender, practicar, entender la lógica detrás de cada vulnerabilidad y dejar evidencia clara de mi avance técnico.
