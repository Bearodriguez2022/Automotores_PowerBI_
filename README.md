# Automotores
Este es un proyecto en Power BI con prácticas de DAX.
La empresa BMW, lider en la industria atomotriz, busca fortalecer su equipo de inteligencia de Negocios para mejorar la toma de decisiones estratégicas en sus operaciones comerciales. BMW necesita comprender mejor el desempeño de sus ventas en distintos mercados y canales de distribición.
Para ello, ha decidido contratarme como Analista de datos, con el objetivo de desarrollar un sistema de reportes dinámicos e interactivos en Power Bi.
1-La primer tarea será construir un reporte inicial que proporcione una visión general del desempeño de la empresa en terminos de ventas, costos, utilidades y comportamiento del mercado.

Las medidas DAX utilizadas:

*% Utilidad = DIVIDE([Utilidad], [Ventas])

*Autos Vendidos = COUNTA(Ventas[ID Auto])

*Ciudades = DISTINCTCOUNT(Ventas[Ciudad]) 

*Clientes = DISTINCTCOUNT(Ventas[ID Cliente])

*Costo = SUM(Ventas[Costo Auto])

*Paises = COUNTA(Pais[ID Pais])

*Utilidad = [Ventas] - [Costo] 

*Vendedores = DISTINCTCOUNT(Ventas[Vendedor])

*Ventas = SUM(Ventas[Precio Venta]) 

