# OpenPRD - Making Resumes Bettter

OpenPRD is dedicated to revolutionizing the way resumes are managed and evaluated in today's job market. We are developing the Open Portable Resume Document (OpenPRD) to make the data contained in resumes easily retrievable and manageable for everyone involved in the application and hiring process.

## What is OpenPRD 

OpenPRD is a set of standards and open source tools to make resume data portable and streamline the hiring process for both job seekers and employers. By using structured data and JSON objects to transmit information, OpenPRD makes it easier for employers to evaluate and compare candidates, as well as identify specific skills and experiences that match their job requirements. This means that job seekers have a better chance of being matched with the right job, and employers can find the right fit more efficiently.

OpenPRD is committed to promoting transparency and openness in resume data management. The organization believes that the standardization of resume data will help to break down barriers and biases in the hiring process, making it more equitable and accessible for everyone.

Overall, OpenPRD is paving the way for a more efficient and effective hiring process, with the potential to transform the job market for the better.

### The contents of a OpenPRD packaged .prd file.

desrcibe.json   ---- Acts as a header for the document, contains a description of data type, version and resource naming.
document.body   ---- Contains the main body of the document in HTML style tags with microdata tags
document.style  ---- Stylesheet in css
resources/      ---- The resources directory contains any resource files such as: imgs, logos, icons, or fonts <b>Note</b> this
