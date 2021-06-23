

Projeto de PI
http://www.lilygo.cn/prod_view.aspx?TypeId=50003&Id=1138&FId=t3:50003:3
http://www.lilygo.cn/prod_view.aspx?TypeId=50033&Id=1237
https://micro.ros.org/
https://github.com/vitorfaccio/IFSC_2020-2_PI3_Faccio

https://drive.google.com/file/d/1IugnNUfNke4xHS9BnmuY3owpf2yVUg6o/view?usp=sharing

https://www.embarcados.com.br/embarcados-live-microros-ros2-no-seu-esp32/

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor


## Cronograma

- [ ] Pesquisa e Documentação sobre:
  - [ ] micro-ROS
  - [ ] FreeRTOS IDF Espressif
  - [ ] LILYGO® TTGO T-Beam V0.7
  - [ ] LILYGO®TTGO LORA32 V2.0
- [ ] Instalar ferramentas necessárias para desenvolvimento
- [ ] Assistir apresentação: [microROS: ROS2 no seu ESP32](https://www.youtube.com/watch?v=n2JenAqCLQQ)
- [ ] Separar material prático para aplicação
- [ ] Simular exemplo de micro-ROS no Gazebo
- [ ] Rodar sistema na placa T-Beam
- [ ] Implementar leitura GPS
- [ ] Transmitir e Receber dados via LoRa com LORA32
- [ ] Debug e Revisão
- [ ] Documentar

## Diagrama de Blocos

Uma visão geral do funcionamento pode ser visto nesse diagrama.



### Referências

https://www.freertos.org/



![Cube](./img/PE_configuration.png)

```dot
graph LR;
Feature-->B[Possui pai?];
B-- não -->C[Product];
B-- sim -->D["O pai é processado?"];
```
