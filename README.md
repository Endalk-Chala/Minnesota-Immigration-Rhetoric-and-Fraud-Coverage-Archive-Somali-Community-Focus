📑 Table of Contents

Purpose

Overview

Repository Structure

Key Analytical and Research Topics

Public Contribution

License & Citation

Disclaimer

How to Submit an Issue or Pull Request

Technical Resources
1. Purpose

Collect, organize, and preserve publicly available information related to media coverage of Somali immigration rhetoric and fraud narratives in Minnesota (2022–Present).

Document how public discourse evolves across news outlets, political groups, government authorities, and community organizations.

Establish a verifiable timeline of how Somali communities are represented in local and national media.

Consolidate coverage from sources such as Star Tribune, MPR News, Sahan Journal, AP, Reuters, Fox 9, YouTube, Threads, Twitter/X, and TikTok.

Provide a centralized, evidence-based archive for journalists, researchers, policymakers, and community advocates.

Preserve statements and analyses by community organizations, advocacy groups, and Minnesota officials regarding the Temporary Protected Status (TPS) controversy and related fraud narratives.
2. Overview

Since 2022, Minnesota has seen renewed national attention around Somali and East African communities — from immigration policy debates (TPS and refugee programs) to high-profile fraud and accountability stories (e.g., Feeding Our Future).

This repository serves as a documentary archive, chronicling how these issues have been represented in the public sphere and how rhetoric around immigration, integrity, and accountability intersects in news coverage, politics, and community responses.
2. Overview

Since 2022, Minnesota has seen renewed national attention around Somali and East African communities — from immigration policy debates (TPS and refugee programs) to high-profile fraud and accountability stories (e.g., Feeding Our Future).

This repository serves as a documentary archive, chronicling how these issues have been represented in the public sphere and how rhetoric around immigration, integrity, and accountability intersects in news coverage, politics, and community responses.

3. Repository Structure

All main content is located in the /data/ directory.

data/
 ├── immigration_rhetoric/
 │    ├── news/                   # News reports, op-eds, and broadcast transcripts
 │    ├── political_statements/   # Statements from officials, agencies, or campaigns
 │    ├── community_responses/    # NGO and advocacy statements, public meetings
 │    └── metadata.csv
 │
 ├── fraud_and_scams/
 │    ├── news/                   # Coverage of fraud and scam stories
 │    ├── court_documents/        # Publicly accessible filings and verdicts
 │    ├── community_reactions/    # Community or advocacy statements
 │    └── metadata.csv
 │
 └── combined_timeline.csv


(Top-level files: README.md, LICENSE, optional /scripts/ if you automate ingestion.)

4. Key Analytical and Research Topics

This archive curates documentation and analysis on the following:

Evolution of Somali immigration rhetoric in Minnesota news and political discourse (2022–Present)

Media framing and bias in coverage of Somali-related fraud cases

Policy communication around TPS and resettlement programs

Intersection of immigration narratives, accountability, and trust

Representation of Somali community organizations and civic leadership

Online discourse on social-media platforms and its amplification through digital media

Comparative analysis of local vs. national coverage

5. Public Contribution

Contributions are welcome from community members, journalists, and researchers:

Add new news reports, official statements, or community responses

Correct metadata or update links

Provide summaries, thematic tags, or visual analyses

Translate or annotate relevant coverage

If you’re new to GitHub, use Issues to suggest additions or corrections.

6. License & Citation

This repository operates under a dual-license model:

Original content (timeline curation, metadata): Licensed under CC BY-SA 4.0

Quoted materials (news reports, videos, government docs): Copyright remains with original authors; archived here under fair use for educational and documentary purposes.

Citation Example

Source: Minnesota Immigration Rhetoric and Fraud Coverage Archive (Somali Community Focus)
URL: https://github.com/Endalk-Chala/Minnesota-Immigration-Rhetoric-and-Fraud-Coverage-Archive-Somali-Community-Focus

License: CC BY-SA 4.0

7. Disclaimer

This repository includes only publicly verifiable information.

No unverified rumors or personal data are included.

The goal is documentation and transparency, not accusation or speculation.

All entries reflect how narratives appeared in publicly accessible sources.

8. How to Submit an Issue or Pull Request
Submitting an Issue

Go to Issues → New Issue.

Provide:

Description of new or corrected information

Source URL(s)

Suggested section (Immigration Rhetoric or Fraud Coverage)

Submit for review.

Use Issues for:

Adding new media links or documents

Reporting broken links or duplicates

Suggesting improvements or metadata updates

Submitting a Pull Request

Fork this repository and create a branch.

Make edits (add news, metadata, etc.).

Submit a Pull Request with:

Summary of changes

Modified files

Source links or rationale

Maintainers will review and merge if appropriate.

9. Technical Resources

(Optional — only if you plan to add scripts.)

/scripts/scraper/ – Automated scraper for collecting new articles

/scripts/archive_links.py – Saves source links to the Internet Archive (Wayback Machine)

/scripts/requirements.txt – Required Python libraries
