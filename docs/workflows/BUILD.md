# Build Workflow

Before writing code:

1. Read:
   - AGENTS.md
   - docs/CLIENT-BRIEF.md
   - docs/DESIGN-SYSTEM.md
   - docs/CONTENT.md
   - docs/SEO.md
   - docs/QA.md

2. Inspect the current project structure.

3. Identify:
   - existing reusable components
   - missing components
   - page structure
   - design direction
   - conversion goal

4. Before implementation, provide a short plan.

During implementation:

- reuse existing components when appropriate
- avoid unnecessary dependencies
- keep the design specific to the client
- maintain mobile-first behaviour
- preserve accessibility basics
- optimize images and JavaScript
- keep SEO metadata complete

After implementation:

1. run the development checks
2. check for console errors
3. test responsive behaviour
4. verify links and CTA
5. run:

npm run build

6. fix all errors before considering the build complete