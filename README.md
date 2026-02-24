# Coffee Machine

A small, robust Python program that simulates a real-world coffee vending machine. It provides an interactive CLI for selecting drinks, manages resources (water, milk, coffee), handles coin transactions, and includes clear error and state handling for a predictable user experience.

**Highlights**

- Interactive command-line interface for ordering drinks
- Tracks and updates internal resources (water, milk, coffee)
- Accepts coin input and returns change when appropriate
- Clear error messages for insufficient funds or resources
- Minimal, well-structured code — easy to extend or test

## Quick Start

- Requirements: Python 3.8+
- Run the program:

```bash
python coffee_machine.py
```

The program will prompt you to choose a drink, insert coins, and will dispense the beverage if resources and payment are sufficient.

## Features

- Menu-driven drink selection (e.g. espresso, latte, cappuccino)
- Resource management preventing drinks when ingredients are low
- Coin parsing for common denominations (handles totals and change)
- Refunds and helpful prompts for invalid input

## Design Notes

This project is intentionally single-file and readable to make it easy to study or modify. The main responsibilities are split between:

- Input/Output (CLI prompts and responses)
- Resource accounting (tracking water, milk, and coffee)
- Transaction handling (coin totals, change, and refunds)

## Contributing

Contributions, issues, and feature requests are welcome. For small changes, open a pull request with a clear description and a brief test showing the change works.



---

