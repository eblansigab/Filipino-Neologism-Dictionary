# Project Plan

## Phase 1 — Dataset Design

- Back up the original spreadsheet
- Create the dictionary_raw sheet
- Define the spreadsheet columns
- Encode 10 representative entries
- Export the test dataset as CSV

## Phase 2 — Data Validation

- Read the CSV using Python and pandas
- Check required fields
- Detect duplicate entries
- Validate status and domain values
- Standardize whitespace and search forms
- Separate accepted and rejected records

## Phase 3 — Relational Database

- Design the normalized database schema
- Create the SQLite database
- Load validated records
- Test SQL queries

## Phase 4 — Dictionary Search

- Implement exact lookup
- Implement prefix lookup
- Add Levenshtein-distance suggestions
- Test misspelled queries

## Phase 5 — Analysis and Interface

- Analyze terminology by scientific domain
- Analyze word-formation patterns
- Build a Streamlit interface
- Document findings and limitations