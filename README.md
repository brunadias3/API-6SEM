# API- Projeto Integrador 6º Semestre ADS - Grupo Fatech

Projeto desenvolvido por alunos do sexto semestre do curso de análise e desenvolvimento de sistemas da Fatec - SJC, durante o primeiro semestre do ano de 2024.

## 🎯 Objetivo

<div style="text-align: justify">

Monitoramento automático por imagem de acesso a área restrita

![Objetivo](https://github.com/4-Fatech/API-6SEM/assets/88987612/4b46e5a5-1277-45da-a834-f280b7e8fe8b)


> Status do Projeto: Em Desenvolvimento.

</br>

</div>

## 📩 Proposta

**Desenvolver um sistema web com os seguintes requisitos:**

> Requisitos Funcionais

- [X] RF1 - Desenvolver uma interface web intuitiva, com autenticação;
- [ ] RF2 - Desenvolver um Dashboard de indicadores por períodos;
- [X] RF3 - Filtros de período para análise dos dados;
- [X] RF4 - Geração de relatórios para compartilhamento.
- [X] RF5 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Usuários.
- [X] RF6 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Redzone.
- [X] RF7 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Departamento.
- [x] RF8 - Utilizar a câmera da entrada para contabilizar as pessoas que entraram e saíram da Redzone.
- [X] RF9 - Criar três níveis (Usuário de visualização, Gerente Por Departamento e Gerente geral ) de acesso para o projeto.


> Requisitos Não Funcionais

- [ ] RNF1 - Manual do Usuário;
- [ ] RNF2 - Documentação do sistema;
- [X] RNF3 - Guia de instalação; [Front](https://github.com/4-Fatech/API-6SEM-Front/tree/main?tab=readme-ov-file#-rodando-a-aplica%C3%A7%C3%A3o-web-modo-desenvolvimento) - [Back](https://github.com/4-Fatech/API-6SEM-Back/tree/main?tab=readme-ov-file#-rodando-a-aplica%C3%A7%C3%A3o-web-modo-desenvolvimento) - [IA](https://github.com/4-Fatech/API-6SEM-AI/tree/main?tab=readme-ov-file#-rodando-a-aplica%C3%A7%C3%A3o-modo-desenvolvimento)
- [X] RNF4 - Acesso a organização do desenvolvimento (kanban, git...)

## 📅 Cronograma das Sprints

- [X] <a href="https://github.com/4-Fatech/API-6SEM-Docs/tree/main/Sprint%201">**1° Sprint:**</a> 25/03/2024 a 14/04/2024<br>
- [X] <a href="https://github.com/4-Fatech/API-6SEM-Docs/tree/main/Sprint%202">**2° Sprint:**</a> 15/04/2024 a 05/05/2024
- [x] <a href="https://github.com/4-Fatech/API-6SEM-Docs/tree/main/Sprint%203">**3° Sprint:**</a> 06/05/2024 a 26/05/2024
- [ ] <a href="">**4°Sprint:**</a> 27/06/2024 a 16/06/2024
- [ ] **Feira de Soluções:** 27/06/2024

 </br>
    
 ## 💻 Tecnologias Utilizadas
 
![Tecnologia](https://github.com/4-Fatech/API-6SEM/assets/89146258/94e376db-e0c1-4b8d-b600-53fdb359c92b)

- **Back-end:** SpringBoot, SupaBase, Python.
- **Front-end:** TypeScript utilizando Vue.
- **Ferramentas:** Visual Studio Code, Azure Devops,   Canva, Git, Github, Discord, Slack e Microsoft Teams.

## 💡 Metodologia

<ul> <li> <strong>Metodologia Ágil: SCRUM </strong> </li> </ul>
</br>

![Metodologia](https://github.com/4-Fatech/API-6SEM/assets/88987612/5b5f6c37-52bb-4840-a4b4-460741086daa)

## 🗒️ Backlog Priorizado
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- |--- |
| 1 | Alta | Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzone para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual. | 80 | 1 | RF8 |
| 2 | Alta | Como gerente, desejo ter a capacidade de visualizar os registros de acesso à redzone, a fim de identificar precisamente os horários de entrada e saída dos usuários, possibilitando um monitoramento eficaz das atividades. | 60 | 1 | RF6 |
| 3 | Alta |Como gerente, desejo visualizar em tempo real a quantidade de pessoas na redzone, para poder monitorar efetivamente a presença de indivíduos nessa área específica. | 15 | 1 | RF8 |
| 4 | Alta |Como gerente, desejo uma interface de busca que utilize a data como filtro e apresente os resultados em uma tabela, incluindo os horários de entrada e saída na redzone, para facilitar futuras análises de dados. | 10 | 1 | RF6 |
| 5 | Média | Como gerente geral, quero poder criar um departamento no sistema, fornecendo informações como nome, responsável e redzones atreladas a esse departamento, para cadastrar as novas redzones. | 15 | 2 | RF7 |
| 6 | Média | Como gerente geral, quero uma página inicial que me permita acessar facilmente todas os departamentos monitorados, incluindo métricas importantes como capacidade atual e alertas ativos, para facilitar o gerenciamento. | 15 | 2 | RF7 |
| 7 | Média | Como gerente geral, quero poder criar uma nova redzone no sistema ela tem que estar atrelada ao departamento que sou responsável, fornecendo informações como nome, responsável, câmera e capacidade máxima, para cadastrar as novas redzones.| 15 | 2 | RF6 |
| 8 | Média | Como gerente geral, quero uma página inicial que me permita acessar facilmente todas as informações como métricas importantes como capacidade atual, alertas ativos e responsável pela redzone, para facilitar o gerenciamento. | 15 | 2 | RF6 |
| 9| Média |Como gerente, desejo uma ferramenta que permita filtrar (por período desejado) os dados de acesso para comparação, para analisar tendências e identificar variações significativas. | 15 | 2 | RF3 |
| 10 | Média | Como gerente, desejo uma função de exportação de dados que me permita baixar relatórios detalhados contendo todas as datas e horários de entrada e saída na redzone durante o período escolhido, para análise externa. |15 | 2 | RF4 |
| 11 | Média | Como gerente geral, quero poder alterar os dados de um determinado departamento no sistema, para poder cadastrar e corrigir dados já existentes. | 10 | 2 | RF7 |
| 12 | Média | Como gerente geral, quero poder alterar os dados de uma determinada redzone no sistema, para poder cadastrar e corrigir dados já existentes. | 10 | 2 | RF6 |
| 13 | Média | Como gerente geral, quero poder cadastrar um novo usuário no sistema, fornecendo seu nome, e-mail, matrícula da empresa e tipo de usuário, (guarda, gerente de área), para garantir que a equipe de segurança esteja completa e atualizada. | 10 | 2 | RF5 |
| 14 | Média | Como gerente geral, desejo uma funcionalidade que me permita visualizar todos os usuários do sistema, sendo os gerentes de área e guardas, para ter uma visão geral da equipe de segurança. | 10 | 2 | RF5 |
| 15 | Média | Como gerente geral, quero poder alterar do usuário, para lidar com mudanças dos dados da equipe. | 10 | 2 | RF5 |
| 16 | Média | Como gerente geral, quero poder desativar um determinado departamento, para garantir a segurança e integridade das áreas monitoradas. | 5 | 2 | RF7|
| 17 | Média | Como gerente geral, quero poder desativar uma determinada redzone, para garantir a segurança e integridade das áreas monitoradas. | 5 | 2 | RF6 |
| 18 | Média | Como gerente geral, quero poder desativar um usuário, para impedir o acesso quando necessário. | 5 | 2 | RF5 |
| 19 | Média | Como gerente geral, necessito de uma função de exportação de dados que me permita baixar relatórios de um departamento específico, com informações detalhadas sobre as datas e horários de entrada e saída na redzones durante o período selecionado para realizar análises externas mais detalhadas e precisa | 20 | 3 | RF4 |
| 20 | Média | Como Gerente Geral, quero um login que gerencie o acesso de usuários com diferentes níveis de permissão, incluindo guardas, gerentes de área e outros gerentes gerai, para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades, mantendo assim a segurança e a integridade dos dados da empresa. | 20 | 3 | RF9 |
| 21 | Baixa |Como gerente, quero poder recuperar minha senha através de um processo seguro e confiável, para caso eu a esqueça no futuro. | 10 | 3 | RF9 |
| 22 | Alta | Como gerente, quero um manual do usuário detalhado e fácil de entender, que forneça orientações passo a passo sobre como utilizar todas as funcionalidades do sistema, para que eu possa utilizar o sistema de forma eficaz e sem problemas. | 40 | 4 | RNF1 | 
| 23 | Média | Como gerente geral, quero um dashboard que compile e exiba métricas importantes de todos os departamentos, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas em relação à segurança e gestão de recursos. | 20 | 4 | RF2 |
| 24 | Média |Como gerente área, quero um dashboard que compile e exiba métricas importantes de todos as redzones que são do meu departamento, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas. | 20 | 4 | RF2 |
| 25 | Baixa | Como gerente geral, quero um guia de instalação detalhado e claro, para facilitar a implantação do sistema. | 20 | 4 | RNF3 |


## 📃 DoR(Definition of Ready):

- [User Stories](https://dev.azure.com/Fatech-Api/Api-6/_workitems/recentlyupdated/)

- [Modelo do Banco de Dados](https://github.com/4-Fatech/API-6SEM-Docs?tab=readme-ov-file#-modelo-entidade-relacionamento)

- [Mockups](https://github.com/4-Fatech/API-6SEM-Docs?tab=readme-ov-file#-layout---mockups)

- [Dados](https://github.com/4-Fatech/API-6SEM-Docs?tab=readme-ov-file#-dados)
</br>


## 👥 Equipe

| Nome             | Função        | GitHub                                                                    | Linkedin                                                                                                       |
| ---------------- | ------------- | ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Everton Ricardo  | Master        | <a href="https://github.com/Evertonrwr" target="_blank">Github</a>        | <a href="https://www.linkedin.com/in/everton-rocha-1a456b20b" target="_blank">Link</a>                         |
| André Ribeiro    | Product Owner | <a href="https://github.com/New-Tomorrow" target="_blank">Github</a>      | <a href="https://www.linkedin.com/in/andre-ramos-ribeiro-320621226/" target="_blank">Link</a>                  |
| Antônio Barbosa  | Desenvolvedor | <a href="https://github.com/Antonio-Barbosa" target="_blank">Github</a>   | <a href="https://www.linkedin.com/in/antonio-marcelo-9a5b68181" target="_blank">Link</a>                       |
| Bruna Dias       | Desenvolvedor | <a href="https://github.com/brunadias3" target="_blank">Github</a>        | <a href="https://www.linkedin.com/in/bruna-dias-977b611b9/" target="_blank">Link</a>                           |
| Dionísio Leão    | Desenvolvedor | <a href="https://github.com/dsslleagion" target="_blank">Github</a>       | <a href="https://www.linkedin.com/in/dionisio-samuel-dos-santos-le%C3%A3o-616848226/" target="_blank">Link</a> |
| Gabriel Coutinho | Desenvolvedor | <a href="https://github.com/Gabriel-Coutinho0" target="_blank">Github</a> | <a href="https://www.linkedin.com/in/gabriel-silva-b778a31aa" target="_blank">Link</a>                         |                     |

</br>
