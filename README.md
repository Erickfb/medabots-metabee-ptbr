# Medabots: Metabee — tradução PT-BR

Tradução completa de **Medabots: Metabee (Game Boy Advance)** para português
brasileiro, criada por [@Erickfb](https://github.com/Erickfb).

[Baixar somente a versão mais recente](https://github.com/Erickfb/medabots-metabee-ptbr/releases/latest)

> Este repositório distribui apenas um patch BPS. A ROM original e a ROM já
> modificada não são fornecidas.

## Versão atual

**PT-BR v1.2.2** — tradução 100% concluída, incluindo diálogos, menus,
batalhas, itens, mapas, mensagens de sistema, fontes, interface e créditos.

Esta versão melhora a assinatura da tela de título para `Traduzido por
ERICKFB` e mantém a correção do desalinhamento da câmera ao trocar de sala no
começo do jogo.

## Como instalar

Você precisa de uma cópia limpa e obtida legalmente da versão americana de
**Medabots: Metabee** e de um aplicador compatível com patches BPS, como o
[Floating IPS](https://github.com/Alcaro/Flips/releases/latest).

1. Confirme que a ROM base tem 8.388.608 bytes e código de jogo `A8BE`.
2. Confira o SHA-256 da ROM base.
3. Baixe o arquivo `.bps` na [Release mais recente](https://github.com/Erickfb/medabots-metabee-ptbr/releases/latest).
4. No aplicador BPS, escolha o patch, depois a ROM limpa, e salve o resultado
   em um novo arquivo.
5. Confira o SHA-256 da ROM resultante antes de jogar.

### Checksums da v1.2.2

| Arquivo | SHA-256 |
| --- | --- |
| ROM base americana limpa (não distribuída) | `78c3b7f9ac9dbc4380237d08743a82fb04c92fb0a67c3d1803e7df5e2cea92c5` |
| Patch `medabots-metabee-ptbr-v1.2.2.bps` | `d7d83a0b278d5d284972b3946de52e6938853e68b3dafff42f7a3ed39a73bae9` |
| ROM resultante da v1.2.2 (não distribuída) | `b8c1caf04a1bb427b51632e00cfe32c5481c24f33702ef561247115cbf6f1d8a` |

No Windows, use `Get-FileHash ARQUIVO -Algorithm SHA256` no PowerShell. No
macOS ou Linux, use `shasum -a 256 ARQUIVO`.

## Encontrou um bug?

[Abra um relato estruturado](https://github.com/Erickfb/medabots-metabee-ptbr/issues/new?template=bug_report.yml).
O formulário pede a versão, o emulador, o local exato e passos numerados para
reproduzir. Isso reduz bastante o tempo necessário para investigar e corrigir.

Antes de relatar:

- teste a Release mais recente;
- confirme os checksums;
- tente reproduzir após iniciar o jogo normalmente, sem savestate nem cheats;
- nunca anexe ROM, BIOS, savestate ou link para conteúdo protegido.

## Apoie o projeto

A tradução e o patch são e continuarão gratuitos. Se este projeto foi útil,
você pode apoiar voluntariamente o tempo dedicado à tradução, aos testes, às
correções e à documentação:

[Apoiar o projeto no Ko-fi](https://ko-fi.com/erickfb)

O apoio não representa a compra do jogo, não dá acesso antecipado e não
fornece ROMs nem qualquer outro conteúdo protegido.

## Créditos

**Tradução, revisão, testes e manutenção:**
[@Erickfb](https://github.com/Erickfb)

A autoria também aparece na tela de título, no menu principal e nos créditos
finais dentro do jogo.

## Aviso legal

Projeto de fã, sem afiliação ou endosso oficial. Medabots e suas marcas
pertencem aos respectivos titulares. Use o patch apenas com uma cópia de
segurança legal do seu próprio jogo. Consulte também o [aviso do projeto](NOTICE.md).
