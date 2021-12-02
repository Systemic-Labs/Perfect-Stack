# Perfect-Stack  🛠i

A development guide and an awesome list of recommendations for a developer/team. 
This document covers libraries, tech stack, platforms, tools and other information 
to help you in deciding on best available options rather than just follow popularity. 

#### Target user:  
This article is useful to Web Developers, Designers, learning devs, startups, all decision makers. 
Feel welcome to contribute, to do an update, improvement, fix a mistake or in case you found a better 
option with clear advantage.

***


### [General Suggestions]

- Most developers use popular and usually outdated practices, due to: required at workplace, learned in the past, directed by a senior,...
include they recommend same things to others, therefore what's most poplular might not be the best option at the time being.

- If you're a new developer, updating your skills or planning a startup, your'e not bound to the above conditions, therefore do your own research, take advice from   professionals, check few review comparisons and finally make best decisions which benefit you and your products in long-term.
 *...Definitions, information, details and discussion on this topic, at the end of this document...*

#### Which Platforms?
- If you specifically targeting mobile Apps for Android and IOS, then use Flutter/dart, it's a native cross-platform SDK, has  very basic support for web and desktop... But if you want a more general purpose open platform, covering everything, choose the web platform, and your choice of stack, including capacitor for mobile app development.

#### ▪ Learning tips
- Development is not simple, it takes time, effort, practice and experience to gain practical skill, as there are many things to cover.  
- 1st learn the basics including the new updates. Ex:  in web >> Basics and new additions of JS, HTML, CSS.  
- Learn from best tutorials/courses, search for recent materials from an experienced tutor with high views/stats, Ex: Fireship.io  
- Learn in a group, join friends, divide learning, research,... share the findouts, work as a team, because it's too much to handle by one person.
  
***

## [Quick list]  

### Frameworks >>
 - **Mobile**: Flutter(pure native)......Capacitor 3 (Web and native)  
 - **Desktop**:  Tauri,  Deno executable (CLI).  
 - **Front-end**: Svelte(best overall, best DX),  Vue(older, a bit more popular, more jobs).  
 - **Back-end**: 1.Deno(js/ts) ___  2.Svelte-kit(svelte.js) ___  3.Node.js(KOA, Polka, nest).  
  
### UI >>  
- Standard CSS is best... specially when used in modular or component form, such as in svelte.   
- You might not need CSS libs, frameworks, pre-processors... as new additions like Grid, Houdini... 
solves problems developers had in the past yet if required:

  - Minimal approachs: (structure)...renderless, headless ui... (UI)...milligram, chota, skeleton...
  - CSS utility fameworks:  Windi CSS - Tailwind v2
  - UI-Kits: (semi/fully made components) Bootstrap, Bulma, Kahi UI, or other ui-kits of your liking.
  - **WebGL 3D**:  Spline,  Babylone.js,  Unity Tiny.

### Cloud platforms:  
- Personal: I found Gun.js handy, free, encrypted, serverless and distributed(web torrent).
- Cloudflare: best business class option, performant, advanced networking platform and services.  
- Hosting clouds:  more of a hosting platform yet offer some cloud functions, such as Vercel, Netlify...
- Enterprise cloud/server:   1. Amazon AWS ..... 2. Firebase (Google) .....  3. Azure (Microsoft)  
- Redis: if you require redis services, database, redis modules, database,...

### Database:
- Personal: Gun.js, is fast, free, simple, encrypted, auth with a semi graphQL data store. 
- Performance and features: Redis + Redis modules.
- Graph QL: 1- Dgraph  2- Hasura  
- Open Source: Arango DB,  best multi-model solution if a local server setup is intended.  

### Other stuff:
- **Low level Programming Languages**: ▪ **Rust**: Web std / Safe / Precise / System / Performance / made by Mozilla / supported.  
- **High level Programming Language**: ▪ **Nim**: Semi python syntax / easy / High performace, above C#, bellow GO 
- **Host**:  Begin, Cloudflare Pages, Deno Deploy,  Netlify, vercel.  
- **Static Site Generator**:  Astro(js, React, Vue, Svelte), Hugo(go), Hexo(js), Next(react), Nuxt(vue), MkDocs(py)  
- **Content Management System**:... Strapi, Ghost, Netlify CMS, Apostrophe, Factor(vue).  
- **Dev collaboration Platforms**: Github, Gitpod, Gitlab, notion.  
- **Dev tools**:  GIT, CDT, CLI tools, npm, vs-code, emmet, skypack...  
- **Other stuff**: find useful online tools.......Bundler: vite, snowpack......
***

## **[Top Web Frameworks]**    

### Frontend: 
 - **1.(Best overall) ▪Svelte**: best of all, DX, and integration with standards and all. long term strategic choice.  
 - **2.(Minimal)  ▪Solid**: fast, efficient, stable, advanced features. .... ▪**Marko**: solid with better DX. .... ▪**Sinuous**: best minimal.
 - **3.(Job offers/forced/required)**:  **Vue** (popular). .... **Angular / React / .net** (GG/FB/MS company platforms)

### Backend :
**1. Deno**: a runtime built by the creator of node.js, it is great, secure by default, lighter, faster, Wasm, latest tech.  
**2. Sveltekit**: if you are using svelte.  **Snel**: Svelte project built and compiled on deno instead of node.  
**3. Node.js**: in case you want most available libs, support, compatibility.  Koa or polka are a good node.js framework.  
  
### Svelte framework offers:  
**1. Developer Experience**: less coding concentrate on your goal/concept instead of development complexity.  
**2. Standard**: the code is compiled to standard JS. Fast/optimized, can be used anywhere, reusable in future.  
**3. Less complexity**: code is pre-compiled, no runtime framework issue/dependency, no online build process.  
     - Less Testing-Dependency issues: less unexpected reactions, glitches, slowdowns...happens at runtime.  
     - Less Testing/Errors: due to not having runtime dependencies, or external factors except your own code.  
     
**4. Less Cost**: more human understandable code, more employees can continue the work. + less bugs + less testing + faster development. 
  
***
***
***
  
  
# Extra Information
***
## **Web Development - about definitions**  
▪ Front-end: Web app/site, Develop/Design of client side. HTML5, CSS, JavaScript, PWA, frameworks, Web assembly...  
▪ Back-end: Processing/data on server network, host/cloud, centralized or distributed. SSR(Server Side Rendering). 
▪ DevOps: Admin, analytics, control, process, automation tools.  
▪ Cloud solutions: provides process, memory and ready functions as a service, 
- Cloud services usecase: 1- hosting if you don't have your own server. 2- require API/Apps/services from amazon, google,... 

▪ Svelte Framework: best model to code web, DevExperice+, compiles to JS (less dependencies/overhead).  
▪ Correct development method ⇒ simplify, reuse, secure, update, avoid complex dependencies/overhead.  
▪ Software Engineering:  use engineering principles and process-methods to approach the issue/task.  
▪ Solution Architect: a senior lead/engineer that evalutes an idea/goal/issue, then design, document and execute a structured plan while making many considerations.  

A solution architect has some business insight/strategy and various technical knowledge/experience, using engineering principles, analytics,... design-pattern-process-methodology and some research experience.  
***


## **Web development guideline tips:**  
 **1. Learn the base web standards** -> (HTML, CSS, Javascript) follow/practice tutorials. Make few apps.(ex: Todo)  
 **2. New web standards** -> ES6/next, new HTML, new CSS (grid,...)  practice/try what you learn.  
 **3. Update the previous apps you made**, using new things you learned. make a game and a blog site.  
 **4. Deploy**: learn how to host/deploy your site.  Host on cloudflare pages, deno deploy, begin, netlify, github/gitlab pages,...  
 **5. Learn a Framework**s: Svelte. current best Dev Experience. Light, simple, fast, code compiles to standard JS (not limited).  
 **6. Learn stuff when is required** learn extra stuff afterwards when is needed.(ex: DB, AI, backend, cloud, tools...)  
 **7. Learn Design**: Patterns, tools, UI/UX(user interface/experience). Concepts: visual clarity, visual effects, utility 1st.  
 **8. Responsive design**: native looks, any device, clear focus, usability/accessibility. CSS flex, grid...  
 **9. Backend**: 1. Sveltekit(if using svelte) ___ 2. Deno: new js-runtime replacement for Node.js by its creator.  
 **10.Personal** various experiences, use GIT, github, Make a portfolio site (show case). a social profile: Linkedin + twitter.  
 **11.Summary**: Be an expert in one field, pro on few more, know the rest. Fullstack: Frontend + Backend + Eco-system + Experience.  
 **12.Work**:
- Better: learn neccessary stuff, use best new tech, Exp++, do remote work/freelancing. start a team company.
- Easier: take relevant internship, Exp++, 
- Collaborate: Learn/Use collaboration tools/platforms like GitHub. 
- Job: find a job or startup a new team.  Wish you the best.  


*** 
 
 
## [The Web - status summary]  
The web eco-system was originally made to communicate with text or data, it later evolved to present simple graphics and images.
Afterwards hardware specs advanced, offering high performance and capacity, smartphones appeared, online use-cases and services.  
Therefore all these things affected the web status which became more complex and confusing in the last decade due to workarounds and fixes to support new features by vendor prefixes, 3rd party libs, tools and frameworks to achieve functional demands of dev/user/market. The slow adoption of new trends was caused by issues with backward compatibility of existing sites and old systems while native mobile and desktop platforms had all breaking changes required once a while. By the mean time all these 3rd party libraries, vendor prefixes and frameworks were made to solve/patch the issue and provide features that didn't exist in web standards yet.

Good news, the new web standards are available, evolved and solved issues and included the most wanted features, furthermore Frameworks evolved and new Web APIs provide functionality and access to new technologies. Therefore with much flexibility and compatibility Web can now compete with native desktop and mobile platforms.  

In summary use the main platform itself whenever you can!  some of the old prefixes, 3rd party libs,... are not required anymore...(as explained above) If you are new dev or refreshing your knowledge, be up to date and follow new trends and best practices of time being, not the past... unless required or there is no alternative. The recommended trends mentioned here were handpicked by checking reviews comparison, personal experiments, and what top professionals are using.
***

### New developer or decision maker? 

*"Details of Why you must not choose a tech only by popularity and statistics"*

- Avoid learning ~10+ years old stuff if a better alternative is available.
 old tech was made for past era ecosystem, development model and HW/SW/issues.  

- Is still popular due to seniors who learned it in past when it was a valid option and using it at work for years, later new developers are forced to follow them. This process might repeat multiple times...   

- The old popular tech nature: ___ it works, is popular and has big community and resources, yet in time it becomes more complex, due to extensions, compatibility patches and conflict solving layers to make both the original and new syntax/tools/requirements work together...  Aside of that each time a new feature is added, this process might repeat, and the platform gets large, complex, multiple different revisions.(Ex: MS SDKs, .net framework,...) 

- Breaking changes and migration: ___ when a new feature that contradicts something in the system which can't be solved, the devs will decide to either give up on the feature, add extra flags/configs or make a breaking change, thus you must stay on old branch or learn + update your previous codes or totally migrate if is hopeless.  

- Each time a breaking change shows up, you might need to repeat this process. this makes multiple dev branches in a company if the team can't / won't follow.  

- Issues: older and more different + higher level a platform be, these issues will stack-up, will cost time + resources + paid team to interface them.  

- Lower level coding is not much affected by the mentioned issues. they rarely change, and if so, is about efficiency and stability.  

- As old devs retire,  new ones might add new layers of abstraction instead of fixing the original code, these issues cause
 extra complexity, overhead, extra cost in long-term, Large number/size of files, large developer teams, or slow working pace,...  
***

**Todo**:   remote work, Security, Web API’s, AI/ML.
