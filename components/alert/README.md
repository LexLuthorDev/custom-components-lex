# Componente de Alerta

Este é um componente de alerta reutilizável para exibir mensagens para os usuários.

## Como usar

1. Inclua o arquivo CSS do componente na sua página HTML:

```html
<link rel="stylesheet" href="custom-components.css" />
```

2. Adicione o HTML do componente onde desejar exibir o alerta:

```html
<div class="alert success">
  <span class="close-btn">&times;</span>
  <strong>Sucesso!</strong> Esta é uma mensagem de sucesso.
</div>
```

- Substitua success pelo tipo de alerta desejado (success, error ou warning).

# Estilos

- Os seguintes estilos CSS estão disponíveis para personalizar o componente:

- .alert: estilo base para o componente de alerta.
- .alert.success: estilo para alerta de sucesso.
- .alert.error: estilo para alerta de erro.
- .alert.warning: estilo para alerta de aviso.
- .close-btn: estilo para o botão de fechar.

# Exemplo

Veja um exemplo completo de utilização do componente na página HTML:

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Exemplo de Componente de Alerta</title>
    <link rel="stylesheet" href="custom-components.css" />
  </head>
  <body>
    <div class="alert success">
      <span class="close-btn">&times;</span>
      <strong>Sucesso!</strong> Esta é uma mensagem de sucesso.
    </div>
  </body>
</html>
```

# Contribuindo

- Se você encontrar algum problema ou tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request.

```css

Esta documentação em Markdown fornece instruções claras sobre como usar o componente, detalhes sobre os estilos disponíveis, um exemplo de uso e incentiva a contribuição de outros desenvolvedores.

```
