# Shubnikov-de Haas (SdH) e Hall clássico

Shubnikov-de Haas é o nome dado à variação da resistividade de um material em função do campo magnético aplicado a ele. Em particular, ao variar continuamente o campo magnético observa-se oscilações na resistividade que estão intimamente relacionadas com a densidade e mobilidade dos portadores de carga elétrica. Como resultado, a devida análise dessas oscilações permite extrair essas informações do material. Por outro lado, o efeito Hall clássico refere-se à variação da resistividade transversão à corrente elétrica, a partir da qual é possível determinar a mobilidade de transporte dos portadores.

Este projeto contém scripts do Microcal Origin para obter a concentração de portadores e suas mobilidades quânticas, inclusive no caso de várias sub-bandas (consegui distinguir até três). Não obstante, esses scripts implementam uma abordagem inédita que desenvolvi no meu trabalho de mestrado, no Instituto de Física da Universidade de São Paulo: veja o apêndice B desse trabalho ([aqui](https://www.teses.usp.br/teses/disponiveis/43/43134/tde-07072004-104036/publico/IvanMS.pdf)). Além disso, os scripts permitem obter a mobilidade de transporte, sem distinguir as sub-bandas.

Os scripts foram originalmente criados para serem executados interativamente no [Microcal Origin](https://microcal-origin.software.informer.com/), versão 6. Ou seja, apesar de o script automatizar e agilizar boa parte da análise, o analista é indispensável nesse processo.

## Dependências
- `FIT.OGS` e `FFT.OTW` (ambos acompanham o Origin)

## Bugs
- Frequentemente ocorre de a rotina `GAUSS` determinar erroneamente o pico e sua posição para o caso da janela Hanning mais curta. Uma segunda (ou terceira) tentativa deve resolver. Ainda não sei a origem deste problema.
- Este script foi testado na versão 6.0 do Microcal Origin. Sabe-se que não funciona na versão 5.0.

## TODO
- Converter o script num módulo Python.
