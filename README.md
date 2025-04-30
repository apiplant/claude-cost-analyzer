# Claude Cost Analyzer

A simple web-based tool for analyzing Anthropic Claude API usage costs from CSV export files.

## Features

- Drag and drop or select CSV files containing Claude API usage data
- Analyze costs by date, showing aggregated usage statistics
- Filter results by model version, API key, and workspace
- Customize pricing for different Claude models (Haiku, Sonnet, Opus)
- Support for input tokens, output tokens, and cache tokens
- Responsive design that works on both desktop and mobile devices

## Usage

1. Open the `index.html` file in your web browser
2. Drag and drop your Claude API usage CSV file onto the page, or click to select a file
3. View your usage data aggregated by date
4. Use the filters to narrow down results by model, API key, or workspace
5. Adjust pricing if needed using the pricing form at the bottom

## CSV Format

The tool expects a CSV file with headers including:
- `usage_date_utc`
- `model_version`
- `api_key`
- `workspace`
- `usage_input_tokens_no_cache`
- `usage_input_tokens_cache_write`
- `usage_input_tokens_cache_read`
- `usage_output_tokens`

## Privacy

All processing happens locally in your browser. No data is sent to any server.
