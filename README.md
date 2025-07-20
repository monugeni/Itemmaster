# Piping Material Codification Program

## Program Aim

This project outlines a framework for a piping material codification system. The goal is to manage an extensible catalog of piping items and generate unique codes for each item that can be used with barcodes.

### Key Objectives

1. **Item Type Management**
   - Users can define various item types (e.g., flanges, valves).
   - Each item type can reference a set of attributes.
   - Attributes may be shared across multiple item types to avoid duplication.

2. **Attribute Definition**
   - Support defining attributes such as diameter, metallurgy, hardness, pressure rating, and others as needed.
   - Allow grouping attributes so new item types can easily reuse them.
   - Ensure the system can grow to support any number or kind of attributes.

3. **Item Master Generation**
   - Generate unique items by combining different attribute values.
   - Provide a mechanism to store and retrieve these item combinations efficiently.

4. **Unique Code Creation**
   - Build a consistent scheme for creating a unique item code from its attribute values.
   - Ensure codes are compatible with barcode systems for physical tracking.

5. **Extensibility**
   - Design the program so new item types and attributes can be added without changing existing data structures.
   - Prepare for potential integrations with other systems that require item information.

## Future Work

This document only describes the program's aim. Implementation details such as database schema, codebase structure, and user interface will be determined in subsequent steps.
