GIT
 
� um sistema de controle de vers�o que gerencia todas as altera��es feitas em um arquivo.
Permite recuperar vers�es espec�ficas quando necess�rio. "voltar no tempo".
Outra vantagem � que v�rias pessoas conseguem trabalhar simultaneamente no mesmo projeto utilizando um reposit�rio.
Um reposit�rio � como um servidor central. Onde os dados de um projeto ficar�o padr�o.
Quando � necess�rio realizar alguma altera��o, o usu�rio vai at� o reposit�rio e pega a vers�o mais atualizada, edita e manda de volta para o reposit�rio.
Quando a vers�o nova chega no reposit�rio ela ser� mesclada com as outras que j� existem.
A vantagem do GIT �: um sistema de gest�o distribu�do, ou seja, cada c�pia do que foi desenvolvido estar� dispon�vel em todas as esta��es de trabalho.
Isso permite uma velocidade maior de trabalho porque n�o � necess�rio ficar acessando o reposit�rio a todo momento.
O que � baixado j� � um "clone" do que existe no reposit�rio com todas as vers�es.
Por isso o GIT � chamado de Sistema de Gest�o Distribu�do.
S�o 3 est�gios de funcionamento:
	Working Directory > criado quando vai no reposit�rio e pega a base do sistema e traz para a pr�rpia m�quina para o desenvolvimento.
	Ap�s dar o (git add) esse arquivo que estava sendo editado para Staging Area> como se fosse uma sala de espera onde os arquivos j� editados ficam antes de serem enviados para o reposit�rio.
	Ap�s dar o comando (git commit) esses arquivos ir�o para o Git Directory que � o reposit�rio principal do projeto. 
