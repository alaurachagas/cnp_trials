# Multiagent Contract Net Protocol Trials

## Plano de Ação!

Acho que a ideia mais inteligente é ter apenas o código de 2 agentes, um responsável pelos *initiators* e um responsavel pelos *participants*. Cada um desses agentes criará os nosso outros agentes que irão operar no sistema.

Existe uma forma de criar **funções** e **organizações** no Jason, veja nesse link [LINK](https://jacamo-lang.github.io/getting-started#participating-to-an-organisation). Caso seja possivel, podemos vincular os novos agentes que serão criados pelos responsáveis em diferences funções de uma organização. Vamos exemplificar:

Digamos que nosso sistema seja uma feira de artesões. Temos vários artesões expondo suas habilidades, alguns fazem queijo, alguns fazer produção de bebidas, alguns trabalham com madeira e outros com ferragem (Tirei essa ideia dos mercados de Natal da Alemanha :] ). Assim que a feira abre, clientes vão marchar pela feira e comparar os preços e fazer orçamentos para peças customizadas. Aqui que entra os nossos *initiators* e *participants*. 

Então teremos grupos de:

- *participants* que irão oferecer diferentes serviços;

- *initiators* que vão querer contratar entre 1 a 10 serviços diferentes. (Acredito que possa ser varios de um único serviço)

### Como deve ser a estrutura dos *participants*

1. Eles deves ser identificados por **serviço**.

2. Eles devem possuir um valor fixo (aleatorizado) pelo serviço prestado.

3. Eles devem ser capazes de receber requisições, informar valor e aceitar o serviço.

4. Eles devem possuir um mecanismo de rejeição de serviço quando ele já tiver aceitado um número x de serviços.

5. Ele deve demorar algum tempo para concluir cada serviço?


### Como deve ser a estrutura dos *initiators*

1. Eles devem querer a realização de um número i de serviços (com 1 < i < 10).

2. Eles devem ser capazes de solicitar o serviço, e analisar diferentes propostas (escolhendo a melhor).



