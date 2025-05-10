# Léxicos

## Introdução

O léxico funciona como uma notação que lista e define os símbolos (palavras ou expressões) usados em uma linguagem. Em Engenharia de Requisitos, seu papel central é identificar termos ou frases próprios do contexto social em que o sistema será aplicado. Cada símbolo do léxico é caracterizado por:

* **Noção**: o seu significado literal, aquilo que ele denota.
* **Impacto**: a sua conotação ou efeito prático, ou seja, a resposta gerada quando o símbolo é utilizado.

Para elaborar os léxicos do DeepSeek, adotamos a abordagem do **Léxico Ampliado da Linguagem (LAL)**, conforme proposta por Sayão e Carvalho. Nesse modelo, cada símbolo é classificado em uma das quatro categorias:

* **Sujeito**: identifica quem é o agente ou entidade responsável pela ação, enquanto o impacto descreve quais operações esse agente executa sobre o sistema ou ambiente.
* **Verbo**: detalha quem realiza determinada ação, em que momento ela ocorre e quais procedimentos a compõem; o impacto mapeia os efeitos dessa ação no contexto e os novos estados que podem emergir.
* **Objeto**: define o elemento ou recurso do sistema e suas associações com outros objetos; o impacto especifica que tipos de operações podem ser aplicadas a esse objeto.
* **Estado**: descreve a condição ou situação atual do sistema, indicando quais eventos o levaram a tal ponto, e o impacto projeta os estados seguintes possíveis a partir dessa condição.

Adotaremos um padrão uniforme para cada entrada do léxico, composto pelos seguintes campos:

- ID: identificador único do termo.
- Noção: significado literal que o termo denota
- Impacto: conotação ou efeito prático que sua aplicação produz no sistema.
- Classificação: categoria do símbolo (Sujeito, Verbo, Objeto ou Estado).
- Dicionário: sinônimos e expressões equivalentes.
- Rastreamento: Código Caso de Uso/Cenário

Esse esquema garante que todo termo usado no DeepSeek seja descrito de forma consistente, permitindo fácil reconhecimento e entendimento por todos os membros da equipe.



## Bibliografia

> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 10/05/2025.

> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 10/05/2025.


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 10/05/2025 |  1.0   | (#LX01) Definições iniciais. | [@Gabriela](https://github.com/gaubiela)   | -- |