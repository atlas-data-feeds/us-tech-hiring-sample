# 📊 US Tech Hiring & Salary Telemetry Dataset (30-Day Sample)

This repository contains a 30-day historical snapshot (1,000 anonymized records) of US Software Engineering job postings, compensation bounds, and tech stack skill requirements harvested by **Atlas Data Feeds**.

## 📁 Schema Overview
| Field Name | Data Type | Description |
| :--- | :--- | :--- |
| `record_id` | String | Unique record identifier |
| `timestamp_harvested` | ISO 8601 | Harvest timestamp |
| `target_company_name` | String | Normalized hiring organization name |
| `functional_role_category` | String | Role classification |
| `compensation_raw_min` | Integer | Lower bound salary scale ($USD) |
| `compensation_raw_max` | Integer | Upper bound salary scale ($USD) |
| `parsed_signals` | String | Extracted tech stack keywords |

## 🚀 Access Full Real-Time Daily Feeds
Looking for live daily streams, full database coverage, or automated API access?

- **Live REST API:** [api.atlasdatafeeds.com](https://api.atlasdatafeeds.com)
- **AWS Data Exchange & Snowflake Catalog:** [atlasdatafeeds.com](https://atlasdatafeeds.com)
- **Documentation & Support:** support@atlasdatafeeds.com
