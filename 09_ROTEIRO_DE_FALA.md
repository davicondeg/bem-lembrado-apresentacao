# Roteiro de fala — Bem Lembrado

## Visão geral

- Duração-alvo: **9 min 20 s**;
- limite da professora: 7 a 10 minutos;
- cada integrante deve falar olhando para a turma, usando o slide apenas como apoio;
- as falas abaixo são um guia. Não precisam ser decoradas palavra por palavra;
- o protótipo e os dados de funcionamento devem ser apresentados oralmente como **simulação da solução planejada**.

## Divisão da apresentação

| Integrante | Slides | Assunto | Tempo |
|---|---:|---|---:|
| Pessoa 1 | 1–4 | Abertura, problema, público, impacto e solução | 2 min 05 s |
| Pessoa 2 | 5–7 | Protótipo, escopo, stakeholders e recursos | 2 min 25 s |
| Pessoa 3 | 8–11 | Requisitos, viabilidade, riscos e cronograma | 2 min 15 s |
| Pessoa 4 | 12–16 | Atividades, metodologia, resultados e encerramento | 2 min 20 s |
| Equipe | Transições | Passagens entre os integrantes | 15 s |
|  |  | **Total estimado** | **9 min 20 s** |

---

## Pessoa 1 — slides 1 a 4

### Slide 1 — Capa · 15 s

> Boa tarde. Nosso projeto se chama Bem Lembrado. Ele propõe apoiar pequenas rotinas de pessoas idosas pelo WhatsApp, mantendo familiares e contatos autorizados informados quando necessário. Nesta apresentação mostraremos o problema, a solução proposta, o planejamento e o protótipo inicial.

### Slide 2 — Problema · 35 s

> O problema identificado não é apenas esquecer uma atividade. Hoje, lembretes, anotações e mensagens ficam espalhados em diferentes lugares, e o familiar nem sempre sabe se a atividade foi realizada. Ao mesmo tempo, exigir um novo aplicativo pode criar uma barreira para parte do público idoso. Por isso, buscamos uma forma simples de enviar lembretes, registrar confirmações e identificar situações de não resposta usando um canal já conhecido. O dado de 84% vem da pesquisa TIC Domicílios 2024 e mostra a presença das mensagens instantâneas entre usuários de Internet com 60 anos ou mais.

### Slide 3 — Público e impacto social · 40 s

> O público principal são pessoas com 60 anos ou mais que já conseguem ler e responder mensagens no WhatsApp. Familiares, cuidadores e contatos autorizados formam o público secundário. A proposta é iniciar com um piloto de 10 a 20 idosos e seus responsáveis. Nas conversas exploratórias, apareceram necessidades como mensagens curtas, respostas simples e frequência controlada. O impacto esperado é ampliar a autonomia, reduzir cobranças repetitivas e tornar uma ausência de confirmação mais perceptível. O sistema não substitui o cuidado humano; ele aproxima a rede de apoio.

### Slide 4 — Proposta da solução · 35 s

> A solução possui duas experiências conectadas. O responsável utiliza um painel web para cadastrar pessoas e programar lembretes. A pessoa idosa recebe e responde pelo WhatsApp, sem precisar instalar outro aplicativo. O Supabase mantém dados e autenticação, enquanto o n8n executa as automações e integra o fluxo de mensagens. Regras críticas, como horários, alertas e permissões, permanecem no sistema. A inteligência artificial é usada apenas para apoiar a compreensão da linguagem.

### Passagem para a Pessoa 2

> Agora, a Pessoa 2 vai mostrar o protótipo desse fluxo e os limites definidos para o MVP.

---

## Pessoa 2 — slides 5 a 7

### Slide 5 — Protótipo inicial · 1 min 10 s

> Este é o protótipo visual do fluxo principal. Primeiro, o responsável agenda um lembrete pelo painel. No exemplo, o painel apresenta os lembretes do dia e seus estados: confirmado, agendado ou aguardando. Depois, a pessoa idosa recebe uma mensagem simples pelo WhatsApp e pode confirmar que realizou a atividade. Por fim, a resposta atualiza o status e o histórico no painel. Se não houver confirmação dentro da regra configurada, o sistema poderá sinalizar o contato autorizado. O que mostramos é uma simulação do comportamento planejado para o MVP; a integração funcional completa será realizada e validada na próxima etapa.

### Slide 6 — Escopo inicial · 35 s

> Para proteger prazo e qualidade, definimos limites claros para o MVP. Entram autenticação, cadastros, consentimento, agendamento, envio, histórico, confirmação, adiamento e alerta de não resposta. Ficam fora diagnóstico, prescrição, atendimento médico, aplicativo próprio e operação comercial em escala. O fluxo mínimo de sucesso é cadastrar, enviar, receber uma resposta e registrar o histórico. Também consideramos como premissas o consentimento e a familiaridade básica com o WhatsApp.

### Slide 7 — Stakeholders e recursos · 40 s

> Os stakeholders com maior influência são a pessoa idosa, o responsável, a equipe e a instituição acadêmica. A Meta e os serviços externos também são relevantes porque afetam integração e disponibilidade. Os recursos tecnológicos incluem Next.js, Supabase, n8n, WhatsApp, OpenAI, Vercel, GitHub e Figma. A estimativa considera 175 horas de trabalho e orçamento de aproximadamente 17 mil reais, incluindo contingência. Também são necessários equipamentos, contas de teste, referências legais e documentação técnica.

### Passagem para a Pessoa 3

> Com os envolvidos e os recursos definidos, a Pessoa 3 vai apresentar os requisitos, a viabilidade e os riscos do planejamento.

---

## Pessoa 3 — slides 8 a 11

### Slide 8 — Requisitos iniciais · 35 s

> Foram definidos 18 requisitos iniciais: 10 funcionais e 8 não funcionais. Os funcionais representam as ações principais, como autenticar, cadastrar, agendar, enviar, interpretar respostas, manter histórico e emitir alertas. Os não funcionais tratam da qualidade e das restrições, com destaque para segurança, LGPD, linguagem acessível, tratamento de falhas, limites da IA e rastreabilidade. Cada requisito foi relacionado a uma atividade e a um responsável.

### Slide 9 — Viabilidade · 35 s

> Para fins acadêmicos e de demonstração, o projeto foi considerado viável técnica, operacional, temporal e economicamente. O prazo previsto é de sete semanas, com 175 horas de equipe, estimativa preliminar de 144 pontos de função e orçamento de 16,9 mil reais. Essas estimativas estão detalhadas na documentação e incluem trabalho, serviços e contingência. Para uma implantação real, seria necessário revisar custos, infraestrutura, políticas da Meta, suporte e dependências externas.

### Slide 10 — Riscos iniciais · 35 s

> Foram identificados nove riscos e quatro receberam maior prioridade. Os principais são a integração com a Meta, o uso inadequado da IA, privacidade e LGPD e o aumento de escopo. Para cada risco definimos probabilidade, impacto e resposta. Por exemplo, regras críticas ficam fora da IA, dados são minimizados e a integração com o WhatsApp deve ser testada desde o início. Também monitoramos falhas do n8n, custos, dificuldade de uso e atrasos da equipe.

### Slide 11 — Cronograma inicial · 30 s

> O cronograma inicial organiza o desenvolvimento em sete semanas. Primeiro são definidos escopo, requisitos e arquitetura. Em seguida vêm banco, autenticação, painel e integração. Depois são implementados cadastro, respostas, histórico e alertas. A IA entra somente quando o fluxo principal estiver estável. As últimas semanas são destinadas à estabilização, aos testes e à validação. A sequência evidencia as principais dependências do projeto.

### Passagem para a Pessoa 4

> Para concluir, a Pessoa 4 vai detalhar os marcos das atividades, a metodologia de gestão e os próximos passos.

---

## Pessoa 4 — slides 12 a 16

### Slide 12 — Atributos das atividades · 30 s

> Além das semanas, cada atividade possui duração, responsáveis, dependências e um marco verificável. Por exemplo, painel e cadastros dependem do banco e da autenticação e devem resultar no primeiro cadastro funcional. A integração com WhatsApp depende das credenciais e do banco e deve entregar o fluxo sem IA. Documentação, frontend e preparação dos testes podem avançar em paralelo quando não dependem da mesma entrega técnica.

### Slide 13 — Metodologia de gestão · 35 s

> A equipe adotou Scrum de forma adaptada para organizar ciclos semanais e Kanban no GitHub Projects para acompanhar o fluxo contínuo. Cada tarefa passa por a fazer, em andamento, revisão ou teste e concluído. Uma entrega só é considerada concluída quando apresenta resultado demonstrável, atende aos critérios de aceite, possui testes executados, defeitos críticos tratados e documentação atualizada. Responsabilidades também foram distribuídas conforme as áreas de cada integrante.

### Slide 14 — Resultados, desafios e aprendizados · 30 s

> Nesta etapa, os resultados alcançados são de pesquisa e planejamento: quatro conversas exploratórias, 18 requisitos, nove riscos analisados, estimativa funcional e protótipo visual. Os maiores desafios foram integrar serviços externos, equilibrar autonomia e acompanhamento e manter o MVP controlado. O principal aprendizado foi separar regras críticas da IA e revisar continuamente as premissas e o escopo.

### Slide 15 — Cronograma da segunda etapa · 30 s

> Na segunda etapa, o trabalho seguirá cinco movimentos: integrar, testar, validar, ajustar e pilotar. Primeiro concluiremos o fluxo técnico. Depois testaremos segurança e falhas, validaremos a experiência com idosos e responsáveis e faremos os ajustes necessários. O piloto previsto terá entre 10 e 20 idosos. Os indicadores serão taxa de confirmação, tempo de resposta, conclusão sem ajuda e satisfação.

### Slide 16 — Encerramento · 15 s

> Em síntese, o Bem Lembrado utiliza uma tecnologia familiar para apoiar a autonomia e aproximar a rede de cuidado. Nosso próximo passo é transformar o protótipo em um fluxo integrado e validá-lo com usuários. Obrigado. Estamos à disposição para perguntas.

---

## Regras para a apresentação

1. Não ler tabelas linha por linha; explicar somente a lógica e os exemplos principais.
2. Não afirmar que o sistema já foi validado ou implantado.
3. Diferenciar sempre **resultado desta etapa** de **meta da próxima etapa**.
4. Quem não estiver falando deve olhar para o apresentador ou para a professora, não para o celular.
5. O integrante seguinte deve começar imediatamente após a passagem, sem pausa longa.
6. Se o tempo chegar a 8 min 30 s antes do slide 15, resumir os slides 15 e 16 em aproximadamente 30 segundos.
