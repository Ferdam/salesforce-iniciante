# Questionário - Entrevista Técnica Salesforce
Fique à vontade para estudar estes tópicos. Vários deles costumam cair em entrevistas técnicas de Salesforce (para Dev sobretudo).

## Fundamentos da Plataforma
1. Explique a diferença entre Objeto Standard, Objeto Custom e Objeto Externo no Salesforce.
2. Descreva a diferença entre Profile e Permission Set. Em quais cenários você usaria cada um?
3. Qual a diferença essencial entre Roles (Papeis) e Profiles (Perfis) no Salesforce?
4. Discorra sobre Custom Metadata Types, Custom Settings e Custom Labels e suas utilidades na implementação de funcionalidades no Salesforce.

## Apex e Programação
1. Descreva a diferença entre Objeto e Classe em programação orientada a objetos (OOP).
2. Qual estrutura de organização de código você recomendaria para implementar uma Apex Trigger?
3. Explique os conceitos de:
   - Bulkification em Apex
   - Métodos estáticos vs não-estáticos
   - Interfaces e classes abstratas
4. Como você implementaria o padrão de design Factory em Apex? Em qual cenário isso seria útil?
5. Quais são as implicações de colocar uma query SOQL dentro de um loop? Como você evitaria esse problema?
6. Para que servem/qual a utilidade de Maps na programação Apex (Javascript, C# também servem)?

## Manipulação de Dados
1. Liste maneiras que permitam atualizar uma grande massa de registros (milhares~milhões) no Salesforce (cite ao menos uma externa)? Compare as vantagens e desvantagens de cada abordagem.
2. Explique a diferença entre SOQL e SOSL. Quando você usaria cada um?
3. Como você pode trazer registros pais e seus respectivos filhos em uma única consulta? Forneça um exemplo.
4. O que são governor limits? Cite três limites e descreva como contornar um deles.
5. O que é uma Transaction em Salesforce? (escopo de Backend/Database) 

## Integrações e Comunicação
1. Explique o que são Platform Events e como funcionam. Qual solução utilizando Platform Events você implementou ou conhece?
2. Descreva os diferentes métodos de integração disponíveis no Salesforce (REST API, SOAP API)
3. Ao receber um requisito de integração com sistemas externos sem detalhes específicos, quais perguntas você faria e quais passos seguiria para implementar essa solução?
4. Liste as formas que conhece para realizar um callout a um sistema externo via Apex.

## Componentes de Interface
1. Compare LWC e Aura Components. Quais são as principais diferenças?
2. Como é feita a comunicação entre componentes em LWC?
3. Explique o ciclo de vida de um componente LWC.
4. Como você traz dados do Salesforce para um componente LWC?

## Automação
1. Compare Workflows, Process Builders e Flows. Quais critérios você usaria para decidir qual ferramenta utilizar?
2. Quais são os diferentes tipos de Flows disponíveis e quando você usaria cada um?
3. Como você parametrizaria uma funcionalidade desenvolvida em Apex/LWC/Flow, permitindo assim manutenção da funcionalidade sem alterar código diretamente?
4. Quantas triggers por objeto posso ter? Posso ter Triggers em Apex e Flows ao mesmo tempo num mesmo objeto? Qual a melhor prática?

## DevOps e Testes
1. Descreva sua experiência com esteiras de DevOps para Salesforce. Quais ferramentas você já utilizou?
2. Explique as melhores práticas para escrever classes de teste em Apex, incluindo o uso de Test.startTest() e Test.stopTest().
3. Para que servem os Asserts nas classes de testes? Qual a melhor maneira de usa-los?
4. Como você implementaria uma estratégia de CI/CD para projetos Salesforce? Considere um projeto simples e uma arquitetura de orgs simplificada (DEV, QA, PROD)

## Experiência Adicional
1. Além de Salesforce, quais outras linguagens, tecnologias ou plataformas você conhece? Como essa experiência complementa seu trabalho com Salesforce?
2. Descreva um desafio técnico complexo que você enfrentou em um projeto Salesforce e como o solucionou.
3. Como você se mantém atualizado sobre as novas funcionalidades e melhores práticas do Salesforce?
4. Já utilizou alguma ferramenta de AI que auxilie a criação de código? Qual/quais? Alguma via prompt? Dê um exemplo de prompt ou como montaria um.
