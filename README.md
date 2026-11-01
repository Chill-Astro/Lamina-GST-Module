  <kbd>    
    <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c7396e3-3262-4ee8-a515-21a4c48224e6" />
  </kbd>
</p>

<div align="center">

A Simple GST Calculator for Lamina ✦ ! 

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

## Note from Developer :

A Star ⭐ will be Appreciated to Support this Project! :)


---

