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

These ancillary types should otherwise be unecessary, so this library intends to hide them through a generic `Entity<T>` type.
