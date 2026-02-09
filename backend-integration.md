# Backend Integration Guide

## Authentication APIs
- POST /api/login
- POST /api/signup
- POST /api/verify-otp

Connected JS: auth.js

## Wallet APIs
- GET /api/wallet/balance
- POST /api/wallet/add
- POST /api/wallet/withdraw

Connected JS: wallet.js

## Transactions
- GET /api/transactions

## Matches
- GET /api/matches
- GET /api/match/{id}

## Sample Wallet Response
{
  "balance": 1250.50
}