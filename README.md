# 🦦 MakeMd — Conversor de arquivos para Markdown

## Por que converter seus arquivos para Markdown antes de enviá-los ao Claude?

Quando você envia um PDF, um Word ou uma planilha Excel diretamente ao Claude ou a outro modelo de linguagem, o modelo precisa processar o arquivo completo: imagens incorporadas, metadados, formatos de página, cabeçalhos decorativos, estilos tipográficos e todo o "ruído" visual que não traz informação real. Esse processamento consome **tokens**, e tokens custam dinheiro ou têm limite de uso.

Um arquivo Markdown (`.md`) é texto simples estruturado. Sem imagens decorativas, sem camadas de formatação, sem bytes desperdiçados. É conteúdo puro. Ao converter seu documento para Markdown antes de enviá-lo ao Claude:

- **Você reduz o consumo de tokens em até 60–80%** dependendo do tipo de arquivo
- O modelo lê mais rápido e responde com maior precisão, porque tem menos ruído para filtrar
- Você pode incluir documentos muito mais longos dentro do mesmo contexto
- Você economiza créditos se usar Claude Pro, Teams ou API

Em resumo: **mesmo conteúdo, muito menos custo**.

---

## O que é o MakeMd?

Em 2024, a **Microsoft lançou o [markitdown](https://github.com/microsoft/markitdown)**, uma biblioteca de código aberto que converte dezenas de formatos de arquivo para Markdown de forma automática. É gratuita e poderosa, mas feita para desenvolvedores: requer terminal e conhecimentos técnicos para utilizá-la.

**MakeMd** é a interface visual sobre essa biblioteca. Um aplicativo de desktop com dark mode e conversão em lote — sem instalar nada, sem abrir nenhum terminal, sem escrever uma única linha de código.

Você baixa o `.exe`, abre, seleciona seus arquivos e pronto.

---

## Como usar?

### 1. Abra o MakeMd.exe

Duplo clique. Não requer instalação. Não deixa rastros no sistema. Se o Windows mostrar um aviso de segurança na primeira vez, escolha "Executar assim mesmo" — é normal para executáveis portáteis sem assinatura digital.

### 2. Selecione seus arquivos

Use o botão **"selecionar arquivos"** para adicioná-los. Você pode adicionar vários de uma vez — todos ficam em uma fila visual com nome, formato e estado de cada um.

### 3. Escolha onde salvar (opcional)

Por padrão, o `.md` é salvo na mesma pasta do arquivo original. Se quiser centralizar os resultados, use o seletor na barra superior.

### 4. Converta tudo

Um clique em **▶ Converter Tudo** processa a fila completa. Cada arquivo mostra seu progresso. Se algo falhar, o erro aparece ao lado desse item sem interromper o restante.

### 5. Cole o `.md` no Claude

Abra o `.md` com o Bloco de Notas, copie o conteúdo e cole no Claude. Ou anexe diretamente. O modelo recebe texto limpo e estruturado, e trabalha com muito mais eficiência.

---

## Formatos suportados

| Categoria | Formatos |
|---|---|
| Documentos | PDF, DOCX |
| Apresentações | PPTX |
| Planilhas | XLSX |
| Web e dados | HTML, CSV, JSON, XML |
| Imagens (OCR) | PNG, JPG, GIF |
| Áudio | MP3, WAV |
| Arquivos comprimidos | ZIP |

---

## Características

- **Portátil** — um único `.exe`, sem instalação, sem dependências
- **Dark mode** — interface confortável para trabalhar por horas
- **Conversão em lote** — todos os arquivos de uma vez
- **Trilíngue** — Espanhol, Inglês e Português
- **Gratuito** — sem publicidade, sem cadastro, sem telemetria

---

## Requisitos

- Windows 10 / 11 (64 bits)
- Nada mais

---

## ☕ Apoiar o projeto

MakeMd é gratuito. Se foi útil para você e quiser colaborar com o desenvolvimento:

👉 [cafecito.app/mestizokabalin](https://cafecito.app/mestizokabalin)

---

*Motor de conversão: [markitdown](https://github.com/microsoft/markitdown) © Microsoft — MIT License*

