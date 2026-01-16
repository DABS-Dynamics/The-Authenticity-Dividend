# The Authenticity Dividend

Simulation codebase for the research paper **"The Authenticity Dividend: Algorithmic Fraud-Resilience and Revenue Optimization in the Post-Streaming Era"**.

This model introduces an intent-weighted ("Entanglement") payout algorithm that:
- Isolates bot/smart-bot fraud mathematically
- Delivers +77.7% revenue to niche artists under normal conditions
- Increases to +181% under heavy adversarial bot attacks (anti-fragile)

## Key Results
- Noise/Bot artists: –89.2% (base) → –71.5% (smart bot stress test)
- Niche artists: +77.7% → +181.3%
- Star artists: +71.4% → +178.8%
- Total revenue conserved ($700k pool)

COMING SOON.............

## Project Structure
- `config.py` — Simulation hyperparameters
- `simulation.py` — Core Entanglement Algorithm
- `main.py` — Entry point
- `requirements.txt` — Dependencies

## How to Run
```bash
pip install -r requirements.txt
python main.py
