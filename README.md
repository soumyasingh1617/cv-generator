CV Generator is an HTML5, CSS3 and Javascript only project that allows you to create a modern, clean and personalized CV according to your tastes. It also allows you to have a CV in dark mode but also to be able to export it directly in PDF format.

This project is obviously responsive: for desktop, laptop and tablet screens, the CV will be displayed in its classic form as a PDF. While for mobile phone screens, this one will be presented as a small showcase website.

To export the CV in PDF format, the html2pdf.js library was used and the version is 0.9.3. (this is the most stable version) html2pdf.js is a Client-side HTML-to-PDF rendering using pure JS, she converts any webpage or element into a printable PDF entirely client-side using html2canvas and jsPDF. (html2pdf.js Github repo).

For the icons, the Internet's icon library and toolkit Font Awesome was used.

The project was created by inspiring me from the bedimcode project called Responsive Resume Cv Smith (project link: responsive-resume-cv-smith) and watching the associated Youtube video of Bedimcode: Responsive Resume Cv Website Using HTML CSS And JavaScript | Light/Dark Theme & Export PDF

Features
This is the first version of the project (v1.0). To improve the project in a new version (v2.0), CV customization could be added: choice of a color palette other than white/black, addition of other less common sections. But also adding data in a .js file instead of touching the index.html file.

 Light/dark mode toggle
 Download to PDF
 Responsive
 Mobile screen mode
 Customization
Demo
Live demo here: live demo

Get started
Prerequisites
The only thing you need is a text editor or an IDE that allows connection to a local server (I recommend Visual Studio Code with its Live Server extension)

Installation
To start, let's go clone the project:

git clone https://github.com/LeaG76/cv-generator.git
Then, open it from your favorite text editor or IDE, normally you should have this project structure:

├── assets/
│   ├── javascripts/
│   │   ├── main.js
│   │   ├── html2pdf.v0.8.0.bundle.min.js
│   │   └── html2pdf.v0.9.3.bundle.min.js
│   ├── pdf/
│   │   ├── myResumeCV-dark.pdf
│   │   └── myResumeCV-light.pdf
│   ├── pictures/
│   │   ├── favicon/
│   │   │   └── ...
│   │   ├── results/
│   │   │   └── myResumeCV-light.png
│   │   ├── profile.png
│   │   └── profile.txt
│   └── stylesheets/
│       ├── layout.css
│       └── style.css
├── index.html
└── README.md
Warning: To carry out this project, you must be connected to a local server, more particularly for the generation in PDF and for the display of the image from the txt file. More details below

If you can't connect to a local server, no problem, don't worry! You can simply upgrade to an older version of html2pdf.js. Version 0.8.0 can save a pdf by just launching the .html file on a browser without going through a local server

Configuration
Local server

As said before, to be able to use this project, you will have to be connected to a local server
Plusieurs éditeurs de textes ont la fonctionnalité de local server (like VSCode, SublimeText, Atom, ...)

Live Server
Go Live Port 5500

Convert your profile picture into an url in Base64
Create multiples size Favicons
Usage
Put your informations
You can therefore modify the index.html file to put your information. If you want different icons, you can go to Font Awesome and select icons from a large selection of free and open-source icons

Customize your resume CV
changer palette couleur
changer police
changer icons Font Awesome
Examples
TodoList
Change html2pdf Version 0.8.0 -> 0.9.3
Création d'un fichier js dans lequel on met le contenu du CV
