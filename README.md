# detectordeduplicadas
O código em Python lê dados de planilhas do Excel contendo informações de usuários e perfis, realiza a junção desses dados e identifica possíveis duplicados. Os dados consolidados são salvos em uma nova planilha.


Esse código lê um arquivo Excel chamado "admincorp.xlsx" e extrai dados de duas planilhas: "USUARIOS" e "PERFIS". Ele então une esses dados em um único DataFrame com 
base no campo "IdAdministrador" e adiciona uma nova coluna "Cpf" do DataFrame "USUARIOS". Em seguida, ele identifica os registros duplicados com base no campo 
"IdAdministrador" e salva esses registros em uma nova planilha chamada "DUPLICADOS". Ele também salva os dados dos usuários em uma guia chamada "USUARIOS", os dados dos 
perfis em uma guia chamada "PERFIS" e os dados consolidados (ou seja, sem duplicatas) em uma guia chamada "CONSOLIDADO". O resultado final é um arquivo Excel chamado 
"resultado.xlsx" com quatro guias contendo os dados correspondentes.

Este código pode ser adaptado para ser usado em outras situações onde se tem arquivos de Excel com várias planilhas contendo dados relacionados que precisam ser consolidados e analisados.

Por exemplo, imagine que você trabalhe em uma empresa com várias filiais espalhadas pelo país, cada uma com seu próprio arquivo de Excel contendo informações sobre vendas, clientes, funcionários, etc. Você pode usar este código para consolidar esses dados em um único arquivo de Excel, o que facilitaria a análise desses dados.

Outra situação onde este código pode ser útil é em projetos de pesquisa que envolvam a coleta de dados em diferentes fontes, como planilhas, bancos de dados, arquivos 
CSV, entre outros. Ao usar este código para consolidar esses dados, é possível economizar tempo e esforço, além de garantir a integridade e consistência dos dados.
