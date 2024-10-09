# Docker e Virtualização

## Docker

Docker usa **containers**. 

Containers são uma maneira de criar ambientes leves e reproduzíveis para a execução de processos.

## Virtualização

Antes de falar sobre containers, é importante entender a virtualização:

### O que é Virtualização?

A virtualização requer os seguintes componentes:

- **Host Machine**: Pode ser um PC local, um servidor na nuvem ou um servidor em um data center. É necessário um pedaço de hardware.
  
- **Recursos Necessários**: O host machine precisa de componentes que controlam como o hardware funciona, como CPU, Memória e Disco Rígido (I/O).

### Processo de Virtualização

Para iniciar o processo, dividimos pequenos pedaços de cada um desses componentes de hardware e os separamos em uma máquina distinta, chamada **Virtual Machine (VM)**.

Em uma virtual machine, executamos um sistema operacional completo. Isso é comumente utilizado na nuvem, se você estiver implantando algo na AWS ou em uma instância EC2.

### Hypervisor

As virtual machines utilizam um tipo especial de programa que pode executar e gerenciar seu ciclo de vida, chamado **Hypervisor**.

O hypervisor é responsável pelas virtual machines, gerenciando seu ciclo de vida. Exemplos de hypervisores incluem: **VMWare**, **VirtualBox**.

## Containerização

Containerização cria um ambiente leve onde processos podem ser executados em um sistema operacional host. Os containers compartilham os mesmos recursos do sistema operacional, mas não podem acessar nada fora de seu ambiente.

O Docker gerencia o ciclo de vida dos containers.

## Instalando o Docker

Para instalar o Docker, use o seguinte comando:

```bash
brew install docker
