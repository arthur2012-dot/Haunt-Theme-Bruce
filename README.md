# Haunt Theme for Bruce Firmware

**Super leve** · Gengar / Haunt palette · Otimizado para **CYD 2432S028** (240×320)

Tema de cores puro extraído do [Haunt Firmware](https://github.com/arthur2012-dot/Haunt) de Batista.  
Sem imagens, sem GIF, sem assets pesados — só o JSON. Ideal para CYD e builds LITE.

## Cores (RGB565)

| Campo       | Valor  | Descrição              |
|-------------|--------|------------------------|
| priColor    | `e59f` | Lavanda / Gengar claro |
| secColor    | `a418` | Roxo médio             |
| bgColor     | `0000` | Preto puro             |
| ledColor    | `960064` | Roxo LED (HEX)       |

- `border: 0` → sem bordas extras
- `label: 1` → labels ativados
- LED com efeito suave

## Instalação (CYD 2432S028)

1. Copie a pasta `Haunt-Theme-Bruce` (ou só o arquivo `Haunt.json`) para a **raiz do LittleFS** ou **SD card**.
2. No Bruce: **Config → UI Theme** → escolha o filesystem → selecione `Haunt.json`.
3. Pronto.

> Recomendado: LittleFS para evitar bugs de tema em alguns builds.

## Por que super leve?

- Zero PNGs / GIFs / boot images
- Apenas 1 arquivo JSON (~250 bytes)
- Compatível com qualquer resolução Bruce (incluindo 180px CYD)
- Não consome memória extra de ícones

## Origem

Baseado no firmware Haunt (Gengar-themed dark UI) criado para o mesmo CYD 2432S028.

MIT · Batista / arthur2012-dot
