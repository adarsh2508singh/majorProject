# Blockchain-Based Certificate Validation System

Welcome to the Certificate Validation System, a blockchain-based solution for generating and verifying digital certificates. This system leverages the Ethereum blockchain, IPFS via Pinata, Firebase, and Streamlit to provide a secure, decentralized, and user-friendly platform for certificate management.

## Table of Contents
- [System Overview](#system-overview)
- [Key Features](#key-features)
- [Installation Guide](#installation-guide)
  - [Local Setup](#local-setup)
  - [Docker Setup](#docker-setup)
- [Screenshots](#screenshots)
- [License](#license)

## System Overview

The system is designed with two main entities in mind:

- **Institute**: The entity responsible for generating and issuing certificates. It has the ability to generate and view certificates.
- **Verifier**: The entity responsible for verifying certificates. It can verify certificates by either uploading a certificate pdf or by inputting the certificate id.

## Key Features

- **Smart Contract**: A Solidity smart contract is used to manage and store certificate details on the Ethereum blockchain.
- **IPFS Integration**: Certificate PDFs are stored on IPFS via Pinata for decentralized and secure file storage.
- **Firebase Authentication**: Firebase is used for authentication.
- **Streamlit App**: A user-friendly interface for generating and verifying certificates.

## Installation Guide

You can set up the project either locally or using Docker. Here are the steps for both:

### Local Setup

#### Prerequisites

- Node version >= 21.0.0 (Truffle requires node version 16 or higher)
- Python version >= 3.9.10
- Globally installed packages for Truffle and Ganache-cli
- Python packages (install from `application/requirements.txt`)
- Firebase project setup
- Pinata account setup
- .env file setup

#### Steps

1. Clone the repository.
2. Install the necessary packages.
3. Set up Firebase and Pinata.
4. Create and configure the .env file.
5. Start the Ganache blockchain.
6. Compile and deploy the smart contracts.
7. Launch the Streamlit app.

### Docker Setup

#### Prerequisites

- Docker

#### Steps

1. Start the Docker engine.
2. Run the Docker compose command to start the containers.
3. Access the app on your browser.
4. Stop and remove the containers when done.

## Screenshots

Here are some screenshots of the application:

- Home Page
- Login Page
- Generate Certificate Page
- View Certificate Page
- Verify Certificate using Certificate ID
- Verify Certificate using Certificate PDF