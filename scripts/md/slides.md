title: Agenda

- Bio
- Inventario Fantasma:
	- Un tipo de Out-Of-Stock (OOS)
	- Desde el punto de vista del Productor
	- Desde el punto de vista del Retailer
	- Analytics!
- Q&A

---

title: Bio
subtitle: "Street Cred"

- Ing. Mecánico Administrador - Tec de Monterrey
- M. Manufactura, Supply Chain y Operaciones - McGill University
- Más de 9 años de experiencia en Supply Chain y Analytics en:
	- Retail y CPGs
	- Distribución de Electrónicos
	- Industria Aeroespacial
	- Industria Automotriz
	- Manufactura
- Sonorense (hasta a -30ºC)

<aside class="note"> <section> <img class="img-responsive" src="images/dataday/carniasada.jpg" alt="OOS Root Cause"></section></aside>

---
title: Inventario Fantasma
subtitle: Un tipo de Out of Stock (OOS)
class: segue dataday nobackground
---
title: Out-Of-Stocks (OOS)
subtitle: Definición
build_lists: true

- **OOS** ocurre cuando no hay "físicamente" un item en el estante para su venta.  
- **OOS** inicia cuando el último item de un SKU es removido del estante.  
- **OOS** termina con el resuministro del mismo SKU en el estante.  

- Podemos definir los siguientes tipos de OOS:

	- DC: **No Existe** inventario
	- Store: **No Existe** inventario en la tienda
	- Shelf: **Existe** inventario en la tienda pero no se encuentra en el estante

<aside class="note"> <section> <img class="img-responsive" src="images/dataday/OOS.png" alt="ejemplos"></section></aside>

---
title: OOS
subtitle: Desde el punto de vista del consumidor

<div class="container-fluid"> 
	<div class="col-md-5">
		<img class="img-responsive" src="images/dataday/root_cause_oos.png" alt="OOS Root Cause">
	</div>
	<div class="col-md-7">
		<h3>Reacción del consumidor ante OOS</h3>
		<table class="table table-hover">
			<thead>
				<tr>
					<th>Acción</th>
					<th>Porcentage</th>
					<th>Tienda</th>
					<th>Proveedor</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Compra item en otra tienda</td>
					<td class="text-right">31 %</td>
					<td class="text-center">X</td>
					<td class="text-center"></td>
				</tr>
				<tr>
					<td>No compra item</td>
					<td class="text-right">9 %</td>
					<td class="text-center">X</td>
					<td class="text-center">X</td>
				</tr>
				<tr>
					<td>Pospone compra</td>
					<td class="text-right">15 %</td>
					<td class="text-center">X</td>
					<td class="text-center">X</td>
				</tr>
				<tr>
					<td>Sustituye otra marca</td>
					<td class="text-right">26 %</td>
					<td class="text-center"></td>
					<td class="text-center">X</td>
				</tr>
				<tr>
					<td>Sustituye misma marca</td>
					<td class="text-right">19 %</td>
					<td class="text-center"></td>
					<td class="text-center"></td>
				</tr>
			</tbody>
		</table>
		<h6>Credito: Gruen, Corsten, and Bharadwaj 2002</h6>
	</div>
</div>

---
title: Shelf - OOS
subtitle: ¿Por que no está mi producto en el estante?
build_lists: true

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
subtitle: El círculo vicioso...

<div class="container-fluid"> 
	<div class="col-md-8 col-md-offset-2">
		<img class="img-responsive" src="images/dataday/vensim.png" alt="SD">
	</div>
</div>

<aside class="note"> <section>
					<div class="text-left">
					<h5><ul>
						<li>Tengo inventario pero **NO TENGO** inventario</li>
						<li>No se ordena más producto por que "el sistema dice que hay"  </li>
						<li>No se registra ninguna venta (POS) en las semanas posteriores </li>
						<li>Se ajusta el "forecast" acorde a las ventas registradas (o no registradas) </li>
						<li>Se llega a la conclusión de que "Ese producto no se vende"  </li>
						<ul>
						<li>Auditoría fisica para corregir inventarios </li>
						<li>Se puede tomar la decisión de descontinuar el producto</li>
						</ul>
					</ul>
					Este ciclo se repite... y se repite... y se repite... y se repite...
					</h5>
				</div>
</section></aside>

---
title: Inventario Fantasma
subtitle: Desde el punto de vista del productor
class: segue dataday nobackground

---
title: Inventario Fantasma
subtitle: Un caso inventado...

<div class="container-fluid"> 
	<div class="col-md-6">
	<h3 class="text-center">Cerveza Artesanal "CHHHeve"</h3>
	<h4 class="text-center">Producida en Hermosillo, Sonora para el mundo</h4>
	<img class="img-responsive" src="images/dataday/sc.png" alt="supply chain routes">
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

<h5>Más de 17,258,000 mts supervisando el suministro, producción y distribución de "CHHHeve" para que al final fallen los últimos 50 mts!!!</h5>

<aside class="note"> <section>
	<p>En este ejemplo se puede ver que no importa tener una Cadena de Suministro perfectamente controlada, si al final el producto no se encuentra en el estante, no puede ser adquirido por el consumidor.</p>
</section></aside>

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


![supply chain routes](images/dataday/simplesc.gif) ![supply chain routes](images/dataday/complexsc.gif)

<aside class="note"> <section>
	<p>Para esta simulación/demostración se tomo en cuenta un "Moving Average" de 6 semanas</p>
</section></aside>

---
title: Inventario Fantasma
subtitle: Desde el punto de vista del Retailer
class: segue dark nobackground

---
title: De la tienda a la casa...
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

<aside class="note"> <section>
	<p>Si bien el Retailer no se tiene que preocupar por lo que pasa en la cadena de suministro de sus proveedores, la combinacion de ITEM x CENTRO DE DISTRIBUCION x TIENDAS hace que sea igual o más complicado controlar lo que sucede </p>
</section></aside>
---
title: Inventario Fantasma
subtitle: Analytics
class: segue dataday nobackground

---
title: #datavis

<iframe
  frameborder="0" seamless="seamless" scrolling="no"
  src="images/dataday/inventario.html">
</iframe>

<aside class="note"> <section>
	<p>Siendo más especificos el periodo de tiempo sin ventas puede ser generado por 1) Inventario Fantasma, 2) Producto en el almacen (no estante), 3) No hay producto disponible, 4) No se vendió el producto, 5) otros.</p>
</section></aside>

---
title: Inventario Fantasma
subtitle: Un nuevo-viejo "approach"
build_lists: true

Cuando el uso de "visuales" no es práctico, se puede hacer uso de analyticos avanzados (y no tan avanzados):

- Clasificar items (i.e. categoría, tipo de producto, temporada)
- Definir "gap" máximo entre actividad de POS (meses, semanas, dias, horas)
- Calcular "Ventas Perdidas" que representa cada combinación item/tienda
	- Seleccionar Top 5, 10, 20 combinaciones
- Validar resultados item/tienda identificados
- Ajustar criterio a validación
- Repetir ciclo hasta obtener % predicción aceptable


---
title: Retail Analytics
subtitle: Otras aplicaciones
build_lists: true

Solo en el área de "replenishment":

- Utilizar precios promedio para identificar eventos o liquidaciones
- Optimización de niveles de inventarios  
- Afinación de Forecast  
- Identificar tendencias por tienda/región/categoría y customatizar soluciones  
- Combinación con información socio-económica  
- Combinación con información meteorológica  
- Entre otras...  

---
title: Inventario Fantasma
subtitle: Q&A
class: segue dataday nobackground

