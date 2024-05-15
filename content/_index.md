---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin

    design:
      biography:
        style: 'font-size: 1.em; font-weight: 450; background-color: rgba(237, 231, 225, 0.9);  color: rgb(105, 102, 99); '

  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on Robust Anomaly Detection
          icon: academicons/arxiv
          url: https://openaccess.thecvf.com/content/CVPR2022W/FaDE-TCV/papers/Guarrera_Class-Wise_Thresholding_for_Robust_Out-of-Distribution_Detection_CVPRW_2022_paper.pdf
        - text: Checkout my Google Scholar
          icon: brands/google-scholar
          url: https://scholar.google.com/citations?user=IYVNi68AAAAJ&hl=it
        - text: Leave a message to connect with me
          icon: brands/linkedin
          url: https://www.linkedin.com/in/matteoguarrera/
---

// background-color: rgba(237, 231, 225, 0.8); text-align: justify;         st.style.color = 'black'; // Change text color to black  // color: white
