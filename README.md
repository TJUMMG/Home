<!-- CSS -->
<style>
.columns {
  display: flex;
}

.column {
  flex: 1;
  text-align: center;
  padding: 10px;
  background-color: #f2f2f2;
}
 .language-content {
  margin-bottom: 15px;
} 
</style>
<button onclick="toggleLanguage()">切换语言</button>

<!-- 中英文内容 -->
<div id="content" class="language-content">
<!-- 分栏界面开始 -->
<div class="columns">
  <a href="publications.html" class="column" target="_blank">Publications</a>
  <a href="members.html" class="column" target="_blank">Members</a>
  <a href="teaching.html" class="column" target="_blank">Teaching</a>
  <a href="resources.html" class="column" target="_blank">Resources</a>
  <a href="joinus.html" class="column" target="_blank">Join Us</a>
</div>
<!-- 分栏界面结束 -->
<!-- README.md -->
<h1>Jing Liu's Homepage</h1>

<img src="image.png" alt="图片描述" style="float:left;margin-right:30px;margin-left:0px;max-width:240px; height:auto;" />

Hi, I am now an Associate Professor with Multimedi Institute of Tianjin University. I received the B.E and Ph.D. degree from Shanghai Jiao Tong Univeristy under the supervision of Prof. <a href="https://english.seiee.sjtu.edu.cn/english/detail/842_802.htm">Xiaokang Yang</a> and Prof. <a href="https://scholar.google.ca/citations?user=E6zbSYgAAAAJ">Guangtao Zhai</a>. I am also supervised by Prof. <a href="https://cse.buffalo.edu/UBMM/People/dr.chen.html">Chang Wen Chen</a> when visiting at SUNY@Buffalo from 2014-2015. My research interest includes: image/video processing and cross-modal video content analysis. </br>
  <ul>
    <li>Email:  jliu_tju@tju.edu.cn</li>
    <li>Address: Tianjin University,26D Building, Rm 413</li>
    <li>Github: <a href="https://github.com/TJUMMG" target="_blank">TJUMMG</a></li>
  </ul>

<h2>Work Experience</h2>
  <ul>
    <li>2019-now: Associate Professor, Tianjin University, China </li>
    <li>2017-2019 : Assistant Professor, Tianjin University, China</li>
    <li>2017-2019 : Post-doc, Tianjin University, China</li>
  </ul>

<h2>Educational Experience</h2>
  <ul>
    <li>2011-2017: PhD, Shanghai Jiao Tong University, China</li>
    <li>2014-2015: Visiting Scholar, State University of New York, U.S.</li>
    <li>2007-2011: Bachelor, Shanghai Jiao Tong University, China</li>
  </ul>

<h2>Research Interest</h2>
  <ul>
    <li>Image/Video Processing (Enhancement, Quality Assessment,  etc.)</li>
    <li>Video Content Analysis (Segmentation, Tracking, Cross-modal Retrieval, etc.)</li>
    <li>Recommendation Systems (Cross-domain Recommender, Interactive Recommender)</li>
  </ul>

<h2>Openings</h2>
  <ul>
    <li>Looking for self-motivated graduate students working with me. For prospective students, please send your resume and transcript to my email.</li>
    <li>The research group is inviting students to enter the Master program in Autumn 2024. Please contact us by email.</li>
  </ul>

<h2>NEWS!</h2>
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
- 09/2023, I am promoted to advanced membership of CCF.
- 09/2023, our work SiamDMU is accepted by IEEE TETCI  with code available at GitHub.
- 09/2023, we have successfully host the 3rd CSIG Excellent Doctoral Forum in Tianjin Univeristy!
- 8/2023, our proposal is granted by National Science and Foundation of China.
- 07/2023, one work is accepted by ACM MM with code coming song.
- 07/2023, our work MSTFN is accepted by IEEE TMM with code available at GitHub.
- 04/2023, our work KCLR is accepted by IEEE TMM.
- 04/2023, our work MALN is accepted by IEEE TCSVT.
- 03/2023, our work MRFT is accepted by IEEE TCSVT.
- 01/2023, our work SAW is accepted by IEEE TIP with code available at GitHub.
- 12/2022, our work TGSR is accepted by IEEETCSVT with code available at GitHub.
- 12/2022, our work BE-DS won the Best Poster Award of IFTC2022.
- 08/2022, I am enrolled in the MM Committee of CSIG and CCF.
- --/2022, our work QA-PRI won the 2021 Prize Paper Award Runner-up of IEEE TMM.
- 09/2021, our work TANET is accepted by IEEE TMM with code available at GitHub.
- 06/2021, our work RMFNet is accepted by IEEE TCSVT.
- 12/2020, I am enrolled  in Editoral Board of Displays (Springer)
- 06/2020, our work LRML is published in IEEE TMM.
- 12/2019, I am enrolled in Beiyang Scholar Program-Young Teacher.
- 10/2019, our work BE-CALF is published in IEEE TIP with code available at GitHub.
- 10/2019, two of my students Wanning Sun and Pingping Liu was granted National Scholarship.
- 09/2019, our work SSCNN is published in IEEE TMM.
- 11/2018, I receive an honer for CSIG candidate excellent doctoral dissertation.
- 10/2018, our work IPAD is published in IEEE TIP with code available at GitHub.
</div>

<script>
function toggleLanguage() {
  var content = document.getElementById("content");
  var zhContent = document.getElementById("zh-CN");
  
  if (content.style.display !== "none") {
    content.style.display = "none";
    zhContent.style.display = "block";
  } else {
    content.style.display = "block";
    zhContent.style.display = "none";
  }
}
</script>
