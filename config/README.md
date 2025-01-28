# Config Directory

This directory contains configuration files for different environments (development, staging, and production) used in the AI Fantasy Battle Arena platform.

## Structure Overview

```
/config │── /dev # Development environment settings │
├── .env # Environment variables for local development │
├── config.json # Development-specific configuration 
│── /staging # Staging environment settings │
├── .env # Environment variables for testing environment │
├── config.json # Staging-specific configuration
│── /prod # Production environment settings │ 
├── .env # Environment variables for production │
├── config.json # Production-specific configuration 
│── README.md # Documentation for configuration files
```


## Key Components
1. **Environment Variables (`.env`):**  
   Store sensitive information such as API keys, database credentials, and secret tokens. These files are excluded from version control using `.gitignore`.

2. **Environment Configurations (`config.json`):**  
   Define settings for each environment, including server URLs, blockchain network IDs, and other runtime parameters.

## Usage
1. Set up the appropriate environment configuration file (`.env`) based on the deployment environment.
2. Reference the configuration in your application code using a library like `dotenv` for Node.js or `os.environ` for Python.
3. Ensure sensitive information is never hardcoded in the source code.

## Contribution Guidelines
- Never commit `.env` files to version control.
- Document all configuration parameters in this file.
- Keep configurations modular and environment-specific.
