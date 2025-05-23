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

---

## O que estudar (resumo dos tópicos)

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