 Sistema de controle de versões 
O que é um sistema de controle de versões?
Os sistemas de controle de versões são programas de software que ajudam a controlar as alterações feitas no código ao longo do tempo e também a rastreá-los, os controles de versões ajudam as equipes de software a trabalharem de forma mais rápida e inteligente 
Vantagens:
 1- rastreabilidade, 2 ramificação e mesclagem,3-Um histórico de alterações completo e a longo prazo de todos os arquivos,4- segurança: cada software de controle de versão utiliza mecanismos para evitar qualquer tipo de invasão de agentes mal-intencionados,5-organização: Alguns softwares disponibilizam uma interface visual onde podem ser vistos todos os arquivos controlados, desde a origem até o projeto completo.
3 exemplos de VCS:
Microsoft Visual SourceSafe (VSS)- produto da Microsoft para controle de versão, integrado a muitas IDEs da Microsoft
Git- Software para controle de versão distribuído com foco de velocidade.
Concurrent Version System (CVS) - software livre clássico e bem testado.
Desafio 2 
Programação orientada a objetos e seus pilares (POO)

A programação orientada a objetos é um paradigma de programação baseado no conceito de
“objetos “, que contém dados nas formas de campos, também conhecidos como atributos, e códigos, na forma de procedimentos, conhecidos como métodos. 
Um dos principais procedimentos do (POO) é facilitar o entendimento e a modelagem de software complexo através da organização do código em unidades lógicas que representam
 entidades ou conceitos do mundo real. Um objeto é uma instancia de uma classe, que pode conter dados (atributos) e métodos (funções). 

Os principais conceitos do (POO) são:
1.Abstração- É basicamente o processo de ocultar detalhes complexos e mostrar apenas as características essenciais de objetos ou sistema. o conceito de Abstração se desdobra 
em: classes- São conjuntos de objetos que possuem o mesmo tipo; objetos- São instâncias de classes.
2.Encapsulamento- Protege os dados de um objeto, restringindo o acesso direto a alguns componentes e permitindo que o acesso seja feito através de métodos.
3.Herança- Permite que uma classe herde atributos e métodos de outra classe, promovendo reutilização e organização de código.
4.Polimorfismo- Permite que diferentes classes sejam tratadas como instancias da mesma classe através de uma interface comum. Isso é alcançado principalmente através de métodos sobrescritos (override) e sobrecarregados (overload).
As 5 vantagens do (POO) são: o uso do (POO) é que a herança e a criação de hierarquias de classes permitem a reutilização eficiente do código, também a modularidade, a facilidade de manutenção, flexibilidade e a abstração do mundo real. 

desafio3
PROTOCOLO DE COMUNICAÇÃO (HTTP)
O HTTP é um protocolo que permite a obtenção de recursos, como documentos HTML. É a base de qualquer troca de dados na Web e um protocolo cliente-servidor, o que significa que as requisições são iniciadas pelo destinatário, geralmente um navegador da Web. Um documento completo é reconstruído a partir dos diferentes sub-documentos obtidos, como por exemplo texto, descrição do layout, imagens, vídeos, scripts e muito mais.
o HTTP é essencial para a comunicação na web, permitindo que clientes (navegadores) façam requisições para servidores web e recebam respostas, possibilitando assim a visualização de páginas web, o envio de dados de formulários, o download de arquivos, entre outros.
API REST, também conhecida como API RESTful, é uma API (interface de programação de aplicações) em conformidade com as restrições do estilo de arquitetura REST, permitindo a interação com serviços web RESTful. REST é a sigla em inglês para "Representational State Transfer", que em português significa "tansferência de estado representacional". 
REST é um protocolo de comunicação, baseado no protocolo de hipermídia HTTP. Porém ele não impõe restrições ao formato da mensagem, apenas no comportamento dos componentes envolvidos. A maior vantagem do protocolo REST é sua flexibilidade.
Uma web API server-side é uma interface programática consistente de um ou mais endpoints publicamente expostos para um sistema definido de mensagens pedido-resposta, tipicamente expressado em JSON ou XML,[2] que é exposto via a internet—mais comumente por meio de um servidor web baseado em HTTP.
POST (CREATE): Cria um recurso.
GET (READ): Retorna uma representação de um recurso.
PUT (UPDATE): Atualiza um recurso existente.
DELETE: Exclui um recurso.

Desafio 4 
Repository (Repositório):

Um repositório é uma camada de abstração que fica entre os serviços (ou a lógica de negócios) e a camada de persistência (geralmente o banco de dados). Ele encapsula a lógica de acesso aos dados e fornece uma interface para manipular e recuperar objetos de dados. Isso ajuda a manter a separação de preocupações e facilita a substituição ou mudança do sistema de armazenamento de dados sem afetar o restante da aplicação. Um repositório pode incluir métodos para criar, ler, atualizar e excluir (CRUD) objetos persistentes.
Entity (Entidade):

Uma entidade representa um objeto de negócio ou um conceito no domínio do problema que está sendo modelado. Em termos de programação orientada a objetos, uma entidade é frequentemente mapeada para uma tabela em um banco de dados relacional. Ela geralmente possui propriedades que correspondem aos campos da tabela e métodos para operar sobre esses dados. As entidades são frequentemente usadas junto com ORM (Object-Relational Mapping) para facilitar o mapeamento entre os objetos da aplicação e os registros do banco de dados.
Service (Serviço):

Um serviço é uma camada responsável por implementar a lógica de negócios da aplicação. Ele contém métodos que encapsulam operações complexas ou regras de negócio que não pertencem diretamente às entidades ou aos repositórios. Os serviços interagem com os repositórios para buscar, persistir ou manipular dados, mas sua principal responsabilidade é coordenar a execução de tarefas e implementar a lógica que não se encaixa nas entidades ou nos repositórios.
Controller (Controlador):

Um controlador é responsável por receber as requisições HTTP dos clientes (como navegadores web ou aplicativos móveis), invocar os serviços apropriados para processar essas requisições e retornar uma resposta adequada. Em aplicações web, por exemplo, os controladores são responsáveis por interpretar as entradas do usuário (parâmetros de URL, dados de formulários, etc.), chamar métodos nos serviços para executar a lógica de negócios e retornar as respostas adequadas (geralmente HTML, JSON, XML, etc.) para os clientes

Desafio 5 
Repository (Repositório):

Um repositório é uma camada de abstração que fica entre os serviços (ou a lógica de negócios) e a camada de persistência (geralmente o banco de dados). Ele encapsula a lógica de acesso aos dados e fornece uma interface para manipular e recuperar objetos de dados. Isso ajuda a manter a separação de preocupações e facilita a substituição ou mudança do sistema de armazenamento de dados sem afetar o restante da aplicação. Um repositório pode incluir métodos para criar, ler, atualizar e excluir (CRUD) objetos persistentes.
Entity (Entidade):

Uma entidade representa um objeto de negócio ou um conceito no domínio do problema que está sendo modelado. Em termos de programação orientada a objetos, uma entidade é frequentemente mapeada para uma tabela em um banco de dados relacional. Ela geralmente possui propriedades que correspondem aos campos da tabela e métodos para operar sobre esses dados. As entidades são frequentemente usadas junto com ORM (Object-Relational Mapping) para facilitar o mapeamento entre os objetos da aplicação e os registros do banco de dados.
Service (Serviço):

Um serviço é uma camada responsável por implementar a lógica de negócios da aplicação. Ele contém métodos que encapsulam operações complexas ou regras de negócio que não pertencem diretamente às entidades ou aos repositórios. Os serviços interagem com os repositórios para buscar, persistir ou manipular dados, mas sua principal responsabilidade é coordenar a execução de tarefas e implementar a lógica que não se encaixa nas entidades ou nos repositórios.
Controller (Controlador):

Um controlador é responsável por receber as requisições HTTP dos clientes (como navegadores web ou aplicativos móveis), invocar os serviços apropriados para processar essas requisições e retornar uma resposta adequada. Em aplicações web, por exemplo, os controladores são responsáveis por interpretar as entradas do usuário (parâmetros de URL, dados de formulários, etc.), chamar métodos nos serviços para executar a lógica de negócios e retornar as respostas adequadas (geralmente HTML, JSON, XML, etc.) para os clientess