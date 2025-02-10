[]()<h1 align="center">Hey there 👋, I'm Benoit!</h1>
<p align="center">
    <i>Self proclaimed</i> <b>СЕО деградации</b> <i>и</i> <b>Чпокаюсь с кодом</b>
    <br />
    <br />
    <a href="https://hits.seeyoufarm.com/">
        <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmrbenoit&title_bg=%232D2D2D&count_bg=%2322AA55&icon=github.svg&icon_color=%23E7E7E7&title=Views%20%28Day%20%2F%20All%29&edge_flat=false" />
    </a>
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/years/mrbenoit?style=flat&labelColor=333333&logoColor=E7E7E7&color=0089FF&label=Years&logo=github" />
    </a>
    <a href="https://github.com/mrbenoit?tab=followers">
        <img src="https://img.shields.io/github/followers/mrbenoit?style=flat&labelColor=333333&logoColor=E7E7E7&color=8939FF&label=Followers&logo=github" />
    </a>
    <a href="#">
        <img src="https://img.shields.io/github/stars/mrbenoit?style=flat&affiliations=OWNER%2CCOLLABORATOR&labelColor=333333&logoColor=E7E7E7&color=EEAA00&label=Stars&logo=github" />
    </a>
    <br />
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/contributions/yearly/mrbenoit?style=flat&labelColor=333333&logoColor=E7E7E7&color=BA4AB9&label=Yearly%20Contributions&logo=github" />
    </a>
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/contributions/all/mrbenoit?style=flat&labelColor=333333&logoColor=E7E7E7&color=E96F24&label=All%20Contributions&logo=github" />
    </a>
    <br />
    <a href="#">
        <img src="https://img.shields.io/badge/Open_Source-❤-FF0069?style=flat&labelColor=333333&logoColor=E7E7E7">
    </a>
    <a href="#">
        <img src="https://img.shields.io/badge/PRs-Welcome-00CC00?style=flat&labelColor=333333&logoColor=E7E7E7">
    </a>
</p>

<br />

<br />

```py
from datetime import date
from sqlalchemy import select
from sqlalchemy import and_
from sqlalchemy.ext.asyncio import AsyncSession

from core.models import engine

class AboutMe():
    def __init__(self):
        async with AsyncSession(engine) as session:
            user = session.scalar(
                select(Users)
                .where(
                    and_(
                        user_id=1,
                        user_name='MrBenoit'
                    )
                )
            )
            
        print(user.username)
        > MrBenoit
        print(user.pronouns)
        > ["he", "him"]
        print(user.location)
        > {"Russian": "Moscow"}
        print(user.occupation)
        > Computer Science Student
        print(user.birthday)
        > 16.06.2004
        print(user.age)
        > 19
        print(user.hobbies)
        > ["Coding", "Gaming", "Anime", "Gym"]
        print(user.interests)
        > ["Programming", "Music", "Open Source"]

if __name__ == "__main__":
    me = AboutMe()
```

<br />

Projects 📦
-----------
- #### <a href="https://github.com/Somy-Discord-Bot"><img align="center" src="https://img.shields.io/badge/-Somy Discord Bot-7289da?style=for-the-badge"></a> -&nbsp;Discord bot with a variety of functionality

- #### <a href="https://github.com/MrBenoit/MatrixCalculator"><img align="center" src="https://img.shields.io/badge/-Matrix Calculator-3f4cba?style=for-the-badge"></a> -&nbsp;A simple matrix calculator. I wrote it out of boredom

- #### <a href="https://mrbenoit.ru"><img align="center" src="https://img.shields.io/badge/-mrbenoit.ru-2880bf?style=for-the-badge"></a> :&nbsp; My personal webpage

<br/>

Languages 💾
------------
[![Python](    https://img.shields.io/badge/-Python-333333?style=for-the-badge&logo=python&logoColor=white&labelColor=3776FB     )](https://www.python.org/)
[![Golang](    https://img.shields.io/badge/-Go-333333?style=for-the-badge&logo=go&logoColor=white&labelColor=3776FB     )](https://go.dev/)
[![SQL](    https://img.shields.io/badge/-PostgreSql-333333?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=2352b8     )](https://www.postgresql.org)
[![HTML CSS JS](https://img.shields.io/badge/-HTML_CSS_JS-333333?style=for-the-badge&logo=html5&logoColor=white&labelColor=DD3A0A)](https://htmlbook.ru)


Tools 🛠️
--------
[![VS Code](   https://img.shields.io/badge/-VS_Code-333333?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+VmlzdWFsIFN0dWRpbyBDb2RlPC90aXRsZT48cGF0aCBkPSJNMjMuMTUgMi41ODdMMTguMjEuMjFhMS40OTQgMS40OTQgMCAwIDAtMS43MDUuMjlsLTkuNDYgOC42My00LjEyLTMuMTI4YS45OTkuOTk5IDAgMCAwLTEuMjc2LjA1N0wuMzI3IDcuMjYxQTEgMSAwIDAgMCAuMzI2IDguNzRMMy44OTkgMTIgLjMyNiAxNS4yNmExIDEgMCAwIDAgLjAwMSAxLjQ3OUwxLjY1IDE3Ljk0YS45OTkuOTk5IDAgMCAwIDEuMjc2LjA1N2w0LjEyLTMuMTI4IDkuNDYgOC42M2ExLjQ5MiAxLjQ5MiAwIDAgMCAxLjcwNC4yOWw0Ljk0Mi0yLjM3N0ExLjUgMS41IDAgMCAwIDI0IDIwLjA2VjMuOTM5YTEuNSAxLjUgMCAwIDAtLjg1LTEuMzUyem0tNS4xNDYgMTQuODYxTDEwLjgyNiAxMmw3LjE3OC01LjQ0OHYxMC44OTZ6IiBmaWxsPSJ3aGl0ZSIvPjwvc3ZnPgo%3D&logoColor=white&labelColor=007ACC)](https://code.visualstudio.com/)[![JetBrains](   https://img.shields.io/badge/-JetBrains-333333?style=for-the-badge&logo=jetbrains&logoColor=black&labelColor=faa84b)](https://code.visualstudio.com/)
[![Zsh](       https://img.shields.io/badge/-Zsh-333333?style=for-the-badge&logo=zelle&logoColor=white&labelColor=FF2299               )](https://www.zsh.org/)
[![GitHub](    https://img.shields.io/badge/-GitHub-333333?style=for-the-badge&logo=github&logoColor=white&labelColor=222222           )](https://github.com/)
[![Git](       https://img.shields.io/badge/-Git-333333?style=for-the-badge&logo=git&logoColor=white&labelColor=F05032                 )](https://git-scm.com/)

My Specs 💻
-----------
![Desktop](https://img.shields.io/badge/Windows_11-Desktop-333333?style=for-the-badge&logo=pcgamingwiki&logoColor=white&labelColor=0078D4)
[![CPU](https://img.shields.io/badge/-Ryzen_7_5700X%20%E2%81%A0%20%E2%81%A0%20-333333?style=for-the-badge&logo=amd&logoColor=white&labelColor=ED1C24)](https://www.amd.com/en/products/cpu/amd-ryzen-7-5700x#product-specs)
[![GPU](https://img.shields.io/badge/-RTX_3070-333333?style=for-the-badge&logo=nvidia&logoColor=white&labelColor=76B900)](https://www.nvidia.com/en-us/geforce/graphics-cards/30-series/rtx-3070/)

![Desktop](https://img.shields.io/badge/Macbook_pro-333333?style=for-the-badge&logo=apple&logoColor=white&labelColor=black)
[![CPU](https://img.shields.io/badge/M1_Pro-333333?style=for-the-badge&logo=apple&logoColor=white&labelColor=black)](https://www.amd.com/en/products/cpu/amd-ryzen-7-5700x#product-specs)

Contact Me 📡
---------------
[![Discord](https://img.shields.io/badge/-%E2%81%A0%20%E2%81%A0%E2%81%A0%20%E2%81%A0mrbenoit00%E2%81%A0%20%E2%81%A0%20-333333?style=for-the-badge&logo=discord&logoColor=white&labelColor=5865F2)](https://discord.gg/5bb3H73deS)
[![Instagram](https://img.shields.io/badge/-@MrBenoit00-333333?style=for-the-badge&logo=instagram&logoColor=white&labelColor=E4405F)](https://www.instagram.com/MrBenoit00)\
[![Reddit](https://img.shields.io/badge/-%E2%81%A0%E2%81%A0u%2FMrBenoit00%E2%81%A0%E2%81%A0-333333?style=for-the-badge&logo=reddit&logoColor=white&labelColor=FF4500)](https://www.reddit.com/user/MrBenoit00)
[![Patreon](https://img.shields.io/badge/-@MrBenoit-333333?style=for-the-badge&logo=patreon&logoColor=white&labelColor=FF4500)](https://www.patreon.com/MrBenoit)\
[![X](https://img.shields.io/badge/-@MrBenoit00-333333?style=for-the-badge&logo=X&logoColor=white&labelColor=000000)](https://twitter.com/MrBenoit00)
[![GitHub](https://img.shields.io/badge/-%E2%81%A0%20%E2%81%A0MrBenoit%20%E2%81%A0%E2%81%A0-333333?style=for-the-badge&logo=github&logoColor=white&labelColor=181717)](https://github.com/MrBenoit)\
[![Telegram](https://img.shields.io/badge/-@MrBenoit-333333?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1DA1F2)](https://t.me/mrbenoit)