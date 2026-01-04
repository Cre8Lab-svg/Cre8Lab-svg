## Hi there 👋

<!--
**Cre8Lab-svg/Cre8Lab-svg** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
const fontSelect = document.getElementById("fontSelect");
const fontSize = document.getElementById("fontSize");

// Apply selected font to the last text added
function changeFont(f) {
  const selected = document.querySelector(".draggable:last-child");
  if (selected && selected.tagName === "DIV") {
    selected.style.fontFamily = f;
  }
}

// Apply font size to last text added
function changeFontSize(size) {
  const selected = document.querySelector(".draggable:last-child");
  if (selected && selected.tagName === "DIV") {
    selected.style.fontSize = size + "px";
  }
}
