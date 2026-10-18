# Editor de Fluxograma — Planta Virtual

Editor de fluxograma de processo no navegador: arraste ativos (bomba, trocador de calor, PSV, tanque e outros) para a área de desenho, conecte as portas e exporte o desenho em JSON.

**Acesse:** https://projetoindustrial.github.io/editor-fluxograma/

- Funciona no celular: toque num ativo para adicioná-lo, arraste o cabeçalho do bloco para mover e a bolinha de uma porta até outra para conectar.
- Arquivo único (`index.html`), sem dependências externas e sem coleta de dados. O desenho fica só no seu aparelho.
- Na versão pública, os botões que dependem de um servidor local (Carregar, Salvar, Executar, HydroCalc e Sessão do ecossistema) ficam ocultos.
- Ferramenta didática, de uso experimental. Projeto independente.

## Rodar localmente

`python -m http.server` na pasta e abrir `http://localhost:8000/`.
