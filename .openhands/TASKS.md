# Task List

1. ✅ Scan repo for file-based python invocations and script references
Identified occurrences in README.md, MIGRATION_GUIDE.md, run_expeirments.sh, and internal call sites in scripts/run_multi_layer_experiments.py
2. ✅ Make scripts a proper package and ensure -m works
Created scripts/__init__.py and renamed numbered scripts to valid module names
3. ✅ Update internal subprocess invocations to use python -m
Updated run_multi_layer_experiments.py to call modules with -m
4. 🔄 Update README and docs to use python -m scripts.xxx
Updated README.md; need MIGRATION_GUIDE.md and doc/README_ko.md
5. 🔄 Update run_expeirments.sh to reflect new module names
Will update to python -m scripts.xxx but it's already -m; just module names change if referenced anywhere else
6. ⏳ Verify no remaining file-based invocations

7. ⏳ Commit changes with clear message


