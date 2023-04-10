npm create vite@latest 
## Install dependencies for Three.js, React Three Fiber, Drei, Maath, React Color, and Framer Motion
npm install @react-three/fiber @react-three/drei maath react-color framer-motion
## Install tailwindcss and postcss
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
## Configure your template paths
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
## Add the Tailwind directives to your CSS file
@tailwind base;
@tailwind components;
@tailwind utilities;
