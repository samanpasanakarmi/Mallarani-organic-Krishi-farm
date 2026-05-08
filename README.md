# Mallarani Organic Krisha Farm Website

This is the official website project for **Mallarani Organic Krisha Farm**.

Website live link:

```text
https://mallarani-organic-farm.netlify.app/

Project Purpose

This website helps visitors learn about the farm, view available products, check prices, see farm photos, contact the farm, place orders through WhatsApp, and find the farm location.

Main Features
Homepage with farm slogan
About farm section
Owner / farm team section
Why Choose Us section
Available This Week section
Product price list
Gallery with image popup
Customer reviews
FAQ section
Google Maps location button
Contact form that opens WhatsApp
Floating Call button
Floating WhatsApp button
Back-to-top button
Mobile menu
Fade animation while scrolling
Google Analytics tracking
Google Search Console support
robots.txt
sitemap.xml
Project Files
Mallarani Agricultural farm/
├── index.html
├── style.css
├── script.js
├── products.js
├── farm-info.js
├── admin.html
├── farm-admin.html
├── sitemap.xml
├── robots.txt
├── 404.html
├── README.md
└── images/
What Each File Does
index.html

This is the main website page. It contains the layout and sections of the website.

You usually do not need to edit this file unless you want to add or remove website sections.

style.css

This controls the design of the website.

Edit this file only when you want to change:

colors
spacing
font sizes
button styles
mobile layout
section design
script.js

This controls website behavior.

It handles:

mobile menu
WhatsApp order buttons
contact form
gallery popup
back-to-top button
fade animations
loading product data
loading farm information
products.js

This stores product information.

Edit this file when you want to update:

product name
product price
product availability
product description

Example:

const farmProducts = [
  {
    name: "Spinach",
    price: "₹50 / kg",
    status: "Available",
    description: "Fresh farm spinach available this week."
  }
];
farm-info.js

This stores farm information.

Edit this file when you want to update:

farm name
slogan
phone number
WhatsApp number
email
owner/team name
visiting hours
location name
Google Maps link

Example:

const farmInfo = {
  name: "Mallarani Organic Krisha Farm",
  slogan: "Pure Organic Food From Our Farm To Your Home",
  phone: "9844959890",
  whatsappNumber: "919844959890",
  email: "samanpasanakarmi@gmail.com",
  owner: "Mr. Gopal Prasad Nakarmi and family",
  visitingHours: "Sunday – Saturday, 9 AM – 5 PM",
  locationName: "Mallarani",
  mapLink: "https://maps.app.goo.gl/gGy54xaws6QoNezY6"
};
admin.html

This is a local product editor.

Use this file to generate updated products.js code without manually writing JavaScript.

How to use:

Open admin.html
Add or edit products
Click Generate products.js Code
Click Copy Code
Paste the copied code into products.js
Save
Redeploy to Netlify
farm-admin.html

This is a local farm information editor.

Use this file to generate updated farm-info.js code.

How to use:

Open farm-admin.html
Edit farm details
Click Generate farm-info.js Code
Click Copy Code
Paste the copied code into farm-info.js
Save
Redeploy to Netlify
sitemap.xml

This helps Google understand your website.

Current sitemap should point to:

https://mallarani-organic-farm.netlify.app/
robots.txt

This tells search engines that they are allowed to read the website.

Example:

User-agent: *
Allow: /

Sitemap: https://mallarani-organic-farm.netlify.app/sitemap.xml
404.html

This is the custom page shown when someone opens a wrong or missing link.

images/

This folder stores website images.

Current expected images:

vegetables.jpg
fruits.jpg
grains.jpg
herbs.jpg
farm-1.jpg
farm-2.jpg
farm-3.jpg
farm-4.jpg
farm-5.jpg
farm-6.jpg
owner.jpg
How to Update Products

Use the local product editor.

Open:
admin.html
Add, edit, or delete products.
Click:
Generate products.js Code
Copy the generated code.
Open:
products.js
Replace everything inside with the copied code.
Save the file.
Test locally.
Redeploy to Netlify.
How to Update Farm Details

Use the local farm info editor.

Open:
farm-admin.html
Update farm name, phone, email, timing, owner, or map link.
Click:
Generate farm-info.js Code
Copy the generated code.
Open:
farm-info.js
Replace everything inside with the copied code.
Save the file.
Test locally.
Redeploy to Netlify.
How to Test Locally

Use VS Code Live Server.

Open the project folder in VS Code.
Right-click index.html.
Click:
Open with Live Server
Test the website in browser.

Check these:

menu links
mobile menu
Available This Week section
price list
WhatsApp buttons
contact form
call button
map button
gallery popup
back-to-top button
footer links
How to Redeploy to Netlify
Save all updated files.
Zip the project folder.
Go to Netlify.
Open the Mallarani Organic Farm site.
Deploy manually by uploading the updated zip.
Wait until deploy is complete.
Open the live website.
Press Ctrl + F5 to refresh.

Live website:

https://mallarani-organic-farm.netlify.app/
Important Testing Checklist After Every Update

After every update, test:

1. Homepage loads correctly
2. Available This Week loads products from products.js
3. Product Price List loads products from products.js
4. Contact details load from farm-info.js
5. WhatsApp order buttons work
6. Contact form opens WhatsApp message
7. Call button works
8. Google Maps button opens correct location
9. Gallery image popup works
10. Mobile menu works
11. Footer links work
12. Google Analytics tag remains inside index.html
Google Analytics

Google Analytics ID:

G-9WLTCSS9NY

The tracking code is inside the <head> section of index.html.

Do not remove it unless you want to stop tracking website visits.

Google Search Console

The website has:

robots.txt
sitemap.xml

These files help Google discover the website.

To check if Google indexed the website, search:

site:mallarani-organic-farm.netlify.app
Backup Instructions

After every major update, create a backup zip.

Recommended names:

mallarani-organic-farm-v1.zip
mallarani-organic-farm-v2.zip
mallarani-organic-farm-before-admin-update.zip

Keep backups in:

Google Drive
external drive
computer folder
Safe Editing Rules

Do not delete these files:

index.html
style.css
script.js
products.js
farm-info.js
images/

When changing products, edit only:

products.js

When changing farm details, edit only:

farm-info.js

When changing design, edit only:

style.css

When changing layout sections, edit:

index.html
Current Farm Details
Farm Name: Mallarani Organic Krisha Farm
Slogan: Pure Organic Food From Our Farm To Your Home
Phone: 9844959890
WhatsApp: 919844959890
Email: samanpasanakarmi@gmail.com
Owner: Mr. Gopal Prasad Nakarmi and family
Visiting Hours: Sunday – Saturday, 9 AM – 5 PM
Location: Mallarani
Google Maps: https://maps.app.goo.gl/gGy54xaws6QoNezY6
Current Products
Spinach - ₹50 / kg
Coriander - ₹10 / bunch
Turmeric Powder - ₹350 / kg
Future Upgrade Ideas

Possible future improvements:

Real backend admin login
Database for products
Online payment system
Product images for each product
Delivery area section
Blog section
Multi-language website
Customer review form
Newsletter signup
Custom domain name