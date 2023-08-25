# Project Title

## Deck of Cards in Go

## Description

This project provides a simple demonstration of a deck of playing cards using Go (Golang). You can perform various operations such as creating a new deck, shuffling the deck, saving the deck to a file, and loading the deck from a file.

## Files Overview

1. deck.go - Contains the main logic for the deck type and its associated functions/methods. This includes functionalities such as creating a new deck, printing a deck, dealing, shuffling, and saving/loading a deck from a file.
2. main.go - The entry point of the program. It uses the functionalities from deck.go to demonstrate their usage.
3. deck_test.go - Contains unit tests to ensure the functionalities in deck.go work as expected.

## Functions & Methods

1. newDeck(): Returns a new deck of cards.
2. print(): Prints the deck of cards.
3. deal(deck, handSize): Deals a hand of cards.
4. toString(): Converts the deck to a comma-separated string.
5. saveToFile(filename): Saves the deck to a file.
6. newDeckFromFile(filename): Loads the deck from a file.
7. shuffle(): Shuffles the deck of cards.

## Usage

To run the main program:

```bash
go run main.go deck.go
```

## Testing:

To run the unit tests:

```bash
go test
```
