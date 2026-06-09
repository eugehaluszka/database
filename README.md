# Geolocation Glossary - Argentina 🇦🇷

This repository contains the database, dictionaries, and geolocation glossary utilised to process, filter, and accurately assign user provenance at the provincial level in Argentina, based on `user_location` metadata.

## Project Overview

To ensure the geographical precision of our data, we implemented a multi-stage location-filtration process on the `user_location` metadata. This repository stores the core resources of that pipeline, allowing for the standardisation of highly variable text strings (such as local toponyms, abbreviations, and common colloquialisms) into their corresponding official provinces.

### The Multi-Stage Filtration Process

1. **Predefined Dictionary (Initial Stage):** A structured mapping that includes the country name, all official provincial names and their abbreviations, and the five largest cities in each province.
2. **Frequency Analysis (Refinement Stage):** A frequency analysis was conducted on the raw `user_location` strings to manually identify and incorporate common local toponyms and regional variants that had not been previously captured.
3. **Final Glossary:** The consolidated output of this process (originally referenced as *Appendix A.3* in our documentation).

---
