You are given one or more large CSS and/or JavaScript files. Your task is to reorganize them into a cleaner, modular structure by splitting the code into multiple files.

Guidelines:

* Analyze the code and group related parts based on their purpose and context (e.g., layout, components, utilities, API logic, UI handling, etc.).
* Do not split arbitrarily; make decisions based on logical separation and cohesion.
* Keep the structure intuitive and scalable, avoiding both overly large files and excessive fragmentation.
* Preserve all existing functionality exactly as it is.
* Maintain consistent naming conventions for files and folders.

For CSS:

* Separate global/base styles, layout, reusable components, and page-specific styles when appropriate.

For JavaScript:

* Separate concerns such as data fetching, UI manipulation, event handling, and utility/helper functions.
* Use ES modules (import/export) if applicable.

Output requirements:

* Provide the proposed folder/file structure.
* Provide the full content of each new file.
* Update and include any necessary import/export or HTML references.

Avoid over-engineering. Favor clarity, maintainability, and practical structure based on the actual code.
