# Jonco Lab development studio custom packages manager

## Available packages:

- [@joncopm/core](#core)
- [@joncopm/frapp](#firebase-react-app)

## Directory structure

```
@joncopm
.
├── core
|   ├── src
│   │   ├── index.ts
│   │   ├── types.d.ts
│   │   └── modules
│   ├── package.json
│   └── README.md
├── packages
│    └── <package_name>
│        ├── node_modules
│        ├── src
│        │   ├── index.ts
│        │   ├── types.d.ts
│        │   └── modules
│        ├── package.json
│        └── README.md
├── tests
├── .gitignore
├── package.json
└── README.md
```

## Core

This package designed mostly for the demonstration purposes and contributions

## Firebase React app

This package contains a set of helpers, and utils to simplify usage of Google Firebase API with `create-react-app`.
