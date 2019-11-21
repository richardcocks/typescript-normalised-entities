# Typescript Normalised Entities

## Entities

When dealing with normalised state we often found ourselves writing code such as:

```typescript
{
    entitity:
        {
            byId: { [EntityTypeKey]: T }
            allIds: [EntityTypeKey]
        }
}
```

The codebase becomes littered with these ancillary types that feel like they should otherwise be unecessary.
