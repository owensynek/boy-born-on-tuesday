# The Boy Born on Tuesday — Bayesian Probability Tear Sheet

An interactive probability tear sheet exploring Gary Foshee's 2010 two-child puzzle, where specifying the day of the week shifts the posterior probability from 1/3 to 13/27 (≈ 48.1%).

### 👉 **[Launch the Live Interactive Website](https://owensynek.github.io/boy-born-on-tuesday/)**

---

## Interactive Features

* **Probability as Area (Fig. 1):** Interactive unit-square geometric representation of Bayes' theorem using the classic librarian-versus-farmer base-rate problem.
* **Warm-up Grid:** The baseline 2×2 two-child sample space without the day-of-the-week condition (P = 1/3).
* **Full 14×14 Sample Space (Fig. 2):** Step-by-step interactive grid shading all 196 equally likely two-child combinations and isolating the overlap cell.
* **Rarity Slider & Likelihood Bars (Fig. 3 & Fig. 4):** Real-time slider showing how a trait shared by 1 in k boys shifts the probability according to (2 - p) / (4 - p).
* **Monte Carlo Simulator (Fig. 5):** Non-blocking simulation up to 5,000,000 trials with a live log-scale convergence chart comparing different ways of learning the clue.

## Credits & Sources

* **Assembly:** Owen Synek using Claude Opus 5.5 (Anthropic).
* **Puzzle Origin:** Gary Foshee at the ninth *Gathering 4 Gardner* (2010), expanding on Martin Gardner's two-children problem (1959).
* **Sample-Space Visual & Generalization:** Inspired by YATAQi, *"The Most Controversial Puzzle in Probability"* (2026).
* **Probability-as-Area Visual:** Inspired by 3Blue1Brown, *"Bayes theorem, the geometry of changing beliefs"* (2019), based on base-rate research by Daniel Kahneman and Amos Tversky.

## License

Released under the MIT License.
