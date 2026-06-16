here are **full, end‑to‑end workflow examples** for **zero‑cost‑claude‑use**, each one designed to be *immediately usable*, *mobile‑friendly*, and *optimized for Claude’s free plan constraints*.  
These are not templates — these are **complete, ready‑to-run workflows** you can drop directly into your repo.

---

# **📘 Workflow 1 — Zero‑Cost Research Engine**  
A full research pipeline using Claude free tier + manual search.





```markdown
# Workflow: Zero‑Cost Research Engine
## Objective
Produce a structured, value‑dense research report using Claude’s free plan.

## Steps

### 1. Define the Research Scope
Paste into Claude:
> “You are my research system. The topic is: **[topic]**.  
> Generate 10 high‑leverage search queries grouped by subtopic.”

### 2. Run Manual Searches
- Use Google, Perplexity, or Bing.
- Copy/paste only **high‑signal excerpts** (100–300 words each).

### 3. Claude Summarizes Each Chunk
Prompt:
> “Summarize this excerpt into a 5‑bullet high‑signal digest.  
> Remove filler. Keep only insights.”

### 4. Build a Knowledge Graph
Prompt:
> “Combine all digests into a structured knowledge graph with:  
> - Entities  
> - Relationships  
> - Claims  
> - Evidence  
> - Contradictions”

### 5. Generate Final Report
Prompt:
> “Using the knowledge graph, produce a final report with:  
> - Executive Summary  
> - Key Insights  
> - Analysis  
> - Implications  
> - Actionable Recommendations”

## Notes
- Keep each paste under ~2,000 tokens.
- Use compression to maintain context.
```

---

# **📘 Workflow 2 — Claude‑as‑Code‑Compiler**  
Turn Claude into a pseudo‑compiler for generating full codebases.





```markdown
# Workflow: Claude-as-Code-Compiler
## Objective
Generate complete code modules using Claude’s free tier.

## Steps

### 1. Define the Project Skeleton
Prompt:
> “Create a file tree for a project that does: **[description]**.  
> Include folders, files, and responsibilities.”

### 2. Generate Each File Individually
For each file:
> “Generate the full contents of: **[path/file]**.  
> Constraints:  
> - Keep imports minimal  
> - Add comments  
> - Follow the architecture”

### 3. Validate & Refine
Paste the generated file back in:
> “Review this file for correctness, clarity, and missing logic.  
> Suggest improvements.”

### 4. Add Tests
Prompt:
> “Generate unit tests for **[file]** using **[framework]**.”

### 5. Produce Documentation
Prompt:
> “Generate documentation for the entire project in Markdown.”

## Notes
- Break files into chunks if they exceed context limits.
- Use iterative refinement instead of one-shot generation.
```

---

# **📘 Workflow 3 — High‑Compression Document Analysis**  
Extract deep insights from long PDFs using chunk‑and‑stitch.





```markdown
# Workflow: High-Compression Document Analysis
## Objective
Analyze long documents using Claude’s free plan.

## Steps

### 1. Extract Text
Use any free PDF → text tool.

### 2. Chunk the Document
Split into 1,000–2,000 token chunks.

### 3. Compress Each Chunk
Prompt:
> “Compress this text into a 10‑bullet semantic summary.  
> Preserve meaning, remove filler.”

### 4. Combine Summaries
Prompt:
> “Merge all chunk summaries into a unified outline.”

### 5. Deep Analysis
Prompt:
> “Using the outline, produce:  
> - Key arguments  
> - Evidence  
> - Weaknesses  
> - Contradictions  
> - Actionable insights”

### 6. Final Deliverable
Prompt:
> “Write a polished, structured analysis report based on the above.”
```

---

# **📘 Workflow 4 — Mobile‑Only Creator Workflow**  
Optimized for iPhone/iPad users with no desktop access.





```markdown
# Workflow: Mobile-Only Creator Workflow
## Objective
Create high‑quality content using only a phone/tablet + Claude free.

## Steps

### 1. Capture Inputs
Use Notes app:
- Ideas  
- Screenshots  
- Links  
- Drafts  

### 2. Send to Claude
Prompt:
> “Turn this into a structured outline with sections and bullet points.”

### 3. Expand Sections
For each section:
> “Expand this section into 2–3 paragraphs.  
> Keep it concise and high‑signal.”

### 4. Style & Tone Pass
Prompt:
> “Rewrite this in a clear, confident, expert tone.”

### 5. Final Assembly
Paste all sections back into Notes.

## Notes
- Screenshots act as context injection.
- Keep each message small to avoid rate limits.
```

---

# **📘 Workflow 5 — Zero‑Cost Agent‑Like Behavior**  
Simulate agent behavior without paid APIs.





```markdown
# Workflow: Zero-Cost Agent-Like Behavior
## Objective
Simulate multi-step autonomous behavior using Claude free.

## Steps

### 1. Define the Task Loop
Prompt:
> “You are a task loop.  
> Goal: **[objective]**.  
> Each cycle:  
> 1. Evaluate progress  
> 2. Generate next action  
> 3. Request needed inputs  
> 4. Produce output  
> Continue until I say STOP.”

### 2. Provide Inputs Manually
Paste results from searches, tools, or notes.

### 3. Claude Generates Next Action
Claude will:
- Analyze state  
- Suggest next step  
- Ask for missing info  

### 4. Repeat Until Complete

## Notes
- This simulates an agent without automation.
- Works best for research, planning, writing, and analysis.
```

---

# **📘 Workflow 6 — Value‑Dense Content Production**  
Produce content that is concise, structured, and high‑impact.





```markdown
# Workflow: Value-Dense Content Production
## Objective
Create content that is high‑signal and minimal‑token.

## Steps

### 1. Generate Structure
Prompt:
> “Create a 5‑section outline for content about **[topic]**.”

### 2. Fill Sections
Prompt:
> “Write each section in 3–5 bullet points.  
> No filler. Only insights.”

### 3. Convert to Polished Prose
Prompt:
> “Convert these bullets into concise paragraphs.”

### 4. Add Examples
Prompt:
> “Add 2–3 concrete examples per section.”

### 5. Final Pass
Prompt:
> “Rewrite for clarity, precision, and authority.”
```

---

# **Want the next level?**  
I can generate:

- **A full folder structure with these workflows included**  
- **An advanced workflow pack (10+ workflows)**  
- **A Claude‑optimized prompt library**  

Just tell me which direction you want to expand.
