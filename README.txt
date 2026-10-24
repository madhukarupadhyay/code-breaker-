RESEARCHMATE - PROTOTYPE (Chrome extension)

HOW TO INSTALL (2 minutes)
1. Unzip this folder.
2. Open Chrome and go to:  chrome://extensions
3. Turn ON "Developer mode" (top right).
4. Click "Load unpacked" and choose the ResearchMate-extension folder.
5. Pin the extension (puzzle icon > pin ResearchMate).

HOW TO USE (this is also your demo script)
1. Open any website about your topic (for example Wikipedia and 2-3 other sites).
2. Select a paragraph, right-click, choose "Add to research".
3. Right-click an image, choose "Add image to research".
4. Repeat on 3-5 websites. The red number on the icon shows how many clips you saved.
5. Click the ResearchMate icon, type the topic, pick Level and Language, click GENERATE NOTES.
6. Copy the note or download it as a .md file.

TWO MODES
- Demo mode (no key): works offline. Removes repeated sentences and keeps sources.
- AI mode: open Settings in the popup and paste an Anthropic API key. The AI writes the full
  structured note, explains images, flags conflicts and can answer in Hindi.
  (The key is stored only in your browser. For a real product, keep the key on a backend server.)

FILES
manifest.json   extension settings
background.js   right-click menu + saving clips
popup.html/css/js   the popup screen
lib.js          note merging, AI prompt, markdown viewer

TIP: if you change a file, click the refresh icon on chrome://extensions.
