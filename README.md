# ViToPaMoS 🎼

**Visualizador e Tocador de Partituras para Moodle e Sites**

O **ViToPaMoS** é uma ferramenta web desenvolvida para facilitar o ensino e a prática musical através da visualização e execução de partituras no formato **MusicXML**. Criado pelo professor **Glauber Santiago** (DAC/UFSCar), ele permite transformar arquivos de partitura em players interativos que podem ser facilmente incorporados em ambientes virtuais de aprendizagem como o **Moodle**.

<img width="1322" height="917" alt="image" src="https://github.com/user-attachments/assets/779473f6-6d5d-4b53-bb0c-f28d94260b45" />


---

## ✨ Principais Funcionalidades

- 📄 **Suporte Abrangente**: Carrega arquivos `.xml`, `.musicxml` e comprimidos `.mxl`.
- 🎹 **Áudio de Alta Qualidade**: Utiliza Soundfonts de General MIDI para uma reprodução fiel de diversos instrumentos.
- 🥁 **Percussão Inteligente**: 
  - Mapeamento customizado de peças de bateria.
  - Bloqueio automático de transposição para kits de bateria (mantendo o mapeamento MIDI correto).
  - Interface dedicada para ajustar sons individuais de percussão.
- 🎸 **Baixo das Cifras**: Recurso pedagógico exclusivo que toca a nota fundamental dos acordes cifrados.
  - **Duração Selecionável**: Escolha entre 1, 2, 3 ou 4 tempos (padrão inicial de 2).
  - Ideal para treino de harmonia e ritmo.
- 🔄 **Transposição em Tempo Real**: Altere o tom da música e do acompanhamento instantaneamente.
- ⏱️ **Controle Total**:
  - Ajuste de **BPM** (andamento).
  - **Metrônomo** integrado e sincronizado.
  - Controle de volume, **Mute** e **Solo** por instrumento.
- 🎨 **Interface Premium**:
  - Temas **Claro** e **Noturno** (Dark Mode).
  - Controle de **Zoom** e layout de compassos por linha.
  - **Cursor Inteligente**: Destaque por Nota ou Compasso.
- 🌍 **Exportação Facilitada**:
  - Gere um arquivo HTML **individual e completo** (self-contained).
  - **Mixer/Acordeon no Exportado**: Novo painel colapsável que permite ao aluno ajustar instrumentos individualmente sem sobrecarregar a interface.

---

## 🚀 Como Usar

1. **Carregamento**: Clique em **"Carregar partitura"** e selecione seu arquivo MusicXML.
2. **Configuração**:
   - Ajuste o título, andamento e escolha os instrumentos desejados no painel de mixagem.
   - Configure a duração e o tom do **Baixo das Cifras**.
   - Use a **Ferramenta de Percussão** para mapear sons de bateria.
3. **Player**: Use os botões de Play, Pause e Stop. Clique na partitura para mover o cursor para um ponto específico.
4. **Exportar**: Ative **"Ocultar Painel no Exportado"** se desejar uma interface focada apenas na partitura, ou deixe desativado para o aluno ter acesso ao Mixer. Clique em **"Copiar HTML"** e cole no Moodle.

---

## 🎓 Uso Pedagógico (Moodle)

O ViToPaMoS foi desenhado pensando no professor de música. Ao exportar o HTML, o professor pode criar atividades interativas onde o aluno ouve a partitura, altera o andamento para praticar, isola apenas o seu instrumento (Mute/Solo) ou transpõe para o seu instrumento específico. O novo **Mixer em Acordeon** no arquivo exportado permite que usuários avançados façam ajustes finos sem poluir a visualização inicial da página.

---

## 🛠️ Tecnologias Utilizadas

- **[OpenSheetMusicDisplay (OSMD)](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay)**: Renderização vetorial da partitura.
- **[Soundfont-player](https://github.com/danigb/soundfont-player)**: Engine de áudio para instrumentos melódicos.
- **[WebAudioFont](https://github.com/surikov/webaudiofont)**: Motor de áudio para percussão e bateria.
- **[JSZip](https://stuk.github.io/jszip/)**: Suporte a arquivos MusicXML comprimidos (.mxl).
- **Vanilla JS & CSS**: Performance otimizada.

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
