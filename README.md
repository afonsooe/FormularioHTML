
# Formulário Completo — Estilização com CSS

Trabalho da disciplina de Programação Web I, referente à estilização de um formulário HTML com CSS externo (conteúdo das Aulas 4 a 7: Formatação de Textos, Box Model, Listas/Tabelas e Formulários).

## Estrutura do Projeto

- `index.html` — marcação do formulário e da tabela de resumo.
- `style.css` — estilização aplicada via CSS externo.

## Seções do Formulário

- Dados Pessoais
- Endereço
- Preferências
- Upload de Arquivos
- Informações de Login
- Botão Enviar

## Tabela de Resumo dos Campos

Tabela HTML com `thead`, `tbody` e `tfoot`, listando todos os campos do formulário, seus tipos e se são obrigatórios.

## Técnicas de CSS Aplicadas

- `fieldset` / `legend` para agrupamento visual dos campos
- `label { display: block }` + `input { display: block; width: 100% }` para alinhamento de rótulos e campos
- `box-sizing: border-box` para manter os campos dentro dos limites do `fieldset`
- Pseudo-classes `:hover` e `:focus` nos campos de entrada
- `cursor: pointer` no botão de envio
- `border-radius`, `box-shadow`, `max-width` e `margin: auto` para acabamento visual e centralização
- Zebramento de linhas (`tr:nth-child(even)`) e `tr:hover` na tabela de resumo
- `text-transform: uppercase` e `letter-spacing` no cabeçalho da tabela

## Evolução do Projeto

O formulário começou como uma versão apenas em HTML, sem estilização. Após a inclusão do requisito de CSS pelo professor, o projeto evoluiu para aplicar as técnicas vistas em aula, migrando também elementos presentacionais do HTML (como `<b>`, `<br>` e `align`) para regras equivalentes em CSS.

## Como Visualizar

1. Clone o repositório.
2. Abra o arquivo `index.html` em um navegador (ou use o servidor embutido do IntelliJ).

## Autor

[Seu nome] — [Curso / Universidade]



