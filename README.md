# DigitalRepublic Code Challenge

## Objetivo da aplicação

Uma aplicação web que ajude o usuário a calcular a quantidade de tinta necessária para pintar uma sala.
Essa aplicação deve considerar que a sala é composta de 4 paredes e deve permitir que o usuário escolha qual a medida de cada parede e quantas janelas e portas possuem cada parede.
Com base na quantidade necessária o sistema deve apontar tamanhos de lata de tinta que o usuário deve comprar.

## Regras de negócio

1. Nenhuma parede pode ter menos de 1 metro nem mais de 15 metros, mas podem possuir alturas e larguras diferentes
2. O total de área das portas e janelas deve ser no máximo 50% da área de parede
3. A altura de paredes com porta deve ser, no mínimo, 30 centímetros maior que a altura da porta
4. Cada janela possui as medidas: 2,00 x 1,20 mtos
5. Cada porta possui as medidas: 0,80 x 1,90
6. Cada litro de tinta é capaz de pintar 5 metros quadrados
7. Não considerar teto nem piso.
8. As variações de tamanho das latas de tinta são:
    1. 0,5 L
    2. 2,5 L
    3. 3,6 L
    4. 18 L

## Instalar o Quasar Framework CLI
https://quasar.dev/quasar-cli/installation

## Instalar Dependências
```bash
npm install
```
### Rodando o projeto em modo dev
```bash
quasar dev
```
### Lint
```bash
npm run lint
```
### Compilando aplicação para produção
```bash
quasar build
```
