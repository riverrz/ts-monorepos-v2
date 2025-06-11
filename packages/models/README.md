# @seeds/models

This package contains the core data models for the Seeds application, providing TypeScript interfaces and types for representing plant and seed packet information.

## Overview

The models package defines comprehensive data structures for:
- Plant characteristics (lifespan, growth habits, environmental needs)
- Seed packet information
- Garden planning data
- Companion planting relationships
- Environmental requirements
- Growth characteristics
- Resource requirements
- Planting information
- Production and harvest data

## Key Features

- Strongly typed interfaces for all plant-related data
- Comprehensive enums for standardized values
- Support for various measurement units and ranges
- Detailed environmental and growth requirements
- Companion planting and garden planning data structures

## Usage

```typescript
import { SeedPacketModel } from '@seeds/models';

// Use the models to type your data
const seedPacket: SeedPacketModel = {
  // ... seed packet data
};
```

## Development

This package is part of the Seeds monorepo. See the root README.md for development setup instructions. 