# Gestión de cupos para parqueo en EAFIT

Aplicación web para ver cuántos cupos libres hay en los parqueaderos de EAFIT y saber a cuál ir. Si todo está lleno, el conductor queda en una lista de espera.

Proyecto final de Estructuras de Datos, Ingeniería de Sistemas, Universidad EAFIT. Autor: Simon Banda.

## Qué hace

- Muestra los cupos libres de los parqueaderos Norte y Sur y la ocupación total.
- Recomienda el parqueadero más cercano a la portería por la que entras y dibuja la ruta.
- Registra el ingreso y la salida de un vehículo por su placa.
- Si no hay cupo, lo pone en una lista de espera y le asigna uno apenas se libera.
- Permite buscar un vehículo por su placa.

## Estructuras de datos

Programadas desde cero, sin librerías:

- **Cola (FIFO):** la lista de espera.
- **Tabla hash:** guarda cada vehículo por su placa para encontrarlo rápido.
- **Grafo:** porterías y parqueaderos, usado para calcular la ruta más corta.

## Cómo probarla

Descarga `gestion-cupos-eafit.html` y ábrelo en el navegador. No necesita instalar nada.

Los datos son de prueba. Solo el total de 1038 celdas viene de un estudio de EAFIT; el reparto entre parqueaderos, las distancias y la ocupación son inventados.
