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
- [AWS Account](#aws-account)
- [AWS Free Tier](#aws-free-tier)
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

É so conjunto de ofertas “gratuitas” que a Amazon Web Services disponibiliza para quem criar (ou já tem) uma conta. Ele serve para testar e aprender sem pagar — desde que você fique dentro de certos limites

#### Existem três tipos de oferta

  - Gratuito por 12 meses
    > Começa na data em que você abre a conta e dura um ano.
  - Gratuito sempre (sempre que usar)
    > Recursos que permanecem grátis enquanto você se mantiver nos limites, mesmo depois de 12 meses.
  - Test‑drive pontual (trials)
    > Ofertas de curta duração (30, 60 ou 90 dias) que começam quando você ativa o serviço.

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
    > Pessoas ou serviços com permissões definidas (por exemplo, “pode acessar apenas o S3”).
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

#### Como funciona

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