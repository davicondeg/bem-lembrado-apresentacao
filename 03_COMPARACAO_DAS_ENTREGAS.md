# Comparação das entregas do Bem Lembrado

## Versões consideradas

A equipe informou que os arquivos foram enviados do mais recente para o mais antigo. Portanto, a cronologia correta, do mais antigo para o mais recente, é:

1. `Bem_Lembrado_Primeira_Entrega_Preto (1).docx`;
2. `Bem_Lembrado_Atualizado_APF_Referencias_Corrigidas.docx`;
3. `Bem_Lembrado_Atualizado.docx`;
4. `Bem_Lembrado_Entrega.docx`.

Essa ordem fornecida pela equipe prevalece sobre os nomes e horários de modificação dos arquivos.

## O que permaneceu consistente

As quatro versões apresentam a mesma base conceitual:

- assistente de apoio à rotina de pessoas idosas pelo WhatsApp;
- painel web destinado ao responsável;
- arquitetura com Next.js, Supabase, n8n, WhatsApp Business Cloud, OpenAI API e Vercel;
- fluxo de lembrete, confirmação, histórico e alerta ao responsável;
- preocupação com consentimento, privacidade, LGPD e limites da IA;
- dez requisitos funcionais e oito requisitos não funcionais;
- planejamento de sete semanas;
- metodologia híbrida Scrum/Kanban;
- nas duas versões mais recentes, contagem estimada de 144 Pontos de Função;
- nas duas versões mais recentes, valor comercial acadêmico estimado em R$ 72.000,00.

A versão intermediária de APF constitui a exceção numérica: ela apresenta 104 PF e R$ 93.600,00. Ainda assim, a proposta central permaneceu estável. A evolução ocorreu principalmente no refinamento de escopo, custos, dados e análise econômica.

## Principais mudanças da versão mais recente

### 1. Revisão do esforço e do orçamento

| Elemento | Versão anterior | Versão mais recente |
|---|---:|---:|
| Horas por integrante | 49 h | 35 h |
| Horas totais da equipe | 245 h | 175 h |
| Mão de obra | R$ 20.335,00 | R$ 14.525,00 |
| Custo-base | R$ 20.495,00 | R$ 15.405,00 |
| Contingência | R$ 1.588,50 | R$ 1.588,50 |
| Orçamento com contingência | R$ 22.083,50 | R$ 16.993,50 |

A versão mais recente corrige explicitamente a interpretação da carga horária: são 35 horas totais por integrante ao longo das sete semanas, e não 35 horas por semana. Para os slides, devem ser usados os números da versão mais recente.

### 2. Redução do escopo de memórias no MVP

Na versão anterior, o RF10 e o cronograma previam visualização e exclusão de memórias autorizadas por uma interface no painel. Na versão mais recente, esse painel específico foi retirado do MVP. Permanecem a gravação controlada, o consentimento e a exclusão mediante solicitação.

Essa alteração é relevante porque demonstra controle de escopo: uma funcionalidade desejável foi adiada para proteger prazo e viabilidade do produto mínimo.

### 3. Modelo de dados acrescentado

A versão mais recente inclui uma seção própria de modelo entidade-relacionamento e validação dos sete grupos lógicos usados na APF:

- responsáveis;
- idosos;
- contatos;
- consentimentos;
- lembretes;
- histórico;
- memórias.

Também explica o vínculo potencialmente muitos-para-muitos entre responsáveis e idosos e separa estruturas de negócio da infraestrutura do Supabase Auth.

### 4. Análise econômica ampliada

A versão mais recente adiciona:

- confronto entre preço de venda e orçamento;
- cenários tributários simulados do Simples Nacional;
- margens estimadas;
- preços mínimos teóricos para margem-alvo;
- análise crítica em nove questões;
- limites e validações pendentes.

Esse conteúdo fortalece a viabilidade econômica, mas deve ser muito resumido na apresentação oral.

### 5. Referências ampliadas

A versão mais recente separa referências complementares e gerais e inclui fontes relacionadas a tributação, benchmarks profissionais, preços das plataformas e documentação técnica.

### 6. Inclusão de recurso visual

A versão anterior não contém mídia incorporada. A versão mais recente contém uma imagem, associada ao modelo entidade-relacionamento. Esse elemento poderá ser reaproveitado visualmente se estiver legível no formato de slide.

## O que a versão anterior ainda esclarece

A versão anterior ajuda a documentar a evolução do escopo e das premissas econômicas. Ela pode servir como evidência de aprendizado e refinamento do planejamento, especialmente em dois pontos:

1. a equipe identificou e corrigiu uma interpretação inadequada da carga horária;
2. a equipe retirou a interface de gestão de memórias do MVP para controlar o escopo.

Essas mudanças podem alimentar o trecho de **desafios e aprendizados**, desde que correspondam à experiência real da equipe.

## Regra para os próximos materiais

- Usar a versão mais recente como fonte principal de números e escopo.
- Consultar a versão anterior apenas para entender evolução e decisões.
- Tratar a versão de 104 PF e R$ 93.600,00 como cálculo intermediário, não como fonte dos números finais.
- Não misturar os custos de R$ 22.083,50 e R$ 16.993,50 no mesmo retrato do projeto.
- Não apresentar o painel de revisão de memórias como parte do MVP atual.
- Preservar os 144 PF e o valor referencial de R$ 72.000,00, pois permaneceram iguais nas duas versões.

