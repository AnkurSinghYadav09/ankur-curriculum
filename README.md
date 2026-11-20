# ankur-curriculum

Pre-reads and lecture scripts for all my batches, in one standard structure.

## Structure

```
ankur-curriculum/
├── README.md
├── templates/
│   ├── pre-read-template.md
│   └── lecture-script-template.md
├── <batch-id>/
│   ├── module-01-<topic>/
│   │   ├── lecture-01-<topic>/
│   │   │   ├── pre-read.md
│   │   │   └── lecture-script.md
│   │   └── lecture-02-<topic>/
│   │       ├── pre-read.md
│   │       └── lecture-script.md
│   └── module-02-<topic>/
│       └── ...
└── ...
```

## Batches

| Batch ID | INI sheet name |
|----------|----------------|
| IITP-AIML-2604 | |
| IITP-AIML-TE-IV-2609 | |
| IITP-AIMLT-2606 | |
| IITR-AIML-TE-I-2606 | |

## Naming rules

- Lowercase and hyphens only (`module-01-linear-regression`, `lecture-03-gradient-descent`).
- Numbered modules and lectures, zero-padded (`module-01`, `lecture-02`).
- Every lecture folder has exactly two files: `pre-read.md` and `lecture-script.md`.
- Use the templates in `templates/` as the starting point for both files.

## Adding a new lecture

1. Create (or reuse) the module folder: `<batch-id>/module-0X-<topic>/`
2. Create the lecture folder: `lecture-0Y-<topic>/`
3. Copy both templates in and rename to `pre-read.md` and `lecture-script.md`.
