# moneytogo — mudou de lugar

O MoneyToGo passou a ser servido na **raiz do domínio**:

**<https://brunocastiglia.github.io/>**

O código e toda a história dos commits foram para o repositório
[`brunocastiglia.github.io`](https://github.com/BrunoCastiglia/brunocastiglia.github.io),
que é onde o desenvolvimento continua.

## Por que mudou

Para o AdSense o "site" é o domínio inteiro, e quem revisa entra pela raiz.
Enquanto o app morava em `/moneytogo/`, a raiz era uma página-vitrine de três
linhas — o retrato de "conteúdo de baixo valor" que reprova a inscrição.

## Por que este repositório continua existindo

Só para o endereço antigo não ficar morto. O `index.html` daqui é um
redirecionamento com `canonical` para a raiz. Servir uma segunda cópia do site
em `/moneytogo/` criaria conteúdo duplicado no mesmo domínio, que é justamente
o que se queria evitar.
