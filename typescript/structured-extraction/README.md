# Structured Extraction With TypeScript

Extract invoice details from plain text into structured JSON using the native ai& TypeScript SDK.

This recipe builds on the ai& [Structured Outputs](https://docs.aiand.com/capabilities/structured-outputs/) docs.

## Setup

```sh
cd typescript/structured-extraction
npm install
export AIAND_API_KEY=your-aiand-api-key
```

For local development, you can also place `AIAND_API_KEY=...` in an ignored `.env.test` file in this directory.

## Run

```sh
npm start
```

The script uses Zod to define the extraction schema, sends the derived JSON Schema to ai&, and validates the parsed response before printing it.
