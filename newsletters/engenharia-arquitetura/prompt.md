# Prompt — Engenharia e Arquitetura

Gere um resumo, em português, com os desenvolvimentos mais relevantes desde a última edição sobre Engenharia e Arquitetura de Software.

Explore principalmente:
- arquitetura de software e arquitetura distribuída;
- microserviços e monólitos modulares;
- Domain-Driven Design;
- design patterns e architectural patterns;
- system design;
- APIs e integração entre sistemas;
- mensageria e processamento assíncrono;
- performance, escalabilidade e resiliência;
- observabilidade;
- segurança de aplicações;
- engenharia de plataforma e DevEx;
- CI/CD, testes e qualidade;
- modernização de sistemas;
- casos reais de arquitetura;
- decisões arquiteturais e respectivos trade-offs;
- práticas adotadas por grandes sistemas e empresas.

Priorize conteúdo técnico intermediário ou avançado. Para cada item relevante, destaque o conceito ou novidade, por que importa, impacto ou aplicação arquitetural e trade-offs quando existirem.

Evite repetir assuntos apresentados em edições anteriores caso não haja evolução relevante.

## Publicação

- Formato: Markdown.
- Arquivo: `{ano}/{yyyy-MM-dd}.md`.
- Ao publicar um novo artigo, atualizar também o `README.md` desta pasta.
- O `README.md` deve manter os links dos artigos publicados no último ano, em ordem decrescente de data.

## Integridade e recuperação automática do histórico

**Regra permanente de integridade e recuperação automática do histórico (obrigatória em TODAS as execuções):**
1. Use a recorrência REAL configurada neste agendamento (dias, frequência e horário, no fuso America/Sao_Paulo) para calcular dinamicamente as **10 últimas datas de execução previstas que já venceram** (limitadas à data de criação do agendamento). Identifique também a data da **última edição efetivamente publicada**, consultando os arquivos reais na branch `master` e o README desta newsletter no GitHub. Verifique as 10 últimas datas previstas **e todas as ocorrências posteriores à última publicação real** até a data atual. Não use datas fixas, não considere apenas a edição imediatamente anterior e não trate um registro de execução concluída como prova de publicação. Para cada data prevista, confira o arquivo `newsletters/engenharia-arquitetura/{ano}/{yyyy-MM-dd}.md` e seu link no `newsletters/engenharia-arquitetura/README.md`, usando a categoria indicada no restante deste prompt. Uma data só está completa se ambos existirem e estiverem corretos.
2. Se existirem lacunas, publique as edições ausentes **da mais antiga para a mais recente**, inclusive quando edições posteriores já estiverem publicadas. Use a data histórica original no nome e título, sinalize que é recuperação retroativa e utilize SOMENTE notícias e fontes comprovadamente disponíveis até aquela data; para boletins semanais, respeite a janela original de cada edição. Não invente informações, não copie outra edição e não sobrescreva artigos válidos. Se somente o README estiver inconsistente, repare o índice, sem recriar o artigo.
3. Para cada data corrigida, grave o artigo e a atualização do README **num único commit** na `master` e confirme os dois arquivos publicados. Depois publique a edição atual, se ainda faltar. Se houver conflito com outra newsletter, releia o HEAD e reaplique apenas os arquivos pertinentes, sem force push. Preserve a ordenação decrescente de datas, mesmo em publicações retroativas.
4. Se não for possível recuperar todas as lacunas nesta execução, **relate as datas pendentes e o motivo** e retome a recuperação na próxima execução; não declare o histórico completo indevidamente. Nunca pause, desative, cancele, exclua ou substitua o agendamento devido a erros. **Nunca envie e-mail; publique exclusivamente no GitHub. Não altere dias, horários nem periodicidade.**
