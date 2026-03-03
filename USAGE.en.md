# CopyKit | 摘抄猫 Usage Guide (Community)

## 1. Install Extension (Developer Mode)

1. Unzip `build/copykit-v0.3.0.zip`
2. Open `chrome://extensions/` or `edge://extensions/`
3. Enable Developer Mode
4. Click "Load unpacked"
5. Select the extracted folder (must contain `manifest.json`)

## 2. Save Content

1. Select text on a web page, or right-click an image
2. Choose "Save text to CopyKit | 摘抄猫" or "Save image to CopyKit | 摘抄猫"
3. Select folder, add tags/notes, then save

## 3. Translation

1. Select text, then use "Translate selected text" from context menu, or click the floating translate button
2. In translation dialog, you can switch source/target language, model, and toggle paraphrase mode
3. Both source and translated text are editable; click "Retranslate" for iterative refinement

## 4. Settings

1. Open extension popup and click Settings
2. Configure translation params (`BASE_URL`, `API_KEY`, `MODEL`, etc.)
3. Optional features (for example clipboard monitoring) require explicit permission grant (`clipboardRead`)

## 5. Troubleshooting

- Install failed: ensure Developer Mode is enabled and you selected the extracted root folder.
- Translation failed: verify `BASE_URL`, `API_KEY`, and `MODEL`.
- Floating button missing: refresh page; if extension was just updated, reload extension and refresh page.

## 6. Contact

- Website: https://afffun.com/
- Email: john88188@outlook.com
- X: https://x.com/biggor888
