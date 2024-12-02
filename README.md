# Personal Website 🚀

Welcome to the repository for my **personal website**! This project is designed to showcase my portfolio, skills, and contact information in a clean and modern way. Built with cutting-edge technologies, this website reflects my passion for web development and attention to detail.

---

## 🌟 Features

- **Dynamic Portfolio:** Displays projects and skills with interactive elements.
- **Responsive Design:** Looks great on all devices, from desktops to smartphones.
- **Lightning-Fast Performance:** Leveraging modern frameworks for optimal speed.
- **Custom Theming:** Styled with Tailwind CSS for a unique and professional appearance.

---

## 🛠️ Tech Stack

This project is powered by:

| **Technology**     | **Purpose**                                            |
|---------------------|--------------------------------------------------------|
| [**Nx**](https://nx.dev)           | Monorepo management and optimized build tooling.     |
| [**Astro**](https://astro.build)   | Static site generation for blazing-fast performance. |
| [**React**](https://reactjs.org)   | Interactive components and dynamic behavior.        |
| [**Tailwind CSS**](https://tailwindcss.com) | Utility-first CSS framework for rapid styling.    |

---

## 📂 Project Structure

The workspace is organized into distinct applications for better modularity:

```
sandeep/
├── apps/
│   ├── astro-site/   # The Astro-powered website
│   ├── react-app/    # React-based components or additional features
├── libs/             # Shared libraries for UI and utilities
├── package.json      # Workspace dependencies
├── tailwind.config.js # Tailwind CSS configuration
└── nx.json           # Nx workspace configuration
```


## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/personal-website.git
cd personal-website
```

### 2. Install Dependencies
Ensure you have Node.js installed, then run:
```bash
npm install
```

### 3. Run the Development Server
Start the Astro site:
```bash
nx serve astro-site
```
Start the React app:
```bash
nx serve react-app
```
Visit the website at http://localhost:4200 (or the specified port).


## 🛠️ Development Notes
### Building the Project
**To generate a production build:**
``bash
nx build astro-site
nx build react-app
```

**Linting and Formatting**
**Run the linter:**
```bash
nx lint
```

**Format the code:**
```bash
nx format
```

**Testing**
You can add tests using the Nx testing capabilities:
```bash
nx test react-app
```

## 📜 License
This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgments
Thanks to the developers behind Nx, Astro, React, and Tailwind CSS for creating such powerful tools.  
Special shoutout to the open-source community for inspiration and resources.
