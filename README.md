Mochi Math Gold

Mochi Math Gold is a static, browser-based educational game designed for middle school Algebra 1 students. The primary objective is to develop proficiency in translating verbal sentences into formal mathematical expressions, equations, and inequalities.

Educational Objectives

The game targets specific curriculum standards related to mathematical literacy and algebraic translation:

Expressions (Easy): Identifying operations from keywords (Sum, Difference, Product, Quotient).

Equations (Medium): Recognizing equality indicators (Is, Equals, Results in).

Inequalities (Hard): Differentiating between "at most" ($\leq$), "at least" ($\geq$), "less than" ($<$), and "greater than" ($>$).

Order Operations: Addressing the "flip" rule for phrases like "less than" and "subtracted from" (e.g., "$5$ less than $x$" $\rightarrow$ $x - 5$).

Technical Architecture

The application is built as a single-file system to optimize for performance and ease of deployment:

Frontend Framework: Tailwind CSS (via CDN) for responsive UI components and Neobrutalist aesthetics.

Logic Layer: Pure JavaScript (ES6+) managing state, difficulty levels, and input normalization.

Assets: Scalable Vector Graphics (SVG) with CSS keyframe animations (mochi-dance, mochi-sad, tear-fall) for a lightweight, dependency-free visual experience.

Features

Progressive Difficulty: Three distinct tiers (Easy, Medium, Hard) focusing on different algebraic structures.

Interactive Feedback: Real-time character animations based on input accuracy.

Translation Guide: Integrated reference table accessible during gameplay to support learning retention.

Input Normalization: Algorithm handles white space and multiple valid mathematical notations (e.g., handling $2x$ vs $2*x$).

Deployment Instructions

Mochi Math Gold is designed to be hosted on static platforms like GitHub Pages:

Create a new repository on GitHub.

Upload index.html to the root directory.

Navigate to Settings > Pages.

Select the main branch and /root folder as the source.

Save settings; the site will be live at https://[username].github.io/[repo-name]/.

Controls

Keyboard: Use the 'Enter' key to submit answers and advance through levels.

Mouse/Touch: Interactive buttons for difficulty selection, menu navigation, and accessing the translation guide.
