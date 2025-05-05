# In or Out

## Metodologgia
Essa abordagem é considerada uma das mais diretas, pois envolve tomar uma decisão binária para cada requisito: In (dentro) ou Out (fora), indicando se ele deve ou não ser implementado na versão atual do projeto. Com o avanço do desenvolvimento, é possível revisitar os requisitos marcados como Out e reavaliá-los para considerar sua inclusão em fases futuras.

A técnica de priorização foi aplicada com a participação voluntária de três usuários/Clientes do aplicativo DeepSeek.

<figcaption align="center">Tabela 1: dados dos Participantes Voluntarios.</figcaption>

| Nome            | Idade   | Gênero   | Ocupação  | Cidade/Estado |
| --------------- | ------- | -------- | --------- | ------------- |
| Janaina | 20 anos | Feminino | Estudante Arquitetura| Barra dos Bugrres(MT)  |
| Kamila Dutra| 20 anos | Feminino | Estudante Medicina| Buenos Aires(ARG)  |
| Pedro Bueno| 20 anos | Masculino | Estudante Medicina| Buenos Aires(ARG)  |

<div style="text-align: center">
<p>Fonte: Fábio Gabriel</p>
</div>

## Aplicação: In or Out
<figcaption align="center">Tabela 2: Tabela de Priorização.</figcaption>

| **ID** | **Requisito**                                                                                                                      | **Categoria** | **In or Out** |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------- |
| #RF01  | Deve oferecer a possibilidade do usuário acionar a pesquisa na web                                                                 | Funcional     | IN            |
| #RF02  | Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking)                                 | Funcional     | IN            |
| #RF03  | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s | Funcional     | IN            |
| #RN01  | Deve fazer o uso da arquitetura DeepSeek-V3                                                                                        | Não funcional | IN            |
| #RN02  | Deve possuir versões para Android e iOS                                                                                            | Não funcional | IN            |
| #RF04  | Deve possuir a opção de login com conta Google/Apple ID                                                                            | Funcional     | IN            |
| #RF05  | Deve salvar chats entre plataformas                                                                                                | Funcional     | IN            |
| #RF06  | Melhorar as capacidades de "deep thinking"                                                                                         | Funcional     | OUT           |
| #RF07  | Deve haver um campo para a interação com a IA                                                                                      | Funcional     | IN            |
| #RF08  | Deve ser possível criar novos chats                                                                                                | Funcional     | IN            |
| #RF09  | Deve ser possível renomear um chat                                                                                                 | Funcional     | IN            |
| #RF10  | Os chats já utilizados devem poder ser acessados posteriormente                                                                    | Funcional     | IN            |
| #RF11  | Deve ser possível dar dislike em uma resposta da IA                                                                                | Funcional     | OUT           |
| #RF12  | Deve ser possível dar like em uma resposta da IA                                                                                   | Funcional     | OUT           |
| #RF13  | Deve ser possível copiar uma resposta da IA                                                                                        | Funcional     | IN            |
| #RF14  | Deve exibir citações de fontes e referências em respostas baseadas em documentos, indicando página, site e/ou trecho extraído      | Funcional     | OUT           |
| #RF15  | Deve ser possível alterar o idioma do sistema                                                                                      | Funcional     | IN            |
| #RF16  | Deve ser possível apagar conversas individuais ou de forma geral                                                                   | Funcional     | OUT           |
| #RF17  | Deve ser possível regenerar uma resposta da IA manualmente ou automaticamente no caso de erro de servidor ou sobrecarga            | Funcional     | IN            |
| #RF18  | O sistema deve exibir respostas formatadas em Markdown com possibilidade de edição                                                 | Funcional     | OUT           |
| #RF19  | Deve ser possível interromper respostas em andamento                                                                               | Funcional     | OUT           |
| #RF20  | Deve possuir uma API Pública                                                                                                       | Funcional     | IN            |
| #RF21  | Deve aceitar autenticação via token de acesso                                                                                      | Funcional     | OUT           |
| #RN03  | Deve guardar um histórico de conversas por 30 dias (não persistente sem salvar)                                                    | Não funcional | IN            |
| #RN04  | Deve fazer a exclusão automática de dados de upload                                                                                | Não funcional | IN            |
| #RN05  | Interface deve seguir diretrizes de usabilidade e acessibilidade                                                                   | Não funcional | IN            |
| #RF22  | Deve haver uma confirmação para limpar o histórico                                                                                 | Funcional     | IN            |
| #RN06  | Em caso de falha, deve retornar mensagens de erro claras                                                                           | Não funcional | OUT           |
| #RN07  | Sistema deve suportar múltiplas requisições simultâneas sem degradação                                                             | Não funcional | IN            |
| #RN08  | Processamento de arquivos grandes deve ocorrer em ≤10s e respostas simples em ≤2s                                                  | Não funcional | IN            |
| #RF23  | Suportar busca incremental (sugestões em tempo real)                                                                               | Funcional     | OUT           |
| #RF24  | Dados sensíveis devem ser criptografados em trânsito (TLS) e em repouso (AES-256)                                                  | Funcional     | IN            |
| #RF25  | Usuário deve controlar quais dados são compartilhados                                                                              | Funcional     | IN            |
| #RF26  | Autenticação multifator opcional para funcionalidades avançadas                                                                    | Funcional     | OUT           |
| #RF27  | Modo escuro e claro, com configuração manual e sincronização com o sistema                                                         | Funcional     | IN            |
| #RF28  | Tutorial interativo na primeira execução e destaque de recursos avançados                                                          | Funcional     | IN            |
| #RN09  | Disponibilizar informações sobre armazenamento e uso de dados                                                                      | Não funcional | OUT           |
| #RN10  | Especificar e permitir consentimento no uso de dados para re-treinamento ou venda de modelos                                       | Não funcional | IN            |
| #RF29  | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga)                                                           | Funcional     | IN            |
| #RF30  | Melhorar retenção de contexto em diálogos longos para evitar “esquecimento” ou mistura de informações previamente dadas.                                                                                  | Funcional     | IN            |
| #RN12  | Garantir estabilidade na geração de conteúdos pesados                                                                              | Não funcional | IN            |
| #RF31  | Implementar memória de contexto persistente entre conversas                                                                        | Funcional     | IN            |
| #RF32  | Permitir escolha de modelos (diferentes versões de IA)                                                                             | Funcional     | IN            |
| #RF33  | Permitir organização de conversas em pastas ou listas por tema                                                                     | Funcional     | IN            |
| #RF34  | Comandos de voz para entrada e saída de informações                                                                                | Funcional     | IN            |
| #RN13  | ≥ 95% dos usuários devem avaliar a usabilidade como “Fácil” ou “Muito fácil”                                                       | Não funcional | OUT           |
| #RN14  | ≥ 90% de concordância em “Interface clara e agradável”                                                                             | Não funcional | OUT           |
| #RN15  | ≤ 5% dos usuários devem relatar dificuldade em encontrar opções                                                                    | Não funcional | OUT           |
| #RF35  | Ajustar visualização do título ao passar o mouse para não cobrir outros elementos                                                  | Funcional     | OUT           |
| #RF36  | Instruções claras e contextualizadas sobre OCR na interface de envio de imagens                                                    | Funcional     | IN            |
| #RF37  | Conexão nativa com ferramentas populares (Google Drive, GitHub etc.)                                                               | Funcional     | IN            |
| #RF38  | Resumo automático de vídeos (importar links do YouTube)                                                                            | Funcional     | IN            |


<div style="text-align: center">
<p>Fonte: Fábio Gabriel</p>
</div>

## Bibliografia

> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. p. 318.


| Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 03/05/2025 |  0.1   | (#IO01) Resultado da técnica In or Out| [@Fabio](https://github.com/fabinsz)   | []() |



