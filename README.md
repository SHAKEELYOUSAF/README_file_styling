<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=170&text=Styling%20Guide%20Of%20README%20file&fontSize=50&descAlign=37&animation=twinkling&fontColor=ffffff&fontAlign=50&section=header" />
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:BCCCAF,100:8CA084&height=90&section=header&text=Adding%20an%20Animated%20Header%20Banner&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

You can add a stylish animated banner to the top of your README using **[Capsule Render](https://capsule-render.vercel.app/)** — no design tool needed.

**Steps:**

1. Open this link in your browser:  
   `https://capsule-render.vercel.app/api?type=waving&height=300&text=Project%20Title`

2. Replace `Project%20Title` in the URL with your own project name (use `%20` for spaces).  
   Example: `text=TailorPro`

3. Once you like the preview, copy the full URL.

4. Paste it into your `README.md` using this HTML snippet, replacing the `src` value with your copied link:

```html
   <p align="center">
     <img src="PASTE_YOUR_LINK_HERE" />
   </p>
```

Save, commit, and push — your animated header banner will now show up live on GitHub.

**Demo:**

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=bcd9a5&text=Project%20Title&fontSize=60&descAlign=37&animation=twinkling&fontColor=ffffff&fontAlign=50&section=header" />
 <p align="center"> ALL your content of Readme between these Ok.</p>
</p>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=bcd9a5&fontSize=60&descAlign=37&animation=twinkling&fontColor=ffffff&fontAlign=50&section=footer" />
</p>
**Workflow:**

```mermaid
flowchart LR
    A[Open Capsule Render Link] --> B[Add Project Name]
    B --> C[Copy Final URL]
    C --> D[Paste HTML in README]
    D --> E[Commit and Push]
    E --> F[Banner Live!]
classDef screen fill:#8a9b68,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#d5ddbc,color:#2b2620,stroke:#6f7d4a,stroke-width:2px;
class A,C,D,F screen;
class B,E action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9C9D9,100:6F9CB3&height=90&section=header&text=Adding%20Tech%20Stack%20Badges&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

You can showcase your project's technologies using **[Shields.io](https://shields.io/)** — clean, colorful badges for every tool in your stack.

**Steps:**

1. List out every major tool, language, and framework used in your project (e.g. React, Node.js, MongoDB).

2. Generate a badge URL for each technology using this format:  
   `https://img.shields.io/badge/{TEXT}-{HEX_COLOR}?style=for-the-badge&logo={LOGO_NAME}&logoColor={LOGO_COLOR}`  
   Example: `text=React`, `logo=react`

3. Find official logo names at **[Simple Icons](https://simpleicons.org/)** — search your tech and copy its slug.

4. Paste each badge into your `README.md` using this HTML snippet, adding one `<img>` line per technology:

```html
   <p align="center">
     <img src="PASTE_YOUR_BADGE_LINK_HERE" />
   </p>
```

Save, commit, and push — your badges will now show up live on GitHub.

**Demo:**

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
</p>

**Workflow:**

```mermaid
flowchart LR
    A[List technologies used] --> B[Generate badge URL]
    B --> C[Find logo name on Simple Icons]
    C --> D[Paste HTML in README]
    D --> E[Commit and Push]
    E --> F[Badges live!]
classDef screen fill:#4a7d94,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bcdbe8,color:#2b2620,stroke:#4a7d94,stroke-width:2px;
class A,C,D,F screen;
class B,E action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:D9B9A9,100:B37F6F&height=90&section=header&text=Add%20Workflow&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

You can add a visual, horizontal workflow diagram using **[Mermaid](https://mermaid.js.org/)** — GitHub renders it automatically, no image or external tool needed.

**Steps:**

1. Open your `README.md` file and decide where the workflow should appear.

2. Add a code block starting with ` ```mermaid ` and define your flow using `flowchart LR` (left-to-right).

3. List each step as a labeled box, connecting them with arrows (`-->`).

4. Save, commit, and push — GitHub will render it as a live diagram.

**Demo:**

```mermaid
flowchart LR
    A[Open README file] --> B[Add mermaid code block]
    B --> C[Define steps with arrows]
    D[Commit and Push] --> E[Workflow live!]
    C --> D
classDef screen fill:#946f4a,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#e8d2bc,color:#2b2620,stroke:#946f4a,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:C9A9D9,100:9C6FB3&height=90&section=header&text=Architecture%20at%20a%20Glance&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

You can visualize your project's structure using **[Mermaid](https://mermaid.js.org/)** — showing how different parts (frontend, backend, database) connect, directly inside your README.

**Steps:**

1. Identify the main components of your project (e.g. Client, Server, Database, APIs).

2. Open your `README.md` and add a code block starting with ` ```mermaid `.

3. Use `flowchart TD` (top-down) to show layers, connecting each component with arrows to show data/request flow.

4. Save, commit, and push — GitHub will render it as a live architecture diagram.

**Demo:**

```mermaid
flowchart TD
    A[Client / Frontend] --> B[Server / Backend API]
    B --> C[(Database)]
    B --> D[Third-Party Services]
classDef screen fill:#7d4a94,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#dbbce8,color:#2b2620,stroke:#7d4a94,stroke-width:2px;
class A,C screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9D9C4,100:6FB39A&height=90&section=header&text=Project%20Structure&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

A clean, well-organized folder structure makes your project easy to navigate for anyone who opens the repo — including future you.

**Steps:**

1. Decide your top-level folders (e.g. `client`, `server`, `docs`, `config`).

2. Inside your `README.md`, add a fenced code block using triple backticks and no language tag, so indentation stays intact.

3. Use tree-style symbols (`├──`, `└──`, `│`) to represent nesting — you can type these manually or copy them from an existing tree.

4. Save, commit, and push — GitHub will display it as a clean, monospaced folder tree.

**Demo:**

```
project-root/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── config/
│   └── db.js
├── .env
├── .gitignore
└── README.md
```

**Workflow:**

```mermaid
flowchart LR
    A[Decide top-level folders] --> B[Open README code block]
    B --> C[Draw tree with symbols]
    D[Commit and Push] --> E[Structure live!]
    C --> D
classDef screen fill:#4a946f,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bce8d2,color:#2b2620,stroke:#4a946f,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>


<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9D9BC,100:6FB38F&height=90&section=header&text=Color%20Reference&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

If your project has a design system, listing your color palette helps contributors stay visually consistent.

**Steps:**

1. Identify your main color palette (primary, secondary, background, text colors).

2. Create a Markdown table with color name, hex code, and a visual swatch.

3. Use a small colored square image or emoji block for the swatch column.

4. Save, commit, and push.

**Demo:**

| Color | Hex |
|-------|-----|
| ![#BCCCAF](https://placehold.co/15x15/BCCCAF/BCCCAF.png) Primary | `#BCCCAF` |
| ![#8CA084](https://placehold.co/15x15/8CA084/8CA084.png) Secondary | `#8CA084` |
| ![#2B2620](https://placehold.co/15x15/2B2620/2B2620.png) Text | `#2B2620` |

**Workflow:**

```mermaid
flowchart LR
    A[Identify color palette] --> B[Build Markdown table]
    B --> C[Add color swatches]
    C --> D[Commit and Push]
    D --> E[Color reference live!]
classDef screen fill:#4a9470,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bce8d2,color:#2b2620,stroke:#4a9470,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9C4D9,100:6F9AB3&height=90&section=header&text=API%20Reference&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Document your API endpoints clearly so other developers know how to interact with your backend.

**Steps:**

1. List each endpoint with its HTTP method (GET, POST, PUT, DELETE).

2. For each endpoint, specify the request format (params, body) and response format.

3. Use a Markdown table or code blocks to keep it organized and scannable.

4. Save, commit, and push — your API docs will render cleanly on GitHub.

**Demo:**

```
GET /api/users
```
Returns a list of all users.

**Response:**

```json
{
  "id": "123",
  "name": "John Doe",
  "email": "john@example.com"
}
```

**Workflow:**

```mermaid
flowchart LR
    A[List all endpoints] --> B[Document method and params]
    B --> C[Add example response]
    C --> D[Commit and Push]
    D --> E[API docs live!]
classDef screen fill:#4a7d94,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bcdbe8,color:#2b2620,stroke:#4a7d94,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9C4A9,100:6F9A6F&height=90&section=header&text=Run%20Locally&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Give clear, copy-paste-ready steps so anyone can clone and run your project on their own machine.

**Steps:**

1. Add the clone command with your repo URL.

2. List commands to install dependencies for both client and server (if applicable).

3. Include the command to start the development server.

4. Save, commit, and push.

**Demo:**

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo.git

# Go to the project directory
cd your-repo

# Install dependencies
npm install

# Start the server
npm run dev
```

**Workflow:**

```mermaid
flowchart LR
    A[Clone repository] --> B[Install dependencies]
    B --> C[Set environment variables]
    C --> D[Run start command]
    D --> E[App running locally!]
classDef screen fill:#4a944a,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bce8bc,color:#2b2620,stroke:#4a944a,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:D9C4A9,100:B3946F&height=90&section=header&text=Appendix&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Use the appendix for extra reference material that doesn't fit neatly into the main sections — glossaries, extended notes, or related links.

**Steps:**

1. Identify any extra details, definitions, or references your README doesn't cover elsewhere.

2. Add a heading titled "Appendix" near the bottom of your README.

3. List supplementary content using bullet points or sub-headings.

4. Save, commit, and push.

**Demo:**

- **Glossary:** JWT — JSON Web Token, used for authentication
- **Related Docs:** [Link to external documentation]
- **Additional Notes:** Any edge cases or known limitations

**Workflow:**

```mermaid
flowchart LR
    A[Gather extra reference info] --> B[Add Appendix heading]
    B --> C[List as bullets or sub-sections]
    C --> D[Commit and Push]
    D --> E[Appendix live!]
classDef screen fill:#94704a,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#e8d5bc,color:#2b2620,stroke:#94704a,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:D9CBA9,100:B3A06F&height=90&section=header&text=Contributing&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Let others know how they can contribute to your project — pull requests, issues, and coding standards.

**Steps:**

1. Explain how to fork and clone the repository.

2. List the branch naming convention and commit message style you expect.

3. Explain how to open a pull request and what checks it must pass.

4. Save, commit, and push.

**Demo:**

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

**Workflow:**

```mermaid
flowchart LR
    A[Fork repository] --> B[Create feature branch]
    B --> C[Commit changes]
    C --> D[Push and open PR]
    D --> E[PR reviewed and merged!]
classDef screen fill:#94804a,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#e8ddbc,color:#2b2620,stroke:#94804a,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9BCD9,100:6F8FB3&height=90&section=header&text=Demo&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Show your project in action with a screenshot, GIF, or live link — this is often the first thing people look at.

**Steps:**

1. Take a screenshot or screen recording of your app (use tools like ScreenToGif or Kap for GIFs).

2. Upload the image/GIF to your repo (e.g. an `assets` folder) or host it externally.

3. Embed it using Markdown image syntax.

4. Save, commit, and push.

**Demo:**

```markdown
![App Demo](assets/demo.gif)
```

Or link to a live deployed version:

```markdown
🔗 [Live Demo](https://your-deployed-app.com)
```

**Workflow:**

```mermaid
flowchart LR
    A[Record screenshot or GIF] --> B[Add to repo or host]
    B --> C[Embed with Markdown]
    C --> D[Commit and Push]
    D --> E[Demo visible!]
classDef screen fill:#4a6f94,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bcd0e8,color:#2b2620,stroke:#4a6f94,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:C4D9A9,100:9AB36F&height=90&section=header&text=Deployment&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Explain how to deploy your project so others can get it running in production.

**Steps:**

1. List the platforms used (e.g. Vercel for frontend, Render for backend, MongoDB Atlas for database).

2. Add the exact commands or steps needed to deploy each part.

3. Mention any required environment variables for deployment.

4. Save, commit, and push.

**Demo:**

```bash
# Build the frontend
npm run build

# Deploy to Vercel
vercel --prod
```

**Workflow:**

```mermaid
flowchart LR
    A[Choose hosting platforms] --> B[Set environment variables]
    B --> C[Run build and deploy commands]
    C --> D[Commit and Push]
    D --> E[App live in production!]
classDef screen fill:#6f9440,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#d2e8bc,color:#2b2620,stroke:#6f9440,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:B3A9D9,100:816FB3&height=90&section=header&text=Documentation&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Link out to detailed documentation for setup, usage, or advanced configuration if your README alone isn't enough.

**Steps:**

1. Decide if documentation lives in a `/docs` folder, a wiki, or an external site.

2. Add a short description of what the docs cover.

3. Link directly to the documentation.

4. Save, commit, and push.

**Demo:**

📚 Full documentation is available [here](./docs/README.md).

**Workflow:**

```mermaid
flowchart LR
    A[Organize docs location] --> B[Write short summary]
    B --> C[Add documentation link]
    C --> D[Commit and Push]
    D --> E[Docs linked!]
classDef screen fill:#6f4a94,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#d2bce8,color:#2b2620,stroke:#6f4a94,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:BCD9D9,100:6FB3B3&height=90&section=header&text=FAQ&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Answer common questions users or contributors might have about your project.

**Steps:**

1. Collect the questions you're most often asked about the project.

2. Format each as a bold question followed by a short answer.

3. Keep answers concise — link to detailed docs for longer explanations.

4. Save, commit, and push.

**Demo:**

**Q: How do I reset my database?**  
A: Run `npm run seed` to reset and repopulate sample data.

**Q: Can I use this without MongoDB?**  
A: Currently no, MongoDB is required as the primary database.

**Workflow:**

```mermaid
flowchart LR
    A[Collect common questions] --> B[Write concise answers]
    B --> C[Format as Q and A]
    C --> D[Commit and Push]
    D --> E[FAQ live!]
classDef screen fill:#4a9494,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bce8e8,color:#2b2620,stroke:#4a9494,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:D9D0A9,100:B3A56F&height=90&section=header&text=Lessons%20Learned&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Share the key challenges you faced and what you learned while building the project — helpful for your own growth and for others in similar situations.

**Steps:**

1. Reflect on the hardest problems you solved during development.

2. Note what approach worked, and what you'd do differently next time.

3. Write each as a short bullet point under a "Lessons Learned" heading.

4. Save, commit, and push.

**Demo:**

- Learned how to structure JWT-based authentication securely across client and server
- Realized early schema planning saves major refactoring time later
- Improved error handling by centralizing it in Express middleware

**Workflow:**

```mermaid
flowchart LR
    A[Reflect on challenges] --> B[Note what worked or didn't]
    B --> C[Write as bullet points]
    C --> D[Commit and Push]
    D --> E[Lessons documented!]
classDef screen fill:#948a4a,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#e8e0bc,color:#2b2620,stroke:#948a4a,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:D9A9BC,100:B36F8F&height=90&section=header&text=Screenshots&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

Visuals help people quickly understand what your app looks like and does, without running it themselves.

**Steps:**

1. Capture clear screenshots of your app's key screens (dashboard, login, main feature).

2. Save them in an `assets` or `screenshots` folder in your repo.

3. Embed each with Markdown image syntax, optionally with a caption.

4. Save, commit, and push.

**Demo:**

```markdown
![Dashboard View](assets/screenshots/dashboard.png)
![Login Page](assets/screenshots/login.png)
```

**Workflow:**

```mermaid
flowchart LR
    A[Capture screenshots] --> B[Save in assets folder]
    B --> C[Embed with Markdown]
    C --> D[Commit and Push]
    D --> E[Screenshots visible!]
classDef screen fill:#944a70,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#e8bcd5,color:#2b2620,stroke:#944a70,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:A9BCD9,100:6F8FB3&height=90&section=header&text=Tech&fontSize=22&fontColor=ffffff&fontAlignY=40" />
</p>

A short technical overview — the core languages, frameworks, and tools that power the project.

**Steps:**

1. List the primary tech stack in one line (client, server, database).

2. Optionally mention key libraries or tools used for specific features (auth, state management, etc.).

3. Keep it brief — detailed badges belong in a separate "Tech Stack Badges" section.

4. Save, commit, and push.

**Demo:**

**Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

**Backend**
<p align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
</p>

**Database**
<p align="left">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

**Workflow:**

```mermaid
flowchart LR
    A[List client tech] --> B[List server tech]
    B --> C[List database and tools]
    C --> D[Commit and Push]
    D --> E[Tech overview live!]
classDef screen fill:#4a6f94,color:#ffffff,stroke:#2b2620,stroke-width:2px;
classDef action fill:#bcd0e8,color:#2b2620,stroke:#4a6f94,stroke-width:2px;
class A,C,E screen;
class B,D action;
```

<br><br>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=170&text=Ended&fontSize=50&descAlign=37&animation=twinkling&fontColor=ffffff&fontAlign=50&section=footer" />
</p>
