# Task List

1. ✅ Scan repo for file-based python invocations and script references
Identified and addressed across README.md, MIGRATION_GUIDE.md, run_expeirments.sh, internal calls
2. ✅ Make scripts a proper package and ensure -m works
scripts/__init__.py created; scripts renamed for valid modules
3. ✅ Update internal subprocess invocations to use python -m

4. ✅ Update README and docs to use python -m scripts.xxx
README.md and MIGRATION_GUIDE.md updated
5. ✅ Update run_expeirments.sh to reflect new module names

6. 🔄 Verify no remaining file-based invocations
Run ripgrep to confirm; update if any missed
7. ✅ Commit changes with clear message


