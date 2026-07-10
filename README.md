# 📅 Schema Vecka 15: Next.js

Vi går arbetar med hur man kan skapa interaktivitet i "client components" (ex med hooks) och hur man kan tänka i uppdelning server/client i Next.js.

Webshop - Admin v 2/3

---

## 📅 Måndag: Client - Server

## Client vs Server
![Server vs Client - från https://levelup.gitconnected.com/next-js-client-side-and-server-side-components-when-and-what-to-use-7c4beccf1eab](https://miro.medium.com/v2/resize:fit:720/format:webp/1*n-TVYb7Hu1LswYOXm2OnzA.png)
Rendering Lifecycle of Server and Client (från https://javascript.plainenglish.io/next-js-15-tutorial-part-38-rendering-lifecycle-of-server-and-client-components-7a80006e14a2)
![Rendering Lifecycle of Server and Client ](https://miro.medium.com/v2/resize:fit:1400/1*AQ1bKekPg_DBR1zDog_MaA.png)



### 🎯 Mål för dagen

* Vi lär oss hur Next.js delar upp arbetet mellan servern och webbläsaren/klienten
* Ev searchParams i server components (PageProps)

### 📚 Material

#### 💻 E-Learning
* [Pluralsight: Se delen (Server Components vs. Client Components)](https://app.pluralsight.com/ilx/video-courses/ccd9b257-fdf5-49c0-b05e-029bf2310416/c0444e39-159a-4077-a664-e632c14a1ee4/6d46e56e-214a-426f-8352-b1dc34131f3a)
* [ByteGrad: When & Where to Add "use client" in React/Next.js (Client Components vs Server Components)](https://www.youtube.com/watch?v=Qdkg_mrniLk)

#### 📃 Läsning
* [Läs gärna igenom denna innan föreläsningen om ni kan - Server and Client Components](https://nextjs.org/docs/app/getting-started/server-and-client-components)
* [React Docs: Server components](https://react.dev/reference/rsc/server-components)
* [React Docs: "use client"](https://react.dev/reference/rsc/use-client)
* [React Use Client](https://react.dev/reference/rsc/use-client)
* [Next.js Docs: Route Handlers (API)](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)

---

## 📅 Tisdag: React Hooks

  * Gör kursen (del 1-4) på Pluralsight (under e-learning), men försök att få det att fungera med next.js. 
  * Del 5-10 är frivilliga just nu. Vi kommer gå igenom del 10 nästa vecka. 
  * Om ni vill så kan ni köra react-app också (vanilla React), som de gör i kursen. Dock missar ni biten om att anpassa till Nextjs som är en bra sak att kunna. 
  * Skippa bitarna om routing (return APP, getServerSideProps osv) då Next.js redan har det inbyggt. 
  * Anpassa till next.js med namnkonventioner och öva på att använda typescript istället för javascript (som i kursen).
  * Använd "use client" för att säga att komponenten är client när det behövs. Next.js utgår från att allt annat är server. 

### 🎯 Mål för dagen

* Förstå hur Hooks i react fungerar
* Kunna använda några olika hooks
* Anpassa vanilla react till Next.js

### 📚 Material

#### 💻 E-Learning
* [React Hooks](https://app.pluralsight.com/ilx/video-courses/react-18-using-hooks/course-overview)

---

## 📅 Onsdag: URL state management

Vi tar vidare det vi arbetat med i server med searchParams, men flyttar in vissa delar in i client components. Vi gör om våra hårdkodade länkar för limit osv till interaktiva element.


### 🎯 Mål för dagen

* **searchParams:** Läsa filter och sökord direkt från URL:en.
* **useRouter & usePathname:** Navigera programmatiskt när användaren klickar eller skriver.
* **Persistens:** Varför URL-state ofta är bättre än vanlig `useState` för filtrering.
* **Leaf Components:** Att hålla sina Client Components små och placerade längst ut i komponentträdet.

### 📚 Material

#### 💻 E-Learning
* [ByteGrad: STOP using useState, instead put state in URL](https://www.youtube.com/watch?v=ukpgxEemXsk)

#### 📃 Läsning
* [Next.js Docs: useSearchParams](https://nextjs.org/docs/app/api-reference/functions/use-search-params)
* [Next.js Docs: useRouter](https://nextjs.org/docs/app/api-reference/functions/use-router)
* [React Hooks](https://react.dev/reference/react/hooks)
* [React Docs: useState](https://react.dev/reference/react/useState)

---

## 📅 Torsdag

Repetition

---

## 📅 Fredag: Sprint Review

Ni kör sprint review på det ni arbetat med i webshop-admin denna vecka.
