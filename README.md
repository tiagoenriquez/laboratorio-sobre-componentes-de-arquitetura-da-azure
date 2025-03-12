# Laboratório sobre Componentes de Arquitetura da Azure
Foi ensinado no laboratório que:
<li>Pares de regiões existem para a Microsoft determinar de antemão qual outra região receberá os dados de uma região que, por algum motivo, ficou indisponível.</li>
<li>Zonas de disponibilidade "grupos separados de datacenters em uma região" (fonte: https://learn.microsoft.com/pt-br/azure/reliability/availability-zones-overview?tabs=azure-cli). As regiões possuem um ou mais datacenters. Costumam ter 3. E o grupo de datacenters é chamado de zona de disponibilidade. Uma aplicação pode estar nos 3 datacenters. E se um falhar há outros 2 para manter os site no ar.</li>
<li>O gerenciamento de recursos é dividido hierarquicmente em 4 níveis: 
<ul>
  <li>Gerenciamento de recursos: permite padronizar política para várias assinaturas</li>
  <li>Assinaturas: uma conta pode ter várias assinaturas e cada assinatura só pode estar associada a uma conta. A fatura mensal vem sobre a assinatura.</li>
  <li>Grupos de recursos: grupos lógicos que permitem ao usuário administrar os recursos</li>
  <li>Uma instância de serviço que o usuário pode criar, a exemplo de banco de dados, máquinas virtuais e armazemanto.</li>
</ul></li>
