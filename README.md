# F1 Championship Simulator

A powerful Formula 1 simulator run in Jupyter Notebook, using **Monte Carlo methods** to predict race results and championships. Featuring historical driver data, dynamic track/weather modeling, and a multi-tab interactive dashboard built with `ipywidgets`.

***

## ✨ Key Features

- **Multi-Tab Dashboard:** Organizes all simulation modes in five easy tabs.
- **Championship Simulation:** Predict Drivers' and Constructors' standings.
- **Advanced Modeling:** Includes driver skills, form, team dynamics, and track/weather variables.
- **Rich Visualizations:** Points progression, race results, driver distributions.
- **Scenario Planning:** Save and reload "What-If" scenarios as `f1_scenario.json`.

***

## 🔢 Dashboard Tabs

| Tab | Function |
|-----|----------|
| 🏆 Full Championship | Full-season simulation—visualize title battles. |
| 🤜 1v1 Head-to-Head | Compare any two drivers over multiple races. |
| 🟢 Next Race Predictor | Predicts the next race with full detail. |
| 🔧 Custom Race | Simulate any track/weather/rules scenario. |
| 🧪 What-If Scenario | Manually set results, simulate outcomes, and save/load states. |

***

## 🌍 Circuit/Track Data

Each track is modeled for:
- Weather probabilities (Sunny, Rainy, Stormy)
- Custom DNF multipliers
- Street/mixed/special conditions

Includes tracks like Monaco, Silverstone, Suzuka, Spa-Francorchamps, and many more with tailored event probabilities.

***

## 🏎️ Initial Driver Standings

- McLaren: Oscar Piastri, Lando Norris
- Red Bull: Max Verstappen, Liam Lawson
- Ferrari: Charles Leclerc, Lewis Hamilton
- Mercedes: George Russell, Kimi Antonelli
- Many more—see table for details!

***

## 🚀 How to Run

### Prerequisites

```bash
pip install numpy matplotlib ipywidgets jupyterlab
```

### Steps

1. Save as `F1SIM.ipynb`.
2. Run: `jupyter lab`
3. Open notebook, run all cells—the dashboard launches!

***

## 🧠 Simulation Logic

- **Monte Carlo Racing:** 1000s of probabilistic runs per race.
- **Performance, Bias & Form:** Driver history, skills, team dynamics.
- **Weather & DNF:** Adjusts for each circuit’s unique risk profile.
- **Aggregation:** Builds real-world championship predictions.

***

## 💡 Technology Stack

- Python (Jupyter Notebook/JupyterLab)
- `numpy`, `matplotlib`, `ipywidgets`, `json`

***

**Enjoy simulating an entire F1 championship—make your own drama, rivalries, and surprises!**
