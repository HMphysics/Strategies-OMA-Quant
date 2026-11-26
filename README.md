<div align="center">

# 📚 Strategies · OMA Quant

### 216 quant finance books. One anti-overfitting engine. Only the strategies that hold up survive.

<p>
  <a href="https://www.omaquant.com/pricing?cupon=OMAQUANT-10"><img alt="10% off with OMAQUANT-10" src="https://img.shields.io/badge/COUPON-OMAQUANT--10%20%C2%B7%20%E2%88%9210%25-C9A227?style=for-the-badge"></a>
  <a href="https://github.com/HMphysics/Strategies-OMA-Quant/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/HMphysics/Strategies-OMA-Quant?style=for-the-badge&color=0B1F33&label=%E2%AD%90%20stars"></a>
  <a href="https://www.omaquant.com"><img alt="omaquant.com" src="https://img.shields.io/badge/omaquant.com-0B1F33?style=for-the-badge"></a>
  <a href="https://x.com/_HMPhysics_"><img alt="Follow @_HMPhysics_ on X" src="https://img.shields.io/badge/Follow-@__HMPhysics__-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://discord.gg/Y4eygGWGS5"><img alt="Discord" src="https://img.shields.io/badge/Discord-community-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>
</p>

**[⭐ Star it](https://github.com/HMphysics/Strategies-OMA-Quant)** · **[𝕏 Follow @_HMPhysics_](https://x.com/_HMPhysics_)** · **[🔁 Share it on X](https://x.com/intent/post?text=They%27re%20reading%20216%20quant%20books%20and%20running%20every%20strategy%20through%20an%20anti-overfitting%20engine.%20Only%20the%20survivors%20get%20published%20%F0%9F%93%9A%F0%9F%93%88&url=https%3A%2F%2Fgithub.com%2FHMphysics%2FStrategies-OMA-Quant)** · **[🎟️ Use the coupon](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

**[English](#-english)** · **[Español](#-español)**

</div>

---

## 🇬🇧 English

### 🎟️ 10% off for you if you share it

If this repo is useful to you, **star it ⭐ and share it**. In return you get **10% off any OMA Quant product** with the code:

<div align="center">

#### `OMAQUANT-10`

**👉 [Open OMA with the coupon already applied](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

</div>

The link remembers the coupon and applies it at checkout, even if you need to create an account first.

### 🧭 What this is

Someone shared a shelf of **216 quant finance books**, all free to read from their authors, universities or publishers ([hft.md/quant-books](https://hft.md/quant-books/)).

We are reading them **one by one**. From each book we take the ideas that can become a strategy, code them on real market data and run them through **YGGDRASIL**, our audit engine. The engine doesn't hunt for the best-looking curve. It freezes the pass criteria **before** seeing any result, measures how much of the performance is luck, and penalises every extra attempt.

> Testing 3,000 strategies is easy. Knowing which of the winners are just luck is the hard part.

Each book is an episode of the series. We tell the story live on [X (@_HMPhysics_)](https://x.com/_HMPhysics_) and on [Substack](https://hmaquant.substack.com/s/216-quant-books).

### 🏆 Strategies that passed the audit

| # | Strategy | Source book | Type | Assets | Sharpe | Max DD | Card |
|:-:|---|---|---|---|:-:|:-:|:-:|
| | *Coming soon* | *Book 1 · Portfolio Optimization (Palomar, 2025)* | | | | | |

> We only publish **what** each strategy does and **how it scored** in the audit. The exact rules, the code and the live signals are for **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)** members.

### 📂 Strategy files

Every strategy we audit gets a full file here: the idea, how it plays, the record, what the engine checked and, at the end, the verdict.

| # | Strategy | Source book | File |
|:-:|---|---|:-:|
| 1 | Risk parity across eight asset classes | Palomar, *Portfolio Optimization* (2025) | [open](strategies/001-risk-parity) |
| 2 | Pairs trading Australia against Canada (EWA/EWC) | Palomar, *Portfolio Optimization* (2025) | [open](strategies/002-pairs-ewa-ewc) |

### 📖 Series progress

| Book | Author | Ideas tested | Passed the audit | Episode |
|:-:|---|:-:|:-:|:-:|
| 1 · *Portfolio Optimization: Theory and Application* | Daniel P. Palomar | in progress | – | [Episode 0](https://hmaquant.substack.com/p/216-quant-books-episode-0-reading) · [Episode 1](https://hmaquant.substack.com/p/216-quant-books-episode-1-risk-parity) |

<sub>216 books in total. Reading order: first the books that propose strategies directly, then the techniques, and the foundations last.</sub>

### 🔬 How we audit (without showing the engine)

```
 Book ──► Idea ──► Rules fixed ──► Criteria frozen ──► YGGDRASIL ──► Verdict
                   (before any      (hashed, no         nulls · stress ·
                    data is seen)    way back)           overfitting · regimes
```

- **Rules first.** Parameters and pass thresholds are written down and frozen before the first result is seen.
- **Against randomness.** Every strategy competes with randomised versions of itself and with buy-and-hold.
- **Every attempt counts.** The more variants we try, the higher the bar (Deflated Sharpe Ratio and probability of backtest overfitting).
- **Stress.** Costs multiplied, late execution, regime changes.

Want to run **your own strategies** through the engine? That's **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)**.

### 🧩 OMA Quant

**A quantitative macro research house for independent investors.**

| Product | What it is |
|---|---|
| **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)** | Live signals from our 25 strategies on Discord, with a members' community and live analysis. Includes 12 intraday strategies for prop firms and funded accounts. |
| **[OMA Research](https://www.omaquant.com/research?cupon=OMAQUANT-10)** | Macro and derivatives reports built on proprietary indicators, options flow, GEX and VIX. |
| **[OMA Terminal](https://www.omaquant.com/terminal?cupon=OMAQUANT-10)** | 3,000+ market time series and our proprietary indicators in one place. |
| **[OMA Brain](https://www.omaquant.com/brain?cupon=OMAQUANT-10)** | About 1,800 quant research notes to plug into Claude, ChatGPT or your own agents. |
| **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)** | The YGGDRASIL audit engine on your own strategies. |
| **[OMA Suite](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)** | All of the above in one subscription. |

<div align="center">

**🎟️ `OMAQUANT-10` → [10% off any of them](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

</div>

### 🔔 Follow along

- ⭐ **Star the repo** to see each new strategy as it lands (use *Watch → Custom → Releases* for notifications).
- 𝕏 **[Follow @_HMPhysics_ on X](https://x.com/_HMPhysics_)**: the series is told live there, book by book.
- 📰 **[Substack · 216 QUANT BOOKS](https://hmaquant.substack.com/s/216-quant-books)**: one long-form episode per book.
- 💬 **[Discord community](https://discord.gg/Y4eygGWGS5)**
- 🌐 **[omaquant.com](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

<sub>
The books belong to their authors and publishers. None is hosted or redistributed here: each book is cited with its official link. This repository is educational content and is not financial advice. Backtest results, however rigorous, do not guarantee future returns. Investing involves risk of loss.
</sub>

---

## 🇪🇸 Español

### 🎟️ Un 10 % para ti si lo compartes

Si este repo te parece útil, **dale una ⭐ y compártelo**. A cambio tienes un **10 % de descuento en cualquier producto de OMA Quant** con el cupón:

<div align="center">

#### `OMAQUANT-10`

**👉 [Entra con el cupón ya aplicado](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

</div>

El enlace guarda el cupón y lo aplica solo al pagar, aunque antes tengas que crearte la cuenta.

**[🔁 Compártelo en X](https://x.com/intent/post?text=Est%C3%A1n%20leyendo%20216%20libros%20quant%20y%20pasando%20cada%20estrategia%20por%20un%20motor%20antisobreajuste.%20Solo%20publican%20las%20que%20sobreviven%20%F0%9F%93%9A%F0%9F%93%88&url=https%3A%2F%2Fgithub.com%2FHMphysics%2FStrategies-OMA-Quant)**

### 🧭 Qué es esto

Alguien publicó una estantería con **216 libros de finanzas cuantitativas**, todos de lectura gratuita desde la web de sus autores, universidades o editoriales ([hft.md/quant-books](https://hft.md/quant-books/)).

Nosotros nos los vamos a leer **uno a uno**. De cada libro sacamos las ideas que se pueden convertir en una estrategia, las programamos con datos reales y las pasamos por **YGGDRASIL**, nuestro motor de auditoría. El motor no busca la mejor curva. Fija los criterios **antes** de mirar los resultados, mide cuánto se debe a la suerte y castiga cada intento de más.

> Probar 3.000 estrategias es fácil. Lo difícil es saber cuáles de las que salen bien son suerte.

Cada libro es un episodio de la serie. Lo vamos contando en directo en [X (@_HMPhysics_)](https://x.com/_HMPhysics_) y en [Substack](https://hmaquant.substack.com/s/216-quant-books).

### 🏆 Estrategias que han superado la auditoría

| # | Estrategia | Libro de origen | Tipo | Activos | Sharpe | Máx. DD | Ficha |
|:-:|---|---|---|---|:-:|:-:|:-:|
| | *Próximamente* | *Libro 1 · Portfolio Optimization (Palomar, 2025)* | | | | | |

> Aquí solo publicamos **qué hace** cada estrategia y **cómo le ha ido** en la auditoría. Las reglas, el código y las señales en directo son para los miembros de **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)**.

### 📂 Fichas de estrategias

Cada estrategia que auditamos tiene aquí su ficha completa: la idea, cómo juega, los resultados, qué comprobó el motor y, al final, el veredicto.

| # | Estrategia | Libro de origen | Ficha |
|:-:|---|---|:-:|
| 1 | Risk parity sobre ocho clases de activo | Palomar, *Portfolio Optimization* (2025) | [abrir](strategies/001-risk-parity) |
| 2 | Pairs trading Australia contra Canadá (EWA/EWC) | Palomar, *Portfolio Optimization* (2025) | [abrir](strategies/002-pairs-ewa-ewc) |

### 📖 Progreso de la serie

| Libro | Autor | Ideas probadas | Superan la auditoría | Episodio |
|:-:|---|:-:|:-:|:-:|
| 1 · *Portfolio Optimization: Theory and Application* | Daniel P. Palomar | en curso | – | [Episodio 0](https://hmaquant.substack.com/p/216-quant-books-episode-0-reading) |

<sub>216 libros en total. Orden de lectura: primero los que proponen estrategias directas, luego las técnicas y al final los fundamentos.</sub>

### 🔬 Cómo auditamos (sin enseñar el motor)

```
 Libro ──► Idea ──► Reglas fijadas ──► Criterios congelados ──► YGGDRASIL ──► Veredicto
                    (antes de ver        (hash, sin vuelta        nulos · estrés ·
                     ningún dato)         atrás)                   sobreajuste · regímenes
```

- **Primero se fijan las reglas.** Los parámetros y los umbrales de aprobado se escriben y se congelan antes de ver el primer resultado.
- **Se compara con el azar.** Cada estrategia compite contra versiones aleatorias de sí misma y contra comprar y mantener.
- **Se cuentan todos los intentos.** Cuantas más variantes se prueban, más exigente es el listón (Sharpe deflactado y probabilidad de sobreajuste).
- **Se estresa.** Costes multiplicados, ejecución tarde, cambios de régimen.

¿Quieres pasar **tus propias estrategias** por el motor? Eso es **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)**.

### 🧩 OMA Quant

**Una casa de research macro cuantitativo para inversores independientes.**

| Producto | Qué es |
|---|---|
| **[OMA Capital](https://www.omaquant.com/capital?cupon=OMAQUANT-10)** | Las señales en directo de nuestras 25 estrategias en Discord, con comunidad y análisis en vivo. Incluye 12 intradía para prop firms y cuentas fondeadas. |
| **[OMA Research](https://www.omaquant.com/research?cupon=OMAQUANT-10)** | Informes de macro y derivados con indicadores propios, flujo de opciones, GEX y VIX. |
| **[OMA Terminal](https://www.omaquant.com/terminal?cupon=OMAQUANT-10)** | Más de 3.000 series de mercado y nuestros indicadores en un solo lugar. |
| **[OMA Brain](https://www.omaquant.com/brain?cupon=OMAQUANT-10)** | Unas 1.800 notas de research quant para conectar a Claude, ChatGPT o tus agentes. |
| **[OMA Lab](https://www.omaquant.com/lab?cupon=OMAQUANT-10)** | El motor de auditoría YGGDRASIL sobre tus estrategias. |
| **[OMA Suite](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)** | Todo lo anterior en una sola suscripción. |

<div align="center">

**🎟️ `OMAQUANT-10` → [10 % de descuento en cualquiera de ellos](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

</div>

### 🔔 Síguelo

- ⭐ **Dale una estrella al repo** para enterarte cada vez que entra una estrategia nueva (usa *Watch → Custom → Releases* si quieres aviso).
- 𝕏 **[Sígueme en X: @_HMPhysics_](https://x.com/_HMPhysics_)**: allí cuento la serie en directo, libro a libro.
- 📰 **[Substack · 216 QUANT BOOKS](https://hmaquant.substack.com/s/216-quant-books)**: un episodio largo por libro.
- 💬 **[Comunidad en Discord](https://discord.gg/Y4eygGWGS5)**
- 🌐 **[omaquant.com](https://www.omaquant.com/pricing?cupon=OMAQUANT-10)**

<sub>
Los libros pertenecen a sus autores y editoriales. Aquí no se aloja ni se redistribuye ninguno: cada libro se cita con su enlace oficial. Este repositorio es contenido educativo y no constituye asesoramiento financiero. Los resultados de un backtest, aunque sea riguroso, no garantizan rendimientos futuros. Invertir conlleva riesgo de pérdida.
</sub>
