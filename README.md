## 📥 Fizzi Drink

A modern, refreshing beverage website built with **Next.js 14**, **React 18**, and **Tailwind CSS**. This project showcases a vibrant drink brand with smooth animations, 3D elements, and headless CMS integration.

---

## 🌍 Live Demo

🔗 [https://fizzi-demo.vercel.app/](https://fizzi-demo.vercel.app/)

---

## 🚀 Features

- **Next.js 14 (App Router)** for optimized routing and server rendering
- **React 18** with modern hooks and patterns
- **Tailwind CSS** for utility-first styling
- **GSAP Animations** for smooth transitions and interactions
- **3D Elements** with React Three Fiber and Drei
- **Headless CMS** integration with Prismic
- **TypeScript** for type safety and better development experience
- **Responsive Design** optimized for all devices
- **SEO-friendly** with Next.js best practices
- **Deployed on Vercel** for global performance

---

## 📂 Project Structure

```
📦 fizzi
┣ 📂 src
┃ ┣ 📂 app
┃ ┃ ┣ 📜 layout.tsx # Root layout file
┃ ┃ ┣ 📜 page.tsx # Homepage entry
┃ ┃ ┣ 📜 globals.css # Global styles
┃ ┃ ┗ 📂 [other pages] # Additional pages
┃
┃ ┣ 📂 components
┃ ┃ ┣ 📂 ui # Reusable UI components
┃ ┃ ┣ 📂 sections # Page sections
┃ ┃ ┣ 📂 three # 3D components
┃ ┃ ┗ 📂 slices # Prismic slice components
┃
┃ ┣ 📂 lib
┃ ┃ ┣ 📜 prismic.ts # Prismic client configuration
┃ ┃ ┣ 📜 utils.ts # Utility functions
┃ ┃ ┗ 📜 constants.ts # App constants
┃
┃ ┣ 📂 hooks # Custom React hooks
┃ ┣ 📂 types # TypeScript type definitions
┃ ┣ 📂 styles # Additional styling
┃ ┗ 📂 sass # SASS modules (if applicable)
┃
┣ 📂 public
┃ ┣ 📂 images # Static images
┃ ┣ 📂 models # 3D model assets
┃ ┗ favicon.ico
┃
┣ 📂 slices # Prismic slices
┣ 📜 package.json
┣ 📜 tailwind.config.ts # Tailwind CSS configuration
┣ 📜 tsconfig.json # TypeScript configuration
┣ 📜 slicemachine.config.json # Slice Machine configuration
┣ 📜 README.md
┗ 📜 .gitignore
```

> 🔑 Each component is modular with proper TypeScript typing and Tailwind CSS styling

---

## 🛠 Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/)
- **Library:** [React 18](https://reactjs.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animations:** [GSAP](https://gsap.com/) + [@gsap/react](https://www.npmjs.com/package/@gsap/react)
- **3D Graphics:** [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) + [Drei](https://github.com/pmndrs/drei)
- **CMS:** [Prismic](https://prismic.io/) with [Slice Machine](https://www.slicemachine.dev/)
- **State Management:** [Zustand](https://github.com/pmndrs/zustand)
- **Icons:** [React Icons](https://react-icons.github.io/react-icons/)
- **Deployment:** [Vercel](https://vercel.com/)

---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/fizzi.git
   cd fizzi
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a \`.env.local\` file with the following variables:

   ```
   PRISMIC_ACCESS_TOKEN=your_prismic_access_token
   PRISMIC_REPOSITORY_NAME=your_repository_name
   ```

4. **Run development server:**

   ```bash
   npm run dev
   ```

   Project will be available at: [http://localhost:3000](http://localhost:3000)

5. **Start Slice Machine (for content editing):**

   ```bash
   npm run slicemachine
   ```

6. **Build for production:**

   ```bash
   npm run build
   npm start
   ```

---

## 📦 Dependencies

From \`package.json\`:

```json
{
  "dependencies": {
    "@gsap/react": "^2.1.1",
    "@prismicio/client": "^7.11.0",
    "@prismicio/next": "^1.6.0",
    "@prismicio/react": "^2.8.0",
    "@react-three/drei": "^9.111.3",
    "@react-three/fiber": "^8.17.6",
    "@types/three": "^0.167.2",
    "clsx": "^2.1.1",
    "gsap": "^3.12.5",
    "next": "^14.2.4",
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "three": "^0.167.1",
    "zustand": "^4.5.5"
  },
  "devDependencies": {
    "@slicemachine/adapter-next": "^0.3.46",
    "@types/node": "^20.14.2",
    "@types/react": "^18.3.3",
    "@types/react-dom": "^18.3.0",
    "autoprefixer": "^10.4.20",
    "concurrently": "^8.2.2",
    "eslint": "^8.57.0",
    "eslint-config-next": "^14.2.4",
    "postcss": "^8.4.41",
    "prettier": "^3.3.3",
    "prettier-plugin-tailwindcss": "^0.6.6",
    "r3f-perf": "^7.2.1",
    "slice-machine-ui": "^2.5.0",
    "tailwindcss": "^3.4.10",
    "typescript": "^5.4.5"
  }
}
```

---

## 🎨 Design Features

- **Vibrant Color Scheme** tailored for beverage brand identity
- **Smooth Animations** for engaging user experience
- **3D Product Visualizations** for immersive content
- **Mobile-First Responsive Design** for all screen sizes
- **Modern Typography** with carefully selected fonts
- **Interactive Elements** with hover effects and transitions

---

## ✨ Author

**Fahad Ali**  
Frontend Developer | Pakistan  
📧 [fa6084904@gmail.com](mailto:fa6084904@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/fahad-ali-759700369/)

---

## 📌 Notes

- This project follows **modern development practices** with TypeScript and Tailwind CSS
- **Prismic CMS** allows non-technical users to manage content easily
- **3D elements** are optimized for performance with React Three Fiber
