### Luis Lelis

Economista (UFPR) e consultor. Implanto IA em operações reais: equipes pequenas, prazos curtos, erro público caro. Nos últimos anos isso significou campanhas eleitorais. Já assessorei mais de 200, e em 2026 operei a minha própria candidatura com os sistemas abaixo.

O que procuro mostrar aqui não é "usei IA", e sim **como colocar IA para trabalhar com controle**:

- quem produz não verifica;
- o humano aprova antes de qualquer ação externa;
- simulação antes de executar;
- auditoria do resultado, não do texto;
- números que se reproduzem.

#### Projetos

| Repositório | O que é | Padrão que se transfere para empresas |
|---|---|---|
| [**agentes-ia-com-supervisao-humana**](https://github.com/loucytconsultoria/agentes-ia-com-supervisao-humana) | Playbook de implantação de agentes: base de conhecimento destilada de ~24 mil mensagens com níveis de confidencialidade, agentes derivados de um agente-mestre, avaliação com red team, teste cego e holdout, bots com aprovação humana e operação 24/7 com monitoramento | Atendimento, SAC, CRM e backoffice com IA e governança |
| [**anuncios-meta-com-ia**](https://github.com/loucytconsultoria/anuncios-meta-com-ia) | Coleta da Biblioteca de Anúncios da Meta (~40 mil anúncios), leitura de ~17 mil criativos por subagentes com vocabulário fechado, auditoria e consenso de 3 verificadores, e automação idempotente da Marketing API | Classificação em lote auditada (tickets, notas, avaliações) e automação segura de mídia |
| [**edicao-de-video-com-ia**](https://github.com/loucytconsultoria/edicao-de-video-com-ia) | Motor de edição: Whisper e alinhamento fonético forçado, plano de edição (EDL) aprovado por uma pessoa, render determinístico e portões de qualidade que medem o vídeo final | Conteúdo, treinamento e cortes de webinar em escala |
| [**impulsionamento-digital-eleicoes**](https://github.com/loucytconsultoria/impulsionamento-digital-eleicoes) | Pesquisa econométrica (TCC, artigo no ANPEC Sul 2026): retorno do gasto digital sobre votos, pipeline R reprodutível por md5 reconstruído com IA sob auditoria, diagnósticos e modelo de orçamento em Python | Mix de marketing, retorno por canal e modelo que diz quando não confiar nele |
| [**apuracao-ao-vivo**](https://github.com/loucytconsultoria/apuracao-ao-vivo) | Painel estático que lê os dados públicos do TSE a cada 30 s e calcula a distribuição de vagas, validado contra 399 de 399 câmaras. [Demonstração ao vivo](https://loucytconsultoria.github.io/apuracao-ao-vivo/?demo=1) | Regra de negócio complexa, codificada e testada contra o histórico, sem backend |
| [**ia-e-decisao-eleitoral**](https://github.com/loucytconsultoria/ia-e-decisao-eleitoral) | Ensaio acadêmico sobre a proibição de LLMs recomendarem candidatos, com uma proposta de *match* eleitoral público | Leitura de regulação de IA e riscos de LLMs com olhar de produto |

#### Ferramentas

Claude Code (agentes, skills, subagentes, workflows) · Python · R (glmmTMB, renv) · ffmpeg · faster-whisper · APIs da Meta (Ad Library, Marketing, Graph), ClickUp e Discord · Linux, systemd e cron · JavaScript estático.

Todos os exemplos usam dados públicos, sintéticos ou de uma cliente fictícia. Nenhum dado de cliente real está publicado.
