<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F3A2E,100:7BA05B&height=190&section=header&text=Monje%20Pohl&fontSize=48&fontColor=ffffff&desc=Software%20engineering,%20by%20way%20of%20viticulture&descSize=17&descAlignY=60&animation=fadeIn" width="100%" alt="Monje Pohl" />

</div>

I came to software engineering through agriculture. My MSc in Viticulture at Stellenbosch involved writing custom image-processing algorithms to measure morphological and colourimetric traits across 1,416 individual grapevines, and running the multivariate analysis that made sense of the results. Writing that analysis is what got me into software development.

I am finishing a BSc IT (Software Engineering) at Eduvos in November 2026. I am most interested in work where software meets the physical world — agriculture, sensors, and data that comes out of a field rather than a form.

Cape Town, South Africa.

<div align="center">

<img src="https://skillicons.dev/icons?i=cs,dotnet,js,react,nextjs,python,postgres,mysql,docker,git&perline=10" alt="C#, .NET, JavaScript, React, Next.js, Python, PostgreSQL, MySQL, Docker, Git" />

</div>

---

### VitiSense

My final-year capstone, built by a team of six. An offline-first system that reads vineyard sensor data over LoRa and warns farmers of downy and powdery mildew risk without needing an internet connection. Leaf nodes report to a Raspberry Pi running a containerised FastAPI service, and a Next.js progressive web app presents the readings.

I worked on the web app, where I was the largest single contributor. Specifically, I built:

- the **Nodes** feature end to end — the leaf-node list, the detail modal, the edit form and the farm map
- the **Alerts**, **Profile** and **Export** screens
- the **settings and theming layer**, a React context built on `useSyncExternalStore` so that saved preferences and the device's dark-mode setting survive server rendering without a hydration mismatch
- the **mildew threshold model**, taken from the published literature

The offline connection detection and the authentication were built by teammates.

→ [Toast1e/capstone_central_node_pwa](https://github.com/Toast1e/capstone_central_node_pwa)

### Data structures and algorithms

An AVL tree, a priority queue and QuickSort, written from first principles in C#. The README walks through the balance factor, the four rotation cases, and the things I would do differently — including the one place where my rebalancing after a deletion stops too early.

→ [Data-structures-and-Algorithms-project](https://github.com/PurpleBubbles/Data-structures-and-Algorithms-project)

### HackJam 2025

My team won the national Eduvos HackJam. I designed and built the PostgreSQL schema behind the progressive web app we submitted, which is now in use by Eduvos students and staff.

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-monjepohl-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/monjepohl)
[![Email](https://img.shields.io/badge/Email-monje.pohl@gmail.com-1F3A2E?style=for-the-badge&logo=gmail&logoColor=white)](mailto:monje.pohl@gmail.com)

</div>
