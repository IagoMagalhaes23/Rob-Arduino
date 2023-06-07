# Robô Arduino com módulo Bluetooth

## Resumo 
Em 2022 adquirir uma impressora 3D Ender 3. Particulamente eu tenho uma paixão por robótica móvel, então ter uma impressora tornou muitos sonhos possíveis. Um deles foi finalmente construir um pequeno **'SMARS modular robot'**, durante anos vi uma série de projetos com esse modelo e desde então quis montar algo parecido.
O robô é bem simples, utiliza o Arduino para controle e pode receber comandos via Bluetooth, porém, a sua criatividade pode te dar muitas novas funcionalidades!

## Introdução
O projeto é simples, através do canal no YouTube [3DELWORLD}(https://www.youtube.com/@3DELWORLD) é possível ver todo o processo de impressão e montagem do sistema. A aplicação é simplificada e de fácil reprodução.

## Peças 3D
A lista completa de peças 3D pode ser encontrada e baixadas no site [Thingiverse}(https://www.thingiverse.com/thing:2662828).

## Hardware
Para a construção deste robô você precisará das seguintes peças (componentes eletrônicos):
- 1 Arduino UNO REV3;
- 2 Motor N20;
- 1 L293D DC Motor Drive Shield;
- 1 HC-06 Bluetooth 2.0;
- 1 Sensor de distância do módulo ultrassônico;
- Fios do jumper da placa de ensaio;
- 1 Baterias de 9 volts.

## Código
O arquivo **'ControleBluetoothRobo.ino'** contém o algoritmo para realizar o controle do robô através do celular. Basta fazer o upload do arquivo para seu Arduino utilizando o Arduino IDE. O App utilizado para enviar comandos pelo celular é o **'Bluetooth RC Controller'** e pode ser encontrado facilmente na Play Store.
## Screenshots
- Robô com sensor ultrassônico
![image](https://github.com/IagoMagalhaes23/Rob-Arduino/assets/65053026/2dd6e6e4-6c65-4b28-84ba-1808981784b6)

- Robô com modulo Bluetooth
![image](https://github.com/IagoMagalhaes23/Rob-Arduino/assets/65053026/efd253fb-269a-4359-9a89-68b373054af9)

## Conclusão

## Referências
- [3D Printing Meets Robotics: How to Make Your Own SMARS Robot #3dprinting](https://www.youtube.com/watch?v=mft36w5Hl1I&list=LL&index=70&t=5s)
- [Como fazer o robô SMARS impresso em 3D 2023](https://3delworld.com/how-to-make-smars-robot-3d-printed-2023/)
- [SMARS modular robot](https://www.thingiverse.com/thing:2662828)
