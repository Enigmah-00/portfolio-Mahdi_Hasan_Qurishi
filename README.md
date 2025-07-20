![Portfolio Screenshot](./images/ss1.png)

## 🚀 Hero Section Preview

---

## 🧩 How This Section Works

The **Hero Section** contains:

- **Profile Image** with neon glow  
- **Name & Introduction** in glowing text  
- **Quick Links**:  
  `Codeforces`, `CodeChef`, `AtCoder`, `GitHub`

---

## 📄 HTML Structure

```html
<div class="hero">
  <div class="container hero-content">
    <div class="portrait">
      <img src="images/ChatGPT Image Jul 18, 2025, 01_41_32 PM.png" alt="Mahdi Hasan Qurishi" />
    </div>
    <div class="bio">
      <h1>Mahdi Hasan Qurishi</h1>
      <p>
        I'm a competitive programmer, 3rd year CSE student at Shahjalal University of Science and Technology.  
        Passionate about AI, ML, and Android development.
      </p>
      <div class="links">
        <a href="https://codeforces.com/profile/ENIGMAH">Codeforces</a>
        <a href="https://www.codechef.com/users/disaster_101">CodeChef</a>
        <a href="https://atcoder.jp/users/enigmah_00">AtCoder</a>
        <a href="https://github.com/Enigmah-00">GitHub</a>
      </div>
    </div>
  </div>
</div>

```
## 🎨 CSS Highlights

```css
.hero {
  background: radial-gradient(ellipse at top left, #07121e 0%, #0c0f1c 100%);
  padding-top: 80px;
}

.hero-content {
  display: flex;
  gap: 40px;
  align-items: center;
}

.portrait img {
  width: 300px;
  border-radius: 12px;
  box-shadow: 0 0 20px #00ffcce0;
}

.bio h1 {
  color: #00ffcc;
  text-shadow: 0 0 10px #00ffcc88;
}

.links a {
  display: inline-block;
  padding: 8px 16px;
  border: 1px solid #00ffcc80;
  color: #00ffcc;
  text-decoration: none;
  border-radius: 8px;
  transition: background 0.3s;
}

.links a:hover {
  background: #00ffcc22;
}
```

## 🗂️ Features Summary

| Feature             | Description                              |
|--------------------|------------------------------------------|
| Neon Profile Image  | Adds a glowing effect to the profile picture |
| Glowing Name Text   | Uses text-shadow for cyberpunk look      |
| Flex Layout         | Places image and bio side by side        |
| Quick Links         | Button-style links with hover interaction |

---

![Portfolio Screenshot](./images/ss2.png)
![Portfolio Screenshot](./images/ss3.png)

## 🧩 How This Section Works

The **Competitive Programming Stats** contains: 

- an image of graph of problem solving

---


## 📄 HTML Structure

```html
  <section class="section container" id="stats">
    <h2>Competitive Programming Stats</h2>
    <img src="images/ChatGPT Image Jul 18, 2025, 12_37_24 PM.png" alt="Problem Solving Graph" class="graph-img"/>
  </section>
```
![Portfolio Screenshot](./images/ss4.png)

## Projects and skill preview

## 📄 HTML Structure

