# Prompt — Consultoria e Negócios

Gere um resumo semanal, em português, com os acontecimentos e tendências mais relevantes da última semana sobre negócios de tecnologia, software e consultoria.

Explore principalmente:
- mercado de consultoria tecnológica;
- serviços de desenvolvimento e arquitetura;
- transformação digital;
- adoção empresarial de IA;
- SaaS e monetização de software;
- modelos de negócio de empresas de tecnologia;
- criação de produtos digitais;
- oportunidades B2B;
- mudanças na forma como empresas contratam tecnologia;
- produtividade e impacto da IA sobre serviços profissionais;
- estratégias de empresas de software;
- fusões e aquisições relevantes;
- investimentos relevantes no setor;
- casos reais de empresas;
- novos mercados e oportunidades geradas por mudanças tecnológicas.

Priorize informações que possam gerar insights sobre oportunidades de consultoria, criação de produtos, posicionamento profissional, novos serviços e mudanças no mercado de software.

Evite notícias corporativas sem consequência prática.

## Publicação

- Formato: Markdown.
- Arquivo: `{ano}/{yyyy-MM-dd}.md`.
- Ao publicar um novo artigo, atualizar também o `README.md` desta pasta.
- O `README.md` deve manter os links dos artigos publicados no último ano, em ordem decrescente de data.

## Integridade e recuperação automática do histórico

**Regra permanente de integridade e recuperação automática do histórico (obrigatória em TODAS as execuções):**
1. Use a recorrência REAL configurada neste agendamento (dias, frequência e horário, no fuso America/Sao_Paulo) para calcular dinamicamente as **10 últimas datas de execução previstas que já venceram** (limitadas à data de criação do agendamento). Identifique também a data da **última edição efetivamente publicada**, consultando os arquivos reais na branch `master` e o README desta newsletter no GitHub. Verifique as 10 últimas datas previstas **e todas as ocorrências posteriores à última publicação real** até a data atual. Não use datas fixas, não considere apenas a edição imediatamente anterior e não trate um registro de execução concluída como prova de publicação. Para cada data prevista, confira o arquivo `newsletters/consultoria-negocios/{ano}/{yyyy-MM-dd}.md` e seu link no `newsletters/consultoria-negocios/README.md`, usando a categoria indicada no restante deste prompt. Uma data só está completa se ambos existirem e estiverem corretos.
2. Se existirem lacunas, publique as edições ausentes **da mais antiga para a mais recente**, inclusive quando edições posteriores já estiverem publicadas. Use a data histórica original no nome e título, sinalize que é recuperação retroativa e utilize SOMENTE notícias e fontes comprovadamente disponíveis até aquela data; para boletins semanais, respeite a janela original de cada edição. Não invente informações, não copie outra edição e não sobrescreva artigos válidos. Se somente o README estiver inconsistente, repare o índice, sem recriar o artigo.
3. Para cada data corrigida, grave o artigo e a atualização do README **num único commit** na `master` e confirme os dois arquivos publicados. Depois publique a edição atual, se ainda faltar. Se houver conflito com outra newsletter, releia o HEAD e reaplique apenas os arquivos pertinentes, sem force push. Preserve a ordenação decrescente de datas, mesmo em publicações retroativas.
4. Se não for possível recuperar todas as lacunas nesta execução, **relate as datas pendentes e o motivo** e retome a recuperação na próxima execução; não declare o histórico completo indevidamente. Nunca pause, desative, cancele, exclua ou substitua o agendamento devido a erros. **Nunca envie e-mail; publique exclusivamente no GitHub. Não altere dias, horários nem periodicidade.**
