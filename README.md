# AI-Powered Lead Generation using n8n

This project is an automated AI-driven lead generation system built using n8n, OpenAI, and Google Maps data extraction.

## Overview
The workflow converts natural language business queries into enriched business leads by:
- Discovering businesses via Google Maps
- Extracting structured business data
- Crawling company websites for contextual information
- Enriching leads using Large Language Models

## Architecture
- **Main AI Agent Workflow**: Handles user queries and orchestration
- **Google Maps Extractor Subworkflow**: Scrapes business listings using Apify
- **Website Content Crawler Subworkflow**: Extracts and cleans website content

## Tech Stack
- n8n (workflow automation)
- OpenAI API (LLM-based enrichment)
- Apify (Google Maps scraping)
- HTTP & Web Scraping
- JSON-based workflow orchestration

## How to Use
1. Install and run n8n locally
2. Import workflows from the `/workflows` directory
3. Configure credentials (OpenAI, Apify)
4. Execute the workflow or use the chat trigger

## Use Cases
- B2B lead generation
- Sales and marketing automation
- Local business intelligence
- Market research

## Notes
Credentials and API keys are intentionally excluded.  
Users must configure their own credentials in n8n.