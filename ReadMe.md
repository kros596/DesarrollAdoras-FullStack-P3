<h1>Práctica 3 Desarrollo Full-Stack (Nivel 3) ED.2022</h1>
<p>
  En esta práctica se pedía elaborar una lista de la compra con los diferentes supermercados, con sus datos, 
  y los productos en dos categorías: productos en oferta y productos habituales. Los productos debían incorporar ciertos atributos
</p>
<p>
  De este modo se han elaborado dos ficheros, un fichero JSON y un fichero XML, que cuentan con dichos datos estructurados de la siguiente manera:
</p>

<h2>Lista de la compra</h2>
<p>Lista de la compra:
<ul>
    <li>
      Supermercado 1
        <ul>
          <li>Nombre</li>
          <li>Dirección
            <ul>
              <li>Dirección</li>
              <li>Numero</li>
              <li>CP</li>
              <li>Localidad</li>
              <li>Provincia</li>
            </ul>
          </li>
          <li>Geolocalización</li>
            <ul>
              <li>Latitud</li>
              <li>Longitud</li>
            </ul>
          </li>
          <li>Horario Habitual
            <ul>
              <li>Lunes
                <ul>
                  <li>Abierto</li>
                  <li>Apertura</li>
                  <li>Cierre</li>
                </ul>
              </li>
              <li>Martes
                <ul>
                  <li>Abierto</li>
                  <li>Apertura</li>
                  <li>Cierre</li>
                </ul>
              </li>
              <li>[...]</li>
              <li>Domingo
                <ul>
                  <li>Abierto</li>
                  <li>Apertura</li>
                  <li>Cierre</li>
                </ul>
              </li>
            </ul>
          </li>
          <li>Productos
            <ul>
              <li>En Oferta
                <ul>
                  <li>Producto/Oferta 1
                    <ul>
                      <li>
                        Producto
                        <ul>
                          <li>Denominación</li>
                          <li>Departamento</li>
                          <li>Marca</li>
                          <li>Precio unidad</li>
                          <li>Unidades</li>
                          <li>Unidad de medida</li>
                          <li>Adquirido</li>
                        </ul>
                      </li>
                      <li>
                        Oferta
                        <ul>
                          <li>Descuento</li>
                          <li>
                            Vigencia
                            <ul>
                              <li>Fecha Inicio</li>
                              <li>Fecha Fin</li>
                            </ul>
                          </li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li>Producto/Oferta 2
                      [...]
                  </li>
                  <li>[...]</li>
                  <li>Producto/Oferta n
                      [...]
                  </li>
                </ul>
              </li>
              <li>Habituales
                <ul>
                  <li>
                        Producto 1
                        <ul>
                          <li>Denominación</li>
                          <li>Departamento</li>
                          <li>Marca</li>
                          <li>Precio unidad</li>
                          <li>Unidades</li>
                          <li>Unidad de medida</li>
                          <li>Adquirido</li>
                        </ul>
                   </li>
                   <li>
                       Producto 2
                       [...]
                   </li>
                   <li>[...]</li>
                  <li>Producto n
                      [...]
                  </li>
                </ul>
              </li>
            </ul>
          </li>
        </ul>
    </li>
     <li>
      Supermercado 2
      [...]
    </li>
    <li>[...]</li>
    <li>
      Supermercado n
    </li>
   
  </ul>
</p>
