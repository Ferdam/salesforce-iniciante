# Guide para Iniciar em Salesforce
Salesforce é, principalmente, uma ferramenta de CRM (Customer Relationship Management), mas hoje é capaz de fazer muito mais do que apenas isso.
É um ecossistema em nuvem, altamente customizável e facilmente integrável com outros sistemas: um ambiente de Salesforce pode enviar dados a outros sistemas e outros sistemas podem enviar dados ao Salesforce.
A plataforma é dividida em clouds, que são conjuntos de soluções para resolver problemas e facilitar assuntos que comumente se encontram na maioria das empresas.
Algumas clouds são oficiais, outras são third-party, feitas com as ferramentas de desenvolvimento Salesforce (são como plugins)

As Clouds principais (oficiais):
- Sales Cloud: a mais comum, gerencia dados de vendas, clientes e até mapeamento de contatos
- Service Cloud: também bem comum; util para gerenciar casos, tickets e registrar informações de suporte e até call center
- Community Cloud: a parte externa do Salesforce, para clientes acessarem - criação/edição de registros, pedidos, cases etc
- Marketing Cloud: conjunto de soluções para marketing (campanhas, e-mails etc)

## Carreiras
Trabalhar com Salesforce envolve diversas carreiras:
- Administrator:
Configuração do ambiente, criação de objetos (tabelas), campos, automações, visibilidade de registros e permissões etc
- Developer:
Criação de automações com as ferramentas padrões (Flow); Customização com código: 
  - Apex - linguagem backend baseada em Java e C#. Faz uso de Orientação a Objetos (OOP); serve para backend no geral: controllers, triggers e integrações; 
  - SOQL - linguagem de consulta de banco de dados; 
  - Aura/Lightning Web Components (LWC) - frameworks para desenvolvimento de elementos visuais (frontend) utilizando tecnologias web como HTML/CSS e JavaScript
- Consultant / Business Analyst:
Pessoas que vão analisar as dores dos clientes e usuários e traduzir em soluções que a plataforma resolva
- Architect: 
Profissionais encarregados de montar a arquitetura de soluções e de sistemas pensando no ecossistema Salesforce
- Designer: 
Salesforce possui um robusto Design System (Salesforce Lightning Design System - SLDS)
- Vendas (Sales Career): 
Profissionais que vão de fato fazer uso da plataforma para gerenciar dados de vendas, registrar produtos e mapear clientes


## Aprender Salesforce - Trailhead
Como aprender a usar, configurar e desenvolver a plataforma Salesforce:

Aprender Salesforce é 100% de graça. 
A plataforma oficial de treinamento se chama Trailhead e lá você encontra treinamentos para todos os assuntos da plataforma, inclusive sobre as diversas clouds.

Primeiro passo é fazer uma conta no Trailhead: https://trailhead.salesforce.com/en

Segundo passo é escolher um career path: quer ser desenvolvedor de customizações? Ou administrar a plataforma? Ou então ser um consultor / analista de negócios?
> Nota: Certamente, o que mais chove vagas nesse mundo é para Desenvolvedor, seguido de Admin e Consultores

Em seguida é seguir uma trilha de aprendizado no trailhead. 
> Nota: Trilhas são conjuntos de módulos que formam um objetivo.

Referência: Salesforce Careers

A trilha oficial da Salesforce para iniciar com Desenvolvimento Salesforce, por exemplo: 
https://trailhead.salesforce.com/users/strailhead/trailmixes/build-your-developer-career-on-salesforce

### Trailmixes
Além disso existem as Trailmixes que são conjuntos de trilhas feitas pela comunidade.
Algumas empresas têm suas próprias Trailmixes, com lições que julgam mais importantes para o dia-a-dia do profissional em aprendizado.

Exemplos: 

#### Deloitte
- Dev: https://trailhead.salesforce.com/en/users/jayres/trailmixes/deloitte-dev-dc
- Admin: https://trailhead.salesforce.com/en/users/jayres/trailmixes/deloitte-funcional-dc
- Geral: https://trailhead.salesforce.com/en/users/diogoboffabraga/trailmixes/deloitte

#### GFT
- Geral: https://trailhead.salesforce.com/en/users/asanches3/trailmixes/road-to-gft-forcers

#### Everis 
- Marketing Cloud: https://trailhead.salesforce.com/en/users/wanderjesus/trailmixes/marketing-cloud-everis-brasil

#### Wipro
- Lightning Web Components (LWC): https://trailhead.salesforce.com/en/users/egarcia22/trailmixes/lwc-path

	
Lembrar que o Trailhead possui lições que são apenas leitura, outras que para a conclusão é preciso acertar o Quiz e, um ultimo tipo, que são os que requerem que você realizar ações em um ambiente pessoal de desenvolvimento (Dev Org / Playgrounds) - haverá uma validação do ambiente para saber se você concluiu a tarefa corretamente
Esses ambientes são 100% gratuitos e você pode criar quantos quiser. Um ambiente Dev ou Playground possuem praticamente todas as capacidades de uma org paga usada em produção por um cliente.

### Documentação Salesforce
Outra forma de aprender sobre o Salesforce é pelo site de documentação, que é bem completo e atualizado:
- Landing page: https://developer.salesforce.com/docs#browse
- Apex Guide: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_dev_guide.htm
- Apex Docs: https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_ref_guide.htm

## Certificações
Um ponto importante na carreira Salesforce é conquistar as certificações oficiais da Salesforce.
Não é a única forma de crescer nessa carreira, mas facilita muito. Seguir sem certificações pode dar certo, não é nenhuma regra, nada obrigatório, porém, quando se possui mais experiência, verá que os demais profissionais do mesmo nível possuem pelo menos 2 ou 3 certificações.

### Como?
Você deve se perguntar agora: "tá, como faço para obter uma então?"
A resposta é que: as certificações oficiais da Salesforce são pagas e não custam barato, sobretudo pro brasileiro que hoje sofre com dolar boiando na faixa dos R$ 5,10.
Existem duas categorias principais: as de arquitetura e as demais. Para as de arquitetura, a prova custa $400 USD; as demais saem por $200 USD.
No entanto, apesar de serem caríssimas, é possível conseguir vouchers de desconto pela própria Salesforce ou direto da empresa que você trabalha.
- Pela Salesforce:
  - Existem diversos eventos, fisicos e virtuais, que promovem todos os anos e em vários desses é possível adquirir um voucher de desconto que vai de $50 USD até $150 USD
  - A Salesforce prepara alguns webinars, palestras e cursos introdutórios/preparatórios relacionados a primeira certificação. Alguns desses 'eventos' podem oferecer, para quem participa, vouchers de até 100% de desconto para primeiras certificações de até $200 USD.
  - Também existem os vouchers globais e regionais. Pessoalmente não vejo um há um bom tempo, mas até durante a pandemia de 2021, costumava ser fácil encontrar vários vouchers com $50 e $100 de desconto
- Pela empresa:
  - Algumas empresas, sobretudo as de consultoria, possuem parceria com a Salesforce e conseguem um pacote de vouchers de 100% de desconto para diversas provas, incluindo até as de arquitetura em alguns casos.
  - Outras, que não possuem essa parceria suficiente para garantir vouchers, podem oferecer reembolso quando o profissional conquista a certificação (a maioria não vai te reembolsar se você falhar, procure saber antes de marcar a prova como funciona)
- (Bonus) conseguir certificação de graça sem pagar nada nada:
  - Além de todas essas formas, é possível conseguir se certificar se você se inscrever no programa de Certificações Beta da Salesforce. São certificações que os voluntários selecionados irão mais com intuito de testar as novas questões que serão aplicadas do que de fato se certificar.

Importante lembrar que você precisa ter uma conta [Trailhead](https://trailhead.salesforce.com/) e uma conta no [Webassessor](https://www.webassessor.com/).
As provas são compradas pelo Webassessor.
As certificações são exibidas na conta Trailhead linkada no Webassessor

> **Note**:
> <u>Nunca crie uma conta Webassessor com email da sua empresa</u>, use o email **PESSOAL**. As certificações são **SUAS**, não das empresas que você trabalha

## Impacto do Trailhead e mais informações
Por fim, o trailhead serve, além de tudo, como portfólio no mundo de Salesforce. Na sua página Trailblazer (perfil do trailhead) é possível ver as conquistas da pessoa pela quantidade de pontos e badges. Além disso, um ponto importante para trabalhar com Salesforce é obter certificações. Assim como a Microsoft, Oracle, SAP e AWS, um profissional pode se certificar em Salesforce em diversos assuntos.
As certificações em Salesforce ajudam muito a alavancar a carreira e conseguir empregos nas melhores empresas (apesar de ser possível ir longe sem certificações, ter algumas facilita a sua vida).

> **Note**: 
> No perfil trailblazer também serão exibidas as certificações conquistadas

Exemplo de perfil Salesforce:
https://trailblazer.me/id/ferdam


Obrigado 😎
