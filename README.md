<h1 align="center">RubberDuck com SDCard - Arduino <img height="33" width="33" src="https://github.com/Fincao/RubberDuck-SDCard-Arduino/blob/master/img/duckduckgo.svg" />.</h1>

<p align="center">
 <img alt="MICRO-PRO E SDCARD" src="https://github.com/Fincao/RubberDuck-SDCard-Arduino/blob/master/img/promicro-sdcard.jpg" width="355px">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-green.svg)
[![code with hearth by William](https://img.shields.io/badge/<%5C>%20with%20♥%20by-Will-red)](https://github.com/Fincao)
![conexões simultaneas](https://img.shields.io/badge/10-Windows-blue?logo=Windows&style=flat)
![conexões simultaneas](https://img.shields.io/badge/OSX-Apple-lightgrey?logo=Apple&style=flat)
![conexões simultaneas](https://img.shields.io/badge/Linux-OS-blue?logo=Linux&style=flat)

<br>
<p align="center">
Passo a passo 🚶 como criar seu proprio "RubberDuck com Scripts editaveis por um SDcard" 🔧.
</p>

<br>

# Requesitos.

 - 1-Computador com IDE do arduino instalado (dãããã!).
 - 2-Plaquinha Arduino **Pro Micro** + seu respectivo cabo USB.
 - 3-Modulo **SDCard** para arduino.

<br/>

# Conexões.

Abaixo segue as conexões fisicas que devem ser feitas entre o Arduino e o modulo SDCard.

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
 
  - O cartão SD déve ser formatado em "Fat", não recomendo usar outro tipo de partição.
  - O passe o "payload" para dentro do SD (dããã²) "payload.txt".
  - Sketch escrito para **qualquer OS**, cabe a você adaptar seu payload para o sistema.  
  - Projeto funciona em Para **Arduino Pro Micro**  &  **Arduino Leonardo** mudando apenas algumas configurações nas pinagens.
 
 <br>
