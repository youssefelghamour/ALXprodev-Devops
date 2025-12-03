# Advanced Shell Scripting

This project focuses on automating data retrieval, processing, and reporting using advanced shell scripting techniques. It covers API interactions, JSON parsing, error handling, parallel processing, and generating structured reports for efficient and reliable data workflows.

- **API Automation:** Fetch data with `curl`.
- **Data Extraction:** Parse JSON with `jq`, `awk`, and `sed`.
- **Batch Processing & Parallelism:** Retrieve multiple data sequentially or in parallel.
- **Error Handling:** Retry failed requests and log errors.
- **Reporting:** Generate CSV reports.

## Project Structure

| File                              | Description                                       |
|-----------------------------------|---------------------------------------------------|
| `apiAutomation-0x00`              | Fetch single data and log errors                  |
| `data_extraction_automation-0x01` | Extract name, type, height, weight                |
| `batchProcessing-0x02`            | Retrieve multiple data sequentially with delay    |
| `summaryData-0x03`                | Generate CSV report with averages                 |
| `batchProcessing-0x02`            | Add retry logic for failed requests               |
| `batchProcessing-0x04`            | Fetch multiple data in parallel                   |