# Hello Koinos World

A simple web application that demonstrates how to interact with the Koinos blockchain by displaying a token balance.

## Overview

This project showcases a basic implementation of connecting to the Koinos blockchain API to fetch and display the KOIN token balance for an account.

## Features

- Retrieves the KOIN token balance for the "@helloworld" account
- Simple, clean user interface
- Demonstrates basic Koinos API integration

## Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript

### Running the Application

1. Clone the repository:
   ```
   git clone https://github.com/Open-Koinos/hello-world.git
   ```

2. Open `index.html` in your web browser.

3. The application will automatically fetch and display the KOIN balance for the "@helloworld" account.

## How It Works

The application uses Axios to make an API call to the Koinos blockchain REST API endpoint:

```javascript
const tokenContract = '15DJN4a8SgrbGhhGksSBASiSYjGnMU8dGL' // Koin contract address
const account = '@helloworld' // Nickname (unique human readable identifier)
const apiUrl = `https://api.koinos.io/v1/token/${tokenContract}/balance/${account}`
```

When the page loads, it fetches the balance and displays it on the page.

## Customization

To check the balance of a different account or token:

1. Modify the `tokenContract` variable to the address of the token you want to check
2. Change the `account` variable to the address or nickname of the account you want to check

## Resources

- [Koinos Blockchain](https://koinos.io/)
- [Official Documentation](https://docs.koinos.io/)
- [GitHub Repository](https://github.com/Open-Koinos/hello-world/)

---

Created with ❤️ for the Koinos community
