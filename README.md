# Mi band 2

Esta é uma aplicação simples para comunicar a Mi Band 2 e o Android usando o Bluetooth, todas as comunicações não são criptografadas pela Xiaomi para que possamos coletar os dados solicitados / recebidos da Mi Band, você pode encontrar o UUID de cada serviço, tais como: frequência cardíaca, alarme e bateria.

**Serviços básicos:** 

UUID of Service: 0000fee0-0000-1000-8000-00805f9b34fb

Battery Info Characteristic: 00000006-0000-3512-2118-0009af100700

**Serviço de alerta** 

UUID of Service: 00001802-0000-1000-8000-00805f9b34fb

New Alert Characteristic: 00002a06-0000-1000-8000-00805f9b34fb
 
**Frequência cardiaca**

UUID of Service: 0000180d-0000-1000-8000-00805f9b34fb

Measurement Characteristic: 00002a37-0000-1000-8000-00805f9b34fb

Control Characteristic: 00002a39-0000-1000-8000-00805f9b34fb

Descriptor: 00002902-0000-1000-8000-00805f9b34fb

 Obs: Não foi incluído o código de emparelhamento, então você deve emparelhar seu dispositivo Mi band 2 primeiro usando o aplicativo Mi Fit e depois conecte-o.
