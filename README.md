# Python Medical Data Validator

A Python script that validates medical records against strict formatting rules, built as part of the FreeCodeCamp Python Certification.

## What it does
Takes a list of patient dictionaries and validates each record against predefined constraints. Reports exactly which fields are invalid and at which position, or confirms all records are valid.

## Validation Rules
- **patient_id** — must be a string matching pattern `P` followed by digits (case-insensitive)
- **age** — must be an integer, 18 or older
- **gender** — must be `"male"` or `"female"` (case-insensitive)
- **diagnosis** — must be a string or None
- **medications** — must be a list of strings
- **last_visit_id** — must be a string matching pattern `V` followed by digits (case-insensitive)

## Concepts Used
- Dictionaries and nested data structures
- List comprehensions
- Regular expressions (`re` module)
- Type checking with `isinstance()`
- Set operations for key validation
- Enumerate for index tracking
- Unpacking with `**kwargs`

## How to Run
```bash
python main.py
```

## Built With
- Python 3
- `re` (standard library)
