# Project-Arena--A-bridge-course-in-c-



# Virtual Pocket Pet & Arena

A simple console game written in C as part of our Bridge Course in C project.

You pick a pet, look after it, train it, and send it into the arena to fight other pets. While you play, the other pets quietly train on their own, so you have to keep up.

## Features

- Choose from 4 ready-made pets (Dragon, Robot, Ninja, Wolf), or create your own
- Care for your pet: feed it when it is hungry, play with it when it has energy
- Train your pet to raise its level
- Battle other pets in the arena (a little luck is involved)
- Find the strongest pet in the list

## C Concepts Used

| Topic | Where it is used |
|---|---|
| Functions, call by value and call by reference | `getScore`, `createPet` |
| Passing arrays to functions | `showPets`, `askMore` |
| Recursion | `trainingPower` |
| Pointers and pointer arithmetic | `pets + i` |
| Function returning a pointer | `strongestPet` |
| Dynamic memory (malloc, realloc, free) | pet list in `main` and `createPet` |
| Structure and typedef | `Pet` |
| Union | `Status` (hunger or energy) |
| Strings | pet names |

## How to Run

You can also paste the code into any online C compiler and run it.

## How to Play

1. Choose your pet (option 3).
2. Care for it and train it.
3. Fight in the arena and win to level up.
4. Use the menu number to pick each action.

Enter numbers only when the game asks for a number.