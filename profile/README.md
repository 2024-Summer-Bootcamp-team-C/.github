# 🫅 We in 전

![header](https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&customColorList=28&text=We%20in%20전&textBg=false&animation=twinkling&reversal=true&fontAlign=50&desc=위인전에%20들어가다&descSize=20&descAlignY=19)
<br/>

# 📢 Instruction

### We in 전은 AI를 활용한 과거 인물과 현재를 잇는 역사 학습 서비스입니다.

### 과거 인물들이 어떤 가치관, 생각을 가지고 있는지 궁금하신가요?

### 직접 대화해 알아보세요! 여러분은 재밌게 역사 지식을 습득할 수 있습니다!

[미디움 주소](https://github.com/2024-Summer-Bootcamp-team-C)
<br/>

# 📖 DEMO

<br/>

# ⚙ System Architecture

<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/image/systemArchitecture.png?raw=true" >
<br/>

# 🔍 Detailed Info

<!-- 수정해야함 자기가 이번 프로젝트에서 중요하게 생각한다. 어필하고 싶다 하는 기술 알려주기-->
<table width="1000">
<tbody>
<tr>
  <th width="200">Name</th>
  <th width="800">Description</th>
</tr>
<tr>
  <th>Nginx</th>
  <td>웹 서버, 프록시 서버 연결 및 SSL/TLS 등을 담당합니다.</td>
</tr>
<tr>
  <th>React</th>
  <td>컴포넌트 기반으로 코드 재사용성을 높이는 프론트엔드 라이브러리입니다.</td>
</tr>
<tr>
  <th>Node.js(Express.js)</th>
  <td>TAIROT의 서버로서 각종 요청을 처리하고 DB와 직접 소통합니다.</td>
</tr>
<tr>
  <th>Socket.IO</th>
  <td>
    Chat GPT로부터 받은 카드별 해석 및 종합 해석을 프론트엔드에 stream 형태로 전달합니다.</br>
    버퍼에 한 줄씩 저장한 TTS를 프론트엔드에 전달합니다.
  </td>
</tr>
<tr>
  <th>EC2</th>
  <td>클라우드 컴퓨팅 서비스로 호스팅을 담당합니다.</td>
</tr>
<tr>
  <th>Jenkins</th>
  <td>CI/CD 자동화를 담당하고 빌드 결과를 실시간으로 슬랙에 전달합니다.</td>
</tr>
<tr>
  <th>Docker</th>
  <td>컨테이너화된 응용 프로그램의 개발, 배포 및 실행을 간소화하고 일관성을 유지합니다.</td>
</tr>
<tr>
  <th>S3</th>
  <td>78장의 타로 카드 정보(번호, 영문 이름, 한글 이름, 이미지 url)를 저장합니다.</td>
</tr>
<tr>
  <th>Prometheus</th>
  <td>오픈 소스 기반의 시스템 및 서비스 모니터링 도구로 Metric 정보를 수집하고 저장합니다.</td>
</tr>
<tr>
  <th>Grafana</th>
  <td>수집한 Metric 정보를 시각화하여 대시보드를 구성하며 모니터링 중 성능 이슈 발생 시 실시간으로 슬랙에 경고 알람을 전달합니다.</td>
</tr>
<tr>
  <th>Filebeat</th>
  <td>서버의 로그를 수집하여 Logstash로 전달합니다.</td>
</tr>
<tr>
  <th>Logstash</th>
  <td>Filebeat로 수집된 데이터를 처리하고 Elasticsearch로 전송하는 역할을 담당합니다.</td>
</tr>
<tr>
  <th>Elasticsearch</th>
  <td>Logstash로부터 전달 받은 데이터를 저장합니다.</td>
</tr>
<tr>
  <th>Kibana</th>
  <td>lasticsearch에 저장된 로그 데이터를 분석하고 시각화합니다.</td>
</tr>
</tbody>
</table>

<br/>
<br/>

# 🛠 Tech Stack

<table width="1000">
<tr align="center">
  <th width="200">Frontend</th>
  <th width="200">Backend</th>
  <th width="200">DevOps</th>
  <th width="200">DB</th>
  <th width="200">Others</th>
</tr>
<tr>
  <td align="center">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/></br>
  </td>
  <td align="center">
    <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></br> 
    <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/djangochannels-010101?style=for-the-badge&logo=django&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"/></br>
  </td>
  <td align="center">
    <img src="https://img.shields.io/badge/AMAZON_EC2-FF9900?style=for-the-badge&logo=AMAZONEC2&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/Cadvisor-34E0A1?style=for-the-badge&logo=tripadvisor&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/githubactions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/></br>
  </td>
  <td align="center">
    <img src="https://img.shields.io/badge/MySql-4479A1?style=for-the-badge&logo=MySql&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/AMAZON_RDS-527FFF?style=for-the-badge&logo=AMAZONRDS&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/AMAZON_S3-569A31?style=for-the-badge&logo=AMAZONS3&logoColor=white"/></br>
  </td>
  <td align="center">
    <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"/></br>
    <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"/></br>
  </td>
</tr>
</table>

<br/>

# 💾 ERD

<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/image/erd.png?raw=true" >
<br/>

# 📜 Swagger

<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/image/swagger.png?raw=true" >
<br/>

# ✨ Team Member

<table width="1000">
<thead>
</thead>
<tbody>
<tr>
<th>Pictures</th>
<td width="100" align="center">
<a href="https://github.com/kingjinyong">
<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/people/jinyoung.jpeg?raw=true" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/choihooo">
<img src="https://raw.githubusercontent.com/2024-Summer-Bootcamp-team-C/.github/main/assets/people/choiho.jpeg" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/D0nghyeonLee">
<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/people/donghyun.jpg?raw=true" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/yena0213">
<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/people/yena.jpeg?raw=true" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/jaehyun-0103">
<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/people/jaehyun.jpeg?raw=true" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/pgc0419">
<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/people/geunchae.jpeg?raw=true" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/yunseo0000">
<img src="https://github.com/2024-Summer-Bootcamp-team-C/.github/blob/main/assets/people/yunseo.png?raw=true" width="60" height="60">
</a>
</td>
</tr>
<tr>
<th>Name</th>
<td width="100" align="center">김진용</td>
<td width="100" align="center">최 호</td>
<td width="100" align="center">이동현</td>
<td width="100" align="center">이예나</td>
<td width="100" align="center">조재현</td>
<td width="100" align="center">박근채</td>
<td width="100" align="center">이윤서</td>
</tr>
<tr>
<th>Position</th>
<td width="150" align="center">
Frontend<br>
Leader<br>
</td>
<td width="150" align="center">
Frontend<br>
</td>
<td width="150" align="center">
Frontend<br>
</td>
<td width="150" align="center">
Backend<br>
DevOps<br>
</td>
<td width="150" align="center">
Backend<br>
DevOps<br>
</td>
<td width="150" align="center">
Backend<br>
DevOps<br>
</td>
<td width="150" align="center">
Backend<br>
DevOps<br>
</td>
</tr>
<tr>
<th>GitHub</th>
<td width="100" align="center">
<a href="https://github.com/kingjinyong">
<img src="https://img.shields.io/badge/kingjinyong-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/choihooo">
<img src="https://img.shields.io/badge/choihooo-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/D0nghyeonLee">
<img src="https://img.shields.io/badge/D0nghyeonLee-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/yena0213">
<img src="https://img.shields.io/badge/yena0213-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/jaehyun-0103">
<img src="https://img.shields.io/badge/jaehyun0103-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/pgc0419">
<img src="https://img.shields.io/badge/pgc0419-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
<td width="100" align="yunseo0000">
<a href="https://github.com/hannaxannah">
<img src="https://img.shields.io/badge/yunseo0000-white?style=for-the-badge&logo=github&logoColor=black"/></br>
</a>
</td>
</tr>
</tbody>
</table>
