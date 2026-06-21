# SPRAY INTERCEPTION

> Ferramenta de compensação de recoil universal para Windows.

[![versão](https://img.shields.io/github/v/release/T1NG4/TGS-SPRAY-interception-releases?include_prereleases&label=versão&style=flat-square)](https://github.com/T1NG4/TGS-SPRAY-interception-releases/releases/latest)
[![download](https://img.shields.io/github/downloads/T1NG4/TGS-SPRAY-interception-releases/total?label=downloads&style=flat-square)](https://github.com/T1NG4/TGS-SPRAY-interception-releases/releases)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-blue?logo=windows&style=flat-square)]()

<!-- COLOCAR PRINT OU GIF DA APLICAÇÃO AQUI -->

---

## O que é

O **SPRAY INTERCEPTION** é um utilitário para Windows que compensa recoil de armas de forma controlada e suave. Ele atua com movimentos periódicos no cursor, permitindo ajustar offsets, intervalos, jitter, rampa e atraso inicial para diferentes armas e jogos.

- Compensação de recoil configurável
- Biblioteca de armas personalizável
- Perfis com atalhos rápidos (primária/secundária)
- Atualizações automáticas
- Interface escura e minimalista

---

## Requisitos

- Windows 10 ou 11 (x64)
- Privilégios de Administrador (necessário para o driver de input)
- Driver Interception (o instalador cuida disso na primeira execução)

---

## Download

Baixe a versão mais recente:

**[⬇ SPRAY INTERCEPTION Setup](https://github.com/T1NG4/TGS-SPRAY-interception-releases/releases/latest)**

---

## Instalação

1. Baixe o arquivo `SPRAY-INTERCEPTION-Setup-x.x.x.exe`.
2. Execute o instalador como Administrador.
3. Siga as telas de instalação.
4. Ao concluir, marque a opção **"Executar o SPRAY INTERCEPTION"**.

> O instalador instala o app para todos os usuários da máquina (`C:\Program Files\SPRAY INTERCEPTION`).

---

## Primeira execução

Na primeira vez que abrir, o aplicativo verifica e instala o driver **Interception** automaticamente. Se o Windows pedir confirmação, aceite a instalação do driver.

<!-- COLOCAR PRINT DA TELA DE CARREGAMENTO AQUI -->

---

## Como usar

### Controles principais

| Ação | Atalho |
|------|--------|
| Ligar / Desligar | `INSERT` |
| Capturar janela em foco | `F8` |
| Selecionar arma primária | `1` |
| Selecionar arma secundária | `2` |

### Ajustes recomendados

1. Vá na aba **Recoil Control** para ajustar os parâmetros globais.
2. Crie suas armas na aba **Perfil** → **Biblioteca de Armas**.
3. Monte perfis escolhendo a arma primária e secundária.
4. Ative o uso de recoil por perfil para trocar automaticamente entre armas.

---

## Atualizações automáticas

O SPRAY INTERCEPTION verifica novas versões sempre que é aberto. Se houver uma atualização, ela é baixada e instalada automaticamente, sem a necessidade de baixar manualmente.

---

## Desinstalação

1. Vá em **Configurações → Aplicativos → Aplicativos instalados**.
2. Procure por **SPRAY INTERCEPTION**.
3. Clique em **Desinstalar**.

---

## Solução de problemas

### O app não abre

- Certifique-se de executar como **Administrador**.
- Verifique se o antivírus não bloqueou o `SPRAY INTERCEPTION.exe` ou `InputHostCore.exe`.

### O driver não instala

- Execute o app novamente como Administrador.
- Se o problema persistir, abra o prompt como Administrador e rode:
  ```
  sc query keyboard
  sc query mouse
  ```
  Se retornar `RUNNING`, o driver está ativo.

### O recoil não está sendo compensado

- Verifique se o app está **ligado** (INSERT).
- Confirme o processo/janela correto na aba **Filtro de Processo**.
- Ajuste os offsets conforme a arma.

---

## Desenvolvimento

O código-fonte está no repositório principal:

**[github.com/T1NG4/TGS-SPRAY-interception](https://github.com/T1NG4/TGS-SPRAY-interception)**

Este repositório (`TGS-SPRAY-interception-releases`) é apenas para distribuição dos instaladores.

---

## Licença

Uso pessoal. Consulte o repositório de código para detalhes.

---

## Contato

Encontrou um bug ou tem uma sugestão? Abra uma issue no repositório de código-fonte:

**[github.com/T1NG4/TGS-SPRAY-interception/issues](https://github.com/T1NG4/TGS-SPRAY-interception/issues)**
