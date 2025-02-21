# Practica 1 - Blink LED

## **Introducción**

La siguiente práctica es una de las más básicas en programación de microcontroladores, consiste en controlar el encendido y apagado de un LED cada determinado tiempo.

## **Descripción**

En esta práctica se utiliza el LED que se encuentra conectado al pin A4 de la tarjeta **X-TRAINER** con el **PIC18F4550/PIC18F45K50**. El pin A4 es configurado como salida y señal digital, de esta forma enciende y apaga el LED cada determinado tiempo.

**Materiales:**

1 x Tarjeta **X-TRAINER**. [**Manuales**](https://microside.com/docs/#manuales-microside) | [**Comprar**](https://store.microside.com/search/?q=x-trainer+pic18)

1 x Cable micro USB.

**Software:**

Windows 7 o posterior.

mikroC PRO Compiler. [**Descarga**](https://www.mikroe.com/mikroc-pic)

MICROSIDE v1.0 [**Descarga**](https://microside.com/wp-content/uploads/2021/12/MICROSIDE_v1_Instalador-1-1.zip)

## **Procedimiento**

**1.** En el apartado de “Diagrama Esquemático” que se encuentra a continuación, selecciona el modelo de tu tarjeta, realiza las conexiones que se muestran en la imagen y conéctalo a la computadora. **Nota:** Las conexiones mostradas en los diagramas esquemáticos son las mismas ya sea que la tarjeta **X-TRAINER** posea el **PIC18F4550/PIC18F45K50**.

**2.** Al final de esta práctica, en el apartado de “Descargas”, puedes encontrar los archivos del código fuente.

**3.** Ejecuta **mikroC PRO compiler**, abre el archivo descargado y compila el programa. En el siguiente [**link**](https://microside.com/docs/mikroc/manual-mikroc-pro-for-pic/) encontrarás un manual para compilar en mikroC PRO compiler.

**4.** Abre el Software **MICROSIDE v1.0** y programa el código que descargaste y compilaste en la tarjeta. En el siguiente[ **link**](https://microside.com/docs/manual-software-microside-v1/) encontrarás el manual de usuario para el Software **MICROSIDE v1.0**.

**5.** Al terminar de programar, la tarjeta **X-TRAINER** se reiniciará y el programa de esta práctica se ejecutará.

## **Diagrama esquemático**

{% tabs %}
{% tab title="X-TRAINER LITE M" %}
<figure><img src="https://raw.githubusercontent.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/main/Diagrama%20de%20conexi%C3%B3n/X-TRAINER_PIC18F45K50_PIC18F4550_MICROSIDE_01.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="X-TRAINER LITE F" %}
<figure><img src="https://github.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/blob/40c1d2db71578483a9a942b71348702fb34450f8/Diagrama%20de%20conexi%C3%B3n/X-TRAINER_PIC18F45K50_MICROSIDE_02.png?raw=true" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="X-TRAINER DIP" %}
<figure><img src="https://raw.githubusercontent.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/40c1d2db71578483a9a942b71348702fb34450f8/Diagrama%20de%20conexi%C3%B3n/X-TRAINER_DIP_Practica-1_Microside_01-768x175.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="X-TRAINER PRO" %}
<figure><img src="https://github.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/blob/40c1d2db71578483a9a942b71348702fb34450f8/Diagrama%20de%20conexi%C3%B3n/X-TRAINER_PIC18F45K50_MICROSIDE_03.png?raw=true" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## **Código**

{% tabs %}
{% tab title="PIC18F45K50" %}
{% @github-files/github-code-block url="https://github.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/blob/main/Proyecto/4550/blink_led.c" %}
{% endtab %}
{% endtabs %}

[1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50](https://github.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/archive/refs/heads/main.zip)

{% file src="../../.gitbook/assets/demo.txt" %}

{% content-ref url="../../Blink%20led%20pic18F45k50/" %}
[Blink%20led%20pic18F45k50](../../Blink%20led%20pic18F45k50/)
{% endcontent-ref %}

{% @github-files/github-code-block url="https://github.com/vhperaltaj/1-Blink-LED-mikroC-PRO-for-PIC-PIC18F4550-45K50/archive/refs/heads/main.zip" %}

Este texto va después del archivo de descarga
