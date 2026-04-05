# ViToPaMoS 🎼

**Visualizador e Tocador de Partituras para Moodle e Sites**

O **ViToPaMoS** é uma ferramenta web desenvolvida para facilitar o ensino e a prática musical através da visualização e execução de partituras no formato **MusicXML**. Criado pelo professor **Glauber Santiago** (DAC/UFSCar), ele permite transformar arquivos de partitura em players interativos que podem ser facilmente incorporados em ambientes virtuais de aprendizagem como o **Moodle**.

<img width="1122" height="927" alt="image" src="https://github.com/user-attachments/assets/b61711d9-ed4c-468a-9b1c-2a1542355b76" />

---

## ✨ Principais Funcionalidades

- 📄 **Suporte Abrangente**: Carrega arquivos `.xml`, `.musicxml` e comprimidos `.mxl`.
- 🎹 **Áudio de Alta Qualidade**: Utiliza Soundfonts de General MIDI para uma reprodução fiel de diversos instrumentos.
- 🥁 **Percussão Inteligente**: 
  - Mapeamento customizado de peças de bateria.
  - Interface dedicada para ajustar sons individuais de percussão.
- 🎸 **Baixo das Cifras**: Recurso pedagógico exclusivo que toca a nota fundamental dos acordes cifrados de forma independente, ideal para treino de harmonia e ritmo.
- 🔄 **Transposição em Tempo Real**: Altere o tom da música e do acompanhamento instantaneamente.
- ⏱️ **Controle Total**:
  - Ajuste de **BPM** (andamento).
  - **Metrônomo** integrado e sincronizado.
  - Controle de volume, **Mute** e **Solo** por instrumento.
- 🎨 **Interface Premium**:
  - Temas **Claro** e **Noturno** (Dark Mode).
  - Controle de **Zoom** e layout de compassos por linha.
  - **Cursor Inteligente**: Destaque por Nota ou Compasso, otimizado para performance.
- 🌍 **Exportação Facilitada**: Gere um arquivo HTML **individual e completo** (self-contained) pronto para ser colado em blocos HTML do Moodle ou qualquer site.

---

## 🚀 Como Usar

1. **Carregamento**: Clique em **"Carregar partitura"** e selecione seu arquivo MusicXML.
2. **Configuração**:
   - Ajuste o título, andamento e escolha os instrumentos desejados no painel de mixagem.
   - Configure o **Baixo das Cifras** se desejar um reforço harmônico.
   - Use a **Ferramenta de Percussão** para mapear sons de bateria.
3. **Player**: Use os botões de Play, Pause e Stop. Clique na partitura para mover o cursor para um ponto específico.
4. **Exportar**: Clique em **"Copiar HTML"** para salvar o código do player na sua área de transferência e use no seu site ou Moodle.

---

## 🎓 Uso Pedagógico (Moodle)

O ViToPaMoS foi desenhado pensando no professor de música. Ao exportar o HTML, o professor pode criar atividades interativas onde o aluno ouve a partitura, altera o andamento para praticar, isola apenas o seu instrumento (Mute/Solo) ou transpõe para o seu instrumento específico.

---

## 🛠️ Tecnologias Utilizadas

- **[OpenSheetMusicDisplay (OSMD)](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay)**: Renderização vetorial da partitura.
- **[Soundfont-player](https://github.com/danigb/soundfont-player)**: Engine de áudio para instrumentos melódicos.
- **[WebAudioFont](https://github.com/surikov/webaudiofont)**: Motor de áudio para percussão e bateria.
- **[JSZip](https://stuk.github.io/jszip/)**: Suporte a arquivos MusicXML comprimidos (.mxl).
- **Vanilla JS & CSS**: Performance otimizada sem dependências pesadas de frameworks.

---

## 👨‍🏫 Créditos

Desenvolvido pelo professor **Glauber Santiago**
**Departamento de Artes e Comunicação (DAC) — UFSCar**

Acesse outros projetos e materiais:
- [Página Institucional](https://servidores.ufscar.br/glauber/)
- [Portfólio de Projetos](https://sites.google.com/view/glauberia)

---

## 📄 Licença

Este projeto é disponibilizado para fins educacionais e acadêmicos. Para outros usos, entre em contato com o autor.

---
*Powered by ViToPaMoS*
