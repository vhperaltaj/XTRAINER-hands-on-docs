# XN01 - Digital Inputs

<figure><img src="https://docs.microside.com/~gitbook/image?url=https%3A%2F%2F177299348-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FbyV2zAlQAiqg46a3Lr8z%252Fuploads%252FjDwm5NLBEwtg8oNR56Kf%252FXN01%2520X-NODE%2520Entradas%2520digitales.webp%3Falt%3Dmedia%26token%3D173ff501-0925-4f0c-9512-dd15cd7e8579&#x26;width=400&#x26;dpr=2&#x26;quality=100&#x26;sign=ce13becb&#x26;sv=2" alt=""><figcaption></figcaption></figure>



<table data-card-size="large" data-view="cards"><thead><tr><th></th><th align="center"></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td></td><td align="center"><mark style="color:green;"><strong>Comprar</strong></mark></td><td></td><td><a href="https://store.microside.com/">https://store.microside.com/</a></td></tr></tbody></table>

El **X-NODE Digital Inputs** es un módulo que integra un switch deslizable de 8 interruptores tipo palanca los cuales pueden variar entre dos posiciones ON <> OFF y un puerto de conexión con 8 entradas y GND. El switch posee una vida eléctrica de hasta 2000 ciclos, una resistencia de aislamiento de hasta 100 MΩ y puede operar en un rango de temperatura de -10 °C hasta 80 °C. El uso de este X-NODE es de propósito general, ya que se usa comúnmente para leer el estado de una señal digital y de esta forma lograr cambios de estado, secuencias o realizar configuraciones en proyectos electrónicos que integren indicadores y actuadores.

### TABLA DE CONTENIDO

1. [¿Cómo funciona?](xn01-digital-inputs.md#i.-como-funciona)
2. [Descripción del hardware](xn01-digital-inputs.md#ii.-descripcion-del-hardware)
3. [Especificaciones](xn01-digital-inputs.md#iii.-especificaciones)
4. [Pinout](xn01-digital-inputs.md#iv.-pinout)
5. [Modo de uso](xn01-digital-inputs.md#v.-modo-de-uso)
   * [Protocolo UART](xn01-digital-inputs.md#protocolo-uart)
   * [Protocolo I2C](xn01-digital-inputs.md#protocolo-i2c)
6. [Descargas](xn01-digital-inputs.md#vi.-descargas)
   * [Esquemático](../../../../dummy-link.md)
   * [Dimensiones](../../../../dummy-link.md)



### I. ¿Cómo funciona?

El módulo **X-NODE Digital Inputs** posee un controlador en hardware integrado con el cual es posible obtener la lectura de diversas entradas digitales sin tener conocimientos avanzados de hardware, ya que solo es necesario enviar una serie de comandos en formato ASCII por medio del protocolo de comunicación serial UART o usando el protocolo I2C, esto permite que el X-NODE sea compatible con cualquier sistema basado en un microcontrolador, microprocesador o equipos industriales.

**X-NODE Digital Inputs** es compatible con el estándar [**mikroBUS™**](https://www.mikroe.com/mikrobus) de [**Mikroe®**](https://www.mikroe.com/) para un uso fácil con un gran ecosistema de kits para desarrollo de hardware, también posee conectores JST compatibles con el estándar [**Qwiic®**](https://www.sparkfun.com/qwiic) de [**SparkFun®**](https://www.sparkfun.com/) para una comunicación entre diversos módulos y tarjetas de desarrollo por medio del protocolo I2C de manera rápida y sencilla.

### **II. Descripción del hardware**

<figure><img src="https://docs.microside.com/~gitbook/image?url=https%3A%2F%2F177299348-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FbyV2zAlQAiqg46a3Lr8z%252Fuploads%252FVkNZDxNxeky7yICpbkvJ%252FXN01%2520descripcion%2520de%2520hardware.jpg%3Falt%3Dmedia%26token%3Dc690358e-28c6-4160-ab00-e20016ce65cb&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=1459f20c&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. Puerto serigrafiado con pines macho y orificios para entradas digitales
2. Switch deslizable
3. Conectores JST compatibles con [**Qwiic®**](https://www.sparkfun.com/qwiic)
4. Controlador en hardware
5. Puertos de comunicación UART <> I2C
6. Modelo de X-NODE
7. Tipo de X-NODE
8. Conectores estándar [**mikroBUS™**](https://www.mikroe.com/mikrobus)
9. Versión de hardware R1
10. Componente principal en el X-NODE

### **III. Especificaciones**

<table data-header-hidden><thead><tr><th width="167"></th><th></th></tr></thead><tbody><tr><td><strong>Tipo</strong></td><td>Entradas digitales</td></tr><tr><td><strong>Aplicaciones</strong></td><td>Integración en proyectos de IoT y uso de propósito general, como en cambios de estado, secuencias o configuración en indicadores y actuadores de un circuito o proyecto electrónico.</td></tr><tr><td><strong>Características</strong></td><td>Switch deslizable de 8 interruptores tipo palanca, vida eléctrica de hasta 2000 ciclos, una resistencia de aislamiento de hasta 100 MΩ y puede operar en un rango de temperatura de -10 °C hasta 80 °C. Puerto de pines macho y orificios para 8 entradas externas y GND.</td></tr><tr><td><strong>Interfaz</strong></td><td>UART, I2C</td></tr><tr><td><strong>Compatibilidad</strong></td><td>Estándar <a href="https://www.mikroe.com/mikrobus"><strong>mikroBUS™</strong></a> y estándar <a href="https://www.sparkfun.com/qwiic">Qwiic®</a></td></tr><tr><td><strong>Tamaño</strong></td><td>65.15 x 25.4 x 20.5 mm</td></tr><tr><td><strong>Voltaje</strong></td><td>3.3 V</td></tr></tbody></table>

### **IV. Pinout**

La siguiente tabla muestra el pinout del **X-NODE Digital Inputs** con respecto al estándar [**mikroBUS™**](https://www.mikroe.com/mikrobus) (este último se encuentra en las dos columnas del centro).

<figure><img src="https://docs.microside.com/~gitbook/image?url=https%3A%2F%2F177299348-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FbyV2zAlQAiqg46a3Lr8z%252Fuploads%252F2FVExt0zz2AKEpXGoAfA%252Fimage.png%3Falt%3Dmedia%26token%3D0aad2f68-f4fa-4010-9d1b-1d51cd1075b8&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=6ee9d75d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

### **V. Modo de uso**

Para un uso fácil y rápido del X-NODE se puede hacer a través de los comandos en formato ASCII que proporciona el controlador en hardware integrado mediante una comunicación serial UART o de forma más avanzada a través del protocolo I2C.

#### Protocolo UART <a href="#protocolo-uart" id="protocolo-uart"></a>

Para poder establecer comunicación con el X-NODE se debe conocer el **ID**, éste se conforma por el **modelo** que se localiza en el punto 6 del apartado “Descripción de hardware”, con la clave “XN01” y se complementa con un **index** que por defecto es la letra “A“, siendo posible configurarlo hasta la letra Z del abecedario, brindando la posibilidad de conectar hasta 10 módulos del mismo tipo.\


<figure><img src="https://docs.microside.com/~gitbook/image?url=https%3A%2F%2Fmicroside.com%2Fwp-content%2Fuploads%2F2022%2F03%2FX-NODE-XN01-MICROSIDE_01-576x240.jpg&#x26;width=400&#x26;dpr=2&#x26;quality=100&#x26;sign=a0e96747&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### **Configuración**

* Velocidad de comunicación: 115,200 bps
* Paridad: Ninguna
* Bits de datos: 8
* Bits de paro: 1

#### Lista de comandos

| **XN01A?\<CR+LF>**                                                           | <p>Verifica si se estableció una comunicación con éxito.</p><p><strong>Respuesta:</strong> OK&#x3C;CR+LF></p>                                                                                                                                                                                                                                                                                                                                        |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **XN01A+V\<CR+LF>**                                                          | <p>Obtiene la versión del firmware actual que integra el X-NODE.</p><p><strong>Respuesta:</strong> XN01A=Versión&#x3C;CR+LF></p><p><strong>Ejemplo:</strong> XN01A=0.1&#x3C;CR+LF></p>                                                                                                                                                                                                                                                               |
| <p><strong>XN01A+ID=</strong></p><p><strong>(A-Z)&#x3C;CR+LF></strong></p>   | <p>Cambia el index del ID por una letra diferente del abecedario de la A a la Z, la nueva letra debe ser en mayúscula. Una vez modificado, para volver a cambiarlo es necesario colocar el ID con el nuevo index.</p><p><strong>Respuesta:</strong> OK&#x3C;CR+LF></p><p><strong>Ejemplo de envío:</strong> XN01C+ID=H&#x3C;CR+LF></p>                                                                                                               |
| <p><strong>XN01A+TW=</strong></p><p><strong>(1-126)&#x3C;CR+LF></strong></p> | <p>Cambia el address I2C que viene de fábrica por uno diferente. El nuevo address se escribe en decimal seleccionando un valor de 1 a 126.</p><p><strong>Respuesta:</strong> OK&#x3C;CR+LF></p><p><strong>Ejemplo de envío:</strong> XN01A+TW=28&#x3C;CR+LF></p>                                                                                                                                                                                     |
| **XN01A+GS\<CR+LF>**                                                         | <p><br>Obtiene el estado de cada una de las 8 entradas, sea en los interruptores o en el puerto. Retorna números 1 (Alto) y 0 (Bajo) dependiendo del estado de cada entrada. La entrada 1 es el primer valor de la izquierda, interpretándolo así el valor de izquierda a derecha.</p><p><strong>Respuesta:</strong> XN01A=int1, int2, int3, int4, int5, int6, int7, int8&#x3C;CR+LF></p><p><strong>Ejemplo:</strong> XN01A=11011011&#x3C;CR+LF></p> |

#### Protocolo I2C

Para poder establecer comunicación se debe conocer la dirección (address) del X-NODE, este se conforma por los dos últimos dígitos del modelo después de “XN”, el cual es necesario convertirlo a formato hexadecimal.

<figure><img src="https://docs.microside.com/~gitbook/image?url=https%3A%2F%2Fmicroside.com%2Fwp-content%2Fuploads%2F2022%2F03%2FX-NODE-XN01-MICROSIDE_02-638x251.jpg&#x26;width=400&#x26;dpr=2&#x26;quality=100&#x26;sign=1f539023&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Configuración

* Velocidad de comunicación: 100 kHz
* Address: 7 bits

{% hint style="warning" %}
**Nota:** Verifica que no cuentes con otro dispositivo con la misma dirección (Address), si es así es necesario cambiarla.
{% endhint %}

#### **Lectura:**

<figure><img src="https://docs.microside.com/~gitbook/image?url=https%3A%2F%2F177299348-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FbyV2zAlQAiqg46a3Lr8z%252Fuploads%252FkTYOpPI0yqo3gHMq1BDs%252Fimage.png%3Falt%3Dmedia%26token%3D3e5e3ce8-cec5-4dcc-a210-7faddafa0ccc&#x26;width=400&#x26;dpr=2&#x26;quality=100&#x26;sign=f44a7d45&#x26;sv=2" alt=""><figcaption></figcaption></figure>

### **VI. Descargas**

<table data-card-size="large" data-view="cards"><thead><tr><th align="center"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><mark style="color:green;"><strong>Esquemático</strong></mark></td><td><a href="../../../../dummy-link.md">dummy-link.md</a></td></tr><tr><td align="center"><mark style="color:green;"><strong>Dimensiones</strong></mark></td><td><a href="../../../../dummy-link.md">dummy-link.md</a></td></tr></tbody></table>

