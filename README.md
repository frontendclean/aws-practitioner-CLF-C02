# Guia para o AWS Certified Cloud Practitioner (CLF-C02)

![Tela inicial](./assets/img/practitioner.png)

Este repositório foi criado para ajudar quem está se preparando para a certificação **AWS Certified Cloud Practitioner**. O foco é compartilhar **recursos gratuitos**, **explicações simples** e **dicas práticas** para quem está começando na nuvem AWS.

## 🎯 O que é a certificação Cloud Practitioner?

A certificação **Cloud Practitioner** é a porta de entrada para o mundo AWS. Ela é ideal para iniciantes e valida conhecimentos básicos sobre:
- Conceitos de nuvem
- Serviços principais da AWS
- Segurança e conformidade
- Preços e suporte

---

## 📚 Recursos de Estudo

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

## 🧠 O que estudar (resumo dos tópicos)

### Menu 

- [Cloud computing](#cloud-computing)
- [AWS Identity and Access Management (IAM)](#aws-identity-and-access-management-iam)
- [IAM Identity Center](#iam-identity-center)
- [AWS Organizations](#️aws-organizations)

### ☁️ Cloud computing

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


### ☁️ AWS Identity and Access Management (IAM) 

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

### ☁️ IAM Identity Center

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

### ☁️ AWS Organizations

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

## 💡 Dicas Finais

- Revise os conceitos, não decore.
- Faça simulados com foco em entender o **porquê da resposta**.
- Use analogias do dia a dia para entender serviços.
- Mantenha a calma no exame — é introdutório!

---

## ✍️ Contribua

Achou um recurso legal? Melhoraria algum trecho? Sinta-se à vontade para abrir um PR ou criar uma issue!

---

## 📩 Contato

Caso tenha dúvidas ou queira trocar ideias, me chama no [Instagram](https://www.instagram.com/frontend_clean/).

---

🧠 **Bons estudos e boa sorte na prova!**