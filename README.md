# Web3 AI-Provider

## Idea

1. User buy subscriptions by LLM models. User not burn all tokens by subscription. User can sell these tokens.
2. User not possible buy subscription by dollar. User can buy tokens by cryptocurrency.

## Realisation

### Blockchain

Coming soon...

### Broker

1. Broker - is user give away self account or API-token from big LLM providers (OpenAI, Anthropic).
2. Broker can set cost for use self tokens.
3. Broker pay fee for provider.

### User

1. User can tokens by cryptocurrency.
2. User not pay any fees (exclude fee blockchain).
3. User forward pays directly to broker (user can see transaction in self crypto wallet) with crypto smart contract. 

### Provider

1. Host proxy for brokers and users.
2. Open Web3 interface for transactions.
3. Validate access to API LLM providers by credentials brokers and sign request.

### User has full anonymous

1. User not send self personal data to provider
2. User login with crypto wallet integration

## Stack

1. Backend - go
2. Frontend - ts\vue
3. BackendBroker - kafka
4. Container builder - docker
5. App orchestrator - k8s
6. Database - postgres
7. Proxy server - nginx
