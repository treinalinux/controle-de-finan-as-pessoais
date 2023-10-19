# Aplicação para controle de finanças pessoais

Aplicação para controle de finanças pessoais.

## Requistos técnicos solicitados

### 1.1 Resultado final

- **Plataforma:** Linux
- **Linguagem:** Java
- **Banco de Dados:** PostgreSQL
- **Lógica**:
  - Entrada de valores aumentando o saldo total;
  - Cadastro de contas no calendário, data de vencimento e se o vencimento é recorrente;
  - Edição de entradas;
  - Mover cadastro entre datas;
  - Saldo total vai sendo decrementado conforme as datas de vencimento;
  - Avisos com cores, ícones e mensagens personalizadas de atrasos ou previsão de não ter saldo suficiente;
- **Padrão de cores**: [Item 2.1](README.md#21-padrão-de-cores-do-projeto)
- **Publicado e versionado no GitHub**: [Item 3.1](README.md#31-publicado-e-versionado-no-github)

### 2.1 Padrão de cores do projeto

- **Cor Background:**`#FFFFFF`
- **Cor texto padrão:** `#202528`
- **Cor título e destaques:** `#6C5C82`
- **Cor notificação de aviso:** `#FFA938`
- **Cor notificação de atraso:** `#B8141E`
- **Cor notificação de sucesso:** `#AFEC3E`

**Obs:** Apenas o sistema de cores deve ser usado para controle (é possível usar combinação de cores sem mudar a cor original), exemplo a conta vai vencer em 5 dias e o saldo atual é negativo para o dia do vencimento, então deve ser o usado o aviso para o próximo pagamento. Mesmo que não exista dinheiro disponível para o dia do vencimento, ele ainda não venceu.

### 3.1 Publicado e versionado no GitHub

Para acomanhamento do projeto precisamos da publicação do projeto no seu GitHub, todos os commits da fase de desenvolvimento devem ser organizados seguindos os padrões do Conventional Commits.

- **Padrão de Versionamento:** [Versionamento Semântico MAJOR.MINOR.PATCH](https://semver.org/lang/pt-BR/)
- **Padrão de Commits:** [Conventional Commits 1.0.0](https://www.conventionalcommits.org/pt-br/v1.0.0/)


### Visão da tela principal

**SALDO ATUAL: R$ 950,00**

Últimos Pagamentos (VALOR DE SAÍDA) | Pagamentos de Hoje (VALOR TOTAL) | Próximos Pagamentos (VALOR PREVISTO)
:--------- | :------: | -------:
(cor atraso) | (cor sucesso) | (cor aviso)

![Imagem de exemplo de como seria a tela inicial](https://github.com/treinalinux/controle-de-financas-pessoais/blob/main/Imagens/tela_inicial_2.png)



