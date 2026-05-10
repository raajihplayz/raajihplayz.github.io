# Developer Portfolio — Raajih Ahmed

    > Modern, dark-aesthetic personal portfolio. Built with vanilla HTML, CSS & JavaScript — zero dependencies, single-file deploy.

    **Live:** [raajihplayz.github.io](https://raajihplayz.github.io)

    ---

    ## Overview

    A single-page portfolio designed to communicate technical skill and design sensibility at a glance. The site features an animated hero, scroll-reveal sections, a project grid, a skills overview, and four working in-page mini-apps (Notes, Tasks, Chat, Music) to demonstrate frontend craft directly.

    ## Features

    - Modern dark UI with gradient hero, glassmorphism cards, and animated background grid
    - Scroll-triggered reveal animations powered by `IntersectionObserver`
    - Fully responsive layout (mobile-first)
    - Four interactive in-page demos (no backend required)
    - SEO meta tags and theme color
    - Single-file deploy — no build step

    ## Tech Stack

    | Layer    | Tools |
    |----------|-------|
    | Markup   | HTML5, semantic structure, OG / SEO meta |
    | Styling  | Modern CSS, custom properties, glassmorphism |
    | Logic    | Vanilla JavaScript, `localStorage`, `IntersectionObserver` |
    | Hosting  | GitHub Pages |
    | Fonts    | Inter, JetBrains Mono |

    ## Run Locally

    ```bash
    git clone https://github.com/raajihplayz/raajihplayz.github.io.git
    cd raajihplayz.github.io
    python -m http.server 8000
    # open http://localhost:8000
    ```

    ## Project Structure

    ```
    .
    ├── index.html      Single-file portfolio (markup + styles + JS)
    ├── .nojekyll       Disable Jekyll processing on GitHub Pages
    └── README.md
    ```

    ## License

    MIT © Raajih Ahmed
    