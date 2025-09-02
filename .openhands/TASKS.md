# Task List

1. ✅ Scan repo for file-based python invocations and script references
Completed and confirmed via ripgrep
2. ✅ Make scripts a proper package and ensure -m works
scripts/__init__.py created; modules renamed
3. ✅ Update internal subprocess invocations to use python -m

4. ✅ Update README and docs to use python -m scripts.xxx
README.md, MIGRATION_GUIDE.md, doc/README_ko.md updated
5. ✅ Update run_expeirments.sh to reflect new module names

6. ✅ Verify no remaining file-based invocations
rg shows no remaining 'python x.py' usages; all examples use python -m modules
7. ✅ Commit changes with clear message


