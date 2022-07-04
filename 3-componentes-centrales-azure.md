# Componentes centrales de Azure

## Regiones de Azure

<p align="center">
  <img src="/images/regiones-azure.png" alt:"Regiones Azure" />
</p>

### Pares de regiones
**Cada región** está **emparejada con otra** dentro de la misma geografía (**pares de regiones**). Para evitar las interrupciones por desastres naturales, cortes de energia o interrupciones de la red física. Si una región de un par se ve afectada, los servicios se conmutarían automaticamente a su región par.

<p align="center">
  <img src="/images/pares-regiones.png" alt:"Pares de Regiones" />
</p>

## Zonas de disponibilidad

Las **zonas de disponibilidad** permiten tener **infraestructura redundante** para tener varios entornos de hardware duplicados (**alta disponibilidad**) por si hay algún fallo.
Las **zonas de disponibilidad** sin centros de datos físicamente separados y aislados dentro de una región con alimentación, refigeración y redes independientes. Si una zona se cae, la otra sigue funcionando.

> Las zonas de disponibilidad se utilizan para ejecutar aplicaciones de misión crítica.

### Infraestructura global de Azure

- Una **región** es un conjunto de centros de datos conectados a través de una red de baja latencia.
- Las **zonas de disponibilidad** son centros de datos separados fisicamente dentro de una región de Azure, con energía, red y enfriamiento.

<p align="center">
  <img src="/images/azure-region.png" alt:"Azure Region" />
</p>