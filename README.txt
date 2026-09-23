Spenzy Ultimate v2.1 — Fast & Stable Liquid Glass Edition

Changes from v2.0:
- Removed CSS animations/transitions that could fight the Android keyboard animation.
- Disabled expensive mobile backdrop blur and reduced shadow/repaint cost for faster WebView performance.
- Removed automatic keyboard opening/autofocus.
- Bottom navigation is hidden while typing so it does not jump above the Android keyboard.
- Activity search now updates only the result list instead of rebuilding the entire page/input.
- AI provider detection rebuilt from the original Spenzy provider system.
- Auto-detects OpenAI, Anthropic, Google Gemini, Groq, OpenRouter and xAI key patterns; ambiguous keys can be manually assigned to a provider such as DeepSeek.
- Added detected-provider display and Detect & Test connection button.
- AI errors now show the real provider/network/WebView error instead of a generic failure.
- OpenAI uses the Responses API; receipt image analysis remains supported.

Everything else from Spenzy Ultimate v2.0 remains in place.
No demo user, transactions, wallets, bills, goals, routines, habits, dues, notes, reminders, wishlist or chat data are preloaded.
Core features work locally/offline. Live AI and receipt analysis require internet and a user-provided API key.

WebToApp ready: index.html is at ZIP root.
