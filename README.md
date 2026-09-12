# Bússola Eleitoral 2026

Questionário interativo que compara suas posições políticas com os programas de governo de seis pré-candidatos à Presidência do Brasil em 2026, eixo por eixo — sem dizer em quem votar.

**[Ver demo ao vivo →](https://gabcapelli.github.io/bussola-eleitoral/)** *(ative o GitHub Pages em Settings → Pages para este link funcionar)*

## Como funciona

- 8 perguntas sobre eixos onde os candidatos mais divergem: papel do Estado na economia, segurança pública, assistência social, meio ambiente, reforma do Estado, educação, política externa e estilo de liderança.
- Cada resposta pontua a afinidade com cada candidato.
- Ao final, o resultado mostra o grau de afinidade (%) com cada um, independente entre si, mais o detalhe eixo a eixo.
- Botão para compartilhar o resultado no WhatsApp.

## Candidatos incluídos

| Candidato | Partido |
|---|---|
| Augusto Cury | Avante |
| Lula | PT / coligação |
| Renan Santos | Missão |
| Flávio Bolsonaro | PL |
| Romeu Zema | Novo |
| Ronaldo Caiado | PSD |

As posições usadas no quiz vêm dos planos de governo/documentos oficiais divulgados publicamente por cada campanha.

## Rodando localmente

Não há build nem dependências — é um único arquivo HTML autocontido.

```bash
git clone https://github.com/gabcapelli/bussola-eleitoral.git
cd bussola-eleitoral
# abra o index.html no navegador, ou sirva com qualquer servidor estático:
python3 -m http.server 8000
```

## Hospedando

Qualquer host de arquivo estático funciona (o link de compartilhamento do WhatsApp usa a URL da própria página, então não precisa configurar nada):

- **GitHub Pages**: Settings → Pages → Branch `main` / `/ (root)`.
- **Netlify Drop**: arraste a pasta em [netlify.com/drop](https://netlify.com/drop).
- **Vercel**: `vercel deploy` na pasta do projeto.

## Aviso

Ferramenta informal e independente, sem afiliação a nenhum candidato ou partido. Não substitui a leitura dos documentos completos, que podem ser atualizados pelas campanhas a qualquer momento.
