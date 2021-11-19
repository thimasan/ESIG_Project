<img src="https://scontent.fnat2-1.fna.fbcdn.net/v/t39.30808-6/238342261_210080597742177_8206461851856926361_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=6e5ad9&_nc_ohc=SaFCQtUegHYAX8ckb2B&_nc_ht=scontent.fnat2-1.fna&oh=ff67f6ffb199b1811fd4014e90f578fc&oe=619B46EE" height="300" width="100%" />

<h1 align="center">:file_cabinet: PROJETO ESIG .md</h1>

## :memo: Descrição
Atividade prática para seleção de Analista de Infraestrutura.
O projeto consiste em simular a estruturação e implementação de dois serviços em nuvem em uma empresa, o Rocket Chat e o Wiki.
O Rocket Chat será utilizado para melhorar a comunicação interna e o Wiki será utlizado para melhorar a documentação dos processos internos.
Todo o ambiente será provisionado utilizando o Kubernetes como ferramenta de orquestração de Cluster.


## :books: Funcionalidades
* <b>RocketChat</b>:
   - [x] Conferência de áudio e vídeo; 
   - [x] Acesso de usuário convidado;
   - [x] Compartilhamento de tela e arquivos; 
   - [x] LiveChat; 
   - [x] LDAP Group Sync;  
   - [x] Autenticação de dois fatores (2FA); 
   - [x] Criptografia E2E; 
   - [x] Usuários ilimitados.
* <b>Wiki.JS</b>:
   - [x] Open source;
   - [x] Pode gerenciar as permissões de usuários e artigos;
   - [x] Possui sistema de busca;
   - [x] Tem suporte a Markdown;
   - [x] Fácil de instalar e Usar;
   - [x] O aplicativo é executado no mecanismo Node.js. Ele é otimizado para usar poucos recursos de CPU.
   - [x] O Wiki.js nos dá a possibilidade de inserir imagens, diagramas, documentos, vídeos, links, etc.
 
## :wrench: Tecnologias utilizadas
<table>
  <tr>
   <td align="center">
      <code><img height="32" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/docker_official_logo_icon_169250.png?raw=true"/></code>         Docker
      <code><img height="32" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/kubernetes.png?raw=true"/></code>   Kubernetes
      <code><img height="32" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/minikube.jpg?raw=true"/></code> Minikube
      <code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png" alt="PostegreSQL"/></code>    PostgreSQL
      <code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png" alt="MongoDB"/></code>   MongoDB
      <code><img height="32" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/Node%20Medio.png?raw=true" alt="Nodejs"/></code> Node.JS
      
</table>
 
* <b>Docker</b>: O Docker tem como objetivo criar, testar e implementar aplicações em um ambiente separado da máquina original, chamado de container.   
* <b>Kubernetes</b>: Kubernetes é um sistema de orquestração de contêineres open-source que automatiza a implantação, o dimensionamento e a gestão de aplicações em contêineres.  
  * <b>Minikube</b>: O Minikube é uma implementação leve do Kubernetes que cria uma VM em sua máquina local e implanta um cluster simples contendo apenas um nó.
* <b>PostgreSQL</b>: O PostgreSQL é um banco de dados objeto-relacional (sem relação com linguagens de programação orientadas a objetos), em que cada coisa criada é tratada como um objeto, tais como bancos de dados, tabelas, views, triggers, etc.
* <b>MongoDB</b>: É um banco de dados opensource, de alta performance e flexível, sendo considerado o principal banco de dados NoSQL.
* <b>NodeJS</b>: Node.js é um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web.
* <b>Funcionalidade 1</b>: O que essa funcionalidade faz?

## :rocket: Rodando o projeto
   *  <h3><b> Pré-requisitos:</b></h3>
 IMPORTANTE:   Visando a fácil leitura e utilização deste README, os processos de download e instalação dos programas necessários
       ao projeto encontram-se nos links associados aos seus respectivos nomes.  o clicar nos tópicos abaixo você será redirecionado para os 
       sites e repositórios oficiais.
- [x] [Ubuntu 20.04](https://ubuntu.com/download/desktop). 
   - Após instalar o Ubuntu, fazer o update e upgrade dos recursos nativos e instalar os programas auxiliares que nos ajudarão no processo de implementação, 
   como um editor de texto de sua preferência, uma IDE de desenvolvimento (ex.: VSCode, Brackets) e programas auxiliares como o VIM ou Nano (minha preferência).
- [x] [Minikube](https://minikube.sigs.k8s.io/docs/start/).
- [x] [Docker](https://docs.docker.com/engine/install/).
- [x] [Minikube](https://minikube.sigs.k8s.io/docs/start/).
- [x] [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/) CLI installed.
- [x] [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/).
- [x] [Kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/).

## :soon: Implementação Rocket-CHat
   * Criação da Imagem Rocket Chat
   * Criação da Image do MongoDB
   * Instalação e Configuração do Banco de Dados
   * Instalação do Conteiner do Rocket Chat
   * Deploy do Serviço no Kubernetes
       - OBSERVAÇÕES IMPORTANTES
   
## :soon: Implementação Wiki.JS
   * Criação da Imagem do Wiki
   * Instalação e Configuração do Banco de Dados
   * Instalação do Conteiner do Wiki
   * Deploy do Serviço no Kubernetes
       - OBSERVAÇÕES IMPORTANTES

   
## :handshake: Colaboradores
<table>
  <tr>
    <td align="center"><a href="https://github.com/thimasan"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/53660425?v=4" width="100px;" alt=""/><br /><sub><b>Thiago Santana</b></sub></a><br /><a href="https://github.com/thimasan" title="Thimasan">👨‍🚀</a></td>
    <td align="center"><a href="https://www.google.com"><img style="border-radius: 50%;" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/Google.png?raw=true" width="100px;" alt=""/><br /><sub><b>Google</b></sub></a><br /><a href="/www.google.com" title="Enciclopédia">👨‍🚀</a></td>
    <td align="center"><a href="https://pt.stackoverflow.com/"><img style="border-radius: 50%;" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/STACK.png?raw=true" width="100px;" alt=""/><br /><sub><b>StackOverFlow</b></sub></a><br /><a href=https://pt.stackoverflow.com/" title="Consultas">👨‍🚀</a></td>
    <td align="center"><a href="https://www.youtube.com"><img style="border-radius: 50%;" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/youtube%20pequeno.png?raw=true4" width="100px;" alt=""/><br /><sub><b>Youtube</b></sub></a><br /><a href="https://www.youtube.com" title="Professor">🚀</a></td>
    <td align="center"><a href="https://github.com/"><img style="border-radius: 50%;" src="https://github.com/thimasan/ESIG_Project/blob/main/imagens_repositorio/github.png?raw=true" width="100px;" alt=""/><br /><sub><b>GitHub</b></sub></a><br /><a href="https://github.com" title="Mercado">🚀</a></td>
  </tr>
</table>

## :dart: Status do projeto
       * EM DESENVILVIMENTO
