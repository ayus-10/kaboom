# Update Instructions

```bash
# 1. Clone
git clone --recursive https://github.com/ayus-10/kaboom.git king-kaboom

# 2. Update submodules to latest
git submodule update --remote --merge

# 3. Push to GitHub
git add kaboom-app kaboom_server
git commit -m "Update submodules to latest HEAD"
git push origin main
```
