# CopyKit | 摘抄猫 Privacy Policy

Effective Date: 2026-02-21  
Last Updated: 2026-02-21

Developer: **afffun.com**  
Website: https://afffun.com/  
Contact: john88188@outlook.com
X: https://x.com/biggor888

---

## 1. Scope

This policy applies to the browser extension **CopyKit | 摘抄猫** and explains how user data is handled.

## 2. Data We Process

As a local-first tool, the extension mainly processes:

1. User-saved content: text, images, source URL/title, timestamps, tags, notes.
2. User structure/configuration: folders, sort preferences, last-used folder.
3. Translation settings: `BASE_URL`, `API_KEY`, `MODEL`, language preferences and related parameters.
4. Clipboard text only when user explicitly enables clipboard monitoring.

The extension does not collect personal identity information by default.

## 3. How Data Is Used

Data is used only to:

1. Provide save/search/organize/edit capabilities.
2. Provide text translation and translation dialog interactions.
3. Run clipboard-triggered save prompts when enabled by user.
4. Maintain core extension stability.

## 4. Storage and Retention

1. Notes/folders are mainly stored locally in browser IndexedDB.
2. Settings are stored in `chrome.storage.local`.
3. By default, note content is not uploaded to developer servers.
4. Local data remains until user deletes/clears data or uninstalls extension.

## 5. Third-Party Transmission (Translation)

1. Selected text is sent to configured third-party LLM API only when user triggers translation.
2. Production build requires `https://` for translation endpoint.
3. Users choose and configure third-party providers on their own and should follow provider terms/policies.
4. Translation content is not used for ads profiling or unrelated resale purposes.

## 6. Permissions

The extension may request:

1. `storage`: save settings and local data.
2. `contextMenus`: context menu save/translate actions.
3. `activeTab`, `tabs`, `scripting`: show save/translate UI in active page.
4. `downloads`: save images locally.
5. `alarms`: scheduled tasks for enabled features.
6. `clipboardWrite`: user-triggered copy actions.
7. `clipboardRead` (optional): requested only when clipboard monitoring is enabled.
8. `https://*/*` host permission: access user-configured HTTPS translation endpoints.

## 7. Sharing and Disclosure

Data is not sold/rented/shared, except:

1. User-initiated translation requests sent to user-configured providers.
2. Legal/regulatory obligations.

## 8. User Controls

Users can:

1. Disable clipboard monitoring.
2. Update/remove translation settings including API keys.
3. Delete notes/folders or clear local data.
4. Manage data backups via export/import.
5. Uninstall extension to stop further processing.

## 9. Children and Sensitive Data

The extension is not targeted at children. Do not process illegal or highly sensitive personal data unless your own environment and provider compliance requirements are met.

## 10. Policy Changes

Important updates will be announced in release notes or developer site, and the "Last Updated" date will be revised.

## 11. Contact

- Website: https://afffun.com/
- Email: john88188@outlook.com
- X: https://x.com/biggor888
