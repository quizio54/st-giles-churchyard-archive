# St. Giles Churchyard Digital Archive

## Project Overview

This repository serves as a structured digital archive documenting the individuals buried in St. Giles Churchyard. The project aims to preserve historical records, transcribe epitaphs, and compile biographical information about the families interred there. By employing a professional project management workflow using GitHub, we can organize research tasks, track progress, and collaborate effectively.

## Project Structure

The archive consists of several key components:

1. **Burial Register (`burial_register.csv`)**: A master CSV database containing structured data for each individual.
2. **Research Issues**: GitHub Issues that break down the research into manageable tasks, each focusing on a specific family or section of the churchyard.
3. **Feature Branches**: Separate branches for each research task to isolate changes.
4. **Pull Requests**: Formal proposals to integrate researched data into the main archive, complete with historical narratives.
5. **Analysis Reports**: Markdown files summarizing findings, patterns, and insights from the collected data.

## Data Schema

The burial register uses the following columns:

- `RecordID`: Unique identifier for each burial record
- `LastName`: Family surname
- `FirstName`: Given name(s)
- `BirthYear`: Year of birth (if known)
- `DeathYear`: Year of death
- `Epitaph`: Transcription of the headstone inscription
- `FamilyPlot`: Identifier for the family plot or section
- `Notes`: Additional historical notes or sources

## How to Contribute

1. Browse open issues to select a research task.
2. Create a new branch from `main` named after the task (e.g., `feature/add-miller-family`).
3. Research the family or section, updating the `burial_register.csv` file with new entries.
4. Commit changes with descriptive messages.
5. Open a pull request referencing the issue and providing a narrative summary of findings.
6. After review, the pull request will be merged into `main`.

## License

This project is open source under the MIT License. See LICENSE for details.

## Acknowledgments

This project is inspired by historical preservation efforts and the rich heritage of St. Giles Churchyard. Contributions from historians, genealogists, and local community members are welcome.