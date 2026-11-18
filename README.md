# Eficiencia nutricional de tubérculos y legumbres en Perú (2000–2025)
Análisis de cuánta proteína y energía se obtiene por cada sol gastado en tubérculos y legumbres, usando precios mayoristas de Lima (centro), San Martín (norte) y Arequipa (sur). El método se basa en Llerena y de Mendiburu (2026), aplicado a precios mayoristas.

## Ver el informe
https://daniel-m-quiroz-a.github.io/eficiencia-nutricional-peru/

## Hallazgos principales
- La lenteja (61.0 g por sol) y el frijol (60.8 g por sol) tienen la mayor eficiencia proteica.
- La yuca (1617.5 kcal por sol), el camote (1194.0) y la papa (839.3) tienen la mayor eficiencia energética.
- Entre 2000 y 2025, la eficiencia proteica cayó entre 55 % y 74 % según el producto.
- Los niveles son parecidos entre zonas; la diferencia clara está en que la caída es más lenta en el sur.

## Contenido del repositorio

- `index.html`: informe final
- `eficiencia_nutricional_peru_2000_2025.Rmd`: código en R
- `Precios_zonas_completo final.xlsx`: datos
- `styles.css`: estilos del informe

## Métodos y herramientas

Modelos lineales mixtos con el producto como efecto aleatorio. R: lmerTest, emmeans, performance.

## Autor

Daniel Mauricio Quiroz Acho
