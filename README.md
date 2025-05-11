
# Semantic Graph Prompt Generator (Prototype)

This is a prototype system for generating backend prompt descriptions from semantic graphs.

It demonstrates a **document-driven development** workflow, where structured semantic graph data is transformed into code-ready textual prompts.


## License

© 2025 陳毅安 / YI-AN CHEN. All rights reserved.  
This repository is published for demonstration purposes only.  
Redistribution or commercial use is not permitted without explicit permission.

---
> ⚠️ **This is not a template-based generator.**  
  While the interface uses dropdowns and forms for simplicity,  
  this project is fundamentally a **semantic graph-driven compiler.**  

> Users define logical components as nodes in a directed graph.  
  These nodes and their relationships are converted into structured prompts,  
  which are then fed to AI to generate **executable backend logic.**

> It's not configuration — it's compilation.
> Since the component types within each environment, as well as the categories of their interactions, can all be exhaustively enumerated, they are implemented as dropdown selections.


## Included HTML Tools (Frontend-only)

This project includes the following frontend-only tools. You can preview them directly online:

###  [graphBuilder.html](graphBuilder.html)
Visual editor for defining components and relationships in your software system.  
＞ [**Open graphBuilder.html**](https://ann0831.github.io/semantic-graph-promptgenerator-prototype/graphBuilder.html)

---

###  [promptGenerator.html](promptGenerator.html)
Compose structured prompts based on the graph.  
These prompts can be used directly with AI to generate the code for each component.  
＞  [**Open promptGenerator.html**](https://ann0831.github.io/semantic-graph-promptgenerator-prototype/promptGenerator.html)

---

###  [graphToText.html](graphToText.html)
Convert the graph into readable plain text, useful for documentation or prompt-based workflows.  
＞  [**Open graphToText.html**](https://ann0831.github.io/semantic-graph-promptgenerator-prototype/graphToText.html)

---

> 　 Simply open these HTML files in your browser. No backend or installation required.

