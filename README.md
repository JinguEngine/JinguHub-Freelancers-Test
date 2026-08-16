# JinguHub-Freelancers-Test

Fonte pública dos anúncios da aba **Freelancers** do Jingu Hub.

## Modelo

- 1 anúncio = 1 GitHub Issue.
- O corpo contém um marcador estruturado `JINGU_FREELANCER_V1` gerado pelo Hub.
- O Hub carrega os anúncios ao vivo; não existe cache offline persistente para essa aba.
- Visualização é pública e não exige login.
- Criar, editar, encerrar e reagir exige autenticação GitHub no Hub.
- Comentários não são exibidos pelo Jingu Hub.
- ❤️ do Issue é a curtida exibida no Hub.

O workflow `sync-freelancer-labels.yml` converte apenas metadados Jingu válidos em labels visíveis no GitHub. Dados livres do Issue não são executados.

> **Ambiente TEST/QA:** anúncios deste repositório não pertencem ao mural público de produção.
