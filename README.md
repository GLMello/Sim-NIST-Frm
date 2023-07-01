<h1>Simulação - Respondendo a um incidente de cibersegurança usando o Framework NIST</h1>

 ### You can also read this in: [English](https://github.com/GLMello/NIST-Frm-Sim/)

<h2>Descrição</h2>
Nesta simulação, minha tarefa foi analisar um ataque de DDoS e criar um relatório de incidente usando o Framework de Cibersegurança do Instituto Nacional de Padrões e Tecnologia Estadunidense (NIST CSF).

<br />


<h2>Cenário</h2>
Você é um analista de cibersegurança que trabalha para uma empresa de multimídia que oferece serviços de design de websites, design gráfico e soluções de marketing em mídias sociais para pequenas empresas. Recentemente, sua organização foi alvo de um ataque de DDoS, que comprometeu a rede interna por duas horas.
Durante o ataque, os serviços de rede da organização pararam de responder repentinamente devido a um flood de pacotes ICMP. O tráfego normal da rede interna não conseguiu acessar nenhum recurso de rede. A equipe de segurança digital respondeu bloqueando pacotes ICMP, desligando todos os serviços de rede não críticos e restaurando os serviços de rede críticos.

A equipe de cibersegurança da empresa investigou o evento de segurança e descobriu que um ator malicioso havia enviado um flood de pings ICMP para a rede da empresa através de um firewall não configurado corretamente. Essa vulnerabilidade permitiu que o atacante sobrecarregasse a rede da empresa através de um ataque DDoS.

Para lidar com esse evento de segurança, a equipe de segurança de rede implementou:

· Uma nova regra de firewall para limitar a taxa de pacotes ICMP recebidos.

· Verificação do endereço IP de origem no firewall para verificar se há endereços IP falsificados nos pacotes ICMP de entrada.

· Software de monitoramento de rede para detectar padrões de tráfego anormais.

· Um sistema de IDS/IPS para filtrar parte do tráfego ICMP com base em características suspeitas.

Como analista de cibersegurança, você tem a tarefa de usar esse evento de segurança para criar um plano para melhorar a segurança de rede da sua empresa, seguindo o Framework de Cibersegurança do Instituto Nacional de Padrões e Tecnologia (NIST CSF). Você utilizará o NIST CSF para ajudá-lo a navegar pelas diferentes etapas de análise desse incidente de cibersegurança e integrar sua análise a uma estratégia geral de segurança:

· **Identificar** riscos de segurança por meio de auditorias regulares nas redes internas, sistemas, dispositivos e privilégios de acesso, para identificar possíveis lacunas de segurança.

· **Proteger** os ativos internos por meio da implementação de políticas, procedimentos, treinamento e ferramentas que ajudem a mitigar ameaças de cibersegurança.

· **Detectar** possíveis incidentes de segurança e melhorar as capacidades de monitoramento para aumentar a velocidade e eficiência das detecções.

· **Responder** para conter, neutralizar e analisar os incidentes de segurança; implementar melhorias no processo de segurança.

· **Recuperar** os sistemas afetados para a operação normal e restaurar os dados e/ou ativos do sistema que tenham sido afetados por um incidente.


<h2>Passo a passo</h2>
Comecei essa simulação analisando cuidadosamente o cenário e baixando uma cópia da framework NIST para ser mais preciso com as decisões.

<p align="left">
 <br/><br />
Assim que entendi a situação, fiz um resumo breve do ataque, de maneira a inteirar o leitor com a situação.
  <br/><br />
<img src="https://i.imgur.com/hXDIByr.png" height="55%" width="55%" alt="Summary"/>
<br /><br />
Daqui em diante, passei a seguir as instruções do framework e integrar cada passo em meu relatório:
<br /><br />
<img src="https://i.imgur.com/toAycts.png" height="55%" width="55%" alt="Report"/>
<br /><br />
Concluí o projeto adicionando uma observação, fazendo uma análise final do ocorrido e recomendando ações futuras.
  <br/><br />
<img src="https://i.imgur.com/CrydodN.png" height="55%" width="55%" alt="Note"/>

</p>
<h2>Nota</h2>

 Este projeto faz parte do curso [Google Cybersecurity Professional Certificate.](https://www.coursera.org/professional-certificates/google-cybersecurity) <br />
