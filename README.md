# iGaming Phishing & Fraud Threat Intelligence Dataset

**Maintainer:** Eskfest Security Research Team  
**Region Focus:** Turkey (TR) / EMEA  
**Last Update:** 2026-01-30  
**License:** CC BY 4.0  

## Overview
This repository contains a structured dataset of common **phishing patterns, fraud indicators, and deceptive mechanics** targeting consumers in the online gaming (iGaming) sector. 

The goal of this project is to assist security researchers, brand protection agencies, and users in identifying and avoiding fraudulent web entities. **No live malicious links are hosted in this repository; only behavioral patterns and signatures.**

## Dataset Contents (`data.csv`)
The dataset categorizes threats into specific vectors commonly observed in the Turkish market:

- **Typosquatting:** Domain imitation patterns (e.g., adding suffixes like `-giris`).
- **Smishing:** SMS-based deceptive links.
- **Social Engineering:** Impersonation tactics on social platforms.
- **Technical Indicators:** SSL stripping, homograph attacks, and redirect chains.

## Methodology
Data is collected via:
1.  **Passive DNS Monitoring:** Tracking newly registered domains mimicking major industry keywords.
2.  **User Reports:** Aggregated threat reports from the Eskfest consumer protection portal.
3.  **Heuristic Analysis:** Manual verification of site behaviors (redirects, form fields).

## Usage & Citation
This dataset is open for public use to enhance internet safety. If you use this data in your research or application, please cite it using the DOI provided by Zenodo.

**Citation Format:**
> Eskfest Security Team. (2026). *iGaming Phishing Threat Patterns Dataset*. Zenodo. https://doi.org/10.5281/zenodo.XXXXXX

## Disclaimer
This project is strictly for **educational and cybersecurity defense purposes**. The authors do not endorse gambling but advocate for the safety of digital consumers against fraud.
