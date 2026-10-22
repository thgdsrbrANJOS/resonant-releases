<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/images/logo-dark.png">
    <img src="docs/images/logo-light.png" alt="RESONANT" width="200">
  </picture>
</p>

<h1 align="center">RESONANT</h1>

<p align="center">
  <b>Controle de turno e registro automático de análises de RMN</b><br>
  <i>Shift control and automatic logging of NMR analyses</i>
</p>

<p align="center">
  <a href="https://github.com/thgdsrbrANJOS/resonant-releases/releases/latest"><img alt="Última versão" src="https://img.shields.io/github/v/release/thgdsrbrANJOS/resonant-releases?label=vers%C3%A3o%20%2F%20version&color=0078D4&style=for-the-badge"></a>
  <img alt="Windows 10/11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=for-the-badge&logo=windows11&logoColor=white">
  <img alt=".NET 10" src="https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white">
  <img alt="Bruker TopSpin" src="https://img.shields.io/badge/Bruker-TopSpin%20%7C%20IconNMR-1E88E5?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/thgdsrbrANJOS/resonant-releases/releases/latest"><b>⬇️ Baixar a versão mais recente / Download the latest version</b></a>
</p>

<p align="center">
  <img src="docs/images/main-logged-pt-light.png" alt="Tela principal do RESONANT" width="860">
</p>

---

## 🇧🇷 Português

O **RESONANT** acompanha em tempo real as análises feitas no espectrômetro de RMN da Bruker (TopSpin e IconNMR). Cada experimento novo é identificado na hora, vinculado ao operador que está em turno e enviado automaticamente para uma planilha do Google Sheets. Não há anotação manual nem análise esquecida.

### Como funciona
1. **O operador inicia o turno.** Ele escolhe o nome na lista e digita a senha.
2. **O RESONANT observa as pastas da Bruker.** Quando o TopSpin grava um experimento, o programa lê os arquivos `acqus` e `title`: data, núcleo, pulso, solvente, instituição e solicitante.
3. **A análise é registrada.** Ela vai para o histórico local e para a planilha do Google. Sem internet, fica na fila e é enviada quando a conexão volta.
4. **Nenhuma análise se perde.** Se alguém usar o RMN sem fazer login, o RESONANT avisa na hora e registra a análise assim que um operador iniciar o turno.

### Destaques
- 🏆 **Ranking mensal dos operadores** por tempo de turno, com coroas de ouro, prata e bronze.
- 📊 **Total de análises no mês** e **total geral**.
- 🕒 **Saída de turno agendada**, por tempo ou ao fim da fila do espectrômetro.
- 🗂️ **Histórico completo**, com busca, filtros, exportação para Excel e sincronização.
- 🌗 **Visual do Windows 11**, com tema claro e escuro e em **português ou inglês**.
- 🔄 **Atualizações automáticas e seguras**, com assinatura digital conferida antes de instalar.

---

## 🇺🇸 English

**RESONANT** monitors the analyses run on a Bruker NMR spectrometer (TopSpin and IconNMR) in real time. Every new experiment is detected instantly, linked to the operator on shift and automatically sent to a Google Sheets spreadsheet. No manual notes, no forgotten analyses.

### How it works
1. **The operator starts a shift.** They pick their name from the list and enter their password.
2. **RESONANT watches the Bruker folders.** When TopSpin writes an experiment, it reads the `acqus` and `title` files: date, nucleus, pulse program, solvent, institution and requester.
3. **The analysis is logged.** It goes to the local history and to the Google spreadsheet. When offline, it is queued and sent once the connection is back.
4. **No analysis is lost.** If someone uses the NMR without logging in, RESONANT warns right away and records the analysis as soon as an operator starts a shift.

### Highlights
- 🏆 **Monthly operator ranking** by shift time, with gold, silver and bronze crowns.
- 📊 **Analyses this month** and **all-time total**.
- 🕒 **Scheduled shift end**, after a set time or when the spectrometer queue finishes.
- 🗂️ **Full history**, with search, filters, Excel export and synchronization.
- 🌗 **Windows 11 look**, with light and dark themes, in **Portuguese or English**.
- 🔄 **Safe automatic updates**: the digital signature is verified before installing.

---

## 🖼️ Telas / Screenshots

| Tela principal (claro) | Main screen (dark) |
|---|---|
| <img src="docs/images/main-logged-pt-light.png" width="420"> | <img src="docs/images/main-logged-en-dark.png" width="420"> |
| **Histórico** | **History** |
| <img src="docs/images/history-pt-light.png" width="420"> | <img src="docs/images/history-en-dark.png" width="420"> |
| **Configurações** | **Settings** |
| <img src="docs/images/settings-pt-light.png" width="420"> | <img src="docs/images/settings-en-dark.png" width="420"> |

---

<p align="center">
  Desenvolvido por / Developed by <b>Thiago Anjos</b> · © 2026
</p>
