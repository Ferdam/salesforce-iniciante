# 1. Guide para Iniciar em Salesforce (Atualizado 2025)
- [1. Guide para Iniciar em Salesforce (Atualizado 2025)](#1-guide-para-iniciar-em-salesforce--atualizado-2025-)
  * [1.1. O que é Salesforce?](#11-o-que---salesforce-)
  * [1.2. Carreiras](#12-carreiras)
  * [1.3. Aprender Salesforce - Trailhead](#13-aprender-salesforce---trailhead)
    + [1.3.1. Trailhead](#131-trailhead)
      - [1.3.1.1 Passo-a-passo](#1311-passo-a-passo)
      - [1.3.1.2. Trailmixes](#1312-trailmixes)
        * [1.3.1.2.1. Deloitte](#13121-deloitte)
        * [1.3.1.2.2. GFT](#13122-gft)
        * [1.3.1.2.3. Everis](#13123-everis)
        * [1.3.1.2.4. Wipro](#13124-wipro)
      - [1.3.1.3. Documentação Salesforce](#1313-documenta--o-salesforce)
    + [1.3.2. Prática](#132-pr-tica)
  * [1.4. Impacto do Trailhead e mais informações](#14-impacto-do-trailhead-e-mais-informa--es)
  * [1.5. Certificações](#15-certifica--es)
    + [1.5.1. IMPORTANTE: Mudança para Trailhead Academy](#151-importante--mudan-a-para-trailhead-academy)
    + [1.5.2. Como obter certificações?](#152-como-obter-certifica--es-)
    + [1.5.3. Tá, mas quais devo focar?](#153-t---mas-quais-devo-focar-)
  * [1.6. O que está em alta hoje](#16-o-que-est--em-alta-hoje)
    + [1.6.1. Einstein GPT e AI Cloud](#161-einstein-gpt-e-ai-cloud)
    + [1.6.2. Agentforce](#162-agentforce)
    + [1.6.3. Data Cloud](#163-data-cloud)
  * [🎯 Dicas Finais Para 2025](#---dicas-finais-para-2025)

## 1.1. O que é Salesforce?
Salesforce é, principalmente, uma ferramenta de CRM (Customer Relationship Management), mas hoje é capaz de fazer muito mais do que apenas isso.
É um ecossistema em nuvem, altamente customizável e facilmente integrável com outros sistemas: um ambiente de Salesforce pode enviar dados a outros sistemas e outros sistemas podem enviar dados ao Salesforce.

A plataforma é dividida em clouds, que são conjuntos de soluções para resolver problemas e facilitar assuntos que comumente se encontram na maioria das empresas.
Algumas clouds são oficiais, outras são third-party, feitas com as ferramentas de desenvolvimento Salesforce (são como plugins)

As Clouds principais (oficiais):
- <u>Sales Cloud</u>: a mais comum, gerencia dados de vendas, clientes e até mapeamento de contatos
- <u>Service Cloud</u>: também bem comum; util para gerenciar casos, tickets e registrar informações de suporte e até call center
- <u>Community Cloud</u>: a parte externa do Salesforce, para clientes acessarem - criação/edição de registros, pedidos, cases etc
- <u>Marketing Cloud</u>: conjunto de soluções para marketing (campanhas, e-mails etc)
- <u>Data Cloud</u>: a cloud que unifica e harmoniza dados de todas as fontes da empresa em tempo real
- <u>AI Cloud</u>: conjunto de ferramentas de IA generativa e agentes autônomos

## 1.2. Carreiras
Trabalhar com Salesforce envolve diversas carreiras:
- <u>Administrator</u>:
Configuração do ambiente, criação de objetos (tabelas), campos, automações, visibilidade de registros e permissões etc
- <u>Developer</u>:
Criação de automações com as ferramentas padrões (Flow); Customização com código: 
  - Apex - linguagem backend baseada em Java e C#. Faz uso de Orientação a Objetos (OOP); serve para backend no geral: controllers, triggers e integrações; 
  - SOQL - linguagem de consulta de banco de dados; 
  - Aura/Lightning Web Components (LWC) - frameworks para desenvolvimento de elementos visuais (frontend) utilizando tecnologias web como HTML/CSS e JavaScript
- <u>AI/Agent Developer</u>: 
Especialista em configurar e desenvolver agentes de IA usando Agentforce, criando automações inteligentes e integrações com IA generativa
- <u>Data Cloud Specialist</u>: 
Profissional focado em unificar dados de múltiplas fontes, criar modelos de dados e implementar soluções de data lakes/warehouses
- <u>Consultant / Business Analyst</u>:
Pessoas que vão analisar as dores dos clientes e usuários e traduzir em soluções que a plataforma resolva
- <u>Architect</u>:
Profissionais encarregados de montar a arquitetura de soluções e de sistemas pensando no ecossistema Salesforce
- <u>Designer</u>:
Salesforce possui um robusto Design System (Salesforce Lightning Design System - SLDS)
- <u>Vendas (Sales Career)</u>:
Profissionais que vão de fato fazer uso da plataforma para gerenciar dados de vendas, registrar produtos e mapear clientes

## 1.3. Aprender Salesforce - Trailhead

### 1.3.1. Trailhead
Aprender Salesforce é 100% de graça: a plataforma oficial de treinamento se chama Trailhead e lá você encontra treinamentos para todos os assuntos da plataforma, inclusive sobre as diversas clouds.
Ou seja, Trailhead é onde você poderá aprender a como usar, configurar e desenvolver a plataforma Salesforce.

O Trailhead possui lições que são apenas leitura, outras que para a conclusão é preciso acertar o Quiz e, um ultimo tipo, que são os que requerem que você realizar ações em um ambiente pessoal de desenvolvimento (Dev Org / Playgrounds) - haverá uma validação do ambiente para saber se você concluiu a tarefa corretamente
Esses ambientes são 100% gratuitos e você pode criar quantos quiser. Um ambiente Dev ou Playground possuem praticamente todas as capacidades de uma org paga usada em produção por um cliente.

#### 1.3.1.1 Passo-a-passo

1. Fazer uma conta no Trailhead: https://trailhead.salesforce.com/en
2. Escolher um career path: 
   * Quer ser desenvolvedor de customizações para a plataforma? 
   * Ou prefere administrar a plataforma? 
   * Ou então ser um consultor / analista de negócios?
   * Quer trabalhar com IA e agentes autônomos?
   * Quer ser especialista em dados e integração?
> **Note**:
> Certamente, o que mais chove vagas nesse mundo é para Desenvolvedor, seguido de Admin e Consultores. No entanto, é notável que as novas áreas de AI/Agents e Data Cloud estão crescendo bem rápido.

3. Seguir uma trilha de aprendizado no trailhead baseada na carreira escolhida
   * Pessoalmente, acho a forma mais facil, pois evita que comece assuntos avançados antes da hora
> **Note**:
> Trilhas são conjuntos de módulos que formam um objetivo (aprender algo especifico sobre Apex; aprender a criar objetos e campos; configurar layouts, etc)

Referência: Salesforce Careers

A trilha oficial da Salesforce para iniciar com Desenvolvimento Salesforce, por exemplo: 
https://trailhead.salesforce.com/users/strailhead/trailmixes/build-your-developer-career-on-salesforce

#### 1.3.1.2. Trailmixes
Além disso existem as Trailmixes que são conjuntos de trilhas feitas pela comunidade.
Algumas empresas têm suas próprias Trailmixes, com lições que julgam mais importantes para o dia-a-dia do profissional em aprendizado.

Exemplos: 

##### 1.3.1.2.1. Deloitte
- Dev: https://trailhead.salesforce.com/en/users/jayres/trailmixes/deloitte-dev-dc
- Admin: https://trailhead.salesforce.com/en/users/jayres/trailmixes/deloitte-funcional-dc
- Geral: https://trailhead.salesforce.com/en/users/diogoboffabraga/trailmixes/deloitte

##### 1.3.1.2.2. GFT
- Geral: https://trailhead.salesforce.com/en/users/asanches3/trailmixes/road-to-gft-forcers

##### 1.3.1.2.3. Everis 
- Marketing Cloud: https://trailhead.salesforce.com/en/users/wanderjesus/trailmixes/marketing-cloud-everis-brasil

##### 1.3.1.2.4. Wipro
- Lightning Web Components (LWC): https://trailhead.salesforce.com/en/users/egarcia22/trailmixes/lwc-path

#### 1.3.1.3. Documentação Salesforce
Outra forma de aprender sobre o Salesforce é pelo site de documentação, que é bem completo e atualizado:
- Landing page: https://developer.salesforce.com/docs#browse
- Apex Guide: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_dev_guide.htm
- Apex Docs: https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_ref_guide.htm

### 1.3.2. Prática
Após algum tempo de trailhead, você vai precisar unificar os diversos modulos que aprendeu pelo Trailhead e por conta própria, para isso, considere criar um projeto implementando um use-case do zero da melhor forma que souber e conseguir. Obtenha os metadados de tudo que criar e coloque num repositorio github. Assim poderá ter como algo prático ao seu dispor e como portfolio para as vagas e recruiters q interagir.

Para mais detalhes da parte prática acesse: (**guide da prática em construção**)

## 1.4. Impacto do Trailhead e mais informações
Por fim, o trailhead serve, além de tudo, como portfólio no mundo de Salesforce. Na sua página Trailblazer (perfil do trailhead) é possível ver as conquistas da pessoa pela quantidade de pontos e badges. Além disso, um ponto importante para trabalhar com Salesforce é obter certificações. Assim como a Microsoft, Oracle, SAP e AWS, um profissional pode se certificar em Salesforce em diversos assuntos.
As certificações em Salesforce ajudam muito a alavancar a carreira e conseguir empregos nas melhores empresas (apesar de ser possível ir longe sem certificações, ter algumas facilita a sua vida).

> **Note**: 
> No perfil trailblazer também serão exibidas as certificações conquistadas

Exemplo de perfil Salesforce:
https://trailblazer.me/id/ferdam

## 1.5. Certificações
Um ponto importante na carreira Salesforce é conquistar as certificações oficiais da Salesforce.
Não é a única forma de crescer nessa carreira, mas facilita muito. Seguir sem certificações pode dar certo, não é nenhuma regra, nada obrigatório. Porém, quando se possui mais experiência, verá que os demais profissionais do mesmo nível possuem 3 ou mais certificações.

### 1.5.1. IMPORTANTE: Mudança para Trailhead Academy

Em julho de 2025, todas as certificações da Salesforce migraram do **Webassessor** para a **Trailhead Academy**.

**O que mudou:**
- ❌ **Webassessor/Kryterion**: não é mais usado
- ✅ **Trailhead Academy**: novo portal oficial (parceria com Pearson VUE)
- **Uma única conta**: Trailblazer profile para tudo
- **Experiência unificada**: Salesforce, Tableau, MuleSoft e Slack em um só lugar

**Benefícios da nova plataforma:**
- Homepage personalizada com recomendações de certificações
- Registro pelo celular (mas provas ainda precisam ser no computador)
- Catálogo completo filtrado por função e produto
- Integração com o ecossistema Trailhead

**Como acessar:**
1. Faça login no [Trailhead Academy](https://trailheadacademy.salesforce.com/) com seu perfil Trailblazer
2. Ou acesse via Trailhead > Certifications
3. Se não tiver perfil Trailblazer, crie um primeiro

> **Note**: 
> ⚠️ **Use sempre seu email PESSOAL** para criar a conta, nunca email corporativo! As certificações são suas, não da empresa.

### 1.5.2. Como obter certificações?

**Preços (2025):**
- Certificações básicas: $200 USD
- Certificações de arquitetura: $400 USD  
- **Salesforce Associate**: $75 USD (certificação de entrada)

**Como conseguir desconto:**
- Pela Salesforce:
  - Eventos (físicos e virtuais) com vouchers de $50-150 USD
  - Webinars preparatórios com vouchers de até 100% para primeira certificação
  - Vouchers regionais (mais raros atualmente)
- Pela empresa:
  - Empresas parceiras podem ter vouchers de 100% de desconto
  - Reembolso mediante aprovação (pergunte antes de marcar a prova)
- **Programa Beta**: certificações beta gratuitas para testar novas questões

**Processo atual (Trailhead Academy + Pearson VUE):**
1. Acesse Trailhead Academy
2. Escolha a certificação desejada
3. Registre-se via Pearson VUE
4. Teste seu computador e internet
5. Agende data e horário
6. Pague e confirme
7. Faça a prova online com proctoring

### 1.5.3. Tá, mas quais devo focar?

**Iniciantes (Entrada no mercado):**
- **Salesforce Certified Platform Foundations** ($75 USD) - **RECOMENDAÇÃO PRINCIPAL**
  - Certificação mais básica de todas
  - Perfeita para quem tem menos de 1 ano de experiência
  - Ótima para dar o primeiro "boost" no currículo
- **Certified AI Associate** (em desenvolvimento) - **FOQUE NESTA TAMBÉM**
  - Nova certificação focada em IA e Agentforce
  - Será essencial para o mercado de trabalho futuro

**Administradores ($200 USD):**
- Salesforce Certified Administrator
- Salesforce Certified Business Analyst

**Desenvolvedores ($200 USD):**
- Salesforce Certified Platform Developer I
- Salesforce Certified Platform App Builder
- Salesforce Certified JavaScript Developer I
  - Requer Super Badge além da prova

**Novas Certificações:**
- **Data Cloud Specialist**
- **Certificações relacionadas a IA/Agentforce**

> **Note**:
> 💡 **Dica de carreira 2025**: Foque primeiro na `Platform Foundations`, depois na `AI Associate`. Em seguida:
> Se estiver optando por um lado mais admin ou consultor, `AI Specialist` e `Data Cloud` são boas opções para se considerar.
> Caso seja um lado mais tecnico/desenvolvedor, foque na `Platform Developer I`.

**Simulados/Exames para praticar (gratuitos):**
- Certified Developer I:
  - https://www.salesforceben.com/salesforce-platform-developer-1-practice-exams/
- Certified Administrator:
  - https://www.salesforceben.com/salesforce-admin-practice-exam/
  - https://focusonforce.com/salesforce-adm-201-exam-questions/
- Certified Platform App Builder:
  - https://www.salesforceben.com/free-salesforce-platform-app-builder-practice-exam-with-answers/

## 1.6. O que está em alta hoje

### 1.6.1. Einstein GPT e AI Cloud
Em março de 2023, a Salesforce lançou o Einstein GPT, a primeira IA generativa para CRM. Principais recursos:
- IA generativa integrada nativamente ao Salesforce
- **Sales GPT**: emails personalizados, resumos de oportunidades
- **Service GPT**: respostas automáticas, artigos de conhecimento
- **Marketing GPT**: conteúdo para campanhas
- **Developer GPT**: geração de código Apex
- **Einstein Trust Layer**: camada de segurança para dados empresariais

### 1.6.2. Agentforce
Lançado em outubro de 2024, o Agentforce vai além de chatbots, são agentes autônomos que executam tarefas complexas:
- **Service Agent**: resolve cases automaticamente 24/7
- **Sales Development Agent**: qualifica leads e agenda reuniões
- **Marketing Agent**: cria campanhas personalizadas
- **Employee Service Agent**: suporte interno para funcionários
Muitas empresas estão implementando Agentforce para diversos cenários e casos-de-uso diferentes. Há uma demanda grande para implementação deles tanto nos pequenos quanto nos grandes clientes.

### 1.6.3. Data Cloud
O Data Cloud se tornou o produto de crescimento mais rápido da Salesforce:
- Unifica dados de 40+ sistemas em tempo real
- **Zero-Copy Integration**: conecta dados sem copia-los fisicamente
- **AI tagging**: classifica automaticamente dados não-estruturados
- Alimenta toda a IA da Salesforce

---

## 🎯 Dicas Finais Para 2025

1. **Obter a Certificação Platform Foundations primeiro**: É barata, dá confiança e abre portas
2. **Se familiarize com IA**: Mesmo que queira ser Admin ou Dev, considere priorizar Agentforce e Einstein GPT em algum momento
3. **Data Cloud**: Toda IA precisa de dados, logo, buscar entender como a Salesforce unifica informações é bastante vantajoso
4. **Trailhead Academy**: Faça bom uso da nova plataforma de certificações
5. **Fique atento às novidades**: O mercado está mudando rápido com IA e a Salesforce está surfando a onda

---

**Obrigado e bons estudos! 😎**
