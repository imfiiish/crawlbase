# Conventions

**All docs must be written in English.**

## Structure

### docs/

```
docs/
├── README.md
├── 0_login.md       ← <N>_<module>.md, sequential
├── 1_xxx.md
└── ...
```

Documents are numbered by exploration order, e.g. login first, then course table: `0_login.md` → `1_xxx.md`.

### docs/src/

```
src/
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

| # | Module | Status |
|---|--------|--------|
| 0 | Login | ✅ Done |
| 1 | Module B | 📋 Pending |
| 2 | Module C | 📋 Pending |
