# Paradise Nursery – e-PlantShopping

A modern, user-friendly web application for browsing, selecting, and purchasing a variety of plants online. Built with React and Redux, Paradise Nursery offers a seamless shopping experience with categorized plant listings, a dynamic cart, and a clean, responsive design.

## Features

- **Browse Plants by Category**: Air Purifying, Aromatic, Insect Repellent, Medicinal, and Low Maintenance plants.
- **Add to Cart**: Easily add plants to your cart and see real-time updates.
- **Cart Management**: View, update, and continue shopping from your cart.
- **Detailed Plant Info**: Each plant card displays an image, description, and price.
- **Fast & Responsive**: Built with React, Redux, and modern CSS for a smooth user experience.

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- pnpm (or npm/yarn)

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd e-plantShopping
   ```
2. Install dependencies:
   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```
3. Start the development server:
   ```bash
   pnpm dev
   # or
   npm run dev
   # or
   yarn dev
   ```
4. Open your browser and visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Project Structure

```
e-plantShopping/
├── public/           # Static assets
├── src/              # Source code
│   ├── App.jsx       # Main app component
│   ├── ProductList.jsx  # Plant listing UI
│   ├── CartItem.jsx  # Cart UI
│   ├── CartSlice.jsx # Redux slice for cart
│   └── ...           # Other components and styles
├── package.json      # Project metadata and scripts
├── vite.config.js    # Vite configuration
└── README.md         # Project documentation
```

## Scripts

- `pnpm dev` / `npm run dev` – Start development server
- `pnpm build` / `npm run build` – Build for production
- `pnpm preview` / `npm run preview` – Preview production build

## Dependencies

- [React](https://react.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Redux](https://react-redux.js.org/)
- [Vite](https://vitejs.dev/)

## Customization

- Add or edit plant categories and data in `ProductList.jsx`.
- Update styles in the `src/` CSS files.

## License

This project is licensed under the MIT License.

---

Enjoy your journey to a greener, healthier home with Paradise Nursery!
