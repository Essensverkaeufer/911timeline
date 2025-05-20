Interactive Timeline: September 11, 2001 Attacks SPA
Objective
This project is a single-page web application (SPA) designed to provide an interactive and detailed chronological account of the September 11, 2001 terrorist attacks. It aims to make the complex sequence of events, the responses, and key decisions easily explorable and understandable for users.

Key Features
Interactive Chronological Timeline: A filterable and sortable timeline of major events from 9/11. Users can click on events to expand and view more detailed information.

Thematic Sections: Dedicated sections provide in-depth information on:

Overview of the attacks

The four hijacked flights (AA11, UA175, AA77, UA93)

The attack sites (World Trade Center, The Pentagon, Shanksville)

National response (FAA, NORAD, White House & Leadership)

Casualties and overall impact

Data Visualization:

Charts (created using Chart.js and HTML Canvas) display casualty statistics by location and visualize the FAA/NORAD notification and fighter scramble timeline gaps.

Dynamic Content: JavaScript is used to populate the timeline, handle filtering, and manage the display of detailed information for flights, locations, and responses.

Responsive Design: The application is styled with Tailwind CSS to ensure a good user experience across various devices (desktop, tablet, mobile).

No SVG/Mermaid JS: All graphics and diagrams are implemented using HTML/CSS or HTML Canvas, adhering to specific project constraints.

Technologies Used
HTML5: For the structure and content of the web page.

Tailwind CSS: For utility-first styling and responsive design. (Loaded via CDN)

JavaScript (Vanilla): For core application logic, interactivity, dynamic content updates, and event handling.

Chart.js: For creating interactive and responsive charts. (Loaded via CDN)

Data Source
The information presented in this application is based on publicly available records, primarily the 9/11 Commission Report and other official documentation related to the events of September 11, 2001.

How to Use/View
This is a self-contained single HTML file. To view and interact with the application:

Save the HTML code as an .html file (e.g., 911_timeline_spa.html).

Open the file in any modern web browser.

