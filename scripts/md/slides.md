title: Agenda

- Bio
- Inventario Fantasma:
	- Desde el punto de vista del Productor
	- Un tipo de Out-Of-Stock (OOS)
	- Desde el punto de vista del Retailer
	- Y los algoritmos 'apá!
- Q&A

---

title: Bio
subtitle: "Street Cred"

Experience Roadmap IMAGE

<aside class="note"> <section> Crear un timeline/roadmap sencillo para representar la experiencia </section></aside>

---
title: Inventario Fantasma
subtitle: Desde el punto de vista del productor
class: segue dark nobackground

---
title: De la tierra a la tienda... 
subtitle: ¿Qué pasta antes de que puedas comprar algo?

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome-animation/0.0.8/font-awesome-animation.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">


<div class="container-fluid">
	<div class="text-center">
		<div class="row">
			<div class="col-md-1">
			</div>
			<div class="col-md-2">
				<i class="fa fa-industry fa-5x"></i>
				<h4>Producción</h4>
				<br>
				<div class="text-left">
					<h5><ul>
						<li>Materia Prima</li>
						<li>Mano Obra</li>
						<li>Mantenimiento</li>
						<li>Reparación</li>
						<li>Operaciones</li>
						<li>Calidad</li>
						<li><font color="red">Control Inventario</font></li>
					</ul></h5>
				</div>
			</div>
			<div class="col-md-1">
				<i class="fa fa-long-arrow-left faa-passing-reverse animated"></i>
				<h6>info</h6>
				<i class="fa fa-arrow-right faa-passing animated"></i>
				<h6>producto</h6>
			</div>
			<div class="col-md-2">
				<i class="fa fa-truck fa-5x fa-flip-horizontal"></i>
				<h4>Distribución</h4>
				<br>
				<div class="text-left">
					<h5><ul>
						<li>Logística</li>
						<li>Transportación</li>
						<li>Almacenamiento</li>
						<li><font color="red">Control Inventario</font></li>
						<li>Mano de Obra</li>
						<li>Cross-docking</li>
						<li>Mantenimiento</li>
					</ul></h5>
				</div>
			</div>
			<div class="col-md-1">
				<i class="fa fa-long-arrow-left faa-passing-reverse animated"></i>
				<h6>info</h6>
				<i class="fa fa-arrow-right faa-passing animated"></i>
				<h6>producto</h6>
			</div>
			<div class="col-md-2">
				<i class="fa fa-shopping-cart fa-5x"></i>
				<h4>Punto de Venta</h4>
				<br>
				<div class="text-left">
					<h5><ul>
						<li>Mano Obra</li>
						<li>Bodega</li>
						<li><font color="red">Control Inventario</font></li>
						<li>Operacion Tienda</li>
						<li>Logistica</li>
					</ul></h5>
				</div>
			</div>
			<div class="col-md-1">
				<i class="fa fa-long-arrow-left faa-passing-reverse animated"></i>
				<h6>info</h6>
				<i class="fa fa-arrow-right faa-passing animated"></i>
				<h6>producto</h6>
			</div>
			<div class="col-md-2">
				<i class="fa fa-home fa-5x"></i>
				<h4>Consumidor</h4>
				<br>
				<div class="text-left">
					<h5><ul>
						<li>Consumo Producto</li>
						<li><font color="red">Control Inventario</font></li>
						<li>Presupuesto</li>
					</ul></h5>
				</div>
			</div>
		</div>
	</div>
</div>
<br>
<br>
---
title: Forecasting
subtitle: Anticipando "lo que viene"
content_class: flexbox vcenter


![supply chain routes](../../images/dataday/simplesc.gif) ![supply chain routes](../../images/dataday/complexsc.gif)

<aside class="note"> <section>[Flowing Data post](http://flowingdata.com/2011/05/11/how-to-map-connections-with-great-circles/)</section></aside>

---
title: Inventario Fantasma
subtitle: Un caso inventado...

<div class="container-fluid"> 
	<div class="col-md-6">
	<h3 class="text-center">Cerveza Artesanal "CHHHeve"</h3>
	<h4 class="text-center">Producida en Hermosillo, Sonora para el mundo</h4>
	<img class="img-responsive" src="../../images/dataday/sc.png" alt="supply chain routes">
	</div>
	<div class="col-md-6">
  <table class="table table-hover">
    <thead>
      <tr>
        <th>item</th>
        <th>Origen</th>
        <th>Destino</th>
        <th>Distancia (Km)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Malta</td>
        <td>Vancouver</td>
        <td>Hermosillo</td>
        <td class="text-right">2,578.8</td>
      </tr>
      <tr>
        <td>Cebada</td>
        <td>Milwaukee</td>
        <td>Hermosillo</td>
        <td class="text-right">2,472.8</td>
      </tr>
            <tr>
        <td>Lúpulo</td>
        <td>Alemania</td>
        <td>Hermosillo</td>
        <td class="text-right">9,474.2</td>
      </tr>
            <tr>
        <td>Envases</td>
        <td>Monterrey</td>
        <td>Hermosillo</td>
        <td class="text-right">1,118.2</td>
      </tr>
            <tr>
        <td>Cerveza</td>
        <td>Hermosillo</td>
        <td>León</td>
        <td class="text-right">1,288.2</td>
      </tr>
            <tr>
        <td>Cerveza</td>
        <td>León</td>
        <td>Cd. México</td>
        <td class="text-right">324.6</td>
      </tr>
                  <tr>
        <td>Cerveza</td>
        <td>Cd. México</td>
        <td>WTC</td>
        <td class="text-right">1.3</td>
      </tr>
            </tr>
                  <tr>
        <td><b>TOTAL</b></td>
        <td></td>
        <td></td>
        <td class="text-right"><b>17,258.4</b></td>
      </tr>
    </tbody>
  </table>
</div>
</div>

Entonces por que son tan importantes los últimos 50 metros??? 

<aside class="note"> <section>[Flowing Data post](http://flowingdata.com/2011/05/11/how-to-map-connections-with-great-circles/)</section></aside>

---
title: Inventario Fantasma
subtitle: Un tipo de Out of Stock (OOS)
class: segue dark nobackground
---
title: Out-Of-Stocks (OOS)
subtitle: La madre del inventario fantasma! 

**OOS** ocurre cuando no hay "físicamente" un item en el estante para su venta.  
**OOS** inicia cuando el último item de un SKU es removido del estante.  
**OOS** termina con el resuministro del mismo SKU en el estante.  

Podemos definir los siguientes tipos de OOS:

- DC: **No Existe** inventario
- Tienda: **No Existe** inventario en la tienda
- Shelf: **Existe** inventario en la tienda pero no se encuentra en el estante

---
title: Shelf - OOS
subtitle: Por que no está mi producto en el estante?

- No hay producto  
- Operación de la Tienda:  
	- Está en un lugar incorrecto  
	- Todavía está en el bodega (backroom)  
	- Está en "transito"  
- Nivel de inventario Incorrecto en el sistema:  
	- Inventario Escondido  
	- ***Inventario Fantasma***  
		- Robado, Dañado o Extraviado  
---
title: Inventario Fantasma
subtitle: El circulo vicioso...

*  Tengo inventario pero **NO TENGO** inventario  
*  No se ordena más producto por que "el sistema dice que hay"  
*  No se registra ninguna venta (POS) en las semanas posteriores  
*  Se ajusta el "forecast" acorde a las ventas registradas (o no registradas)  
*  Se llega a la conclusión de que "Ese producto no se vende"  
	+ Auditoría fisica para corregir inventarios  
	+ Se puede tomar la decisión de descontinuar el producto:  

Este ciclo se repite... y se repite... y se repite... y se repite...
---
title: Inventario Fantasma
subtitle: Desde el punto de vista del Retailer
class: segue dark nobackground

---
title: De la tienda a las casas...
subtitle: ¿Los problemas del productor a la <sup>n</sup> potencia?

<div class="container-fluid">
	<div class="text-center">
		<div class="row">
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-truck fa-2x fa-flip-horizontal"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-truck fa-2x fa-flip-horizontal"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-truck fa-2x fa-flip-horizontal"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
			<div class="col-md-1">
				<font size="4"><i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i>&nbsp;<i class="fa fa-industry"></i></font>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-2x fa-fw">&nbsp;</i>
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-shopping-cart fa-2x"></i> 
				<i class="fa fa-arrow-down faa-float animated"></i> 
				<i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i><i class="fa fa-home"></i>
			</div>
		</div>
	</div>
---
title: Inventario Fantasma
subtitle: Y los algoritmos 'apá!
class: segue dark nobackground

---
title: #datavis

<iframe
  frameborder="0" seamless="seamless" scrolling="no"
  src="../../images/dataday/inventario.html">
</iframe>

---
title: Inventario Fantasma
subtitle: Un nuevo approach

Por medio de algoritmos podemos identificar instancias de Inventario Fansamsa Potencial y tomar medidas especificas para solucionarlos

---
title: Retail Analytics
subtitle: Otras aplicaciones

Solo en el área de replenishment:

- Identificación de eventos por medio de precios promedios  
- Optimización de niveles de inventarios  
- Afinación de Forecast  
- Identificar tendencias por tienda/region/categoria y customatizar soluciones  
- Combinación con información socio-economica  
- Combinación con información del clima  
- Entre otras...  

---
title: Inventario Fantasma
subtitle: QA
class: segue dark nobackground

