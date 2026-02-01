# Modelos clásicos vs bayesianos para datos de recuento

Análisis comparativo entre modelos Poisson clásicos y bayesianos aplicado al estudio del número de golpes de Estado en países africanos, utilizando el dataset `africa` de la librería `faraway`.

## Contenido del análisis
- Regresión Poisson clásica
- Diagnóstico de supuestos y sobre-dispersión
- Selección de variables (AIC, Lasso)
- Modelos Poisson bayesianos con priors shrinkage
- Comparación predictiva entre enfoques

## Herramientas
- R
- Stan (`rstan`)
- `glm`, `glmnet`
- `loo`, `bayesplot`
- `ggplot2`

## Principales conclusiones
- El enfoque bayesiano ofrece una mejor cuantificación de la incertidumbre.
- El prior Horseshoe produce modelos más parsimoniosos y estables.
- Los resultados son consistentes entre ambos enfoques.

## Autora
Lucía Muñiz Presno
