# Planilla del módulo

* Enlace a Google Sheets (cualquier persona con el enlace puede ver): https://docs.google.com/spreadsheets/d/1XU2AjS4UztfiYEkPv1G4EiYxlnEQ1BWV2GD_Q1o0lkY/edit?usp=sharing
* Archivo subido: `02-datos/planilla.xlsx`

## Hojas incluidas
1. Costos: precio, costo variable, costos fijos, flete, despacho y seguro por envío (datos de datos_base.md) y total de costos fijos mensuales.
2. Resultado: ingresos, costos variables, margen de contribución, costos fijos totales y resultado mensual a 10.000 paquetes.
3. Equilibrio: punto de equilibrio en paquetes y en USD, y margen de seguridad.
4. Sensibilidad: ingresos, costos y resultado mensual para 6.000, 8.000, 10.000, 12.000 y 14.000 paquetes.

## Fórmulas principales utilizadas
* Seguro por envío = valor asegurable × tasa (USD 42.000 × 0,6 % = USD 252)
* Costos fijos totales = costos fijos mensuales + flete + despacho + seguro
* Margen de contribución = ingresos − costos variables
* Resultado mensual = margen de contribución − costos fijos totales
* Punto de equilibrio (paquetes) = costos fijos totales ÷ (precio − costo variable unitario)
* Punto de equilibrio (USD) = punto de equilibrio en paquetes × precio

## Gráfico
Gráfico de líneas en la hoja Sensibilidad: ingresos vs. costos totales según volumen. Las líneas se cruzan cerca del punto de equilibrio.

## Supuesto
El marketing (USD 3.000 en 3 meses) no está incluido en el caso base. En la hoja Costos hay un interruptor (1 = sí, 0 = no) para incluirlo.

