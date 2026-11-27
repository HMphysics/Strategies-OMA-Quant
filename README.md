<div align="center">

# 📚 216 Quant Books · OMA Quant

### 216 quant finance books. Every strategy inside them, audited by an engine that can't be talked into a good result.

<p>
  <a href="https://github.com/HMphysics/Strategies-OMA-Quant/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/HMphysics/Strategies-OMA-Quant?style=for-the-badge&color=0B1F33&label=%E2%AD%90%20stars"></a>
  <a href="https://x.com/_HMPhysics_"><img alt="Follow @_HMPhysics_ on X" src="https://img.shields.io/badge/Follow-@__HMPhysics__-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://hmaquant.substack.com/s/216-quant-books"><img alt="Substack" src="https://img.shields.io/badge/Substack-216%20Quant%20Books-FF6719?style=for-the-badge&logo=substack&logoColor=white"></a>
  <a href="https://www.omaquant.com"><img alt="omaquant.com" src="https://img.shields.io/badge/omaquant.com-0B1F33?style=for-the-badge"></a>
</p>

**[English](#-english)** · **[Español](#-español)**

</div>

---

## 🇬🇧 English

### 🧭 The series

**216 Quant Books** is a series where we read a whole shelf of quantitative finance, one book at a time. The shelf is the one collected at [hft.md/quant-books](https://hft.md/quant-books/): 216 books, all free to read from their authors, universities or publishers.

From each book we pull out every idea that can become a trading strategy, write its rules down, code it on real market data and send it through **YGGDRASIL**, our audit engine. Then we tell you what happened: how the strategy plays, what it does well, where it breaks, and whether it earns a place in a real portfolio.

Each strategy is an episode. The series runs live on [X (@_HMPhysics_)](https://x.com/_HMPhysics_) and in long form on [Substack](https://hmaquant.substack.com/s/216-quant-books).

### 🌳 YGGDRASIL, the engine behind the verdicts

Most backtests look good because someone kept trying until one did. YGGDRASIL is built to make that impossible.

- **The verdict is decided before the backtest.** Rules and pass thresholds are written down and sealed before the first result exists. Nobody can move the goalposts afterwards, not even us.
- **58 checks on every strategy.** Integrity of the data, raw performance, randomness, overfitting, parameter sensitivity, where the edge really comes from, execution stress, regimes and operational limits.
- **Luck has to be ruled out.** Each strategy competes against shuffled and randomised versions of itself and against simply buying the market.
- **Every attempt is counted.** Each variant we try raises the bar the winner has to clear.
- **Unseen data.** The most recent months are kept out of the design and only looked at once the rules are fixed.

The result is a verdict you can trust in both directions: when a strategy passes, it earned it, and when it doesn't, you know exactly why.

> Testing 3,000 strategies is easy. Knowing which of the winners are just luck is the hard part.

Want the same engine on **your own strategies**? That's **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)**.

### 🏆 Strategies that passed the audit

| # | Strategy | Source book | Type | Assets | Sharpe | Max DD | File |
|:-:|---|---|---|---|:-:|:-:|:-:|
| | *None yet* | | | | | | |

> For strategies that pass we publish **what** they do and **how they scored**. The exact rules, the code and the live signals are for **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)** members.

### 📂 Every strategy we audit

Passed or not, each one gets a full file: the idea, how it plays, the record, what the engine checked and, at the end, the verdict.

| # | Strategy | Source book | Verdict | File |
|:-:|---|---|:-:|:-:|
| 1 | Risk parity across eight asset classes | Palomar, *Portfolio Optimization* (2025) | Not accepted | [open](strategies/001-risk-parity) |
| 2 | Pairs trading Australia against Canada (EWA/EWC) | Palomar, *Portfolio Optimization* (2025) | 🟡 Middle ground | [open](strategies/002-pairs-ewa-ewc) |
| 3 | Momentum across the Nasdaq-100 | Palomar, *Portfolio Optimization* (2025) | Not accepted | [open](strategies/003-momentum-ndx) |
| 4 | Risk parity with a 12-month trend filter · variants of [1](strategies/001-risk-parity) | Palomar, *Portfolio Optimization* (2025) | 🟡 Middle ground | [open](strategies/004-risk-parity-trend) |
| 5 | The pairs rulebook on three new pairs · variants of [2](strategies/002-pairs-ewa-ewc) | Palomar, *Portfolio Optimization* (2025) | Not accepted | [open](strategies/005-pairs-variants) |
| 6 | Minimum variance across the sectors | Palomar, *Portfolio Optimization* (2025) | 🟡 Middle ground | [open](strategies/006-sector-min-variance) |

### 📖 Series progress

| Book | Author | Strategies audited | Passed | Episodes |
|:-:|---|:-:|:-:|:-:|
| 1 · *Portfolio Optimization: Theory and Application* | Daniel P. Palomar | 6 so far | – | [0](https://hmaquant.substack.com/p/216-quant-books-episode-0-reading) · [1](https://hmaquant.substack.com/p/216-quant-books-episode-1-risk-parity) · [2](https://hmaquant.substack.com/p/216-quant-books-episode-2-pairs-trading) |

<sub>Reading order: first the books that propose strategies directly, then the techniques, and the foundations last.</sub>

### 🧩 About OMA Quant

**OMA Quant is a quantitative research house for independent investors.** We build systematic strategies, macro and derivatives research, and the data and tools behind them, and we put all of it in the hands of people who invest on their own.

This series is a window into how we work: the same data, the same discipline and the same engine we rely on every day.

| Product | What you get |
|---|---|
| **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)** | Live signals from our 25 strategies on Discord, with a members' community and live analysis. Includes 12 intraday strategies for prop firms and funded accounts. |
| **[OMA Research](https://www.omaquant.com/research?cupon=OMAQUANT-10)** | Macro and derivatives reports built on proprietary indicators, options flow, GEX and VIX. |
| **[OMA Terminal](https://www.omaquant.com/terminal?cupon=OMAQUANT-10)** | 3,000+ market time series and our proprietary indicators in one place. |
| **[OMA Brain](https://www.omaquant.com/brain?cupon=OMAQUANT-10)** | About 1,800 quant research notes, ready to plug into Claude, ChatGPT or your own agents. |
| **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)** | YGGDRASIL, the engine behind this series, on your own strategies. |
| **[OMA Suite](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)** | All of the above in one subscription. |

### 🔔 Follow the series

- ⭐ **Star the repo** to see each new strategy as it lands (*Watch → Custom → Releases* for notifications).
- 𝕏 **[@_HMPhysics_](https://x.com/_HMPhysics_)**: every episode, live.
- 📰 **[Substack · 216 QUANT BOOKS](https://hmaquant.substack.com/s/216-quant-books)**: the long version of each episode.
- 💬 **[Discord community](https://discord.gg/Y4eygGWGS5)**

### 🎟️ If the series is useful to you

Share it. **[Post it on X](https://x.com/intent/post?text=216%20quant%20books%2C%20every%20strategy%20audited%20by%20an%20engine%20that%20can%27t%20be%20talked%20into%20a%20good%20result.%20%F0%9F%93%9A%F0%9F%93%88&url=https%3A%2F%2Fgithub.com%2FHMphysics%2FStrategies-OMA-Quant)**, send it to a friend who trades, or drop a star. As a thank you, the code **`OMAQUANT-10`** takes **10% off any OMA Quant product**. **[This link applies it for you](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**, even if you create your account first.

<sub>
The books belong to their authors and publishers. None is hosted or redistributed here: each book is cited with its official link. This repository is educational content and is not financial advice. Backtest results, however rigorous, do not guarantee future returns. Investing involves risk of loss.
</sub>

---

## 🇪🇸 Español

### 🧭 La serie

**216 libros quant** es una serie en la que nos leemos una estantería entera de finanzas cuantitativas, libro a libro. La estantería es la recopilada en [hft.md/quant-books](https://hft.md/quant-books/): 216 libros, todos de lectura gratuita desde la web de sus autores, universidades o editoriales.

De cada libro sacamos todas las ideas que se pueden convertir en una estrategia, fijamos sus reglas, las programamos con datos reales y las pasamos por **YGGDRASIL**, nuestro motor de auditoría. Luego contamos qué ha pasado: cómo juega la estrategia, qué hace bien, dónde falla y si se gana un sitio en una cartera de verdad.

Cada estrategia es un episodio. La serie va en directo en [X (@_HMPhysics_)](https://x.com/_HMPhysics_) y en versión larga en [Substack](https://hmaquant.substack.com/s/216-quant-books).

### 🌳 YGGDRASIL, el motor detrás de los veredictos

La mayoría de los backtests salen bien porque alguien siguió probando hasta que uno salió bien. YGGDRASIL está hecho para que eso no pueda pasar.

- **El veredicto se decide antes del backtest.** Las reglas y los umbrales de aprobado se escriben y se sellan antes de que exista el primer resultado. Nadie puede mover la portería después, ni siquiera nosotros.
- **58 comprobaciones en cada estrategia.** Integridad de los datos, rendimiento, azar, sobreajuste, sensibilidad a los parámetros, de dónde sale de verdad el edge, estrés de ejecución, regímenes y límites operativos.
- **Hay que descartar la suerte.** Cada estrategia compite contra versiones barajadas y aleatorias de sí misma y contra comprar el mercado sin más.
- **Se cuentan todos los intentos.** Cada variante que probamos sube el listón que tiene que superar la ganadora.
- **Datos que no se han visto.** Los últimos meses se dejan fuera del diseño y solo se miran cuando las reglas ya están fijadas.

El resultado es un veredicto fiable en los dos sentidos: cuando una estrategia pasa, se lo ha ganado, y cuando no, sabes exactamente por qué.

> Probar 3.000 estrategias es fácil. Lo difícil es saber cuáles de las que salen bien son suerte.

¿Quieres el mismo motor para **tus propias estrategias**? Eso es **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)**.

### 🏆 Estrategias que han superado la auditoría

| # | Estrategia | Libro de origen | Tipo | Activos | Sharpe | Máx. DD | Ficha |
|:-:|---|---|---|---|:-:|:-:|:-:|
| | *Todavía ninguna* | | | | | | |

> De las que pasan publicamos **qué hacen** y **cómo les ha ido** en la auditoría. Las reglas, el código y las señales en directo son para los miembros de **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)**.

### 📂 Todas las estrategias auditadas

Pasen o no, cada una tiene su ficha completa: la idea, cómo juega, los resultados, qué comprobó el motor y, al final, el veredicto.

| # | Estrategia | Libro de origen | Veredicto | Ficha |
|:-:|---|---|:-:|:-:|
| 1 | Risk parity sobre ocho clases de activo | Palomar, *Portfolio Optimization* (2025) | No aceptada | [abrir](strategies/001-risk-parity) |
| 2 | Pairs trading Australia contra Canadá (EWA/EWC) | Palomar, *Portfolio Optimization* (2025) | 🟡 Media | [abrir](strategies/002-pairs-ewa-ewc) |
| 3 | Momentum en el Nasdaq-100 | Palomar, *Portfolio Optimization* (2025) | No aceptada | [abrir](strategies/003-momentum-ndx) |
| 4 | Risk parity con filtro de tendencia de 12 meses · variantes de la [1](strategies/001-risk-parity) | Palomar, *Portfolio Optimization* (2025) | 🟡 Media | [abrir](strategies/004-risk-parity-trend) |
| 5 | Las reglas de pares en tres pares nuevos · variantes de la [2](strategies/002-pairs-ewa-ewc) | Palomar, *Portfolio Optimization* (2025) | No aceptada | [abrir](strategies/005-pairs-variants) |
| 6 | Mínima varianza por sectores | Palomar, *Portfolio Optimization* (2025) | 🟡 Media | [abrir](strategies/006-sector-min-variance) |

### 📖 Progreso de la serie

| Libro | Autor | Estrategias auditadas | Pasan | Episodios |
|:-:|---|:-:|:-:|:-:|
| 1 · *Portfolio Optimization: Theory and Application* | Daniel P. Palomar | 6 por ahora | – | [0](https://hmaquant.substack.com/p/216-quant-books-episode-0-reading) · [1](https://hmaquant.substack.com/p/216-quant-books-episode-1-risk-parity) · [2](https://hmaquant.substack.com/p/216-quant-books-episode-2-pairs-trading) |

<sub>Orden de lectura: primero los libros que proponen estrategias directas, luego las técnicas y al final los fundamentos.</sub>

### 🧩 Qué es OMA Quant

**OMA Quant es una casa de research cuantitativo para inversores independientes.** Construimos estrategias sistemáticas, research de macro y derivados, y los datos y herramientas que hay detrás, y lo ponemos todo en manos de quien invierte por su cuenta.

Esta serie es una ventana a cómo trabajamos: los mismos datos, la misma disciplina y el mismo motor que usamos cada día.

| Producto | Qué te llevas |
|---|---|
| **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)** | Las señales en directo de nuestras 25 estrategias en Discord, con comunidad y análisis en vivo. Incluye 12 intradía para prop firms y cuentas fondeadas. |
| **[OMA Research](https://www.omaquant.com/research?cupon=OMAQUANT-10)** | Informes de macro y derivados con indicadores propios, flujo de opciones, GEX y VIX. |
| **[OMA Terminal](https://www.omaquant.com/terminal?cupon=OMAQUANT-10)** | Más de 3.000 series de mercado y nuestros indicadores en un solo lugar. |
| **[OMA Brain](https://www.omaquant.com/brain?cupon=OMAQUANT-10)** | Unas 1.800 notas de research quant, listas para conectar a Claude, ChatGPT o tus agentes. |
| **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)** | YGGDRASIL, el motor de esta serie, sobre tus propias estrategias. |
| **[OMA Suite](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)** | Todo lo anterior en una sola suscripción. |

### 🔔 Sigue la serie

- ⭐ **Dale una estrella al repo** para enterarte de cada estrategia nueva (*Watch → Custom → Releases* si quieres aviso).
- 𝕏 **[@_HMPhysics_](https://x.com/_HMPhysics_)**: cada episodio, en directo.
- 📰 **[Substack · 216 QUANT BOOKS](https://hmaquant.substack.com/s/216-quant-books)**: la versión larga de cada episodio.
- 💬 **[Comunidad en Discord](https://discord.gg/Y4eygGWGS5)**

### 🎟️ Si la serie te resulta útil

Compártela. **[Publícala en X](https://x.com/intent/post?text=216%20libros%20quant%2C%20cada%20estrategia%20auditada%20por%20un%20motor%20al%20que%20no%20se%20le%20puede%20convencer%20de%20un%20buen%20resultado.%20%F0%9F%93%9A%F0%9F%93%88&url=https%3A%2F%2Fgithub.com%2FHMphysics%2FStrategies-OMA-Quant)**, pásasela a alguien que opere o déjale una estrella. Como agradecimiento, el código **`OMAQUANT-10`** te da un **10 % de descuento en cualquier producto de OMA Quant**. **[Este enlace te lo aplica solo](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**, aunque antes tengas que crearte la cuenta.

<sub>
Los libros pertenecen a sus autores y editoriales. Aquí no se aloja ni se redistribuye ninguno: cada libro se cita con su enlace oficial. Este repositorio es contenido educativo y no constituye asesoramiento financiero. Los resultados de un backtest, aunque sea riguroso, no garantizan rendimientos futuros. Invertir conlleva riesgo de pérdida.
</sub>
