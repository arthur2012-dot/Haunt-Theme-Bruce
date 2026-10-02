# Haunt Theme for Bruce Firmware

**Super leve + boot otimizado** · Gengar palette · Otimizado para **CYD 2432S028**

Tema extraído do [Haunt Firmware](https://github.com/arthur2012-dot/Haunt) de Batista.

## Arquivos

| Arquivo     | Tamanho   | Descrição                          |
|-------------|-----------|------------------------------------|
| `Haunt.json`| ~230 B    | Cores + config                     |
| `boot.gif`  | **~10.5 KB** | Gengar animado, **sem texto**, 4 frames, 16 cores |

## Cores (RGB565)

| Campo       | Valor    | Descrição              |
|-------------|----------|------------------------|
| priColor    | `e59f`   | Lavanda / Gengar       |
| secColor    | `a418`   | Roxo médio             |
| bgColor     | `0000`   | Preto puro             |
| ledColor    | `960064` | Roxo LED               |

## Instalação (CYD 2432S028)

1. Baixe o ZIP ou os arquivos (`Haunt.json` + `boot.gif`).
2. Coloque **os dois** na **raiz do LittleFS** (recomendado) ou SD.
3. No Bruce: **Config → UI Theme** → selecione o filesystem → escolha `Haunt.json`.
4. O `boot.gif` será usado automaticamente no boot.

## Otimizações do boot.gif

- Removido **todo texto** (“Haunt firmware”, versão, Initializing…)
- Reduzido para **4 frames** (animação leve do Gengar flutuando)
- Apenas **16 cores**
- 320×240 (compatível com CYD)
- ~10.5 KB (de ~40 KB originais)

## Origem

Sprites originais do Haunt + compressão máxima para Bruce/CYD.

MIT · Batista / arthur2012-dot
