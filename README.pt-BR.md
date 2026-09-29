# Kalmuri

**Ferramenta de captura gratuita para Windows: captura a tela inteira, uma região, uma janela ou uma página web inteira com uma única tecla de atalho, e grava a tela em MP4.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-4.3.1-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kalmuri?lang=pt)

![Tela do Kalmuri](images/kalmuri-en.webp)

> O programa não tem tradução para português; ele é exibido em inglês. Os nomes de botões e menus abaixo aparecem como na tela.

## Visão geral

Com o Kalmuri você escolhe só duas coisas — o que capturar (**Capture**) e como guardar (**SaveTo**) — e depois basta pressionar `PrintScreen`. Não é preciso abrir janela nem digitar nome de arquivo a cada vez: os resultados vão se acumulando na pasta de salvamento como `K-001.png`, `K-002.png` e assim por diante.

Dá para capturar a tela inteira, uma região fixa, uma área arrastada com o mouse, a janela que você está usando, um único botão dentro de uma janela ou uma página web inteira com rolagem. Com o mesmo atalho você também grava a tela em MP4, pega códigos de cor da tela e transforma o texto de uma imagem em arquivo de texto.

Ao fechar a janela, o Kalmuri continua rodando na área de notificação (bandeja do sistema); uma vez aberto, você pode capturar a qualquer momento com o atalho.

## Principais recursos

- **7 modos de captura** — Tela inteira, região fixa, área arrastada, janela ativa, controle de janela, página web inteira e seletor de cor.
- **Vários tipos de saída** — Arquivos PNG · JPG · GIF · BMP · WebP, vídeo MP4, reconhecimento de texto (TXT), área de transferência, compartilhamento de imagem, impressora e imagem flutuante na tela.
- **Gravação de tela** — Grave a tela inteira ou uma região em MP4, com o som tocado no seu PC se quiser.
- **Captura de página web inteira** — Salve uma página aberta no Edge · Chrome como uma única imagem, até o fim da rolagem.
- **Reconhecimento de texto (OCR)** — Salve o texto da tela capturada em um arquivo de texto.
- **Seletor de cor** — Copie a cor sob o cursor nos formatos HEX · RGB · Web · TColor.
- **Compartilhar capturas** — Envie uma captura para a web e abra-a na hora para compartilhar o link.
- **Floating** — Mantenha uma imagem capturada por cima das outras janelas, no mesmo lugar da captura, como referência.
- **Ajuste da região pelo teclado** — Ajuste a região até o pixel com as setas · `Ctrl`+seta · `Shift`+seta.
- **Configurações práticas** — Atalho personalizável, formato do nome de arquivo (numeração · data e hora), som de captura, incluir o cursor, iniciar com o sistema.
- **8 idiomas** — Coreano · inglês · japonês · chinês · russo · italiano · francês · espanhol.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Download](https://down.kilho.net/kalmuri?lang=pt) |
| Portátil (ZIP) | [Download](https://down.kilho.net/kalmuri?lang=pt&nosetup) |

O instalador abre o Kalmuri assim que a instalação termina e ativa **Run on system start**, para que o Kalmuri inicie na bandeja toda vez que o Windows iniciar. Na versão portátil, descompacte o ZIP e execute `Kalmuri.exe`.

A versão portátil contém só o executável, então **a gravação MP4 e o salvamento em WebP só estão disponíveis na versão instalada**. Todo o resto é igual nas duas.

## Como usar

### Primeiros passos

1. Execute o Kalmuri. Uma janela pequena se abre e o ícone do Kalmuri aparece na área de notificação.
2. Em **Capture**, escolha o que capturar. O padrão é **Full Screen**.
3. Em **SaveTo**, escolha como guardar. O padrão é **PNG**. Escolher JPG · WebP mostra uma caixa de qualidade ao lado; escolher TXT mostra uma caixa de idioma de reconhecimento.
4. Pressione `PrintScreen`. Com um som de obturador, a captura é salva na pasta de salvamento (a área de trabalho, no início) como `K-001.png`.
5. Clique em **Open Folder** para abrir a pasta de salvamento e ver o resultado.
6. Fechar a janela mantém o Kalmuri ativo na bandeja. Clique no ícone para trazer a janela de volta e clique com o **botão direito** na janela ou no ícone para o menu de configurações.

### Organização da tela

**Janela principal**

| Elemento | Função |
|---|---|
| **Capture** | Escolher o que capturar (tabela abaixo) |
| **SaveTo** | Escolher como guardar a captura (tabela abaixo). JPG · WebP mostram uma caixa de qualidade (100 – 60), TXT uma de idioma de reconhecimento |
| **Open Folder** | Abre a pasta de salvamento no Explorador |
| **Crafted by Kilho** | Abre a página de apresentação do Kalmuri |

**Capture**

| Item | O que é capturado |
|---|---|
| **Full Screen** | A tela inteira |
| **Region** | O interior de uma janela com moldura vermelha — para capturar sempre o mesmo lugar e tamanho |
| **Drag** | A parte arrastada com o mouse depois de pressionar o atalho |
| **Active Window** | A janela que você está usando |
| **Window Control** | A janela ou o elemento (botão, painel…) sob o cursor |
| **WebBrowser** | A página web inteira aberta no Edge · Chrome, até o fim da rolagem |
| **Color Picker** | O código de cor sob o cursor |

**SaveTo**

| Item | Resultado |
|---|---|
| **PNG** · **JPG** · **GIF** · **BMP** · **WebP** | Um arquivo de imagem nesse formato |
| **MP4** | Gravação de tela (só Full Screen · Region) |
| **TXT** | Reconhece o texto da tela capturada e salva em um arquivo de texto |
| **Clipboard** | Copia só para a área de transferência, sem arquivo |
| **Upload Imgbox** | Envia para a web e abre a página da imagem no navegador |
| **Printer** | Imprime na hora |
| **Floating** | Mantém a imagem por cima de tudo, no lugar da captura |

**Menu do botão direito** (janela principal ou ícone da bandeja)

| Item | Função |
|---|---|
| **Open Folder** · **Folder setting** | Abrir ou mudar a pasta de salvamento |
| **Capture Settings** | **Capture Sound** (None · Before capture · After capture) · **Mouse cursor** · **With Clipboard** |
| **Recoder setting** | **Limit recording time** (Unlimited · 30 minutes · 1 hour · 2 hours · 4 hours) · **Mouse cursor** · **Include sound** |
| **Language** | Idioma da interface |
| **Filename setting** | **Auto increment number #1** · **Auto increment number #2** · **DateTime** |
| **Hotkey setting** | Mudar o atalho de captura |
| **Run on system start** | Iniciar automaticamente na bandeja quando o Windows inicia |
| **Crafted by Kilho** · **Quit** | Página de apresentação · sair do programa |

### O que fazer quando…

**Quer capturar a tela inteira de uma vez**
Deixe **Capture** em **Full Screen** e pressione `PrintScreen`. Não precisa abrir a janela: enquanto o Kalmuri estiver na bandeja, a captura funciona de qualquer lugar.

**Quer capturar sempre o mesmo lugar e tamanho**
Escolha **Region** e aparece uma janela com moldura vermelha piscando. Arraste a moldura para movê-la e as bordas para mudar o tamanho; depois pressione `PrintScreen` para capturar só o que está **dentro** da moldura. O tamanho atual (por exemplo, `480x360`) aparece no topo da moldura, e a posição e o tamanho ficam guardados para a próxima vez. O X no canto superior direito fecha a moldura e volta para **Full Screen**.

**Quer ajustar a região até o pixel**
Clique na moldura da região e use o teclado. As setas **movem** 1 pixel; `Ctrl`+seta **muda o tamanho** em 10 pixels e `Shift`+seta em 1 pixel. Acerte por alto com o mouse e finalize no teclado.

**Quer salvar os tamanhos que usa sempre**
Clicando com o botão direito na moldura aparece uma lista de tamanhos como `320x240` · `640x480` · `720x480` para trocar com um clique. Mude esses tamanhos em **Setting** informando a largura e a altura de **Custom #1 – #3**. Digite valores em **Current state** e clique em **Apply** para dar esse tamanho à região atual. **Hide**, no mesmo menu, só esconde a moldura por enquanto.

**Quer escolher com o mouse só a parte que precisa**
Escolha **Drag** e pressione `PrintScreen`: a tela congela e escurece. Arraste sobre a parte que quer capturar e solte para salvar só ela. `Esc` cancela. Como é o instante congelado que é capturado, dá para pegar até um menu aberto ou uma notificação que aparece só por um momento.

**Quer capturar só a janela que está usando**
Escolha **Active Window**, clique na janela para trazê-la à frente e pressione `PrintScreen`. A área de trabalho e as outras janelas ficam de fora; só aquela janela é salva.

**Quer capturar um único botão ou painel de uma janela**
Escolha **Window Control** e uma moldura pontilhada acompanha o elemento sob o cursor. Passe o cursor sobre o botão, campo ou painel que quer e pressione `PrintScreen` para salvar só o elemento dentro da moldura — prático para recortar uma parte para um manual ou um pedido de suporte.

**Quer salvar uma página web longa em uma só imagem**
Escolha **WebBrowser** e o Kalmuri abre uma janela separada do Edge (Chrome, se não houver Edge). Abra nela a página que quiser e pressione `PrintScreen`: a página inteira, incluindo a parte que precisaria rolar para ver, é salva como uma única imagem. Com várias abas abertas, é capturada a aba que você está vendo. Fechar essa janela do navegador volta para **Full Screen**. Requer Windows 8 ou posterior com Edge ou Chrome instalado.

**Quer descobrir o código de cor de algo na tela**
Escolha **Color Picker** e a janela mostra em tempo real a cor e o código sob o cursor. Posicione o cursor e pressione `PrintScreen`: essa cor entra no topo da lista e é copiada para a área de transferência. Clique com o botão direito na lista → **Format** para escolher o formato da cópia — **HEX** (`FF9933`) · **RGB** (`255, 153, 51`) · **Web** (`#FF9933`) · **TColor** (`$003399FF`) — e use **Copy** · **Delete** no mesmo menu para organizar a lista.

**Quer gravar a tela em vídeo**
Ponha **SaveTo** em **MP4** e pressione `PrintScreen` para começar a gravar; a janela mostra **Recording** e o tempo decorrido. Pressione `PrintScreen` de novo para parar e salvar o arquivo MP4. A gravação funciona com **Full Screen** e **Region**; ao gravar uma região, `[REC]` e o tempo aparecem na moldura e a região fica travada.

**Quer gravar também o som do PC**
Ative **Recoder setting → Include sound** para gravar, junto com a imagem, o som tocado no seu PC (vídeos, jogos, notificações). Ative ao gravar uma aula ou a reprodução de um vídeo.

**Quer deixar uma gravação rodando enquanto está fora**
Defina **Recoder setting → Limit recording time** como **30 minutes** · **1 hour** · **2 hours** · **4 hours** e a gravação para sozinha quando esse tempo passar — nada de disco cheio por esquecer de parar.

**Quer tirar o cursor das gravações**
Desative **Recoder setting → Mouse cursor** para esconder o cursor nos vídeos. É separado de **Capture Settings → Mouse cursor** para as capturas, então você pode deixar o cursor fora das capturas e mantê-lo nas gravações, ou o contrário.

**Quer transformar o texto de uma imagem em texto**
Ponha **SaveTo** em **TXT** e aparece ao lado uma caixa de idioma de reconhecimento. Escolha o idioma do texto e capture: o texto da tela é lido e salvo em um arquivo de texto (`K-001.txt`). Ótimo para texto em imagens ou documentos que não dá para copiar. Combine com **Drag** para reconhecer só o parágrafo que precisa. A lista de idiomas mostra os idiomas de reconhecimento de texto instalados no Windows.

**Quer colar uma captura em outro lugar na hora**
Ponha **SaveTo** em **Clipboard** para copiar a captura só para a área de transferência, sem criar arquivo, e colar num chat ou documento com `Ctrl`+`V`. Para salvar arquivo e também poder colar, ative **Capture Settings → With Clipboard**: em qualquer formato, a captura também é copiada para a área de transferência.

**Quer compartilhar uma captura por link**
Ponha **SaveTo** em **Upload Imgbox** e capture: a imagem é enviada para a web e a página dela abre no navegador. Copie o endereço e envie para compartilhar a captura sem anexar arquivo.

**Quer imprimir assim que capturar**
Ponha **SaveTo** em **Printer** e a captura é impressa na hora na impressora padrão.

**Quer deixar uma captura na tela como referência**
Ponha **SaveTo** em **Floating** e capture: uma imagem do mesmo tamanho fica por cima das outras janelas, no mesmo lugar da captura. Arraste para movê-la — útil para copiar valores ou comparar duas telas. Clique com o botão direito na imagem → **Save Image** para salvar como PNG · JPG · GIF · BMP · WebP, ou **Delete Floating** · **Delete All Floating** para fechá-la.

**Quer arquivos menores**
Ponha **SaveTo** em **JPG** ou **WebP** e escolha 100 · 90 · 80 · 70 · 60 na caixa de qualidade ao lado (90 por padrão). Quanto menor o número, menor o arquivo. PNG combina com telas cheias de texto; JPG · WebP com telas cheias de fotos.

**Quer mudar a regra de nomes de arquivo**
Escolha em **Filename setting**.
- **Auto increment number #1** (padrão) — continua a partir do maior número da pasta de salvamento (`K-001`, `K-002` …).
- **Auto increment number #2** — preenche a partir do menor número livre. Se você apagou um arquivo no meio, o número dele é usado de novo.
- **DateTime** — nomeia pelo horário da captura (`K-20260928-153012345`). Bom para organizar em ordem cronológica capturas de vários dias.

Qualquer que seja a regra, se já existir um arquivo com o mesmo nome, ele não é sobrescrito: a captura é salva com um nome novo.

**Quer mudar a pasta de salvamento**
Escolha uma pasta em **Folder setting**. O padrão é a área de trabalho. **Open Folder** no menu (ou **Open Folder** na janela) abre essa pasta a qualquer momento.

**Quer mudar o atalho**
Em **Hotkey setting**, marque `Ctrl` · `Alt` · `Shift`, escolha uma tecla e clique em **OK**. Você pode escolher `PrintScreen`, `A` – `Z`, `0` – `9`, `F1` – `F12` ou `DEL`. Se outro programa já usar essa combinação, você será avisado; escolha outra.

**`PrintScreen` abre a Ferramenta de Captura do Windows**
O Windows 11 tem uma configuração que faz `PrintScreen` abrir a Ferramenta de Captura. O Kalmuri desativa essa configuração ao iniciar para que `PrintScreen` funcione com o Kalmuri.

**Quer mudar o som de captura**
Em **Capture Settings → Capture Sound**, escolha **None** · **Before capture** (padrão) · **After capture**. **None** combina com lugares silenciosos; **After capture** avisa por som que o salvamento terminou.

**Quer incluir ou tirar o cursor**
Com **Capture Settings → Mouse cursor** ativado (padrão), o cursor aparece nas capturas. Deixe ativado para capturas que apontam um botão; desative para uma tela limpa.

**Quer deixá-lo pronto toda vez que o Windows iniciar**
Com **Run on system start** ativado, o Kalmuri inicia na bandeja sem janela quando o Windows inicia, pronto para o atalho. Na versão instalada já vem ativado.

**Quer continuar usando depois de fechar a janela, ou sair de vez**
O X da janela não fecha o Kalmuri: ele só o esconde na bandeja. Para sair de vez, clique em **Quit** no menu do botão direito e confirme. Se houver uma gravação em andamento, pare-a primeiro e depois saia.

**Quer mudar o idioma da interface**
Escolha 한국어 · English · 日本語 · 中文 · Русский · Italiano · Français · Español em **Language** e a mudança é imediata.

### Aviso de direitos autorais

As telas que você captura ou grava com o Kalmuri podem conter textos, imagens, vídeos ou músicas de outras pessoas. Compartilhá-las ou publicá-las além do uso pessoal de arquivo e consulta pode exigir a permissão do titular dos direitos; respeite os termos de uso de cada serviço e a lei de direitos autorais.

## Configuração

Cada configuração é salva assim que você a muda e usada de novo na próxima execução.

| Item | Padrão |
|---|---|
| Capture | Full Screen |
| SaveTo | PNG |
| Qualidade JPG · WebP | 90 |
| Pasta de salvamento | Área de trabalho |
| Filename setting | Auto increment number #1 |
| Atalho | `PrintScreen` |
| Capture Sound | Before capture |
| Mouse cursor (captura · gravação) | On |
| With Clipboard | Off |
| Limit recording time | Unlimited |
| Include sound | Off |
| Run on system start | On na versão instalada |
| Idioma | Segue a configuração de região do Windows (inglês quando o idioma não é suportado) |

## Requisitos

- Windows 10 · Windows 11
- A captura **WebBrowser** precisa do Microsoft Edge ou do Google Chrome.
- **TXT** (reconhecimento de texto) usa os idiomas de reconhecimento de texto instalados no Windows.
- A conexão com a internet é usada só para avisos de nova versão, **Upload Imgbox** e a captura **WebBrowser**.

## Atualizações

O Kalmuri **não** se atualiza sozinho. Ao iniciar, ele verifica se há uma nova versão e mostra um aviso; clicar em **[Yes]** abre a página de download e fecha o programa. As novas versões são publicadas manualmente após testes internos e anunciadas na [página do Kalmuri](https://kilho.net/kalmuri). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

**Histórico de versões**

| Versão | Data | Mudanças |
|---|---|---|
| 4.3.1 | 2026-09-28 | Mais segurança no envio de imagens, salvamento WebP mais confiável, início de gravação mais confiável, capturas de tela e por arrasto mais estáveis, arquivos existentes preservados mesmo em capturas rápidas seguidas, melhor prevenção de execução duplicada e melhor salvamento do tamanho e da posição da janela de região |
| 4.3.0 | 2026-08-28 | Captura de páginas web refeita — mais rápida e confiável com os Edge · Chrome mais recentes, páginas longas capturadas até o fim em uma imagem, navegador instalado encontrado automaticamente, captura precisa da página que você está vendo entre várias janelas e abas |
| 4.2.7 | 2026-08-14 | Captura de páginas web e escolha da pasta de salvamento mais confiáveis |
| 4.2.6 | 2026-07-23 | Captura do navegador web mais estável, região travada durante a gravação, indicador de gravação mais nítido, melhor salvamento do texto OCR e compatibilidade com coreano e caracteres especiais |

## Licença

O Kalmuri é **freeware**. Pode ser usado de graça e sem restrições em qualquer lugar — no trabalho, em casa, em órgãos públicos ou na escola — e redistribuído livremente.

## Links

- Site: <https://kilho.net/kalmuri>
- Fórum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
