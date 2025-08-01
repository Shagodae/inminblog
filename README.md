# InMinBlog Client

This is the client-side application for the InMinBlog project, built with React and Vite.

## Features
- Responsive navigation bar
- Blog pages and home page
- Modern UI with SVG and PNG assets
- Easy to customize and extend

## Project Structure
```
client/
  ├── public/           # Static assets
  ├── src/
  │   ├── assets/       # Images and icons
  │   ├── components/   # Reusable React components
  │   ├── pages/        # Page components (Blog, Home)
  │   ├── App.jsx       # Main app component
  │   ├── main.jsx      # Entry point
  │   └── index.css     # Global styles
  ├── index.html        # HTML template
  ├── package.json      # Project metadata and scripts
  ├── vite.config.js    # Vite configuration
  └── README.md         # Project documentation
```

## Getting Started

1. **Install dependencies**
   ```sh
   npm install
   ```
2. **Run the development server**
   ```sh
   npm run dev
   ```
3. **Build for production**
   ```sh
   npm run build
   ```

## Scripts
- `npm run dev` — Start development server
- `npm run build` — Build for production
- `npm run preview` — Preview production build

## Customization
- Add or update assets in `src/assets/`
- Modify components in `src/components/`
- Edit pages in `src/pages/`

## License
MIT
