# micro-ROS-TTGO
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


Implementação de uma arquitetura sistólica para multiplicação de matrizes em FPGA

## Cronograma

- [ ] Exemplo
- [ ] Pesquisar tipos de arquiteturas
- [ ] Implementação da arquitetura escolhida
- [ ] Debug e Revisão
- [ ] Treinamento de uma NN simples para testar o funcionamento
- [ ] Verificar a diferença do desempenho com e sem a implementação
- [ ] Documentar

## Diagrama de Blocos

Uma visão geral do funcionamento pode ser visto nesse diagrama.

![Cube](./img/PE_configuration.png)

```dot
graph LR;
Feature-->B[Possui pai?];
B-- não -->C[Product];
B-- sim -->D["O pai é processado?"];
```
