## ❓ Numeración de facturas al cambiar de año

Otra situación habitual al comenzar un nuevo ejercicio son las **dudas relacionadas con la numeración de las facturas**.

### Reinicio de numeración por ejercicio

En **eclipseERP**, al iniciar un nuevo ejercicio:

- La numeración de los documentos **vuelve a arrancar desde el número 1**.
- Este comportamiento es normal y correcto, ya que la numeración es **independiente por ejercicio**.

Esto **no implica** que la primera factura del año tenga que llevar obligatoriamente el número 1, sino que el programa **lo propone como valor inicial**.

## ⚠️ Mensaje de inicio de numeración

Al emitir la **primera factura del nuevo ejercicio**, el programa muestra un mensaje indicando:

- Que se trata de la primera factura del año.
- Que se propone el **número 1** como inicio de numeración.

En ese momento, el usuario puede:
- Aceptar la numeración propuesta.
- **Modificarla manualmente** e indicar el número por el que desea comenzar.

### Uso de prefijos y sufijos en la numeración

Muchos clientes utilizan **prefijos y/o sufijos** en la numeración de los documentos de venta para hacerla más clara o identificativa.

Ejemplo habitual:

- **FA-123-25**
  - `FA` → Prefijo del tipo de documento 
  - `123` → Número correlativo.
  - `25` → Sufijo que hace referencia al año.

Esta estructura funciona como una **máscara de numeración** aplicada a los documentos de venta.

## 🛠️ Configuración de la máscara de numeración

Los prefijos y sufijos pueden **predeterminarse desde la configuración general del programa**, de forma que:

- Se apliquen automáticamente al crear nuevos documentos de vena.
- Se mantenga una numeración homogénea durante todo el ejercicio.

## ⭐ Importante al cambiar de año

Cuando la numeración incluye **elementos dependientes del año** (por ejemplo, un sufijo con el año):

- Es imprescindible **revisar y actualizar la configuración antes de emitir la primera factura**.
- Si no se modifica:
  - Las facturas del nuevo ejercicio podrían seguir mostrando el sufijo del año anterior.
  - Esto puede generar confusión administrativa y contable.

### Atención especial con Veri*Factu

De cara a **Veri*Factu**, este punto cobra todavía más importancia:

- La numeración debe ser **coherente, correlativa y correcta desde la primera factura**.
- Un error en el prefijo o sufijo al inicio del año puede suponer:
  - Rectificaciones innecesarias.
  - Incidencias adicionales en el cumplimiento normativo.

## ✅ Recomendaciones

- Revisar **prefijos y sufijos** antes de emitir la primera factura del año.
- Confirmar que cualquier referencia al año esté correctamente actualizada.
- Definir y documentar el criterio de numeración con la asesoría.
- Ante la duda, **no emitir la primera factura** hasta revisar la configuración.
