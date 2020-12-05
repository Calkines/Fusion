# Fusion
Este repositório serve para ajudar pessoas que queiram aprender Fusion Server.

## O que é o Fusion

Fusion é um sistema desenvolvido pela [Lucidworks](https://lucidworks.com/products/fusion/) para resolver situações onde é necessário realizar descoberta de dados com interligência artificial, aplicações de busca de maneira moderna, conteinerizada, e arquiteturalmente pensadas para nuvem.

### Funcionalidades

1. Navegação tranquila com Kubernetes
2. Machine Learning em qualquer lugar
3. Respostas inteligentes 
4. Merchandiser preditivo
5. Pacote avançado de linguistica
6. Opções de implantação flexíveis


## Começando a aplicação

Para começar a utilizar você precisará baixar o repositório [cloud-native](https://github.com/lucidworks/fusion-cloud-native). Nele estão todos os pacotes/documentos que você precisa para conseguir implementar o Fusion server em diferentes serviços de Cloud.

Aqui vamos explorar o cenário de uso com Kubernetes na modalidade de Baremetal. (tentativa, continuar testes e escrever resultados).

### Namespace

Então qual o primeiro passo? Escolher o namespace da sua aplicação. De acordo com a documentação, podemos instalar várias instâncias do Fusion em namespaces diferentes, mas não é indicado instalar mais de uma instância em um mesmo namespace.

### Helm
Na sequencia é necessário instalar o [Helm](https://helm.sh/docs/using_helm/).
Para isso use o comando: `brew install kubernetes-helm`.

Permissões para Helm. O Fusion permite a instalação de pacotes pelo Help usando um usuário que não seja admin, para configurar este usuário, você deverá olhar para o diretório `install-roles` no repositório e aplicar os arquivos de lá no seu repositório.

(necessário pesquisar mais sobre o assunto e melhorar este trecho).

#### Helm no Windows:
Para instalar o Helm no Windows, você vai precisar do Chocolatey. Uma vez que você o Choco instalado, basta usar o seguinte comando: `choco install kubernetes-helm`.




