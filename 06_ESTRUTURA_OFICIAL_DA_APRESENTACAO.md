# Estrutura oficial da apresentação — Bem Lembrado

## Decisão adotada

A apresentação terá como base uma narrativa de **9 slides**, planejada para **7 a 10 minutos**:

**problema real → público → solução → funcionamento → planejamento → protótipo e resultados → impacto → próximos passos**

O cenário-alvo é apresentar o protótipo pronto e funcionando. Enquanto a implementação estiver em finalização, resultados e funcionalidades deverão ser marcados internamente como:

- **Confirmado:** implementado e testado;
- **em finalização:** implementado parcialmente ou ainda em integração;
- **planejado:** ainda não demonstrável.

Somente itens confirmados serão apresentados como resultados alcançados na versão final.

## Slide 1 — Capa

### Mensagem principal

**Bem Lembrado** — assistente virtual de apoio à rotina da pessoa idosa pelo WhatsApp.

### Conteúdo

- Nome do projeto;
- subtítulo curto;
- integrantes;
- disciplina e instituição.

### Tempo sugerido

20 a 30 segundos.

## Slide 2 — O problema

### Mensagem principal

Lembretes espalhados e falta de confirmação dificultam a rotina da pessoa idosa e de seus familiares.

### Conteúdo

- Esquecimento de medicamentos previamente prescritos, consultas e tarefas;
- alarmes e anotações não informam ao familiar se o lembrete foi confirmado;
- aprender um aplicativo novo pode representar uma barreira;
- dado de contexto sobre uso de mensagens instantâneas por pessoas com 60 anos ou mais.

### Evidência qualitativa

Sintetizar as entrevistas: mensagens curtas, respostas simples, tolerância antes de alertar e respeito à autonomia.

### Tempo sugerido

50 a 60 segundos.

## Slide 3 — Público e impacto social

### Mensagem principal

Apoio à autonomia do idoso em um canal familiar, com acompanhamento responsável e autorizado.

### Conteúdo

- Público principal: pessoas com 60 anos ou mais que já utilizam WhatsApp;
- público secundário: familiares, cuidadores e contatos autorizados;
- benefício: organização da rotina sem exigir um novo aplicativo;
- impacto esperado: mais clareza, tranquilidade e percepção rápida de não confirmação;
- princípio: apoio sem vigilância excessiva.

### Tempo sugerido

45 a 55 segundos.

## Slide 4 — A solução Bem Lembrado

### Mensagem principal

O responsável configura os lembretes; o idoso interage naturalmente pelo WhatsApp.

### Conteúdo visual

Fluxo resumido:

**Painel do responsável → Supabase → n8n → WhatsApp do idoso → resposta → histórico/alerta**

### Funcionalidades centrais

- Cadastro do idoso e de contatos autorizados;
- cadastro e agendamento de lembretes;
- confirmação, adiamento ou não realização;
- histórico no painel;
- alerta em caso de não confirmação;
- conversa simples em linguagem natural.

### Tempo sugerido

60 segundos.

## Slide 5 — Protótipo e demonstração

### Mensagem principal

Demonstrar o ciclo completo do principal valor do produto.

### Roteiro ideal

1. Entrar no painel;
2. selecionar ou cadastrar uma pessoa idosa;
3. criar um lembrete;
4. mostrar o recebimento no WhatsApp;
5. responder ao lembrete;
6. mostrar a atualização do histórico;
7. mostrar o alerta ao responsável, se estiver funcional.

### Plano de segurança

Preparar capturas de tela ou vídeo curto do fluxo para o caso de indisponibilidade de Internet ou de algum serviço externo.

### Tempo sugerido

1 minuto e 40 segundos a 2 minutos.

## Slide 6 — Escopo, requisitos e segurança

### Mensagem principal

O MVP concentra-se no fluxo essencial e mantém regras críticas fora da decisão livre da IA.

### Síntese

- 10 requisitos funcionais e 8 não funcionais;
- autenticação, consentimento e controle de acesso;
- minimização dos dados enviados à IA;
- regras de horário, repetição e alertas controladas pelo sistema;
- diagnóstico, prescrição, alteração de dose e atendimento de emergência fora do escopo;
- painel específico de revisão de memórias fora do MVP final.

### Tempo sugerido

45 a 55 segundos.

## Slide 7 — Gestão, viabilidade e riscos

### Mensagem principal

O projeto foi planejado com responsabilidades, dependências, orçamento e riscos definidos.

### Conteúdo

- Gestão híbrida Scrum/Kanban;
- cinco integrantes com funções complementares;
- cronograma inicial de sete semanas;
- 175 horas estimadas de equipe;
- orçamento com contingência de R$ 16.993,50;
- 144 Pontos de Função e valor comercial acadêmico de R$ 72.000,00;
- riscos prioritários: integrações externas, privacidade, uso inadequado da IA, dificuldade de uso e atraso.

### Tempo sugerido

55 a 65 segundos.

## Slide 8 — Resultados, desafios e aprendizados

### Mensagem principal

Apresentar somente evidências reais obtidas até o fechamento do protótipo.

### Campos a completar

- Funcionalidades implementadas;
- integrações validadas;
- testes executados;
- resultados de validação com usuários ou voluntários;
- dificuldades técnicas e de organização;
- correções de premissas e decisões de redução de escopo;
- principal aprendizado da equipe.

### Possível aprendizado já documentado

O conceito central permaneceu estável, enquanto esforço, orçamento e escopo foram refinados ao longo das entregas.

### Tempo sugerido

60 segundos.

## Slide 9 — Impacto e segunda etapa

### Mensagem principal

O protótipo valida o caminho inicial; a próxima etapa transforma a solução em uma experiência mais estável, segura e testada.

### Conteúdo a completar

- Estado final do MVP;
- impacto social esperado;
- limitações atuais;
- atividades da segunda etapa;
- prazos, responsáveis e dependências do próximo ciclo;
- encerramento com o valor central do projeto.

### Tempo sugerido

45 a 60 segundos.

## Duração total estimada

| Bloco | Tempo aproximado |
|---|---:|
| Capa, problema e público | 2 min |
| Solução e demonstração | 3 min |
| Escopo, gestão e viabilidade | 2 min |
| Resultados e segunda etapa | 2 min |
| **Total previsto** | **9 min** |

## Evidências que deverão ser reunidas

- Logotipo ou identidade visual do Bem Lembrado, se existir;
- telas do protótipo em boa resolução;
- conversa de demonstração no WhatsApp;
- tela de histórico e alerta;
- diagrama simplificado da arquitetura;
- status final das funcionalidades;
- registros dos testes;
- desafios e aprendizados relatados pela equipe;
- cronograma real da segunda etapa;
- plano reserva da demonstração.

## Regra editorial

O relatório será usado como fonte de conteúdo, mas não como modelo de densidade. Cada slide deverá transmitir uma mensagem principal, com pouco texto, evidências visuais e fala complementar.

