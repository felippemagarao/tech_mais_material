# Requisitos do projeto (5W2H):
## Quem?
 -Empresa Microméros que atua no setor industrial e utiliza IOT para a tomada de decisões de seus clientes. A empresa fornece a infraestrutura, a instalação e a manutenção dos sensores, e ainda fornece relatorios com os dados coletados, por meio de gráficos, telas de payback e insights. A Microméros atua no eixo industrial, atendendo fábricas, transportadoras, etc. 

-Equipe de tecnologia. Restrito. Login, registro e usuários. Permissões personalizadas. Cargo de administrador é o único com a permissão de registro de novos 		    usuários.
- O sistema é para os setores de tecnologia, setor comercial e setor de operações.

## Quando?
	O projeto será desenvolvido no 1º semestre de 2023. 
    
## O que?
	A empresa busca um sistema web para controle de chamados. O sistema deve:
- ter login e senha (somente o administrador pode criar novos usuários e gerencias as permissões de 0);
- controlar o acesso dos usuários;
- classificar os chamados por meio de uma divisão entre os setores e subdivisões por hierarquia de urgência;
- controlar diariamente a quantidade de chamados abertas e fechados/concluidos nos diferentes departamentos; 
- classificar os chamados em "Pendentes", "Abertos" ou "Resolvidos";
- informar os dados para o gerente de operação em tempo real ( criação de um relatorio com informaçoes diárias e dicas especializadas, tais como: número de soluções por dia, relatorios e análises detalhadas, eventos e log de eventos, para gestão de desempenho operacional; Gestão de métricas e desempenho. 
- SLA (Acordo de Nível de Serviço) de acordo com as prioridades dos chamados (ex: queda de um servidor - chamado urgente). Caso, um chamado expire, o mesmo deve ser duplicado no card de pendente e expirado, pq mesmo assim deve ter uma solução o quanto antes

	Os dados utilizados para o desenvolvimento do sistema serão fícticios. Além das características descritas anteriormente, o sistema também precisa: 
- ser Interativo, prático e eficiente;
- ter Responsividade, ou seja, ser adaptável com possibilidade de acesso via mobile.
- guardar informações em Logs.
  
## Onde?
  	O sistema deve funcionar tanto em computadores como em dispositivos móveis. 
    
## Por que?
	O sistema antigo utilizado pela empresa possui algumas falhas e não estava suprindo as necessidades operacionais da empresa. A principais críticas do antigo sistemas são: 
- O sistema antigo não é orientado a chamados;
- Há dificuldade em guardar informações dos chamados (logs) e os mesmos se perdem como tempo;
- Não há informações relevantes para os analistas;
- Os funcionários precisam se reunir presencialmente para a analise dos dados, pois os dados que aparecem no sistema são de dificil interpretação  

 ## Quanto?
 	O projeto não possui custo inicial.
    
## Como?
	O sistema será construído com base em conceitos de Design Thinking e metodologias ágeis. Também serão utilizadas ferramentas de codificação de aplicação com uso de framework JavaScript (Angular, React, Vue.js ou similar), em ambiente de desenvolvimento integrado ou editor de texto com complementação de código (Visual Studio Code, Atom, Sublime ou similar), utilização de dados provenientes de API web, integração com mídias e imagens, implementação de design de interface adaptável a diferentes tamanhos de tela (proporcional, responsivo, media queries, mobile first).
	
## Lista de Requisitos Funcionais em tópicos:

1- O sistema deve controlar o acesso do usuário através de login, senha e dupla autenticação (se precisar). A única pessoa com a permissão de criar/gerenciar acessos é o administrador, que terá acesso à todas as logs do sistema e ao sistema de criação e gerenciamento de usuários.

2- O sistema precisa mostrar, controlar e definir os chamados. Na hora de criar o chamado, o usuário deve definir a criticidade, o tipo de problema, descrevê-lo em uma caixa de texto e definir a tag do setor, que será mostrada na tela.

3- O sistema classificará, através de tags no dashboard, os chamados em abertos, fechados e pendentes. Os pendentes são chamados que já expiraram o prazo mas ainda precisam de uma resolução. Terá tags para classificar de qual área cada chamado é.

4- O sistema precisa exibir quantos chamados foram abertos/fechados no dia, para gestão de desempenho e métricas. Pode mostrar o tempo médio de resposta de cada área.

5- O sistema deve gerar logs de abertura, fechamento e andamento de chamados, sempre notificando os gerentes operacionais de cada área (operações, comercial e TI). 

6- Um chamado X será criado por um usuário do setor Y, o setor responsável será notificado com o tipo do problema, a criticidade e o prazo. Quando o chamado for aberto pelo responsável e a resolução começar, quem abriu o chamado será notificado.

7- Sistema de busca personalizada por setor e criticidade. O usuário selecionará a pesquisa avançada e definirá os critérios. A pesquisa também pode ser feita por nome, buscando no sistema e exibindo o chamado de acordo com os critérios utilizados.

*OBS: Pode ser feita, depois da resolução do problema, uma pesquisa de satisfação para avaliar a eficiência da equipe de atendimento.

## Lista de requisitos não funcionais em tópicos:

1- O software deve ser seguro e proteger as informações do usuário;

2- O software deve ter um tempo de resposta rápido;

3- O software deve ter uma interface fácil de usar e intuitiva;

4- O software deve ser escalável e capaz de lidar com grande volume de dados;

5- O software deve ser confiável e ter alta disponibilidade;

6- O software deve ser fácil de manter e atualizar.

7- O sistema não terá integração com nenhum outro sistema da empresa.

8- O sistema deve ser capaz de processar a alta carga (a definir específicamente) de chamados sem sair do ar.

9- O sistema deve ficar disponível 24h, ser escalável e responsivo.

