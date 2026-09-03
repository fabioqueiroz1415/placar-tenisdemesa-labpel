# Placar de Tênis de Mesa - Labpel

Este projeto é um sistema de placar para partidas e campeonatos de tênis de mesa.

Eu fiz o sistema para facilitar o controle dos jogos do Labpel, mostrando o placar, os jogadores, os resultados e a tabela do campeonato.

## Funcionalidades

- controle dos pontos e sets;
- escolha de quem está sacando;
- controle do placar em uma página separada;
- cadastro dos jogadores;
- registro dos resultados das partidas;
- tabela do campeonato;
- histórico de campeonatos salvos;
- modo de partida única entre dois jogadores;
- geração de QR Code para abrir as páginas pelo celular;
- acesso pela rede local.

## Tecnologias usadas

- Python
- Flask
- HTML
- CSS
- JavaScript
- JSON
- QR Code

## Como executar

Instale as principais dependências:

```bash
pip install flask qrcode pillow
```

Depois execute:

```bash
python run.py
```

O servidor será iniciado na porta `5000`.

No computador, você pode acessar:

```text
http://localhost:5000
```

## Páginas do sistema

```text
/                Tabela para visualização
/placar          Placar da partida
/controle        Controle do placar
/tabela          Tabela do campeonato
/jogadores       Cadastro dos jogadores
/campeonatos     Campeonatos salvos
/links           Links e QR Codes
/partida-unica   Partida simples entre dois jogadores
```

## Dados

Os jogadores, partidas e resultados são salvos em arquivos JSON dentro da pasta:

```text
json/
```

Alguns dos arquivos usados são:

```text
jogadores.json
partidas.json
resultados.json
```

## Sobre

Esse projeto foi criado para ajudar na organização das partidas de tênis de mesa do Labpel.

Também usei o projeto para aprender mais sobre Python, Flask, páginas web e comunicação entre diferentes dispositivos pela rede local.
