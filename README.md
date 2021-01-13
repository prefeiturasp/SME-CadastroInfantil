# Estratégia de Transformação Digital e Governo Aberto na SME

Como um governo pode atuar para garantir o bem comum de todos? Na SME, acreditamos que um dos meios para isso seja garantir transparência e prestação de contas e constante relação entre governo e sociedade para o desenvolvimento e implementação de políticas públicas. 

A Portaria SME nº 8.008, de 12 de novembro de 2018 oficializou a estratégia da Secretaria Municipal de Educação de SP para que nossas ações sejam pautadas nos princípios de Governo Aberto e para usarmos os valores e benefícios do mundo digital para melhorarmos nossos processos e serviços para os cidadãos. Com isso, pretendemos: 

- aumentar os níveis de transparência ativa e de abertura de dados, garantindo a proteção de dados pessoais; 
- instituir metodologias ágeis e colaborativas como parte do processo de desenvolvimento e de evolução de sistemas administrativos e de serviços digitais; 
- fortalecer o controle das políticas educacionais e da aplicação de recursos por parte da gestão e da sociedade; 
- promover espaços e metodologias de colaboração entre governo, academia, sociedade civil e setor privado. 

O [Ateliê do Software](http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1X/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf) é uma das ferramentas para operacionalização. Baseado em um modelo de contratação inspirado pelos movimentos ágil e de Software Craftsmanship, trabalhamos com equipes multidisciplinares para o desenvolvimento de produtos que beneficiam toda a comunidade escolar (técnicos da SME e DREs, gestores, professores, alunos e famílias) e concretizam os objetivos da Estratégia de Transformação Digital e Governo Aberto “Pátio Digital”.

# Conteúdo

1.  [Sobre o Produto](#sobre-o-produto)

2.  [Como surgiu](#como-surgiu)

3.  [Links Úteis](#links-úteis)

4.  [Comunicação](#comunicação)

5.  [Como contribuir](#como-contribuir)

6.  [Repositórios](#repositórios)

7.  [Instalação e Configuração](#instalação-e-configuração)

# Sobre o Produto

## Visão de Futuro

Para as  **famílias e responsáveis dos estudantes**

Que  **gostariam de inscrever as crianças na Educação Infantil sem a necessidade do atendimento presencial**

O  **Cadastro Infantil**

É um  **formulário online**

Que  **possibilita o pré-cadastro na rede municipal de educação**

Diferentemente da **necessidade de atendimento presencial**

O Nosso produto **possibilita que as famílias registrem o interesse de ingresso na Educação Infantil** 

## Objetivos de Negócio

O Cadastro Infantil é um formulário online para realização do pré-cadastro de crianças na Educação Infantil da rede municipal de educação. Com isso, a SME apoia as orientações dos órgãos de saúde de evitar aglomerações e garante maior facilidade e agilidade no momento de inscrição.

**O que é/Faz**

- Um formulário para cadastro da intenção de matrícula na Educação Infantil da rede municipal de São Paulo

**O que não é/não faz**

- Não garante a efetivação da matrícula

- Não realiza todo o processo de matrícula que deve ser seguido de acordo com legislação

## Personas

**Quem:** Famílias e responsáveis
**Características principais:** público bastante heterogêneo que gostaria de cadastrar as crianças na Educação Infantil da rede pública
**Necessidades:** garantir uma vaga da educação infantil próximo a sua residência e realizar o cadastro com facilidade para a rede municipal inteira

**Quem:** técnicos das Diretorias Regionais de Educação (DREs)
**Necessidades:** receber da SME os cadastros realizados no sistema

**Quem:** servidores da Secretaria Municipal de Educação (SME)
**Necessidades:** encaminhar cadastro para as DREs responsáveis inserirem o cadastro no sistema e acompanhar se todos os cadastros foram realizados

## Funcionalidades

- Formulário de cadastro de interesse, com e-mail automatizado de confirmação de realização de cadastro

## Jornadas

- Família faz cadastro

- SME recebe cadastro e repassa para DRE

- DRE faz cadastro no Eol e retorna para SME

- SME envia e-mail para cadastrante com número do protocolo pelo e-mail próprio do Cadastro Infantil

## Roadmap

Não há roadmap previsto, uma vez que a evolução desse produto é realizar o cadastro diretamente via Eol.

# Como surgiu

## Fase de Descoberta:

Surgiu da necessidade das famílias e responsáveis realizarem o cadastro na Educação Infantil da rede municipal de ensino durante o período que as escolas estavam com horário reduzido por conta da pandemia. Com essa situação, identificou-se a possibilidade de criação de um modelo remoto de cadastro para garantir o atendimento a todas as famílias que buscam uma vaga na Educação Infantil na rede municipal.

**Entrevista com a área de negócio:**

Não houve etapa oficial de descoberta por conta da urgência da demanda, mas existiu um momento de pesquisa interna com área de negócios para melhorias no produto.

**Oficina sobre Ateste:**

Não houve oficina de ateste com usuários finais, mas existiram diversos testes internos para melhorias no produto antes do lançamento e também melhorias identificadas a partir de experiências com os primeiros cadastros.

## Protótipos:

O protótipo foi criado a partir de documentos produzidos pela área com as informações necessárias para a realização do cadastro infantil.

## Testes de Usabilidade

Não houve oficina de ateste com usuários finais, mas existiram diversos testes internos para melhorias no produto antes do lançamento e também melhorias identificadas a partir de experiências com os primeiros cadastros.

# Links Úteis

**Homologação:**
https://hom-cadastroinfantil.sme.prefeitura.sp.gov.br/

**Produção:**
https://cadastroinfantil.sme.prefeitura.sp.gov.br/

# Comunicação

| Canal de comunicação | Objetivos |
|----------------------|-----------|
| [Issues do Github](https://github.com/prefeiturasp/SME-CadastroInfantil/issues) | - Sugestão de novas funcionalidades<br> - Reportar bugs<br> - Discussões técnicas |

# Como contribuir

Contribuições são **super bem vindas**! Se você tem vontade de construir o Cadastro Infantil conosco, veja o nosso [guia de contribuição](./CONTRIBUTING.md) onde explicamos detalhadamente como trabalhamos e de que formas você pode nos ajudar a alcançar nossos objetivos. Lembrando que todos devem seguir  nosso [código de conduta](./CODEOFCONDUCT.md).

# Repositórios

[SME-CADASTRO INFANTIL - FRONT]
https://github.com/prefeiturasp/SME-CadastroInfantil-FrontEnd

[SME-CADASTRO INFANTIL - BACK]
https://github.com/prefeiturasp/SME-CadastroInfantil-BackEnd

# [](#instalacao-e-configuracao)Instalação e Configuração:

## Pré-requisitos

-   npm
-   git

## Instruções

Após clonar o projeto, execute o comando para instalar as bibliotecas utilizadas:

    $ npm install
  
## Configurando as variáveis de ambiente

Crie um arquivo *.env* na raiz do projeto. Nele, utilize a variável **REACT_APP_API_URL** com o endereço do backend para realizar as requisições.

    conf
    public
    node_modules
    src
    .env

## Execução do projeto

Para rodar o projeto, basta:

    $ npm start
Pré-requisitos
Docker
Docker Compose
Build do projeto
Para buildar as imagens do projeto, executar o comando abaixo

$ docker-compose -f local.yml build
Execução do projeto
Abra um terminal na raiz do projeto e execute o seguinte para o desenvolvimento local:

$ docker-compose -f local.yml up
Executar comandos de gerenciamento
Como acontece com qualquer comando shell que desejamos executar em nosso contêiner, isso é feito usando o comando docker-compose -f local.yml run --rm:

$ docker-compose -f local.yml run --rm django python manage.py migrate
$ docker-compose -f local.yml run --rm django python manage.py createsuperuser
Configurando as váriaveis de ambiente
As pastas com as variaves estão dispostas da seguinte maneira: :

.envs

├── .local

│   ├── .django

│   └── .postgres

└── .production 

    ├── .django
    
    └── .postgres 
