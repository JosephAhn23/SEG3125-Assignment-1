SEG 3125 A1 Report - Joseph Ahn

Report title: Design choices for my portfolio shell (visual communication)

Name: Joseph Ahn
Student number: 300360267

Before you upload this to Brightspace as a PDF, fill in part 4 and 5 with your real links. Right now those lines are still fake placeholders.


2. JavaScript experience and preparation for this project

I already work as a software engineer so JavaScript is not new to me. At work I use React a lot, like components and hooks and getting data onto the screen. For small sites or school work I still use normal HTML, CSS, and JS when I do not need a full app.

For this portfolio I mostly followed what the assignment wanted. I used W3Schools for Bootstrap 5 stuff like grid, spacing, navbar, and cards so I was not building every little layout from scratch. Same site when I forgot basic HTML or CSS. There is a main.js file in the project but it is almost empty, just a comment. I can add something small later like a footer year if we need more JS showing. When Bootstrap confused me I watched random YouTube walkthroughs. For the NN/g part on my site I read a few short articles on the Nielsen Norman Group website so I had normal words for why I spaced things how I did.

I still like React for bigger apps but this project was ok for practicing a simple static page with Bootstrap.


3. At least three portfolio or personal sites that inspired me

Three sites I actually looked at while I was working on my layout.

Brittany Chiang https://www.brittanychiang.com/
Her site has a lot on it but it does not feel crazy busy. You can jump around because the sections are clear. The colors are calm. It made me think I do not need bright neon stuff everywhere if the headings are clear.

Josh W Comeau https://www.joshwcomeau.com/
It feels like a real person made it, not a copy paste template. The text is easy to read and there are small fun details. That is one reason I picked Fraunces for my headings so my page is not the same boring sans font as every other dev site.

Jonathan Grado https://www.jonathangrado.com/?ref=siteinspire
Photo and art portfolio I saw on SiteInspire. It is dark and moody with grainy pictures and weird creative shots, not a coder portfolio. I still liked it because it shows you can have one clear look for a whole site and keep the fonts simple instead of piling on a bunch of different ones. I am not doing his art style for SEG but it made me want a little warmth in the background and hero instead of plain flat white only.


4. Link to hosted UI

Hosted portfolio (replace with your live URL):
https://[YOUR-HOSTING-PROVIDER]/[YOUR-SITE-PATH]

Examples people use: https://something.netlify.app or https://something.vercel.app or https://YOURUSERNAME.github.io/REPO-NAME/


5. Link to Bootstrap / source code

Public repository (replace with your GitHub or GitLab URL):
https://github.com/[YOUR-USERNAME]/[YOUR-REPO-NAME]


6. Design choices and visual communication

This part explains why I picked my colors, fonts, and layout. I am not a pro designer, I just tried to keep it easy to read and not ugly.

6a. Colours

I saved the colors as variables in styles.css so they stay the same everywhere.

Page background is about f6f3ef, warm off white, easier on my eyes than bright white.

Main text is about 1a1f24, basically black.

Gray 5c6670 for smaller labels and helper text.

Teal 1e4d4a for headings and that darker accent color.

Orange red c45c3e for links and badges so you notice what you can click.

I did not want the basic all blue tech look. The warm background plus the orange red means links stand out. The teal part stops it from feeling like a hospital flyer.

The site is only light mode for now. I skipped a dark mode toggle so A1 stayed simple.


6b. Typography

Fraunces from Google Fonts for titles and my name area. A little fancy but not over the top.

Source Sans 3 for body text and nav. Simple and still readable when it is small.

Big text for titles, smaller text for paragraphs, so you can tell what is what pretty fast.


6c. Screen layout scale hierarchy balance contrast whatever

Nav stays stuck at the top. My name on the left, How I work and Case studies on the right. No burger menu button, the links just stay there and wrap on a small phone.

Hero is a big title and one paragraph under it so you get the idea of the page quickly.

About is one rounded card in the middle. The top row has the visual identity text and my OKC card picture on the right. Under the line is Who I am and What I like. On a phone it stacks in order.

How I work has a slightly different background color so it looks like its own section.

Case studies are four Bootstrap cards in a row on a big screen. Same pattern each time: picture, design label, short text, link.

Size wise the hero is the biggest, then section titles, then normal body text.

Order down the page is nav, hero, about card, how I work, case studies.

I capped how wide the about text gets so lines do not stretch forever on a super wide monitor.

I did not splash the orange color on every line. Mostly links and badges use it.

I wanted it clean and easy to read with a bit of personality, not like a whole video game menu.
