# Skill: analisis-fiscal

Analizar el impacto fiscal de articulos o medidas especificas del Proyecto de Ley Boletin 18216-05.

## Cuando usarla

Cuando el usuario pida evaluar el costo fiscal, financiamiento, o impacto presupuestario de una medida del proyecto.

## Instrucciones

1. Identificar la medida o articulo especifico que el usuario quiere analizar
2. Leer las secciones relevantes de `archivo.pdf` (texto legal) y la presentacion del CFA
3. Clasificar la medida como:
   - **Ingreso permanente** o **transitorio**
   - **Gasto permanente** o **transitorio**
4. Cuantificar el impacto usando los datos del CFA cuando esten disponibles:
   - Efecto directo (sin considerar crecimiento)
   - Efecto de segunda vuelta (con crecimiento economico)
5. Evaluar riesgos fiscales asociados
6. Presentar el resultado en formato tabla con:
   - Medida analizada
   - Tipo (ingreso/gasto, permanente/transitorio)
   - Impacto estimado (% PIB)
   - Horizonte temporal
   - Riesgos identificados

## Marco de referencia

Situar siempre el analisis en relacion a:
- Deficit estructural actual (3.6% PIB)
- Deuda bruta (41.5% PIB) y umbral prudente (45%)
- Estado del FEES (1.0% PIB)
- Regla fiscal chilena y recomendaciones del CFA

## Formato de salida

```
### Analisis Fiscal: [nombre de la medida]

**Clasificacion**: [ingreso/gasto] [permanente/transitorio]

| Concepto | Valor |
|---|---|
| Impacto directo | X% PIB |
| Efecto segunda vuelta | X% PIB |
| Impacto neto | X% PIB |
| Horizonte | 20XX-20XX |

**Riesgos**: [lista de riesgos]
**Referencia**: archivo.pdf pag. XX / Presentacion CFA pag. XX
```
