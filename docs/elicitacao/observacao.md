# Observação

A técnica de observação consiste em observar um usuário da sistema utilizando ele. Ela pode ser feita passivamente ou ativamente, sendo que passivamente o observador não interfere enquanto ativamente o observador pode fazer perguntas e observações. Aplicamos ambas as formas em diferentes observações. Foi aos usuários que eles poderiam explicar o que estavam fazendo se quisessem.

## Aplicação

Para aplicarmos a observação, foram escolhidos dois usuários do sistema. Antes da observação foi explicado o que seria feito e o objetivo disso, contextualizando a disciplina e o aplicativo escolhido pelo grupo.

### Primeira observação

Alexia Cardoso, estudante de Engenharia de Software, mostrou e explicou a realização de uma tarefa frequente dela no DeepSeek. Ela apresentou o processo que faz de adaptação de currículo para adequação de vagas específicas. A usuária optou por explicar o processo além de fazê-lo para um maior entendimento e a observação foi feita de forma ativa, onde a observadora fez algumas perguntas sobre o uso da plataforma e quais funcionalidades a usuária mais utilizava. Além disso, Alexia comentou sobre outras situações que ela recorria ao uso de IA.

Gravação da observação: [Observação Alexia](https://youtu.be/qE3cUEjGY9k)

### Segunda observação

Mateus Vieira, estudante de Engenhariade Software, mostrou a realização de duas tarefas que ele já fez em plataformas como o DeepSeek. Essa observação foi feita de forma passiva, ou seja, a observadora não interferiu no processo. Primeiro, ele pediu para a IA gerar um email de pedido de férias em inglês para o seu trabalho, mandando informações como período de férias e pessoa para a qual seria enviado o email. Após isso, por ser um entusiasta por cubos mágicos, Mateus usou a IA para saber mais sobre os algoritmos necessários para montar um cubo mágico.

Gravação da observação: 

## Requisitos Elicitados

??? summary "TABELA DE REQUISITOS ELICITADOS" 

    | ID      | Técnica         | Categoria       | Descrição                                                                                                     | Status               | Observação         |
    |----- ----|-----------------|-----------------|---------------------------------------------------------------------------------------------------------------|----------------------|--------------------|
    | ROF01   | OBSERVAÇÃO    | Funcional       | Deve haver um campo para a interação com a IA.             | Implementado     | Em ambas as observações esse campo foi utilizado |
    | ROF02   | OBSERVAÇÃO    | Funcional       | Deve ser possível criar novos chats.       | Implementado         | Em ambas as observações esse requisito foi utilizado |
    | ROF03   | OBSERVAÇÃO    | Funcional       | Deve ser possível renomear um chat.      | Implementado     | Observação com Mateus Vieira  |
    | ROF04   | OBSERVAÇÃO    | Funcional       | Os chats já utilizados devem poder se acessados posteriormente.                         | Implementado     | Em ambas as observações esse requisito foi utilizado  |
    | ROF05   | OBSERVAÇÃO    | Funcional       | Deve ser possível dar dislike em uma resposta da IA.       | Implementado         | Observação com Alexia Cardoso |
    | ROF06   | OBSERVAÇÃO    | Funcional       | Deve ser possível dar like em uma resposta da IA.        | Implementado         | Observação com Alexia Cardoso |
    | ROF07   | OBSERVAÇÃO    | Funcional       | Deve ser possível copiar uma resposta da IA.             | Implementado     | Em ambas as observações esse requisito foi utilizado |
    | ROF08   | OBSERVAÇÃO    | Funcional   | As respostas devem ser capazes de disponibilizarem links.| Implementado     | Observação com Mateus Vieira |
    | ROF09   | OBSERVAÇÃO    | Funcional   | Deve ser possível alterar o idioma do sistema. | Implementado     | Observação com Alexia Cardoso |
    | ROF10   | OBSERVAÇÃO    | Funcional       | Deve ser possível apagar chats antigos.        | Implementado         | Observação com Alexia Cardoso |
    | ROF11   | OBSERVAÇÃO    | Funcional       | Deve ser possível regenerar uma resposta da IA.             | Implementado     | Observação com Alexia Cardoso |
    | ROF12   | OBSERVAÇÃO    | Funcional   | As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis.| Implementado     | Em ambas as observações esse requisito foi utilizado |

<div align="center">
    Autor: <a href="https://github.com/anabborges">Ana Borges</a>
</div>

## Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de requisitos: software orientado ao negócio. Rio de Janeiro: Brasport Livros e Multimídia, 2016. p. 159-163.

> WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013, p. 125-126.

</br>

| Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 04/05/2025 |  0.1   | (#O01) Documentação referente a técnica de observação.| [Ana Borges](https://github.com/anabborges)   | [Mateus](https://github.com/MVConsorte) |