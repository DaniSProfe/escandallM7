# escandallM7
PROGRAMA DE ESCANDALLOS

Un programa para el control y la gestión de escandallos. Será dirigido a orbjetos y con acceso de datos.

En este caso el lenguaje de programación será PHP y la base de datos seleccionada será MySQL.

DISTRIBUCIÓN DE OBJETOS:

-MATERIA PRIMA:
Atributos:
*Ref(String) // Referencia del proveedor.
*Descripcion (String) // Descripción interna del artículo.
*Medida (String) // Unidad de medida por la que se indicará el precio. UNI (unidades), M2 (metro cuadrado), MLINEAL (metro lineal), LT (litro), KG (Kilo), etc...
*Precio (int) // Precio de la unidad de medida.
*Proveedor (String) // Nombre identifictivo del proveedor
*alta (date) // fecha de alta del producto
*ultima (date) // fecha última modificación
Funcionalidades:
*Constructor (ref, description, umedida, precio, proveedor) // 
*Constructor (ref) //
*Consulta () // retorna toda la información el producto
*Alta ()
*Modificar
