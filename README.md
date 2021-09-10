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
add the fact that each of these people must recommend others, therefore what's most poplular might not be the best option at the time being.

If you're a new developer, updating your skills or planning a startup, your'e not bound to the above conditions, therefore take advice from a top professional or update your base knowledge, check few review comparisons and finally make best decisions which benefit you in long-term.
 *...Web Keyword definitions and more detailed discussion on this topic, at the end of this document...*

#### ▪ Platforms?
- If your are only planning to target mobile Apps for Android and IOS, then start with Flutter/dart, it's a native cross-platform SDK, yet it has basic support for web and desktop... But if you want a more general purpose open platform, covering everything, choose the web platform, and your choice of stack, including capacitor for mobile app development.

#### ▪ Learning tips
- Development is not simple, it takes time, effort and experience to gain practical skill, as there are many things to cover.  
- 1st learn the basics including the new updates. Ex:  in web >> Basics and new additions of JS, HTML, CSS.  
- Learn from best tutorials/courses, search for recent materials from an experienced tutor with high views/stats, Ex: Fireship.io  
- Learn in a group, join friends, divide learning, research,... share the find outs, might even work as team, because it's too much to handle by one person.
  
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

### Cload platforms:  
- Personal : I found Gun.js handy, free, encrypted and distributed(torrent model)
- Small: SupaBase   L: Cloadflare  or  Firebase  
- Enterprise cloud/server:   1.Amazon AWS ...._______... 2.GCP (Google cload platform).  

### Database:
- Personal: Gun.js, is fast, free, simple, encrypted auth and data store.  
- Performance and features: Redis + Redis modules.
- Graph QL: 1- Dgraph  2- Hasura
- Open source, quality and completeness: Arango db.  

### Others:
- **Host**:  Begin,  Deno Deploy,  Netlify,  vercel,  Firebase.  
- **Static Site Generator**:  Astro(js, React, Vue, Svelte), Hugo(go), Hexo(js), Next(react), Nuxt(vue), MkDocs(py)  
- **Content Management System**:... Strapi, Ghost, Netlify CMS, Apostrophe, Factor(vue).  
- **Dev collaboration Platforms**: Github, Gitpod, Gitlab, notion.  
- **Dev tools**:  GIT, CDT, CLI tools, npm, vs-code, emmet, skypack...  
- **Other stuff**: find useful online tools.......Bundler: vite, snowpack......
***

## **Web Development - about definitions**  
▪ Front-end: Web app/site, Develop/Design of client side. HTML5, CSS, JavaScript, PWA, frameworks, Web assembly...  
▪ Back-end: Processing/data on server network, host/cloud, centralized or distributed. SSR(Server Side Rendering). 
▪ DevOps: Admin, analytics, control, process, automation tools.  

▪ Svelte Framework: best model to code web, DevExperice+, compiles to JS (less dependencies/overhead).  
▪ Correct development method ⇒ simple, secure, reusable, less external dependencies/overhead.  
▪ Software Engineering:  use engineering principles and process-methods to approach the issue/task.  
▪ Solution Architect: a senior lead/engineer that evalutes an idea/goal/issue, then design, document and execute a structured plan while making many considerations. 
A solution architect has some business insight/strategy and various technical knowledge/experience, using engineering principles, analytics,... design-pattern-process-methodology and some research experience.  
***



## **[Top Web Frameworks]**    

### Frontend: 
 - **1.(Best overall) ▪Svelte**: best of all, DX, and integration with standards and all. long term strategic choice.  
 - **2.(Minimal)  ▪Solid**: fastest, stable, well developed. ....... ▪**Marko**: solid with better DX. ...... ▪**Sinuous**: best minimal.
 - **3.(Job offers/forced/required)**:  **Vue** (popular). ... **Angular / React / .net** (GG/FB/MS company-platforms)

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
 **10.Personal** Experience: Make a portfolio site (products show case). Build your profile: CV, Linkedin, twitter.  
 **11.Summary**: Be an expert on one or few fields, pro on few more, know the rest. Fullstack: Frontend+Backend ecosystem.  
**12.Work**: Learn/do remote work/freelancing, or best go for a relevant internship, get experience. Learn/Use collaboration platforms like GitHub/Lab. find a job or startup a new team.  Wish you the best.  

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

- Avoid learning ~10+ years old stuff if there is a better alternative.
 old tech was made for past era ecosystem, development model and HW/SW/issues.  

- Is still popular due to seniors who learned it in past when it was a valid option and using it at work for years, and new developers are forced to follow them. This process might repeat multiple times...   

- The old popular tech nature: ___ it works, is popular and has big community and resources, yet in time it becomes more complex, due to extensions, compatibility patches and conflict solving layers to make both the original and new syntax/tools/requirements work together...  Aside of that. Each time a new feature is added, this process might be repeated, and the platform gets large, complex, many different variations.(Ex: MS SDKs, .net framework,...) 

- Breaking changes and migration: ___ when there is a new feature that contradicts something which can't be solved, the devs will decide to either give up on the feature, or make a breaking change which means you must either update previous your previous codes(migration), or stick to the old model/version.  

- Each time a breaking change shows up, you might need to repeat this process. this makes multiple builds in a company if all won't follow the same version.  

- Most cases: Older and more different a platform is, and higher level it be, the issue is seen more often.  

- Lower level coding is not much affected by the mentioned issues. they rarely change, and if so, is about efficiency and stability.  

- As old devs retire,  new ones might add new layers of abstraction instead of fixing the original code, these issues cause
 extra complexity, overhead, extra cost in long-term, Large number/size of files, large developer teams, or slow working pace,...  
***

**Todo**:   remote work, Security, Web API’s, AI/ML / TensorFlow.
