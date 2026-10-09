# newsletter

Uma newsletter gerada por GPT.

## Cronograma

| Relatório                                                                          | Hora  |  Seg  |  Ter  |  Qua  |  Qui  |  Sex  |  Sáb  |  Dom  |
| ---------------------------------------------------------------------------------- | ----- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [AI — Diário](newsletters/ai/README.md)                                            | 08:00 |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |       |       |
| [Engenharia e Arquitetura](newsletters/engenharia-arquitetura/README.md)           | 08:30 |   ✅   |       |   ✅   |       |   ✅   |       |       |
| [.NET](newsletters/dotnet/README.md)                                               | 08:30 |       |   ✅   |       |       |       |       |       |
| [Front-end](newsletters/frontend/README.md)                                        | 09:00 |       |   ✅   |       |       |       |       |       |
| [Cloud + Kubernetes](newsletters/cloud-kubernetes/README.md)                       | 09:30 |       |   ✅   |       |       |       |       |       |
| [Consultoria e Negócios](newsletters/consultoria-negocios/README.md)               | 10:00 |       |   ✅   |       |       |       |       |       |
| [Economia + Reforma + Investimentos](newsletters/economia-investimentos/README.md) | 08:30 |       |       |       |   ✅   |       |       |       |
| [Tecnologia e Notícias](newsletters/tecnologia-noticias/README.md)                 | 09:00 |       |       |       |   ✅   |       |       |       |

## Estrutura

```text
newsletters/{tipo}/prompt.md
newsletters/{tipo}/README.md
newsletters/{tipo}/{ano}/{yyyy-MM-dd}.md
```

O `README.md` de cada newsletter funciona como sua home e mantém os links dos artigos publicados no último ano.
