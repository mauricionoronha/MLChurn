EXPLORAÇÃO, ANÁLISE E TRATAMENTO DE DADOS: Projeto de previsão de churn

Este projeto tem como objetivo utilizar modelos de machine learning para prever tendências de cancelamento utilizana base de dados de uma operadora de telecomunicações.

Segue um resumo da estrutura dos dados que compõe o dataframe:
* IDCliente - Identificação do cliente 
* Genero  - Sexo do cliente
* Dependentes - Informa se o cliente possui serviços de compartilhamento com dependentes
* MesesComoCliente - Tempo de base ( Da ativação dos serviços até o presente momento, contabilizado em meses )
* ServicoTelefone - O cliente possui linhas telefônicas ativas?
* ValorTelefone - Se possuir linhas telefônicas ativas informa o valor do plano habilitado
* MultiplasLinhas - Possui mais de uma linha?
* ServicoInternet - Informa o tipo de serviço de internet habilitado ( Fibra, DSL ou Não, caso não tenha )
* ValorInternet - Valor do serviço de internet habilitado
* ServicoSegurancaOnline - O cliente possui serviço de segurança como antivirus e VPN?
* ValorSegurancaOnline  - O valor do serviço de segurança online caso tenha
* ServicoBackupOnline - O cliente possui serviço de backup de dados?
* ValorBackupOnline - O valor do serviço de backup caso tenha
* ProtecaoEquipamento - O cliente possui seguro dos equipamentos? Obs.: Não gera cobrança e sim fidelização.
* ServicoSuporteTecnico - O cliente pode solicitar suporte técnico para instalação ou mudança de local de pontos? Obs.: Não gera cobrança e sim fidelização.  
* ServicoStreamingTV - Foi habilitado serviço de streaming como Netflix, Amazon Prime e HBO Max?
* ValorServiçoStreaming - O valor do serviço caso esteja habilitado
* ServicoFilmes - O cliente contrata pacotes de Pay-per-view?
* ValorServicoFilmes - O valor do serviço caso esteja habilitado
* TipoContrato - Qual o tipo de contrato? ( Mensal, Anual ou de 2 ANOS)
* FaturaDigital - Cliente habilitou fatura digital? Obs.: Se sim ele deixa de receber a fatura física e recebe apenas por whatsapp ou email
* FormaPagamento - Forma de pagamento escolhida: boleto eletrônico, boleto impresso, débito automático ou cartão de crédito?
* ValorMensal - Valor total da fatura do cliente
* Churn - Informa se o cliente cancelou ou se mantem os serviços ativos     

