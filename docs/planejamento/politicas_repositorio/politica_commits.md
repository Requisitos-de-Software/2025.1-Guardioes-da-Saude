Padronização dos commits no projeto. 

## Semântica do Commit

Os commits devem seguir o seguinte padrão:

### Formato:
```
<tipo> (#código da tarefa): descrição
```

#### Código da tarefa:
- Referenciamento ao código da tarefa estabelecido no cronograma do trabalho

#### Tipos:
- :repeat: quando alguma alteração for feita
- :cool: quando melhorias de formato/estrutura da documentação
- :memo: quando adicionar/atualizar documentação
- :bug: quando consertar um problema
- :fire: quando remover código ou arquivos
- :lipstick: quando adicionar estilizações
- :bulb: quando adicionar ou alterar comentários
- :heavy_plus_sign: quando adicionar uma dependência
- :heavy_minus_sign: quando remover uma dependência

#### Descrição:
- Deve possuir no máximo 50 caracteres
- Deve estar em letras minúsculas
- Deve estar em pt-BR devido ao público alvo e aplicação escolhida

*Exemplo de commit:*
```
git commit -m ":memo: (#D02): adição da documentação da política de commits"
```

## Histórico de Versões


| Data       | Versão | Descrição                                 | Autor             | Revisor          |
| :--------: | :----: | :----------:                              | :---------------: | :---------------:|
| 13/04/2025 |  0.1   | Criação da política de commits           | [Ana Clara Borges](https://github.com/anabborges)| [Gabriela Alves](https://github.com/gaubiela)|