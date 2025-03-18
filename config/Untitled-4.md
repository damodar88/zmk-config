


🔹 Implementar primero:
✔ Factory Method → Para manejar múltiples APIs fácilmente.
✔ Adapter → Para unificar los datos en un solo formato.
✔ Circuit Breaker → Para evitar problemas si una API externa falla.

🔹 Implementar después si es necesario:
✔ Strategy → Si quieres comparar precios y elegir el mejor automáticamente.
✔ Observer → Si en el futuro agregas alertas en tiempo real.






data
    -gateway 
        -CryptoPriceGateway.java

    -gatewayimpl

    -budaapigatewayimpl: directorio de la interface 
        -budaapigatewayimpl: la implementacion de la interface
        -model: data cada respuesta de api

    -coingeckoapigateway: directorio de la interface 
        -coingeckoapigatewayimpl: la implementacion de la interface
         -model: data cada respuesta de api


