## Autorização e Confirmação de Resgate (Apenas débito de pontos)

Basicamente é apenas um débito de pontos para um fim de qualquer espécie, em qualquer plataforma que aceite a moeda da Ltm Fidelidade como pagamento e/ou transferência.

Neste caso o CloudLoyalty atua como uma carteira ou conta corrente de pontos.

Neste cenário os parceiros **não fazem parte** do portfólio do CloudLoyalty e as **"compras são feitas externamente".**

No fluxo de **Autorização e Confirmação de Resgate** a aplicação cliente é responsável pela gestão do carrinho do usuário.

### Exemplos de cenários em que clientes utilizam o CloudLoyalty como carteira ou conta corrente:

 - Compra de milhas aéreas.
 - Compras de passagens Aéreas.
 - Compra e reserva de restaurantes.
 - Venda de seguros com pagamento em pontos.

Para entender melhor o portfólio de parceiros acesse:
[Qual o modelo de resgates devo adotar?](/purchase/readme.md)

    O CloudLoyalty não efetua chamadas em fornecedores nos casos de compras externas, neste cenário o CloudLoyalty atua apenas como conta-corrente (Account). Ou seja só o débito e estorno dos pontos. É de responsabilidade da aplicação cliente efetuar a compra do produto / servico no parceiro / fornecedor (Vendor).

    Isso aumenta a autonomia da aplicação cliente e abre a possibilidade de integrar com qualquer serviço desejado.

    Para tal é necessário um código de vendor (vendor id), pois neste caso é criado um parceiro genérico para representar todos os resgates. O vendor é necessário para finalidades de conciliação e outros tramites administrativos.

### Como funciona

- Autorização de compra

  ![Authorize Purchase](/images/purchase-external-1-diagram.svg)

- Compra externa (Responsabilidade da aplicação cliente)

  ![External Vendor](/images/purchase-external-2-diagram.svg)

- Confirmação de compra

  ![Confirm Purchase](/images/purchase-external-3-diagram.svg)

## Próximos passos

[Authorização de compra](/purchase/authorize.md)
