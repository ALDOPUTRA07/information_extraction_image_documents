# Information Extraction on Image Documents

<br />
<div align="center">
  <a href="">
    <img src="static/Information Extraction on Image Documents.png">
  </a>
</div>

<p></p>

<!-- TABLE OF CONTENTS -->
<details>
  <p>
  <summary>Table of Contents</summary>
  <ol>
    <li> <a href="#about-the-project">About The Project</a></li>
    <li><a href="#background">Background</a></li>
    <li><a href="#business-values">Business Values</a></li>
    <li><a href="#how-to-works">How to Works</a></li>
    <li><a href="#license">License</a></li>
  </ol>
  </p>
</details>


<p></p>

<!-- ABOUT THE PROJECT -->
## About The Project

Imagine a world where vast amounts of data locked in physical or digital documents can be easily extracted, analyzed, and utilized. The OCR document makes this vision a reality. Converting scanned documents such as images or PDFs into editable text significantly reduces manual effort and speeds up information retrieval.

This project performs the complex task of Information Extraction on structured image documents (Specifically, this project uses KTP as a document). This project utilizes the CNN model using pytorch to carry out 4 stages: document classification, document detection, document orientation, and information extraction. This project will use KTP documents.

<div align="center">
  <a href="">
    <img src="static/ information extraction.png" width="600">
  </a>
</div>


## Background
In today's digital age, the ability to extract valuable information from documents and images swiftly and accurately is crucial for businesses across various industries. This is where Document OCR (Optical Character Recognition) and structured image data extraction come into play. 

For example, in the financial area, there are a lot of scanned documents, such as salary slips, statements from banks, and loan agreements, among other forms. These documents can present information without a consistent structure, so extracting important information can be time-consuming.

Document information extraction involves using computer algorithms to extract structured data (like employee name, address, designation, phone number, etc.) from unstructured or semi-structured documents, such as reports, emails, and web pages. 

## Business Values
- Reducing manual effort
- Speeding up information retrieval.


## How to Works
This project will be divided into the following four projects:

**Note**: The project will specifically use a case document in the form of an ID card

<div align="center">
  <a href="">
    <img src="static/ information extraction.png" width="600">
  </a>
</div>

1. **Document Classification**, For Classifying a document to target label, such as KTP or Non-KTP.

    [Link Project](https://github.com/ALDOPUTRA07/ktp_classification)

2. **Document Detection**, For detecting and locating a document such as KTP within images while performing image alignment on them.

    [Link Project using OpenCV](https://github.com/ALDOPUTRA07/edge_detection_using_opencv)

    [Link Project using CNN Model](https://github.com/ALDOPUTRA07/id_card_detection_mask_rcnn)
3. **Document Orientation**, For detecting a document to determine the orientation of an aligned document.
    
    [Link Project](https://github.com/ALDOPUTRA07/id_card_orientation)
4. **Information Extraction**, An Information Extraction, last in the process, extracts relevant contents from information fields of aligned document in the correct orientation.
    
    Link Project (Coming soon)


## License
MIT

<p align="right">(<a href="#automed-forecasting">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Pytorch]: https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[Pytorch-url]: https://pytorch.org/