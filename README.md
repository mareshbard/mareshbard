### Hi there 👋

<!--
**mareshbard/mareshbard** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

### - 🔭 I’m currently working on ... POO Project
- 🌱 I’m currently learning ... Java, Javascript 
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ... she/her
- ⚡ Fun fact: ...
<!--
-->

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mareshbard)](https://github.com/mareshbard/github-readme-stats)
![Leticia's GitHub stats](https://github-readme-stats.vercel.app/api?username=mareshbard&show_icons=true&theme=tokyonight)

pragma solidity ^0.8.15;

contract Profile {
    string public name = "Letícia Gomes";
    string public pronouns = "She | Her";
    string public currentFocus = "Java / JavaScript";

    string[] internal skills;

    function getSkills() public returns (string[] memory) {
        skills = [
            string("Java"),
            "Javascript",
        ];

        return skills;
    }

    function fun() public view returns (string memory) {
        return
            "Two bytes meet.  The first byte asks, 'Are you ill?' The second byte replies, 'No, just feeling a bit off.'";
    }
}
