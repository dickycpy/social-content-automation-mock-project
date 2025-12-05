# 01 — Product Overview

## 1. Background

Marketing teams often need to collect social content from multiple external sources, filter it based on campaign criteria, and prepare clean reports for stakeholders.  
However, the process is typically manual, repetitive, and prone to human error. Common challenges include:

- Manual content collection is highly time‑consuming, leading to repetitive copy‑and‑paste tasks and heavy reporting workloads.
- Difficulty managing multiple campaigns simultaneously, with limited tools to streamline oversight.
- Excessive reliance on personal devices for screenshots, creating clutter and inefficiency.
- No notification system when key opinion leaders (KOLs) publish new content, resulting in missed opportunities for timely engagement.
- Stories and ephemeral posts disappear after 24 hours, restricting the available window for capturing and archiving content.

This mock project proposes a **Content Automation Platform** that simplifies content aggregation, filtering, and reporting through workflow automation and a clean user interface.

---

## 2. Problem Summary

Marketing analysts and campaign managers spend excessive time:

- Pulling content manually from external sources  
- Organizing assets in spreadsheets  
- Filtering irrelevant posts  
- Exporting content into client-facing reports  

These steps are high-volume, mechanically repetitive, and lack standardization.  
The result is **inconsistent output quality and inefficiency**.

---

## 3. Product Vision

To automate content aggregation and streamline campaign reporting, enabling marketing teams to deliver faster, more accurate, and standardized reports.

The platform integrates external content APIs with workflow automation. Users can filter content, review results, and export final deliverables in a consistent format.

---

## 4. Target Users

### Primary Users

**Marketing Analysts**  
- Responsible for collecting and organizing social content  
- Need quick filtering and reliable export output  

**Campaign Managers**  
- Oversee reporting workflow  
- Require standardized, client-ready deliverables  

### Secondary Users

**Team Leads / Operations Managers**  
- Need oversight on report quality and consistency  

---

## 5. Product Goals

### Core Goals
- Reduce manual time spent on content gathering and filtering  
- Standardize reporting output and minimize errors  
- Provide an easy-to-use interface for non-technical users  
- Support workflow automation for repetitive tasks  

### Extended Goals (Future)
- Support multi-source content aggregation  
- Allow custom export templates  
- Provide API-based integrations and scheduled runs
- AI sentiment analysis for content analysis
- KOL selection pool 

---

## 6. Non-Goals

To maintain a clear MVP scope, the following are out of scope:

- Real-time analytics or monitoring  
- Advanced AI content classification  
- Custom report branding  
- Full CMS-level content editing  

These features may be considered in future iterations.

---

## 7. Success Metrics (Abstracted)

*(Sanitized for demonstration purposes only.)*

- Reduce manual workflow time by ~40–60%  
- Increase report accuracy consistency (fewer manual edits needed)  
- Decrease error rate in content selection  
- Improve turnover time per report  

---

## 8. MVP Scope Summary

The MVP includes:

- Fetching content from a third-party service via API  
- Applying basic filtering (date, keywords, content type)  
- Displaying filtered results in a simple UI or dataset  
- Exporting selected content to a standardized format  
- Supporting automation through workflow integration (e.g., n8n)  

**Excluded from MVP:** advanced filtering, AI classification, multi-user collaboration, team dashboards.

---

## 9. High-level System Flow (Abstract)

1. User inputs filtering criteria  
2. Automation workflow fetches content from external API  
3. System applies filters and deduplicates results  
4. User reviews content list on platform  
5. User exports final report  

A simplified flowchart will be included in `/docs/03_user_flow.md`.

---

## 10. Risks & Assumptions

### Risks
- API rate limits may affect content retrieval  
- Inconsistent metadata across content sources  
- Over-filtering leading to incomplete reports  

### Assumptions
- Users are familiar with basic content review workflows  
- API access is stable and authenticated  
- Export format can remain fixed for MVP  
