# Structured Extraction With Python

Extract invoice details from plain text into structured JSON using the native ai& Python SDK.

This recipe builds on the ai& [Structured Outputs](https://docs.aiand.com/capabilities/structured-outputs/) docs.

## Setup

```sh
cd python/structured-extraction
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
export AIAND_API_KEY=your-aiand-api-key
```

For local development, you can also place `AIAND_API_KEY=...` in an ignored `.env.test` file in this directory.

## Run

```sh
python structured_extraction.py
```

The script prints validated JSON matching the invoice extraction schema.
