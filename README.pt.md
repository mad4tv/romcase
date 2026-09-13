<p align="center">
  <img src="Resources/AppIcon.png" width="128" alt="ROM Case">
</p>

<h1 align="center">ROM Case</h1>

<p align="center">
  <a href="README.md">English</a> · <strong>Português</strong>
</p>

<p align="center">
  App nativa para macOS: estojo de retroconsolas — <strong>R36S</strong>, <strong>Anbernic</strong> (RG35XX e afins),<br>
  e os cartões com as ROMs, BIOS, saves e capas.
</p>

<p align="center">
  <img src="Resources/os/logo-r36s.png" height="48" alt="R36S">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-anbernic.png" height="48" alt="Anbernic">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-arkos.png" height="48" alt="ArkOS">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-darkos.png" height="48" alt="dArkOS">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-amberelec.png" height="48" alt="AmberELEC">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-pan4elec.png" height="48" alt="PAN4ELEC">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-knulli.png" height="48" alt="KNULLI">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-rocknix.png" height="48" alt="ROCKNIX">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-muos.png" height="48" alt="muOS">
</p>

<p align="center">
  <strong>ArkOS</strong> · <strong>dArkOS</strong> · <strong>PAN4ELEC</strong> · <strong>AmberELEC</strong> · <strong>KNULLI</strong> ·
  <strong>ROCKNIX</strong> · <strong>Anbernic Stock</strong> · <strong>muOS</strong>
</p>

<p align="center">
  <a href="https://github.com/mad4tv/romcase/releases/latest/download/ROM-Case-1.2.1.dmg">
    <img src="https://img.shields.io/badge/Descarregar-ROM%20Case%201.2.1.dmg-4FB8FF?style=for-the-badge&logo=apple&logoColor=white" alt="Descarregar ROM Case 1.2.1.dmg">
  </a>
  &nbsp;
  <a href="https://www.buymeacoffee.com/joseteixeira">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-joseteixeira-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee">
  </a>
</p>

<p align="center">
  <a href="https://github.com/mad4tv/romcase/releases/latest"><strong>Descarregar o instalador (.dmg)</strong></a>
  ·
  v1.2.1 · macOS 14+ · Apple Silicon
  ·
  <a href="https://www.buymeacoffee.com/joseteixeira">Buy Me a Coffee</a>
</p>

---

## O que é

**ROM Case** é uma app para Mac para quem tem clones **R36S** e consolas **Anbernic** (RG35XX Plus, H, Pro e o resto da prateleira) em mais do que um firmware.

Vê o cartão SD quando o ligas, identifica o OS (ou deixas escolher) e faz o trabalho chato que normalmente é uma janela do Finder, a pasta errada e um `.srm` em falta.

O inglês é a língua predefinida na app quando o macOS não está em português. No menu da primeira abertura (ou na barra à esquerda) clica 🇵🇹 ou 🇬🇧; a escolha fica gravada.

O **código-fonte permanece privado**. Esta página é a documentação pública e o sítio de onde se descarrega a app.

## Descarregar

**[ROM-Case-1.2.1.dmg](https://github.com/mad4tv/romcase/releases/latest/download/ROM-Case-1.2.1.dmg)** — arrasta **ROM Case** para Aplicações.

[Todas as versões](https://github.com/mad4tv/romcase/releases)

### Requisitos

- **macOS 14** (Sonoma) ou superior
- **Apple Silicon** (M1, M2, M3, M4)
- Leitor de cartões SD / USB que o Finder consiga montar
- Primeira abertura: **clique com o botão direito → Abrir** (a app tem assinatura ad-hoc; o Gatekeeper pergunta uma vez)
- Opcional: conta [ScreenScraper](https://www.screenscraper.fr) para completar boxart 2D em falta

Não precisas de Xcode para usar a app descarregada.

## O que a app faz

| | Tarefa | |
| :---: | --- | --- |
| <img src="Resources/menu/menu-prepare.png" width="72" alt="Preparar"> | **Preparar** | Grava o OS num SD vazio (imagem oficial ou um `.img` teu). Consolas típicas: **R36S** (ArkOS, dArkOS, PAN4ELEC, AmberELEC, ROCKNIX, …) e **Anbernic** RG35XX (stock, KNULLI, muOS, ROCKNIX). Segundo cartão opcional só para ROMs. **Apaga o cartão.** |
| <img src="Resources/menu/menu-transfer.png" width="72" alt="Passar jogos"> | **Passar jogos** | Origem (SD velho, pasta de ROMs ou `.img` montado) → destino. Copia ROMs, BIOS, saves e capas para a pasta que cada OS usa de verdade. |
| <img src="Resources/menu/menu-structure.png" width="72" alt="Estrutura"> | **Estrutura** | Cria as pastas vazias do OS num cartão novo, antes de copiar. |
| <img src="Resources/menu/menu-covers.png" width="72" alt="Boxart"> | **Boxart** | Completa a caixa 2D em falta via ScreenScraper (conta de membro no ecrã). Depois Update Gamelists no KNULLI / ArkOS. |
| <img src="Resources/menu/menu-themes.png" width="72" alt="Temas"> | **Temas** | Listas por OS (ecrãs 4:3 pequenos / Batocera / MustardOS) ou um ZIP / `.muxthm` no cartão. Quem liga o tema é a consola. |
| <img src="Resources/menu/menu-duplicates.png" width="72" alt="Duplicados"> | **Duplicados** | Encontra ROMs iguais no cartão e elimina as cópias extra. Fica sempre uma. |
| <img src="Resources/menu/menu-backup.png" width="72" alt="Arquivo"> | **Arquivo** | Cópia das pastas de ROMs para o Mac, ou clone **integral** `.img` do SD (BOOT incluído) e reposição depois. |

Também: a app **ejeta** o cartão físico inteiro (não uma partição) em todos os sítios onde há cartão ou disco, e **recusa** listar ou tocar no disco interno do Mac.

Não mistura layouts. Cartões estilo ArkOS (R36S), Batocera/KNULLI, Anbernic stock e muOS ficam cada um nas suas pastas.

## Instalar

1. [Descarrega o `ROM-Case-1.2.1.dmg`](https://github.com/mad4tv/romcase/releases/latest/download/ROM-Case-1.2.1.dmg)
2. Abre o disco e arrasta **ROM Case** para **Aplicações**
3. Na primeira vez: clique com o botão direito na app → **Abrir** → confirma
4. Liga um SD, ou larga uma pasta / `.img`

Se o macOS disser que a app é de um programador não identificado, é a assinatura ad-hoc. O caminho certo é clique direito → Abrir; não desligues o Gatekeeper.

## Sistemas suportados

| OS | Família | Consolas (típico) |
| --- | --- | --- |
| ArkOS 2.0 | ArkOS | **R36S** · AeolusUX (arquivado) |
| dArkOS | ArkOS | **R36S** · dArkOSen |
| AmberELEC | ArkOS | RK3326 · RG351 · também **R36S** |
| PAN4ELEC | ArkOS | **R36S** Panel 4 |
| KNULLI | Batocera | **Anbernic** RG35XX |
| ROCKNIX | Batocera | **R36S** · RG35XX · JELOS |
| Anbernic Stock | Anbernic | **Anbernic** RG35XX Pro / Plus / H · OS original |
| muOS | MustardOS | **Anbernic** RG35XX · ARCHIVE para temas |

## Apoiar o projeto

O **ROM Case** é feito por **José A. Teixeira** (AKA Mad4linux).

Se te poupou uma noite a copiar a pasta errada:

**[Buy Me a Coffee](https://www.buymeacoffee.com/joseteixeira)**

## Créditos

**ROM Case** — © 2026 José A. Teixeira · AKA Mad4linux
