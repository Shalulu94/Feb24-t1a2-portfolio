# **Feb24 Term 1 Assignment 2 Web Portfolio**

## **Shahrul's Web Portfolio**

I have designed my website to act as a platform to showcase my coding and development skills.   and future projects to potetnial employers. You can view my website [here](https://shahrulwd.netlify.app/)

## **All links**

- [Portfolio Website](https://shahrulwd.netlify.app/)
- [Github Repository](https://github.com/Shalulu94/Feb24-t1a2-portfolio/tree/main)
- [LinkedIn](https://www.linkedin.com/in/shahrul-nasir-a7308b122/)


## **Features and Functionality**

My website is designed to be simple and minimalistic, displaying all the relevant information without being cluttered or excessive.

### Key features include:

- Multiple linked pages with constantly present navigation bar to allow users to switch between each page from any page
    - **Home Page** - Landing page with a very simple design featuring website logo and a brief description of the page
    - **About me** - Provide some insight into my life including my background, hobbies and previous work experience. This page includes a mini nav bar to switch between the sub topics
    - **Projects** - This is a showcase of all the projects I have worked on across different platforms and programming languages. This page will also include links to relevant project pages
    - **Blogs** - This is to keep updated with things about my life, both personal and professional. Provides potential employers with a better understanding of my personality and work ethic
    - **Connect** - Contains links to my professional profiles including LinkedIn and Github. Also allows users to contact me directly via email
- Each page has been designed with responsiveness in mind. Elements will change depending on whether user is viewing this one a computer screen or a mobile. Given the simple design nature, a third break point for tablets was not necessary as structures are reasonable above 700px
- The Tech stack required for the development include:
    - **Diagrams** - Utilised for the sitemap. Designed online at this [Website](https://app.diagrams.net/)
    - **Figma** - For Wireframing and design planning
    - **Windows Terminal** - For version control and connection to Github repo
    - **Visual Studios Code** - Primary IDE for coding
    - **HTML** - Page content
    - **CSS** - Page styling including animations
    - **GitHub** - Version control
    - **Netlify** - Deployment

## Target Audience

My target audience for this portfolio website would be potential employers or recruiters seeking to get a better understanding of my experience, skills and past projects. As I am targeting potential employers, language and formatting is important to ensure that my website is refined and professional to give a good first impression. 

This page will be a continuous work in progress and I will constantly update as I develop new skills throughout the course. 

## Sitemap

Please see below my Sitemap. Each page is interlinked with each other allowing user to navigate between every page from any page. Only exception is the Homepage which is used more as a landing page before users enter into main content. 

![Insert of my sitemap](./Docs/Wireframes/Site_Map.png)

The creation of the sitemap was the first step of my website development. It allowed me to visualise the amount of pages necessary, how I wanted to split the information across different pages and the navigation links required. Given the idea is that each main page would have it's own theme, it also gave me an indication of how many page templates i needed to create during the wireframing process.

## Wireframing - Figma

The second step in my development process was wireframing and designing all of the necessary page themes. I would consider my wireframes to be low fidelity, however in order to make it easier for me to visualise how certain elements change depending on desktop/mobile view, I've utilised colours for the specific elements. As wireframing was the initial design phase, some elements on the pages changed when I started properly coding it. Reasons for these included changed of thought, new design elements or limitations of functionality. 

**Understanding the Wireframe elements:**

- **Pink** - Represents a picture or photo
- **Grey** - Represents text
- **Red** - Represents the page header
- **Green** - Represents the main navigation bar
- **Blue** - Represents mini navigation bar
- **Orange** - Represents the page footer

### Homepage

The homepage was a simple landing page and was intended to not include a lot of overwhelming features or information. Originally this was designed to include a photo of myself on the homepage with a brief description. During the actual coding process, I experimented using my self-made website logo which i thought better suited as a landing page. 

![Homepage wireframe](./Docs/Wireframes/Homepage.PNG)

![Homepage wireframe - mobile view](./Docs/Wireframes/Homepage-mobile.PNG)

**Final product**

![Screenshot of finished homepage](./Docs/Screenshots/Homepage.PNG)

![Screenshot of finished homepage-mobile](./Docs/Screenshots/Homepage-Mobile.PNG)

### About me

The About me page consists of 3 separate pages with the same layout. As per the sitemap, I have included a mini navbar specific to the about me pages and allowing transition between the Background, Hobby and Experience pages. I have designed it this way to ensure minimal clutter and minimised scrolling for the user. If I had all of this information on a single page including the photos, then the users will need to be scrolling down a lot especially on a mobile which was not my intention. 

![About me page wireframe](./Docs/Wireframes/Aboutme.PNG)

![About me page wireframe - mobile](./Docs/Wireframes/Aboutme-mobile.PNG)

**Final product**

![Screenshot of finished About me page](./Docs/Screenshots/Aboutme-Background.PNG)

![Screenshot of finished About me page - mobile](./Docs/Screenshots/Aboutme-Background-mobile.PNG)

![screenshot of finished about me page hobby](./Docs/Screenshots/Aboutme-Hobby.PNG)

![screenshot of finished about me page hobby - mobile](./Docs/Screenshots/Aboutme-Hobby-mobile.PNG)

![screenshots of finished about me page experience](./Docs/Screenshots/Aboutme-experience.PNG)

![screenshots of finished about me page experience - mobile](./Docs/Screenshots/Aboutme-experience-mobile.PNG)

### Projects

This page has been designed as a page to quickly showcase all of my current and future projects. Each card represents a separate project and when active should take the user to the respective project page. At the moment, I currently only have a web portfolio project which is completed, but as other projects come online, the other cards will become active. I have kept the final product aligned with the wireframes and added some additional design effects such as shadows and pseudo-class elements. 

![projects page wireframe](./Docs/Wireframes/Projects.PNG)

![projects page wireframe - mobile](./Docs/Wireframes/Projects-mobile.PNG)

**Final Product**

![screenshots of finished projects page](./Docs/Screenshots/projects.PNG)

![screenshots of finished projects page-mobile](./Docs/Screenshots/projects-mobile.PNG)

![screenshots of finished projects page-mobile](./Docs/Screenshots/projects-mobile-2.PNG)

![screenshots of finished projects page-mobile](./Docs/Screenshots/projects-mobile-3.PNG)

### Blog

The blog posts have similar functionality to the projects cards and I originally thought to use the same design for both pages. However, in order to challenge myself and fully utilise the capabilities of flexbox, I decided to switch up the design and have images side by side with text and alternate the direction with each post. 

For this, i was required to use columns as the flexbox direction compared to standard flexbox in the projects page which would also automatically adjust based on different viewing ports. This required additional CSS and breakpoint management to ensure the blog posts stacked up correctly on mobile devices. 

![blog page wireframe](./Docs/Wireframes/Blog.PNG)

![blog page wireframe - mobile](./Docs/Wireframes/Blog-mobile.PNG)

**Final Product**

![screenshots of finished blogs page](./Docs/Screenshots/blog.PNG)

![screenshots of finished blogs page](./Docs/Screenshots/blog2.PNG)

![screenshots of finished blogs page](./Docs/Screenshots/blog3.PNG)

![screenshots of finished blogs page - mobile](./Docs/Screenshots/blog-mobile.PNG)

![screenshots of finished blogs page - mobile](./Docs/Screenshots/blog-mobile2.PNG)

![screenshots of finished blogs page - mobile](./Docs/Screenshots/blog-mobile3.PNG)

### Contact

The contact page is what is used for potential employers to connect via socials or contact me directly. This section has had some deviation from the original wireframes which included a form where users could enter their details plus some comments to allow me to get back to them in time. 

However, building a functional form requires some Javascript to be included which we have not yet covered and I did not want to include sections that do not work in my website. I decided to switch this out with a static photo instead, but will keep the wireframe as inspiration going forward once I develop the skills necessary to include a functioning form. 

This page also includes external links to my socials and a mail:to function to email me directly.

![contact page wireframes](./Docs/Wireframes/Contact.PNG)

![contact page wireframes - mobile](./Docs/Wireframes/Contact-mobile.PNG)

**Final Product**

![screenshots of finished contact page](./Docs/Screenshots/connect.PNG)

![screenshots of finished contact page - mobile](./Docs/Screenshots/connect-mobile.PNG)


