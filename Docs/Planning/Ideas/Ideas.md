# Legend
<!-- ! NEW folder added here -->
<!-- TODO: Finish adding README.md for ILLUSTRIOUS -->
<!-- ? QUESTION: {{Quesion}} ? -->
<!-- * [JSON] config expected here -->
<!-- * [JSON] config expected here -->


1. Tag-vs-Asset Boundaries
<!-- ? QUESTION: What about v. Project ? -->
<!-- ? QUESTION: Is there a better place to store this distinction guide ? -->
Whenever you find yourself writing a utility or component that’s useful for both SystemCore and ILLUSTRIOUS, pause and decide:

If it’s purely a “tag definition,” push it into SystemCore/.

If it’s a “UI button” or “modal snippet” you only want in ILLUSTRIOUS’s web dashboard, keep it under ILLUSTRIOUS/Assets/.

This keeps “SystemCore” lean—just tags and core logic—while ILLUSTRIOUS can grow its own UI/UX library.
<!-- ? QUESTION: {{Quesion}} ? -->