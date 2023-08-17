 # AWS ESTUDOS  
<strong># TIPOS DE SERVIÇOS QUE TEMOS EM CLOUD </strong>
<br>
<strong>IaaS</strong> 
1 - infrastructure-as-a-Service - 
O que seria a infrastrutura como serviço você, contrataria apenas a infraestrutura da aws exemplo as partes como (networking,storage,services e virtualization ),as questões de O/S e aplicação seria de sua
responsabilidade
<br>
<strong>PaaS</strong>
2 - plataform-as-a-Service -
Na plataforma como serviço você estaria contratando a infra como  tambem a parte que gerencia  seu O/S e outras coisas como middleware, assim ficando para você apenas a aplicação
<br>
<strong>SaaS</strong>
3 - Software-as-a-Service -
Está ultima opção a aws ira gerenciar toda sua infra como tambem sua aplicação assim ficando mais restrito as modificações um exemplo seria um software de CRM
______________________________________________________________________________________________________________________________________________________________________________________________________________
<strong># TIPOS DE NUVEM QUE TEMOS NA ATUALIDADE</strong>
<br>
<strong>Public Cloud</strong> - Oferecidas por provedores cloud como a aws , o que significa public cloud esse conceito diz que o serviços de cloud estão disponivel para qual quer pessoal da internet,mas não
que ao você criar um server exemplo ele ficará disponivel para todos.
<br>
<strong>Private Cloud</strong> - Algumas empresas ou órgãos governamentais optão por essa opção , essa opção de cloud diz que todo a infra e demais será alocada em um lugar diferente das que usam a opção public cloud, 
isso sendo muito mais caro.
<br>
<strong>Hybrid Cloud</strong> - E por fim temos está opção como ela funciona tenho um sistema de cadastro ,o front-end ficaria na parte da public cloud e para ter uma maior segurança colocaria meu banco de
dados na private cloud.
_____________________________________________________________________________________________________________________________________________________________________________________________________________
<strong># SERVIÇOS DA AWS </strong>
<br>
Lista de Alguns dos serviços mais utilizados da Amazon e suas Funções.
<br>
<strong>AMAZON ELASTIC COMPUTE CLOUD (EC2)</strong> : Podemos criar maquinas virtuais, facilitando a instalação de software. Podemos desligar e ligar nossas vm a qualquer momento e pagamos somente pelo que utilizamos,e também podemos ampliar ou reduzir a infraestrutura a qualquer momento, sendo assim uma solução escalavel.
<br>
<strong>ELASTIC BEANSTALK</strong> : Possibilita a implantação de aplicações em ambientes .NET,Java,Python e outros, também  é escalável e agiliza o trabalho para desenvolvedores, exemplo quando subimos um código, na aws a mesma já faz o restante do trabalho a implementação, balanceamento de carga e monitora o desempenho.
<br>
<strong>AMAZON INSPECTOR</strong> : Faz a varredura de ameaças nas instancias (EC2), e criar uma lista para vocẽ para você poder tomar ações.
<br>
<strong>SHIELD AWS DDoS PROTECTION</strong> :
<br>
Distributed Denial of Service,Filtra o trafego e vigia a sua aplicação
<br>
Standard funciona de forma automática, monitora a rede,verifica o ataque e dropa,verifica a assinatura,trafego suspeito analisa,detecta e filtra em tempo Real(Não Paga) - Já é Habilitado
<br>
Advanced: Você paga pelo o que utiliza,regras, assinaturas, como todos os outros softwares que combatem DDOS
Elastic IP, CloudFront, Route 53, Load Balancing
<br>
<strong>TRUSTED ADVISOR</strong> : Ferramenta online para saber de forma geral os serviços da AWS, visão online sobre todos os erviços para podermos otimizalos e te ajudar na questão de segurança ,monitoramento.
<br>
<strong>ATHENA E MACIE</strong> :
<br>
Macie: Para dados de informações pessoais (PII), ele analisa através de machine learning e gera analise de riscos de tentativa de acesso não autorizado,apenas so S3.
<br>
ATHENA :  Usa consultas SQL interativas e armazena no S3. Serveless(Não depende de infraestrutura), mas vocẽ paga por consulta.
<br>
<strong>CloudWatch</strong> : Informações e Dados para acompanhar os aplicativos. tendo uam visão completa de consumo dos serviços, metricas, eventos, dados de logs, Conseguimos configurar alarmes e automatizar ações.(Mandar e-mail para aumentar os recursos)
<br>
<strong>CLOUDTRAIL</strong> : Ajuda em conformidade,autidoria,Governança,conseguimos ver nos logs quando habilitado o serviço.Mantendo o historico e anomalias na conta.(Espécie de Registro de Portaria(Auditoria))
<br>
<strong>AWSCONFIG</strong : Serviço de auditoria, monitoria,analise de como estão meus recursos. Gerencia a Configuração dos recursos AWS, tipo mudança nos serviços,histórico e gerenciamento.
____________________________________________________________________________________________________________________________________________________________________________________________________________
<strong>SEGURANÇA E CONFORMIDADE </strong>
<br>
A Aws Trata sobre segurança com altissima prioridade
<br>
<strong>Na nuvem toda a parte de segurança é baseada em Software:</strong>
Firewall
<br>
<strong>A aws considera como  beneficios em questão de segurança:</strong>
<br>
Manter nosso dados seguros, conformidade, Economia de Dinheiro(Conceito Nuvem)
<br>
Escala Rápida(Conceito Nuvem)
___________________________________________________________________________________________________________
<strong>MODELO DE RESPONSABILIDADE COMPARTILHADA</strong>
<br>
O que seria responsabilidade compartilhada é uma responsabilidade compartilhada entre AWS e Cliente.
<br>
<strong>Exemplos - 1 </strong> Toda manutenção fisica, SO e Virtualização é responsabilidade AWS 
<br>
<strong>Exemplos - 2 </strong> Atualizações de Segurança, liberação de aplicações em EC2 é responsabilidade do cliente
<br>
Of the Cloud, segurança da nuvem responsabilidade AWS (Termos)
<br>
In the Cloud , segurança na nuvem responsabilidade do usuario(Termos )
___________________________________________________________________________________________________________





