# Criando-VM

# Criando Máquinas Virtuais no Microsoft Azure

Este README é um resumo sobre o lab da DIO sobre criação de uma VM com Azure.

## Introdução

As Máquinas Virtuais no Azure permitem que você execute aplicações em ambientes isolados, simulando servidores físicos. Este guia explica como criar uma VM a partir do zero.

Acesse o portal do Azure: Visite o site https://portal.azure.com.

# Criando uma Máquina Virtual

## Passo 1: Acessar a Seção de Máquinas Virtuais

No painel de navegação à esquerda, clique em "Todos os Serviços". No campo de busca, digite "Máquinas Virtuais" e selecione a opção "Máquinas Virtuais" em "Computação".

Clique em "Adicionar" ou "Criar" para iniciar o processo de criação de uma nova máquina virtual.

## Passo 2: Configurações Básicas

Assinatura e Grupo de Recursos: Selecione a assinatura correta e um grupo de recursos existente ou crie um novo.

Detalhes da Instância: Insira o nome da máquina virtual, escolha a região onde a VM será hospedada e selecione a disponibilidade, se necessário (opcional).

Imagens e Sistema Operacional: Selecione a imagem do sistema operacional que deseja usar (por exemplo, Windows Server, Ubuntu, etc.).

Tipo de Autenticação: Escolha entre senha ou chave SSH para autenticação.

## Passo 3: Tamanho da Máquina Virtual

Escolha o tamanho da máquina virtual com base nos requisitos de CPU, memória e armazenamento. Azure oferece várias opções, desde VMs pequenas e econômicas até instâncias maiores e mais potentes.

## Passo 4: Configurações de Disco

Selecione o tipo de disco de SO (SSD, HDD).
Adicione discos adicionais, se necessário, para armazenamento de dados.
Passo 5: Configurações de Rede
Rede Virtual e Sub-rede: Escolha uma rede virtual existente ou crie uma nova. Selecione a sub-rede desejada.

Endereço IP Público: Escolha se a VM terá um endereço IP público.

Grupo de Segurança de Rede (Firewall): Configure regras de entrada e saída, como permitir acesso via RDP (para Windows) ou SSH (para Linux).

## Passo 6: Revisão e Criação

Revisar Configurações: Verifique todas as configurações feitas e clique em "Revisar + criar".

Implantação: Após a revisão, clique em "Criar" para iniciar o processo de implantação da máquina virtual. A criação pode levar alguns minutos.
Gerenciando a Máquina Virtual

Acessar a VM: Após a criação, você pode acessar a VM utilizando RDP, SSH ou outras ferramentas de gerenciamento remoto.

Configurações Adicionais: Acesse o painel da VM para ajustar configurações, monitorar desempenho e gerenciar recursos associados.
