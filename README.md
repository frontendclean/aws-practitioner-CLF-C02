# Guia para o AWS Certified Cloud Practitioner (CLF-C02)

![Tela inicial](./assets/img/practitioner.png)

Este repositório foi criado para ajudar quem está se preparando para a certificação **AWS Certified Cloud Practitioner**. O foco é compartilhar **recursos gratuitos**, **explicações simples** e **dicas práticas** para quem está começando na nuvem AWS.

## O que é a certificação Cloud Practitioner?

A certificação **Cloud Practitioner** é a porta de entrada para o mundo AWS. Ela é ideal para iniciantes e valida conhecimentos básicos sobre:
- Conceitos de nuvem
- Serviços principais da AWS
- Segurança e conformidade
- Preços e suporte

---

## Recursos de Estudo

### 1. **Guia do exame** 
- [AWS Guia do exame (português)](https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
  > Guia oficial da AWS.

### 2. **Cursos gratuitos**
- [AWS Cloud Practitioner Essentials (português)](https://www.aws.training/Details/Curriculum?id=20685)
  > Curso oficial e gratuito da AWS. Ideal para começar.

### 3. **Simulados e testes**

- [AWS Pré-teste](https://explore.skillbuilder.aws/learn/courses/18542/simulado-oficial-de-recursos-para-exames-aws-certified-cloud-practitioner-clf-c02-portugues-brasil-exam-prep-official-pretest-aws-certified-cloud-practitioner-clf-c02-portuguese-brazil)
  > Pré-teste oficial da AWS.

- [Exame de demonstração da AWS (Official Sample Questions)](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf)
  > PDF com perguntas oficiais de exemplo.

- [Tutorial Dojo (ExamTopics)](https://www.examtopics.com/exams/amazon/aws-certified-cloud-practitioner/view/)
  > Questões comentadas por outros candidatos. Use com senso crítico.

- [Simula+ (Criado por @frontendclean) GRATUITO](https://simulaplus.com.br/)
  > Plataforma com diversas questões e simulados para praticar.

---

## O que estudar (+130 tópicos)

### Menu 

- [Cloud computing](#cloud-computing)
- [Nuvem pública](#nuvem-pública)
- [Nuvem privada](#nuvem-privada)
- [Escalabilidade](#escalabilidade)
- [Elasticidade](#elasticidade)
- [Disponibilidade](#disponibilidade)
- [AWS Account](#aws-account)
- [AWS Free Tier](#awsfreetier)
- [AWS Pricing Calculator](#aws-pricing-calculator)
- [AWS Identity and Access Management (IAM)](#aws-identity-and-access-management-iam)
- [IAM Identity Center](#iam-identity-center)
- [IAM Credential Report](#iam-credential-report)
- [Access Advisor](#access-advisor)
- [AWS Organizations](#aws-organizations)
- [CloudShell](#cloudshell)
- [CLI](#cli-command-line-interface)
- [AWS Access](#aws-access)
- [AWS SDK (Software Development Kit)](#aws-sdk-software-development-kit)
- [AWS Wavelength](#aws-wavelength)
- [AWS Outposts](#aws-outposts)
- [Shared Responsibility Model](#shared-responsibility-model)
- [CloudWatch](#cloudwatch)
- [EC2 (Elastic Compute Cloud)](#ec2-elastic-compute-cloud)
- [EC2 Instance Connect](#ec2-instance-connect)
- [Security Group](#security-group)
- [AMI (Amazon Machine Image)](#ami-amazon-machine-image)
- [Amazon EBS (Elastic Block Store)](#amazon-ebs-elastic-block-store)
- [Snapshots](#snapshots)
- [Snapshot X AMI](#snapshot-x-ami)
- [Amazon EFS (Elastic File System)](#amazon-efs-elastic-file-system)
- [Diferença entre EFS, EBS e S3](#diferença-entre-efs-ebs-e-s3)
- [Amazon FSx (File System X)](#amazon-fsx-file-system-x)
- [AWS Auto Scaling](#aws-auto-scaling)
- [ELB (Elastic Load Balancing)](#elb-elastic-load-balancing)
- [Amazon S3 (Simple Storage Service)](#amazon-s3-simple-storage-service)
- [Bucket S3](#bucket-s3)
- [Classes de armazenamento do Amazon S3](#classes-de-armazenamento-do-amazon-s3)
- [Versionamento no Amazon S3](#versionamento-no-amazon-s3)
- [Criptografia no Amazon S3](#criptografia-no-amazon-s3)
- [AWS Storage Gateway](#aws-storage-gateway)
- [Amazon S3 Transfer Acceleration](#amazon-s3-transfer-acceleration)
- [AWS Snow Family](#aws-snow-family)
- [Bancos de Dados](#bancos-de-dados)
- [Amazon RDS](#amazon-rds)
- [Amazon Aurora](#amazon-aurora)
- [Amazon ElastiCache](#amazon-elasticache)
- [Amazon DynamoDB](#amazon-dynamodb)
- [Amazon Neptune](#amazon-neptune)
- [AWS Glue](#aws-glue)
- [Amazon Redshift](#amazon-redshift)
- [VPC (Virtual Private Cloud)](#vpc-virtual-private-cloud)
- [Subnet](#subnet)
- [Internet Gateway (IGW)](#internet-gateway-igw)
- [Network ACL (Access Control List)](#network-acl-access-control-list)
- [VPC Peering](#vpc-peering)
- [VPC Endpoints](#vpc-endpoints)
- [VPC Flow Logs](#vpc-flow-logs)
- [VPN (Virtual Private Network)](#vpn-virtual-private-network)
- [AWS PrivateLink](#aws-privatelink)
- [AWS Direct Connect ](#aws-direct-connect)
- [AWS Transit Gateway](#aws-transit-gateway)
- [Amazon Route 53](#amazon-route-53)
- [Amazon CloudFront](#amazon-cloudfront)
- [AWS Global Accelerator](#aws-global-accelerator)
- [Docker](#docker)
- [ECS (Elastic Container Service)](#ecs-elastic-container-service)
- [EKS (Elastic Kubernetes Service)](#eks-elastic-kubernetes-service)
- [AWS Fargate](#aws-fargate)
- [Amazon Kinesis](#amazon-kinesis)
- [Amazon SQS (Simple Queue Service)](#amazon-sqs-simple-queue-service)
- [Amazon SNS (Simple Notification Service)](#amazon-sns-simple-notification-service)
- [AWS Batch](#aws-batch)
- [Amazon Lightsail](#amazon-lightsail)
- [AWS Lambda](#aws-lambda)
- [AWS Control Tower](#aws-control-tower)
- [AWS RAM (Resource Access Manager)](#aws-ram-resource-access-manager)
- [AWS Trusted Advisor](#aws-trusted-advisor)
- [AWS Service Catalog](#aws-service-catalog)
- [Amazon Rekognition](#amazon-rekognition)
- [Amazon Transcribe](#amazon-transcribe)
- [Amazon Comprehend](#amazon-comprehend)
- [Amazon Polly](#amazon-polly)
- [Amazon Translate](#amazon-translate)
- [Amazon Lex](#amazon-lex)
- [Amazon Kendra](#amazon-kendra)
- [Amazon Textract](#amazon-textract)
- [Amazon SageMaker](#amazon-sagemaker)
- [AWS Well-Architected Framework](#aws-well-architected-framework)
- [AWS CAF (Cloud Adoption Framework)](#aws-caf-cloud-adoption-framework)
- [AWS Ecosystem (Ecossistema AWS)](#aws-ecosystem-ecossistema-aws)
- [AWS Cognito](#aws-cognito)
- [Amazon STS (Security Token Service)](#amazon-sts-security-token-service)
- [AWS AppSync](#aws-appsync)
- [AWS Amplify](#aws-amplify)
- [AWS IoT Core](#aws-iot-core)
- [AWS Step Functions](#aws-step-functions)
- [AWS AppFlow](#aws-appflow)
- [AWS Disaster Recovery Strategy (Estratégia de Recuperação de Desastres da AWS)](#aws-disaster-recovery-strategy-estratégia-de-recuperação-de-desastres-da-aws)
- [AWS WorkSpaces](#aws-workspaces)
- [AWS WAF (Web Application Firewall)](#aws-waf-web-application-firewall)
- [Bring Your Own License (BYOL), ou Traga Sua Própria Licença](#bring-your-own-license-byol-ou-traga-sua-própria-licença)
- [AWS CloudFormation](#aws-cloudformation)
- [AWS Artifact](#aws-artifact)
- [Amazon Inspector](#amazon-inspector)
- [AWS Security Hub](#aws-security-hub)
- [Amazon GuardDuty](#amazon-guardduty)
- [AWS Shield](#aws-shield)
- [AWS Config](#aws-config)
- [AWS Knowledge Center](#aws-knowledge-center)
- [AWS Database Migration Service (DMS)](#aws-database-migration-service-dms)
- [AWS Schema Conversion Tool (SCT)](#aws-schema-conversion-tool-sct)
- [Amazon EventBridge](#amazon-eventbridge)
- [AWS Budgets](#aws-budgets)
- [AWS Cost Explorer](#aws-cost-explorer)
- [Amazon Athena](#amazon-athena)
- [Amazon EMR (Elastic MapReduce)](#amazon-emr-elastic-mapreduce)
- [AWS Elastic Beanstalk](#aws-elastic-beanstalk)
- [AWS CloudHSM](#aws-cloudhsm)
- [AWS Detective](#aws-detective)
- [Amazon Macie](#amazon-macie)
- [AWS Compute Optimizer](#aws-compute-optimizer)
- [AWS Resource Explorer](#aws-resource-explorer)
- [Amazon QuickSight](#amazon-quicksight)
- [AWS Support](#aws-support)
- [AWS Professional Services](#aws-professional-services)
- [AWS Launch Wizard](#aws-launch-wizard)
- [Amazon Personalize](#amazon-personalize)
- [AWS DataSync](#aws-datasync)
- [AWS Audit Manager](#aws-audit-manager)
- [AWS CloudTrail](#aws-cloudtrail)
- [AWS License Manager](#aws-license-manager)
- [AWS Certificate Manager (ACM)](#aws-certificate-manager-acm)
- [Amazon Forecast](#amazon-forecast)
- [AWS Application Discovery Service](#aws-application-discovery-service)
- [AWS Application Migration Service (MGN)](#aws-application-migration-service-mgn)
- [AWS Key Management Service (KMS)](#aws-key-management-service-kms)

---

### Cloud computing

Cloud computing (ou computação em nuvem) é um modelo de fornecimento de recursos de computação — como servidores, armazenamento, bancos de dados, redes, software e mais — pela internet ("a nuvem"), em vez de depender de computadores locais ou servidores físicos.

#### Em termos simples:
É como alugar uma infraestrutura de TI em vez de comprar e manter tudo por conta própria.

#### Principais características:
- Acesso remoto: Você pode acessar serviços e dados de qualquer lugar, com internet.
- Escalabilidade: É fácil aumentar ou diminuir recursos conforme a necessidade.
- Pagamento sob demanda: Você paga apenas pelo que usar, como água ou luz.
- Atualizações automáticas: Os provedores mantêm os sistemas atualizados sem você precisar se preocupar.

#### Principais modelos:
- IaaS (Infrastructure as a Service): Infraestrutura básica (ex: AWS EC2, Azure VMs).
  - É um modelo de computação em nuvem onde você aluga recursos de infraestrutura de TI, como servidores, redes, armazenamento e sistemas operacionais, em vez de comprá-los e mantê-los fisicamente.
  - Ex: Em vez de comprar um servidor físico para rodar seu site, você aluga uma máquina virtual na AWS (EC2), Azure, ou Google Cloud, e instala o que quiser nela.
- PaaS (Platform as a Service): Plataforma para desenvolver e hospedar apps (ex: Heroku, Google App Engine).
  - É um modelo de computação em nuvem que oferece um ambiente completo para desenvolver, testar, implantar e gerenciar aplicações, sem você precisar se preocupar com a infraestrutura (como servidores, rede, sistema operacional).
  - Ex: Você quer criar um app web. Com PaaS, você só sobe o código e o serviço cuida do resto: servidor, deploy, escalabilidade, atualizações etc.
- SaaS (Software as a Service): Aplicações prontas para uso (ex: Gmail, Zoom, Salesforce).
  - É um modelo em que você usa um software pronto via internet, sem precisar instalar, configurar ou se preocupar com servidores, atualizações ou manutenção.
  - Ex: Gmail / Netflix 

#### Vantagens da cloud computing

  - Escalabilidade
    - Você pode aumentar ou reduzir recursos (como processamento e armazenamento) rapidamente, conforme a demanda do seu negócio.
    - Ex: durante uma Black Friday, seu site pode aguentar muito mais acessos sem travar.

  - Redução de custos
    - Elimina gastos com compra e manutenção de servidores físicos.
    - Modelo pay-as-you-go (pague pelo que usar).

  - Manutenção simplificada
    - O provedor de nuvem cuida de atualizações, segurança e infraestrutura.
    - Você foca no seu produto ou serviço, sem se preocupar com servidores.

  - Acesso remoto e mobilidade
    - Acesse seus sistemas e arquivos de qualquer lugar, em qualquer dispositivo com internet.

  - Segurança
    - Provedores grandes (como AWS, Azure, Google Cloud) oferecem criptografia, backups automáticos, controle de acesso e monitoramento 24/7.
    - Muitas vezes, a nuvem é mais segura do que servidores internos mal gerenciados.

  - Agilidade e inovação
    - Lançamento de produtos e ambientes em minutos.
    - Permite testar e inovar sem alto investimento inicial.

  - Colaboração facilitada
    - Equipes podem trabalhar juntas em tempo real em documentos, sistemas e projetos, mesmo à distância.

---

### Nuvem pública

É um modelo de computação em a AWS oferece infraestrutura, plataformas e serviços pela internet, compartilhados entre vários clientes. Você aluga recursos (servidores, storage, banco, IA, etc.) em vez de comprá‑los / mantê‑los.

#### Vantagens

  - Agilidade
  - Alcance global
  - Serviços gerenciado

---

### Nuvem privada

É um ambiente de computação em nuvem dedicado a uma única organização. Em vez de compartilhar a infraestrutura com outros clientes (como na nuvem pública), todo o hardware, rede e serviços ficam isolados — fisicamente ou logicamente — para uso exclusivo daquela empresa ou entidade.

#### Para que ele serve

  - Isolamento completo – recursos não são compartilhados com terceiros.
  - Maior controle – você decide topologia de rede, políticas de segurança, compliance, local físico dos dados.
  - Customização profunda – pode adaptar hardware, hypervisors e processos às necessidades do negócio.
  - Responsabilidade total – a maior parte da manutenção e segurança recai sobre sua equipe (ou sobre o provedor se for hospedada).

#### Vantagens

  - Atende requisitos rígidos de compliance (por ex., dados sensíveis de governo/saúde).
  - Previsibilidade de desempenho e ausência de "vizinhos barulhentos".
  - Integração fácil com sistemas legados no mesmo site.

---

### Escalabilidade 

É a capacidade de um sistema crescer (ou encolher) de acordo com a demanda, mantendo desempenho, estabilidade e eficiência.

Um sistema escalável aumenta ou reduz seus recursos (como servidores, armazenamento ou performance) conforme a necessidade, de forma automática ou planejada.

#### Tipos de escalabilidade

  - Horizontal
    > Adiciona ou remove mais servidores (ex: mais EC2s, mais containers)
  - Vertical
    > Aumenta ou reduz os recursos de um servidor só (ex: mais CPU ou RAM)

#### Vantagens

  - Atende mais usuários sem travar
  - Economiza recursos quando a demanda é baixa
  - Mantém desempenho estável mesmo com picos de acesso
  - Facilita manutenção e upgrades

---

### Elasticidade 

É a capacidade automática de um sistema aumentar ou diminuir seus recursos de forma dinâmica, conforme a carga de trabalho muda — sem intervenção manual.

Enquanto escalabilidade é a capacidade de crescer ou diminuir, a elasticidade é a ação automática e em tempo real de ajustar os recursos.

#### Pra que serve

  - Se o tráfego aumenta, o sistema adiciona recursos automaticamente
  - Se o tráfego cai, ele remove os recursos desnecessários
  - Isso acontece de forma rápida e automática, com base em regras ou métricas

#### Vantagens

  - Reduz custos automaticamente
  - Responde rápido a mudanças de carga
  - Ajusta recursos sem parar o sistema
  - Menos intervenção humana

---

### Disponibilidade 

É a capacidade de um sistema ou serviço permanecer acessível e funcional o maior tempo possível, mesmo diante de falhas ou picos de uso.

Um sistema com alta disponibilidade está sempre "no ar", minimizando interrupções para os usuários.

#### O que garante alta disponibilidade

  - Redundância: múltiplos servidores, zonas de disponibilidade, regiões
  - Balanceadores de carga: distribuem tráfego entre instâncias saudáveis
  - Auto Scaling: substitui recursos com falha automaticamente
  - Backups e failovers: permitem recuperação rápida
  - Monitoramento ativo: detecta e responde a problemas rapidamente

#### Vantagens

  - Melhor experiência para o usuário (menos quedas)
  - Mais confiabilidade para o negócio
  - Redução do tempo de recuperação
  - Continuidade de serviço mesmo com falhas

---

### AWS Account

É simplesmente a sua conta de usuário dentro da Amazon Web Service

#### Vantagens

  - Acessa e paga pelos serviços da AWS (EC2, S3, Lambda, etc.).
  - Isola recursos e cobrança
    > Tudo que você cria (máquinas virtuais, bancos, buckets) fica vinculado àquela conta e aparece na fatura correspondente. 
  - Gerencia permissões
    > Via IAM, você cria usuários/chaves e define quem pode fazer o quê.
  - Separa ambientes
    > muitas empresas mantêm contas distintas para produção, staging, testes, ou até por cliente/projeto, para manter segurança e controle de custos.

---

### AWS Free Tier

É so conjunto de ofertas "gratuitas" que a Amazon Web Services disponibiliza para quem criar (ou já tem) uma conta. Ele serve para testar e aprender sem pagar — desde que você fique dentro de certos limites

#### Existem três tipos de oferta

  - Gratuito por 12 meses
    > Começa na data em que você abre a conta e dura um ano.
  - Gratuito sempre (sempre que usar)
    > Recursos que permanecem grátis enquanto você se mantiver nos limites, mesmo depois de 12 meses.
  - Test‑drive pontual (trials)
    > Ofertas de curta duração (30, 60 ou 90 dias) que começam quando você ativa o serviço.

---

### AWS Pricing Calculator

É uma ferramenta gratuita da Amazon que permite estimar quanto vai custar usar os serviços da AWS antes de você contratá-los.

#### Pra que serve

  - Planejar custos de projetos na nuvem
  - Comparar tipos de instâncias ou serviços
  - Simular diferentes regiões (ex: São Paulo vs. Virgínia)
  - Fazer propostas para clientes com base realista

#### Vantagens

  - Transparência
  - Planejamento de orçamento
  - Simulações flexíveis
  - Gera relatórios

---

### AWS Identity and Access Management (IAM) 

É um sistema que controla e gerencia quem pode acessar o quê em um ambiente de TI, como uma rede, aplicativo ou sistema.

#### Principais funções do IAM

  - Gerenciar Identidades
    > Controla quem são os usuários (funcionários, clientes, sistemas) e cria contas de usuário.

  - Controlar Acesso
    > Define quais recursos cada usuário pode acessar, com base em suas permissões e funções.

  - Autenticação
    > Verifica a identidade do usuário, normalmente por meio de senhas, autenticação multifatorial (MFA), biometria, etc.

  - Autorização
    > Determina o que o usuário pode fazer após ser autenticado (ler, escrever, modificar dados, etc.).

  - Auditoria e Monitoramento
    > Registra as atividades de usuários para garantir que não haja acessos não autorizados.

  - Política de senha (personalizada)
    > Conjunto de regras definidas para criação, uso e manutenção de senhas. Ex: Não permitir repetição de senhas.

#### Para que ele serve

  - Criação de Identidades
    > Você cria contas de usuários (ou grupos de usuários) e atribui funções a essas contas.

  - Autenticação
    > Quando o usuário tenta acessar um sistema, o IAM verifica se ele é quem diz ser (por exemplo, com uma senha ou código enviado por SMS).

  - Autorização
    > Depois de autenticado, o IAM define o que o usuário pode fazer, com base em permissões que você definiu.
    
  - Auditoria
    > O sistema registra os acessos e atividades, permitindo rastrear quem fez o quê e quando.

#### Vantagens

  - Segurança
    > Minimiza o risco de acessos não autorizados.

  - Eficiência
    > Garante que os usuários tenham apenas as permissões necessárias para suas funções.

  - Conformidade
    > Ajuda a atender a requisitos legais e regulatórios, como a GDPR, ao manter um registro das ações dos usuários.

---

### IAM Identity Center

É um serviço da AWS que ajuda a gerenciar identidades e acessos de usuários de forma centralizada para múltiplas contas e aplicações dentro da AWS. Só é habilitado quando utilizamos o AWS Organizations.

#### Para que ele serve

  - Login centralizado (Single Sign-On – SSO)
    > Usuários fazem login uma única vez para acessar várias contas e serviços.

  - Gerenciamento de usuários e grupos
    > Você pode criar, organizar e gerenciar usuários e grupos dentro da AWS ou conectar a um sistema externo (como Microsoft Active Directory ou Google Workspace).

  - Atribuição de permissões
    > Define quais ações cada grupo ou usuário pode realizar em cada conta da AWS.

#### Vantagens

  - Centralização do acesso (SSO).
  - Gerenciamento mais fácil de múltiplas contas.
  - Integração com provedores externos de identidade (IdPs).
  - Relatórios e auditoria integrados.
  - Mais segurança e controle sobre acessos.

---

### IAM Credential Report

É um relatório gerado pela AWS que mostra o status de segurança das credenciais de todos os usuários IAM da sua conta.

#### Vantagens

  - Auditoria de segurança: ver quem está usando credenciais inseguras ou antigas.
  - Conformidade: ajuda a seguir boas práticas de segurança ou requisitos legais.
  - Revisão de acessos: identificar usuários inativos ou com permissões desnecessárias.

---

### Access Advisor

É uma funcionalidade do IAM (Identity and Access Management) da AWS que mostra quais serviços da AWS um usuário, grupo ou função usou recentemente – e quando foi o último uso.

#### Vantagens

  - Identificar permissões desnecessárias
  - Reduzir o risco de acesso excessivo (princípio do menor privilégio)
  - Limpar ou ajustar políticas de IAM

---

### AWS Organizations

É um serviço da Amazon Web Services que permite gerenciar várias contas da AWS de forma centralizada, como se fossem parte de uma "empresa" ou "organização" única.

#### Para que ele serve

  - Separar ambientes
    > Ex: produção, desenvolvimento e testes em contas diferentes.

  - Delegar responsabilidades
    > Cada time pode ter sua própria conta.

  - Melhor governança
    > Aplicar regras e limites em toda a organização.

  - Unificar pagamento
    > Você recebe uma única fatura com o custo de todas as contas.

#### Vantagens

  - Governança centralizada
  - Segurança e conformidade padronizadas
  - Faturamento simplificado
  - Isolamento entre ambientes
  - Facilidade para escalar e criar novas contas

---

### CloudShell 

É um terminal online fornecido pelo provedor de nuvem, que já vem configurado com as ferramentas necessárias para você usar e gerenciar seus serviços em nuvem diretamente do navegador.

#### Vantagens

  - Ambiente pré-configurado com ferramentas como o CLI da nuvem, Python, Git etc.
  - Sem precisar instalar nada no seu computador.
  - Armazena arquivos temporários ou persistentes (dependendo do provedor).
  - Ideal para execuções rápidas de comandos e testes.

---

### CLI (Command Line Interface)

É a ferramenta de linha de comando que você instala no seu computador para interagir com um serviço AWS.

#### Vantagens

  - Permite executar comandos diretamente no seu terminal local.
  - Você precisa instalar e configurar (ex: com credenciais).
  - Útil para automatizar tarefas via scripts.
  - Exige autenticação e configuração local (ex: aws configure).

---

### AWS Access

Refere-se às credenciais e permissões que permitem que alguém (ou algum sistema) acesse recursos da AWS.

#### Vantagens

  - Chave de acesso (Access Key ID + Secret Access Key)
    > Usada por sistemas, scripts ou SDKs para autenticar chamadas à AWS.
  - Usuários do IAM (Identity and Access Management)
    > Pessoas ou serviços com permissões definidas (por exemplo, "pode acessar apenas o S3").
  - Políticas de permissão (IAM Policies)
    > Regras que definem o que um usuário ou sistema pode ou não fazer (ex: só pode ler arquivos do S3, não deletar).
  - MFA (Autenticação multifator)
    > Para maior segurança nos acessos via console.

---

### AWS SDK (Software Development Kit)

É um conjunto de bibliotecas que você usa em linguagens de programação (como JavaScript, Python, Java, etc.) para interagir com os serviços da AWS diretamente no seu código.

#### Vantagens

  - Criar uma instância EC2 com código
  - Fazer upload de arquivos para o S3
  - Ler mensagens do SQS
  - Integrar com Lambda, DynamoDB e outros serviços programaticamente

---

### AWS Wavelength

É um serviço da Amazon que leva os recursos da AWS para mais perto dos usuários finais, diretamente nas redes 5G de operadoras de telecomunicação.

#### Por que isso importa

Alguns aplicativos precisam de respostas muito rápidas. O Wavelength ajuda nisso ao colocar servidores AWS dentro das redes 5G, perto dos dispositivos dos usuários.

  - Jogos online em tempo real
  - Carros autônomos
  - Realidade aumentada (AR) e virtual (VR)
  - Monitoramento industrial com sensores

#### Para que serve

  - Você usa instâncias EC2, EBS, VPC etc. como em qualquer região AWS.
  - Mas os recursos rodam em zonas Wavelength, que estão fisicamente dentro das instalações das operadoras 5G.
  - A conexão é super rápida porque não precisa ir até uma região AWS "central" (como São Paulo ou Virgínia).

#### Vantagens

  - Baixa latência (ideal para aplicações críticas)
  - Integração total com AWS padrão
  - Uso otimizado de 5G
  - Mais performance para edge computing

---

### AWS Outposts

É um serviço da Amazon que leva a infraestrutura da AWS para dentro do seu data center ou ambiente local — ou seja, é a AWS rodando fisicamente na sua empresa.

#### Para que serve

  - Baixa latência: quando os sistemas precisam responder em milissegundos (por exemplo, produção industrial ou hospitais).
  - Requisitos legais ou de compliance: quando a empresa não pode armazenar dados fora do país ou precisa de controle físico total.
  - Ambientes sem conexão confiável com a nuvem pública.

#### Vantagens

  - Latência ultra baixa
  - Controle físico
  - Mesmas APIs AWS
  - Híbrido verdadeiro

---

### Shared Responsibility Model

O Shared Responsibility Model (Modelo de Responsabilidade Compartilhada) da AWS define quem é responsável pelo quê em relação à segurança e conformidade na nuvem: a AWS cuida de parte da segurança, e você (cliente) cuida da outra parte.

#### Para que serve

  - Evita falhas de segurança
  - Ajuda a entender quem cuida do quê
  - Esclarece responsabilidades para auditorias e compliance

#### Divisão de responsabilidades

|       Categoria       | Responsabilidade da AWS | Sua responsabilidade (cliente) |
|-----------------------|:------:|:------:|
| Infraestrutura física | Sim | Não |
| Hardware | Sim | Não |
| Serviços gerenciados | Sim | Sim |
| Sistema operacional | Não | Sim |
| Gerenciamento de identidade IAM | Não | Sim |
| Criptografia de dados | AWS fornece ferramentas | Você decide se/como usar |
| Configuração da rede | Não | Sim |
| Aplicações e dados | Não | Sim |

---

### CloudWatch

É o serviço de monitoramento e observabilidade da AWS

#### Para que serve

  - Coleta métricas em tempo real de praticamente todos os serviços AWS (CPU, memória, requisições, latência, etc.) e de aplicações próprias via API/Agent.
  - Armazena logs (CloudWatch Logs) e permite filtrar, buscar e criar insights em tempo quase real.
  - Gera alarmes: define limites (thresholds) ou expressões; quando violados, dispara SNS, Auto Scaling, Lambda, e‑mail, etc.
  - Cria dashboards interativos para visualizar métricas e logs num só painel.
  - Rastreia eventos (CloudWatch Events/EventBridge) para reagir a alterações na infraestrutura ― por ex., iniciar um workflow quando uma instância muda de estado.

#### Vantagens

  - Detectar problemas cedo (picos de CPU, erros 5xx).
  - Automatizar respostas (scale‑out quando fila crescer).
  - Acompanhar custo e performance em múltiplas contas/regiões.
  - Centralizar logs sem precisar gerir servidores de ELK ou Grafana.

---

### EC2 (Elastic Compute Cloud) 

É um serviço da AWS que permite criar e usar servidores virtuais na nuvem, chamados de instâncias EC2.

EC2 é como alugar um computador na nuvem, com o sistema operacional e configurações que você quiser, e só pagar pelo tempo de uso.

#### Para que serve

  - Hospedar aplicações web (como sites, APIs, backends)
  - Executar scripts, bots, jobs e tarefas de processamento
  - Rodar bancos de dados, sistemas legados, VPNs, etc.
  - Simular ambientes de produção/teste com rapidez

#### O que você escolhe ao criar uma instância EC2

  - Tipo de máquina (CPU, memória, rede) → ex: t2.micro, m5.large
  - Sistema operacional → Linux, Windows, etc.
  - Armazenamento (EBS)
  - Segurança (grupo de segurança, VPC, chaves SSH)
  - Região e zona de disponibilidade

#### Vantagens

  - Flexibilidade
    > Escolha SO, tamanho, configurações
  - Pague pelo uso
    > Por hora, segundo, ou uso reservado/spot
  - Escalável
    > Pode aumentar/diminuir conforme a demanda
  - Seguro
    > Com IAM, grupos de segurança, criptografia
  - Alta disponibilidade
    > Pode rodar em várias regiões e zonas

#### Tipos de instância EC2

  - Otimizadas para computação
  - Otimizadas para memória
  - Computação acelerada
  - Otimizadas para armazenamento
  - Otimizadas para HPC

[documentação completa da aws](https://aws.amazon.com/pt/ec2/instance-types/).

#### Valores EC2 (Modelos de aquisição)

| Modelo de aquisição | Como funciona | Quando faz sentido |
|-----------------------|:------:|:------:|
| Sob demanda (On‑Demand) | Paga por hora ou segundo enquanto a instância está ligada. Sem compromisso de longo prazo. | Workloads variáveis, testes, picos imprevisíveis, primeiro deploy antes de medir uso. |
| Instâncias Reservadas (Reserved Instances – RI) | Você firma um compromisso de 1 ou 3 anos para usar um tipo de instância numa região ou zona. Garante desconto de até ~72 % sobre sob demanda | Workloads estáveis 24×7 (bancos, back‑ends de produção). Planejamento de custos previsível. |
| Savings Plans | Compromisso de gasto hora médio (ex.: US$ 10/h) por 1 ou 3 anos. Aplica desconto automático a EC2, Fargate e Lambda, sem travar num tipo ou região específica (Compute SP). Há também o EC2 Instance SP (ligado à família/região, desconto maior). | mbientes elásticos que rodam continuamente, mas querem liberdade para mudar tipos ou migrar para Fargate/Lambda. |
| Spot Instances | Você usa capacidade ociosa do data center com desconto de 70–90 %, mas a AWS pode encerrar a instância com 2 min de aviso se precisar da capacidade. | Tarefas tolerantes a interrupção: big data, renderização, CI/CD distribuído, containers stateless, machine learning batch. Pode ser combinado com Auto Scaling. |

---

### EC2 Instance Connect

É uma forma fácil e segura de acessar sua instância EC2 Linux via navegador, sem precisar de um cliente SSH instalado.

#### Para que serve

  - A AWS cria automaticamente uma chave temporária pública
  - Essa chave é injetada na instância EC2 na hora do acesso
  - A conexão SSH acontece por websocket seguro, direto do console
  - Só funciona com instâncias EC2 baseadas em Amazon Linux, Ubuntu, etc., e que tenham:
    - Acesso via porta 22 permitido no Security Group
    - EC2 Instance Connect habilitado no sistema

#### Vantagens

  - Sem SSH local
  - Acesso via navegador
  - Mais seguro
  - Fácil para dev/teste

---

### Security Group

É como um firewall virtual que controla o tráfego de entrada e saída de instâncias EC2 (e outros recursos compatíveis).

É um conjunto de regras que definem quem pode acessar sua instância EC2 e para onde ela pode se conectar.

#### Para que serve

  - Associado a instâncias EC2, Load Balancers, RDS, entre outros
  - Funciona no nível da instância, não da rede inteira
  - Pode ser reutilizado em várias instâncias
  - As regras são stateful: se você permite entrada, a resposta sai automaticamente

#### Vantagens

  - Segurança clara
    > Regras explícitas, controle fino
  - Isolamento
    > Cada instância pode ter seu próprio grupo
  - Dinâmico
    > Alterações nas regras são aplicadas em tempo real
  - Reutilizável
    > Pode associar o mesmo grupo a várias instâncias

---

### AMI (Amazon Machine Image)

É uma imagem pré-configurada que contém tudo o que sua instância EC2 precisa para ser criada e executada.

#### O que uma AMI contém

  - Sistema operacional
    > Ex: Amazon Linux, Ubuntu, Windows Server
  - Volume(s) EBS
    > Disco(s) com arquivos, banco, configs, etc.
  - Permissões
    > Quem pode usar a AMI (privada, pública, etc.)
  - Configurações de boot
    > Scripts de inicialização, informações de kernel

#### Vantagens

  - Rápido de lançar
    > Cria EC2 em minutos com tudo pré-configurado
  - Reutilizável
    > Pode usar a mesma AMI para várias instâncias
  - Seguro
    > Cria uma cópia "congelada" do sistema
  - Compartilhável
    > Pode compartilhar com outras contas/regiões

---

### Amazon EBS (Elastic Block Store)

É um serviço da AWS que fornece armazenamento em blocos durável e de alta performance para ser usado com instâncias EC2.

O EBS funciona como um HD ou SSD virtual, que você conecta a uma instância EC2 para guardar arquivos, bancos de dados, logs, sistemas operacionais, etc.

#### Para que serve

  - Armazenamento em blocos → como um disco rígido (ideal para leitura/gravação rápida)
  - Persistente → seus dados não somem quando a EC2 é parada ou reiniciada
  - Conectado a 1 instância por vez (por padrão)
  - Pode ser aumentado, copiado ou criado a partir de snapshots

#### Vantagens

  - Guardar arquivos da aplicação
  - Armazenar banco de dados (como MySQL, PostgreSQL, MongoDB)
  - Disco principal da instância EC2 (com o sistema operacional)
  - Discos separados para logs, cache ou dados temporários

---

### Snapshots

São cópias seguras(backups) de volumes, feitas ponto a ponto. É uma imagem de um volume tirado em um determinado momento, que pode ser armazenado, restaurado ou usado para criar um novo volume.

#### Vantagens

  - Backup
  - Recuperação de desastres
  - Clonagem de ambientes

---

### Snapshot X AMI

| Descrição | Snapshot | AMI |
|:------:|:------:|:------:|
| O que é | Cópia de um volume EBS | Imagem completa de uma EC2 |
| Usa EBS? | Sim | Sim (contém 1 ou mais snapshots EBS) |
| Cria EC2? | Não diretamente | Sim, é usada para lançar novas EC2 |

---

### Amazon EFS (Elastic File System)

É um serviço de armazenamento de arquivos na nuvem da AWS que pode ser acessado por várias instâncias EC2 ao mesmo tempo, como se fosse um sistema de arquivos compartilhado em rede.

O EFS funciona como um disco em rede (NFS), onde várias máquinas podem ler e gravar arquivos ao mesmo tempo, de forma elástica, segura e escalável.

Criado para Linux.

#### Para que serve

  - Arquivos
    > Ideal para guardar arquivos compartilhados, não blocos (como o EBS)
  - Multi-instância
    > Pode ser acessado por várias EC2 ao mesmo tempo
  - Elástico
    > Escala automaticamente (você não precisa definir tamanho)
  - Alta disponibilidade
    > Replicado automaticamente em várias zonas de disponibilidade
  - Seguro
    > Suporta criptografia, controle de acesso (IAM, NFS), VPC, etc.
  - Cobrança por uso
    > Você paga somente pelo espaço usado (GB)


#### Vantagens

  - Fácil de usar com EC2 Linux
  - Totalmente gerenciado pela AWS
  - Alta performance e disponibilidade
  - Paga só pelo que usar
  - Permite backup automático

---

### Diferença entre EFS, EBS e S3

| Serviço | Tipo | Uso principal | Pode ser compartilhado? |
|:------:|:------:|:------:|:------:|
| EBS | Bloco (disco) | Disco para EC2 (como HD/SSD) | Não (só 1 EC2 por vez) |
| EFS | Arquivo (NFS) | Sistema de arquivos em rede para EC2 | Sim |
| S3 | Objeto | Armazenamento de arquivos e dados estáticos | Sim (via API) |

---

### Amazon FSx (File System X)

É um serviço da AWS que oferece sistemas de arquivos totalmente gerenciados, otimizados para diferentes necessidades — como Windows, Lustre (para alto desempenho), NetApp ONTAP, e OpenZFS.

O Amazon FSx permite usar sistemas de arquivos poderosos e compatíveis com protocolos específicos (SMB, NFS, Lustre, etc.), sem precisar configurar ou manter servidores de arquivos.

Criado para Windows.

#### Para que serve

  - Criar compartilhamentos de arquivos para aplicações corporativas
  - Acelerar o processamento de dados com arquivos em paralelo (Lustre)
  - Substituir servidores de arquivos físicos/virtuais
  - Armazenar dados com alto desempenho e baixa latência

#### Vantagens

  - Gerenciado pela AWS
    > Sem necessidade de instalar ou manter servidores
  - Seguro
    > Suporte a VPC, IAM, KMS, backups e criptografia
  - Alta performance
    > Projetado para uso intenso de dados
  - Integração com outros serviços
    > Ex: S3, EC2, AD, etc.
  - Compatível com protocolos
    > NFS, SMB, ZFS, etc. dependendo do tipo escolhido

---

### AWS Auto Scaling

É um serviço que ajusta automaticamente a quantidade de recursos computacionais (como instâncias EC2) com base na demanda de uso, para garantir desempenho, economia e disponibilidade.

O Auto Scaling aumenta ou reduz automaticamente a capacidade do seu sistema conforme necessário — sem você precisar fazer isso manualmente.

#### O que ele pode escalar

  - EC2 (servidores virtuais)
    > Aumentar instâncias quando o tráfego sobe
  - ECS (containers)
    > Subir mais tarefas quando há mais carga
  - DynamoDB (banco NoSQL)
    > Ajustar capacidade de leitura/gravação
  - Aurora (banco relacional)
    > Adicionar réplicas para lidar com consultas

#### Vantagens

  - Resposta automática
    > Reage a picos de tráfego em tempo real
  - Economia de custos
    > Reduz recursos quando a demanda cai
  - Melhora desempenho
    > Garante que o sistema esteja sempre com capacidade ideal
  - Aumenta a disponibilidade
    > Evita falhas ao substituir instâncias com problemas

---

### ELB (Elastic Load Balancing)

É um serviço da AWS que distribui automaticamente o tráfego de rede entre vários recursos, como instâncias EC2, garantindo alta disponibilidade, escalabilidade e tolerância a falhas.

O ELB funciona como um "porteiro inteligente" que recebe as requisições dos usuários e as envia para os servidores certos, equilibrando a carga entre eles.

#### Para que serve

  - Evitar sobrecarga em uma única instância EC2
  - Reduzir tempo de resposta
  - Manter o sistema disponível mesmo se um servidor falhar
  - Trabalhar junto com Auto Scaling para escalar aplicações

#### Vantagens

  - Balanceamento automático da carga
  - Integração com Auto Scaling e VPC
  - Alta disponibilidade e tolerância a falhas
  - Suporte a SSL/TLS (HTTPS)
  - Monitoramento com CloudWatch

#### Tipos de Load Balancer na AWS

| Tipo | Indicado para | Protocolos suportados |
|:------:|:------:|:------:|
| Application Load Balancer (ALB) | Aplicações web (HTTP/HTTPS), APIs REST | HTTP, HTTPS (nível 7 - camada de aplicação) |
| Network Load Balancer (NLB) | Alto desempenho e baixa latência | TCP, TLS, UDP (nível 4 - transporte) |
| Gateway Load Balancer (GWLB) | Integração com appliances de segurança | IP (camada 3 - rede) |
| Classic Load Balancer (CLB) | Modelo mais antigo, compatível com EC2 | HTTP, HTTPS, TCP (camada mista) |

---

### Amazon S3 (Simple Storage Service)

É um serviço da AWS que permite armazenar e recuperar qualquer quantidade de dados, de forma escalável, segura e altamente disponível, usando a web.

O S3 é como um disco virtual na nuvem, ideal para guardar arquivos como imagens, vídeos, documentos, backups, logs, e muito mais.

#### Para que serve

  - Os dados são armazenados em "buckets" (como pastas principais)
  - Cada objeto (arquivo) tem uma chave única e pode ter metadados
  - Você acessa os arquivos via URL, API, SDK ou AWS CLI

#### Vantagens

  - Escalabilidade
    > Armazena de poucos KB a petabytes, sem limite de crescimento
  - Pagamento por uso
    > Você paga só pelo que usar (armazenamento, requisições, tráfego)
  - Segurança integrada
    > Suporte a criptografia, controle de acesso com IAM e políticas
  - Alta durabilidade
    > 99.999999999% (11 noves) de durabilidade dos objetos
  - Integração ampla
    > Funciona com outros serviços da AWS (EC2, Lambda, CloudFront etc.)

#### Casos de uso comuns

  - Armazenar imagens e vídeos de um site
  - Fazer backups automáticos de servidores ou bancos de dados
  - Guardar logs e dados analíticos
  - Hospedar um site estático
  - Distribuir arquivos com alta performance (via CloudFront)

---

### Bucket S3

É como uma pasta raiz onde você armazena objetos (arquivos e dados) na nuvem.

Um bucket é o "conteiner" principal do S3, onde você organiza e gerencia os seus arquivos. Todo objeto dentro do S3 precisa estar em um bucket.

#### Características de um bucket

  - Nome único global
    > O nome do bucket deve ser único no mundo inteiro da AWS
  - Contém objetos
    > Armazena arquivos como imagens, vídeos, PDFs, backups, etc.
  - Organização
    > Você pode organizar objetos com prefixos (como pastas simuladas)
  - URL de acesso
    > Cada objeto pode ter um link como: https://bucket-nome.s3.amazonaws.com/arquivo.jpg
  - Segurança
    > Suporte a políticas de acesso, criptografia, logs e versionamento
  - Região
    > Cada bucket pertence a uma região específica da AWS

#### O que dá pra configurar em um bucket

  - Controle de acesso (ACLs, políticas, IAM)
  - Versionamento de arquivos
  - Logs de acesso
  - Ciclo de vida dos objetos (por ex: excluir após 30 dias)
  - Criptografia automática
  - Replicação entre regiões

---

### Classes de armazenamento do Amazon S3

As classes de armazenamento do Amazon S3 são diferentes níveis de custo, performance e durabilidade, criados para otimizar o uso e reduzir custos conforme o tipo de dado e a frequência de acesso.

#### Principais classes do S3

| Classe | Quando usar | Frequência de acesso | Características principais |
|:------:|:------:|:------:|:------:|
| S3 Standard | Para dados acessados com frequência | Alta | Alta durabilidade, baixa latência, sem requisitos mínimos |
| S3 Intelligent-Tiering | Quando o padrão de acesso varia e você quer otimizar custos | Variável | Move automaticamente dados entre níveis (frequente/raro) |
| S3 Standard-IA | Para dados raramente acessados, mas que precisam estar disponíveis rapidamente | Baixa | Mais barato que o Standard, com cobrança por recuperação |
| S3 One Zone-IA | Como o IA, mas armazenado em uma única zona de disponibilidade | Baixa | Custo menor, menos tolerância a falhas |
| S3 Glacier Instant Retrieval | Arquivos raros, mas que você precisa acessar rapidamente | Muito baixa | Acesso quase instantâneo, mas bem mais barato |
| S3 Glacier Flexible Retrieval | Arquivos de arquivamento, com acesso em minutos ou horas | Muito baixa | Mais barato ainda, recuperação em 1 minuto a 12 horas |
| S3 Glacier Deep Archive | Arquivos quase nunca acessados (como backups antigos) | Quase nenhuma | Custo mais baixo possível, acesso em 12–48 horas |

#### Vantagens de escolher a classe certa

  - Economia significativa
  - Otimização de performance
  - Gerenciamento automático com Intelligent-Tiering

---

### Versionamento no Amazon S3

É um recurso que permite manter várias versões de um mesmo objeto (arquivo) dentro de um bucket. Ele ajuda a proteger dados contra exclusões acidentais e alterações indesejadas.

Com o versionamento ativado, toda vez que você substituir ou excluir um arquivo, o S3 guarda a versão anterior, e você pode recuperá-la depois.

#### Para que serve

  - Cada vez que você faz upload de um objeto com o mesmo nome, o S3 cria uma nova versão, e a anterior continua guardada.
  - Quando você "deleta" um arquivo, o S3 marca com um "delete marker", mas não apaga a versão antiga (a menos que você apague explicitamente).

#### Vantagens

  - Proteção contra perdas
    > Você pode recuperar arquivos excluídos ou sobrescritos
  - Histórico de alterações
    > Guarda todas as versões de um mesmo objeto
  - Gerenciamento flexível
    > Pode configurar políticas para expirar versões antigas

#### Pontos de atenção

  - Custo: versões antigas ocupam espaço e geram cobrança
  - Recomendado configurar regras de ciclo de vida para apagar versões antigas automaticamente
  - Funciona apenas em buckets com versionamento ativado (não vem por padrão)

---

### Criptografia no Amazon S3

A criptografia no Amazon S3 protege seus dados em repouso (armazenados no bucket) usando algoritmos de criptografia seguros, para garantir que somente pessoas autorizadas consigam acessá-los, mesmo que alguém tenha acesso físico ao armazenamento.

Com a criptografia habilitada no S3, seus arquivos são automaticamente codificados ao serem salvos e decodificados apenas no momento da leitura, com controle total sobre as chaves.

#### Tipos de criptografia em repouso no S3

| Tipo | Nome | Gerenciamento de chaves |
|:------:|:------:|:------:|
| SSE-S3 | Server-Side Encryption com chaves da AWS | A AWS gerencia tudo para você |
| SSE-KMS | Server-Side Encryption com AWS KMS | Você usa o AWS Key Management Service para controlar as chaves |
| SSE-C | Server-Side Encryption com chave do cliente | Você fornece a chave em cada requisição |
| Criptografia do lado do cliente | Client-Side Encryption | Você criptografa os dados antes de enviá-los ao S3 |

#### Vantagens

  - Segurança forte com algoritmos como AES-256
  - Conformidade com normas (LGPD, ISO, HIPAA, etc.)
  - Visibilidade com logs no CloudTrail (especialmente com SSE-KMS)
  - Pode ser aplicada automaticamente em buckets inteiros

---

### AWS Storage Gateway

É um serviço que conecta seu ambiente local (on-premises) à nuvem da AWS, permitindo que você use o armazenamento da AWS como se fosse um disco local. Ele serve como uma ponte entre data centers e o armazenamento em nuvem.

O Storage Gateway integra seus servidores ou aplicações locais ao Amazon S3, Glacier ou EBS, permitindo backup, arquivamento ou extensão de armazenamento sem sair do ambiente local.

#### Vantagens

  - Usa a AWS como extensão de armazenamento local
  - Reduz custos com infraestrutura física
  - Integra-se com sistemas existentes (sem mudar aplicações)
  - Backup e arquivamento automáticos na nuvem
  - Suporte a criptografia e logs de auditoria

#### Modos de operação (tipos de gateway)

| Tipo de Gateway | Para que serve | Armazenamento final na AWS |
|:------:|:------:|:------:|
| File Gateway | Compartilhamento de arquivos via NFS/SMB | Armazena arquivos no S3 |
| Volume Gateway | Monta discos locais em servidores, mas replica na nuvem | Snapshots armazenados no EBS/S3 |
| Tape Gateway | Substitui fitas físicas por fitas virtuais (VTL) | Arquiva no S3 Glacier |

#### File Gateway

Permite que você armazene e acesse arquivos na nuvem usando protocolos padrão (NFS ou SMB), como se fossem arquivos locais.

  - Interface: Arquivos
  - Protocolos: NFS (Linux) e SMB (Windows)
  - Armazena os arquivos no Amazon S3
  - Usado para:
    - Compartilhar arquivos entre equipes
    - Backup de arquivos
    - Análise de dados com acesso direto do S3

#### Volume Gateway

Apresenta discos (volumes) locais para seus servidores, mas armazena os dados de forma segura e redundante na nuvem.

| Modo | Funciona assim | Uso típico |
|:------:|:------:|:------:|
| Cached volumes | Os dados recentes ficam em cache local, e o restante na AWS | Reduz espaço físico, melhora acesso |
| Stored volumes | Todos os dados ficam localmente, e são espelhados na AWS | Continuidade de negócios e backup |

  - Armazena snapshots no Amazon S3 / EBS
  - Usado para:
    - Backup de bancos de dados
    - Recuperação de desastres

#### Tape Gateway

Emula uma biblioteca de fitas magnéticas (VTL) compatível com seu software de backup, mas usa a nuvem.

  - Substitui fitas físicas por fitas virtuais
  - Armazena em Amazon S3 e arquiva em Amazon S3 Glacier ou Deep Archive
  - Usado para:
    - Eliminar manutenção de hardware de fita
    - Arquivamento de longo prazo

#### Comparação rápida

| Tipo | Interface | Usa S3? | Usa EBS? | Usa Glacier? | Protocolo local |
|:------:|:------:|:------:|:------:|:------:|:------:|
| File Gateway | Arquivos | sim | não | não | NFS / SMB |
| Volume Gateway | Blocos | sim | sim | não (via snapshot) | iSCSI |
| Tape Gateway | Fita VTL | sim | não | sim | VTL (via software de backup) |

---

### Amazon S3 Transfer Acceleration

É um recurso do Amazon S3 que aumenta a velocidade de upload e download de arquivos (objetos) usando a rede global da Amazon CloudFront.

---

### AWS Snow Family

É um conjunto de dispositivos físicos fornecidos pela Amazon para transferência de dados em larga escala entre seu ambiente local (on-premises) e a nuvem da AWS — especialmente útil quando a rede é lenta, cara ou inexistente.

A Snow Family ajuda a mover grandes volumes de dados de forma segura, eficiente e até em áreas remotas, usando dispositivos físicos robustos enviados pela própria AWS.

#### Membros da família Snow

| Serviço | Capacidade | Uso principal | Observações |
|:------:|:------:|:------:|:------:|
| AWS Snowcone | Até 8 TB | Pequenos volumes ou ambientes remotos | Leve, portátil e resistente (cabe numa mochila) |
| AWS Snowball | Até 80 TB (por unidade) | Migração em massa, backup, arquivamento | Suporta clusters e criptografia |
| AWS Snowmobile | Até 100 PB | Transferência em escala exabyte (extrema) | Caminhão com container de dados! |

#### Como funciona

  - Você solicita o dispositivo pela AWS
  - Ele é enviado fisicamente até seu local
  - Você transfere os dados para o dispositivo
  - Ele é devolvido para a AWS, que importa os dados no seu bucket S3 ou serviço especificado

#### Vantagens

  - Migração de data center para a nuvem
  - Coleta de dados em áreas sem internet (militares, mineração, navios)
  - Transferência segura e criptografada de dados sensíveis
  - Processamento local com Snowcone ou Snowball Edge com EC2 e Lambda embutidos
  - Dispositivo é bloqueado e se autodestrói logicamente após uso incorreto
  - Suporte a chaves gerenciadas pelo AWS KMS

---

### Bancos de Dados

A AWS oferece diversos tipos de bancos de dados, otimizados para diferentes casos de uso, modelos de dados e desempenho. Eles são agrupados em categorias baseadas no tipo de estrutura e finalidade.

#### Bancos de Dados Relacionais (SQL)

Armazenam dados em tabelas com colunas e linhas. Usam linguagens como SQL.

| Serviço | Descrição | Compatível com |
|:------:|:------:|:------:|
| Amazon RDS | Banco relacional gerenciado | MySQL, PostgreSQL, Oracle, SQL Server, MariaDB |
| Amazon Aurora | Versão otimizada da AWS com alta performance | Compatível com MySQL e PostgreSQL |

#### Bancos de Dados Não Relacionais (NoSQL)

Armazenam dados em formatos flexíveis (chave-valor, documentos, grafos, etc.).

| Serviço | Tipo | Descrição |
|:------:|:------:|:------:|
| Amazon DynamoDB | Chave-valor / Documento | Escalável, baixa latência, sem servidor |
| Amazon ElastiCache | Chave-valor em memória | Cache de alta velocidade (Redis ou Memcached) Mais caro |

#### Bancos de Dados em Grafos

Usados para representar e consultar relacionamentos complexos (redes sociais, recomendações).

| Serviço | Descrição |
|:------:|:------:|
| Amazon Neptune | Banco de dados em grafo altamente conectado |

#### Bancos de Dados de Documentos

Armazenam dados como documentos (geralmente em JSON).

| Serviço | Descrição |
|:------:|:------:|
| Amazon DocumentDB | Compatível com MongoDB (armazenamento por documento) |

#### Bancos de Dados de Tempo-Série

Otimizados para dados cronológicos (ex: métricas, IoT).

| Serviço | Descrição |
|:------:|:------:|
| Amazon Timestream | Armazena e consulta séries temporais em escala |

#### Quando usar cada tipo?

| Serviço | Descrição |
|:------:|:------:|
| Relacional | Sistemas ERP, bancos, e-commerces tradicionais | 
| NoSQL | Aplicações web/mobile, cargas imprevisíveis | 
| Grafo | Recomendação, redes sociais, dependências | 
| Documento | Catálogos, perfis de usuários, apps flexíveis | 

---

### Amazon RDS 

O Amazon RDS (Relational Database Service) é um serviço da AWS que permite criar, operar e escalar bancos de dados relacionais de forma automática e gerenciada, sem se preocupar com tarefas como instalação, backups, atualizações ou alta disponibilidade.

O RDS é um banco de dados relacional na nuvem, pronto para uso, com manutenção automatizada feita pela AWS.

#### Vantagens

  - Backups automáticos
  - Escalabilidade vertical (CPU/RAM) e horizontal (replicas de leitura)
  - Atualizações e patches automatizados
  - Segurança com criptografia e controle via IAM e VPC
  - Alta disponibilidade com Multi-AZ
  - Monitoramento com Amazon CloudWatch

#### Bancos compatíveis no RDS

| Banco de dados | Suporte via RDS |
|:------:|:------:|
| MySQL | sim |
| PostgreSQL | sim |
| MariaDB | sim |
| Oracle | sim |
| Microsoft SQL Server | sim |
| Amazon Aurora | sim (compatível com MySQL/PostgreSQL) |

---

### Amazon Aurora

O Amazon Aurora é um banco de dados relacional gerenciado pela AWS, compatível com MySQL e PostgreSQL, que oferece alta performance, escalabilidade e disponibilidade, sendo até 5 vezes mais rápido que o MySQL padrão e 3 vezes mais rápido que o PostgreSQL.

O Aurora é um banco de dados moderno da AWS, totalmente gerenciado, que combina a facilidade do RDS com alta performance, resiliência e custos menores que bancos comerciais como Oracle ou SQL Server.

#### Vantagens

  - Alta performance (até 5x mais rápido que MySQL no RDS)
  - Alta disponibilidade (Multi-AZ e replicação automática em até 6 cópias)
  - Escalabilidade automática (Aurora Serverless v2)
  - Criptografia em repouso e em trânsito
  - Backup contínuo para o S3
  - Failover automático em segundos
  - Compatível com MySQL e PostgreSQL (mesmo driver e comandos)

#### Modos de uso

| Modo | Descrição |
|:------:|:------:|
| Aurora Provisioned | Capacidade fixa, ideal para cargas constantes |
| Aurora Serverless | Capacidade automática sob demanda (paga pelo uso) |

#### Diferenças entre Aurora e RDS

| Recurso | RDS MySQL/PostgreSQL | Aurora MySQL/PostgreSQL |
|:------:|:------:|:------:|
| Performance | Padrão | Muito maior (até 5x/3x) |
| Armazenamento | Manual/definido | Escala automaticamente (até 128 TB) |
| Replica de leitura | 5 | Até 15 |
| Tempo de failover | 1-2 minutos | Menos de 30 segundos |
| Custo | Médio | Um pouco maior, mas mais eficiente |

---

### Amazon ElastiCache

É um serviço da AWS que permite criar e gerenciar caches de dados em memória, de forma totalmente gerenciada, usando os mecanismos Redis ou Memcached.

O ElastiCache acelera o acesso aos dados, armazenando informações temporariamente em memória RAM, o que reduz a carga sobre bancos de dados e melhora o desempenho de aplicações.

#### Vantagens

  - Alta performance (respostas em microssegundos)
  - Cache distribuído para aplicações web, APIs, bancos de dados
  - Reduz a latência e a carga no banco de dados
  - Gerenciado: AWS cuida de instalação, patch, monitoramento, failover
  - Compatível com Redis e Memcached

---

### Amazon DynamoDB

É um banco de dados NoSQL totalmente gerenciado pela AWS, projetado para oferecer alta performance, baixa latência e escalabilidade automática, mesmo com milhões de requisições por segundo.

O DynamoDB é ideal para aplicações modernas que precisam de respostas rápidas, grande volume de dados e escalabilidade sob demanda, sem a complexidade de gerenciar infraestrutura.

#### Vantagens

  - Latência de milissegundos
  - Escalabilidade automática (on-demand ou provisionado)
  - Armazena dados como pares chave-valor ou documentos JSON
  - Totalmente gerenciado: sem servidores, sem patch, sem backup manual
  - Alta disponibilidade e replicação automática
  - Suporte a IAM, criptografia, e auditoria com CloudTrail

---

### Amazon Neptune

É um serviço de banco de dados de grafos totalmente gerenciado da AWS, projetado para armazenar e consultar relacionamentos complexos entre dados, como redes sociais, sistemas de recomendação, e detecção de fraudes.

O Neptune é um banco de dados orientado a grafos, ideal quando o foco não é só os dados em si, mas como eles se conectam.

#### Vantagens

  - Suporta dois principais modelos de grafos:
    - Property Graph, com a linguagem Gremlin
    - RDF (Resource Description Framework), com a linguagem SPARQL
  - Totalmente gerenciado: backups, replicação, failover
  - Segurança com VPC, IAM, KMS e integração com CloudTrail
  - Baixa latência para consultas complexas
  - Ideal para dados com muitos relacionamentos

---

### AWS Glue

É um serviço de integração e preparação de dados totalmente gerenciado da AWS. Ele facilita a extração, transformação e carga (ETL) de dados — ou seja, ajuda a coletar dados de diferentes fontes, transformá-los e enviá-los para outro lugar, como um data lake ou banco de dados.

O AWS Glue é como um "encanamento inteligente" para organizar dados brutos, transformá-los, e colocá-los onde podem ser analisados.

#### Vantagens

  - ETL sem servidor: não precisa configurar servidores, ele escala automaticamente
  - Catálogo de dados: registra metadados (nomes, formatos, tipos de dados) para facilitar buscas e análises
  - Transformações em Python ou Scala
  - Glue Studio: interface visual para montar fluxos ETL sem código
  - Glue DataBrew: ferramenta no-code para preparar dados com interface gráfica
  - Suporte a Job Triggers, Workflows e partições

#### Casos de uso

| Caso | O que o Glue faz |
|:------:|:------:|
| Preparar dados para análise | Limpeza, transformação, formatação | 
| Integrar dados de várias fontes | Junta dados de S3, RDS, Redshift, etc. | 
| Criar data lakes | Organiza e cataloga os dados no S3 | 
| Atualizar catálogos de dados | Descobre e registra automaticamente os esquemas | 
| Processamento de logs, IoT | Transforma e organiza grandes volumes de dados | 

---

### Amazon Redshift

É um serviço de data warehouse totalmente gerenciado da AWS. Ele foi projetado para armazenar e analisar grandes volumes de dados com alta performance, usando consultas SQL.

O Redshift é ideal para análise de dados em larga escala, como relatórios, dashboards e BI (Business Intelligence), funcionando como um banco de dados analítico.

#### Vantagens

  - Alta performance para consultas em terabytes ou petabytes de dados
  - Usa armazenamento colunar e compressão para melhorar velocidade
  - Integrado com ferramentas como Amazon QuickSight, Tableau, Power BI
  - Suporte a consultas paralelas (MPP – processamento massivamente paralelo)
  - Pode se integrar a dados em S3, RDS, Aurora, DynamoDB, etc.
  - Suporte a Redshift Spectrum: consultar dados diretamente no S3 sem carregar
  - Segurança com VPC, IAM, KMS e criptografia

#### Casos de uso

| Caso | Por que usar o Redshift |
|:------:|:------:|
| BI e dashboards executivos | Consultas rápidas para grandes volumes |
| Análise de logs | Agrega milhões de eventos em segundos |
| Relatórios de vendas e KPIs | Permite explorar dados históricos |
| Análise de comportamento de usuários | Permite cruzar dados de diferentes fontes |

---

### VPC (Virtual Private Cloud)

É um serviço da AWS que permite criar uma rede virtual privada, isolada dentro da nuvem da AWS, onde você pode lançar recursos como EC2, RDS, Lambda, com controle total sobre o tráfego e a segurança.

A VPC é como uma rede privada dentro da AWS, onde você define quem pode entrar, sair, e como os serviços se comunicam entre si — como se fosse uma "sala fechada" na nuvem.

#### Vantagens

  - Sub-redes (subnets): segmentam sua rede em partes públicas e privadas
  - Internet Gateway: permite acesso à internet
  - Security Groups e NACLs: controlam o tráfego de entrada e saída
  - Route Tables: definem os caminhos que o tráfego pode seguir
  - VPN ou Direct Connect: conecta sua rede local à VPC
  - Peering e Transit Gateway: conecta várias VPCs

#### Componentes principais da VPC

| Componente | Função |
|:------:|:------:|
| CIDR Block | Faixa de IPs da rede (ex: 10.0.0.0/16) |
| Subnets | Dividem a VPC em zonas públicas ou privadas |
| Internet Gateway | Permite acesso à internet |
| NAT Gateway | Permite que subnets privadas acessem a internet |
| Route Table | Define o roteamento do tráfego |
| Security Groups | Firewall em nível de instância (EC2, RDS, etc) |
| NACLs | Firewall em nível de subnet |

---

### Subnet 

Uma subnet (sub-rede) é uma divisão lógica dentro de uma VPC (Virtual Private Cloud) na AWS. Ela define um bloco de endereços IP que pode ser usado para lançar recursos como instâncias EC2, bancos de dados, etc.

A subnet é como um "quarto" dentro da casa (VPC), onde você coloca recursos da nuvem. Cada quarto pode ter acesso diferente à internet e a outros serviços.

#### Vantagens

  - Cada subnet pertence a uma única zona de disponibilidade (AZ) dentro de uma região
  - Pode ser pública (com acesso à internet) ou privada (sem acesso direto à internet)
  - Recursos são lançados dentro de subnets (ex: EC2, RDS, Lambda com VPC)
  - As subnets são definidas com uma faixa de IPs (CIDR block)

#### Tipos

| Tipo de Subnet | Acesso à Internet? | Exemplo de uso |
|:------:|:------:|:------:|
| Pública | Sim (via Internet Gateway) | Servidores web, load balancers |
| Privada | Não diretamente | Bancos de dados, servidores internos |

---

### Internet Gateway (IGW)

É um componente da AWS que permite que recursos em uma VPC se comuniquem com a internet — tanto para enviar quanto para receber tráfego.

O Internet Gateway é a "porta de entrada e saída" para a internet dentro da sua VPC.

#### Vantagens

  - Permite instâncias EC2 em subnets públicas acessarem a internet (e serem acessadas)
  - Funciona em conjunto com a Route Table para direcionar o tráfego
  - É altamente disponível e gerenciado pela AWS (sem custo adicional por si só)
  - Só pode estar associado a uma VPC por vez

---

### Network ACL (Access Control List)

É uma lista de regras de controle de acesso à rede, usada para permitir ou negar tráfego que entra ou sai de uma subnet dentro de uma VPC.

A Network ACL (NACL) é um firewall em nível de subnet, que define quais pacotes podem passar com base em regras numéricas.

#### Vantagens

  - Atua em nível de subnet, protegendo todos os recursos dentro dela
  - É sem estado (stateless): as regras de entrada e saída são independentes
  - Regras são avaliadas em ordem numérica (da menor para a maior)
  - Pode ter regras para permitir ou negar tráfego
  - É possível associar uma única NACL por subnet, mas uma NACL pode ser usada por várias subnets

---

### VPC Peering

É um recurso da AWS que permite conectar duas VPCs (Virtual Private Clouds), permitindo que os recursos dessas VPCs se comuniquem como se estivessem na mesma rede, sem precisar passar pela internet.

O VPC Peering é como fazer um "cabo direto" entre duas redes privadas dentro da AWS.

#### Vantagens

  - Permite tráfego privado entre instâncias em VPCs diferentes
  - Funciona dentro da mesma região ou entre regiões (inter-region peering)
  - Não há roteamento via internet, VPN ou gateway — é direto
  - As VPCs podem estar em contas diferentes
  - Tráfego é criptografado automaticamente pela infraestrutura da AWS
  - Unidirecional por padrão, mas normalmente configurado como bidirecional

---

### VPC Endpoints

VPC Endpoints são recursos da AWS que permitem que você se conecte privadamente a serviços da AWS (como S3, DynamoDB) sem passar pela internet pública, diretamente de dentro da sua VPC.

Um VPC Endpoint é como um "atalho seguro e privado" entre a sua VPC e serviços da AWS, sem usar internet, VPN ou NAT Gateway.

#### Tipos 

| Tipo | Descrição |
|:------:|:------:|
| Interface Endpoint | Usa uma ENI (Elastic Network Interface) com IPs privados dentro da VPC. Usado para a maioria dos serviços da AWS (ex: SSM, API Gateway, etc). |
| Gateway Endpoint | Usado especificamente para S3 e DynamoDB. Adiciona uma rota na Route Table. Não usa ENI. |

#### Vantagens

  - Mais seguro: o tráfego não sai da rede privada da AWS
  - Mais barato: reduz uso de NAT Gateway ou internet
  - Mais simples: não precisa configurar VPN, proxies ou IP público
  - Melhor performance e latência

---

### VPC Flow Logs

VPC Flow Logs são registros que capturam informações sobre o tráfego de rede que entra e sai das interfaces de rede em sua VPC (Virtual Private Cloud) na AWS.

Os VPC Flow Logs funcionam como "câmeras de segurança" da rede: mostram quem está se comunicando com quem, quando e como dentro da sua VPC.

#### O que eles registram

  - Endereços IP de origem e destino
  - Portas de origem e destino
  - Protocolo (TCP, UDP, etc.)
  - Status da conexão (aceito ou rejeitado)
  - Quantidade de dados enviados/recebidos
  - Tempo de início e fim do fluxo

#### Onde podem ser criados

  - VPC inteira
  - Subnets
  - Interfaces de rede (ENI) individuais

#### Para onde os logs vão

  - Amazon CloudWatch Logs (para monitoramento e alertas)
  - Amazon S3 (para arquivamento e análise posterior)

---

### VPN (Virtual Private Network)

É uma tecnologia que cria uma conexão segura e criptografada entre dois pontos através da internet ou de outra rede pública.

A VPN funciona como um "túnel seguro" que protege os dados enquanto trafegam entre o seu dispositivo ou rede local e outro ambiente, como a AWS ou um servidor remoto.

#### Vantagens

  - Segurança: Criptografa os dados transmitidos
  - Privacidade: Oculta o tráfego da rede pública
  - Acesso remoto seguro: Permite que usuários ou redes se conectem com segurança a uma rede corporativa
  - Conexão site-to-site: Integra redes diferentes (por exemplo, sua rede on-premises com uma VPC da AWS)

#### Tipos de VPN na AWS

| Tipo | Descrição |
|:------:|:------:|
| Site-to-Site VPN | Conecta a sua rede local (on-premises) a uma VPC na AWS |
| Client VPN | Permite que usuários individuais se conectem com segurança à VPC |
| Software VPN | Soluções de terceiros instaladas em instâncias EC2 |

---

### AWS PrivateLink

É um serviço que permite acessar serviços da AWS, serviços de terceiros ou serviços próprios hospedados em VPCs diferentes, de forma privada, sem passar pela internet pública.

O PrivateLink cria uma conexão privada e segura entre a sua VPC e outro serviço, usando a rede da AWS, sem expor IPs públicos ou depender de Internet Gateway, NAT ou VPN.

#### Vantagens

  - Usa Interface VPC Endpoints (com ENIs privados)
  - O tráfego não sai da rede da AWS
  - Suporta serviços da AWS, Marketplace ou serviços personalizados
  - É ideal para evitar exposição à internet
  - Usa DNS interno para facilitar acesso ao serviço

#### Quando usar o AWS PrivateLink

| Situação | Benefício com PrivateLink |
|:------:|:------:|
| Acessar um serviço em outra VPC | Conexão privada e segura, mesmo entre contas diferentes |
| Fornecer um serviço para outras contas | Você publica como um "serviço PrivateLink" |
| Acessar serviços da AWS com segurança | Comunicação sem passar pela internet |
| Substituir peering em arquiteturas complexas | Escala melhor e mais seguro que VPC Peering |

---

### AWS Direct Connect 

É um serviço que permite estabelecer uma conexão de rede física e dedicada entre o seu ambiente local (como um data center, escritório ou colocation) e a AWS, sem passar pela internet pública.

O Direct Connect é como instalar um "cabo direto e seguro" entre sua empresa e a AWS, oferecendo mais velocidade, confiabilidade e segurança que uma conexão pela internet.

#### Vantagens

  - Baixa latência e alta largura de banda
  - Mais seguro: não passa pela internet
  - Previsibilidade de desempenho (menos variação de tráfego)
  - Economia em transferência de dados (taxas mais baixas que Internet Gateway ou VPN)

#### Exemplos de uso

| Situação | Como o Direct Connect ajuda |
|:------:|:------:|
| Empresa com alto volume de dados | Transfere dados de forma rápida e econômica |
| Aplicações sensíveis à latência | Garante estabilidade na comunicação |
| Necessidade de conformidade ou segurança | Evita tráfego pela internet |
| Substituição de VPN por algo mais robusto | Mais confiável e performático que VPN/IPsec |

---

### AWS Transit Gateway

É um serviço que permite conectar múltiplas VPCs e redes locais (on-premises) por meio de um ponto central de roteamento, de forma escalável, segura e eficiente.

O Transit Gateway funciona como um "hub central" que simplifica a comunicação entre várias VPCs, contas e conexões Direct Connect/VPN, evitando a complexidade de conexões diretas entre todas elas.

#### Vantagens

  - Centraliza o roteamento entre várias redes
  - Escala para centenas de VPCs
  - Isolamento e controle com políticas e domínios de roteamento
  - Suporta VPN, Direct Connect e VPCs multi-conta
  - Integra com AWS Resource Access Manager (RAM) para compartilhar com outras contas

#### Exemplos de uso

| Situação | Como o Transit Gateway ajuda |
|:------:|:------:|
| Muitas VPCs que precisam se comunicar | Elimina a complexidade do VPC Peering em malha |
| Ambientes multi-conta com redes separadas | Conecta todas através de um hub |
| Conexão híbrida com redes locais (on-premises) | Facilita o roteamento via Direct Connect ou VPN |
| Centralizar regras e segurança de rede | Usa domínios de roteamento e ACLs mais controlados |

---

### Amazon Route 53

É o serviço de DNS (Domain Name System) da AWS, usado para registrar domínios, gerenciar nomes de domínio e rotear tráfego para aplicações na internet ou internamente na nuvem.

O Route 53 traduz nomes de domínio (como www.exemplo.com) em endereços IP (como 192.0.2.1) e pode controlar para onde o tráfego vai, com alta disponibilidade e baixa latência.

#### Vantagens

  - DNS Gerenciado
    - Resolve nomes de domínio para IPs de instâncias, ELBs etc.
  - Registro de Domínio
    - Você pode comprar e gerenciar domínios dentro da AWS
  - Roteamento de Tráfego
    - Direciona usuários com base em regras geográficas, failover, latência etc.
  - Health Checks
    - Monitora recursos e desvia tráfego em caso de falha
  - DNS Interno (privado)
    - Resolve nomes dentro de uma VPC (sem expor para a internet)

#### Políticas do Amazon Route 53

As políticas do Amazon Route 53 (Route 53 routing policies) definem como o tráfego de rede será roteado para os recursos configurados nos registros DNS (como instâncias EC2, buckets S3, load balancers etc.).

Essas políticas controlam quem acessa o quê, de onde, e com que prioridade, com base em diferentes critérios.

#### Tipos de Routing Policies (Políticas de Roteamento) no Route 53:

| Política | Descrição | Quando usar |
|:------:|:------:|:------:|
| Simple Routing | Um único destino para o domínio. | Sites ou apps simples com um único backend. |
| Weighted Routing | Distribui o tráfego entre múltiplos recursos com pesos definidos. | Balanceamento de carga com pesos diferentes. |
| Latency-based Routing | Direciona o tráfego para a região da AWS com menor latência. | Melhorar a performance com base na geolocalização. |
| Failover Routing | Usa um destino primário e outro de backup caso o primário falhe. | Alta disponibilidade e recuperação de falhas. |
| Geolocation Routing | Direciona com base na localização geográfica do usuário (país, estado, etc.). | Mostrar conteúdo regionalizado ou cumprir requisitos locais. |
| Geoproximity Routing | Direciona com base na proximidade do usuário e do recurso (usado com Route 53 Traffic Flow). | Reduzir latência e controlar balanceamento com mais precisão. |
| Multivalue Answer Routing | Retorna vários IPs e atua como um mini balanceador de carga com verificação de saúde. | Alta disponibilidade sem usar um ELB. |

---

### Amazon CloudFront

É o serviço de CDN (Content Delivery Network) da AWS. Ele acelera a entrega de conteúdos (como sites, vídeos, APIs, arquivos e apps) para usuários no mundo todo, ao distribuir o conteúdo em centenas de pontos de presença (edge locations) espalhados globalmente.

#### Como funciona

  - Um usuário acessa seu conteúdo (por exemplo, uma imagem ou vídeo em seu site).
  - O CloudFront redireciona a requisição para o edge location mais próximo do usuário.
  - Se o conteúdo já está nesse local (em cache), ele é entregue imediatamente → rápido e com baixa latência.
  - Se não está, o CloudFront busca o conteúdo da origem (como S3, EC2, API Gateway, ou servidor externo), entrega ao usuário e guarda em cache para futuras requisições.

#### Para que serve

  - Sites estáticos e dinâmicos (HTML, CSS, JS, APIs)
  - Streaming de vídeo (HLS, DASH)
  - Entrega de software e arquivos grandes
  - Proteção de aplicações com WAF, TLS, restrições geográficas
  - Integração com S3, ALB, EC2, Lambda@Edge

---

### AWS Global Accelerator

É um serviço da AWS que melhora a performance e a disponibilidade de aplicações globais, direcionando o tráfego dos usuários para a AWS usando a rede global da Amazon em vez da internet pública.

#### Vantagens

  - Quando você ativa o Global Accelerator, ele fornece dois IPs fixos globais (Anycast).
  - Usuários de qualquer lugar do mundo se conectam a esses IPs.
  - O tráfego entra na edge location mais próxima do usuário (ponto de presença da AWS).
  - A partir dali, os dados viajam pelo backbone da AWS, que é mais rápido, confiável e seguro do que a internet pública.
  - O serviço redireciona automaticamente para a região AWS mais saudável e próxima da origem, com base em latência e disponibilidade.

#### Casos de uso

| Uso | Benefício |
|:------:|:------:|
| Aplicações globais com usuários espalhados | Roteamento mais rápido e consistente |
| Failover automático entre regiões | Alta disponibilidade |
| Jogos online, fintechs, VoIP, APIs críticas | Baixa latência e alta confiabilidade |
| Substituir IPs elásticos ou balanceadores regionais | IP fixo global simplifica integração e firewall |

#### Diferenças entre Global Accelerator e CloudFront

| Recurso | Global Accelerator | CloudFront |
|:------:|:------:|:------:|
| Tipo de tráfego | TCP/UDP direto (ex.: APIs, aplicações, sockets) | HTTP/HTTPS com cache (ex.: sites, imagens) |
| Cache | Não | Sim |
| IP fixo | Sim (2 IPs globais) | Não |
| Roteamento inteligente | Sim (por latência, saúde) | Sim (por geolocalização, TTL) |
| Indicado para | APIs, backends, aplicações | Sites estáticos, conteúdo web, vídeos |

---  

### Docker 

É uma plataforma de containers que permite empacotar uma aplicação junto com todas as suas dependências (bibliotecas, configurações, etc.) em um único container. Isso garante que a aplicação funcione da mesma forma em qualquer ambiente — seja no seu computador, em um servidor ou na nuvem.

Docker é como uma "caixa" que carrega seu programa pronto para rodar, não importa onde.

#### Vantagens

  - Portabilidade
    - roda igual em qualquer lugar (dev, teste, produção)
  - Leveza e velocidade
    - containers são mais rápidos e usam menos recursos que máquinas virtuais
  - Reprodutibilidade
    - elimina o famoso "na minha máquina funciona"
  - Escalabilidade
    - facilita rodar várias instâncias da aplicação
  - Isolamento
    - cada container roda separado dos outros

--- 

### ECS (Elastic Container Service)

É um serviço da AWS para orquestração de containers, ou seja, ele gerencia o desdobramento, execução, escalonamento e monitoramento de containers Docker em ambientes da AWS.

O ECS é como um "gerente de containers" que garante que seus containers estejam sempre funcionando, escalando conforme necessário, e rodando onde for mais eficiente.

#### Vantagens

| Recurso | Descrição |
|:------:|:------:|
| Suporte nativo a Docker | ECS usa containers Docker como unidade de execução |
| Orquestração automática | Decide onde e como os containers rodam (como o Kubernetes faz) |
| Auto scaling | Escala containers ou instâncias automaticamente |
| Integração com AWS | Funciona perfeitamente com IAM, CloudWatch, ALB, ECR, etc. |
| Dois modos de execução | Você pode rodar no EC2 (com servidor) ou Fargate (serverless) |

--- 

### EKS (Elastic Kubernetes Service)

É o serviço gerenciado da AWS para rodar clusters Kubernetes. Ele permite que você implante, gerencie e escale aplicações em containers usando Kubernetes, sem precisar configurar manualmente todo o cluster.

O EKS é o Kubernetes "pronto para usar" na AWS — você usa o poder do Kubernetes, e a AWS cuida da infraestrutura.

#### Vantagens

| Recurso | Descrição |
|:------:|:------:|
| Gerenciado pela AWS | AWS configura, atualiza e mantém o plano de controle (control plane) |
| Integração com AWS | Funciona bem com IAM, VPC, ELB, CloudWatch, EBS, etc. |
| Totalmente compatível | É Kubernetes padrão — tudo que funciona em Kubernetes funciona no EKS |
| Alta disponibilidade | O control plane roda de forma redundante e segura |

#### Diferença entre ECS e EKS

| Característica | ECS | EKS |
|:------:|:------:|:------:|
| Orquestrador | Proprietário da AWS | Kubernetes (open-source) |
| Curva de aprendizado | Mais simples | Mais complexa, mas mais flexível |
| Comunidade | AWS | Mundial (open-source) |
| Portabilidade | Menor (mais preso à AWS) | Alta (mesmo Kubernetes em qualquer lugar) |

#### Kubernetes 

O Kubernetes (também chamado de K8s) é uma plataforma open-source de orquestração de containers. Ele automatiza o processo de implantação, gerenciamento, escalonamento e atualização de aplicações em containers, como os criados com Docker.

O Kubernetes é como um "sistema operacional para containers" — ele cuida de tudo: onde rodar, como escalar, como reiniciar se algo falhar, etc.

--- 

### AWS Fargate

É um serviço da AWS que permite executar containers (como Docker) sem precisar gerenciar servidores ou clusters. Ele funciona como um "motor serverless" para serviços de orquestração como o ECS (Elastic Container Service) e o EKS (Kubernetes).

Com o Fargate, você executa containers sem se preocupar com instâncias EC2, dimensionamento ou gerenciamento de infraestrutura.

#### Vantagens

  - Serverless para containers
    - Não precisa configurar EC2, VPCs, clusters ou escalabilidade manual
  - Escala automática
    - Executa desde 1 até milhares de containers, conforme a carga
  - Segurança isolada
    - Cada tarefa/container roda de forma isolada
  - Custo sob demanda
    - Paga apenas pelos recursos usados (CPU e memória, por segundo)
  - Integra com ECS e EKS
    - Pode usar com ECS (mais simples) ou EKS (Kubernetes)
    
--- 

### Amazon Kinesis

É um serviço da AWS para coletar, processar e analisar grandes volumes de dados em tempo real — como logs, cliques, dados de sensores, streams de vídeo, etc.

O Kinesis é como uma esteira rolante de dados: ele capta dados continuamente de várias fontes e permite processá-los quase instantaneamente.

#### Principais componentes do Kinesis

| Serviço | Função |
|:------:|:------:|
| Kinesis Data Streams | Capta e armazena fluxos de dados em tempo real para processar depois |
| Kinesis Data Firehose | Capta dados e envia automaticamente para destinos como S3, Redshift, etc |
| Kinesis Data Analytics | Permite usar SQL para consultar e processar dados em tempo real |
| Kinesis Video Streams | Transmite, armazena e analisa fluxos de vídeo |

--- 

### Amazon SQS (Simple Queue Service)

É um serviço da AWS que oferece filas de mensagens totalmente gerenciadas, permitindo que sistemas distribuídos se comuniquem de forma assíncrona e desacoplada.

O SQS é como uma "fila de correio" digital: uma aplicação envia mensagens para a fila e outra aplicação pega essas mensagens quando puder processá-las — cada uma no seu tempo.

#### Vantagens

  - Desacopla sistemas
    - o produtor (quem envia a mensagem) e o consumidor (quem lê) funcionam de forma independente.
  - Alta escalabilidade
    - processa milhões de mensagens por segundo.
  - Tolerância a falhas
    - mensagens ficam na fila mesmo se o consumidor cair.
  - Controle de mensagens
    - define tempo de retenção, tentativas, e ordem de leitura.

#### Tipos de filas no SQS

| Tipo | Características |
|:------:|:------:|
| Standard Queue | Alta performance, entrega pelo menos uma vez, ordem não garantida |
| FIFO Queue | Entrega exatamente uma vez, ordem garantida (First-In-First-Out) |

--- 

### Amazon SNS (Simple Notification Service)

É um serviço da AWS para envio de notificações em tempo real, baseado no modelo pub/sub (publicador/assinante). Ele permite que uma aplicação envie mensagens para múltiplos destinos ao mesmo tempo, como e-mails, SMS, outras aplicações ou serviços AWS.

O SNS é como um "alto-falante": você publica uma mensagem em um tópico, e todos os assinantes recebem ao mesmo tempo.

#### Vantagens

  - Enviar alertas por e-mail ou SMS
  - Disparar notificações push para aplicativos móveis
  - Informar outros serviços AWS (como SQS, Lambda)
  - Criar fluxos de eventos assíncronos

#### SNS vs SQS

| Característica | SNS (Pub/Sub) | SQS (Fila) |
|:------:|:------:|:------:|
| Tipo de entrega | Envia para múltiplos destinos ao mesmo tempo | Armazena mensagem até que seja consumida |
| Ordem de consumo | Todos recebem ao mesmo tempo | Um consumidor por vez |
| Tempo de retenção | Não guarda mensagens | Armazena por até 14 dias |
| Usado para | Notificações, broadcast | Processamento assíncrono, filas de tarefas |

--- 

### AWS Batch

É um serviço da AWS que permite executar tarefas de computação em lote (batch jobs) de forma totalmente gerenciada, escalável e eficiente, sem precisar se preocupar com servidores ou filas manuais.

O AWS Batch roda tarefas de processamento intensivo (como cálculos, conversões, análises) em segundo plano, em qualquer escala e de forma automática.

#### Vantagens

  - Gerenciamento automático
    - Ele provisiona e escala os recursos (instâncias EC2, Fargate, etc.)
  - Execução de jobs em lote
    - Ideal para tarefas como renderização, análise de dados, machine learning
  - Job queues
    - Você pode organizar e priorizar tarefas por fila
  - Integração com Docker
    - Você empacota seu código em containers e o AWS Batch executa

--- 

### Amazon Lightsail

É um serviço da AWS voltado para quem quer implementar aplicações de forma simples e rápida, sem precisar lidar com toda a complexidade dos serviços mais avançados da AWS como EC2, VPC, etc.

O Lightsail é como uma versão mais fácil e amigável do EC2, ideal para sites simples, blogs, pequenos sistemas e testes rápidos.

#### Vantagens

  - Instâncias prontas
    - Crie um servidor com WordPress, LAMP, Node.js, etc. com 1 clique
  - Preço fixo
    - Você escolhe um plano com valor mensal previsível
  - Endereço IP público
    - Já vem com IP fixo, DNS, e pode configurar domínios facilmente
  - Armazenamento SSD
    - Inclui disco rápido com backup integrado
  - Rede simplificada
    - Inclui firewall, DNS e balanceador de carga fáceis de configurar
  - Console intuitivo
    - Painel visual muito mais simples que o do EC2

#### Quando usar

  - Blogs (WordPress, Ghost, etc.)
  - Sites institucionais
  - Pequenos e-commerces
  - Aplicações web pessoais ou de teste
  - Ambientes de desenvolvimento

--- 

### AWS Lambda

É um serviço da AWS que permite executar funções (código) sem precisar gerenciar servidores — por isso é chamado de computação serverless.

Com o Lambda, você sobe seu código, define quando ele deve rodar, e a AWS cuida de toda a infraestrutura por trás. Você só paga pelo tempo de execução.

#### Vantagens

  - Totalmente gerenciado
    - Você não precisa criar ou escalar servidores
  - Event-driven
    - Responde a eventos de outros serviços AWS (S3, DynamoDB, SNS, etc.)
  - Escala automática
    - Roda 1 vez ou milhões, sem precisar configurar
  - Custo por uso
    - Você paga só pelos milissegundos que o código roda
  - Seguro por padrão
    - Integra com IAM e roles para permissões seguras

#### Lambda vs EC2

| Característica | Lambda | EC2 |
|:------:|:------:|:------:|

| Infraestrutura | Oculta (serverless) | Você gerencia a máquina virtual |
| Escalabilidade | Automática e instantânea | Manual ou via Auto Scaling |
| Ideal para | Tarefas rápidas e event-driven | Aplicações complexas e contínuas |
| Preço | Por execução e tempo de uso | Por hora de instância ativa |

---

### AWS Control Tower

É um serviço da AWS que facilita a criação, organização e governança de múltiplas contas AWS dentro de um ambiente corporativo — ou seja, ele ajuda você a criar e manter um ambiente multi-conta seguro, padronizado e escalável.

O Control Tower é como um "gerente de nuvem corporativa", que configura boas práticas automaticamente, como segurança, compliance e contas separadas, desde o início.

#### O que o Control Tower faz

| Função | Descrição |
|:------:|:------:|
| Landing zone automática | Cria uma base com segurança, redes e contas organizadas |
| Guardrails | Regras pré-definidas de segurança e compliance (ex: impedir root access) |
| Automação de contas |	Criação automática de contas novas com políticas aplicadas |
| Organização via AWS Organizations | Integra com o serviço que gerencia múltiplas contas (AWS Organizations) |
| Auditoria e visibilidade | Ajuda a acompanhar o uso e conformidade de cada conta |

---

### AWS RAM (Resource Access Manager)

É um serviço da AWS que permite compartilhar recursos entre contas da AWS de forma simples e segura. Ele ajuda a facilitar a colaboração e o uso compartilhado de recursos, sem a necessidade de duplicação ou migração de recursos entre contas.

O AWS RAM permite que você compartilhe recursos, como VPCs, sub-redes, imagens, etc., de uma conta AWS para outras contas ou organizações, sem precisar replicar esses recursos.

#### Vantagens

  - Compartilhamento de recursos
    - Permite compartilhar recursos como VPC, sub-redes, snapshots e mais
  - Controle de acesso
    - Você pode definir quais contas ou organizações podem acessar os recursos
  - Segurança
    -	Controle fino de permissões com AWS IAM para governança e controle
  - Multi-contas e organizações
    - Pode compartilhar recursos entre contas e organizações AWS diferentes

---

### AWS Trusted Advisor

É um serviço da AWS que oferece recomendações sobre como melhorar a eficiência, segurança e reduzir custos da sua infraestrutura na AWS. Ele age como um consultor automatizado, analisando as configurações e práticas de uso da sua conta para fornecer sugestões práticas e melhores práticas.

O Trusted Advisor verifica a sua infraestrutura AWS e fornece alertas e recomendações personalizadas para ajudá-lo a otimizar seus recursos e garantir que você está seguindo as melhores práticas da AWS.

#### Principais funcionalidades

| Recurso | Descrição |
|:------:|:------:|
| Recomendações de custo | Sugestões sobre como reduzir custos (ex: desligar instâncias ociosas) |
| Segurança | Alertas sobre configurações de segurança inadequadas (ex: permissões excessivas) |
| Performance | Sugestões para melhorar a performance (ex: usar instâncias mais adequadas) |
| Práticas recomendadas | Dicas gerais para manter sua infraestrutura eficiente e segura |
| Limitações e quotas | Alerta sobre limites de recursos que você pode estar alcançando |

---

### AWS Service Catalog

É um serviço que permite que empresas criem, organizem e disponibilizem catálogos de serviços/aplicações aprovados — como templates de infraestrutura, stacks do CloudFormation, softwares, AMIs, VMs e containers — para que os times usem de forma padronizada, segura e controlada.

#### Vantagens

  - Controle de acesso
    - Define quem pode lançar e gerenciar produtos
  - Governo e compliance
    - Garante padrões de segurança e tags obrigatórias
  - Reuso de infraestrutura
    - Evita retrabalho e erros manuais
  - Auditoria e visibilidade
    - Integração com CloudTrail e AWS Config
  - Compatível com múltiplas contas
    - Ideal para ambientes multi-conta com AWS Organizations

---

### Amazon Rekognition

É um serviço de Machine Learning da AWS que permite analisar imagens e vídeos de forma automática. Ele oferece reconhecimento facial, detecção de objetos, leitura de texto em imagens (OCR), moderação de conteúdo e outras funcionalidades avançadas de visão computacional, sem que você precise treinar modelos de IA do zero.

#### Vantagens

  - Detecção de objetos e cenas
    - Identifica itens como carros, pessoas, animais, prédios, etc., em imagens ou vídeos.
  - Reconhecimento facial
    - Detecta rostos em imagens ou vídeos.
    - Compara rostos (por exemplo, comparar um rosto com uma base de dados).
    - Identifica emoções (feliz, triste, surpreso, etc.).
    - Estima idade, gênero e outros atributos faciais.
  - Análise de texto em imagens (OCR)
    - Extrai texto impresso de imagens (como placas, documentos, sinais etc.).
  - Moderação de conteúdo
    - Detecta conteúdo inapropriado, como nudez, violência ou drogas, útil para redes sociais ou uploads públicos.
  - Análise de vídeos
    - Permite rastrear pessoas em movimento, detectar atividades e identificar rostos ao longo do tempo em vídeos.

---

### Amazon Transcribe

É um serviço de Machine Learning da AWS que faz transcrição automática de áudio em texto. Ou seja, ele converte gravações de voz (como reuniões, ligações, vídeos ou podcasts) em texto escrito de forma precisa e automatizada.

#### Vantagens

  - Transcrição de fala em tempo real (streaming)
    - Converte fala para texto à medida que o áudio é capturado (útil para legendas ao vivo, por exemplo).
  - Transcrição de arquivos de áudio gravados
    - Suporta formatos como MP3, WAV, FLAC, etc.
  - Identificação de múltiplos locutores (diarização)
    - Informa quando há mais de uma pessoa falando (ex: "Locutor 1:", "Locutor 2:").
  - Reconhecimento de idiomas
    - Detecta automaticamente o idioma falado (como português, inglês, espanhol, etc.).
  - Vocabulário personalizado
    - Permite adicionar nomes técnicos, termos específicos ou nomes de marcas para melhorar a precisão.
  - Detecção de palavras-chave e marcação de tempo
    - Mostra quando cada palavra foi dita no áudio (útil para buscas em vídeo, por exemplo).

---

### Amazon Comprehend

É um serviço de Processamento de Linguagem Natural (NLP) da AWS que usa machine learning para entender o significado de textos. Ele analisa textos e extrai informações como sentimentos, tópicos, entidades (nomes, lugares, empresas) e idioma.

#### Vantagens

  - Detecção de idioma
    - Identifica automaticamente em qual idioma o texto está escrito.
  - Análise de sentimento
    - Determina se o texto expressa um sentimento positivo, negativo, neutro ou misto.
  - Extração de entidades
    - Reconhece nomes de pessoas, empresas, locais, datas, quantias em dinheiro, etc.
  - Extração de palavras-chave (key phrases)
    - Identifica os conceitos principais em uma frase ou parágrafo.
  - Classificação de texto
    - Organiza textos em categorias personalizadas (por exemplo: suporte técnico, reclamação, elogio).
  - Reconhecimento de relações entre entidades
    - Analisa conexões entre nomes, eventos e objetos no texto.
  - Análise de tópicos
    - Identifica os principais temas em grandes volumes de texto (por exemplo, comentários de clientes ou postagens em redes sociais).

---

### Amazon Polly

É um serviço de Machine Learning da AWS que transforma texto em fala (Text-to-Speech – TTS). Ou seja, ele lê textos em voz alta com qualidade natural, usando vozes geradas por inteligência artificial.

#### Vantagens

  - Conversão de texto em fala (TTS)
    - Converte texto escrito em áudio, usando vozes humanas realistas.
    - Suporta dezenas de idiomas, incluindo português do Brasil.
  - Vozes neurais (Neural TTS)
    - Usa deep learning para criar vozes mais naturais, com entonação e ritmo semelhantes aos de um ser humano.
  - Ajuste de pronúncia e entonação (SSML)
    - Permite controlar pausas, velocidade, ênfase, volume e pronúncia usando marcações no texto.
  - Streaming de áudio
    - Permite começar a falar imediatamente, antes de terminar de processar todo o texto (útil para leitura ao vivo).
  - Geração de arquivos de áudio
    - Converte textos em arquivos MP3, OGG ou PCM, que podem ser armazenados e reproduzidos.

---

### Amazon Translate

É um serviço de tradução automática de texto baseado em Machine Learning da AWS. Ele permite traduzir textos entre diferentes idiomas de forma rápida, precisa e escalável, sem precisar treinar um modelo próprio.

#### Vantagens

  - Tradução automática de idiomas
    - Suporta mais de 75 idiomas, incluindo português, inglês, espanhol, francês, alemão, entre outros.
    - Permite traduções em tempo real ou em grandes volumes de texto.
  - Detecção automática de idioma
    - Se o idioma de entrada não for especificado, o serviço pode detectá-lo automaticamente.
  - Tradução personalizada com Custom Terminology
    - Permite definir vocabulário específico para garantir que termos técnicos ou nomes de marcas sejam traduzidos corretamente.
  - Integração com outros serviços AWS
    - Pode ser combinado com Amazon Comprehend, Amazon Polly, ou Amazon S3, por exemplo.

---

### Amazon Lex

É um serviço de Machine Learning da AWS que permite criar chatbots e assistentes virtuais inteligentes que entendem linguagem natural falada ou escrita. Ele usa a mesma tecnologia do Amazon Alexa para interpretar e responder interações humanas.

#### Vantagens

  - Processamento de linguagem natural (NLP)
    - Entende intenções do usuário e extrai informações importantes da fala ou texto (por exemplo: horários, datas, nomes).
  - Entrada de voz e texto
    - Pode interagir por texto (chat) ou voz (áudio).
  - Integração com outros serviços
    - Fácil de integrar com Amazon Connect (central de atendimento), Lambda, DynamoDB, etc.
  - Gerenciamento de sessões e contexto
    - Lembra de informações durante uma conversa e conduz diálogos mais naturais.
  - Criação de bots com interface visual
    - Você pode criar e configurar bots diretamente na console da AWS, definindo intenções (intents) e frases de exemplo.

---

### Amazon Kendra

É um serviço de busca inteligente (enterprise search) baseado em Machine Learning da AWS. Ele permite que as empresas criem sistemas de pesquisa com linguagem natural dentro dos seus próprios documentos e sistemas internos — como se fosse um "Google corporativo".

#### Vantagens

  - Busca por linguagem natural
    - E o Kendra entende a intenção e retorna respostas precisas, mesmo que a pergunta não esteja escrita literalmente nos documentos.
  - Conectores para múltiplas fontes
    - Conecta-se a SharePoint, S3, Salesforce, Dropbox, bancos de dados, sites internos, entre outros, para buscar dados.
  - Resposta direta (Answer Extraction)
    - Em vez de mostrar apenas links ou documentos, o Kendra pode mostrar um trecho direto da resposta.
  - Relevância inteligente
    - Usa ML para ranquear os melhores resultados, com base no contexto, uso anterior e feedback do usuário.
  - Controle de acesso
    - Garante que os usuários só vejam resultados para os quais têm permissão.

---

### Amazon Textract

É um serviço de Machine Learning da AWS que extrai automaticamente texto, tabelas e dados de formulários em documentos digitalizados — como PDFs, imagens escaneadas ou fotos de papéis.

Diferente de um OCR tradicional (que apenas lê o texto), o Textract compreende a estrutura do documento, identificando campos, rótulos, colunas e relações entre dados.

#### Vantagens

  - Extração de texto impresso e manuscrito
    - Lê texto de documentos escaneados (como contratos, recibos, faturas, formulários, etc.).
  - Reconhecimento de formulários
    - Identifica pares de chave-valor.
  - Detecção de tabelas
    - Reconhece linhas, colunas e células em tabelas de documentos, mesmo com layouts complexos.
  - Processamento de documentos em lote
    - Permite extrair dados de milhares de documentos de forma automatizada.
  - Integração com outros serviços
    - Pode ser combinado com Amazon Comprehend (para entender o conteúdo), AWS Lambda, S3 e Textract Analyze Lending (voltado para documentos financeiros).

---

### Amazon SageMaker 

É um serviço da AWS que permite criar, treinar e implantar modelos de machine learning de forma rápida, segura e escalável. Ele é voltado tanto para iniciantes quanto para cientistas de dados experientes, e elimina muito do trabalho manual envolvido no desenvolvimento de modelos de ML.

#### Vantagens

  - Ambiente completo de desenvolvimento
    - Fornece notebooks Jupyter prontos para escrever código, explorar dados e treinar modelos — sem precisar configurar infraestrutura.
  - Treinamento de modelos em grande escala
    - Treina modelos com rapidez usando instâncias otimizadas, com suporte a paralelismo e GPU.
  - Implantação automática de modelos
    - Permite publicar modelos em produção com um clique, criando endpoints com escalabilidade automática.
  - AutoML com SageMaker Autopilot
    - Gera automaticamente os melhores modelos para seus dados, mesmo sem saber programar ou entender algoritmos.
  - Rotulagem de dados (Ground Truth)
    - Ajuda a anotar dados de treinamento (como imagens, texto, etc.) com rotulagem automatizada e humana.
  - Monitoramento e ajuste contínuo
    - Acompanha a performance do modelo em produção e sugere re-treinamento se ele começar a ter baixa precisão.

---

### AWS Well-Architected Framework

É um conjunto de boas práticas e diretrizes da AWS para ajudar empresas e desenvolvedores a projetar, construir e operar sistemas na nuvem que sejam seguros, eficientes, resilientes e otimizados em custo.

Ele fornece um modelo estruturado com recomendações que ajudam a garantir que suas aplicações estejam:

- Seguras
- Confiáveis
- Eficientes em performance
- Otimizada em custos
- Sustentáveis

#### Vantagens

  - Avaliar a arquitetura atual de suas aplicações na AWS.
  - Identificar riscos e pontos de melhoria.
  - Planejar mudanças para aumentar a qualidade e segurança dos sistemas.
  - Guiar equipes de desenvolvimento e operações com práticas recomendadas.

#### 6 pilares

  - Excelência operacional (Operational Excellence)
    - Melhores práticas para executar e monitorar sistemas, automatizar processos e melhorar continuamente.
  - Segurança (Security)
    - Proteção de dados, controle de acesso, monitoramento e resposta a incidentes.
  - Confiabilidade (Reliability)
    - Garantir que a aplicação continue funcionando bem mesmo com falhas, recuperação automática e escalabilidade.
  - Eficiência de performance (Performance Efficiency)
    - Uso eficiente dos recursos de computação para entregar a melhor performance.
  - Otimização de custos (Cost Optimization)
    - Gerenciar custos e evitar gastos desnecessários, usando os recursos de forma inteligente.
  - Sustentabilidade (Sustainability)
    - Minimizar o impacto ambiental da infraestrutura em nuvem, otimizando o uso de recursos.

---

### AWS CAF (Cloud Adoption Framework)

É um guia da AWS que ajuda empresas a planejar e acelerar a adoção da nuvem de forma organizada e estratégica.

Ele oferece um conjunto de melhores práticas, diretrizes e ferramentas para que organizações consigam:

- Preparar pessoas, processos e tecnologia para migrar para a nuvem.
- Gerenciar mudanças culturais e organizacionais.
- Identificar lacunas e necessidades antes, durante e depois da migração.

#### Vantagens

  - Planejar a jornada para a nuvem.
  - Identificar pontos fortes e áreas que precisam de melhoria.
  - Criar um roadmap personalizado de migração e transformação digital.
  - Engajar todas as áreas da empresa para uma adoção mais eficaz.

#### 6 pilares (perspectivas)

  - Negócios (Business)
    - Alinha a estratégia de negócios com a adoção da nuvem, incluindo ROI, análise de custos e valor para o negócio.
  - Pessoas (People)
    - Gestão de mudanças culturais, treinamento e capacitação das equipes para a nuvem.
  - Governança (Governance)
    - Políticas, conformidade, segurança, riscos e gerenciamento financeiro na nuvem.
  - Plataforma (Platform)
    - Arquitetura técnica, infraestrutura, automação e implantação de aplicações na nuvem.
  - Segurança (Security)
    - Proteção de dados, identidade, controle de acesso e conformidade.
  - Operações (Operations)
    - Monitoramento, gestão de incidentes, continuidade e otimização das operações na nuvem.

---

### AWS Ecosystem (Ecossistema AWS)

É o conjunto de serviços, ferramentas, parceiros e recursos que a Amazon Web Services oferece para apoiar empresas e desenvolvedores na criação, gerenciamento e escalabilidade de aplicações em nuvem.

O ecossistema AWS é como um "universo completo" de soluções que cobre infraestrutura, segurança, dados, IA, DevOps, aplicações, redes, entre outros.

#### Componentes principais do ecossistema:

| Categoria | Exemplos |
|:------:|:------:|
| Serviços de Computação | EC2, Lambda, ECS, EKS, Fargate |
| Machine Learning / IA | SageMaker, Rekognition, Comprehend, Lex |
| Bancos de Dados | RDS, DynamoDB, Aurora, Redshift, ElastiCache |
| Armazenamento | S3, EBS, EFS, FSx, Storage Gateway |
| Segurança e Acesso | IAM, KMS, Shield, WAF, Cognito |
| Redes | VPC, Route 53, CloudFront, Direct Connect |
| DevOps / Ferramentas de gestão | CloudFormation, CloudWatch, CodeBuild, CodeDeploy, CodePipeline |
| Analytics e Dados | Athena, Glue, Kinesis, QuickSight |
| Integração de aplicações | SQS, SNS, EventBridge, Step Functions |
| Parceiros e Marketplace | Ferramentas de terceiros, consultorias, licenças via AWS Marketplace |

#### Vantagens

  - Permite construir soluções completas 100% na nuvem, sem depender de infraestrutura própria
  - Facilita a integração entre serviços com escalabilidade e segurança
  - Dá liberdade para inovar, desde startups até grandes corporações
  - Oferece apoio técnico e comercial com parceiros e suporte especializado

---

### AWS Cognito

É um serviço da Amazon Web Services que permite adicionar autenticação, autorização e gerenciamento de usuários facilmente em suas aplicações web e mobile.

O AWS Cognito cuida de login, cadastro, recuperação de senha, autenticação social (Google, Facebook, etc.) e autenticação multifator (MFA) — tudo com segurança e escalabilidade gerenciadas pela AWS.

#### Principais componentes do Cognito

| Componente | Função |
|:------:|:------:|
| User Pools | Sistema de gerenciamento de usuários com suporte a login/senha, MFA, etc. |
| Identity Pools | Permite que usuários autenticados tenham acesso temporário a recursos da AWS, como S3 ou DynamoDB |
| Federated Identity | Integração com provedores externos como Google, Facebook, Apple, SAML, OpenID |

#### Vantagens

  - Criar um sistema de login para seu site ou app
  - Permitir login via redes sociais
  - Habilitar autenticação multifator (MFA)
  - Integrar com o Active Directory da empresa (via SAML)
  - Conceder permissões temporárias a recursos AWS com base na identidade do usuário
  
---

### Amazon STS (Security Token Service)

É um serviço da AWS que permite criar credenciais temporárias de segurança para acessar recursos da AWS.

O STS gera tokens temporários (credenciais válidas por minutos ou horas), usados por usuários, aplicações ou serviços para acessar recursos da AWS com segurança e sem precisar de credenciais fixas.

#### Principais usos do STS

| Situação | Como o STS ajuda |
|:------:|:------:|
| Acesso temporário para usuários IAM ou federados | Gera credenciais com tempo de validade definido |
| Assumir outra role (função) | Permite trocar de função dentro da AWS para executar uma tarefa |
| Login com provedores externos (SSO/SAML/OpenID) | Dá acesso à AWS após autenticação com Google, AD, etc. |
| Aplicações móveis ou web acessando AWS sem credenciais fixas | STS fornece tokens seguros para essas apps |
| Cross-account access (acesso entre contas) | Um usuário de uma conta pode assumir uma role em outra |

#### Vantagens

  - Mais seguro do que usar access keys fixas
  - Credenciais com validade controlada
  - Permissões limitadas e personalizadas
  - Usado em conjunto com IAM, Cognito e SSO

---

### AWS AppSync

É um serviço totalmente gerenciado da AWS que permite criar APIs GraphQL (e também REST) de forma rápida, segura e escalável, integrando diversas fontes de dados como DynamoDB, Lambda, RDS, Elasticsearch, HTTP APIs e mais.

O AppSync permite criar uma única API GraphQL que conecta e orquestra vários serviços da AWS, oferecendo dados sob demanda para apps web, mobile e IoT, com recursos como real-time (WebSocket), cache, controle de acesso e sincronização offline.

#### Principais recursos

| Recurso | Descrição |
|:------:|:------:|
| Integração com vários dados | Conecta facilmente a DynamoDB, Lambda, RDS, Elasticsearch, S3, HTTP APIs |
| Real-time com GraphQL Subscriptions | Envia dados em tempo real para os clientes |
| Sincronização offline (DataStore) | Suporte para apps móveis que funcionam sem conexão |
| Controle de acesso | Suporte nativo a IAM, Cognito e API keys |
| Caching automático | Acelera a resposta de queries com cache gerenciado |
| Escalável e gerenciado | A AWS cuida da infraestrutura, escalabilidade e segurança |

#### Vantagens

  - Reduz a complexidade no frontend (menos chamadas e processamento)
  - Backend mais desacoplado e organizado
  - Ideal para aplicativos modernos (React, Angular, Flutter, etc.)
  - Suporte a dados em tempo real e offline

---

### AWS Amplify

É uma plataforma da AWS que facilita o desenvolvimento de aplicações web e mobile fullstack, oferecendo ferramentas para frontend, backend e CI/CD, com foco na velocidade, integração com serviços AWS e simplicidade para desenvolvedores.

O Amplify ajuda você a criar, configurar, implantar e escalar aplicações modernas com recursos como autenticação, banco de dados, APIs, storage, hospedagem, e mais, tudo com comandos simples ou via interface visual.

#### Vantagens

| Recurso | Descrição |
|:------:|:------:|
| Frontend hosting | Hospedagem para SPAs (React, Angular, Vue, Next.js, etc.) com CI/CD |
| Autenticação | Login via email/senha, redes sociais, MFA — usando Cognito |
| API (REST ou GraphQL) | Criação de APIs com Lambda + API Gateway ou AppSync + GraphQL |
| Banco de dados | Integração com DynamoDB ou Aurora Serverless |
| Armazenamento | Upload e acesso a arquivos no Amazon S3 |
| Gerador de backend | Criação e configuração do backend com comandos CLI ou interface web |
| DataStore | Sincronização offline/online automática para apps móveis |

---

### AWS IoT Core

É um serviço da AWS que permite conectar dispositivos físicos (sensores, câmeras, eletrodomésticos, carros, etc.) à nuvem de forma segura, escalável e em tempo real.

O IoT Core conecta dispositivos à nuvem para que eles possam enviar dados, receber comandos e interagir com outros serviços da AWS, como Lambda, S3, DynamoDB e Machine Learning.

#### Vantagens

| Recurso | Descrição |
|:------:|:------:|
| Conectividade segura | Conecta milhões de dispositivos via MQTT, HTTP ou WebSockets com TLS |
| Mensageria em tempo real | Dispositivos podem enviar e receber mensagens instantaneamente |
| Gerenciamento de identidade e segurança | Cada dispositivo tem um certificado, política e autenticação próprios |
| Processamento de dados | Envia dados para Lambda, S3, Kinesis, DynamoDB, etc. |
| Regras inteligentes | Permite criar regras (como SQL) para rotear, transformar ou armazenar dados |

---

### AWS Step Functions

É um serviço da AWS que permite orquestrar múltiplos serviços da AWS em fluxos de trabalho visuais, definidos por etapas (steps), de forma sequencial ou paralela, com controle, monitoramento e tratamento de erros.

O Step Functions cria máquinas de estado (state machines) que coordenam tarefas como chamadas a Lambda, ECS, DynamoDB, SQS, API Gateway, etc., permitindo construir aplicações distribuídas, confiáveis e escaláveis sem gerenciar servidores.

#### Vantagens

| Recurso | Descrição |
|:------:|:------:|
| Orquestração de serviços | Controla a execução de múltiplos serviços da AWS |
| Visualização do fluxo | Interface gráfica para ver passo a passo o fluxo |
| Etapas sequenciais e paralelas | Suporta decisões condicionais, loops, paralelismo |
| Tratamento de erros automático | Retry, fallback e catch para lidar com falhas |
| Logs e monitoramento nativos | Integra com CloudWatch para rastrear e debugar |
| Alta segurança | Integração com IAM para controle de acesso |

---

### AWS AppFlow

É um serviço da AWS que permite a transferência segura e automatizada de dados entre aplicações SaaS (Software as a Service) e os serviços da AWS, como Amazon S3, Redshift, e outros.

O AWS AppFlow facilita a integração de dados entre plataformas como Salesforce, ServiceNow, Google Analytics, SAP, etc., e a AWS, sem a necessidade de escrever código, permitindo fluxos de dados bidirecionais e automáticos.

#### Vantagens

| Recurso | Descrição |
|:------:|:------:|
| Transferência de dados bidirecional | Envia dados para a AWS ou de volta para o SaaS |
| Segurança e conformidade | Criptografa dados em trânsito e em repouso, com controle de acesso via IAM |
| Mapeamento e transformação de dados | Suporta transformação de dados durante o fluxo (filtros, agregações) |
| Integração com diversos SaaS | Conecta com aplicações populares como Salesforce, SAP, ServiceNow, etc. |
| Facilidade de uso (sem código) | Interface gráfica para configurar fluxos de dados |
| Agendamento e automação | Defina quando e com que frequência os fluxos de dados serão executados |

---

### AWS Disaster Recovery Strategy (Estratégia de Recuperação de Desastres da AWS)

Estratégia de Recuperação envolve um conjunto de práticas, processos e serviços da AWS para garantir que os dados e as aplicações possam ser recuperados rapidamente e com mínima perda após eventos inesperados, como falhas de hardware, desastres naturais ou ataques cibernéticos.

A AWS oferece diversos níveis de estratégias de recuperação, que vão desde soluções mais simples e menos dispendiosas até estratégias mais complexas e robustas. A escolha da estratégia depende do nível de criticidade da aplicação, do tempo de inatividade aceitável (RTO - Recovery Time Objective) e da quantidade de dados aceitável de perda (RPO - Recovery Point Objective).

Uma estratégia de recuperação de desastres na AWS utiliza serviços de backup, replicação e recuperação para garantir que a infraestrutura, dados e aplicações possam ser rapidamente restaurados após uma falha ou desastre.

#### Estratégias de Recuperação de Desastres da AWS

A AWS define 4 tipos principais de estratégia para recuperação de desastres, com base no custo e na complexidade da implementação:

  - Backup e Restore (Backup e Recuperação):
    - Como funciona: Os dados são copiados periodicamente para um armazenamento seguro (como o Amazon S3 ou Amazon Glacier) e, no caso de um desastre, você restaura a partir desse backup.
    - Custo: Baixo custo, pois depende de backups periódicos.
    - RTO/RPO: O maior RTO e RPO entre as opções.
  - Pilot Light:
    - Como funciona: A infraestrutura crítica é mantida em execução em baixa capacidade em uma região de recuperação. Quando ocorre um desastre, a infraestrutura é aumentada para suportar a carga total.
    - Custo: Baixo custo de operação, pois a maioria dos recursos são mantidos em estado ocioso.
    - RTO/RPO: RTO e RPO mais rápidos que o modelo de Backup e Restore.
  - Warm Standby:
    - Como funciona: Mantém uma infraestrutura parcialmente provisionada em uma região secundária. Em caso de falha, a infraestrutura é escalada rapidamente para retomar a operação.
    - Custo: Maior custo do que o modelo Pilot Light, pois envolve manter uma parte dos recursos ativos.
    - RTO/RPO: RTO e RPO rápidos, mas não tão rápidos quanto o modelo Hot Standby.
  - Hot Standby (Hot Standby/Active-Active):
    - Como funciona: Mantém infraestruturas totalmente provisionadas e em funcionamento em duas regiões (primária e secundária). Em caso de falha, o tráfego é redirecionado instantaneamente para a região de recuperação.
    - Custo: Alto custo, pois todos os recursos são mantidos ativos.
    - RTO/RPO: O RTO e o RPO são muito baixos (praticamente instantâneos).

#### Vantagens

  - Redução do tempo de inatividade: Estratégias como Hot Standby oferecem quase nenhuma interrupção.
  - Custo-benefício: A AWS permite escolher uma estratégia que se adapte ao orçamento e à criticidade do sistema.
  - Escalabilidade: A recuperação de desastres pode ser feita de forma escalável e sem a necessidade de infraestrutura física.
  - Facilidade de gerenciamento: A AWS oferece ferramentas e automação para simplificar a recuperação.

---

### AWS WorkSpaces 

É um serviço gerenciado da Amazon que permite criar escritórios virtuais (desktops na nuvem) para seus usuários, acessíveis de qualquer lugar, usando dispositivos como PCs, tablets, navegadores ou thin clients.

O AWS WorkSpaces fornece desktops baseados na nuvem, seguros e escaláveis, com Windows ou Linux, permitindo que empresas ofereçam acesso remoto aos seus funcionários sem a necessidade de infraestrutura física de TI.

#### Características principais

| Recurso | Descrição |
|:------:|:------:|
| Desktop como serviço (DaaS) | Substitui PCs físicos por desktops virtuais gerenciados pela AWS |
| Segurança integrada | Armazena dados na AWS, não no dispositivo local, e integra com IAM |
| Custo sob demanda | Paga por hora ou por mês, de acordo com o uso |
| Customização | Escolha sistema operacional, quantidade de CPU, RAM e armazenamento |
| Autoescalável | Criação e destruição automática de WorkSpaces conforme necessário |
| Integração com AD | Integra com Active Directory local ou na AWS |

#### Vantagens

  - Rápida implantação: Crie desktops virtuais em minutos.
  - Alta segurança: Dados não ficam armazenados localmente.
  - Flexível e escalável: Crie quantos WorkSpaces precisar e ajuste o tamanho com facilidade.
  - Sem necessidade de manutenção de hardware físico.

---

### AWS WAF (Web Application Firewall) 

É um serviço de firewall da AWS que protege aplicações web contra ameaças comuns da internet, como injeções SQL, scripts maliciosos (XSS), bots, ataques DDoS de camada 7, entre outros.

O AWS WAF permite criar regras personalizadas para filtrar, bloquear ou permitir o tráfego para suas aplicações web, protegendo-as de ataques e acessos indesejados.

#### Principais funcionalidades

| Recurso | Descrição |
|:------:|:------:|
| Regras personalizadas | Cria regras para bloquear ou permitir requisições com base em IP, headers, URI, etc. |
| Managed Rules da AWS | Conjuntos prontos de regras para proteção contra ameaças conhecidas (mantidas pela AWS ou parceiros) |
| Proteção contra bots | Detecta e bloqueia bots maliciosos automaticamente |
| Taxa de requisição (rate-based) | Bloqueia IPs que fazem muitas requisições em pouco tempo (rate limiting) |
| Geo blocking | Bloqueia ou permite acesso por localização geográfica |
| Integração com CloudFront, ALB e API Gateway | Funciona com serviços que expõem suas aplicações à web |

#### Vantagens

  - Segurança personalizável: Crie políticas de segurança adaptadas à sua aplicação.
  - Escalabilidade automática: Protege independentemente do volume de tráfego.
  - Baixa latência: Não impacta significativamente a performance da aplicação.
  - Relatórios e visibilidade: Integra com Amazon CloudWatch para monitoramento.

---

### Bring Your Own License (BYOL), ou Traga Sua Própria Licença

É um modelo de licenciamento que permite que você use licenças de software que já possui (de fornecedores como Microsoft, Oracle, etc.) na nuvem da AWS, sem precisar pagar novamente por uma nova licença.

O BYOL permite que você migre workloads para a AWS usando as licenças existentes, economizando custos e aproveitando os contratos já adquiridos com fornecedores.

#### Como funciona

  - Você já tem uma licença válida (por exemplo, do Windows Server ou do SQL Server).
  - Em vez de pagar por uma licença incluída na instância EC2 (modelo License Included), você usa a sua própria.
  - A AWS fornece opções específicas (como instâncias dedicadas ou hosts dedicados) que são compatíveis com BYOL.
  - Em alguns casos, você precisa informar à AWS que está usando o modelo BYOL para manter conformidade de uso.

#### Vantagens

| Vantagem | Descrição |
|:------:|:------:|
| Redução de custos | Evita pagar duas vezes pela mesma licença |
| Aproveitamento de contratos existentes | Usa acordos de licenciamento corporativo já firmados |
| Flexibilidade | Facilita a migração de workloads on-premises para a nuvem |
| Conformidade | Mantém licenças de forma legal e controlada |

---

### AWS CloudFormation 

É um serviço da AWS que permite criar, gerenciar e provisionar infraestrutura na nuvem usando código. Ele usa arquivos de template (em YAML ou JSON) para definir e provisionar recursos da AWS de forma automatizada e reprodutível.

O CloudFormation é a ferramenta de Infraestrutura como Código (IaC) da AWS. Com ele, você pode descrever toda a infraestrutura em arquivos de texto e a AWS monta tudo pra você automaticamente.

#### O que você pode fazer com CloudFormation

  - Criar instâncias EC2, VPCs, S3, RDS, IAM roles, etc.
  - Automatizar criação de ambientes de desenvolvimento, teste ou produção.
  - Gerenciar atualizações e rollback de recursos com segurança.
  - Reutilizar templates padronizados em múltiplas contas e regiões.

#### Vantagens

| Vantagem | Descrição |
|:------:|:------:|
| Automação completa | Sem necessidade de clicar no console: tudo por código |
| Consistência | Evita erros manuais e garante ambientes idênticos |
| Controle de versão | Templates versionáveis via Git ou qualquer controle de código |
| Rollback automático | Se algo der errado, ele desfaz as mudanças automaticamente |
| Integração com outros serviços | Pode ser usado junto com CI/CD, Lambda, CodePipeline etc. |

---

### AWS Artifact 

É um serviço da AWS que fornece acesso sob demanda a relatórios de conformidade, certificações e acordos legais relacionados à segurança e conformidade dos serviços da AWS.

O AWS Artifact é como a biblioteca de documentos de compliance da AWS — onde você encontra auditorias, certificações e termos legais para fins regulatórios, jurídicos e de segurança.

#### O que o AWS Artifact oferece

| Funcionalidade | Descrição |
|:------:|:------:|
| Artifact Reports | Acesso a relatórios de auditorias da AWS como SOC 1, SOC 2, ISO 27001, etc. |
| Artifact Agreements | Permite visualizar e aceitar acordos como o Business Associate Addendum (BAA) para HIPAA ou GDPR Addendum |
| Documentos atualizados | Sempre com versões recentes das certificações da AWS |
| Download simples e legalmente válido | Ideal para equipes de segurança, auditoria ou governança |

#### Vantagens

  - Acesso rápido a auditorias oficiais
  - Gratuito e disponível em todas as contas AWS
  - Facilita auditorias internas e externas
  - Ajuda a documentar conformidade ao migrar para a nuvem

---

### Amazon Inspector 

É um serviço da AWS que analisa automaticamente a segurança das suas instâncias EC2, containers (ECR) e workloads na nuvem, em busca de vulnerabilidades conhecidas e erros de configuração.

O Amazon Inspector é uma ferramenta de verificação de vulnerabilidades automatizada, que ajuda você a manter sua infraestrutura segura, identificando falhas antes que sejam exploradas.

#### O que ele faz

| Função | Descrição |
|:------:|:------:|
| Scan automático e contínuo | Verifica continuamente instâncias EC2, imagens de containers (ECR), Lambda etc. |
| Detecção de vulnerabilidades (CVEs) | Verifica se há falhas conhecidas no sistema operacional, pacotes e bibliotecas |
| Avaliação de risco | Atribui pontuação de risco (baseado no CVSS) para cada vulnerabilidade encontrada |
| Integração com AWS Organizations | Permite gerenciar contas múltiplas em grandes ambientes corporativos |
| Relatórios de segurança centralizados | Visualização dos achados no console e integração com CloudWatch ou SNS |

#### Vantagens

  - Automação
    - Não precisa escanear manualmente; o Inspector roda de forma contínua
  - Precisão
    - Usa banco de dados atualizado com CVEs conhecidos
  - Integração com outros serviços
    - Como ECR, Lambda, EC2, Security Hub, EventBridge
  - Redução de riscos
    - Identifica e ajuda a corrigir vulnerabilidades antes de um ataque

---

### AWS Security Hub 

É um serviço que centraliza e organiza alertas de segurança e verificações de conformidade de diversos serviços da AWS e parceiros, tudo em um painel único.

O Security Hub é a central de segurança da AWS, que coleta alertas de segurança de serviços como GuardDuty, Inspector, IAM Access Analyzer, e mostra tudo em um painel integrado, com recomendações de correção.

#### O que ele faz

| Função | Descrição |
|:------:|:------:|
| Agrega alertas (findings) | Coleta alertas de serviços como Amazon GuardDuty, Inspector, Macie etc. |
| Verificações de conformidade | Executa checagens com base em padrões como CIS AWS Foundations ou AWS Foundational Security Best Practices |
| Classificação de risco | Cada alerta recebe severidade (baixo, médio, alto, crítico) |
| Ações automatizadas | Integra com EventBridge, Lambda ou Step Functions para correção automática |
| Suporte a múltiplas contas | Pode coletar dados de segurança de várias contas AWS via AWS Organizations |

#### Vantagens

  - Visão centralizada
    - Um único lugar para ver alertas de segurança e conformidade
  - Redução de tempo de resposta
    - Automatiza ações quando problemas são detectados
  - Integração com parceiros
    - Suporta ferramentas de terceiros como Splunk, CrowdStrike, etc.
  - Melhoria contínua
    - Ajuda a manter as melhores práticas de segurança na nuvem da AWS

---

### Amazon GuardDuty 

É um serviço de detecção de ameaças da AWS que monitora continuamente sua conta e seus recursos em busca de atividades maliciosas ou comportamento suspeito.

O GuardDuty funciona como um sistema de alarme inteligente de segurança para sua conta AWS. Ele analisa logs automaticamente para encontrar indícios de ataques, invasões ou uso indevido.

#### O que ele analisa

| Fonte de dados | O que é analisado |
|:------:|:------:|
| CloudTrail | Ações feitas na conta, como criação de recursos ou alterações IAM |
| VPC Flow Logs | Tráfego de rede nas suas VPCs |
| DNS logs | Requisições DNS feitas pelos seus recursos |
| EKS audit logs | Logs de auditoria de clusters Kubernetes (EKS) |

#### Vantagens

  - Monitoramento contínuo
    - Sem necessidade de instalar agentes ou configurar regras complexas
  - Detecção baseada em ML
    - Usa machine learning e inteligência de ameaças para detectar riscos reais
  - Sem impacto na performance
    - Roda de forma independente dos seus recursos
  - Fácil integração
    - Integra com Security Hub, EventBridge, Lambda e sistemas de terceiros

---

### AWS Shield 

É um serviço gerenciado da AWS que protege aplicações contra ataques DDoS (Distributed Denial of Service), ou seja, ataques que tentam derrubar seu site ou sistema sobrecarregando-o com tráfego malicioso.

O AWS Shield protege seus recursos na AWS contra ataques DDoS, ajudando a manter seus serviços disponíveis e funcionando, mesmo sob ataque.

#### Tipos de AWS Shield

| Tipo | O que oferece |
|:------:|:------:|
| Shield Standard | Proteção automática gratuita contra ataques DDoS comuns para todos os clientes AWS |
| Shield Advanced | Proteção premium com mitigação avançada, suporte 24/7, e relatórios detalhados |

#### Shield Standard (grátis)

  - Ativado automaticamente para CloudFront, Route 53, Elastic Load Balancer (ELB) e Global Accelerator
  - Protege contra ataques de camada de rede mais comuns (ex: SYN flood, UDP flood)
  - Sem necessidade de configuração

#### Shield Advanced (pago)

Inclui tudo do Standard, mais:

| Funcionalidade | Benefício |
|:------:|:------:|
| Detecção e mitigação avançada | Resposta mais rápida e inteligente contra ataques sofisticados |
| Proteção contra custo de escala | Reembolso dos custos gerados por auto scaling em caso de ataque DDoS |
| Equipes de resposta da AWS (DDoS Response Team - DRT) | Suporte direto da AWS durante ataques |
| Relatórios e métricas detalhadas | Integra com CloudWatch e AWS Firewall Manager |
| Proteção para aplicações específicas | Pode proteger EC2, ELB, Elastic IPs, CloudFront, Route 53 etc. |

---

### AWS Config 

É um serviço que monitora, registra e avalia a configuração dos recursos da AWS ao longo do tempo. Ele permite que você veja quem mudou o quê, quando, e se aquilo está em conformidade com regras definidas.

O AWS Config funciona como uma caixa-preta de auditoria e conformidade para seus recursos na nuvem. Ele registra mudanças de configuração, verifica se estão de acordo com suas políticas de segurança ou governança, e ajuda em auditorias.

#### O que ele faz

| Função | Descrição |
|:------:|:------:|
| Rastreamento de mudanças | Detecta alterações em recursos da AWS (ex: alguém abriu um bucket S3) |
| Histórico completo | Armazena a linha do tempo de configurações de cada recurso |
| Avaliação de conformidade | Verifica se os recursos estão seguindo regras definidas |
| Integração com regras customizadas | Permite criar regras com Lambda ou usar regras gerenciadas pela AWS |

#### Vantagens

  - Visibilidade total
    - Entenda como seus recursos mudam com o tempo
  - Conformidade contínua
    - Detecta violações automaticamente
  - Auditoria simplificada
    - Histórico de quem mudou o quê, ideal para revisões de segurança
  - Automatização com Lambda
    - Pode reagir automaticamente a violações de regras

---

### AWS Knowledge Center 

É um repositório oficial de perguntas frequentes (FAQs) e artigos de ajuda mantido pela própria AWS. Ele serve como uma base de conhecimento técnica para tirar dúvidas comuns sobre serviços da nuvem AWS.

O AWS Knowledge Center é como um "pergunte aqui" oficial da AWS: você encontra respostas rápidas e práticas para problemas ou dúvidas comuns sobre os serviços da AWS.

#### O que você encontra lá

| Conteúdo | Descrição |
|:------:|:------:|
| Respostas para dúvidas comuns | "Como resetar senha do IAM?", "Por que meu EC2 não inicia?" |
| Guias de solução de problemas | Passo a passo para resolver erros específicos |
| Explicações técnicas | Diferença entre instâncias, criptografia, billing, etc. |
| Links para tutoriais e docs | Referência para documentação oficial e vídeos da AWS |

#### Vantagens

  - Respostas rápidas
    - Curto, direto ao ponto, ideal para problemas do dia a dia
  - Fonte confiável
    - Criado e mantido pela equipe da própria AWS
  - Fácil de buscar
    - Busca por palavra-chave ou por serviço
  - Complementa o suporte
    - Pode te ajudar antes mesmo de abrir um chamado na AWS Support

---

### AWS Database Migration Service (DMS) 

É um serviço gerenciado da AWS que facilita a migração de bancos de dados para a nuvem da AWS de forma rápida, segura e sem interrupção. Ele permite que você migre dados entre bancos de dados diferentes, sejam eles em um ambiente local, na AWS ou entre diferentes serviços de banco de dados da AWS.

O AWS DMS ajuda a migrar dados de forma simples e eficiente, com suporte a diferentes tipos de bancos de dados, como relacionais, NoSQL e data warehouses, sem a necessidade de parar suas aplicações durante o processo.

#### Como funciona

  - Fonte e Destino
    - Você define o banco de dados de origem (pode ser local ou na AWS) e o banco de dados de destino (geralmente um serviço AWS, como RDS, DynamoDB ou Redshift).
  - Configuração de migração
    - O DMS configura a migração de dados, mapeando as tabelas, registros e relacionamentos.
  - Execução da migração
    - O serviço copia os dados em tempo real, garantindo que as mudanças feitas na origem durante a migração sejam refletidas no destino. Esse processo pode ser feito de forma offline (apenas uma vez) ou em tempo real (com a replicação contínua).
  - Monitoramento e ajuste
    - Durante a migração, você pode acompanhar o progresso e garantir que tudo esteja ocorrendo corretamente.

#### Vantagens

  - Migrations sem downtime
    - A migração pode ser feita sem interromper as operações de banco de dados
  - Suporte a diferentes tipos de banco
    - Transfere dados entre diferentes tecnologias de banco de dados
  - Fácil de configurar
    - Configuração simples via console ou API da AWS
  - Replicação contínua
    - Permite replicação contínua de dados para sincronização em tempo real

---

### AWS Schema Conversion Tool (SCT) 

É uma ferramenta que ajuda na conversão de esquemas de banco de dados quando você migra entre diferentes tipos de banco de dados. A AWS SCT facilita a transição de bancos de dados de diferentes plataformas (por exemplo, de um banco de dados relacional como o Oracle para o Amazon Aurora ou Amazon RDS), convertendo o esquema (estruturas de tabelas, índices, procedures, etc.) e, em alguns casos, até mesmo o código-fonte (como funções ou triggers).

O AWS SCT converte o esquema de um banco de dados de uma tecnologia para outra, facilitando a migração de dados e mantendo a compatibilidade entre os dois sistemas.

#### Como funciona

  - Análise do banco de dados de origem
    - A ferramenta faz uma análise do esquema do banco de dados de origem e identifica os objetos de banco de dados como tabelas, índices, triggers, procedures, entre outros.
  - Conversão do esquema
    - O AWS SCT converte o esquema do banco de dados de origem para um banco de dados de destino (por exemplo, de Oracle para Amazon Aurora ou RDS).
  - Ajuste de código
    - Em alguns casos, pode ser necessário ajustar ou reescrever procedures, funções e triggers que não sejam compatíveis diretamente com o banco de dados de destino. O AWS SCT ajuda nesse processo, indicando as mudanças necessárias.
  - Exportação do esquema convertido
    - Depois da conversão, o esquema pode ser exportado para o banco de dados de destino, para que a migração de dados ocorra de maneira mais fluida.

#### Vantagens

  - Facilidade na migração
    - A AWS SCT facilita a transição entre diferentes tecnologias de banco de dados
  - Compatibilidade com código
    - Ajuda a adaptar funções, procedures e triggers entre plataformas de banco de dados
  - Reduz a complexidade
    - Automatiza a conversão do esquema, reduzindo a necessidade de refazer a estrutura manualmente
  - Suporte a diferentes fontes
    - Suporta bancos de dados amplamente utilizados como Oracle, SQL Server, MySQL e PostgreSQL

---

### Amazon EventBridge 

É um serviço gerenciado da AWS que facilita a criação de arquiteturas de eventos em tempo real. Ele permite que você conecte aplicações diferentes, sistemas ou serviços de uma forma desacoplada, reagindo automaticamente a eventos e realizando ações com base nesses eventos.

Ele é uma evolução do Amazon CloudWatch Events e fornece uma maneira mais poderosa e flexível de integrar e orquestrar sistemas e serviços na AWS ou fora dela, com suporte a eventos de aplicativos personalizados e eventos de terceiros.

O Amazon EventBridge permite que você construa aplicações reativas, em que eventos de diferentes fontes (como AWS, SaaS ou aplicativos personalizados) disparam ações em sistemas conectados. Ele ajuda a desacoplar os componentes de uma aplicação, tornando-a mais escalável e flexível.

#### Como funciona

  - Fonte de Evento
    - O EventBridge recebe eventos de diversas fontes (por exemplo, serviços AWS, aplicações personalizadas ou aplicativos SaaS).
  - Regras de Evento
    - Você cria regras para filtrar quais eventos de fontes específicas devem acionar quais ações.
  - Destinos
    - Quando um evento corresponde a uma regra, ele pode acionar destinos, como funções AWS Lambda, Amazon SNS, Amazon SQS, Step Functions, entre outros.

#### Vantagens

  - Desacoplamento de componentes
    - EventBridge permite que os componentes da aplicação sejam independentes, o que facilita escalabilidade e manutenção.
  - Suporte a múltiplas fontes de eventos
    - Pode integrar eventos de AWS, SaaS, e aplicações personalizadas em uma única plataforma.
  - Escalabilidade automática
    - O EventBridge lida com eventos de qualquer volume, permitindo que sua aplicação escale conforme necessário.
  - Facilidade de orquestração
    - Permite orquestrar fluxos de trabalho automatizados e respostas a eventos sem gerenciar infraestrutura adicional.

---

### AWS Budgets 

É um serviço da AWS que permite monitorar e controlar os custos e o uso dos recursos da AWS, ajudando a garantir que você não ultrapasse os limites orçamentários estabelecidos. Ele oferece uma maneira de definir orçamentos personalizados, receber alertas e tomar ações proativas quando os custos ou o uso se aproximam ou excedem os valores estabelecidos.

O AWS Budgets permite que você monitore seus gastos na AWS de maneira proativa, definindo orçamentos para diferentes serviços ou recursos e recebendo alertas quando o gasto ou o uso estiver prestes a ultrapassar os limites definidos.

#### Como funciona

  - Criação de orçamentos
    - Você define orçamentos personalizados para um ou mais serviços da AWS ou para o uso total da conta, podendo especificar valores mensais, trimestrais ou anuais.
  - Definição de metas de uso e custos
    - Ao criar um orçamento, você pode definir limites de custo e/ou de uso para diferentes serviços, como EC2, S3, RDS, etc.
  - Monitoramento e alertas
    - AWS Budgets monitora o uso e os custos em tempo real, comparando-os com os limites que você definiu. Quando os custos ou o uso se aproximam ou ultrapassam os valores configurados, você recebe alertas por e-mail ou SMS.
  - Relatórios e visibilidade
    - O serviço oferece relatórios detalhados sobre os custos e o uso para que você possa analisar o comportamento de consumo e tomar medidas corretivas.

#### Vantagens

  - Controle de custos
    - Monitore seus gastos de forma contínua, evitando surpresas no final do mês.
  - Alertas e notificações
    - Receba alertas via e-mail ou SMS quando os custos ou uso se aproximam do orçamento.
  - Personalização
    - Defina orçamentos por serviço, categoria ou usuário, de acordo com suas necessidades.
  - Visibilidade e relatórios
    - Obtenha relatórios detalhados sobre gastos históricos, previsões e tendências de uso.

---

### AWS Cost Explorer 

É uma ferramenta da AWS que permite visualizar, analisar e gerenciar os custos e o uso dos serviços da AWS ao longo do tempo. Ele fornece relatórios detalhados e gráficos interativos para ajudar a entender como os recursos estão sendo utilizados e onde estão ocorrendo os gastos. Isso facilita a identificação de padrões de custo, o que é crucial para otimizar os gastos na AWS.

O AWS Cost Explorer ajuda a visualizar e analisar os custos da AWS de maneira interativa, permitindo que você monitore e otimize seus gastos, identifique tendências de consumo e tome decisões mais informadas sobre o uso de recursos.

#### Funcionalidades principais

  - Análise de custo e uso
    - O Cost Explorer permite ver detalhes sobre o custo de cada serviço, como EC2, S3, RDS, entre outros. Você pode filtrar por tipo de serviço, conta, tags ou tempo.
  - Relatórios interativos
    - O Cost Explorer permite criar relatórios personalizados com base em suas necessidades. Você pode analisar custos em períodos diários, mensais ou até mesmo por hora.
  - Gráficos e visualizações
    - Os relatórios podem ser visualizados de forma gráfica, o que facilita a compreensão de tendências de gastos e o comportamento do consumo ao longo do tempo.
  - Previsão de custos futuros
    - Ele pode fornecer previsões baseadas em gastos passados, ajudando a antecipar custos para o próximo mês ou trimestre.
  - Filtragem por tags
    - Se você usa tags para identificar e categorizar seus recursos (por exemplo, por projeto, departamento ou equipe), pode filtrar e ver os custos associados a essas tags, permitindo um controle mais granular.
  - Cost Anomaly Detection
    - Detecta anomalias de custo de maneira proativa, notificando quando os custos de um serviço ou recurso estão fora do esperado.

#### Vantagens

  - Visualização detalhada
    - Permite visualizar custos detalhados por serviço, região ou conta
  - Otimização de custos
    - Ajuda a identificar padrões e tendências para otimizar os gastos.
  - Previsões de gastos
    - Fornece previsões baseadas em custos históricos, ajudando no planejamento financeiro.
  - Filtros e tags
    - Possibilita a filtragem por tags, facilitando o gerenciamento de custos por projeto ou equipe.

---

### Amazon Athena 

É um serviço de análise interativa de dados na AWS que permite consultar dados diretamente em Amazon S3 usando SQL padrão, sem a necessidade de mover ou carregar os dados para um banco de dados. É uma solução serverless (sem servidor), o que significa que você não precisa gerenciar infraestrutura ou se preocupar com provisionamento de recursos, e paga apenas pelas consultas realizada.

Amazon Athena é um serviço que permite executar consultas SQL diretamente sobre dados armazenados no S3, sem a necessidade de configurar servidores ou bancos de dados. Ele é ideal para análise de grandes volumes de dados, especialmente dados não estruturados ou semiestruturados, como logs ou arquivos CSV.

#### O que ele faz

  - Consultas SQL sobre dados no S3
    - Você pode consultar dados em formatos como CSV, JSON, Parquet, ORC, Avro, entre outros, armazenados no S3 diretamente com SQL.
  - Serverless (sem servidor)
    - O Athena não exige que você configure ou gerencie servidores, tornando-o uma solução serverless. Isso reduz a complexidade de manutenção.
  - Escalabilidade automática
    - O serviço escala automaticamente para lidar com grandes volumes de dados, sem a necessidade de configuração adicional.
  - Integração com outras ferramentas AWS
    - Athena se integra bem com AWS Glue para catalogação de dados e AWS QuickSight para visualização de resultados. Você também pode usar o AWS Lambda para automação e integração com outros serviços.
  - Consulta de dados sem transformação
    - Não é necessário mover ou transformar os dados antes da consulta, já que você pode consultar diretamente arquivos armazenados no S3.
  - Suporte a formatos de dados otimizados
    - Athena é compatível com formatos de dados otimizados para consultas rápidas, como Parquet e ORC, o que reduz o custo de consulta e melhora a performance.

#### Vantagens

  - Serverless
    - Sem necessidade de gerenciamento de infraestrutura ou servidores.
  - Consultas rápidas
    - Execute consultas SQL rápidas em grandes volumes de dados.
  - Custo sob demanda
    - Paga-se apenas pelo volume de dados lido nas consultas, o que pode ser muito econômico.
  - Facilidade de integração
    - Integra-se com diversos serviços AWS como Glue, QuickSight, Lambda.
  - Suporte a vários formatos de dados
    - Suporta diversos formatos, incluindo CSV, JSON, Parquet, Avro, entre outros.

---

### Amazon EMR (Elastic MapReduce) 

É um serviço da AWS que facilita o processamento de grandes volumes de dados usando frameworks de código aberto, como Apache Hadoop, Apache Spark, Apache Hive, HBase, entre outros. Ele permite que você crie e gerencie clusters para processar dados de maneira escalável e eficiente, sem a necessidade de gerenciar a infraestrutura subjacente.

Amazon EMR é uma solução gerenciada para processamento de grandes volumes de dados usando frameworks como Hadoop e Spark na AWS, oferecendo escalabilidade e facilidade de uso, sem a necessidade de gerenciamento de infraestrutura.

#### O que ele faz

  - Processamento distribuído de dados
    - O EMR usa frameworks como Hadoop e Spark para dividir grandes volumes de dados e processá-los de forma paralela, distribuída, o que melhora a performance e escalabilidade do processamento.
  - Escalabilidade
    - O Amazon EMR permite que você escalone automaticamente a capacidade de processamento (número de nós) conforme necessário, permitindo que você lide com grandes volumes de dados sem se preocupar com limitações de capacidade.
  - Integração com outros serviços AWS
    - O EMR se integra com serviços como Amazon S3 (para armazenar dados), Amazon RDS, Redshift, AWS Glue, e Amazon DynamoDB, o que facilita o fluxo de dados entre serviços da AWS e amplia as possibilidades de análise e processamento.
  - Suporte a frameworks de Big Data
    - EMR oferece suporte a frameworks populares como Hadoop, Spark, Hive, HBase, Presto, Flink, entre outros, permitindo que você utilize a melhor tecnologia para o seu caso de uso.
  - Gerenciamento simplificado
    - O serviço é gerenciado, o que significa que a AWS cuida da infraestrutura, como a provisão de servidores, manutenção, e configuração do cluster, facilitando a operação do seu processamento de dados.
  - Economia de custos
    - Você paga apenas pelos recursos que usa. Além disso, o EMR suporta o uso de instâncias spot, que podem reduzir significativamente os custos de execução, aproveitando a capacidade não utilizada da AWS.

#### Vantagens

  - Gerenciamento automatizado
    - A AWS gerencia a infraestrutura e a configuração dos clusters EMR, permitindo que você foque no processamento de dados.
  - Escalabilidade
    - Você pode escalonar seus clusters de acordo com a demanda de processamento, adicionando ou removendo nós conforme necessário.
  - Facilidade de integração
    - O EMR se integra perfeitamente com diversos serviços AWS, como S3, DynamoDB, Redshift, entre outros.
  - Suporte a múltiplos frameworks
    - Suporta Hadoop, Spark, Hive, HBase e outros frameworks populares para processamento de grandes volumes de dados.
  - Custo sob demanda
    - Paga-se apenas pelos recursos utilizados, com a possibilidade de usar instâncias spot para reduzir custos.

---

### AWS Elastic Beanstalk 

É um serviço PaaS (Plataform as a Service) da Amazon Web Services que permite implantar e gerenciar aplicações web de forma automática e simplificada, sem se preocupar com a infraestrutura subjacente (como servidores, balanceadores, escalabilidade ou monitoramento).

Elastic Beanstalk é um serviço que implanta, gerencia e escala automaticamente sua aplicação web ou API, bastando você enviar seu código. Ele cuida da infraestrutura por trás disso (EC2, ELB, Auto Scaling, etc.).

#### Tecnologias suportadas

  - Plataformas
    - Java, .NET, Node.js, PHP, Python, Ruby, Go, Docker.
  - Servidores de aplicação
    - Apache, Nginx, Passenger, IIS, Tomcat.
  - Ambientes personalizados
    - Também é possível usar Docker ou criar AMIs customizadas.

#### Custo

O Elastic Beanstalk não tem custo adicional. Você paga apenas pelos recursos que ele usa, como:

  - EC2 (máquinas virtuais)
  - RDS (banco de dados, se usado)
  - ELB (load balancer)
  - S3 (armazenamento)

#### Vantagens

| Vantagem | Descrição |
|:------:|:------:|
| Implantação rápida | Basta fazer upload do código — sem configurar servidores manualmente. |
| Gerenciado pela AWS | A AWS cuida da infraestrutura, patches, balanceamento e escalonamento. |
| Suporte a várias linguagens | Suporta múltiplas plataformas (Java, Node.js, Python, PHP, etc.). |
| Escalabilidade automática | Escala horizontalmente de forma automática com base na demanda. |
| Integração com outros serviços AWS | Integra facilmente com S3, RDS, CloudWatch, IAM, entre outros. |
| Customização | É possível customizar o ambiente, se necessário (por ex., mudar o tipo de instância EC2). |

---

### AWS CloudHSM 

É um serviço da Amazon Web Services que fornece módulos de segurança de hardware (HSMs) dedicados na nuvem para você gerar, armazenar e gerenciar chaves criptográficas com alto nível de segurança.

Um HSM (Hardware Security Module) é um dispositivo físico projetado para:

  - Gerar chaves criptográficas com segurança.
  - Armazenar chaves protegidas contra acesso não autorizado.
  - Realizar operações de criptografia e descriptografia com alto desempenho.

#### O que ele faz

| Recurso | Descrição |
|:------:|:------:|
| HSM dedicado | Você recebe um HSM físico dedicado a você (não é compartilhado). |
| FIPS 140-2 nível 3 | Certificação de segurança reconhecida para uso governamental e financeiro. |
| Controle total da chave | Só você tem acesso e controle sobre as chaves armazenadas. |
| Alta disponibilidade | Pode ser implantado em múltiplas zonas para tolerância a falhas. |
| Integração com apps | Integra com aplicações via APIs como PKCS#11, Java JCE e Microsoft CNG. |

---

### AWS Detective 

É um serviço de análise e investigação de segurança que ajuda você a identificar, entender e resolver possíveis problemas ou incidentes de segurança em sua conta da AWS.

O AWS Detective coleta automaticamente dados de atividades e redes da AWS e os analisa para ajudar na investigação de ameaças ou comportamentos suspeitos.

#### O que ele faz

  - Coleta de dados
    - Ele coleta logs do AWS CloudTrail, VPC Flow Logs e Amazon GuardDuty.
  - Análise automática
    - Usa machine learning, análise estatística e gráficos para encontrar padrões e relações entre eventos.
  - Visualizações interativas
    - Apresenta gráficos, timelines e relacionamentos entre recursos para facilitar a investigação.
  - Ajuda na resposta a incidentes
    - Permite que equipes de segurança investiguem comprometimentos, acessos não autorizados ou anomalias.

#### Vantagens

| Vantagem | Descrição |
|:------:|:------:|
| Automatiza coleta de dados | Elimina trabalho manual com logs de várias fontes. |
| Visualização clara | Exibe relações entre recursos e eventos de forma gráfica. |
| Ajuda a detectar anomalias | Identifica comportamentos fora do padrão automaticamente. |
| Integração com GuardDuty | Investiga facilmente alertas do GuardDuty com mais contexto. |

---

### Amazon Macie 

É um serviço da AWS que usa inteligência artificial para descobrir, classificar e proteger dados sensíveis armazenados no Amazon S3, como:

  - Números de CPF, cartão de crédito, RG
  - Dados pessoais identificáveis (PII)
  - Dados financeiros ou de saúde

O Amazon Macie ajuda você a detectar e proteger dados confidenciais automaticamente dentro dos seus buckets do S3, usando machine learning.

#### O que ele faz

| Recurso | Descrição |
|:------:|:------:|
| Descoberta de dados sensíveis | Verifica arquivos nos buckets S3 e identifica informações confidenciais. |
| Classificação automática | Categoriza os dados encontrados com base no tipo (PII, financeiro etc.). |
| Alertas de risco | Gera alertas se detectar dados sensíveis armazenados de forma insegura. |
| Relatórios detalhados | Exibe onde estão os dados sensíveis e se há permissões públicas. |
| Integração com Security Hub |	Envia achados automaticamente para consolidação com outros alertas. |

#### Vantagens

| Vantagem | Descrição |
|:------:|:------:|
| Automático e inteligente | Usa machine learning para aprender os padrões de dados sensíveis. |
| Alta escalabilidade | Funciona com grandes volumes de dados no S3. |
| Fácil de usar | Basta ativar e configurar um escaneamento. |
| Foco em segurança | Ajuda a evitar violações de dados e falhas de conformidade. |

---

### AWS Compute Optimizer 

É um serviço que usa machine learning para analisar o uso dos seus recursos de computação (como EC2, Lambda, EBS, ECS) e recomendar ajustes automáticos para melhorar performance e custo.

O Compute Optimizer ajuda você a dimensionar corretamente seus recursos, evitando que você pague por instâncias subutilizadas ou tenha desempenho abaixo do ideal.

#### O que ele faz

| Recurso | Recomendações que pode fazer |
|:------:|:------:|
| EC2 Instances | Tipo e tamanho ideais (ex: trocar t3.medium por t3a.small). |
| EBS Volumes | Tipo de volume mais eficiente. |
| Lambda Functions | Melhorar a configuração de memória e tempo de execução. |
| Auto Scaling Groups | Ajuste no tamanho mínimo/máximo e tipo de instância. |
| ECS com Fargate | Recomenda CPU/memória mais apropriada. |

#### Vantagens

  - Economia de custos
    - reduz desperdício de recursos.
  - Melhoria de performance
    - evita sobrecarga e lentidão.
  - Recomendações inteligentes
    - baseadas em dados reais de uso.
  - Fácil de usar
    - basta ativar e ele começa a gerar sugestões.

---

### AWS Resource Explorer 

É um serviço da AWS que permite procurar e visualizar recursos da nuvem (como EC2, S3, Lambda, RDS, etc.) de forma rápida e centralizada, mesmo em múltiplas regiões.

O AWS Resource Explorer é como um "buscador de recursos" da AWS — você digita o nome ou tipo de recurso e ele encontra onde está, sem precisar procurar manualmente.

#### Principais funcionalidades

| Função | O que faz |
|:------:|:------:|
| Busca rápida | Localiza recursos por nome, tipo, tag ou ID. |
| Busca multi-região | Permite buscar recursos em todas as regiões da conta. |
| Interface simples | A busca funciona como uma "barra de pesquisa" do console. |
| Filtros por tipo/tags | Você pode refinar os resultados por tipo ou metadados. |

#### Vantagens

  - Ganha tempo
    - sem precisar entrar em cada serviço e região manualmente.
  - Visão unificada
    - útil para ambientes com muitos recursos e contas.
  - Gratuito
    - sem custo extra para uso.

---

### Amazon QuickSight 

É um serviço da AWS de Business Intelligence (BI) que permite criar painéis interativos, relatórios e visualizações de dados diretamente na nuvem.

O QuickSight ajuda você a transformar dados brutos em gráficos e dashboards interativos, para que seja possível tomar decisões com base em dados, de forma rápida e escalável.

#### Principais recursos

| Recurso | O que faz |
|:------:|:------:|
| Dashboards interativos | Crie visualizações como gráficos, tabelas e mapas com poucos cliques. |
| Análises automáticas (ML Insights) | Detecta padrões, anomalias e tendências nos dados. |
| SPICE Engine | Motor interno de alta performance para análises em tempo real. |
| Integração com dados da AWS | Conecta com S3, Redshift, RDS, Athena, entre outros. |
| Compartilhamento fácil | Publique dashboards com controle de acesso (IAM ou ACL). |
| BI embutido (Embedded BI) | Permite incorporar visualizações em seus próprios apps ou portais. |

#### Vantagens

  - Escalável e serverless
    - sem precisar provisionar infraestrutura.
  - Pagou pelo uso
    - cobra por usuário e uso, com versão gratuita para testes.
  - Segurança integrada com IAM, criptografia e logs.
  - Fácil integração com fontes internas e externas de dados.

---

### AWS Support 

É o serviço de suporte técnico e consultivo da Amazon Web Services, que oferece ajuda para resolver problemas técnicos, tirar dúvidas, planejar soluções e otimizar custos na nuvem AWS.

#### O que ele oferece

| Tipo de ajuda | Exemplos práticos |
|:------:|:------:|
| Suporte técnico | Resolver erro em instância EC2, problemas com S3, etc. |
| Recomendações de arquitetura | Melhorar segurança, escalabilidade ou performance. |
| Otimização de custos | Análise de uso e sugestões para economizar. |
| Ferramentas automáticas | Trusted Advisor, Health Dashboard, etc. |

#### Planos de suporte disponíveis

| Plano | Ideal para... | O que inclui |
|:------:|:------:|:------:|
| Basic | Todos os clientes AWS (grátis) | Documentação, fóruns e suporte ao faturamento. |
| Developer | Equipes em teste/desenvolvimento | Acesso a engenheiros via e-mail, horário comercial. |
| Business | Produção em ambientes críticos | Suporte 24/7, prioridade alta, Trusted Advisor completo. |
| Enterprise | Grandes empresas e missão crítica | Gerente Técnico Designado (TAM), tempo de resposta prioritário. |

---

### AWS Professional Services 

É um time de consultores especializados da própria AWS que ajuda empresas a planejar, implementar e adotar soluções em nuvem de forma mais rápida e eficaz.

É como contratar especialistas da própria AWS para te ajudar a executar projetos complexos ou estratégicos com boas práticas e segurança.

#### O que eles fazem

| Serviço | O que significa na prática |
|:------:|:------:|
| Consultoria técnica | Ajuda a arquitetar e migrar sistemas para a AWS. |
| Transformação digital | Apoia mudanças culturais, processos e adoção de nuvem. |
| Projetos complexos | Suporte em soluções como data lakes, machine learning, etc. |
| Treinamento e capacitação | Trabalham junto com sua equipe para repassar conhecimento. |
| Boas práticas e compliance | Garantem que tudo esteja seguro, escalável e bem projetado. |

#### Quando usar o AWS Professional Services

  - Vai migrar um sistema legado grande e crítico para a AWS.
  - Precisa acelerar um projeto estratégico (como IA, Big Data).
  - Quer garantir uma arquitetura segura, escalável e resiliente.
  - Deseja criar uma cultura de DevOps e modernização.

---

### AWS Launch Wizard 

É um serviço da AWS que guia você passo a passo para implantar aplicações complexas (como SAP, SQL Server, Active Directory, etc.) na nuvem, de forma automatizada e com boas práticas.

O AWS Launch Wizard é como um "assistente de instalação" que ajuda você a criar toda a infraestrutura necessária para uma aplicação com poucos cliques.

#### O que ele faz

| Função | Explicação |
|:------:|:------:|
| Implantação guiada (wizard) | Interface simples que guia a criação do ambiente. |
| Infraestrutura automática | Cria VPC, instâncias EC2, volumes EBS, bancos de dados, etc. |
| Ajustes de performance/custo | Você escolhe entre diferentes tamanhos e configurações. |
| Boas práticas da AWS | Arquiteturas recomendadas e seguras são seguidas automaticamente. |
| Suporte a aplicações específicas | SAP, SQL Server, AD, Exchange, entre outras. |

#### Vantagens

  - Reduz erros de configuração.
  - Economiza tempo em projetos complexos.
  - Garante conformidade com arquiteturas testadas.
  - Não cobra pelo uso — você paga apenas pelos recursos criados.

---

### Amazon Personalize 

É um serviço da AWS que permite criar sistemas de recomendação personalizados com inteligência artificial (IA), do mesmo tipo que a Amazon.com usa para sugerir produtos.

O Amazon Personalize permite que você adicione recomendações inteligentes em tempo real no seu app, site ou e-commerce — sem precisar ser especialista em machine learning.

#### O que ele faz

| Função | Exemplo prático |
|:------:|:------:|
| Recomendações de produtos | "Produtos que você pode gostar" |
| Listas personalizadas | "Filmes recomendados para você" |
| Previsão de comportamento | "Usuários que provavelmente cancelarão" |
| Ranking personalizado | Ordenar itens com base no perfil do usuário |

#### Vantagens

  - Pronto para uso: não precisa saber programar IA.
  - Em tempo real: recomendações atualizadas conforme o comportamento do usuário.
  - Altamente personalizável.
  - Escalável e seguro.

---

### AWS DataSync 

É um serviço gerenciado que permite mover dados rapidamente e com segurança entre armazenamento local (on-premises) e serviços da AWS, como Amazon S3, EFS, FSx e até entre regiões da AWS.

O DataSync automatiza e acelera a transferência de grandes volumes de dados, com recursos de verificação, compressão e criptografia.

#### Vantagens

  - Até 10× mais rápido que ferramentas de cópia tradicionais (como rsync).
  - Verificação automática de integridade dos dados.
  - Criptografia em trânsito.
  - Integração com CloudWatch e EventBridge.
  - Suporta cron jobs para sincronizações periódicas.

---

### AWS Audit Manager 

É um serviço da AWS que ajuda você a automatizar a coleta de evidências para auditorias de conformidade e segurança.

O Audit Manager facilita o trabalho de auditorias e certificações, como ISO 27001, PCI-DSS, GDPR, SOC 2, etc., coletando automaticamente as evidências exigidas diretamente dos serviços da AWS.

#### O que ele faz

| Função | Explicação |
|:------:|:------:|
| Automatiza coleta de evidências | Captura logs, configurações e atividades dos serviços da AWS. |
| Modelos de conformidade prontos | Já vem com frameworks como ISO, PCI, HIPAA, entre outros. |
| Geração de relatórios | Cria relatórios organizados para auditores e equipes de compliance. |
| Mapeamento de controles | Relaciona serviços e configurações com controles específicos da auditoria. |

#### Vantagens

  - Reduz esforço manual em auditorias.
  - Evita esquecimentos ou falhas humanas na coleta de evidências.
  - Melhora a segurança e conformidade contínua.
  - Facilita a preparação para certificações e revisões regulatórias.

---

### AWS CloudTrail 

É o serviço que registra todas as ações realizadas na sua conta AWS — quem fez, o que fez, quando, de onde e em qual recurso.

#### O que ele faz

  - Auditoria e rastreabilidade
    - grava eventos de API (console, CLI, SDK, serviços).
  - Detecção de incidentes
    - integra-se com CloudWatch Logs/Events, Security Hub, GuardDuty.
  - Compliance
    - fornece trilha de auditoria para normas como ISO 27001, PCI-DSS, LGPD/GDPR.
  - Investigação forense
    - permite saber “quem deletou aquela instância S3 ontem às 14h?”.

#### Vantagens

  - Visibilidade completa
    - Saber o histórico de chamadas de API.
  - Segurança
    - Investigar acessos suspeitos ou não autorizados.
  - Automação
    - Disparar ações (ex.: bloquear IP) usando EventBridge/CloudWatch Events.
  - Custo baixo
    - Paga-se só por Data Events/Insights; Management events são gratuitos para gravação em S3.

---

### AWS License Manager 

É um serviço que ajuda você a controlar, rastrear e aplicar o uso de licenças de software (Microsoft, Oracle, SAP, SUSE, etc.) dentro dos ambientes AWS (e on-premises, se integrado).

#### Para que serve

| Problema | Como o License Manager ajuda |
|:------:|:------:|
| Excesso ou falta de licenças | Define limites de CPUs, sockets, vCPUs ou instâncias e gera alertas/impede lançamentos que excedam. |
| Inventário disperso | Descobre automaticamente instâncias EC2, hosts dedicados, VMware-vCenter (via agente) e mapeia quais licenças estão em uso. |
| Auditoria e compliance | Relatórios unificados sobre quem está usando qual licença, por quanto tempo e em que região/conta. |
| Otimização de custos | Permite estratégia Bring-Your-Own-License (BYOL) com controle central e evita pagar por licenças desnecessárias. |

#### Vantagens

  - Governança centralizada de licenças BYOL e Marketplace.
  - Reduz risco de multas por não-conformidade.
  - Visibilidade multi-conta e multi-região.
  - Sem custo adicional: você paga apenas pelos recursos subjacentes (EC2, etc.).

---

### AWS Certificate Manager (ACM) 

É o serviço da AWS que emite, gerencia e renova automaticamente certificados SSL/TLS para proteger domínios, APIs e aplicações na nuvem — sem precisar lidar com processos manuais de criação de CSR, validação e instalação.

#### Por que usar 

  - Emissão grátis de certificados públicos para domínios que você possui.
  - Renovação automática (evita expiração acidental).
  - Integração nativa com Elastic Load Balancer, CloudFront, API Gateway, App Runner, etc.
  - Suporte a certificados privados via ACM Private CA (autoridade certificadora privada gerenciada).
  - Importação de certificados de terceiros, se já possuir.

---

### Amazon Forecast 

É um serviço da AWS que usa machine learning para gerar previsões (forecasting) de séries temporais — vendas, demanda, tráfego, estoque, temperatura, etc. Ele aproveita a mesma tecnologia que a Amazon utiliza internamente para prever demanda em seu e-commerce, mas empacotado como serviço gerenciado.

#### Vantagens

| Vantagem | Por quê importa |
|:------:|:------:|
| Sem expertise em ML | Todo o tuning de modelos é automático. |
| Alta precisão | Combina vários algoritmos e escolhe o melhor por série. |
| Explicabilidade | Relatórios de importância de variáveis e métricas de erro. |
| Escalável | Processa de poucas a milhares de séries em paralelo. |
| Integração fácil | S3 para dados, SDK/CLI para chamadas, exporta para Redshift, QuickSight, etc. |

---

### AWS Application Discovery Service 

É um serviço que ajuda empresas a planejar migrações para a nuvem, identificando automaticamente quais aplicações e servidores estão rodando no seu ambiente local (on-premises).

O AWS Application Discovery Service coleta informações sobre ambientes locais (on-premises) para ajudar no planejamento e execução de migrações para a nuvem, identificando servidores, aplicações e suas dependências.

#### O que ele faz

Ele coleta dados detalhados sobre sua infraestrutura local, como:

  - Quais aplicações estão rodando.
  - Quais servidores físicos ou virtuais estão sendo usados.
  - Uso de CPU, memória, rede e armazenamento.
  - Dependências entre aplicações (por exemplo, um servidor web que se conecta a um banco de dados).

Essas informações ajudam a planejar a migração para a AWS de forma mais eficiente e segura.

---

### AWS Application Migration Service (MGN) 

É um serviço da AWS que permite migrar servidores físicos, virtuais ou em outras nuvens para a AWS de forma automática, rápida e com interrupção mínima.

#### O que ele faz

Ele copia e converte automaticamente seus servidores on-premises, VMware, Hyper-V ou de outras nuvens para máquinas virtuais na AWS (instâncias EC2), mantendo:

  - Sistema operacional
  - Aplicações
  - Dados
  - Configurações

Tudo isso com replicação contínua, o que permite realizar testes e cortar para o ambiente na AWS com o mínimo de downtime.

---

### AWS Key Management Service (KMS) 

É um serviço gerenciado da AWS que permite criar, armazenar e controlar chaves de criptografia usadas para proteger seus dados.

#### O que ele faz

  - Cria e gerencia chaves criptográficas (CMKs) usadas para criptografar dados em repouso e em trânsito.
  - Integra-se com outros serviços da AWS, como S3, EBS, RDS, Lambda, etc., permitindo criptografia automática de dados.
  - Permite controle de acesso detalhado às chaves com o IAM.
  - Suporta auditoria via AWS CloudTrail, registrando quem usou as chaves e quando.

---

## Dicas Finais

- Revise os conceitos, não decore.
- Faça simulados com foco em entender o **porquê da resposta**.
- Use analogias do dia a dia para entender serviços.
- Mantenha a calma no exame — é introdutório!

---

## Contribua

Achou um recurso legal? Melhoraria algum trecho? Sinta-se à vontade para abrir um PR ou criar uma issue!

---

## Contato

Caso tenha dúvidas ou queira trocar ideias, me chama no [Instagram](https://www.instagram.com/frontend_clean/).

---

**Bons estudos e boa sorte na prova!**