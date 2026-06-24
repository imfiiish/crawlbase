# Conventions

**Docs must be written in English.**

## Structure

### docs/

```
docs/
├── README.md
├── 00_overview.md
├── 01_login.md       ← <NN>_<module>.md, sequential
├── 02_xxx.md
└── ...
```

Documents are numbered by exploration order, e.g. login first, then course table: `00_overview.md` → `01_login.md`.

### docs/src/

```
src/
├── README.md
├── login/                   ← top-level: by feature
│   ├── *.har
│   └── *.js
├── module_b/                ← nested when multiple systems per feature
│   ├── system_a/
│   │   └── *.har
│   └── system_b/
│       └── *.har
├── module_c/
│   └── *.har
└── ...
```

Raw capture data and extracted frontend scripts, organized by feature.

## Content

## Module Status

| # | Module | Description | Status |
|---|--------|-------------|--------|
| 00 | Login | <description> | ✅ Done |
| 01 | Module B | <description> | 🔄 In Progress |
| 02 | Module C | <description> | 📋 Pending |

### Module B

| System | Description | Status |
|--------|-------------|--------|
| System A | <description> | ✅ Done |
| System B | <description> | 🔄 In Progress |
| System C | <description> | 📋 Pending |
