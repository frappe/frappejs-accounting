# FrappeJS + Accounting

## Getting Started

This guide is to help setup a development environment for building apps based on the FrappeJS framework, in this case, Accounting.

Both [FrappeJS](https://github.com/frappe/frappejs) and [Accounting](https://github.com/frappe/accounting) have their own individual git repositories, this is a parent repository set up to use Yarn Workspaces and Monorepo workflow which makes development a bit easier.

> You are not required to use this setup, this is just a hassle-free way we found for development.

### Installation

#### Step 1

Install [Node.js](https://nodejs.org/en/) LTS (version 8.11.1)

> Tip: The best way to install and manage Node is to install [nvm](https://github.com/creationix/nvm)

#### Step 2

Install `yarn` package manager.

```bash
npm install -g yarn
```

#### Step 3

Clone this repo

```bash
git clone --recurse-submodules https://github.com/frappe/frappejs-accounting
```

#### Step 4

Install dependencies and launch Accounting

```bash

cd frappejs-accounting

# Install dependencies
yarn

# Build static assets (js/css)
yarn build

# Run Electron
yarn electron

# Or

# Run Server
yarn server

```

On running `yarn electron`, Accounting will be launched within an Electron window.
On running `yarn server`, a Node server will start on http://localhost:8000

---

Frappe Technologies