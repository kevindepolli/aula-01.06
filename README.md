# aula-01.06

CSS

- Pode ser aplicado em qualquer elemento
- body {background-color: #FF0000;}
- Inline -> <body style="background-color: #FF0000;">
    - Vantagem: Específico, "se tiver 10 tags p e quiser modificar apenas uma".

- Interno: <style type="text/css">
            body {background-color: #FF0000;}
          </style>

- Externo: mais recomendado
    <link rel="stylesheet" type="text/css" href="style/style.css" />

TAGS

- color -> muda a cor do elemento.

- background-color -> imagem de fundo.

- background-image -> imagem de fundo.
    background-image: url("butterfly.gif");
    backgorund-repeat -> controla as repetições da imagem de fundo.

- background-attachment -> define se  aimagem irá rolar ou não juntamente com a tela.

- background-position -> alterar o posicionameno padrão.
    coordenadas, porcentagem, posição (top, right,...)

- Notação resumida: precisa ser na ordem, mas pode faltar.
    ordem: color, image, repeat, attachment, position