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

<a href="https://aws.amazon.com/pt/ec2/instance-types/" target="_blank" rel="noopener noreferrer">
  documentação completa da aws
</a>

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