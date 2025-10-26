# Next.js Interview Preparation Guide
*Essential Next.js Concepts for React Developers*

**For Students:**  
This guide assumes you already know React.  
It’s designed for developers who want to transition smoothly into **Next.js** and prepare for real-world **Next.js interviews**.

---

## Structure

- **Part 1** — Read-Aloud Interview Questions (concept + how to answer)  
- **Part 2** — Quick-Reference Questions  

---

## 📘 Table of Contents

### Part 1: Read-Aloud Interview Questions

#### 🧩 Next.js Fundamentals
1. [What is Next.js?](#q1-what-is-nextjs) *(Document2)*
2. [How does Next.js work?](#q2-how-nextjs-works) *(Document1)*
3. [Key features of Next.js](#q3-key-features-of-nextjs) *(Document2)*
4. [Next.js vs React.js](#q4-nextjs-vs-reactjs) *(Document1)*
5. [What is File-Based Routing in Next.js?](#q5-file-based-routing-in-nextjs) *(Document2)*
6. [What is the difference between client-side and server-side rendering?](#q6-client-vs-server-rendering) *(Document1)*

#### ⚙️ Rendering & Data Fetching
7. [What is Server-Side Rendering (SSR)?](#q7-ssr) *(Document1)*
8. [What is Static Site Generation (SSG)?](#q8-ssg) *(Document2)*
9. [What is Incremental Static Regeneration (ISR)?](#q9-isr) *(Document2)*
10. [Difference between SSR, SSG, and CSR](#q10-difference-between-rendering-types) *(Combined)*
11. [What are getStaticProps and getServerSideProps?](#q11-getstaticprops-and-getserversideprops) *(Document1)*
12. [When to use getStaticProps vs getServerSideProps](#q12-when-to-use-getstaticprops-vs-getserversideprops) *(Document1)*
13. [What is getStaticPaths?](#q13-getstaticpaths) *(Document1)*
14. [How to fetch data in Next.js?](#q14-how-to-fetch-data-in-nextjs) *(Document2)*

#### 🧭 Routing & Navigation
15. [What is the Link component in Next.js?](#q15-what-is-the-link-component-in-nextjs) *(Document2)*
16. [What is the useRouter hook in Next.js?](#q16-what-is-the-userouter-hook-in-nextjs) *(Document2)*
17. [Programmatic Navigation in Next.js](#q17-programmatic-navigation-in-nextjs) *(Document1)*
18. [What is Dynamic Routing in Next.js?](#q18-what-is-dynamic-routing-in-nextjs) *(Document1)*
19. [What are redirects and rewrites in Next.js?](#q19-what-are-redirects-and-rewrites-in-nextjs) *(Document1)*
20. [What is Prefetching in Next.js?](#q20-what-is-prefetching-in-nextjs) *(Document1)*

#### 🎨 Styling & Components
21. [What is Styled JSX in Next.js?](#q21-what-is-styled-jsx-in-nextjs) *(Document1)*
22. [How do you use CSS Modules or Tailwind in Next.js?](#q22-how-do-you-use-css-modules-or-tailwind-in-nextjs) *(Document2)*
23. [What is the Image Component and Image Optimization in Next.js?](#q23-what-is-the-image-component-and-image-optimization-in-nextjs) *(Document1)*
24. [How to add global and component-level CSS in Next.js?](#q24-how-to-add-global-and-component-level-css-in-nextjs) *(Document2)*

#### ⚙️ Configuration & Environment
25. [What is next.config.js and what does it do?](#q25-what-is-nextconfigjs-and-what-does-it-do) *(Document2)*
26. [What is the purpose of publicRuntimeConfig and serverRuntimeConfig?](#q26-what-is-the-purpose-of-publicruntimeconfig-and-serverruntimeconfig) *(Document1)*
27. [What are Environment Variables in Next.js?](#q27-what-are-environment-variables-in-nextjs) *(Document1)*
28. [How do you add custom headers in Next.js?](#q28-how-do-you-add-custom-headers-in-nextjs) *(Document2)*
29. [What is the experimental property in next.config.js?](#q29-what-is-the-experimental-property-in-nextconfigjs) *(Document1)*

#### 🚀 Deployment & Optimization
30. [How do you deploy a Next.js application?](#q30-how-do-you-deploy-a-nextjs-application) *(Document1)*
31. [What is Serverless Deployment in Next.js?](#q31-what-is-serverless-deployment-in-nextjs) *(Document1)*
32. [How can you optimize performance in Next.js?](#q32-how-can-you-optimize-performance-in-nextjs) *(Document1)*

#### 🧠 Advanced Concepts
33. [What is Middleware in Next.js?](#q33-what-is-middleware-in-nextjs) *(Document2)*
34. [What is App Router vs Pages Router?](#q34-what-is-app-router-vs-pages-router) *(Document2)*
35. [What are Layouts and Templates in App Router?](#q35-what-are-layouts-and-templates-in-app-router) *(Document1)*
36. [What is the use of the _app.js and _document.js files?](#q36-what-is-the-use-of-the-_appjs-and-_documentjs-files) *(Document2)*
37. [How do you implement authentication in Next.js?](#q37-how-do-you-implement-authentication-in-nextjs) *(Document1)*
38. [What are React Server Components (RSC) in Next.js?](#q38-what-are-react-server-components-rsc-in-nextjs) *(Document2)*

#### 🧩 Error Handling & Debugging
39. [What are _error.js and 404.js used for?](#q39-what-are-_errorjs-and-404js-used-for) *(Document1)*
40. [How do you implement custom error boundaries?](#q40-how-do-you-implement-custom-error-boundaries) *(Document1)*
41. [Best practices for debugging and testing Next.js apps](#q41-best-practices-for-debugging-and-testing-nextjs-apps) *(Document1)*

---

## Part 1: Read-Aloud Interview Questions

### Q1: What is Next.js?
Next.js is a React framework that helps you build fast, scalable, and SEO-friendly (Search Engine Optimization) web applications.
It improves performance by:

Using SSR (Server-Side Rendering) – pages are generated on the server before being sent to the browser, so they load faster and are better for SEO.

Using SSG (Static Site Generation) – pages are pre-built at build time and served instantly to users, making websites even faster.
It also provides built-in routing, API routes for backend logic, and automatic code optimization — all in one framework that supports both frontend and backend development.

---

### Q2: How does Next.js work?
Next.js works as a React framework that handles rendering, routing, and optimization automatically, making web apps faster and SEO-friendly.

Pre-rendering: Pages can be rendered on the server (SSR) or per-rendered at build time (SSG) for faster load and better SEO.
Routing: File-based routing automatically maps pages to URLs.
API Routes: Allows backend functionality within the application. Each file inside pages/api/ automatically becomes an API endpoint.
Automatic Code Splitting: Loads only the necessary JavaScript for each page, improving performance.
Optimized Builds: Bundling, minification, and image optimization happen out-of-the-box.
Easy Deployment: Supports multiple deployment options like static site hosting and serverless functions, simplifying the release process.

Client Request
       │
       ▼
  Next.js Server
       │
       ▼
   ┌────────────┐
   │ Route Type │
   └─────┬──────┘
         │
   ┌─────┴──────┐
   │            │
Dynamic       Static
   │            │
   ▼            ▼
Server       Static
Runtime       Page
   │            │
   ▼            │
Generate HTML   │
   │            │
   └──────┬─────┘
          ▼
     Sent To Client
          │
          ▼
 Hydration (React attaches event listeners and makes the static HTML interactive)
          │
          ▼
     Interactive Page



---

### Q3: Key features of Next.js
1. Server-Side Rendering (SSR) –
Next.js can render pages on the server before sending them to the browser, which makes the app load faster and improves Search Engine Optimization (SEO).

2. Static Site Generation (SSG) –
Next.js can pre-build pages at build time, so they load instantly for users. This is great for blogs, portfolios, or e-commerce sites where content doesn’t change often.

3. API Routes –
You can create backend APIs directly inside your Next.js project without needing a separate server — perfect for full-stack apps.

4. File-Based Routing –
Next.js automatically creates routes based on the files in your pages/ folder — no need to manually set up routing.

5. Client-Side Rendering (CSR) –
It also supports normal React-style rendering, where the browser loads the page and fetches data dynamically.

6. Incremental Static Regeneration (ISR) –
Next.js lets you update static pages automatically after deployment, so your content stays fresh without rebuilding the whole site.

7. Image Optimization –
Next.js comes with built-in image optimization, which automatically resizes and compresses images for faster page loading.

8. Automatic Code Splitting –
It splits your code into smaller parts so only the necessary code is loaded per page — improving performance.

9. TypeScript Support –
Next.js has native TypeScript support, making it easier to write type-safe and reliable code.

10. Fast Refresh –
It provides instant updates while coding, so you can see changes immediately without losing component state.

---

### Q4: Next.js vs React.js
| **Feature**                          | **Next.js**                                                                                                                                                | **React.js**                                                               |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Type**                             | A **framework** built on top of React                                                                                                                      | A **JavaScript library** for building UI components                        |
| **Rendering Methods**                | Supports **SSR (Server-Side Rendering)**, **SSG (Static Site Generation)**, **ISR (Incremental Static Regeneration)**, and **CSR (Client-Side Rendering)** | Supports only **CSR (Client-Side Rendering)** by default                   |
| **Routing**                          | Uses **File-based Routing** (automatic routes from `pages/` folder)                                                                                        | Requires manual setup using **React Router** or other libraries            |
| **API Handling**                     | Built-in **API Routes** to create backend endpoints                                                                                                        | Needs a separate backend or API setup                                      |
| **SEO (Search Engine Optimization)** | Excellent SEO because of server-side and static rendering                                                                                                  | Limited SEO as content is loaded on the client side                        |
| **Image Optimization**               | Built-in **Image Optimization** with automatic resizing and lazy loading                                                                                   | No built-in optimization (manual handling or external libraries needed)    |
| **Code Splitting**                   | **Automatic** per-page code splitting                                                                                                                      | Requires manual configuration or dynamic imports                           |
| **Setup & Configuration**            | **Ready-to-use** setup with optimized defaults                                                                                                             | **Manual setup** needed for tools like Webpack, Babel, etc.                |
| **Performance**                      | Generally faster due to SSR, SSG, and optimization features                                                                                                | Depends on client-side rendering; might be slower initially                |
| **TypeScript Support**               | Built-in TypeScript support                                                                                                                                | TypeScript setup must be configured manually                               |
| **Deployment**                       | Easy deployment with **Vercel** (officially supported)                                                                                                     | Requires custom configuration for hosting/deployment                       |
| **Learning Curve**                   | Slightly steeper since it adds extra concepts like SSR and SSG                                                                                             | Easier to start as it’s purely frontend-focused                            |
| **Use Case**                         | Best for **production-grade**, **SEO-friendly**, or **full-stack** apps                                                                                    | Best for **single-page applications (SPAs)** or **frontend-only** projects |


---

### Q5: What is File-Based Routing in Next.js?
File-Based Routing in Next.js
is a routing system where the structure of files and folders inside the pages/ directory automatically defines the routes of the application. Each file corresponds to a specific route, and folders represent nested routes. This eliminates the need for external routing libraries like React Router, making navigation simple and intuitive.

Example:

pages/index.js → /
pages/about.js → /about
pages/blog/[id].js → /blog/:id (dynamic route)

In short:
File-based routing allows developers to create pages just by adding files — Next.js automatically maps them to routes.

---

### Q6: What is the difference between client-side and server-side rendering?
| **Aspect**                           | **Client-Side Rendering (CSR)**                                        | **Server-Side Rendering (SSR)**                                    |
| ------------------------------------ | ---------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **Where rendering happens**          | In the **browser (client)**                                            | On the **server** before sending to the browser                    |
| **Initial Load Speed**               | **Slower**, as the browser must download JavaScript and render content | **Faster**, as the HTML is pre-rendered and sent directly          |
| **Subsequent Navigation**            | **Faster**, because pages update without full reloads                  | May be **slightly slower** since the server processes each request |
| **SEO (Search Engine Optimization)** | **Not ideal**, as content is loaded via JavaScript after page load     | **Excellent**, since full HTML is available for search engines     |
| **Data Fetching**                    | Data is fetched **after** the page loads (on client side)              | Data is fetched **before** sending the page to the user            |
| **User Experience**                  | May show a blank or loading screen initially                           | Page appears complete immediately when loaded                      |
| **Server Load**                      | **Low**, since most work is done by the browser                        | **High**, as the server renders pages for every request            |
| **Use Case**                         | Best for **single-page apps (SPAs)** and **dashboards**                | Best for **SEO-focused websites** and **content-heavy apps**       |
| **Example Frameworks**               | React, Vue.js (default)                                                | Next.js, Nuxt.js, Remix                                            |


In short:

CSR: The browser builds the page — faster updates, but slower first load and weaker SEO.
SSR: The server builds the page — faster first load and better SEO, but higher server load.

---

### Q7: What is Server-Side Rendering (SSR)?
SSR stands for Server-Side Rendering, a technique where the server generates the full HTML of a page before sending it to the client. Key points:

Request from Client: The user requests a web page from the server.
Server-Side Processing: The server executes the JavaScript code, fetches data if needed, and renders the complete HTML.
Sending Rendered HTML to Client: The fully rendered HTML, along with necessary CSS and JavaScript, is sent to the browser.
Client-Side Hydration: Once the HTML is received, JavaScript runs to enable interactive elements on the client.


---

### Q8: What is Static Site Generation (SSG)?

Static Generation means creating the page’s HTML in advance during the build process,  
not when a user visits the page. This makes the page load very fast because it’s already pre-built.

---

#### 💻 Example Code:
```
export async function getStaticProps() {
  const res = await fetch("https://api.github.com/repos/vercel/next.js");
  const repo = await res.json();
  return { props: { repo } };
}

export default function Page({ repo }) {
  return <p>{repo.stargazers_count} Stars</p>;
}
```
---

### Q9: What is Incremental Static Regeneration (ISR)?
Incremental Static Regeneration (ISR) is a feature in Next.js that lets you update static pages after the site is built, without rebuilding the whole website. It works by automatically refreshing and updating pages in the background, so users always see the latest content.

```
export async function getStaticProps() {
  const res = await fetch("https://api.github.com/repos/vercel/next.js");
  const repo = await res.json();

  return {
    props: { stars: repo.stargazers_count },
    revalidate: 10, // Regenerate the page every 10 seconds
  };
}

export default function Page({ stars }) {
  return <p>Next.js has ⭐ {stars} stars on GitHub.</p>;
}


```

🧠 How it Works
The page is statically generated at first build.

When someone visits after 10 seconds, Next.js regenerates the page in the background.

The next user automatically sees the updated version — without any downtime.



---

### Q10: What is SSG
Static Site Generation (SSG) is a feature in Next.js that pre-renders pages at build time.
This means Next.js creates the HTML for each page in advance — not when a user visits the site.
Because the pages are already built, they load very fast and are great for SEO.

💡 In Simple Words:

Next.js builds the page once → saves it as a ready-to-serve HTML file → shows it instantly to every visitor.

```
export async function getStaticProps() {
  const res = await fetch("https://api.example.com/posts");
  const posts = await res.json();

  return {
    props: { posts }, // Pass data to the page
  };
}

export default function Blog({ posts }) {
  return (
    <div>
      <h1>Blog Posts</h1>
      <ul>
        {posts.map((post) => (
          <li key={post.id}>{post.title}</li>
        ))}
      </ul>
    </div>
  );
}

```

⚙️ How it Works

The page HTML is generated at build time.
When users visit the site, the pre-built HTML is served instantly (no waiting).
Perfect for blogs, portfolios, or marketing websites where content doesn’t change often.

---

### Q11: What are getStaticProps and getServerSideProps?
🧩 Definition
In Next.js, both getStaticProps and getServerSideProps are data fetching methods used to load data before a page is rendered — but they work in different ways.

⚙️ 1. getStaticProps (Static Site Generation - SSG)

Used to fetch data at build time.

The page is pre-rendered as static HTML during the build process.

Ideal for pages where the data doesn’t change often (like blogs or product pages).

Key Point: Runs once at build time, not on every request.

Example:

```
export async function getStaticProps() {
  const res = await fetch("https://api.example.com/posts");
  const posts = await res.json();

  return {
    props: { posts }, // passed to the page component
  };
}

export default function Blog({ posts }) {
  return (
    <div>
      <h1>Blog Posts</h1>
      {posts.map((p) => (
        <p key={p.id}>{p.title}</p>
      ))}
    </div>
  );
}

```

⚙️ 2. getServerSideProps (Server-Side Rendering - SSR)

Used to fetch data on every request from the server.

The page is generated at runtime whenever a user visits it.

Ideal for pages that need up-to-date or user-specific data (like dashboards or news feeds).

Key Point: Runs on the server every time the page is requested.

Example:

```
export async function getServerSideProps() {
  const res = await fetch("https://api.example.com/users");
  const users = await res.json();

  return {
    props: { users }, // passed to the page component
  };
}

export default function Users({ users }) {
  return (
    <div>
      <h1>Users List</h1>
      {users.map((u) => (
        <p key={u.id}>{u.name}</p>
      ))}
    </div>
  );
}

```

Comparison Table

| Feature            | `getStaticProps`                 | `getServerSideProps`                  |
| ------------------ | -------------------------------- | ------------------------------------- |
| **When it runs**   | At **build time**                | On **every request**                  |
| **Rendering type** | **Static Site Generation (SSG)** | **Server-Side Rendering (SSR)**       |
| **Performance**    | Very **fast** (pre-built)        | **Slower** (runs on server each time) |
| **Use case**       | Data that rarely changes         | Data that changes frequently          |
| **SEO**            | Excellent                        | Excellent                             |
| **Example**        | Blog, portfolio, docs            | Dashboard, live data, user profile    |


---

### Q12: When to use getStaticProps vs getServerSideProps and vice verca
**Choose getStaticProps when:**

**Content is static and rarely changes**: Pre-rendering pages at build time with getStaticProps delivers lightning-fast performance and optimal SEO, as search engines can readily crawl and index the content.
**Scalability and cost-effectiveness:** Since page generation happens at build time, no server requests are needed on every visit, improving server performance and reducing costs.
**Improved user experience**: Pages load instantly as they’re already pre-rendered, leading to a smooth and responsive user experience, especially for initial visits.

**Choose getServerSideProps when:**

**Dynamic content that frequently updates**: Use getServerSideProps to fetch data and pre-render pages at request time when content changes frequently, like news articles, stock prices, or personalized user data.
**User authentication and personalization:** Access user-specific data like shopping carts or logged-in states, personalize UI elements, and implement authentication logic dynamically based on user requests.
**API data integration:** For real-time data from external APIs or databases, getServerSideProps allows fetching and integrating data directly into page responses during server-side rendering.


---

### Q13: What is getStaticPaths?
getStaticPaths is used to create pages for dynamic routes (like /blog/[id]) when using Static Site Generation (SSG).
It tells Next.js which dynamic pages to build in advance at build time.

⚙️ Simple Explanation
Runs only at build time.
Generates a list of paths (URLs) for dynamic pages.
Works together with getStaticProps to fetch data for each page.

---



### Q14: How to fetch data in Next.js?
In Next.js, you can fetch data in three main ways:
**At build time** → using **getStaticProps()** (for Static Site Generation - SSG)
**On each request** → using **getServerSideProps()** (for Server-Side Rendering - SSR)
**On the client side** → using **fetch**, **axios**, or React hooks like **useEffect() **(for Client-Side Rendering - CSR)

Example:

```
// getStaticProps
export async function getStaticProps() {
  const res = await fetch("https://api.github.com/repos/vercel/next.js");
  const repo = await res.json();
  return { props: { repo } };
}

export default function Page({ repo }) {
  return repo.stargazers_count;
}
```
```
// getServerSideProps
export async function getServerSideProps() {
  // Fetch data from external API
  const res = await fetch("https://api.github.com/repos/vercel/next.js");
  const repo = await res.json();
  // Pass data to the page via props
  return { props: { repo } };
}

export default function Page({ repo }) {
  return (
    <main>
      <p>{repo.stargazers_count}</p>
    </main>
  );
}
```

---

### Q15: What is the Link component in Next.js?
The Link component in Next.js is used for client-side navigation between pages. It allows users to move from one page to another without reloading the entire site, making navigation faster and smoother — just like in a single-page application (SPA).

Example:
```
import Link from 'next/link';

<Link href="/about">Go to About Page</Link>

```

---

### Q16: What is the useRouter hook in Next.js?
The useRouter hook in Next.js is used for programmatic navigation — it lets you navigate between pages using code instead of links. It also allows you to access route details like the current path or query parameters inside your components.

Example :
```
import { useRouter } from 'next/router';

const Home = () => {
  const router = useRouter();

  return (
    <button onClick={() => router.push('/about')}>
      Go to About Page
    </button>
  );
};

```

---

### Q17: Programmatic Navigation in Next.js -- (DELETE QUESTION)
Use `router.push('/page')` or `router.replace('/page')` for navigation.  
**Source:** Document1  

---

### Q18: What is Dynamic Routing in Next.js? - (DELETE QUESTION)




---

### Q19: What are redirects and rewrites in Next.js?
Redirects and rewrites in Next.js are used to control how URLs behave, but they function differently.

Redirects: Change the URL in the browser. They are used for permanent (301) or temporary (302) moves.

Example:

```
module.exports = {
  async redirects() {
    return [
      {
        source: '/old-blog',
        destination: '/new-blog',
        permanent: true,
      },
    ];
  },
};
```
In this example, When a user visits /old-blog, the browser URL changes to /new-blog, and search engines update their links accordingly.


Rewrites: Keep the URL in the browser unchanged. They internally map a URL to a different page or API route.

Example:
```
module.exports = {
  async rewrites() {
    return [
      {
        source: '/about',
        destination: '/info',
      },
    ];
  },
};
```
In this example, When a user visits /about, the browser still shows /about, but Next.js internally renders content from /info. This is useful for clean URLs or proxying API requests.




---

### Q20: What is Prefetching in Next.js?
Prefetching in Next.js means loading the next page’s files (JavaScript and assets) in advance, before the user actually clicks the link.
This makes navigation faster and smoother.

⚙️ How It Works (Step by Step):

When a page has a <Link> to another route, Next.js automatically starts downloading that page’s resources in the background.
The user hasn’t clicked yet, but the page is already partly loaded.
When the user clicks the link, the page opens instantly.
Prefetching is enabled by default for <Link> components in production builds.
This helps reduce page load time and gives a better user experience, especially in large or multi-page apps.



---

## Part 2: Quick Reference Questions
- [What is File-Based Routing?](#q5-file-based-routing-in-nextjs)
- [What is getStaticPaths used for?](#q13-getstaticpaths)
- [What is ISR and why is it useful?](#q9-isr)
- [How do you add meta tags using the Head component?](#q23-what-is-the-image-component-and-image-optimization-in-nextjs)
- [What is the difference between Layouts and Templates?](#q35-what-are-layouts-and-templates-in-app-router)
- [What are Redirects vs Rewrites?](#q19-what-are-redirects-and-rewrites-in-nextjs)
- [What is Prefetching and how does it improve performance?](#q20-what-is-prefetching-in-nextjs)
- [What is Serverless Architecture in Next.js?](#q31-what-is-serverless-deployment-in-nextjs)
- [What are publicRuntimeConfig and serverRuntimeConfig?](#q26-what-is-the-purpose-of-publicruntimeconfig-and-serverruntimeconfig)
- [How does Next.js handle CORS?](#q26-security-and-cors)
- [What is the difference between App Router and Pages Router?](#q34-what-is-app-router-vs-pages-router)
- [What is Middleware used for?](#q33-what-is-middleware-in-nextjs)
- [What are React Server Components (RSC)?](#q38-what-are-react-server-components-rsc-in-nextjs)
- [How do you handle authentication in Next.js?](#q37-how-do-you-implement-authentication-in-nextjs)
- [What is Incremental Static Regeneration (ISR)?](#q9-isr)

---

📘 **Note:**  
Questions **Q33 (Docker)** and **Q39 (JWT/NextAuth/Firebase)** were intentionally removed as per your request.

---
