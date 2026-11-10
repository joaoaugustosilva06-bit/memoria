# Mente — Jogo da Memória

Jogo da memória responsivo feito com HTML, CSS e JavaScript puro. Não precisa instalar dependências.

## Como rodar localmente

1. Baixe o repositório ou clone:
   `git clone https://github.com/joaoaugustosilva06-bit/memoria.git`
2. Entre na pasta:
   `cd memoria`
3. Abra o arquivo `index.html` no navegador.

### Alternativa com servidor local

Se tiver Python instalado, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000

## Recursos

- Três níveis: fácil (6 pares), médio (8 pares) e difícil (12 pares).
- Cronômetro, movimentos e progresso.
- Cartas com animação, feedback de combinação e tela de vitória.
- Layout adaptável a celular e desktop.
- Sem bibliotecas ou build.

## Estrutura

- `index.html`: estrutura da página.
- `style.css`: estilos e responsividade.
- `script.js`: lógica do jogo.
