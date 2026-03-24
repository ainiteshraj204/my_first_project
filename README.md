🛒 Smart Inventory Validation System
Modern Python Data Integrity Engine for E-commerce
📖 Overview
Building a real-world e-commerce application requires strict data validation to prevent business losses. This project demonstrates a Production-Ready Data Validation Engine built with Python 3.13. It ensures that every product entered into the system meets specific business rules before it reaches the database.

🛠️ Tech Stack
Language: Python 3.13+

Validation: Pydantic v2 (Industry Standard)

Package Manager: uv (Extremely fast Rust-based manager)

Editor: Cursor (AI-Native IDE)

✨ Key Features
Strict Type Checking: Uses Python Type Hints to ensure data consistency.

Business Logic Validation: - Price must be greater than 0.

Stock must be a non-negative integer.

Tags must be a list of strings.

Graceful Error Handling: Instead of crashing, the system provides detailed JSON-formatted error reports for debugging.

Modern Tooling: Managed entirely via uv for reproducible environments.
