# 👋 Hello, I'm Adnan Hassan!

I'm a **WordPress Developer** and **SEO Expert** with a passion for building efficient, user-friendly websites and applications. I specialize in custom WordPress solutions, e-commerce platforms, and seamless API integrations. Check out my projects and feel free to reach out if you'd like to collaborate!

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=imadnanhassane&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=imadnanhassane&layout=compact&theme=radical)

![Profile Views](https://komarev.com/ghpvc/?username=imadnanhassane&color=blueviolet)
[![GitHub Followers](https://img.shields.io/github/followers/imadnanhassane?label=Followers&style=social)](https://github.com/imadnanhassane)

---

## 🛠️ Tech Stack

Here are the technologies I work with:

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white&style=flat-square)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white&style=flat-square)
![SASS](https://img.shields.io/badge/-SASS-CC6699?logo=sass&logoColor=white&style=flat-square)
![MUI](https://img.shields.io/badge/-MUI-007FFF?logo=mui&logoColor=white&style=flat-square)
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=flat-square)
![React Router](https://img.shields.io/badge/-React%20Router-CA4245?logo=react-router&logoColor=white&style=flat-square)
![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=next.js&logoColor=white&style=flat-square)
![Redux](https://img.shields.io/badge/-Redux-764ABC?logo=redux&logoColor=white&style=flat-square)
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=flat-square)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?logo=typescript&logoColor=white&style=flat-square)
![Express.js](https://img.shields.io/badge/-Express.js-000000?logo=express&logoColor=white&style=flat-square)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat-square)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white&style=flat-square)
![JWT](https://img.shields.io/badge/-JWT-000000?logo=json-web-tokens&logoColor=white&style=flat-square)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat-square)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?logo=firebase&logoColor=black&style=flat-square)
![Netlify](https://img.shields.io/badge/-Netlify-00C7B7?logo=netlify&logoColor=white&style=flat-square)
![Vercel](https://img.shields.io/badge/-Vercel-000000?logo=vercel&logoColor=white&style=flat-square)
![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white&style=flat-square)
![GIT](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat-square)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?logo=figma&logoColor=white&style=flat-square)
![Canva](https://img.shields.io/badge/-Canva-00C4CC?logo=canva&logoColor=white&style=flat-square)

---

## 📬 Connect with Me
- 🌐 Website: [adnanhassan.net](https://adnanhassan.net)
- 📧 Email: hello@adnanhassan.net
- 💼 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/imadnanhassan/)

---

*Thanks for visiting! Feel free to explore my repositories and reach out if you have any questions or collaboration ideas.* 😊

## 🧑‍💻 My Code

Here’s a glimpse of my coding style and some key snippets I often use:

```javascript
// Sample API Fetching in React
import React, { useEffect, useState } from 'react';
import axios from 'axios';

const MyComponent = () => {
  const [data, setData] = useState([]);

  useEffect(() => {
    axios.get('https://api.example.com/data')
      .then(response => setData(response.data))
      .catch(error => console.error('Error fetching data:', error));
  }, []);

  return (
    <div>
      <h2>Data List</h2>
      <ul>
        {data.map((item, index) => (
          <li key={index}>{item.name}</li>
        ))}
      </ul>
    </div>
  );
};

export default MyComponent;
