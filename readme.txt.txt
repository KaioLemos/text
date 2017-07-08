GIT
 
É um sistema de controle de versão que gerencia todas as alterações feitas em um arquivo.
Permite recuperar versões específicas quando necessário. "voltar no tempo".
Outra vantagem é que várias pessoas conseguem trabalhar simultaneamente no mesmo projeto utilizando um repositório.
Um repositório é como um servidor central. Onde os dados de um projeto ficarão padrão.
Quando é necessário realizar alguma alteração, o usuário vai até o repositório e pega a versão mais atualizada, edita e manda de volta para o repositório.
Quando a versão nova chega no repositório ela será mesclada com as outras que já existem.
A vantagem do GIT é: um sistema de gestão distribuído, ou seja, cada cópia do que foi desenvolvido estará disponível em todas as estações de trabalho.
Isso permite uma velocidade maior de trabalho porque não é necessário ficar acessando o repositório a todo momento.
O que é baixado já é um "clone" do que existe no repositório com todas as versões.
Por isso o GIT é chamado de Sistema de Gestão Distribuído.
São 3 estágios de funcionamento:
	Working Directory > criado quando vai no repositório e pega a base do sistema e traz para a prórpia máquina para o desenvolvimento.
	Após dar o (git add) esse arquivo que estava sendo editado para Staging Area> como se fosse uma sala de espera onde os arquivos já editados ficam antes de serem enviados para o repositório.
	Após dar o comando (git commit) esses arquivos irão para o Git Directory que é o repositório principal do projeto. 
