# Informações básicas para desenvolvedores

## Infraestrutura

### Local

Entenda que sua infraestrutura local é basicamente o seus "pertences" de uso pessoal - como sua escova de dente, toalha, roupa de baixo. Uma toalha ou roupa de baixo, desde que você tenha confiança e intimidade, pode até ser usada por outra pessoa - mas com certeza você vai se precaver de manter aquele pertece higienizado, livre de problemas, para que você volte a usa-lo.

Como é seu, você faz o que quer e, portanto pode ser que algo que funcionava de uma forma deixe de funcionar devido a mudanças no ambiente - por exemplo um aplicativo não deveria mas pode impactar a forma que outro aplicativo funciona.

### Conteineres

Podemos pensar como um hotel que você vai usar - você tem que levar tudo que vai precisar e precisa se lembrar de que se deixar algo lá pode se perder. O que você grava em um conteiner, a partir do momento que você o perca, se perderá também. A ideia é poder repetir algo da mesma forma tantas vezes quanto se queira se que nada mude.

### Na nuvem

Podemos pensar como um hotel de luxo - você pede e lá está o que você precisa. Lá tem uma prateleira quase infinita de opções a sua disposição. Quantos processadores? Quanta memória? Que tipo de disco? É só escolher. Novamente, lembre-se que até você pode alugar por tempo indeterminado mas no final nada ali te pertence.

#### AWS

Glossário:

 * EC2 - uma intância com CPU, memória, disco e todos os recursos para se hospedar uma solução.
 * Conteiner service - Kubernetes vendido como serviço
 * Elastic Beanstalk - faz deploy e escalonamento de aplicações web e de serviços.
 * Lambda - permite rodar código como serviço vinculando a eventos de outros serviços da AWS.
 * ELB (Elastic Load Balancing) - distibui requisições para um grupo de hosts que oferecem um serviço como uma API, aplicação web, Solr, etc.
 * S3 (Simple Storage Service) - oferece unidades de armazenamento com serviço.
 * ELB (Elastic Block Store) - oferece unidades de armazenamento persistentes que podem ser vinculados a um EC2.
 * Glacier - similar ao S3 mas usado para armazenar dados que não são usados com frequência - backup, por exemplo.
 * Aurora - database relacionais como serviço que oferece MySQL e PostgreSQL engines turbinadas, 5x e 3x repectivamente.
 * RDS (Relational Database Service) - database como serviço com custo/benefício razoável - AWS cuida da infraestrutura.
 * DynamoDB - database de chave/valor vendido como serviço. Escalável e muito barato ou muito caro dependendo do uso.
 * ElastiCache - serviço de cache que traz Redis e Memcached como engine. Database de chave e valor.
 * Redshift - solução de warehouse como serviço.
 * VPC (Virtual Private Cloud) - permite criar redes privadas virtuais para isolar logicamente seus serviços.
 * CloudFront - uma CDN (Content Delivery Network) com serviço. Podemos pensar como um cache para suas aplicações.
 * Route 53 - DNS (Domain Name System) como serviço. Ao invés de usar IP, use www.meusite.com.br para seu acesso.
 * API Gateway - permite criar, publicar, manter API de forma escalável. Age como a porta da frete de sua API.
 * CloudWatch - serviço de monitoramento e gerenciamento dos serviços da AWS.
 * Cloud​Formation - infraestrutura como código - você define o que e como e ele cria para você o que precisar. Disaster recovery
 * CLI (Command Line Interface) - uma interface em linha de comando para os serviços da AWS.
 * Machine Learning - serviço de machine learning empacotado pela AWS.
 * TensorFlow - serviço de deep learning.
 * Athena - consulta de dados para análises adHoc usado padrões SQL.
 * EMR - solução Big Data que oferece Hadoop, Spark, HBase, Presto, Hive, e outros frameworks para Big Data.
 * Elasticsearch Service - Elasticsearch como serviço. Engine de busca full text, database com foco em buscas.
 * Kinesis - Kafka como serviço: coleta, processa, e analisa dados em tempo real ia streaming de dados.
* WAF (Web Application Firewall) - serviço de seguran* TODOça para aplicações com regras definidas previamente ou por você.
* Cognito - serviço de autenticação para provedores de identificação como Facebook, Google, etc.
* MQ (message queue) - serviço que oferece message brokers com Apache ActiveMQ engine.
* SQS (Simple Queue Service) - serviço de totalmente gerenciável de message queuing.
* SNS (Simple Notification Service) - serviço de notificação que oferece pub/sub coordenando a entrega das mensagens para os clients.
* SES (Simple Email Service) - serviço de entrega de e-mails.

#### Google Cloud

Glosssário:

 * TODO
 * TODO

Conclusão: cada tipo de infraestrutura é adequado a um uso, não tem uma infra certa ou errada. Tudo depende de o que e como pretendemos usar. Lembre-se de duas variáveis importantes: o ônus e o bônus, elas andam lado a lado e uma tem uma relação direta com a outra:
 * TODO
 * o bonus de ter tudo na nuvem é você não precisar cuidar de infraestrutura. O ônus é que pode sair mais caro se não souber usar e os cuidados de preservar o seus dados é totalmente seu.
 * o bônus de se ter uma infraestrutura própria é poder fazer o que quiser, quando quiser e como quiser. O ônus é ter que cuidar de todos os detalhes da operação.

## Arquitetura

### Camel

TODO

## Ferramentas de desenvolvimento

### IDE

* Visual Studio e SQL Management Studio - ide rica em recusos e cheia de facilidades
* Visual Studio Code - rica em recursos e cheia de facilidades porém você deve instalar e configurar de acordo com seu gosto e necessidades.
* DBeaver - uma IDE de acesso a dados que possibilita acesso aos maiores databases do mercado.
* InteliJ - ide gratuita para Java.
* PyCharm - A versão para Python da Jetbrains
* Atom, Notepad++, Vim - versões mais raiz de ide de desenvolvimento.

## Qualidade de código

### lint

* [wikipedia - Lint (software)](https://en.wikipedia.org/wiki/Lint_(software))
* ferrramentas de análise de código por problemas no código, no estilo e não conformidades com os padrões.
* [List of tools for code analysis](https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis)

### Testes unitários

### Testes integrados

## Liguagens e frameworks

## snipets

