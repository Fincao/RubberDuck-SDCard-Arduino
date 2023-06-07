<h1 align="center">RubberDuck com SDCard - Arduino <img height="33" width="33" src="https://github.com/Fincao/RubberDuck-SDCard-Arduino/blob/master/img/duckduckgo.svg" />.</h1>

<p align="center">
 <img alt="MICRO-PRO E SDCARD" src="https://github.com/Fincao/RubberDuck-SDCard-Arduino/blob/master/img/promicro-sdcard.jpg" width="355px">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![code with hearth by William](https://img.shields.io/badge/<%5C>%20with%20♥%20by-Will-red)](https://github.com/Fincao)
![Windows](https://img.shields.io/badge/Microsoft-Windows-blue?logo=Windows&style=flat)
![Apple](https://img.shields.io/badge/OSX-Apple-lightgrey?logo=Apple&style=flat)
![Linux](https://img.shields.io/badge/Linux-OS-blue?logo=Linux&style=flat)
![Arduino](https://img.shields.io/badge/Arduino-IDE-green?logo=Arduino&style=flat)

<br>
<p align="center">
Passo a passo 🚶 como criar seu proprio "RubberDuck com Scripts editaveis por um SDcard" 🔧.
</p>

<br>

# Requisitos.

 - 1º - Computador com IDE do arduino instalado (dãããã!).
 - 2º - Plaquinha Arduino **Pro Micro** + seu respectivo cabo USB.
 - 3º - Modulo **SDCard** para arduino.

# Conexões.

Abaixo segue as conexões físicas que devem ser feitas entre o Arduino e o modulo SDCard.

<br/>

 ARDUINO| SDCARD 
------------ | -------------
VCC | VCC | -
GND   | GND | -
D15  | SCK | -
D4 | CS | -
D14   | MISO | -
D16   | MOSI | -

 <br>
 
 <img alt="MICRO-PRO E SDCARD" src="https://github.com/Fincao/RubberDuck-SDCard-Arduino/blob/master/img/sdcardCONNECT.png" width="555px">

 <br>
 
 - >Representação da conexão entre o **Pro-Micro** e **SDCard**.
 
 <br>
 
 # Considerações.
 
  - O cartão SD deve ser formatado em "Fat", não recomendo usar outro tipo de partição.
  - O passe o "payload" para dentro do SD (dããã²), "payload.txt".
  - Sketch escrito para **qualquer OS**, ![Windows](https://img.shields.io/badge/Microsoft-Windows-blue?logo=Windows&style=flat)
![Apple](https://img.shields.io/badge/OSX-Apple-lightgrey?logo=Apple&style=flat)
![Linux](https://img.shields.io/badge/Linux-OS-blue?logo=Linux&style=flat).
    - Cabe a você adaptar seu payload para o sistema alvo.
  - Projeto funciona em **Arduino Pro Micro**  &  **Arduino Leonardo** mudando apenas algumas configurações nas pinagens.
 
 <br>
 
 > Os códigos aqui contidos são apenas para estudo e me isento de qualquer uso para dano a si ou a terceiros. Use por sua conta e risco.
 
 </br>
 
 
##### Busco melhorar meus conhecimentos a toda hora, e para isso bebo muuuito café 😎.
<a href="https://ko-fi.com/williampedrodeoliveira" target="_blank"><img src="https://github.com/Fincao/Fake-Captive-Portal-ESP8266/blob/master/img/Kofi_Logo_Blue.svg" alt="Pay Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
 [![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H21K0OU)

