# Department Operations Hub

A centralized operational hub and resource repository designed for team alignment, process clarity, and cross-functional execution.  

It is a self-contained page—it does not require complex software, build steps, or developer environments to function.  


## Architecture and Main Philosophy

This hub is engineered as a **zero-dependency, single-file application**.  

* No installation required
* Portable
* Self-contained Setup  

---

Core architecture follows a two-tier hierarchy based on **priority** and **importance**, resulting in the following structure:

**ONBOARDING** (User setup, accounts, navigation)

**01 GOVERNANCE** (Main guidelines, Dos and Don'ts, compliance, policies, structural frameworks)

**02 EXECUTION** (Daily workflows, standard procedures, active tools)

**03 SUPPORT** (Troubleshooting, FAQs, Help Desk resources)

**04 ASSETS** (Templates, source files, central repositories)  


## Use Cases

* **As a Shared Team File (Standalone):** Drop the file into a shared folder. Anyone on the team can double-click it, and it will open instantly as a webpage in their browser.  
  
* **Embedded Inside Existing Corporate Tools:** Insert this page directly into portals your team already uses by using their "Embed" blocks. It will keep its custom look right inside your corporate wiki.  
  
* **Cloud Storage:** Upload this single file directly to a cloud storage bucket and permit "Static Website Hosting".

## Getting Started  
Choose the best option for you:

1. **Download everything:** Click the green **Code** (or Download) button at the top right of this page and select **Download ZIP**. Unzip the folder on your computer to access the file.  
   
2. **Direct Download:** Click on `index.html` in the list above, click the **Raw** button on the right side of the screen, then right-click anywhere on the page and select **Save As...** to save it directly to your computer.

Double-click to open `index.html` directly in any modern web browser  


## Edit Links

Open `index.html` with any compatible text editor (Notepad, VS Code, etc.).   

Swap out the `#` symbol with your document URL and change the placeholder text to your link's title, under the `link-list` lists:

```
<!-- BEFORE -->
<li><a href="#" class="link-item">Link 1</a></li>

<!-- AFTER -->
<li><a href="https://onlinelocation.com/your-company-doc-url" class="link-item">Q2 Project Tracker</a></li>
```

## Change the Theme  
The main colour palette is controlled by 5 variables at the top of the file, right under the `:root` section.  

Change these colour codes to update the look of the Hub:

```
:root{
    --bg-main: #161412;
    --text-main: #faf6f0;
    --text-muted: #b5ad9e;
    --accent-color: #f08c7a;
    --border-color: #36322e;

    /* ... other layout styles ... */
}
``` 

## Credits
☕ Made by @achlys-viii ☕
