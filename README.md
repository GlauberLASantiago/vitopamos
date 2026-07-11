# ViToPaMoS 🎼

**Visualizador e Tocador de Partituras para Moodle e Sites**

O **ViToPaMoS** é uma ferramenta web desenvolvida para facilitar o ensino e a prática musical através da visualização e execução de partituras no formato **MusicXML**. Criado pelo professor **Glauber Santiago** (DAC/UFSCar), ele permite transformar arquivos de partitura em players interativos que podem ser facilmente incorporados em ambientes virtuais de aprendizagem como o **Moodle**.

<img width="1322" height="917" alt="image" src="https://github.com/user-attachments/assets/779473f6-6d5d-4b53-bb0c-f28d94260b45" />


---

## ✨ Principais Funcionalidades

- 📄 **Suporte Abrangente**: Carrega arquivos `.xml`, `.musicxml` e comprimidos `.mxl` — via clique ou **arrastar e soltar** diretamente na área de carregamento.
- 💾 **Projetos (.vtp)**: Salve e carregue projetos completos (partitura + todas as configurações do mixer, cifras editadas, BPM, BT Delay) em arquivos `.vtp`.
- 🎹 **Áudio de Alta Qualidade**: Utiliza Soundfonts de General MIDI para uma reprodução fiel de mais de 100 instrumentos.
- 🥁 **Percussão Inteligente**:
  - Mapeamento customizado de peças de bateria.
  - Bloqueio automático de transposição para kits de bateria (mantendo o mapeamento MIDI correto).
  - Interface dedicada para ajustar sons individuais de percussão (botão 🛠️ Percussão).
- 🎵 **Acompanhamento de Cifras**:
  - **Cifra: baixo** — toca a nota fundamental (ou nota do baixo) de cada acorde cifrado.
  - **Cifra: acordes** — toca o acorde completo com o instrumento de sua escolha (padrão: Piano elétrico Rhodes).
  - **Padrões de ritmo variados**: note longa (1–4 tempos), arpejo em colcheias, acordes em semínimas/colcheias ou padrão semínima pontuada + colcheia.
  - Suporte a dezenas de tipos de acordes: tríades, sétimas, nonas, décimas-primeiras, décimas-terceiras, sus, add, power chord, notação brasileira (7M, m7M) e mais.
- ✏️ **Editor de Cifras**:
  - Ative o modo **"Editar Cifras"** para adicionar, editar, mover e excluir acordes cifrados diretamente na partitura.
  - Clique em qualquer cifra no SVG para selecioná-la; duplo clique para editar o nome inline.
  - Use as teclas ← → para mover o acorde entre posições dentro do compasso ou entre compassos; Delete/Backspace para excluir.
  - Botão **"Adicionar Acorde"** abre diálogo para inserir um novo acorde em qualquer compasso.
  - **Timeline de Cifras**: painel com todos os acordes agrupados por compasso para acesso rápido.
- 🔄 **Transposição em Tempo Real**: Altere o tom global (±6 semitons) instantaneamente durante a reprodução.
- ⏱️ **Controle Total**:
  - Ajuste de **BPM** (andamento), com leitura automática do tempo do arquivo.
  - **Metrônomo** integrado e sincronizado (suporte a compassos compostos).
  - **Reverberação** ajustável (0–100%).
  - Controle de volume, **Mute** e **Solo** por instrumento.
  - Ajuste de **oitava/transposição individual** por faixa (8vb, In loco, 8va etc.).
  - **Trecho de Execução**: defina o compasso inicial e final para repetir passagens específicas.
- 🎨 **Interface Premium**:
  - Temas **Claro** e **Noturno** (Dark Mode).
  - Controle de **Zoom** e três modos de layout: Automático, Do Arquivo ou Fixar (N compassos por linha).
  - **Cursor Inteligente**: destaque por Nota, por Compasso ou sem cursor.
  - Edição do **Título** da peça diretamente na interface (campo Título + botão Aplicar).
- 📡 **BT Delay**: Ajuste de atraso visual (0–1200 ms) para sincronizar o cursor com fones de ouvido Bluetooth sem afetar o áudio.
- ⌨️ **Atalhos de Teclado**: Teclas **1–5** alternam o Solo das primeiras faixas; ← → Delete para mover/excluir cifras no modo de edição.
- 🌍 **Exportação Facilitada**:
  - **Copiar HTML**: gera um arquivo HTML individual e completo (self-contained) e copia para a área de transferência.
  - **Baixar HTML**: salva o arquivo HTML diretamente no computador.
  - **Mixer em Acordeon**: painel colapsável no arquivo exportado que permite ao aluno ajustar instrumentos individualmente sem sobrecarregar a interface inicial.
  - **Rolagem Automática**: o cursor acompanha a execução rolando a página automaticamente no arquivo exportado.
  - Opção **"Ocultar Painel no Exportado"** para uma interface focada apenas na partitura.

---

## 🚀 Como Usar

1. **Carregamento**: Clique em **"Carregar partitura"** e selecione seu arquivo MusicXML, ou arraste e solte o arquivo na área indicada. Para retomar um trabalho anterior, use **"Carregar Projeto (.vtp)"**.
2. **Configuração Geral**:
   - Ajuste **BPM**, **Zoom**, **Layout** e **Transposição** global na barra de controles.
   - Ative o **Metrônomo** e/ou a **Reverberação** conforme necessário.
   - Defina o **Trecho** (compasso inicial e final) para isolar passagens.
3. **Mixer de Instrumentos**:
   - Use **Mute** e **Solo** por faixa para isolar vozes.
   - Ajuste o **volume**, a **oitava** e o **timbre** (General MIDI) de cada instrumento.
   - Para bateria, clique em **🛠️ Percussão** para remapear sons individuais.
4. **Acompanhamento de Cifras**:
   - As faixas **"Cifra: acordes"** e **"Cifra: baixo"** aparecem automaticamente se a partitura contiver cifras.
   - Escolha o padrão rítmico e o instrumento de cada faixa no Mixer.
5. **Edição de Cifras** *(opcional)*:
   - Clique em **"Editar Cifras"** para ativar o modo de edição.
   - Clique em qualquer acorde na partitura para selecioná-lo; duplo clique para alterar o nome.
   - Use o botão **"Adicionar Acorde"** para inserir novos acordes por compasso.
6. **Metadados**: Edite o título da peça no campo **Título** e clique em **Aplicar**.
7. **Salvar Projeto**: Clique em **"Salvar Projeto (.vtp)"** para guardar toda a configuração atual.
8. **Exportar**:
   - Ative **"Ocultar Painel no Exportado"** se quiser uma interface limpa para o aluno.
   - Use **"Copiar HTML"** para colar no editor do Moodle (ícone `</>`), ou **"Baixar HTML"** para enviar o arquivo diretamente.

---

## 🎓 Uso Pedagógico (Moodle)

O ViToPaMoS foi desenhado pensando no professor de música. Ao exportar o HTML, o professor pode criar atividades interativas onde o aluno ouve a partitura, altera o andamento para praticar, isola apenas o seu instrumento (Mute/Solo) ou transpõe para o seu instrumento específico. O **Mixer em Acordeon** no arquivo exportado permite que usuários avançados façam ajustes finos sem poluir a visualização inicial da página. O recurso de **cifras completas** (acordes + baixo) abre possibilidades para atividades de harmonia, percepção e arranjo, enquanto o **Editor de Cifras** permite ao professor adaptar ou corrigir as cifras diretamente no ViToPaMoS antes de exportar.

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
