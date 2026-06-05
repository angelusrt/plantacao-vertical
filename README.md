## Plantação vertical para pequenas hortaliças

A ideia do projeto é criar quatro estruturas:
- A prateleira
- O vaso conjugado para 4 hortas
- A caixa de água
- E a central de controle (onde ficará o IOT)

O propósito é tanto aprender sobre 
marcenaria, cultivo e engenharia; como, áreas mais comuns a mim, 
como: IOT, engenharia e ciência de dados, e engenharia de software.

Meu desejo é ter um vaso de madeira retangular de proporção 4x1, onde 
eu consiga compartimentalizá-lo, para que eu consiga controlar esses 4 
compartimentos diferentemente - para a realização de experimentos.

A restrição que eu tenho é minimizar o gasto e maximizar aprendizado (priorizando dados).

## Lista de compras

Para o hardware:
- 1 Raspberry PI (~R$600,00)
- ESP32 (~R$60,00)
- ESP32-CAM (~R$70,00)
- 4 sensor capacitivo de umidade do solo (~R$80,00)
- 1 sensor AHT20 (ou DHT22) (~R$30,00)
- 4 Servo sg90 (~R$100,00)
- 4 Bombinhas 5V Mini (R$140,00)

Para o vaso:
- Madeira de Pinus
- Mangueiras de 5mm de silicone [especificar metros]
- Conexões
- Acrílico
- Cola de madeira
- Cola solvente para acrílico
- Manta EPDM interna
- Verniz marítimo externo

Para a estante:
- [A planejar]

Para a caixa de água:
- 5 placas de acrílico 
- Cola de acrílico

## Modelando o vaso

A modelagem foi feita com o Blender 5.1.2 e o desenho das 
especificações técnicas com o FreeCAD 1.1.1.

### As dimensões

![Blueprint do vaso](./exports/vaso.svg)

Dimensões:
- comprimento: 20cm (útil) + 3cm (vãos para 2 tábuas de 15mm)
- largura: 80cm (útil) + 3cm (vãos para 2 tábuas de 15mm) + 1.5cm (vãos para 3 tábuas de 5mm)
- altura: 20cm (útil) + 1.5cm (sobra superior) + 1.5cm (encaixe para base de 15mm) 

Interno: 
20cm x 20cm x 20cm para cada compartimento.

Total:
23cm x 84.5cm x 23cm.

[Esqueci da base para a caixa de água de acrílico]
