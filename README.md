# FoodResq Backend Keep-Alive

This repository contains a GitHub Actions workflow used to keep the FoodResq backend awake.

## What it does

- Sends a GET request to: https://foodresq-backend.onrender.com/api/listings
- Runs every 10 minutes between 07:00 and 22:00 Bucharest time (EET / UTC+2)
- Can also be started manually from the GitHub Actions tab using workflow_dispatch
