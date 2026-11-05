ACE AI - offline AI for Android (runs on the phone's CPU, no GPU needed)

ALL FILES ARE FLAT (no folders):
index.html, icon-only.png, icon-foreground.png, icon-background.png,
splash.png, splash-dark.png, build.yml, README.txt

SETUP ON GITHUB (works from a phone browser)
1. Create a new repository.
2. Add file > Upload files: upload index.html and the 5 icon/splash .png files.
   Commit.
3. The build script must live in a special folder, but GitHub can make it for you:
   Add file > Create new file. In the name box type exactly:
       .github/workflows/build.yml
   (typing the slashes creates the folders). Open build.yml from this zip in a text
   app, copy everything, paste it into the big box, then Commit.
4. Open the Actions tab > "Build Ace AI" > Run workflow. Wait for the green tick.
5. Open the run and download from Artifacts:
   - ace-ai-apk       -> app-debug.apk (install on Android; Ace AI logo icon)
   - ace-ai-full-zip  -> full offline web app

NOTES
- The model (Qwen2.5 0.5B, ~400 MB) and the AI engine are packed into the app by the build.
- CPU mode is slow on old phones: a few words per second, short answers.
- Needs about 1.5 GB free storage and 3 GB RAM.
