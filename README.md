# TradingOS Configuration Migration & API Layer

## Overview
This repository contains the architecture and migration framework for **TradingOS**, shifting our core configuration management from legacy YAML files to a robust, transactional **SQLite database** paired with a lightweight **RESTful API layer**. 

Designed for high-frequency algorithmic trading systems (supporting multiple broker environments such as Fintokei and Titan), this project ensures secure data handling, clean separation of concerns, and atomic configuration updates without interrupting live execution threads.

---

## Architecture Design
