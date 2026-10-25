# Lokesh Addagiri

I study Data Science and Business Administration at Northeastern University, with concentrations in Supply Chain Management and International Business. Most of my work starts with data that arrives messy and ends with something a person can act on.

I'm looking for a **January to June 2027 co-op** in data science, analytics, or operations.

[lokeshaddagiri.com](https://www.lokeshaddagiri.com) · [LinkedIn](https://www.linkedin.com/in/lokeshaddagiri) · [Resume (PDF)](https://www.lokeshaddagiri.com/documents/lokesh-addagiri-resume.pdf) · [Email](mailto:addagiri.l@northeastern.edu)

## Projects

I built these two apps on my own. Both are live, and the code for both is public.

### CardEdge

**Play the spot. Know the math.** A phone-first poker and blackjack trainer: enter the hand in a few taps and it tells you the move, with the numbers behind it.

<p align="center">
  <a href="https://cardedge-five.vercel.app/brag.mp4">
    <img src="https://raw.githubusercontent.com/neu-laddagiri/cardedge/main/docs/brag-preview.gif" alt="CardEdge preview: &quot;Call or fold?&quot; on a heart draw, answered with Raise at 70.8% equity against 33.3% pot odds" width="640">
  </a>
  <br>
  <a href="https://cardedge-five.vercel.app/brag.mp4"><b>▶ Watch the 20-second launch video</b></a>
  <br>
  <a href="https://cardedge-five.vercel.app"><b>Try it live →</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/neu-laddagiri/cardedge"><b>Source</b></a>
</p>

- **Poker:** live Hold'em equity against modeled opponent ranges, next to the exact pot odds, with a fold, call or raise recommendation. Monte Carlo simulations run in a cancellable Web Worker and report a 95% interval.
- **Blackjack:** the Wizard of Odds basic-strategy charts for your table's deck count and rules, with every chart cell checked by tests.
- **Results:** a dated profit/loss ledger for both games, kept to the cent. Everything works without an account; signing in syncs it through Supabase Postgres with row-level security.
- Unit tests with coverage gates run on every push in GitHub Actions.

Built with Next.js 16, React 19, TypeScript, Tailwind CSS 4, Zustand, Supabase and Vitest.

### IG Wrapped

**Your Instagram data export, turned into your own Instagram:** a feed, stories, a profile and a DM inbox, all about you. It never asks for your Instagram password.

<p align="center">
  <a href="https://ig-wrapped-snowy.vercel.app/brag.mp4">
    <img src="https://raw.githubusercontent.com/neu-laddagiri/ig-wrapped/main/docs/brag-preview.gif" alt="IG Wrapped preview: the Instagram-style feed with insight posts" width="640">
  </a>
  <br>
  <a href="https://ig-wrapped-snowy.vercel.app/brag.mp4"><b>▶ Watch the 22-second launch video</b></a>
  <br>
  <a href="https://ig-wrapped-snowy.vercel.app"><b>Try it live →</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/neu-laddagiri/ig-wrapped"><b>Source</b></a>
</p>

- Shows who doesn't follow you back, the people you actually talk to, your peak era and what advertisers think you're into. No export yet? The live site has demo data.
- Parses export ZIPs of up to 512 MB in the browser with JSZip, so the ZIP never leaves your device. An optional account saves the parsed analysis, never the original ZIP or media.
- One identity graph matches follows, DMs, likes, comments and story interactions to the same account, so every number about a person agrees across the app.
- The AI analyst chat answers questions from aggregated metrics, not the raw archive or full DM history.

Built with Next.js 16, TypeScript, Tailwind CSS 4, JSZip, Recharts and Supabase.

### More work

- **[Banking Fraud and Corporate Misconduct](https://www.lokeshaddagiri.com/documents/ds2500-banking-fraud-final-report.pdf)**, my DS 2500 capstone with a four-person team. Do regulatory penalties change bank behavior? I owned ingestion and cleaning: about 35,000 consumer complaints pulled from the CFPB API into Pandas tables. We then compared complaint patterns at Wells Fargo and TD Bank around major enforcement actions.
- **[NFL Salary vs. Team Performance](https://github.com/bclynde/nfl-salary-performance)**, a DATA Club project where I led a four-person team. Ten NFL seasons (2013 to 2022) of salary cap spending by position group, modeled against team results. I built the data cleaning and merging, the scikit-learn model, and the Panel and Plotly dashboard.
- **[Smart Health Monitoring System Rollout Plan](https://www.lokeshaddagiri.com/documents/mg4057-shms-final-report.pdf)**, a team project for my project management capstone in Athens. A 195-day, 55-task rollout across a healthcare network: a work breakdown structure, a five-phase Microsoft Project schedule, a stakeholder map and ten ranked risks.
- **[SEC Football Spending vs. Performance](https://www.lokeshaddagiri.com/coursework/mgsc2301)**, my Business Statistics capstone. Across 70 SEC program-seasons from 2020 to 2024, athletic spending was statistically significant (p = 0.013) but explained only 8.7% of the variance in conference standings.
- **[lokeshaddagiri.com](https://www.lokeshaddagiri.com)** ([source](https://github.com/neu-laddagiri/lokesh-website)), my portfolio, where every course report, presentation and model is published.

## Right now

- **Webmaster, INFORMS at Northeastern** (since October 2026). I'm on the officer board of Northeastern's student chapter of INFORMS, the largest professional society for operations research and analytics. I maintain the chapter's website and publish each event there with its registration link.
- **Junior Technology Consultant, Family Business Consulting Club** (since September 2026). A newly created technical role at a 30-member student consultancy that does pro bono work for family-owned businesses. I support consulting teams of 8 to 15 on data and technical workstreams, and I own the club's website, starting with an audit that ranked six issues by priority.
- **Fall 2026 courses:** Introduction to Databases (CS 3200), Advanced Programming with Data (DS 3500) and Mathematical Foundations of AI (DS 3000).

## Education

- **Northeastern University**, Boston. B.S. in Data Science and Business Administration, expected May 2029. Concentrations in Supply Chain Management and International Business. John Martinson Honors Program, Dean's List, 3.83 GPA.
- **The American College of Greece**, Athens. Summer study abroad, May to June 2026: Project Management and Management Accounting.

## Skills

- **Languages:** Python, SQL, TypeScript, JavaScript, Java, HTML, CSS
- **Data and analytics:** Pandas, NumPy, scikit-learn, Matplotlib, Plotly, Tableau, Excel, SPSS, regression
- **Web:** React, Next.js, Tailwind CSS, PostgreSQL (Supabase), REST APIs, Web Workers
- **Tooling:** Git, GitHub Actions, Vitest, Vercel, Microsoft Project
- **AI tools:** Claude Code, ChatGPT, Gemini, GitHub Copilot, Cursor, LLM APIs

## Contact

Email is fastest: [addagiri.l@northeastern.edu](mailto:addagiri.l@northeastern.edu). I'm also on [LinkedIn](https://www.linkedin.com/in/lokeshaddagiri), and [lokeshaddagiri.com](https://www.lokeshaddagiri.com) has my resume and every course report and presentation.
