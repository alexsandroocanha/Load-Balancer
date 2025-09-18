<h1 align="center">Resumo ALB e LB</h1>
<p align="center"> <i>Auto Scaling Group, Load Balancer e Regras de Scaling Up e Down</i></p>

## **Auto Scaling:**
```
É um serviço/funcionalidade da computação em nuvem, que monitora e
aloca automaticamente recursos computacionais com base na demanda
do sistema, pelo menor custo possível. 
```

## **Regras de Scaling Up:** 
```
Ele define quando o grupo de escalonamento vai realmente subir as
instancias/serviços. Pode ser definido regras como “50% de cpu”, “90%
de armazenamento”, “Trafego massivo de dados”, etc.
```

## **Regras de Scaling Down:**
```
Ele define quando as instancias subidas pelo auto scaling vão desligar.
Exemplo quando a instancia ec2 fica abaixo de “50%”, as instancias que
subiram com as Regras de Scaling Up serão desligadas 
```
 

## **Load Balancer:** 
```
É um serviço para manter a estabilidade de um servidor/instancia
balanceando a carga e distribuindo o tráfego de rede ou de dados igualmente
em um grupo de recursos que oferecem suporte a uma aplicação.   
```
 
