# GST Rule 88A ITC Calculator

A responsive GST Input Tax Credit (ITC) Calculator built using HTML, CSS, and JavaScript.

This application allows users to compute ITC set-off, net GST payable, remaining ITC balance, and visualize utilization based on Rule 88A of the CGST Rules.

Live Demo:  
https://tamannasayyed360-collab.github.io/gst-rule88a-itc-calculator/

---

## Overview

The GST ITC Calculator helps users simulate statutory tax credit utilization under Rule 88A and Section 49(5) of the CGST Act. It applies IGST first and then optimizes CGST and SGST set-off while maintaining compliance constraints.

The interface is designed to provide structured computation clarity along with graphical visualization.

---

## Features

- IGST-first utilization logic  
- Optimized CGST and SGST set-off  
- ITC reversal handling  
- Net payable calculation  
- Remaining ITC tracking  
- Chart-based visualization using Chart.js  
- Input validation  
- Responsive design for mobile and desktop  

---

## Utilization Logic (Rule 88A Summary)

ITC is utilized in the following order:

1. IGST ITC against IGST liability  
2. Remaining IGST ITC against CGST or SGST  
3. CGST ITC against CGST liability  
4. SGST ITC against SGST liability  

Cross-utilization between CGST and SGST is restricted as per Section 49(5).

---

## Tech Stack

- HTML5  
- CSS3  
- Vanilla JavaScript  
- DOM Manipulation  
- Chart.js  

---

## Project Structure

gst-rule88a-itc-calculator/
├── index.html
└── README.md

---

## Deployment

This project is deployed using GitHub Pages from the main branch.

To deploy:

1. Push the project to GitHub.  
2. Go to Repository → Settings → Pages.  
3. Select "Deploy from branch".  
4. Choose branch: main.  
5. Select folder: / (root).  
6. Save.  

---

## Disclaimer

This calculator is intended for educational and demonstration purposes only. It does not replace professional tax advice or statutory interpretation. Actual tax liability may vary depending on amendments, circulars, notifications, and specific transaction scenarios.

---

## Author

Tamanna Sayyed  
© 2026 All Rights Reserved
