# Calculadora web

![Calculadora](image.png)


Calculadora simples no navegador: números de **0** a **9**, operações **adição**, **subtração**, **multiplicação** e **divisão**, com interface em tema escuro e um único arquivo HTML (marcação, estilo e script juntos).

**Repositório:** [github.com/euAlt/calculadora](https://github.com/euAlt/calculadora)

## Funcionalidades

- Teclado numérico completo (0–9).
- Operadores: `+` (somar), `−` (subtrair), `×` (multiplicar), `÷` (dividir).
- `=` calcula o resultado da operação em andamento.
- `C` limpa o visor e o estado da conta.
- Divisão por zero exibe **Erro** no visor.
- Layout responsivo e acessível (`aria-label`, `aria-live` no display).

## Como usar

1. Clone ou baixe o repositório.
2. Abra o arquivo **`calculadora.html`** no navegador (duplo clique ou arrastar o arquivo para uma aba).

Não é necessário instalar dependências nem rodar servidor; tudo roda localmente no cliente.

Para desenvolvimento, você pode usar a opção “Abrir com Live Server” (ou similar) no editor — é opcional.

## Uso rápido na calculadora

1. Digite o primeiro número.
2. Toque em uma operação (`+`, `−`, `×` ou `÷`).
3. Digite o segundo número.
4. Toque em `=` para ver o resultado.
5. Use `C` para começar de novo.

É possível encadear operações: após um resultado, escolha outro operador e continue digitando.

## Estrutura do projeto

| Arquivo           | Descrição                                      |
| ----------------- | ---------------------------------------------- |
| `calculadora.html`| Página única: estrutura, CSS e JavaScript.     |
| `LICENSE`         | Licença MIT.                                   |

## Tecnologias

- HTML5  
- CSS3 (variáveis CSS, grid, layout flexível)  
- JavaScript (ES5+ compatível com navegadores modernos, sem frameworks)

## Licença

Este projeto está sob a **licença MIT**. Veja o arquivo [`LICENSE`](LICENSE) para o texto completo.

---


