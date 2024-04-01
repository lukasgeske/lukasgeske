### Lukas Geske

<h1>Merhabalar!</h1>
<div style="display: flex;">
    <img src="https://media.tenor.com/m97ACRCSn_kAAAAM/hello-minion.gif" alt="Örnek Resim" style="width: 200px; height: 200px; margin-right: 20px;">
    <img src="https://media3.giphy.com/media/1fYi7IQLtBuRm2nPNo/200w.gif" alt="Örnek Resim" style="width: 200px; height: 200px; margin-left: 10rem;">
</div>

#container {
    position: relative;
    overflow: hidden;
    width: 300px;
    height: 300px;
}

#snake {
    position: absolute;
    width: 100px;
    height: 100px;
    background-image: url('yilan.gif'); /* yilan.gif dosyanızın yolunu belirtin */
    animation: moveSnake 5s infinite linear;
}

@keyframes moveSnake {
    0% { left: -100px; }
    100% { left: calc(100% + 100px); }
}


<!--
**lukasgeske/lukasgeske** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on making guitar pedal sounds.
- 🌱 I’m currently learning Python
- 💬 Ask me about: Anything
- 📫 How to reach me: e-Mail
- 😄 Pronouns: As wl all know there's just 2 and I'm a males.
-->
