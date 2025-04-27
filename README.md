# WSAA-coursework


[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Coursework](https://img.shields.io/badge/Status-In%20Progress-brightgreen.svg)]()

***

Analysing data retrieval from external sources (CSO, weather, stocks) in XML, JSON, and CSV formats via APIs, 
using JavaScript and Python.

This repository contains coursework completed for the Web Services and Applications (WSAA) module.

The coursework demonstrates interaction with public APIs, retrieval and storage of open data, and basic automation 
using Python and GitHub.

***

## 📁 Repository Structure

```bash
WSAA-coursework/
├── assignments/
│   ├── assignment02-carddraw.ipynb     # Simulates drawing cards from a shuffled deck
│   ├── assignment03-cso.ipynb          # Downloads JSON dataset from CSO
│   └── assignment04-github.ipynb       # Replaces text in a file and pushes to GitHub
└── README.md
```


## ⚙️ Requirements

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [requests library](https://pypi.org/project/requests/)
- [Git](https://git-scm.com/)
- [GitHub authentication (Personal Access Tokens)](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

---

## 🚀 How to Run the Notebooks

Each notebook is self-contained. To run a notebook:

1. Open the notebook using [Jupyter Notebook](https://jupyter.org/) or [VS Code](https://code.visualstudio.com/).
2. Run all cells from top to bottom.
3. Ensure you are connected to the internet for API calls.
4. For Assignment 04, ensure GitHub authentication is set up to allow push access.

---

## 📚 Assignment Summaries

- **Assignment 02 – Card Draw**  
  Shuffles a deck of cards using the [Deck of Cards API](https://deckofcardsapi.com/).  
  Draws 5 cards and checks for pairs, triples, straights, or same suits.

- **Assignment 03 – CSO Data Retrieval**  
  Retrieves the "Exchequer Account (Historical Series)" dataset from the [Central Statistics Office (CSO)](https://www.cso.ie/).  
  Saves the dataset in JSON format without reformatting.

- **Assignment 04 – GitHub File Update**  
  Edits a file by replacing all instances of "Andrew" with "Hugo."  
  Commits and pushes the changes back to GitHub automatically.

---

## 📖 References

- [Deck of Cards API](https://deckofcardsapi.com/)
- [Central Statistics Office (CSO)](https://www.cso.ie/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Personal Access Tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

---

## 👤 Author

**Hugo Camach Romero**

