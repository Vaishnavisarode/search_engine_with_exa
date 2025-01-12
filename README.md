# Search Engine using exa_py

This repository contains a Python-based search engine built using the `exa_py` library. The project demonstrates how to integrate and utilize `exa_py` for creating a robust search solution.

## Features

- **Simple Integration**: Leverages the `exa_py` library for seamless search functionalities.
- **Fast and Efficient**: Designed for performance and scalability.
- **Ease of Use**: Straightforward API to initialize and perform searches.

## Requirements

- Python 3.6 or higher
- `exa_py` library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/search-engine-exapy.git
   cd search-engine-exapy
   ```

2. Install the required dependencies:
   ```bash
   pip install exa_py
   ```

## Usage

1. Import the `exa_py` library and initialize the engine:
   ```python
   from exa_py import Exa
   
   exa = Exa('your-api-key')
   ```

2. Use the `Exa` object to perform search operations:
   ```python
   results = exa.search('query term')
   print(results)
   ```

3. Customize or extend the implementation as needed to suit your specific use case.

## Example

Here's a simple example of initializing and using the search engine:

```python
# Install exa_py first if not already installed
pip install exa_py

from exa_py import Exa

# Initialize the Exa engine with your API key
exa = Exa('your-api-key')

# Perform a search query
query = "Example search query"
results = exa.search(query)

# Display results
print("Search Results:", results)
```


