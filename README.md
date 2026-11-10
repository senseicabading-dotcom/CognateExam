# Profile Databases
Run: `DB_PASSWORD='your-password' python3 run_all.py`
Push: `git init && git add . && git commit -m "Profile DBs" && git branch -M main && git remote add origin <repo-url> && git push -u origin main`
Never commit `column.key` or plaintext `.db` files (excluded in .gitignore); the plaintext .bak is excluded too.
