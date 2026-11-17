# CriadorMapa

Um pequeno projeto em JavaScript para criar e visualizar um mapa em estilo ASCII diretamente no terminal.

## Visão geral

O script `criarMapa.js` recebe uma matriz de linhas representando o cenário do mapa e organiza os elementos em uma estrutura final que pode ser exibida no console. O projeto foi pensado para gerar mapas simples com elementos visuais como blocos, paredes e estruturas.

## Estrutura do projeto

- `criarMapa.js` — script principal com a lógica de criação do mapa e um exemplo de uso.
- `package-lock.json` — arquivo de lock do npm, gerado automaticamente pelo ambiente.

## Requisitos

- Node.js instalado na máquina
- Terminal ou prompt de comando

## Como executar

Na raiz do projeto, rode:

```bash
node criarMapa.js
```

## Personalização

O mapa de exemplo está definido na variável `mapa1` dentro do arquivo `criarMapa.js`. Para criar outro cenário, basta alterar os valores dessa matriz:

```javascript
let mapa1 = [
  "  __    __    __    __    __    __    __    __    #*******************************************",
  " (00)  (00)  (00)  (00)  (00)  (00)  (00)  (00)   #*******************************************",
  "(0000)(0000)(0000)(0000)(0000)(0000)(0000)(0000)  #*******************************************"
]
```

Depois, o script chama a função `criarMapa(mapa1)` e imprime o resultado no console.

## Exemplo de saída

Ao executar o programa, você verá uma matriz com as linhas do mapa no terminal, permitindo verificar a estrutura visual do cenário gerado.

## Observação

Este projeto é uma base simples e pode ser expandido para adicionar:

- diferentes tipos de tiles ou blocos;
- geração procedural de mapas;
- leitura de mapas a partir de arquivos externos;
- interface visual em browser ou terminal mais avançada.

---

Se quiser, posso também criar uma versão mais profissional do README com badges, instruções de instalação, exemplos de mapas e uma seção de "como contribuir".