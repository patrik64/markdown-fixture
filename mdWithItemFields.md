---
itemId: some-unique-id
itemType: SIS
itemFulfills: KP-45
---

# Ketryx **rocks**

The Ketryx platform and Application Lifecycle Management (ALM) system. This is our main product.

## Setup

Make sure you have a development setup as described in the company handbook

### Prepare the Postgres user and databases

Make sure your \`postgres\` service is running:

## Item fields

### Description
Some description of the item

### Inputs
Some input of the item

### Outputs
Some output of the item

### Rationale
Some rationale of the item

## After the item fields
Should not count as part of the item fields
`;

export const mdWithItemFieldsAndNoSpecialDescription = `
# Title

This is part of the description, unless there's an explicit ### Description under ## Item fields.

## Description

still part of the description

## Item fields

### Inputs

something

### Outputs

something else

## Another section

(This will be ignored entirely.)
