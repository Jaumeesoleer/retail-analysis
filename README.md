## 📊 Insights de negocio - Día 1

Tras el análisis exploratorio inicial (EDA), se han detectado los siguientes patrones clave en el comportamiento de ventas:

### 1. Rendimiento por categoría

- **Liderazgo disputado:** La categoría **Electronics** genera el mayor volumen de ingresos ($156k), seguida muy de cerca por **Clothing** ($155k). Ambas categorías representan el núcleo del negocio.
- **Oportunidad en beauty:** Aunque es la categoría con menores ingresos totales ($142k), sorprendentemente tiene el **ticket medio más alto ($464)**.
  - _Recomendación:_ Implementar estrategias de _cross-selling_ para aumentar el volumen de transacciones en beauty, aprovechando que los clientes ya están dispuestos a pagar precios altos por unidad.

### 2. Estacionalidad y tendencias

- **Pico atípico en mayo:** mayo se posiciona como el mes más fuerte del año ($53k), superando incluso a la temporada navideña (Dic: $44k).
  - _Acción:_ Investigar qué campaña o evento ocurrió en mayo para intentar replicar ese éxito en los meses de caída como **septiembre** ($23k).

### 3. Comportamiento del precio

- La varianza del precio promedio entre categorías es mínima ($443 - $464). La baja varianza del precio promedio entre categorías sugiere una política de precios homogénea o una cartera de productos con posicionamiento similar

### 4. Comportamiento humano

- Dentro de los clientes no se detecta gran diferencia en género, ya que están a un 51% a 49% aproximadamente. Por otro lado, en las edades de los clientes vemos que el público más jóven (18-35 años) y el más adulto (42-64 años) son quien más gasta en importe, la edad media de los clientes es donde se nota una bajada en compra (36-41 años).
- El dataset muestra ausencia total de recurrencia (1 compra por cliente), lo que impide analizar fidelización y limita el análisis a comportamiento transaccional aislado.
