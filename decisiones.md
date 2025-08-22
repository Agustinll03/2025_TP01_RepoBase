# Decisiones

## Configuración de identidad
- user.name: Agustin Llancaman Canavesio
- user.email: agustinllancaman@gmail.com

## Estrategia de rama y commits
- Rama: feat/mi-funcionalidad (aisla cambios y facilita PR)
- Commits atómicos: 1) código de la función, 2) docs de uso.
- Beneficios: revertir/granularidad/CI más claro.

## Integración del hotfix
- Elegí *merge* de main → feat/mi-funcionalidad para traer todo el historial y minimizar conflictos futuros.
- Alternativa considerada: cherry-pick del commit del fix; descarté para no fragmentar historial.

