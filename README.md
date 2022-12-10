<h1 align="center">
    My-Enews
</h1>

<p align="center">
  <strong>나만의 e-뉴스 페이지</strong><br>
  Suwon e-News Page. <br>
  <a href="https://www.turtleheadsnake.site/">수원 E-News 바로가기</a>
</p>

<p>나만의 수원 e-뉴스는 정부 공공 API 포털로부터 제공받은 수원 e-news의 API를 활용하여 최신 뉴스의 정보와 이벤트 배너 그리고 수원 e 뉴스 채널의 설명과 이동을 확인할 수 있도록 도와주는 페이지입니다. </p>

<p>전체 페이지</p>
    <img src='https://user-images.githubusercontent.com/50876935/206856225-c0de042c-1749-4631-90ce-6ba1a61696a1.PNG' width="300" >

<p>베너와 홍보영상 이동</p>
  <img src='' width="300" >

## Service & Explanation

---

-  [check_the_news](#-check_the_news)
-  [Banner_Youtube](#-Banner_Youtube)
-  [AWS_Architecture](#-AWS_Architecture)
-  [Tech_Stacks](#-Tech_Stacks)

## 📖 check_the_news

---

수원 e-news API를 통해 수원의 최신 소식들을 만나보실 수 있습니다.

<div>
  <br>
    <p> 뉴스 제목과 일자 확인</p>
  <img src='https://user-images.githubusercontent.com/50876935/206856264-ace35817-d2b1-459e-9ff6-a5ce2c7adf45.png' width="300" >
</div>

## 👔 Banner_Youtube

---

Banner와 Youtube 그리고 수원 e-news 페이지로 이동할 수 있는 버튼이 함께합니다. 뉴스를 전체적으로 확인해보고 관심이 생긴 뉴스가 있으면 뉴스페이지로 이동하여 원하는 뉴스를 확인하실 수 있습니다.

<div>
  <br>
    <p> Banner & Youtube </p>
  <img src='https://user-images.githubusercontent.com/50876935/206856322-40291095-8271-4ecd-a642-38246ca63b3b.png' width="300" >
</div>

## 🧑‍💻AWS_Architecture

---

![undefined](https://user-images.githubusercontent.com/50876935/206857506-50860aa3-ec55-4f66-90dc-2e07e2d7fda0.png)

<p>이 프로젝트는 Route53 -> Cloud-Front -> S3의 과정을 통한 정적호스팅 방식으로 웹을 호스팅하고 있습니다. 웹에서 동적 활용이 필요할 경우 EC2로 처리하고 그외 Client가  Route53을 통해 접속할 경우 정적인 페이지로 호스팅 진행하였습니다.</p>

## 🔨 Tech_Stacks

---

<strong>Front-end :</strong>
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

<strong>Back-end :</strong>
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
