# Análise da entrega — Bem Lembrado

## Identificação do documento

- Arquivo analisado: `Bem_Lembrado_Entrega.docx`;
- título: **Bem Lembrado — Análise de Pontos de Função, Modelo de Dados e Viabilidade Econômica**;
- equipe: Arthur Prates Pessoti, Davi Conde Garcia, Gabriel Oliveira de Souza Aguiar, Miguel Saiter Padovan e Rafael Lordes Lovat;
- proposta: assistente virtual integrado ao WhatsApp para apoiar a rotina de pessoas idosas e permitir acompanhamento por contatos autorizados.

## Resumo executivo do projeto

O **Bem Lembrado** é um SaaS voltado a pessoas idosas que já usam WhatsApp. O sistema envia lembretes de medicamentos previamente prescritos, consultas e tarefas, recebe confirmações e pode alertar um familiar ou responsável autorizado quando não houver resposta dentro de um período configurado.

O responsável utiliza um painel web para cadastrar idosos, contatos, consentimentos e lembretes. A arquitetura planejada conecta Next.js, Supabase, n8n, WhatsApp Business Cloud, OpenAI API e Vercel. Regras críticas, como horários, repetições e alertas, ficam em fluxos determinísticos; a IA é reservada à compreensão e geração de linguagem natural.

O diferencial social é aproveitar um canal já conhecido pelo público, reduzindo a necessidade de aprender um novo aplicativo. A proposta procura equilibrar autonomia, apoio familiar, privacidade e simplicidade.

## Cobertura dos critérios da professora

| Critério | Cobertura no documento | Evidência principal |
|---|---|---|
| 1. Identificação | Completa | Nome, objetivo, equipe e funções |
| 2. Contexto e problema | Completa | Envelhecimento populacional, esquecimentos e limitações das alternativas atuais |
| 3. Público e impacto | Completa | Idosos usuários de WhatsApp, responsáveis e entrevistas de campo |
| 4. Solução inicial | Completa | SaaS com painel web, lembretes, respostas e alertas via WhatsApp |
| 5. Viabilidade | Completa | Análises técnica, econômica, operacional e de prazo |
| 6. Escopo | Completa | Objetivo, produto, funcionalidades, critérios de sucesso e itens fora do escopo |
| 7. Stakeholders | Completa | Interesse, influência e comunicação |
| 8. Recursos | Completa | Recursos humanos, tecnológicos, financeiros e informacionais |
| 9. Requisitos | Completa | RF01–RF10 e RNF01–RNF08, com responsáveis e prazos |
| 10. Riscos | Completa | Probabilidade, impacto e resposta para nove riscos |
| 11. Cronograma | Completa | Sete semanas, atividades, responsáveis, resultados e dependências |
| 12. Metodologia | Completa | Abordagem híbrida Scrum/Kanban e acompanhamento pelo GitHub Projects |
| 13. Apresentação final | Parcial | O documento fornece a base, mas protótipo, demonstração, resultados realizados, aprendizados e cronograma da segunda etapa dependem de evidências atualizadas |

## Informações fortes para a narrativa dos slides

### Problema

- Lembretes ficam espalhados entre alarmes, anotações e mensagens familiares.
- O familiar muitas vezes não sabe se o lembrete foi visto ou confirmado.
- Uma nova aplicação pode criar barreira de adoção para a pessoa idosa.

### Evidência do público

- Foram registradas conversas com dois idosos, uma responsável e uma pessoa próxima à rotina de uma idosa.
- Os relatos indicam preferência por mensagens curtas, respostas simples, suporte a áudio, frequência controlada e alerta somente após tolerância configurável.
- As entrevistas também revelam preocupações com vigilância excessiva, falsos alertas, privacidade e excesso de notificações.

### Solução e fluxo demonstrável

1. O responsável cadastra a pessoa idosa, o contato autorizado e o lembrete no painel.
2. O painel grava os dados no Supabase.
3. O n8n identifica o horário e envia a mensagem pelo WhatsApp Business Cloud.
4. A pessoa idosa confirma, adia ou informa a não realização.
5. O sistema atualiza o histórico no Supabase e no painel.
6. Se não houver confirmação no prazo definido, o responsável recebe um alerta.
7. Em conversas livres, a IA pode responder usando apenas contexto autorizado.

### Escopo e segurança

- O projeto não diagnostica, prescreve nem altera medicamentos.
- Não substitui acompanhamento médico ou serviço de emergência.
- Não compartilha automaticamente toda a conversa com familiares.
- Consentimento, minimização de dados, autenticação e controle de acesso fazem parte do escopo.

### Viabilidade e números relevantes

- Piloto planejado: aproximadamente 10 a 20 idosos e seus responsáveis.
- Desenvolvimento planejado: sete semanas.
- Esforço estimado: 175 horas de equipe, sendo 35 horas por integrante.
- Custo total orçado com contingência: **R$ 16.993,50**.
- Contagem estimada: **144 Pontos de Função**.
- Valor comercial de referência: **R$ 72.000,00**.

Os números econômicos são úteis como prova de planejamento, mas devem ocupar pouco tempo na apresentação, salvo se a professora der destaque específico à APF e à viabilidade financeira.

## Pontos que exigem confirmação antes de montar os slides finais

- Quais partes do protótipo estão realmente implementadas e quais permanecem planejadas.
- Quais integrações funcionam hoje: painel, Supabase, n8n, WhatsApp e IA.
- Quais resultados de testes ou validações já existem e podem ser mostrados como evidência.
- Quais dificuldades ocorreram de fato e quais aprendizados a equipe teve.
- Qual será o cronograma real da segunda etapa; o documento contém o cronograma inicial de sete semanas, mas a professora pede especificamente o próximo ciclo.
- Se as telas do Figma e o diagrama do modelo de dados estão disponíveis em melhor resolução.
- Se há capturas de tela, vídeo ou ambiente funcional para uma demonstração ao vivo e um plano reserva.

## Pontos de atenção e consistência

- O documento mistura planejamento futuro com descrição de entrega. Nos slides, é essencial usar rótulos como **planejado**, **implementado**, **testado** e **pendente**.
- A apresentação possui somente 7 a 10 minutos; não será possível detalhar todos os requisitos, riscos, custos e semanas. Esses conteúdos devem virar sínteses visuais.
- A denominação e a disponibilidade dos serviços, modelos e preços citados devem ser conferidas antes da versão final, pois podem mudar.
- A estimativa de 175 horas para um MVP com múltiplas integrações é reconhecida no próprio documento como enxuta e deve ser apresentada como premissa, não como certeza.
- O valor por Ponto de Função e os cenários tributários são estimativas acadêmicas; não devem parecer uma proposta comercial definitiva.
- O alerta de não confirmação representa apoio, não confirmação de uma emergência ou de um problema médico.

## Direção preliminar para a apresentação

Esta entrega sustenta uma narrativa curta e convincente:

**problema real → evidência com usuários → solução familiar pelo WhatsApp → fluxo do protótipo → planejamento e segurança → resultados reais → impacto → próximos passos.**

Uma estrutura provável terá entre 8 e 10 slides. A definição final deverá aguardar os demais arquivos, principalmente as evidências do protótipo e do estágio atual do desenvolvimento.

