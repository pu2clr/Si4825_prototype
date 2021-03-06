# Protótipo de um rádio AM, FM e OC de baixo custo com base no SI4825 

## Observação: Este documento ainda está em fase de construção e revisão. 


Este documento busca orientar o hobista em eletrônica e radioescuta em uma montagem de um rádio baseado no chip Si4825, da Silicon Labs. 
Muito mais que mostrar o passo a passo de como construir um rádio, este trabalho fornece um conjunto de informações, recomendações e boas práticas sugeridas pelo próprio fabricante do chip, bem como por outras fontes de informações, incluindo vídeos no Youtube. 

Na primeira versão do meu protótipo, apesar de não ter seguido à risca as recomendações da Silicon Lab, fui surpreendido com o excelente resultado. O principal documento utilizado para minha montagem foi o ["Si4825/36-A ANTENNA, SCHEMATIC, LAYOUT, ANDDESIGN GUIDELINES"](https://www.silabs.com/documents/public/application-notes/AN738.pdf), também denominado de AN738 e construído pela própria Silicon Labs. Este documento é completo e praticamente dispensa qualquer outra fonte de informação para montagem de um protótipo simples. Analisando outros projetos, incluindo de rádios comerciais como o Dunga VII da Motobras, encontrei pouca diferença em relação a proposta da Silicon Labs.  



Um destaque que pode oferecer um pouco de dificuldade é quanto à abordagem de seleção de bandas. __O esquema sugerido no no documento AN738, página 11 apresenta um circuito com 12 bandas, sendo 10 de Ondas Curtas__. A seleção de bandas no si4825 é dada por meio de rresisores. __No documento supracitado, na página 4, há uma tabela descrevendo os valores dos resistores para a seleção de cada banda. Ao todo, existem 41 configurações de bandas possíveis para o si4825__. Cabe o projetista do rádio ou hobista selecionar aquelas que mais se enquadram no requisitos do rádio ou protótipo a ser construído. 


O documento [AN738](https://www.silabs.com/documents/public/application-notes/AN738.pdf) prover informações sobre o si4825 com foco no projetista de rádio. Além disso, oferece um guia para seleção de antenas a serem utilizadas, layout de circuito impresso e configuração para seleção de bandas. 


## Passos para a montagem

1. Faça a montagem com base no circuito da página 11 do documento [AN738](https://www.silabs.com/documents/public/application-notes/AN738.pdf).
2. Selecione a configuração de bandas com base na  table apresentada na página 4 (Table 3. Band Sequence Definition for Si4825-A).



# Aquisição do Si4825

Cinco unidades do Si4825 podem ser adquiridas no eBay por aproximadamente R$12,00. Também é possível encontrar com preços variados na AliExpress.
Um simples busca no ebay ou AliExpress com a palavra "si4825" mostrará dezenas de fornecedores com preços variados. 


## Referências bibliográficas


1. [Si4825/36-A ANTENNA, SCHEMATIC, LAYOUT, ANDDESIGN GUIDELINES](https://www.silabs.com/documents/public/application-notes/AN738.pdf)
2. [BROADCAST MECHANICAL TUNING AM/FM/SW RADIO RECEIVER](https://www.silabs.com/documents/public/data-sheets/Si4825-A10.pdf)
3. [Si4825 DEMO BOARD USER’S GUIDE](https://www.silabs.com/documents/public/user-guides/Si4825DEMO.pdf)




## Vídeos

1. [Protótipo de Rádio AM, FM e OC baseado no Si4825A](https://youtu.be/LscqPhFYeGc)
2. [Teste em OC de um protótipo de rádio AM, FM e OC de baixo custo](https://youtu.be/ZS32zr9E_cw)




