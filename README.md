# Perfect-Stack  🛠i

**About:** an awsome guide of top picks in dev stack, tools, tips, for a Web developer / team. 
This document covers libraries, tech stack, platforms, tools and other information.
Therefore you get informed of best available options rather than just popularity. 

#### Target user:  
This article is useful to Web Developers, Designers, learning devs, startups, all decision makers. 
Feel welcome to contribute, to do an update, improvement, fix a mistake or in case you found a better 
option with clear advantage.




### [Advice for new developers]

- People use old/popular tech choices for some reason: required at workplace, learned in past, following senior's old eco-system,... but if you're a new developer or need a refresh or doing a startup, update your base knowledge and pick the best popular new framework + tools/libs which you need.  *...more detailed discussion at the end of this doc...*

- If your are mainly making mobile Apps for Android and IOS, then start with Flutter/dart, is the most cross-platform native SDK, covers all: mobile, web, desktop... But if you're into web both web and app stuff use capacitor.

### Learning tips
- 1st learn basics well, including new additions. Ex: in web standards>> ES6/next, new HTML, new CSS (Grid, Houdini,...)
- Learn from best tutorials/courses, search based on time and views, choose more recent new materials, from a sharp experienced tutor, Ex: Fireship.io  
  
***

## [Quick list]  

**Frameworks >>**
 - **Mobile**: Flutter(pure native)......Capacitor 3 (Web and native)  
 - **Desktop**:  Deno executable or Tauri.
 - **Front-end**: Svelte(best overall, best DX),  Vue(older, a bit higher popularity and more jobs)  
 - **Back-end**: 1.Deno ___  2.Svelte-kit ___  3.Node (KOA, Polka).  
  
**UI **>>  
- Standard CSS is best... specially when used in modular or component form, such as in svelte
- You might not need libs, frameworks, pre-processors... learn new CSS additions Grid, Houdini...

- yet if you insist:
  - Minimal approachs: (structure)...renderless, headless ui... (UI)...milligram, chota, skeleton...
  - CSS utility fameworks:  Windi CSS - Tailwind v2
  - UI-Kits: (semi/fully made components) Bootstrap, Bulma, Kahi UI, or other ui-kits of your liking.

- **WebGL 3D**:  Spline,  Babylone.js,  Unity Tiny.
- **Cload platform**:  S: SupaBase   L: Cloadflare  or  Firebase    XL: Amazon AWS  or GCP (Google cload platform).  
- **Host**:  Begin,  Deno Deploy,  Netlify,  vercel,  Firebase.  
- **Static Site Generator**:  Astro(js, React, Vue, Svelte), Hugo(go), Hexo(js), Next(react), Nuxt(vue), MkDocs(py)  
- **Content Management System**:... Strapi, Ghost, Netlify CMS, Apostrophe, Factor(vue).  
- **Dev collaboration Platforms**: Github, Gitpod, Gitlab, notion.  
- **Dev tools**:  GIT, CDT, CLI tools, npm, vs-code, emmet, skypack...  
- **Other stuff**: find useful online tools.......Bundler: vite, snowpack......
***

## **Web Development - about definitions**  
▪ Front-end: Web app/site, Develop/Design of client side. HTML5, CSS, JavaScript, PWA, frameworks, Web assembly...  
▪ Back-end: Processing/data on server network, host/cloud, centralised or distributed. SSR(Server Side Rendering). 
▪ DevOps: Admin, analytics, control, process, automation tools.  

▪ Svelte Framework: best model to code web, DevExperice+, compiles to JS (less dependencies/overhead).  
▪ Correct development method ⇒ simple, secure, reusable, less external dependencies/overhead.  
▪ Software Engineering:  use engineering principles and process-methods to approach the issue/task.  
▪ Solution Architect: a senior lead/engineer that evalutes an idea/goal/issue, then design, document and execute a structured plan while making many considerations. 
A solution architect has some business insight/strategy and various technical knowledge/experience, using engineering principles, analytics,... design-pattern-process-methodology and some research experience.  
***



## **Web design and development tips:**
 **1. Learn the base web standards** -> (HTML, CSS, Javascript) follow/practice tutorials. Make few apps.(ex: Todo)  
 **2. New web standards** -> ES6/next, new HTML, new CSS (grid,...)  practice/try what you learn.  
 **3. Update the previous apps you made**, using new things you learned. make a game and a blog site.  
 **4. Deploy**: learn how to host/deploy your site.  Host on cloudflare pages, deno deploy, begin, netlify, github/gitlab pages,...  
 **5. Learn a Framework**s: Svelte. current best Dev Experience. Light, simple, fast, code compiles to standard JS (not limited).  
 **6. Learn stuff when is required** learn extra stuff afterwards when is needed.(ex: DB, AI, backend, cloud, tools...)  
 **7. Learn Design**: Patterns, tools, UI/UX(user interface/experience). Concepts: visual clarity, visual effects, utility 1st.  
 **8. Responsive design**: native looks, any device, clear focus, usability/accessibility. CSS flex, grid...  
 **9. Backend**: 1. Sveltekit(if using svelte) ___ 2. Deno: new js-runtime replacement for Node.js by its creator.  
 **10.Personal** Experience: Make a portfolio site (products show case). Build your profile: CV, Linkedin, twitter.  
 **11.Summary**: Be an expert on one or few fields, pro on few more, know the rest. Fullstack: Frontend+Backend ecosystem.  
**12.Work**: Learn/do remote work/freelancing, or best go for a relevant internship, get experience. Learn/Use collaboration platforms like GitHub/Lab. find a job or startup a new team.  Wish you the best.  

*** 

## **[Top Frameworks]**    
**Mobile development**: Flutter / Dart, the most cross-platform native SDK, covers IOS, Android, web. 
### Frontend: 
 - **1.(Best) ▪ Svelte**: best in total, great for new start or update migration strategy.  
 - **2.(Minimal) ▪ Sinuous**: fast & good design.  ▪ Solid: fast & stable  ▪ Mikado: virtual-dom processing performance.  
 - **3.(Job offers, by force/requirements)**:  **Vue** (popular). ... **Angular / React / .net** (G/FB/MS company-platforms)

### Backend :
**1. Deno**: a runtime built by the creator of node.js, it is great, secure by default, lighter, faster, Wasm, latest tech.  
**2. Sveltekit**: if you are using svelte.  **Snel**: Svelte project built and compiled on deno eco-system.  
**3. Node.js**: in case you want most available libs, support, compatiblity.  Koa is a good node.js framework.  
  
### Svelte framework offers:  
**1. Developer Experience**: less coding concentrate on your goal/concept instead of development complexity.  
**2. Standard**: the code is compiled to standard JS. Fast/optimised, can be used anywhere, reusable in future.  
**3. Less complexity**: code is pre-compiled, no runtime framework issue/dependency, no online build process.  
     - Less Testing-Dependency issues: less unexpected reactions, glitches, slowdowns...happens at runtime.  
     - Less Testing/Errors: due to not having runtime dependancies, or external factors except your own code.  
     
**4. Less Cost**: more human understandable code, more employees can continue the work. + less bugs + less testing + faster development.  ***  
  
  
## [The Web - status summary]  
The web eco-system was originally made to communicate with text or data, it later evolved to present simple graphics and images.
Afterwards hardware specs advanced, offering high performnce and capacity, smartphones appeared, online usecases and services multiplied.  
Therefore all these things affected the web status which became more complex and confusing in the last decade due to workarounds and fixes to support new features by vendor prefixes, 3rd party libs, tools and frameworks to achieve functional demands of dev/user/market. The slow adoption of new trends was caused by issues with backward compatiblity of existing sites and old systems while native mobile and desktop platforms had all breaking changes required once a while. By the mean time all these 3rd party libraries, vendor prefixes and frameworks were made to solve/patch the issue and provide features that didn't exist in web standards yet.
Good news is the new web standards are available now, evolved and solved issues and adopted the most wanted features in time and add ne posibilities, furthermore Frameworks evolvedand new Web APIs provide functionality and access to new technologies. Therefore with much flexiblity and compatiblity Web can now compete with native desktop and mobile platforms.  
In summary use the main platform itself whenever you can!  some of the old prefixes, 3rd party libs,... are not neccessary anymore...(as explained above) If you are new dev or refreshing your knowledge, be up to date and follow new trends and best practices of time being, not the past... unless required or there is no alternative. The recommended trends mentioned here were handpicked by review, testing and analysis over many criterias.  


### New developer or decision maker? and why you must avoid popular old tech.

- Avoid learning ~10+ years old model if possible and there is a better alternative.
 old tech was made for past era ecosystem, development model and HW/SW/problems.
- Is still popular due to seniors who learned it in past when it was a valid option and using it at work for years, and new developers are forced to follow them. This process might repeat multiple times...   
- The old popular tech nature: ___ it works, is popular and has big community and resources, yet is=n time it became complex and heavy, due to extentions, compatibility patches and extra layers to make it work with original and new tools or requirements, yet it must keep things compatible with old syntax and system model.  Each time a new feature is added, 100s of changes are involved to the tech code base.
- Breaking changes and migration: ___ when there is a new feature that contradicts something which can't be solved, the devs will decide to either giveup on the feature, or make a breaking change which means you must either update previous your previous codes(migration), or stick to the old model/version.
- Each time a breaking change shows up, you might need to repeat this process. this makes multiple builds in a company if all won't follow the same version.
- Most cases: Older and more different a platform is, and higher level it be, the issue is seen more often. 
- Lower level coding is less/not affected by these isssues. Ex: C programming language is old and rarely seen changes at all, it works well.
- As old devs retire,  new ones might add new layers of abstraction instead of fixing the original code, these issues cause
 extra complexity, overhead, extra cost in long-term, Large number/size of files, large developer teams, or slow working pace,...  


**Todo**:  Cloud platform, remote work, Database, Security, Web API’s, AI/ML / TensorFlow.
