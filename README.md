# docker-projeto2-cluster
 Criação de um Cluster Swarm local, utilizando máquinas virtuais, além, de aplicar nossos conhecimentos em Vagrant
 
 ## Definições
 - Vagrantfile com as definições de 4 maquinas virtuais. Sendo uma maquina com o nome de master e as outras com os nomes de node01, node02 e node03.
 - Cada maquina virtual possui um id fixo
 - Todas as maquinas virtuais devem possuir um Docker pré-instalado
 - A maquina master é o manager do cluster
 - as outras maquinas fazem parte do cluster como workers
