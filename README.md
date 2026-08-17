# Análisis de hábitos de compra — Instacart

Análisis exploratorio de los patrones de compra en Instacart, una plataforma
de entrega de comestibles a domicilio.

## Objetivo

Identificar patrones de comportamiento en los pedidos de los clientes:
horarios de mayor actividad, frecuencia de compra, productos más solicitados
y tasa de recompra por producto.

## Datos

Cinco tablas relacionadas publicadas por Instacart en 2017:

| Tabla | Contenido |
|---|---|
| `instacart_orders` | pedidos con fecha, hora y días desde el anterior |
| `products` | catálogo de productos |
| `order_products` | artículos por pedido y si fueron recompra |
| `aisles` | categorías de pasillo |
| `departments` | departamentos de la tienda |

Los datos contienen valores ausentes y duplicados que requirieron limpieza
previa al análisis.

## Metodología

1. Corrección de tipos de datos y formato de lectura
2. Identificación y tratamiento de valores ausentes
3. Detección y eliminación de duplicados
4. Análisis de distribuciones temporales
5. Análisis de productos y tasas de recompra

## Hallazgos principales

- Mayor afluencia de pedidos entre las 10:00 y las 16:00
- Los días de mayor actividad son domingo y lunes
- Las frutas y verduras concentran la mayor parte de las ventas
- Los plátanos son el producto más pedido y también el más recomprado

## Stack

- Python
- pandas — manipulación y limpieza de datos
- matplotlib — visualización

## Nota sobre los datos

Los archivos CSV no se incluyen en este repositorio. El notebook conserva
todas las salidas ejecutadas.