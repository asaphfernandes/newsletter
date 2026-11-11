# Prompt — .NET

Gere um resumo semanal, em português, com os desenvolvimentos mais relevantes da última semana no ecossistema .NET.

Explore principalmente:
- .NET e C#;
- ASP.NET Core e desenvolvimento de APIs;
- performance;
- segurança, autenticação e autorização;
- Entity Framework Core;
- Native AOT;
- gRPC e SignalR;
- bibliotecas relevantes e NuGet;
- tooling;
- Visual Studio e VS Code relacionados a .NET;
- .NET Aspire;
- .NET MAUI;
- arquitetura aplicada ao ecossistema .NET;
- previews, releases e roadmaps;
- mudanças futuras relevantes na plataforma.

Priorize anúncios oficiais, análises técnicas aprofundadas, benchmarks, novas bibliotecas e mudanças que possam afetar decisões de desenvolvimento ou arquitetura.

Para cada item relevante, destaque o impacto prático para quem desenvolve aplicações modernas em .NET.

Evite tutoriais básicos e pequenas atualizações sem impacto relevante.

## Publicação

- Formato: Markdown.
- Arquivo: `{ano}/{yyyy-MM-dd}.md`.
- Ao publicar um novo artigo, atualizar também o `README.md` desta pasta.
- O `README.md` deve manter os links dos artigos publicados no último ano, em ordem decrescente de data.

## Integridade e recuperação automática do histórico

**Regra permanente de integridade e recuperação automática do histórico (obrigatória em TODAS as execuções):**
1. Use a recorrência REAL configurada neste agendamento (dias, frequência e horário, no fuso America/Sao_Paulo) para calcular dinamicamente as **10 últimas datas de execução previstas que já venceram** (limitadas à data de criação do agendamento). Identifique também a data da **última edição efetivamente publicada**, consultando os arquivos reais na branch `master` e o README desta newsletter no GitHub. Verifique as 10 últimas datas previstas **e todas as ocorrências posteriores à última publicação real** até a data atual. Não use datas fixas, não considere apenas a edição imediatamente anterior e não trate um registro de execução concluída como prova de publicação. Para cada data prevista, confira o arquivo `newsletters/dotnet/{ano}/{yyyy-MM-dd}.md` e seu link no `newsletters/dotnet/README.md`, usando a categoria indicada no restante deste prompt. Uma data só está completa se ambos existirem e estiverem corretos.
2. Se existirem lacunas, publique as edições ausentes **da mais antiga para a mais recente**, inclusive quando edições posteriores já estiverem publicadas. Use a data histórica original no nome e título, sinalize que é recuperação retroativa e utilize SOMENTE notícias e fontes comprovadamente disponíveis até aquela data; para boletins semanais, respeite a janela original de cada edição. Não invente informações, não copie outra edição e não sobrescreva artigos válidos. Se somente o README estiver inconsistente, repare o índice, sem recriar o artigo.
3. Para cada data corrigida, grave o artigo e a atualização do README **num único commit** na `master` e confirme os dois arquivos publicados. Depois publique a edição atual, se ainda faltar. Se houver conflito com outra newsletter, releia o HEAD e reaplique apenas os arquivos pertinentes, sem force push. Preserve a ordenação decrescente de datas, mesmo em publicações retroativas.
4. Se não for possível recuperar todas as lacunas nesta execução, **relate as datas pendentes e o motivo** e retome a recuperação na próxima execução; não declare o histórico completo indevidamente. Nunca pause, desative, cancele, exclua ou substitua o agendamento devido a erros. **Nunca envie e-mail; publique exclusivamente no GitHub. Não altere dias, horários nem periodicidade.**
