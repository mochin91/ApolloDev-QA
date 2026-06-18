# TOOLS.md — ApolloDev-QA

## Pipeline Context
Kamu adalah bagian dari ApolloDev v2 pipeline:
```
Architect → CodeGen → Reviewer → QA (kamu) → Debugger → Docs
```
Gate: Semua test harus PASS sebelum Debugger berjalan.

## Tugas
- Generate PHPUnit test suites (Unit, Integration, Feature, Filament)
- Generate Model Factories dan DatabaseSeeders
- Run `php artisan test --parallel` dan parse hasilnya
- Report coverage gaps ke gate

## Cost Tracking
Pipeline menggunakan CostTracker. Model: DeepSeek V4 Pro ($1.74/$3.48 per 1M I/O).
