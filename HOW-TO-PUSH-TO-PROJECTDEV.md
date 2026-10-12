
# How to Push to https://github.com/samriddhi30gauri/projectdev

## Option 1: GitHub Website (Easiest - No Command Line)

1. Open: https://github.com/samriddhi30gauri/projectdev
2. Click "Add file" -> "Upload files"
3. Drag ALL files from projectdev-READY-TO-PUSH.zip (extract first)
   - Important: Upload demo/ folder with index.html + images
   - Upload README.md
   - Upload all other folders
4. Commit message: "Add website link and visible diagrams - Final"
5. Click "Commit changes"

6. Enable Website:
   - Go to Settings -> Pages (https://github.com/samriddhi30gauri/projectdev/settings/pages)
   - Source: Deploy from a branch
   - Branch: main / Folder: /demo or / (root)
   - Save
   - Wait 2 min -> Your site: https://samriddhi30gauri.github.io/projectdev/

## Option 2: Command Line (If you have Git)

```bash
# 1. Download and extract
unzip projectdev-READY-TO-PUSH.zip -d projectdev
cd projectdev

# 2. Initialize git
git init
git add .
git commit -m "Add website link and visible diagrams - Final"

# 3. Connect to your repo
git branch -M main
git remote add origin https://github.com/samriddhi30gauri/projectdev.git

# 4. Push (will ask for GitHub username and token)
git push -u origin main --force
```

### How to get GitHub Token (if password fails):
1. GitHub -> Settings -> Developer settings -> Personal access tokens -> Tokens (classic)
2. Generate new token -> Check "repo" -> Generate
3. Copy token
4. When git push asks for password, paste TOKEN not password

## Option 3: GitHub Desktop

1. Download GitHub Desktop: https://desktop.github.com/
2. File -> Add Local Repository -> Choose projectdev folder
3. Publish repository -> Select samriddhi30gauri/projectdev -> Push

## After Push - Your Website Links:

- GitHub Repo: https://github.com/samriddhi30gauri/projectdev
- Live Website: https://samriddhi30gauri.github.io/projectdev/
- Demo with Diagrams: https://samriddhi30gauri.github.io/projectdev/demo/

Check: Open repo after push, you should see README with website links and demo folder with images.
