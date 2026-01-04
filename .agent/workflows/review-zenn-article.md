---
description: Review a Zenn article draft for guidelines and best practices
---

1. **[CRITICAL]** Read the Zenn Guidelines to ensure the agent has the latest context.
   - Read https://zenn.dev/guideline
2. Read the project's specific agent guidelines.
   - Read AGENTS.md
3. Read the target article.
   - Ask the user which article to review if not specified, or use the currently active file.
4. Analyze the article against the following criteria:
   - **Front Matter**: Check title length, emoji presence, type (tech/idea), topics (max 5), and published: false.
   - **Structure**: Ensure valid Markdown. Verify "Verification Appendix" is **DELETED** (it must not exist in the final article).
   - **Images**: Verify images use Zenn's specific path format (absolute paths starting with `/images/`).
   - **Links**: Ensure external links (libraries, specs) are embedded in text, not just listed at bottom.
   - **Persona**: Verify the tone matches "The Veteran Survivor" (Desu/Masu, relatable, experienced but humble).
   - **Zenn Compliance**: Check against the rules read in step 1 (e.g., no affiliate links, proper message box formats).
5. Output a review report.
   - List any violations or suggestions for improvement.
   - If the article is perfect, state that explicitly.
