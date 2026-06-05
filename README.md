# D3

**D3** is a platform for market data research, trading scenario simulation, and strategy testing.

The project is currently in active private development.  
This repository serves as a public project page for the project concept, screenshots, development notes, and release information.

<img width="1915" height="958" alt="d3" src="https://github.com/user-attachments/assets/e07a7dd0-bb20-49bb-a928-82e29f9af4e0" />
---

## Project Idea

D3 is being developed as a research environment for working with market data.

The goal of the project is to provide a system where market data can be connected, analyzed with indicators and processors, used in simulations, and applied to research the behavior of trading algorithms.

D3 is focused not only on chart viewing, but also on step-by-step inspection of what happens inside a trading model: what data is received, which indicators are calculated, how trading agents react, and what results those reactions lead to.

---

## Project Scope

D3 is designed around several core directions.

### Market Data

D3 is designed to support different market data sources:

* local datasets;
* historical data;
* online sources;
* real-time streaming data.

The goal is to make it possible to work both with prepared datasets and with live market data.

### Indicators and Processors

Connected market data can be processed by indicators and computational processors.

Indicators and processors sequentially handle market events, calculate values, store intermediate results, and provide data for further analysis, simulation, or decision-making.

### Trading Agents

One of the project directions is the creation of trading agents.

Trading agents are intended to react to market events, use indicator data, make trading decisions, and participate in simulations.

The purpose of these simulations is to research algorithmic behavior and explore potentially effective trading approaches.

### Simulations

D3 is designed to support different simulation modes:

* step-by-step market data replay;
* interactive debugging of trading logic;
* accelerated simulations on historical data;
* analysis of indicators, processors, and trading agents.

Simulation is treated not only as a way to get a final result, but also as a way to understand the process itself: what events occurred, what reactions were triggered, and why the system reached a particular state.

---

## Concept

D3 is built around the idea of sequential event processing.

The market can be represented as a stream of data and events.  
D3 is intended to provide an environment where these events pass through a set of connected components:

1. data source;
2. market data window;
3. indicators;
4. processors;
5. trading agents;
6. simulation engine;
7. analysis results.

This approach makes it possible to research not only the final result of a strategy, but also the entire chain of system reactions to market changes.

---

## Current Status

D3 is an independent experimental project currently being developed in private.

The project is not production-ready yet. Its current goal is to validate the core architecture, explore market data simulation workflows, and gradually shape the first usable version of D3 Studio.

At the current stage, the main focus is on:

* the runtime core;
* market data windows;
* viewing and simulation modes;
* indicator and processor infrastructure;
* the basic architecture of D3 Studio.

---

## Source Code

The source code is currently private.

D3 is being developed in a closed mode until the project reaches a stable `1.0` milestone.  
The source code is planned to be opened after the closed development stage.

This repository currently serves as a public project page, development log, and place for release information.
