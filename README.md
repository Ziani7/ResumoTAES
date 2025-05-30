# Resumo Tópicos avançados em engenharia de software

* Desafio da engenharia é desenvover software de qualidade
com elevada produtividade, dentro do prazo estabelecido
e sem necessitar de mais recursos do que os alocados

* A principal causa dos problemas de desenvolvimento é a falta de um processo bem definido e efetivo



# Qualidade de software

## Etapas

1. Definição

2. Construção

3. Manutenção



 ## Conceito

 * “A qualidade de software é um conjunto de         características ou fatores de software, que determinam o nível de eficiência do software em uso, em relação ao atendimento das expectativas dos clientes”. (IEEE).

 * “Conformidade a requisitos funcionais e de desempenho explicitamente declarados, a padrões de desenvolvimento claramente documentados e a características implícitas que são esperadas de todo software profissionalmente desenvolvido” (Pressman, 2011).

 * Para Robert Glass: Satisfação do usuário = produto compatível + boa qualidade + entrega dentro do orçamento e do prazo previsto


 ## Panorama de qualidade

 * O que é? Para software de computador, qualidade é
    algo que tem de ser definido.

* Quem realiza? Todos os envolvidos

* Por que é importante? Resulta em custos menores, e entrega mais rápida.

* Quais são as etapas envolvidas? Processo e prática comprovados de engenharia de software, gerenciamento consistente de projetos, controle global de qualidade e a presença de uma infraestrutura para garantir a qualidade.

* Qual o artefato? Software que atenda às necessidades do cliente, execute de forma precisa e confiável e gere valor para todos aqueles que o utilizam.


## Dimensões de qualidade de Garvin

1. Qualidade do desempenho

2. Qualidade dos recursos

3. Confiabilidade

4. Conformidade

5. Durabilidade

6. Facilidade de manutenção

7. Estética

8. Percepção


## Fatores de qualidade de Mccall

1. Correção

2. Confiabilidade

3. Eficiência

4. Integridade

5. Usabilidade

6. Facilidade de manutenção

7. Flexibilidade

8. Testabilidade

9. Portabilidade

10. Reusabilidade

11. Interopenabilidade


## Fatores de qualidade ISO 9126

1. Funcionalidade

2. Confiabilidade

3. Usabilidade

4. Eficiência

5. Facilidade de manutenção

6. Portabilidade


## Fatores de qualidade desejados

* Intuição

* Eficiência

* Robustez

* Riqueza


## Custo da qualidade

### Custo de prevenção

* O custo de atividades de gerenciamento necessárias para planejar e coordenar todas as atividades de controle e garantia da qualidade

* O custo de atividades técnicas adicionais para desenvolver modelos completos de requisitos e de projeto

* Custos de planejamento de testes

* O custo de todo o treinamento associado a essas atividades

### Custo de avaliação

* Custo para realização de revisões técnicas para produtos
resultantes de engenharia de software

* Custo para coleta de dados e avaliação de métricas

* Custo para testes e depuração

### Custo de falhas 

* Custo necessário para realizar retrabalhos (reparos) para corrigir um erro.

* Custo que ocorre quando retrabalhos geram, inadvertidamente,
efeitos colaterais que devem ser reduzidos;

* Custos associados à reunião de métricas de qualidade que permitem a uma organização avaliar os modos de falha;

# Garantia de qualidade de software (SQA)

A Garantia da Qualidade de Software (SQA) abrange um espectro amplo de atividades planejadas e sistemáticas que são incorporadas dentro do processo de desenvolvimento de software para assegurar que os padrões de qualidade sejam cumpridos. Essas atividades incluem a definição de processos, auditorias e métricas que acompanhem e avaliem continuamente a eficácia dos processos estabelecidos.

**Como podemos garantir a qualidade de software ou (SQA) Software Quality Assurance?**

Para garantir a qualidade de software (SQA), é essencial implementar um conjunto de práticas planejadas e sistemáticas durante todo o ciclo de vida do desenvolvimento. Isso começa com a definição de processos padronizados que orientem as equipes em cada etapa, desde a coleta de requisitos até a manutenção

## Boas práticas do SQA

1. Definição de processos claros: padronizar as etapas do desenvolvimento para garantir consistência e qualidade.

2. Revisões técnicas: realizar inspeções e revisões de código, requisitos e design para identificar falhas precocemente.

3. Testes sistemáticos: aplicar testes unitários, de integração, sistema e aceitação para validar o funcionamento do software.

4. Uso de métricas: acompanhar indicadores como densidade de defeitos, cobertura de testes e produtividade para melhorar continuamente.

5. Auditorias internas: verificar se os processos estão sendo seguidos conforme o planejado.

6. Automatização de testes: reduzir erros humanos e acelerar a validação de funcionalidades.

7. Treinamento da equipe: manter os profissionais atualizados sobre padrões de qualidade e ferramentas.

8. Gestão de mudanças: controlar e documentar alterações nos requisitos e no código.

## Elementos da SQA

1. Padrões de Qualidade: diretrizes e normas (como ISO/IEC 25010, CMMI) que definem critérios de qualidade a serem seguidos.

2. Procedimentos e Metodologias: processos padronizados para desenvolvimento, testes e manutenção do software.

3. uditorias e Revisões: avaliações sistemáticas dos processos e produtos para garantir conformidade com os padrões definidos.

4. Testes de Software: verificação e validação do produto em várias fases (unitário, integração, sistema, aceitação).

5. Métricas de Qualidade: indicadores que permitem medir a eficácia dos processos e a qualidade do software (ex.: taxa de defeitos, tempo de resposta).

6. Gerência de Configuração: controle de versões, mudanças e integridade dos artefatos do projeto.

7. Ferramentas de Apoio: softwares para automação de testes, análise de código, controle de versão e rastreamento de defeitos.

8. Capacitação da Equipe: treinamentos contínuos para garantir que todos os envolvidos estejam alinhados com as práticas de qualidade.

## Quality Control SQA

Quality Control (QC), ou controle de qualidade, é o processo focado na verificação do produto de software para garantir que ele atenda aos requisitos especificados e esteja livre de defeitos. Diferente da Garantia da Qualidade (SQA), que é preventiva e atua nos processos, o QC é corretivo e atua diretamente no produto final.

# Confiabilidade

* É a probabilidade de operação livre de falhas de um
programa de computador num ambiente específico durante
determinado tempo

* Pode ser medida e estimada usando dados históricos do
desenvolvimento ou do uso do software

## Métricas

* Métricas do n° de falhas do sistema
    * Tempo médio de ocorrência de falhas
    * Tempo médio até a ocorrência de falhas
    * Tempo médio de reparo

* Métricas de tempo ou n° de transações
    * ROCOF: Taxa de ocorrência de falha
    * POFOD: Probabilidade de falha sob demanda

* Tempo gasto para reparar ou reiniciar sistema
    * Diponibilidade

## Dimensões

* Disponibilidade: A capacidade do sistema de 
    disponibilizar serviços quando necessário

* Confiabilidade: Disponibilizar serviços conforme 
    especificado

* Segurança: Operar sem falhas catastróficas

* Proteção: Se proteger contra invasão acidental ou deliberada
    
# Falhas

| Classe de Falha   | Descrição                                                                 |
|-------------------|---------------------------------------------------------------------------|
| Transiente        | Ocorre somente com algumas entradas.                                      |
| Permanente        | Ocorre com todas as entradas.                                             |
| Recuperável       | O sistema pode se recuperar sem a intervenção do operador.                |
| Irrecuperável     | É necessário a intervenção do operador para a recuperação a partir da falha. |
| Não corruptível   | A falha não corrompe o estado do sistema ou seus dados.                   |
| Corruptível       | A falha corrompe o estado do sistema ou seus dados.                       |


1. Qual o desafio da engenharia de software no que diz respeito ao tema qualidade?
**Desenvolver software de qualidade com alta produtividade, dentro do prazo e sem ultrapassar os recursos alocados.**

2. Quais as causas dos problemas que ocorrem durante o processo de desenvolvimento de software?
**A principal causa é a ausência de um processo bem definido e efetivo.**

3. Conceitue qualidade de software.
**É o conjunto de características que determina o nível de eficiência do software em atender às expectativas dos clientes, conforme requisitos funcionais e de desempenho.**

4. O que é a gestão de qualidade de software?
**É o conjunto de práticas e processos que asseguram que o software será desenvolvido com qualidade, conforme requisitos, prazos e custos estabelecidos.**

5. Como podemos garantir a qualidade de software ou (SQA) Software Quality Assurance?
**Implementando práticas sistemáticas como definição de processos, auditorias, uso de métricas, revisões técnicas, testes e capacitação da equipe.**

6. Por que as métricas são importantes no processo de qualidade de software?
**Elas permitem avaliar a eficácia dos processos, identificar falhas e tomar decisões baseadas em dados para melhoria contínua.**

7. Quais os pontos de vista denominados por David Garvin para classificar qualidade? Dê exemplos.
**Desempenho (velocidade de um app), Confiabilidade (funcionamento sem falhas), Estética (interface atrativa), Durabilidade (tempo de vida útil).**

8. Quais as dimensões da qualidade utilizadas por David Garvin?
**Desempenho, Recursos, Confiabilidade, Conformidade, Durabilidade, Manutenção, Estética e Percepção.**

9. Quais os fatores de qualidade segundo Richard Mccall?
Correção, Confiabilidade, Eficiência, Integridade, **Usabilidade, Manutenibilidade, Flexibilidade, Testabilidade, Portabilidade, Reusabilidade, Interoperabilidade.**

10. Quais os fatores de qualidade segundo a norma ISO 9126?
**Funcionalidade, Confiabilidade, Usabilidade, Eficiência, Manutenibilidade, Portabilidade.**

11. Baseado nas questões 7 a 10, quais os principais fatores de qualidade desejados para o software?
**Intuição, Eficiência, Robustez e Riqueza, além de usabilidade, confiabilidade e manutenibilidade.**

12. Comente sobre a variável custo, no processo de desenvolvimento e na qualidade do software.
**O custo se divide em prevenção, avaliação e falhas. Investir em prevenção e avaliação reduz os custos com falhas no futuro.**

13. Que práticas devem ser adotadas para alavancar a qualidade de software?
**Processos padronizados, revisões técnicas, testes automatizados, métricas, auditorias internas, gestão de mudanças e capacitação.**

14. Como você avaliaria a qualidade de uma universidade antes de se candidatar a ela?
**Consideraria fatores como reconhecimento, qualidade do ensino, infraestrutura, suporte ao aluno, empregabilidade. Críticos seriam qualidade dos professores e acessibilidade.**

15. Quais são os elementos da SQA - software quality assurance?
**Padrões de qualidade, metodologias, auditorias, testes, métricas, gerência de configuração, ferramentas de apoio e capacitação.**

16. Descreva sobre Quality Assurance – garantia de qualidade no processo.
**É a abordagem preventiva que define processos, métodos e práticas para garantir que o software atenda aos padrões de qualidade.**

17. Descreva sobre Quality Control – controle de qualidade no produto.
**É uma abordagem corretiva que envolve testes e revisões para identificar e corrigir defeitos no produto final.**

18. Qual o conceito de confiabilidade de software?
**É a probabilidade de o software operar sem falhas, em ambiente específico, durante um tempo determinado.**

19. Que métricas podem ser utilizadas para medir a confiabilidade de um software?
**Número de falhas, tempo médio até a falha, tempo médio de reparo, ROCOF (taxa de falhas), POFOD (probabilidade de falha sob demanda), disponibilidade.**

20. Sobre as dimensões da confiança do software, descreva e dê exemplos:

**Disponibilidade: estar funcional quando necessário (ex.: app de banco 24h).**

**Confiabilidade: funcionar conforme especificado (ex.: sistema de reserva de passagens).**

**Segurança: operar sem falhas catastróficas (ex.: software médico).**

**Proteção: resistir a invasões ou acessos indevidos (ex.: criptografia em sistemas bancários).**

21. Que classificação das falhas podemos encontrar?
**Transiente, Permanente, Recuperável, Irrecuperável, Não Corruptível, Corruptível.**