
**Step 1:**

Download or clone this repo by using the link below:

```bash
git clone https://github.com/ladunjexa/reactjs18-3d-portfolio.git
```

**Step 2:**

Execute the following command in the root directory of the downloaded repo in order to install
dependencies:

```bash
npm install
```

**Step 3:**

Execute the following command in order to run the development server locally:

```bash
npm run dev
```

**Step 4:**

Open [http://localhost:5173](http://localhost:5173) with your browser to see the result.

### 📜 Scripts

All scripts are defined in the `package.json` file. Here is a list of all scripts:

| Script             | Action                                      |
| :----------------- | :------------------------------------------ |
| `npm install`      | Installs dependencies                       |
| `npm run dev`      | Starts local dev server at `localhost:5137` |
| `npm run build`    | Build your production site to `./dist/`     |
| `npm run preview`  | Boot up a local static web server           |
| `npm run lint`     | Run ESLint                                  |
| `npm run ts:check` | Perform type-checking                       |

## 🔒 Environment Variables

Environment variables[^3] can be used for configuration. They must be set before running the app.

> [Environment variables](https://en.wikipedia.org/wiki/Environment_variable) are variables that are
> set in the operating system or shell, typically used to configure programs.

**React.js 18 3D Portfolio** uses [EmailJS](https://www.emailjs.com/) as external service. You need
to create an account and get the required credentials to run the app.

Create a `.env` file in the root directory of the project and add the following environment
variables:

```env
VITE_EMAILJS_SERVICE_ID=<VITE_EMAILJS_SERVICE_ID>
VITE_EMAILJS_TEMPLATE_ID=<VITE_EMAILJS_TEMPLATE_ID>
VITE_EMAIL_JS_ACCESS_TOKEN=<VITE_EMAIL_JS_ACCESS_TOKEN>
```

## 🚀 Deployment

#### Deploy to production (manual)

You can create an optimized production build with the following command:

```bash
npm run build
```

#### Deploy on Vercel (recommended)

The easiest way to deploy this Next.js app is to use the
[Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fladunjexa%2Freactjs18-3d-portfolio)

#### Deploy on Netlify

You can also deploy this Next.js app with [Netlify](https://www.netlify.com/).

[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ladunjexa/reactjs18-3d-portfolio)

Check out [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## 🔧 Contributing

[![contributors](https://contrib.rocks/image?repo=ladunjexa/reactjs18-3d-portfolio)](https://github.com/ladunjexa/reactjs18-3d-portfolio/graphs/contributors)

Contributions are what make the open source community such an amazing place to learn, inspire, and
create. Any contributions you make are **greatly appreciated**.

To fix a bug or enhance an existing module, follow these steps:

1. Fork the repo
2. Create a new branch (`git checkout -b improve-feature`)
3. Make the appropriate changes in the files
4. Commit your changes (`git commit -am 'Improve feature'`)
5. Push to the branch (`git push origin improve-feature`)
6. Create a Pull Request 🎉

### 📩 Bug / Feature Request

If you find a bug (failure of a module to execute its intended function), kindly open an issue
[here](https://github.com/ladunjexa/reactjs18-3d-portfolio/issues/new) by including the issue with a
title and clear description.

If you'd like to request a new function, feel free to do so by opening an issue
[here](https://github.com/ladunjexa/reactjs18-3d-portfolio/issues/new). Please include sample
queries and their corresponding results.

## 💎 Acknowledgements

I'd like to express my gratitude to the following people who helped me with this project and made it
possible:

- [Tailwind CSS](https://tailwindcss.com/)
- [Three.js](https://threejs.org/)
- [Framer Motion](https://www.framer.com/motion/)
- [React Vertical Timeline Component](https://www.npmjs.com/package/react-vertical-timeline-component)
- [React Parallax Tilt](https://www.npmjs.com/package/react-parallax-tilt)
- [Maath](https://www.npmjs.com/package/maath)
- [EmailJS](https://www.emailjs.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Vercel](https://vercel.com/)
- [JavaScript Mastery](https://www.jsmastery.pro/)
