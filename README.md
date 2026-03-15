# Player de Partitura

Aplicação web para carregar arquivos **MusicXML**, exibir a partitura na tela e reproduzir as notas com diferentes timbres usando **General MIDI**. O projeto também permite exportar um HTML incorporável com a partitura já embutida, pronto para compartilhamento ou publicação.

## Visão geral

O **Player de Partitura** foi desenvolvido para facilitar a visualização e a reprodução de partituras em formato **.xml** e **.musicxml** diretamente no navegador.

A ferramenta permite:

- carregar uma partitura local
- renderizar a notação musical em SVG
- reproduzir as notas com diferentes timbres
- controlar andamento em BPM
- pausar e retomar a execução
- copiar um HTML pronto com a partitura incorporada

É uma solução útil para fins didáticos, demonstrações musicais, estudo de arranjos e publicação de exemplos musicais em páginas web.

## Funcionalidades

- Upload de arquivos `.xml` e `.musicxml`
- Renderização visual da partitura no navegador
- Reprodução de notas com áudio sintetizado
- Controle de **Play**, **Pause** e **Stop**
- Ajuste manual de **BPM**
- Seleção de diferentes **timbres instrumentais**
- Exportação de um **HTML completo** com a partitura embutida
- Cópia automática do HTML para a área de transferência
- Interface moderna e responsiva

## Timbres disponíveis

- Piano normal
- Piano elétrico Rhodes
- Órgão
- Violão nylon
- Contrabaixo elétrico
- Xilofone
- Flauta
- Oboé
- Clarineta
- Trompa
- Cordas

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript puro (Vanilla JS)
- [OpenSheetMusicDisplay](https://opensheetmusicdisplay.org/)
- [Soundfont Player](https://github.com/danigb/soundfont-player)
- General MIDI SoundFonts

## Como funciona

1. O usuário seleciona um arquivo `.xml` ou `.musicxml`.
2. O conteúdo do arquivo é carregado no navegador.
3. A biblioteca **OpenSheetMusicDisplay** renderiza a partitura em SVG.
4. O sistema percorre os eventos musicais da partitura e extrai:
   - posição temporal
   - altura MIDI
   - duração de cada nota
5. A biblioteca **Soundfont Player** carrega o timbre selecionado.
6. As notas são agendadas no `AudioContext` para reprodução no tempo correto.
7. O usuário pode alterar o BPM ou trocar o timbre.
8. A aplicação também pode gerar um HTML independente contendo:
   - a partitura embutida em Base64
   - o player pronto para uso
   - controles de andamento e timbre

## Estrutura do projeto

O projeto principal está concentrado em um único arquivo:

- `index.html` — interface, estilos e lógica de carregamento, renderização, reprodução e exportação

## Como usar

1. Clone ou baixe o repositório:

```
git clone <URL_DO_REPOSITORIO>
```

2. Abra o arquivo `index.html` no navegador.

3. Clique em **Carregar partitura**.

4. Selecione um arquivo `.xml` ou `.musicxml`.

5. Use os controles para:
   - reproduzir
   - pausar
   - parar
   - ajustar o BPM
   - trocar o timbre

6. Clique em **Copiar HTML** para gerar uma versão incorporável da partitura.

## Exportação de HTML

Ao usar o botão **Copiar HTML**, a aplicação gera um documento HTML completo com:

- partitura embutida em Base64
- renderização automática no navegador
- reprodução por clique
- duplo clique para parar
- seletor de andamento
- seletor de timbre

Esse HTML pode ser colado em outro arquivo, publicado em páginas web ou usado em ambientes educacionais.

## Casos de uso

Este projeto pode ser útil para:

- ensino de leitura musical
- estudo de partituras
- demonstrações musicais online
- materiais didáticos interativos
- publicação de trechos musicais em sites
- experimentação com MusicXML no navegador

## Possíveis melhorias

- destaque visual das notas durante a reprodução
- barra de progresso musical
- suporte a múltiplas vozes mais detalhado
- exportação para MIDI
- suporte offline
- importação por arrastar e soltar
- biblioteca ampliada de timbres

## Público-alvo

- professores de música
- estudantes de música
- pesquisadores
- arranjadores
- músicos
- desenvolvedores de ferramentas educacionais

## Créditos

Desenvolvido para uso educacional e experimental com foco em visualização e reprodução de partituras musicais no navegador.

## Licença

Este projeto pode ser distribuído sob a licença de sua escolha, como por exemplo a licença MIT.
