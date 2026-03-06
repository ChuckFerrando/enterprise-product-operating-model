# Portfolio Heatmap Visualization

The Portfolio Heatmap is used during portfolio governance reviews to visualize proposed and active initiatives across key decision dimensions.

The visualization helps leadership evaluate tradeoffs between strategic alignment, delivery risk, and investment size when prioritizing initiatives.

---

## Example Portfolio Heatmap

```mermaid
quadrantChart
    title Portfolio Investment Evaluation

    x-axis Low Strategic Alignment --> High Strategic Alignment
    y-axis Low Delivery Risk --> High Delivery Risk

    quadrant-1 Invest Aggressively
    quadrant-2 Monitor / Manage Risk
    quadrant-3 Reconsider Investment
    quadrant-4 Strategic Bets

    Initiative A: [0.85, 0.30]
    Initiative B: [0.60, 0.75]
    Initiative C: [0.30, 0.40]
    Initiative D: [0.75, 0.85]
