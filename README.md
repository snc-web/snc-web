# 💫 DHIRAJ SNC

> **Full-Stack Developer — Backend & Frontend**

---

<p align="center">
  <img alt="Hero: phone + desktop mockup" src="https://via.placeholder.com/1000x400?text=Phone+%2B+Desktop+Mockup" width="100%" />
</p>

---

## 👋 Hello — I'm Dhiraj from Nepal 🇳🇵

I’m **Dhiraj**, a passionate **Full-Stack Developer** from **Nepal**.  
I work on both **backend** and **frontend** technologies and have completed **50+ real-world projects**, helping me gain deep practical experience.  
I focus on building responsive, optimized, and scalable web applications that work beautifully on both **mobile** 📱 and **desktop** 💻.

---

## 🚀 About Me

- 🌍 **Location:** Nepal  
- 💼 **Role:** Backend & Frontend Developer  
- 💪 **Experience:** 50+ completed projects  
- 🧠 **Skills:** JavaScript, Node.js, Express.js, React.js, MongoDB, Tailwind CSS, REST API  
- 🎯 **Focus Areas:** Clean architecture, UI/UX design, API optimization, and performance  
- 🔥 **Goal:** To keep learning, building, and pushing web experiences to the next level  

---

## ✨ 3D CSS Showcase

> GitHub Markdown doesn’t support live CSS animations, but you can view this **3D hero effect** by copying the following code into an `index.html` file and opening it in a browser.

---

### 🧩 3D HERO DEMO (paste into `index.html`)

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DHIRAJ SNC — 3D Hero Demo</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html, body { height: 100%; font-family: 'Poppins', sans-serif; }

    .hero {
      height: 100vh;
      display: flex;
      align-items: flex-end;
      justify-content: center;
      background: linear-gradient(180deg, #0f172a 0%, #031226 100%);
      color: #fff;
      padding: 40px;
      overflow: hidden;
      position: relative;
    }

    .title-wrap {
      text-align: center;
      max-width: 1100px;
    }

    .title {
      font-size: clamp(48px, 9vw, 140px);
      font-weight: 900;
      letter-spacing: -0.03em;
      position: relative;
      display: inline-block;
      transform-style: preserve-3d;
      perspective: 1000px;
      color: #fff;
    }

    .title::before {
      content: attr(data-text);
      position: absolute;
      left: 0;
      top: 0;
      z-index: -1;
      filter: blur(0.8px);
      text-shadow:
        1px 1px 0 rgba(0,0,0,0.15),
        2px 2px 0 rgba(0,0,0,0.14),
        3px 3px 0 rgba(0,0,0,0.13),
        4px 4px 0 rgba(0,0,0,0.12),
        5px 5px 0 rgba(0,0,0,0.11),
        6px 6px 30px rgba(0,0,0,0.7);
      transform: translateZ(-45px);
    }

    .title span {
      background: linear-gradient(90deg, rgba(255,255,255,0.06), rgba(255,255,255,0.02));
      padding: 10px 20px;
      border-radius: 14px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.6);
      backdrop-filter: blur(4px);
    }

    .subtitle {
      font-size: clamp(16px, 2.6vw, 22px);
      font-weight: 700;
      margin-top: 14px;
      opacity: 0.9;
    }

    .devices {
      display: flex;
      gap: 20px;
      align-items: center;
      justify-content: center;
      margin-top: 40px;
      flex-wrap: wrap;
    }

    .device {
      border-radius: 20px;
      overflow: hidden;
      background: #071227;
      box-shadow: 0 20px 50px rgba(0,0,0,0.6);
    }

    .phone { width: 220px; height: 440px; }
    .desktop { width: 540px; height: 340px; }

    .device img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    @media (max-width: 700px) {
      .devices { flex-direction: column; }
    }
  </style>
</head>
<body>
  <section class="hero">
    <div class="title-wrap">
      <h1 class="title" data-text="DHIRAJ SNC"><span>DHIRAJ SNC</span></h1>
      <p class="subtitle">I’m Dhiraj from Nepal — a backend & frontend developer. I’ve built 50+ projects that helped me grow my skills and experience.</p>

      <div class="devices">
        <div class="device phone">
          <img src="https://via.placeholder.com/360x780?text=Phone+Preview" alt="Phone preview" />
        </div>
        <div class="device desktop">
          <img src="https://via.placeholder.com/1280x720?text=Desktop+Preview" alt="Desktop preview" />
        </div>
      </div>
    </div>
  </section>
</body>
</html>
