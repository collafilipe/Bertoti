# Bot Telegram

Este código implementa um bot no Telegram que auxilia os usuários a buscar imóveis para aluguel ou venda utilizando Selenium para automatizar a navegação em sites imobiliários como QuintoAndar e Chaves na Mão. Quando o usuário inicia o bot com o comando /start, ele recebe orientações sobre como utilizar as funcionalidades de busca de imóveis. O usuário pode escolher entre as opções de aluguel ou venda, e, em seguida, especificar o tipo de imóvel (casa ou apartamento) e o preço máximo que deseja pagar. O bot coleta essas informações, realiza a busca nos sites em questão, e retorna os links dos imóveis encontrados diretamente no chat do Telegram, facilitando a pesquisa.

O código utiliza a biblioteca telebot para comunicação com o Telegram e o Selenium para automatizar as buscas nos sites. As funções principais são responsáveis por acessar as páginas dos imóveis e filtrar os resultados de acordo com o tipo e o preço informado pelo usuário. Dependendo da escolha entre aluguel ou venda, o bot busca casas ou apartamentos no site relevante e retorna os resultados encontrados. Para controlar o fluxo das interações com o usuário, o bot utiliza estados para acompanhar em que etapa o usuário está (por exemplo, se ele já definiu o preço ou o tipo de imóvel).

Assim, o bot permite que o processo de pesquisa de imóveis seja mais eficiente, automatizando a coleta de informações e exibindo os resultados diretamente no Telegram, sem que o usuário precise acessar os sites manualmente
