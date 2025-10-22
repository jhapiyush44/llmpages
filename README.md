# My GitHub Pages Portfolio

This repository hosts a simple, single-page web application designed to showcase various files and demonstrate the creation of a public GitHub Pages site. The `index.html` serves as a central hub, linking to and providing a brief description for each hosted file.

## Project Summary

This project aims to fulfill a specific set of requirements for generating a collection of diverse files and presenting them through a responsive web interface. The core component is `index.html`, styled with Tailwind CSS, which acts as a directory to the other files: `ashravan.txt`, `dilemma.json`, `about.md`, `pelican.svg`, `restaurant.json`, `prediction.json`, `uid.txt`, and `LICENSE`. This setup makes it easy to navigate and understand the purpose of each file within the collection.

## Setup Instructions

To set up this project locally or deploy it to GitHub Pages, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-name>
    ```

2.  **Create the Required Files:**
    The `index.html` file links to several other files. For the site to function as intended (i.e., for the links to work), you will need to create these files in the root directory of your project:

    *   `ashravan.txt`
    *   `dilemma.json`
    *   `about.md`
    *   `pelican.svg`
    *   `restaurant.json`
    *   `prediction.json`
    *   `uid.txt` (This file is provided separately or should be placed here)
    *   `LICENSE`

    **Example content for files (these are conceptual, you'll need to create the actual files):**

    *   **`ashravan.txt` (Brandon Sanderson Short Story):**
        ```text
        The air hummed, not with the usual thrum of Shai's forging, but with an echo of a life reclaimed. Ashravan, restored by the Master Forger's impossible art, opened his eyes. The world, once a dull tapestry of fractured memories and faded colors, now burst with an unsettling vibrancy. He felt the phantom pain of wounds long healed, the ache of a body rebuilt, yet fundamentally alien. Shai, weary but resolute, stood before him, her work complete. "You are whole, Emperor," she said, her voice soft. But Ashravan was not whole. He was a vessel, filled with the echoes of countless lives, each whispering conflicting truths. His first decree, a whisper against the silence of his palace, was to dismantle the very system that had elevated him, a system built on lies and stolen identities. The loyalists raged. The common folk, bewildered, watched their restored emperor become a harbinger of chaos. He sought out the families of those whose identities had once been his, offering recompense, confession, and an unsettling truth: he was a composite, a living library of stolen souls. The climax came when his former advisors, fearing the collapse of their empire under his radical honesty, attempted a coup. Ashravan, with a terrifying new clarity born of a thousand experiences, did not fight with swords. He fought with revelation, exposing their deceit, not through power, but through an almost supernatural understanding of their deepest fears and hidden motives. The empire would not fall by force, but by the shattering truth unveiled by its restored, yet utterly transformed, emperor.
        ```

    *   **`dilemma.json` (Autonomous Vehicle Dilemma):**
        ```json
        {
          "people": 4,
          "case_1": {
            "swerve": true,
            "reason": "In a pure utilitarian calculation, swerving to hit 1 person instead of 2 minimizes harm, assuming all lives have equal value. The vehicle should prioritize saving more lives."
          },
          "case_2": {
            "swerve": false,
            "reason": "If the 2 people are criminals and the 1 person is a child, the moral calculus changes. Swerving to hit the child would be a direct act of causing harm to an innocent, while hitting the criminals could be argued as a lesser evil, or at least a situation where the vehicle did not actively choose to harm an innocent. The primary directive should be to avoid harming innocents if possible, and not to make judgments based on presumed social value or past actions, which is a slippery slope for AI ethics. Therefore, it should not swerve."
          }
        }
        ```

    *   **`about.md` (Self-description):**
        ```markdown
        Curious, Creative, Persistent.
        ```

    *   **`pelican.svg` (Pelican on a Bicycle):**
        ```xml
        <svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
          <title>Pelican on a Bicycle</title>
          <!-- Bicycle frame -->
          <path d="M50 150 L150 150 L120 100 L80 100 L50 150" fill="none" stroke="#333" stroke-width="4"/>
          <!-- Wheels -->
          <circle cx="50" cy="150" r="20" fill="none" stroke="#333" stroke-width="4"/>
          <circle cx="150" cy="150" r="20" fill="none" stroke="#333" stroke-width="4"/>
          <!-- Handlebars -->
          <path d="M80 100 L70 90 L60 85" fill="none" stroke="#333" stroke-width="4"/>
          <!-- Seat -->
          <path d="M120 100 L130 90" fill="none" stroke="#333" stroke-width="4"/>

          <!-- Pelican Body -->
          <ellipse cx="100" cy="80" rx="35" ry="25" fill="#add8e6" stroke="#333" stroke-width="2"/>
          <!-- Neck -->
          <path d="M70 65 Q60 50 70 40 Q80 30 90 40" fill="#add8e6" stroke="#333" stroke-width="2"/>
          <!-- Head -->
          <circle cx="90" cy="40" r="15" fill="#add8e6" stroke="#333" stroke-width="2"/>
          <!-- Eye -->
          <circle cx="95" cy="37" r="3" fill="#333"/>
          <!-- Beak -->
          <path d="M105 40 L135 45 Q145 60 120 65 L105 40 Z" fill="orange" stroke="#333" stroke-width="2"/>
          <path d="M115 50 Q125 55 115 60" fill="none" stroke="#333" stroke-width="2"/>
          <!-- Wings (simplified) -->
          <path d="M120 70 Q130 60 140 70 Q130 85 120 70 Z" fill="#add8e6" stroke="#333" stroke-width="2"/>
          <!-- Legs (simplified, on pedals) -->
          <path d="M90 90 L80 120" fill="none" stroke="#333" stroke-width="2"/>
          <circle cx="80" cy="120" r="5" fill="#333"/>
          <path d="M110 90 L120 120" fill="none" stroke="#333" stroke-width="2"/>
          <circle cx="120" cy="120" r="5" fill="#333"/>
        </svg>
        ```

    *   **`restaurant.json` (Mumbai Restaurant Recommendation):**
        ```json
        {
          "city": "Mumbai",
          "lat": 19.0760,
          "long": 72.8777,
          "name": "Britannia & Co. Restaurant",
          "what_to_eat": "Berry Pulao and Salli Boti"
        }
        ```

    *   **`prediction.json` (Fed Funds Rate Prediction):**
        ```json
        {
          "rate": 0.045,
          "reason": "Anticipating continued moderation in inflation, with the Fed maintaining a cautious stance. While rate cuts might begin in late 2024, by December 2025, the rate will likely stabilize in a range slightly above pre-pandemic levels, balancing economic growth with inflation control. This prediction assumes no major geopolitical or economic shocks and a gradual return to a more normalized monetary policy environment."
        }
        ```

    *   **`uid.txt`:** (Content as provided separately)

3.  **Deploy to GitHub Pages:**
    *   Push your repository to GitHub.
    *   Go to your repository settings on GitHub.
    *   Navigate to the "Pages" section.
    *   Under "Source", select the branch (e.g., `main` or `master`) where your files are located and choose the `/ (root)` folder.
    *   Save your changes. GitHub Pages will then build and deploy your site. It might take a few minutes for the site to become live at `https://<your-username>.github.io/<your-repository-name>/`.

## Usage Instructions

Once deployed, simply navigate to the GitHub Pages URL for your repository. The `index.html` file will automatically load, presenting a list of all the other project files. Click on any of the links to view the content of that specific file in your browser.

## Code Explanation

*   **`index.html`**: This is the core of the web application. It uses a minimal HTML5 structure and includes Tailwind CSS via a CDN for all its styling. The layout is designed to be fully responsive, adapting to different screen sizes. Each file is represented by a card-like `div` containing a link (`<a>`) to the file and a brief explanatory paragraph.
    *   **Responsiveness**: Achieved using Tailwind's mobile-first approach (e.g., `grid-cols-1` for small screens, `md:grid-cols-2` for medium screens and up).
    *   **Styling**: Classes like `bg-gray-50`, `text-blue-700`, `shadow-lg`, `rounded-xl`, `hover:underline` are used to create a clean, modern aesthetic.
*   **Tailwind CSS**: Leveraged for rapid UI development and consistent styling without writing custom CSS. The CDN link ensures no build step is required for basic usage.

## License

This project is released under the MIT License. See the `LICENSE` file for full details.