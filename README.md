# Curated Collections

Curated repository collections for Principal AI.

This repository serves as a storage backend for curated collections displayed on the Principal AI website. It uses the Collection schema from `@principal-ai/alexandria-collections`.

## Structure

- `collections.json` - Collection definitions (name, description, theme, icon)
- `collection-memberships.json` - Repository assignments to collections

## Collections

| Collection | Description |
|------------|-------------|
| AI Coding Agents | Tools that code with and for you |
| Agent Orchestration | Frameworks for building multi-agent systems |
| AI Infrastructure | Core ML and LLM tools |
| Developer Tools | Productivity and infrastructure tools |
| AI Utilities | Helpful AI-powered tools and integrations |
| Creative & Business | Apps for creativity and business |

## Schema

Collections use types from `@principal-ai/alexandria-collections`:

```typescript
import type {
  Collection,
  CollectionMembership,
  CollectionsData,
  CollectionMembershipsData
} from '@principal-ai/alexandria-collections';
```

## Contributing

To add or modify collections, edit the JSON files and submit a PR.
