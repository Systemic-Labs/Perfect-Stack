# [Perfect-Stack](#perfect-stack--i)  🛠i


### A development guide and an `awesome-list` of recommendations.  

>- This document covers information for best practices, libs, tech stack, platforms, tools,...  
>- Decide on best available options for the use-case rather than just popularity.  
>- Welcome to contribute, suggest an update, recommend better options for a review comparison.   
>- Target users:  *developers, designers, researchers, students, startups, and decision makers*.  
> 
>> -[ Awesome list](#awesome-list)  
   -[ Frameworks - more info/details](#frameworks-information)  
   -[ Extra information and discussion](#extra-information)  

***
▪    
### [To beginners and startups](#to-beginners-and-startups)

> Most developers use popular yet not the best development trends, either due to Job/workplace skill requirements, online article or a senior's advice, which might been the best choice in the past, but a new learner adopting outdated practices is wrong, this cycle repeats few times in many years and old tech and practices get stuck in job/edu systems, therefore instead of choosing only based on poplularity, make decisions which solves the problem in the best way, mostly if you're a new developer or planning a startup, you're not bounded to  specific conditions or eco-system, therefore do your own research, check review comparisons, and finally make decision which benefit you in long-term.  
- [*...Information details, definitions and extra discussion on this topic...*](#new-developer-or-decision-maker)  

 ***

#### Which Platforms?
> Targeting only mobile devices and native functions/apps => use Flutter(cross platform), or any native SDKs of the device...  
> But if your target is cross-platform or web based, then use the web dev and mobile sdk's as required such as Tauri, or "Capacitor" for web, mobile, desktop development.  
  
  
#### Learning tips
> Development is not easy, it takes time, effort, practice and experience to gain real skills, as there are many things to cover.  
> 1st learn the basics including the new updates. Ex:  for web >> Basics and new additions of JS, HTML, CSS. [Web-Dev guideline](#web-development-guideline-tips)  
  
> Learn from best tutorials/courses, search for recent materials from an experienced tutor with high views/stats, Ex: Fireship.io  
> Make a group, join friends, divide tasks/learning, share your findouts, work as a team,... is too much to handle by only one person.

***
  
# [Awesome list]  

### [Frameworks](#frameworks--)  >>
 - **`Mobile`**: Flutter(pure native)......Capacitor 3 (android, ios... but under web development)  
 - **`Desktop`**:  Tauri (Web App),  Deno executable(Web/CLI).  
 - **`Front-end`**: Svelte(best overall, best DX),  Vue(older, a bit more popular, more jobs).  
 - **`Back-end`**: -Deno/Bun.js ___  -Svelte-kit(svelte.js) ___  -Node.js(KOA, Polka, nest).  
 - **`Programming Languages`**:  Rust, Go, Nim, Dart, Swift... - (each specific use-case, SSP, Backend, Mobile).  
  
### [UI](#ui-) >>  
**`Standard CSS`**:
>
 - when more control, precision and customization or zero dependency is required.   
 - new CSS standards solve much issuess developers had in the past.  
 - recommended for: small projects and teams, in any case you must master it to use libs effectively.  
 
 **`UI Lib/kit`** - main advantages* >> less text instructions(+readability), uniform design model in team, faster development and prototyping, tools automation.  
 
 ### [UI categories](#ui-categories)
 
  - **`UI Structure`** (minimal): renderless, headless ui.......  
  - **`CSS UI Libs`**: pico css, milligram, DaisyUI.  
  
  - **`CSS toolkit`**:  UnoCSS - compiles other CSS frameworks into standard CSS.  
  - **`UI-Kits`**: Daisy UI(CSS) .... fully functional components:  Skeleton, flowbite...  
  - **`3D (WebGL/GPU)`**:  Spline, Babylone.js, Three.js(lower level), Threlte(Svelte+three), Unity Tiny.  
  
  
 ### [UI Recommendations](#ui-recommendations--reason) + `reason`:
 - `UnoCSS`  - best toolset for available lib presets, use your Lib instructions yet behaves as standard CSS.  
 - `picoCSS` - best for predefined styling of standard HTML Tags.  
 - `DaisyUI` - best a CSS UI lib can achieve without using JS or being a components kit.  
 - `Skeleton`- best UI components Kit for Svelte fraamework.  
 


### [Cloud platforms](#cloud-platforms):  
- `Free Personal`: Gun.js, free, encrypted, serverless and distributed(web torrent).  
- `Cloudflare`: best business class option, performant, advanced networking platform and services.  
- `Hosting clouds`:  more of a hosting platform yet offer some cloud functions, such as Vercel, Netlify...  
- `Enterprise` (cloud functions server):  1. Amazon AWS ..... 2. Firebase (Google) ..... 3. Azure (Microsoft)  
- `Alternatives`: web based-> Vercel, simple cloud-> Supabase,  Self hosted-> PocketBase.  
- `Redis`: in case redis modules and cloud services are required, a complete customizable database solution.  


### [Database](#database):
- `Personal`: Gun.js, is fast, free, simple, encrypted, auth with a semi graphQL data store.  
- `Performance` and features: Redis + Redis modules.  
- `Innovative`: (graphQLish+DX): - EdgeDB  - Dgraph - SurrealDB  
- `Open Source`: Arango DB,  multi-model solution for self hosted open source local server setup.
- `Recommendation` >> **` EdgeDB `**  


### [Other stuff](#other-stuff):
- **`Programming Languages`**:
  - **(Low level)**: 
      - **`C++ alternatives`** -> `Carbon`, `Zig`,  `Nim` (easy/semi python syntax)  
      - **`Rust`**: Web std / Safe / Precise / System / Performance / by Mozilla / support.  
- **(High level)**: ▪ **Platforms ecosystem**: JS/ESNext, Python, Swift, Dart  
- **`Hosting`**: .. Vercel, Cloudflare Pages, Deno Deploy, Begin, Netlify.  
- **`Static Site Generator`**: .. Astro(js, React, Vue, Svelte), Hugo(go), Hexo(js), Next(react), Nuxt(vue), MkDocs(py)  
- **`Content Management System`**: .. Primo(svelte), Strapi, Ghost, Netlify CMS, Apostrophe, Factor(vue).  
- **`Dev/Repo/Collab` Platforms**: Github, Gitpod, Gitlab, notion.  
- **`Dev tools`**:  CLI tools(GIT, bash, npm...), vs-code, emmet, skypack...  
- **`Other stuff`**: find useful online tools, use bundlers: vite, snowpack......  
***
  
## [Frameworks information](#frameworks-information)  

### Frontend:  
 - **1. `Svelte`**: (Best overall), DX+, integrates and compiles to standard web, long term strategic choice.  
 - **2. `Solid`**: (Minimal), fast, efficient, reliable, fine tuned core structure, migration choice for react developers.  
 - **3. `Vue`**: (popular). ....  Angular / React / .net** (GG/FB/MS company platforms, Job offers/forced/required).  
  
  
### Backend:

#### JavaScript Runtimes:  
** > `Deno.js`**: by creator of node.js, secure by default, lighter, faster, Wasm, better concept, DX+.  
** > `Node.js`**:  most libs, support, popular eco-system. -- **Bun.js**: Node.js compatible but higher performance.  

### Fullstack frameworks: 
**`Sveltekit`**: current recommendation due to the fact it's strong on both frontend and backend.  
 > A complete web/app framework, scalable, stable release of latest innovations in web ecosystem.  

**`Node.js frameworks`**:  Next(Vercel, React), Nuxt(VUE), Astro(multi platform), JS(polka, koa).  

**`Python eco-system`**:  jobs, popularity, AI libs, ease of usage, beginners, resources...  

  
### [Svelte framework pros](#svelte-framework-pros):  
**1. `Developer Experience`**: write less code, concentrate on your ideas, not development complexity.  
**2. `Standard`**: the code is compiled to standard JS. Fast/optimized, can be used anywhere, reusable.  
**3. `Less complexity`**: easier to read code, compiled and no online build process, no framework issues at runtime.  
     - Less Testing/Dependency issues:  unexpected reactions, conflicts, misunderstanding source of issues.  
     - Less Errors: due to not having runtime dependencies, or external factors except your own code.  
**4. `Less Cost`**: easier to read code of other devs => continue their work + less bugs + less testing + faster development.  
**5. `Smaller bundle size`** (Compiled), without virtual-dom and framework overhead...  

***
***
***
  
  
# [Extra Information](#extra-information)  
***
## **Web Development - about definitions**   
▪ `Front-end`: Web app/site, Develop/Design of client side. HTML5, CSS, JavaScript, PWA, frameworks, Web assembly...  
▪ `Back-end`: Processing/data on server network, host/cloud, centralized or distributed. SSR(Server Side Rendering). 
▪ `DevOps`: Admin, analytics, control, process, automation tools.  
▪ `Cloud solutions`: provides process, memory and ready functions as a service.  
- `Cloud services` usecase: 1- hosting if you don't have your own server. 2- require API/Apps/services from amazon, google,... 

▪ `Svelte Framework`: best way to code web, DevExperice+, compiles to JS (less dependencies/overhead).  
▪ `Correct development method` ⇒ simplify, reuse, secure, update, avoid complex dependencies/overhead.  
▪ `Software Engineering`:  use engineering principles and process-methods to approach the issue/task.  
▪ `Solution Architect`: a senior lead/engineer that evalutes an idea/goal/issue, then design, document and execute a structured plan while making many considerations.  

A solution architect has some business insight/strategy and various technical knowledge/experience, using engineering principles, analytics,... design-pattern-process-methodology and some research experience.  
***


## **[Web development guideline tips](web-development-guideline-tips):**  
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
 
 
## [The Web - status summary](#the-web-status-summary)
The web was originally made to communicate with text and data, it later evolved to present simple graphics and images.
Hardware advancements in performance and capacity, plus emerging smartphones and social networks caused web based online services go mainstream in network communications, it progressed fast and competes with native platforms.  
The sudden progress pace in contrast with the concept of keeping it backward compatible with legacy standards, caused some complexity and confusion in the last decade due to workarounds to support new features by vendor prefixes, various 3rd party libs, tools and frameworks to achieve demands of dev/user/market. The slow adoption of new trends was caused by issues with backward compatibility of existing sites and old systems while native mobile and desktop platforms had all breaking changes at once to support new hardware. By then 3rd party libs, prefixes and frameworks... were made to solve/patch the issue and provide features that didn't exist in web standards yet.

Good news, the new web standards and innovations, improved the situation, furthermore Frameworks evolved and matured including new Web APIs to provide functionality and access to new technologies. Therefore with much flexibility, compatibility and openness, Web eco-system can now compete with native desktop and mobile platforms.  

Whenever learning something new, adopt the new web standards and best practices, some of the old prefixes, 3rd party libs,... are not required anymore...(as explained above) unless required or there is no alternative. The recommended trends mentioned here were handpicked by checking reviews comparison, personal experiments, and by looking into new trends top professionals adopt.
***

### [New developer or decision maker?](#new-developer-or-decision-make?)

*"Details of Why you must not choose a tech only by popularity and general statistics"*

- Avoid learning ~10+ years old stuff if a better alternative is available.
 old tech was made for past era ecosystem, development model and HW/SW/issues.  

- Is still popular due to seniors who learned it in past when it was a valid option and using it at work for years, later new developers are forced to follow them. This process might repeat multiple times...   

- The old popular tech nature: ___ it works, is popular and has big community and resources, yet in time it becomes more complex, due to extensions, compatibility patches and conflict solving layers to make both the original and new syntax/tools/requirements work together...  Aside of that each time a new feature is added, this process might repeat, and the platform gets large, complex, multiple different revisions.(Ex: MS SDKs, .net framework,...)  

- Breaking changes and migration: ___ when a new feature that contradicts something in the system which can't be solved, the devs will decide to either give up on the feature, add extra flags/configs or make a breaking change, thus you must stay on old branch or learn + update your previous codes or totally migrate if is hopeless.  

- Each time a breaking change shows up, you might need to repeat this process. this makes multiple dev branches in a company if the team can't / won't follow.  

- Issues:  an old legacy target which depends on layers of other legacy tech, will encounter conflicts, comptiblity, deprecated dependencies, which will cost time + resources + man power to solve them. 

- Lower level coding is not much affected by the mentioned issues. they rarely change, and if so, is about efficiency and stability.  

- As old devs retire,  new ones might add new layers of abstraction instead of fixing the original code, these issues cause
 extra complexity, overhead, extra cost in long-term, Large number/size of files, large developer teams, or slow working pace,...  
***

**Todo**:   remote work, Security, Web API’s, AI/ML.
