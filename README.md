# Redes de interação entre personagens: Minha Mãe é uma Peça (Triologia)

## Discentes
- Matheus Fernandes Crippa
- Otavio Ferraz do Bonfim

## Obra
Triologia *Minha Mãe é uma Peça* (Filmes 1,2,3), assistida na Globoplay.

## Estrutura
- `data/`: Dicionário de personagens e interações de cada filme.
- `docs/`: Manual de anotação.

## Formato das anotações
Cada registro é uma linha com 6 campos separados por espaço:
	``personagem1 personagem2 sinal ambiente filme tempo`` 
- personagem1, personagem2: IDs do dicionário.
- sinal: `+` (positivo), `-` (negativo) ou `0` (neutro)
- ambiente: local da cena
- filme: `F1`, `F2` ou `F3`
- tempo: `HH:MM:SS` - Referente ao tempo da Globoplay
