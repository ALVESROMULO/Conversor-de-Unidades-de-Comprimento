# Conversor de Unidades de Comprimento

Um conversor simples que transforma valores em metros para unidades do sistema imperial (jardas, pés, polegadas e milhas).

## Funcionalidades

- Conversão de metros para:
  - Jardas (yd)
  - Pés (ft)
  - Polegadas (in)
  - Milhas (mi)
- Interface limpa e intuitiva
- Cálculos precisos com até 6 casas decimais
- Validação de entrada para evitar erros

## Como Usar

1. Insira o valor em metros no campo de entrada
2. Selecione a unidade de destino no menu suspenso
3. Clique no botão "Converter"
4. Veja o resultado exibido abaixo do botão

## Fatores de Conversão Utilizados

- 1 metro = 1.09361 jardas
- 1 metro = 3.28084 pés
- 1 metro = 39.3701 polegadas
- 1 metro = 0.000621371 milhas

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## Instalação

Não requer instalação. Basta abrir o arquivo `index.html` em qualquer navegador moderno.

```bash
git clone https://github.com/seu-usuario/conversor-unidades.git
cd conversor-unidades
```

## Personalização

Você pode modificar:
- O número de casas decimais alterando o parâmetro em `toFixed()`
- O estilo visual editando as classes CSS
- Os fatores de conversão no objeto `fatores`

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
