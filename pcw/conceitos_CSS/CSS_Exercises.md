# Adicionando CSS

-   28/02/2023

Quando um navegador lê uma folha de estilo, ele formata o documento HTML de acordo com as informações da folha de estilo. E existem três maneiras de inserir uma folha de estilo, sendo elas:

## Inline style (Estilo inline)

Esse tipo é utilizado para estilizar somente aquele elemento, não passando a regra para mais nenhum outro. Sua prioridade é máxima, sobrepondo qualquer estilo aplicado nas opções abaixo.

Por ser muito específico, é melhor evitar esse tipo de estilização por ser muito difícil na manutenção do código.

## Internal style (Estilo incorporado)

Aplicado dentro da tag `<style>`, esse tipo é utilizado para estilizar a página inteira, sendo aplicado em todos os elementos daquela página e fica sempre dentro da tag `<head>`. Com uma prioridade média, sobrepõe somente o `external style` abaixo.

Também é um tipo específico de estilização, e por isso também é melhor evitar esse tipo de estilização por ser difícil na hora da manutenção do código.

## External style (Estilo Importado)

Esse tipo aplica, assim como no exemplo anterior, o estilo na página inteira, mas por ser externo pode ser reutilizado em diversas páginas. Sua prioridade é mínima e não sobrepõe nenhuma das opções acima.

Por ser de utilização global e poder ser reutilizado por todo o projeto, é o mais indicado a ser usado.

&nbsp;

Fontes da pesquisa: [website 1 ](https://www.w3schools.com/CSS/css_howto.asp), [website 2](https://wmerussi.com.br/css-primeiros-passos/).

&nbsp;

# Exercícios

1. R: Abra o `index.html` da pasta 'Exercise_01'. 

2. R: Abra o `index.html` da pasta 'Exercise_02'. 

3. R: Abra o `index.html` da pasta 'Exercise_03'. 

4. R: A cor final do `body` será vermelho, pois apesar de no exercício 3 definirmos um estilo incorporado para a página HTML com a cor marrom, a cor vermelha já havia sido definida com estilização inline no exercício 2.

&nbsp;

# Alunos

## Lucas Matos Foltran

## Luiz Fabiano




