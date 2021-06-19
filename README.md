# Perfect-Stack
Best in development stack, trends and best practices for a new developer, software/web development team. 🛠  
In this document we state better choices rather than just what's popular.  

#### A guide about best tech stack, tips, tools and informationton for a new software developer  The information is useful for Web Developers, Designers and Project Managers, startups,...  

## [Quick list]  

- Use new web standards: ES6/next, new HTML, new CSS (Grid, Houdini,...), web components, Web Assembly.  

- **Frameworks >>**
 - **Mobile**: Flutter.  
 - **Front-end**: Svelte(best),  Vue(older, popularity, more jobs)  
 - **Back-end**: 1.Deno.  2.Svelte-kit.  3.Node (KOA, Polka).  
  
- **UI**: ... Mater standard CSS, new Grid and Houdini.  still need it? Tailwind v2.  
- **WebGL 3D**:  Spline,  Babylone.js,  Unity Tiny.
- **Cload platform**:  S: SupaBase    L: Cloadflare  or  Firebase    XL: Amazon AWS  or GCP (Google cload platform).  
- **Host**:  Deno Deploy,  Begin,  Netlify,  vercel,  Firebase.  
- **Static Site Generator**:  Hexo(js), Hugo(go), Eleventy(js), Nikola(py), Svbtle.  
- **Content Management System**:... Strapi, Ghost, Netlify CMS, Apostrophe, Factor(vue).  
- **Dev collaboration Platforms**: Github, Gitpod, Gitlab, notion(paid).  
- **Dev tools**:  CDT, CLI tools, skypack, npm, vs-code, emmet,... search for useful online tools.  
- **Other stuff**:  Bundler: vite, snowpack.  Deno or Tauri for desktop apps.  
***

### **Web Development - about definitions**  
▪ Front-end: Web app/site, Develop/Design of client side. HTML5, CSS, JavaScript, PWA, frameworks, Web assembly...  
▪ Back-end: SSR(Server Side Rendering) development, Processing on server/cload, network. Admin, DevOps, tools, framework.  
▪ Svelte Framework: performance+, DX+, compiles to JS (no FW runtime dependencies, less overhead).  
▪ Correct development method ⇒ simple, secure, reusable, no overhead, less external dependencies.  
▪ Software Engineering: means using engineering principles and process-methods to approach the issue/task.  
▪ Solution Architect: a senior lead/engineer that evalutes an issue/goal/idea, then design, document and execute a complete structured plan while making many considerations. A Solution Architect has some business insight/strategy and much technical knowledge/experience, use engineering principles, or at least good in design-pattern-process-methodology better with some research experience.  
▪ Solution Architect VS Software Engineer: ToDo...
***

## [Advice for new developers in 2020]

People use old/popular tech choices for some reason: as required by jobs, workplace old platforms, learned long ago, using different platforms/hard to update,... but if you're new to dev/web, need a refresh or doing a startup, pick the best tech useful to you at the time being.  
▪ If your main goal is making mobile Apps for Android and IOS, then start with Flutter/dart, is the most cross-platform native SDK, covers all: mobile, web, desktop...  

## **Web design and development tips:**
 **1. Learn the base web standards** -> (HTML, CSS, Javascript) follow/practice tutorials. Make few apps.(ex: Todo)  
 **2. New web standards** -> ES6/next, new HTML, new CSS (grid,...)  practice/try what you learn.  
 **3. Update the previous apps you made**, using new things you learned. make a game and a blog site.  
 **4. Deploy**: learn how to host/deploy your site. make a simple page, host on Netlify, github/gitlab pages, zeit, surge...  
 **5. Learn a Framework**s: Svelte. current best rxperience. Light, simple, fast, code compiles to standard JS (not limited).  
 **6. Learn things if required** learn other tools/libs/platforms afterwards, when needed.(ex: DB, AI, backend, cloud, tools...)  
 **7. Learn Design**: Patterns, tools, UI/UX(user interface/experience). Concepts: visual clarity, visual effects, utility 1st.  
 **8. Responsive design**: native looks, any device, clear focus, usability/accessibility. CSS flex, grid...  
 **9. Backend**: either 1. Sapper(if using svelte) or 2. Deno: new js-runtime replacement for Node.js by its creator.  
 **10.Personal** Experience: Make a portfolio site (products show case). Make profile: CV, Linkedin, twitter.  
 **11.Summary**: Be an expert on one or few fields, pro on few more, know the rest. Fullstack: Frontend+Backend ecosystem.  
**12.Work**: Learn/do remote work/freelancing, or best go for a relevant internship, get experience. Learn/Use collaboration platforms like GitHub/Lab. find a job or startup a new team.  Wish you the best.  

*** 

## **[Top Frameworks]**    
**Mobile development**: Flutter / Dart, the most cross-platform native SDK, covers IOS, Android, web. 
### Frontend: 
 - **1.(Best) ▪ Svelte**: best in total, great for new start or update migration strategy.  
 - **2.(Minimal) ▪ Sinuous**: fast minimal framework. ▪ Mikado: (Minimal/Max speed) virtual-dom framework.  
 - **3.(Job offers, by force/work/ecosystem)**:  **Vue** (popular). ... **Angular / React / .net** (G/FB/MS company-platforms)

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
The web eco-system was originally made to communicate information like simple text or data, it evolved to simple graphical presentation but later hardware and systems evolved with better specifications, and smartphones appeared, therefore the web technology situation became more complex and confusing in last 7 years due to workarounds and fixes to support more new features by vendor prefixes, many 3rd party libs, tools and frameworks to achieve functional demands of dev/user/market. The slow adoption of new trends was caused by issues with backward compatiblity of existing sites and old systems while native mobile and desktop platforms had all breaking changes required once a while. By the mean time all these 3rd party libraries, vendor prefixes and frameworks were made to solve/patch the issue and provide features that didn't exist in web standards yet.
Good news is the new web standards are available now, evolved and solved issues and adopted the most wanted features in time and add ne posibilities, furthermore Frameworks evolvedand new Web APIs provide functionality and access to new technologies. Therefore with much flexiblity and compatiblity Web can now compete with native desktop and mobile platforms.  
In summary you see that old prefixes, 3rd party libs,... are not neccessary anymore, If you are starting development be up to date and follow new trends and best practices of time being, unless required or there be no replacements. The recommended trends mentioned here were handpicked by review, testing and analysis over many criterias.  

**Todo**:  Cloud platform, remote work, Data base, Web API’s, AI/ML / TensorFlow.
