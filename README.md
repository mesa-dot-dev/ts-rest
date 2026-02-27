# @mesadev/sdk

TypeScript SDK for the [Mesa](https://mesa.dev) API.

Generated from the OpenAPI specification using [@hey-api/openapi-ts](https://heyapi.dev).

## Installation

```bash
npm install @mesadev/sdk
```

## Usage

```typescript
import { createClient } from "@mesadev/sdk";

const client = createClient({
  baseUrl: "https://depot.mesa.dev/api/v1",
  headers: {
    Authorization: "Bearer YOUR_API_KEY",
  },
});
```

## License

Apache-2.0
