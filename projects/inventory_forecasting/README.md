# Inventory Forecasting

## Purpose

Build a practical forecasting project that predicts future inventory demand or stock needs. This project is a strong fit for combining SQL, backend systems, business constraints, time-series reasoning, and ML evaluation.

## Problem Framing

Potential question: given historical inventory, sales, seasonality, and operational signals, can a model estimate future demand or replenishment needs better than simple rules?

No dataset is assumed. Data discovery is part of the project.

## Possible Approaches

- Naive baseline using recent averages
- Seasonal baseline using comparable prior periods
- Classical ML regression with engineered time features
- Time-series forecasting methods
- Deep learning only if simpler approaches justify the added complexity

## Evaluation Ideas

- Mean absolute error
- Root mean squared error
- Mean absolute percentage error where appropriate
- Stockout-oriented or overstock-oriented cost metrics
- Backtesting across historical time windows

## Milestones

- [ ] Define the inventory domain and target prediction.
- [ ] Identify possible public, synthetic, or self-created data sources.
- [ ] Create baseline forecasting strategy.
- [ ] Define evaluation windows and metrics.
- [ ] Draft deployment concept for scheduled batch forecasts.

## Next Actions

- [ ] Write a one-page problem statement.
- [ ] List candidate datasets without assuming availability.
- [ ] Define what a useful forecast would mean to a user.
