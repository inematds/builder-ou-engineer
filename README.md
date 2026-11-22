# Builder ou Engineer: chegue pronto na próxima vaga de IA

[![Builder ou Engineer: chegue pronto na próxima vaga de IA](guia/assets/banner.jpg)](https://inematds.github.io/builder-ou-engineer/guia/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## O que é

As empresas que mais usam IA já separam dois perfis de entrada: o **AI Engineer**, que constrói modelos e sistemas, e o **AI Builder**, que vem de qualquer área e usa a IA para resolver problemas do negócio. O iFood paga de R$ 5.200 a R$ 7.000 por mês para formar os dois no programa genAI, e as inscrições da turma de 2027 fecharam em 17/11/2026. O **Plano Builder ou Engineer** é um plano grátis de 12 semanas para você chegar pronto na próxima turma, ou em qualquer vaga de IA: descobrir o seu perfil, seguir a trilha com cursos grátis do INEMA.CLUB, fazer um projeto com número de antes e depois e treinar cada etapa da seleção com a IA.

Não tem ligação com o iFood e não garante vaga: é preparo.

## 📖 Guia de uso

Guia completo: **https://inematds.github.io/builder-ou-engineer/guia/**

🎬 Vídeo: em produção (entra no guia quando publicado).

## Comece pedindo para a sua IA

Cole no ChatGPT, no Claude ou no Gemini:

```
Seja meu treinador para eu entrar num programa de estágio ou residência em IA (como o genAI do iFood), em português simples.
1. Faça comigo, uma pergunta por vez, um teste para saber se eu sou mais AI Builder ou AI Engineer. Pergunte também meu curso e quando me formo.
2. Monte um plano de 12 semanas, umas 5 horas por semana, seguindo o "Plano Builder ou Engineer" em https://inematds.github.io/builder-ou-engineer/guia/ e usando os cursos grátis citados lá.
3. Me ajude a escolher um projeto-prova que resolva a dor real de alguém, com um número de antes e depois.
4. Quando eu disser "treino", faça o papel do avaliador de cada etapa da seleção. No fim de cada uma, me dê nota e diga o que eu esqueci.
Seja honesto: se eu estiver fraco em algo, diga.
```

## O programa de referência (conferido em 22/11/2026)

- 2ª edição do genAI do iFood: inscrições de 27/10 a 17/11/2026, início em fevereiro de 2027.
- Estágio: formatura entre jul/2027 e jan/2029, bolsa R$ 5.200. Residência: formados entre dez/2025 e dez/2026, bolsa R$ 7.000.
- AI Engineer: computação, engenharia de software, matemática, estatística, física. AI Builder: qualquer formação, sem código profundo.
- Fontes: [comunicado oficial](https://institucional.ifood.com.br/releases/programa-gen-ia/) · [página de carreiras](https://carreiras.ifood.com.br/gen-ai/).

---

## O processo, do início ao fim

Quem faz: 🧠 você (com a IA ao lado) · 🤖 a sua IA (ChatGPT, Claude, Gemini) · ⚙️ nenhum script: o plano é só leitura e prática.

| # | Passo | Onde | Quem |
|---|---|---|---|
| 1 | Descobrir o perfil (Builder ou Engineer) | pedido acima ou [guia#perfis](https://inematds.github.io/builder-ou-engineer/guia/#perfis) | 🤖 + 🧠 |
| 2 | Semanas 1–2: usar IA em 3 tarefas e anotar o tempo antes/depois | [PLANO.md](PLANO.md) | 🧠 |
| 3 | Semanas 3–6: trilha do perfil (cursos grátis) | [PLANO.md](PLANO.md#semana-a-semana) | 🧠 |
| 4 | Semanas 7–10: projeto-prova + 1 página de portfólio | [PLANO.md](PLANO.md#semana-a-semana) | 🧠 |
| 5 | Semanas 11–12: treino das 6 etapas da seleção | [pedidos de treino](PLANO.md#pedidos-de-treino-cole-na-sua-ia) | 🤖 + 🧠 |
| 6 | Até a próxima turma: um projeto por mês | — | 🧠 |

## Instalação técnica

Não há nada para instalar: o projeto é um guia estático (`guia/index.html`, `guia/en/`, `guia/es/`) e o plano em texto (`PLANO.md`). Para ver o guia localmente:

```bash
git clone https://github.com/inematds/builder-ou-engineer.git
cd builder-ou-engineer && python3 -m http.server 8000   # abrir http://localhost:8000/guia/
```

Publicação: GitHub Pages pela Action `.github/workflows/pages.yml` (raiz do repo).

## Licença

MIT. Grátis no inema.club, direto na internet.
