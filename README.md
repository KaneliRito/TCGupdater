# TCG Power Tools Stock Pricing Scraper & GUI

A Playwright-powered scraper and Tkinter GUI to automate pricing updates on [TCG Power Tools].  
Supports undercutting by average or lowest competitor price (with configurable thresholds), or bumping price by +€ if no competitors are found.


⚠️Use at your own risk. The author is not responsible or liable for any incorrect pricing updates, financial losses, or other consequences resulting from using this tool. Always double-check suggested prices before confirming.⚠️
---

## 📦 Features

- **Automated CLI**  
  - Login flow saves session state.  
  - Two undercut methods:  
    - **Average** of all competitor prices minus €0.01 (if base > €0.02)  
    - **Lowest** competitor price minus €0.01 (if base > €0.02)  
  - If no competitors: raise current price by +€X.  
  - Configurable UI-build delay to avoid timing issues.  
  - Detailed 📝logging

- **Modern GUI**  
  - Tabbed interface with **Controls** and **Log** views.  
  - Real-time console output & progress bar.  
  - Choose pricing method (Average vs. Lowest).  
  - Set UI-build delay.  
  - Clear log with one click.  

---
- Windows  

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

