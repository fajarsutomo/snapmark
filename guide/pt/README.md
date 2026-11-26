# Guia do usuário do SnapMark

O SnapMark captura a tela do Windows e permite anotá-la com marcas que **continuam editáveis**: retângulos, setas, texto, ocultações e mais são objetos separados, não pixels pintados na imagem. A imagem original nunca é modificada.

[Outros idiomas / Other languages](../README.md)

## Sumário

1. [Instalação](#instalação)
2. [Capturar a tela](#capturar-a-tela)
3. [Ferramentas de anotação](#ferramentas-de-anotação)
4. [Atalhos de teclado](#atalhos-de-teclado)
5. [Copiar e salvar](#copiar-e-salvar)
6. [Projetos e histórico](#projetos-e-histórico)
7. [Configurações](#configurações)
8. [Privacidade](#privacidade)
9. [Solução de problemas](#solução-de-problemas)

## Instalação

Execute o instalador `SnapMark_x.y.z_x64-setup.exe`. Ele instala apenas para a sua conta (não exige permissão de administrador). Depois, o SnapMark fica na **área de notificação** (a área de ícones perto do relógio, também chamada de bandeja do sistema). Se o ícone não aparecer, clique na seta ^ para mostrar os ícones ocultos.

Clique com o botão direito no ícone para abrir o menu: **Capturar**, **Histórico**, **Abrir projeto…**, **Configurações**, **Sair**.

## Capturar a tela

1. Pressione **Print Screen** (ou clique no ícone da área de notificação, ou escolha **Capturar**). A tela congela por um instante; com vários monitores, todos são capturados.
2. **Arraste** para escolher uma área. Você pode alterá-la a qualquer momento, mesmo depois de adicionar anotações: arraste o **contorno** para movê-la, uma **alça** de canto ou lado para redimensioná-la, ou arraste na área escura de fora para escolher de novo. As setas do teclado deslocam a área; **Ctrl + seta** a redimensiona; **Shift** faz o passo ser de 10 pixels.
3. Use a barra de ferramentas para adicionar anotações.
4. Pressione **Enter** para copiar para a área de transferência ou **Ctrl+S** para salvar. **Esc** cancela.

O primeiro Esc desmarca os objetos; o seguinte fecha o SnapMark.

## Ferramentas de anotação

| Ferramenta | Tecla | Observações |
|---|---|---|
| Selecionar e editar | `V` | Clique em um objeto para selecioná-lo; **Shift+clique** adiciona ou remove da seleção. Arraste para mover, puxe uma alça para redimensionar. |
| Retângulo | `R` | **Shift** = quadrado. Pode ter preenchimento. |
| Elipse | `E` | **Shift** = círculo. |
| Linha | `L` | **Shift** = ângulos de 45°. Estilos: contínua, dupla, tracejada. |
| Seta | `A` | **Shift** = 45°. Ponta em uma ou nas duas extremidades. |
| Caneta livre | `P` | Desenho à mão livre. |
| Marca-texto | `H` | Marcador translúcido. |
| Ocultar | `S` | Mosaico, desfoque ou **bloco preto** (o mais seguro). Formato retangular ou pincel. |
| Número de passo | `N` | Clique para colocar 1, 2, 3… em ordem. |
| Texto | `T` | Fundo à escolha. **Ctrl+Enter** ou **Esc** conclui. |

Cor, espessura, tamanho da fonte e negrito são definidos na barra de ferramentas; as mudanças valem para os objetos selecionados.

## Atalhos de teclado

| Tecla | Ação |
|---|---|
| `Enter` / `Ctrl+C` | Copiar o resultado para a área de transferência |
| `Ctrl+S` | Salvar o PNG na pasta de salvamento |
| `Ctrl+Shift+S` | Salvar como… |
| `Ctrl+Alt+S` | Salvar um projeto `.snapmark` |
| `Ctrl+Z` / `Ctrl+Y` (ou `Ctrl+Shift+Z`) | Desfazer / refazer |
| `Ctrl+D` | Duplicar os objetos selecionados |
| `Ctrl+A` | Selecionar todos os objetos |
| `Ctrl+]` / `Ctrl+[` | Trazer para frente / enviar para trás |
| `Delete` / `Backspace` | Excluir os objetos selecionados |
| Setas (`Shift` = 10 px) | Mover os objetos selecionados; sem seleção, mover a área (com `Ctrl`: redimensioná-la) |
| `Esc` | Desmarcar e, depois, fechar |

## Copiar e salvar

O resultado é sempre **somente a área selecionada**, na **resolução original** da tela, exatamente como você vê.

- **Copiar** (Enter): vai para a área de transferência, pronto para colar.
- **Salvar** (Ctrl+S): direto na pasta de salvamento como `snapmark_20261125_143005.png` (data_hora). Arquivos existentes nunca são sobrescritos (é acrescentado o sufixo `_2`, `_3`, …). Pasta padrão: `Imagens\SnapMark`.
- **Salvar como** (Ctrl+Shift+S): você escolhe o nome e a pasta.

Depois de copiar ou salvar com sucesso, o SnapMark fecha automaticamente.

## Projetos e histórico

Um **projeto `.snapmark`** guarda a imagem original e cada anotação como objeto, para que você possa reabri-lo e editá-lo depois. Salve com **Ctrl+Alt+S**; abra com um clique duplo no arquivo ou pela área de notificação → **Abrir projeto…**.

> **Cuidado com as ocultações.** Como o arquivo de projeto guarda a imagem *original*, qualquer pessoa que o abrir poderá ver o que você ocultou. Para compartilhar, use **Copiar** ou **Salvar PNG**, que contêm apenas o resultado já ocultado. O SnapMark avisa antes de salvar um projeto que contém ocultação.

**Histórico**: cada Copiar/Salvar é registrado automaticamente como projeto editável (os últimos 50 por padrão, somente neste computador). Abra pela área de notificação → **Histórico** e clique em um item para editá-lo de novo.

## Configurações

Área de notificação → **Configurações**.

| Configuração | Descrição |
|---|---|
| Atalho de captura | Padrão `Print Screen`. Clique em **Alterar…** e pressione a nova combinação (use Ctrl/Alt/Win para não atrapalhar a digitação). |
| Pasta de salvamento | Destino do Ctrl+S. |
| Idioma | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, ou igual ao Windows. |
| Histórico | Quantos itens guardar (0 = desativado, máximo 500). |
| Iniciar com o Windows | O SnapMark está pronto assim que você faz login. |
| Cor da dica | Cor do texto de instruções ao escolher a área. |
| Tema | Igual ao Windows, Claro, Escuro ou Liquid Glass. |
| Atualizações | Verificar e instalar automaticamente a cada 6 horas, ou **Verificar agora**. |

As atualizações são baixadas da versão oficial, instaladas sem janela de instalação, e o SnapMark reabre sozinho; suas configurações e seu histórico são mantidos. Uma atualização espera você terminar de editar.

## Privacidade

- Capturas e projetos **nunca saem do seu computador**.
- Sem telemetria. O único acesso à rede é a verificação de atualizações.

## Solução de problemas

**Print Screen não faz nada / o atalho não está ativo.** O Windows 11 pode reservar essa tecla para a própria ferramenta de captura. Nas Configurações do SnapMark, clique em **Abrir configurações de teclado do Windows** e desative a opção que faz a tecla Print Screen abrir essa ferramenta (o nome e o local da opção variam conforme a versão do Windows). Ou escolha outro atalho.

**O ícone da área de notificação não aparece.** Clique na seta ^ da barra de tarefas; arraste o ícone do SnapMark para fora para que fique sempre visível.

**Onde ficam os dados.** Configurações: `%APPDATA%\app.snapmark.desktop\settings.json`. Histórico: `%LOCALAPPDATA%\app.snapmark.desktop\history`.
