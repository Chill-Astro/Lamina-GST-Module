  <kbd>    
    <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f472c58c-c277-4f85-83d0-82c2ecdcc713" />
  </kbd>
</p>

<div align="center">

A Simple GST Calculator for Lamina ✦ ! This is for v11.26100.16.0 BETA and Higher.

</div>

---

## Installation :

- Open Menu > Scroll Down > Press "Add" 
- Open `Chill-Astro.GST.lamina`

Enjoy! :)

---

## Module Code :

      {
        "Metadata": {
          "Name": "GST Calculator",
          "Author": "Chill-Astro Software",
          "Version": "1.0",
          "Description": "Calculate GST Amount and Total Price",
          "Repo": "https://github.com/Chill-Astro/Lamina-Modules-Repo"
        },
        "UI": {
          "Formula": "Total = Price + (Price * GST%)",
          "Inputs": [
            { 
              "Header": "Net Price", 
              "Label": "Amount before tax", 
              "Key": "price", 
              "Placeholder": "100.0" 
            },
            { 
              "Header": "GST Percentage", 
              "Label": "Tax Rate (%)", 
              "Key": "tax_rate", 
              "Placeholder": "18" 
            }
          ]
        },
        "Logic": {
          "Output": "'GST Amount: ' + (price * tax_rate / 100) + ' | Total Price: ' + (price + (price * tax_rate / 100))",
          "Error": "Please enter valid numbers for price and rate."
         }
      }

---

## ⚠️ IMPORTANT NOTICE ⚠️

Please be aware: There are fraudulent repositories on GitHub that are cloning this project's name and using AI-generated readmes, but they contain **completely random and unrelated files in each release**. These are NOT official versions of this project.

**ALWAYS ensure you are downloading or cloning this project ONLY from its official and legitimate source:**
`https://github.com/Chill-Astro/Lamina-GST-Module`

I am trying my best to report these people.

---

## ⚠️ Smoking Gun for Danger :

> [!CAUTION]
> **MALWARE ALERT:** If your downloaded folder looks like the images below, **DO NOT OPEN** any files. Format the drive or delete the folder immediately. Official releases are ONLY `.msix` files or an Inno Setup `.exe`.

<details>
<summary><b>View Details</b></summary>
  
* **Suspicious Windows Executables:** Files ending in `.exe`, `.bat`, or `.dll` (e.g., `luau.exe`, `StartApp.bat`).
* **Compressed Archives:** This project is distributed as an **MSIX**, never as a `.zip` or `.7z` containing Windows binaries.
* **Hidden Scripts:** Text files like `asm.txt` used to execute malicious code on your PC.
* The Following Folder Structure is used by Malware (Shown in a VM) :

![Screenshot_2026-03-01-18-52-39-337_com clone android dual space](https://github.com/user-attachments/assets/be691c9f-7def-4e8b-982c-c7ca2e9a067d)

![Screenshot_2026-03-01-18-53-09-759_com clone android dual space](https://github.com/user-attachments/assets/1c75031d-95be-4716-9347-b762e3dad5b8)

</details>

---


## Note from Developer :

Appreciate my effort? Why not leave a Star ⭐ ! Also if forked, please credit me for my effort and thanks if you do! :)

---

