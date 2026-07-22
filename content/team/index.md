---
title: "Team"
date: "{{ .Date }}"
---
<style>
    table {
        width: 100%;
    }

    /* 整个团队区域的容器 */
    .team-grid {
        display: flex;
        flex-wrap: wrap;            /* 允许换行 */
        justify-content: center; /* 与简介区块保持左对齐 */
        gap: 2.5rem;                /* 卡片之间的间距 */
        width: 90%;
        max-width: 1100px;
        margin: 2rem auto;
    }

    /* 每个人的卡片样式 */
    .team-member {
        flex: 0 1 calc(33.333% - 2rem); /* 默认一行占 1/3 宽度（即一行3人） */
        min-width: 200px;              /* 限制最小宽度，防止手机端太挤 */
        text-align: center;            /* 文字居中 */
        box-sizing: border-box;
    }

    .team-section-title {
        width: 100%;
        display: block;
        font-weight: 700;
        margin: 2rem 0 1rem;
        color: #7c76bb;
        letter-spacing: 0.02em;
        font-size: xx-large;
    }

    /* 头像样式 */
    .team-avatar {
        width: 80%;                    /* 头像大小比例 */
        max-width: 260px;              /* 限制最大尺寸 */
        height: auto;
        border-radius: 8px;            /* 可选：给图片加一点圆角，更好看 */
        margin-bottom: 0.8rem;
    }

    .member-name {
        font-weight: bold;
        margin: 0.3rem 0;
        font-size: 1.1rem;
    }

    .member-role {
        color: #666;                   /* 职位颜色稍淡一点以示区分 */
        font-size: 0.95rem;
        margin: 0;
    }
    
    /* 新增 Flexbox 布局样式 */
    .profile-container {
        width: 90%;
        max-width: 1100px;
        margin: 2rem auto 10em;
        display: flex;          /* 开启弹性布局 */
        align-items: center;    /* 让图片和文字在垂直方向上居中对齐 */
        justify-content: center;
        gap: 14rem;              /* 图片和文字之间的间距，可以根据喜好调整 */
    }

    .profile-image {
        height: auto;           /* 保持图片比例 */
        max-width: 340px;
        flex-shrink: 0;
    }

    .profile-text {
        margin: 0;              /* 清除默认的段落边距 */
        line-height: 1.6;       /* 让多行文字看起来更舒适 */
    }
</style>

<div class="profile-container">
    <img src="Tatsuya Yamada_PI.webp" alt="Tatsuya Yamada" class="profile-image"/>
    <p class="profile-text">
        Tatsuya Yamada, Ph.D. <br>
        Principal Investigator<br><br>
        Assistant Professor​<br>
        Department of Biochemistry​<br>
        N241 Beadle, University of Nebraska-Lincoln​<br>
        Lincoln, NE​<br>
        Email: tyamada2”@”unl.edu​<br>
        TEL: 402-472-6504​<br>
        <a href="CV-TY.pdf">CV</a>
    </p>
</div>


<div class="team-grid">
    <!-- 第 1 个人 -->
    <div class="team-member">
        <img src="Kimberly Borgstahl_Undergraduate Researcher.webp" class="team-avatar"/>
        <p class="member-name">Kimberly Borgstahl</p>
        <p class="member-role">Undergraduate Research Assistant</p>
    </div>
    <!-- 第 3 个人（新加的） -->
    <div class="team-member">
        <img src="Shun Sato_Posdoc Fellow.webp" class="team-avatar"/>
        <p class="member-name">Shun Sato</p>
        <p class="member-role">PostDoc Fellow</p>
    </div>
    <!-- 第 4 个人（新加的，自动换到第二行） -->
    <div class="team-member">
        <img src="Danny Vinton_Posbac Felllow.webp" class="team-avatar"/>
        <p class="member-name">Danny Vinton</p>
        <p class="member-role">PostBac Fellow</p>
    </div>
    <!-- 第 5 个人（新加的，自动换到第二行） -->
    <div class="team-member">
        <img src="Anna Tews_Graduate student (Accerelated M.S. course).webp" class="team-avatar"/>
        <p class="member-name">Anna Tews</p>
        <p class="member-role">Graduate student (Accerelated M.S. course)</p>
    </div>
    <h2 class="team-section-title">Alumni</h2>
    <div class="team-member">
        <img src="Vaishvika Balamurugan_Undergraduate Summer Internship.webp" class="team-avatar"/>
        <p class="member-name">Vaishvika Balamurugan</p>
        <p class="member-role">Research Intern Summer 2025</p>
    </div>
</div>


<p style="font-size: xx-large; margin-top: 5em; text-align:center">
We are actively searching for motivated scientists at all levels​!</p>
<p style="font-size: x-large;">
Positions of postdoctoral researchers, graduate students, undergraduate students, research assistants, and technicians are open to individuals who have enthusiasm for physiological research.</p>