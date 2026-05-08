# Skill: resumen-articulos

Generar resumenes estructurados de articulos, titulos o secciones del Proyecto de Ley Boletin 18216-05.

## Cuando usarla

Cuando el usuario pida explicar, resumir o desglosar articulos especificos, titulos, o secciones completas del proyecto de ley.

## Instrucciones

1. Localizar la seccion solicitada en `archivo.pdf`
2. Identificar el contexto dentro de la estructura del proyecto:
   - Titulo y capitulo al que pertenece
   - Relacion con otros articulos
3. Resumir en lenguaje claro, evitando jerga legal innecesaria
4. Destacar:
   - Que establece (obligacion, derecho, mecanismo)
   - A quien afecta (contribuyentes, empresas, estado, regiones)
   - Cuando entra en vigencia (permanente, transitorio, gradual)
   - Conexion con los objetivos del proyecto (crecimiento, empleo, reconstruccion)

## Estructura del proyecto de ley

Referencia de organizacion del articulado:

- **Medidas tributarias**: declaracion voluntaria, impuesto corporativo, creditos al empleo, integracion
- **Medidas de gasto**: reconstruccion (Nuble, Bio Bio), infraestructura, empleo
- **Simplificacion regulatoria**: permisologia, tramites, plazos
- **Modificaciones aduaneras**: regimenes especiales, aranceles
- **Disposiciones transitorias**: vigencia, plazos de implementacion

## Formato de salida

```
### Resumen: [Articulo/Titulo/Seccion]

**Ubicacion**: Titulo X, Capitulo Y, Art. Z
**Tipo de norma**: [permanente/transitoria]

**Contenido**:
[Resumen en 3-5 oraciones en lenguaje claro]

**Afectados**: [quienes]
**Vigencia**: [cuando aplica]
**Conexion con objetivos**: [crecimiento/empleo/reconstruccion/fiscal]
**Referencia**: archivo.pdf pag. XX
```
