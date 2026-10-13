# Filipino Neologism Dictionary Pipeline

## Overview

This project creates a structured and searchable dataset of Filipino
neologisms, initially focusing on scientific and academic terminology.

The project applies data-engineering and classical computational-linguistics
concepts without using artificial intelligence or machine learning.

## Problem

Filipino scientific neologisms are often recorded across different
dictionaries, books, websites, and personal word lists. Their definitions,
etymologies, spellings, and sources may be inconsistent or difficult to search.

## Objectives

- Preserve Filipino neologisms in a structured dataset
- Record definitions, domains, etymologies, and sources
- Validate and standardize manually encoded entries
- Store the data in a relational database
- Support exact and typo-tolerant dictionary searches
- Analyze linguistic and morphological patterns

## Initial Scope

The first version will:

- Use manually collected entries
- Focus mainly on scientific terminology
- Use Google Sheets as the initial data source
- Validate data using Python
- Store validated records in SQLite
- Use classical string-matching algorithms
- Avoid AI and machine-learning features

## Planned Pipeline

Google Sheets → CSV → Python validation → Clean CSV → SQLite → Search interface

## Current Status

The spreadsheet schema and data-validation rules are being designed.

## Technology

- Google Sheets
- Python
- pandas
- SQLite
- Streamlit
- Git and GitHub
