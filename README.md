# Payment Gateway UI

A responsive checkout page UI where a customer reviews their order, selects a payment method, and proceeds to pay.

## Features

- Merchant header with order details
- Order summary section
- Selectable payment methods (cards, UPI, net banking, etc.)
- Proceed button with selected-option handling
- Clean, reusable component structure

## Tech Stack

- React
- TypeScript
- Vite
- CSS

## Project Structure

```
src/
├── components/
│   ├── MerchantHeader.tsx
│   ├── OrderSummary.tsx
│   ├── PaymentMethods.tsx
│   ├── PaymentOption.tsx
│   ├── PoweredBy.tsx
│   ├── ProceedButton.tsx
│   └── icons.tsx
├── data.ts
├── App.tsx
├── main.tsx
└── index.css
```

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/vaishnavimahawar/payment-gateway-ui-Swift.git
   cd payment-gateway-ui-Swift
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Start the dev server
   ```bash
   npm run dev
   ```
4. Open the URL shown in the terminal (usually http://localhost:5173)

## Build for Production

```bash
npm run build
```

## Author

Vaishnavi Mahawar
