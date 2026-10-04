# ig-extractor

## Run

From PowerShell, in the project folder:

1. Start Chrome with the project profile and remote debugging enabled:

   ```powershell
   .\launcher.ps1
   ```

2. Start the extractor:

   ```powershell
   node .\extractor.js
   ```

3. In the opened Chrome window, sign in to Instagram if needed and open the profile's Followers or Following list. When the extractor prompts you, press Enter. It saves the usernames as a CSV in `extracts\`.

4. Run the diff:

   ```powershell
   node .\diff.js
   ```

Install the Node.js dependencies first if this is a fresh checkout:

```powershell
npm install
```
