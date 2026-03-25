No primeiro commit implementei a passagem de parâmetros obrigatórios na navegação e criei uma rota dinâmica "perfil/{nome}" no Navigation.

O botão da tela de menu passou a navegar enviando um nome na URL(dado mockado).

A PerfilScreen foi modificada para receber esse parâmetro e exibi-lo na tela.


No primeiro ajuste, implementei o envio de um parâmetro opcional na navegação para a tela de pedidos.

Pra isso defini uma rota no formato "pedidos?cliente={cliente}" utilizando "navArgument", além de configurar um valor padrão como “Cliente Genérico”.

Também adaptei a PedidosScreen para capturar esse parâmetro e exibi-lo na interface.
