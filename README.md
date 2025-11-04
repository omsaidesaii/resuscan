#  Resuscan -- Smart Resume Analyzer & Application Tracker

Resuscan is an intelligent web platform that helps users **upload,
manage, and analyze resumes** with **AI-powered feedback**.\
It streamlines the job application process by tracking submissions,
providing resume ratings, and offering actionable career insights.

Built with **React, TypeScript, TailwindCSS, Zustand**, and **KV Storage
API**, Resuscan ensures a modern, responsive, and efficient experience.

------------------------------------------------------------------------

## 🚀 FEATURES

-   🔐 **Authentication & Security** -- Redirects and secure login
    handling
-   📂 **Resume Upload & Management** -- Store and manage multiple
    resume versions
-   🤖 **AI Feedback System** -- Get instant feedback on strengths,
    weaknesses, and ATS optimization
-   📊 **Application Tracker** -- Monitor which jobs you've applied to
    and track status
-   🎨 **Modern UI/UX** -- Responsive, mobile-first design with
    TailwindCSS
-   ⚡ **Real-Time Resume Loading** -- Smooth loaders and animated UI
    for feedback
-   📈 **Dashboard Analytics** -- Insights on job applications, ratings,
    and performance trends

------------------------------------------------------------------------

## 🛠️ TECHNOLOGIES USED

-   **Frontend**: React (with TypeScript)
-   **Styling**: TailwindCSS
-   **Routing**: React Router
-   **State Management**: Zustand (via `usePuterStore`)
-   **Storage**: KV Storage API
-   **UI Components**: Custom Navbar, ResumeCard
-   **Build Tool**: Vite

------------------------------------------------------------------------

## 📂 PROJECT STRUCTURE

``` bash
resuscan/
│── public/                # Static assets (images, favicon, loaders)
│   ├── images/
│   │   ├── bg-main.svg
│   │   ├── resume-scan-2.gif
│   └── ...
│
│── src/
│   ├── components/        # Reusable UI components
│   │   ├── Navbar.tsx
│   │   ├── ResumeCard.tsx
│   │   └── ...
│   │
│   ├── lib/               # Custom hooks & utilities
│   │   ├── puter.ts       # usePuterStore (auth & KV storage)
│   │
│   ├── routes/            # Application routes
│   │   ├── home.tsx       # Home page logic
│   │   └── auth.tsx       # Authentication flow
│   │
│   ├── types/             # TypeScript interfaces & types
│   │   ├── resume.d.ts
│   │   └── kv.d.ts
│   │
│   ├── App.tsx            # Root app component
│   ├── main.tsx           # Entry point
│   └── index.css          # Tailwind & global styles
│
│── package.json
│── vite.config.ts
└── README.md
```

------------------------------------------------------------------------

## 🔧 INSTALLATION & USAGE

1.  **Clone the Repository**

    ``` bash
    git clone https://github.com/yourusername/resuscan.git
    cd resuscan
    ```

2.  **Install Dependencies**

    ``` bash
    npm install
    ```

3.  **Run Development Server**

    ``` bash
    npm run dev
    ```

4.  **Visit in Browser**

        http://localhost:5173

------------------------------------------------------------------------

## ⚙️ CUSTOMIZATION

-   **Branding**: Update `/components/Navbar.tsx` with your own logo &
    brand colors.
-   **Authentication**: Configure `/lib/puter.ts` for your KV storage &
    auth provider.
-   **Assets**: Replace `/public/images` with your own background,
    icons, and loader GIFs.
-   **Theme**: Modify `tailwind.config.js` for custom color palettes and
    typography.

------------------------------------------------------------------------

## 🤝 CONTRIBUTING

We welcome contributions! To contribute:

1.  Fork this repository.

2.  Create a new feature branch:

    ``` bash
    git checkout -b feature-name
    ```

3.  Commit your changes:

    ``` bash
    git commit -m "Added new feature"
    ```

4.  Push to your fork and submit a pull request.

------------------------------------------------------------------------

## 📌 LIVE DEMO

👉 <https://resuscan.vercel.app/> 

------------------------------------------------------------------------

## 📜 LICENSE

This project is licensed under the **MIT License** -- you're free to
use, modify, and distribute with attribution.

------------------------------------------------------------------------

## 👨‍💻 AUTHOR

**Omsai Kushkumar Desai**\
📧 Email: <omsaidesai9@gmail.com>\
🔗 LinkedIn:
[linkedin.com/in/omsai-desai-a924a6300](https://www.linkedin.com/in/omsai-desai-a924a6300/)\
💻 GitHub: [github.com/omsaidesaii](https://github.com/omsaidesaii)

------------------------------------------------------------------------
