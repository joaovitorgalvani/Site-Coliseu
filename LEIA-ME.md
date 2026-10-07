# Pasta do projeto — como usar

Esta é a pasta do site do seu grupo. **Abra ela inteira no VS Code** (`Arquivo → Abrir pasta`),
nunca os arquivos soltos — é isso que faz o editor, o Copilot e a pré-visualização enxergarem
o projeto todo.

## O que tem aqui

| Arquivo | Para que serve |
|---|---|
| `instrucao.md` | **O mais importante.** É o pedido que você faz para a IA. Vem com as seis partes vazias — você preenche, e **o arquivo inteiro vai para o chat, de uma vez** |
| `modelo-instrucao.md` | A referência: o que entra em cada uma das seis partes, com exemplos. **Só de leitura, não escreva nele** |
| `iteracoes.md` | O registro do que você foi pedindo depois da primeira versão. Vale nota no memorial |
| `index.html` | A página inicial. Está quase vazia de propósito — é ela que a IA vai preencher |
| `estilo.css` | A aparência do site. Também começa vazio |
| `imagens/` | Logo, fotos e tudo que for imagem do projeto |

## A ordem de trabalho

1. **Preencha o `instrucao.md` primeiro.** As seis partes, com o material que você já tem:
   briefing (Entrega 1) e mapa do site + wireframes (Entrega 2). Com o `modelo-instrucao.md`
   aberto ao lado, para consultar o que entra em cada parte
2. Só então abra o chat do Copilot e **cole o `instrucao.md` inteiro**, de uma vez
3. Quando o resultado voltar, **anote no `iteracoes.md`** cada coisa que você pediu depois

> ⚠️ **Não rascunhe no chat — escreva no arquivo primeiro.** A conversa até fica salva no
> VS Code, dá para reabrir. Mas ela não é o projeto, por três motivos práticos:
>
> - **a cota do Copilot é limitada.** Cada mensagem consome. Quem vai pedindo aos pedaços
>   queima a cota antes de o site ficar de pé;
> - **a conversa fica na conta e na máquina em que você logou** — não vem junto na pasta, não
>   se entrega ao cliente e não entra no memorial. E no laboratório a máquina é de todo mundo;
> - **pedido espalhado em cinco mensagens não é instrução, é conversa.** É assim que nasce o
>   site ruim que vocês viram na aula.

> ⚠️ **Não cole o `modelo-instrucao.md` nem o `iteracoes.md` no chat.** Só o `instrucao.md`.
> Os exemplos do modelo falam de uma cafeteria que não é o seu cliente — se eles forem junto,
> o site volta com pedaços dela.

## Para ver o site

Duas formas, as duas funcionam:

- **Clique duas vezes no `index.html`** — abre no navegador. Depois de cada mudança, `F5`
- **Live Preview / Live Server** no VS Code — atualiza sozinho enquanto você edita

## Nome da pasta

Renomeie esta pasta para o nome do seu projeto, sem espaço e sem acento:
`cafe-botanica`, `estudio-lima`, `pet-shop-alegria`.
