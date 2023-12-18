# Projeto-Redes-AdaTech 🚀🚀

Projeto final da matéria de Redes dentro do curso de Devops da Ada Tech

## Um pouco do que foi feito durante nossa materia de Redes. 📋

## Objetivos do caso. 🎯

( Realizar a criação de 2 redes diferentes e realizar a comunicação via ICMP entre uma e outra.

Rede A (Alunos)
192.168.0.0/24 192.168.10.254 (Gateway) 192.168.10.253 (DHCP e DNS)

Criação de Outras 4 máquinas dentro da Rede Interna A utilizando DHCP para desktops, e IP fixo para Servidores.

Rede B (Alunos)
172.15.0.254/24 172.15.0.254 (Gateway) 172.15.0.253 (DHCP e DNS) 172.15.0.252 (Servidor Web)

Criação de Outras 5 máquinas dentro da Rede Interna B utilizando DHCP para desktops, e IP fixo para Servidores.

Equipamentos:
1 Router 1841 3 Switches 2960 24TT

Explicação:
O objetivo final, é que um dos Desktops da Rede A, consiga colocar em seu navegador interno, o endereço do Site do Servidor WEB que está na REDE B, e a página possa ser carregada corretamente, validando deste modo o Roteamento entre as Redes, DNS e a camada da Aplicação funcionando corretamente.)

<div align="center">
<h2>
Projeto montado 📝
<h2>
<img src=projeto-foto.jpg/>

</div>


<div align="center">
<h2>
Acesso de uma maquina da rede 'A' acessando o servidor web da rede 'B'.
<h2>
<img src=acessoweb.jpg/>

</div>

<div align="center">
<h2>
Servidor 'A' configurado com os IPs indicados na proposta do caso.
<h2>
<img src=server-a.jpg/>

</div>

<p>
Nesse projeto todos os terminais estão configurados em DHCP, onde eles ja estão com todos as configuraçoes corretas, sendo enviado pelo servidor DHCP e DNS de cada rede.
</p>