# Logistics Alliance: shipment data entry

HachiAi, logistics.

[Back to portfolio](../../README.md)

## Problem

Staff entered shipment data into the logistics system by hand, which took more than 40 hours a week and produced mismatches.

## What I built

1. The bot reads shipment details from structured Excel reports.
2. It posts them to the logistics system through REST APIs.
3. Every response and exception is logged centrally.

Credentials and endpoints sit in Orchestrator assets, and retries cover transient API failures. The design is modular, so new endpoints and formats can be added.

## Result

- **40+ hours** saved every week
- **50%** fewer errors
- A full audit log of every posting

## Stack

UiPath, Orchestrator, REST APIs, Excel
