# Microphone vs Pen

Marcel Proust wrote *In Search of Lost Time* by hand.
13 years. 7 volumes. 1,500,000 words.

I'm dictating 1,500,000 prompts to Claude through Genspark Speakly.
Each spoken word produces ~15 words of code. ~2 lines.
Target output: 3,200,000 lines of code.

**He had a pen. I have a microphone.**

→ **Live tracker:** https://grimonprezedition-art.github.io/microphone-vs-pen/

---

## The reference

| Volume | Words | Year |
|---|---|---|
| Du côté de chez Swann | 224,000 | 1913 |
| À l'ombre des jeunes filles en fleurs | 213,000 | 1919 |
| Le côté de Guermantes | 311,000 | 1920–21 |
| Sodome et Gomorrhe | 240,000 | 1921–22 |
| La Prisonnière | 142,000 | 1923 † |
| Albertine disparue | 119,000 | 1925 † |
| Le Temps retrouvé | 213,000 | 1927 † |
| **Total** | **~1,500,000** | **1909–1922** |

## The pace

|  | François | Proust |
|---|---|---|
| Method | Voice + AI | Hand + pen |
| Daily output | ~8,100 words | ~316 words |
| Ratio | **×26 faster** | reference |

## Why publish this

Proust took 13 years because writing *is* slow.
Voice + AI is a phase shift, not an improvement. The bottleneck moved from hand to mouth, then from mouth to thinking.

This tracker is one runner posting their splits.

## Stack

- Single-file HTML/CSS/JS, no dependencies
- [Genspark Speakly](https://www.genspark.ai/) for dictation
- Claude (Opus 4.7 / Sonnet 4.6) for code generation
- `localStorage` for the running counter
- No backend, no tracking, no analytics

## License

MIT.
