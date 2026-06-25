# Bulk Upload Improvements — Campaign Manager

## Overview
Bulk upload via Excel template now supports all campaign types 
including Display Ads and Offsite campaigns. Previously only 
Sponsored Product Ads were supported.

## Why this matters
Large advertisers managing 50 or more campaigns were forced to 
create Display and Offsite campaigns manually one by one. This 
update removes that bottleneck entirely.

## How to enable
1. Go to Campaign Manager → Bulk Actions → Download Template
2. Select campaign type: Sponsored / Display / Offsite
3. Fill in the Excel template — one row per campaign
4. Upload via Bulk Actions → Upload File
5. Validation errors shown inline before submission

## Supported Fields
- Campaign name, type, status
- Budget, daily cap, schedule
- Targeting: keywords, categories, audiences
- Creative asset IDs

## Notes
- Maximum 500 rows per upload
- Template version must match current — download fresh each time
- Failed rows are skipped, successful rows are processed
