# Greenview Heights HOA Portal

**A browser-based HOA workflow prototype built with Google Apps Script and Google Sheets.**

[Open the synthetic prototype](https://script.google.com/macros/s/AKfycbyi3BvhA_0hRkMkFhduit0x79MTbgk3OU1_-NzATvOavHLuc8bP3hp4FKeh0JClLQcXBw/exec)

> **Portfolio note:** Greenview Heights and the records shown in this demo are synthetic. This is a prototype, not a production system for real homeowner records.

## The problem

Keeping a separate spreadsheet for each household makes dues tracking difficult to maintain and review. Officers also need a clear place to publish notices and summarize the HOA's finances. I built a single portal to explore a more organized workflow using Google Sheets as the data source and Apps Script for the web interface.

## What the prototype shows

| View | Purpose |
| --- | --- |
| Board Announcements | Present community notices, maintenance updates, and events. |
| Financial Transparency | Show aggregate collections, expenses, retained funds, and category-level inflows and outflows. |
| Member Dues Inquiry | Let a household request its balance through a household selection and registered mobile-number check. |

The interface has mobile and tablet layouts. The live link above opens the synthetic demonstration.

## Screenshots

### Board announcements

![Board announcements](https://raw.githubusercontent.com/wgoleta/wgoleta/main/assets/hoa/hoa-announcements.jpg)

### Financial transparency

![Aggregate financial dashboard](https://raw.githubusercontent.com/wgoleta/wgoleta/main/assets/hoa/hoa-finances.jpg)

### Member dues inquiry

![Blank member balance inquiry form](https://raw.githubusercontent.com/wgoleta/wgoleta/main/assets/hoa/hoa-balance.jpg)

These screenshots show the public-facing views and a blank inquiry form; they do not display individual household statements.

## How I built it

- Used Google Sheets to organize the prototype's records in a shared data source.
- Used Google Apps Script to serve the web app and connect the interface to the sheet-backed data and workflows.
- Designed the portal around separate announcement, financial summary, and member inquiry tasks.
- Tested the interface with synthetic records and reviewed its layout at narrower screen sizes.

## Scope and next steps

This repository documents the prototype and links to the live demo. The backing spreadsheet and deployed Apps Script project are separate from this repository. Before using a similar system with real homeowner data, authentication, permissions, privacy controls, and financial calculations would need a dedicated review.

## Related work

- [GitHub profile and other analytics projects](https://github.com/wgoleta)
- [Global Payments Performance portfolio](https://github.com/wgoleta/global-payments-performance)
