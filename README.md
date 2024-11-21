<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart Rain Animation</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            background-color: #FF80AB; /* 분홍색 배경 */
            overflow: hidden;
        }

        .heart {
            position: absolute;
            width: 30px;
            height: 30px;
            background-color: white;
            clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
            animation: fall 5s infinite ease-in-out;
            pointer-events: none;
        }

        @keyframes fall {
            0% {
                top: -30px;
                left: calc(100% * random());
            }
            100% {
                top: 100%;
            }
        }

        /* 랜덤한 위치를 계산하는 JavaScript 함수 */
        @keyframes randomPosition {
            0% {
                left: 50%;
                top: -30px;
            }
            100% {
                left: 50%;
                top: 100%;
            }
        }

        /* 애니메이션 효과를 여러 하트에 적용 */
        .heart:nth-child(odd) {
            animation-duration: 5s;
        }
        .heart:nth-child(even) {
            animation-duration: 7s;
        }

    </style>
</head>
<body>
    <div class="heart" style="animation-delay: 0s;"></div>
    <div class="heart" style="animation-delay: 1s;"></div>
    <div class="heart" style="animation-delay: 2s;"></div>
    <div class="heart" style="animation-delay: 3s;"></div>
    <div class="heart" style="animation-delay: 4s;"></div>

    <script>
        // 랜덤한 위치 계산
        function randomPosition() {
            return Math.random();
        }

        // 하트 애니메이션을 여러 번 생성하는 코드
        let hearts = document.querySelectorAll('.heart');
        hearts.forEach((heart, index) => {
            heart.style.left = `${randomPosition() * 100}%`;
        });
    </script>
</body>
</html>











### 👋안녕하세요! 
저는 **음악과 미술**을 좋아하는 개발자입니다. 🎨🎶   
웹 개발 및 데이터 분석을 배우고 있으며, 창작 활동과 기술을 결합한 프로젝트를 진행 중입니다.

#### 기술 스택 💻
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-00599C?style=flat&logo=c&logoColor=white) ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)   
![Photoshop](https://img.shields.io/badge/-Photoshop-31A8FF?style=flat&logo=adobephotoshop&logoColor=white) ![Illustrator](https://img.shields.io/badge/-Illustrator-FF9A00?style=flat&logo=adobeillustrator&logoColor=white) ![Figma](https://img.shields.io/badge/-Figma-000000?style=flat&logo=figma&logoColor=white)   
![AIVA](https://img.shields.io/badge/-AIVA-00BFFF?style=flat&logo=google&logoColor=white)


#### 프로젝트 🔧  
#### [프로젝트 이름](GitHub 링크)
- **기술**: HTML, CSS, JavaScript
- **설명**: 음악 데이터를 시각화한 웹 애플리케이션입니다. 🎵

#### 연락처 📞
- [LinkedIn](https://linkedin.com/in/yourname)
- [이메일](mailto:your.email@example.com)

#### GitHub 통계 📊
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical)
















<!--
**haapie4576/haapie4576** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
