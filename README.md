<h1 align="center">Hey there 👋, I'm Benoit!</h1>
<p align="center">
    <b>I am learning to program in order to simplify my life and create something new</b>
    <br />
    <br />
    <a href="https://github.com/MrBenoit">
        <img src="https://badges.strrl.dev/years/mrbenoit?style=flat&labelColor=333333&logoColor=&color=FFFFFF&label=Years&logo=github" />
    </a>
    <a href="https://github.com/MrBenoit?tab=followers">
        <img src="https://img.shields.io/github/followers/MrBenoit?style=flat&labelColor=333333&logoColor=E7E7E7&color=8939FF&label=Followers&logo=github" />
    </a>
    <a href="https://github.com/MrBenoit">
        <img src="https://img.shields.io/github/stars/MrBenoit?style=flat&affiliations=OWNER%2CCOLLABORATOR&labelColor=333333&logoColor=E7E7E7&color=EEAA00&label=Stars&logo=github" />
    </a>
    <a href="https://github.com/MrBenoit">
        <img src="https://img.shields.io/badge/Open_Source-❤-FF0069?style=flat&labelColor=333333&logoColor=E7E7E7">
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

- #### <a href="https://github.com/MrBenoit/Lapis"><img align="center" src="https://img.shields.io/badge/-Lapis-7289da?style=for-the-badge"></a> -&nbsp;Discord bot with a variety of functionality

- #### <a href="https://github.com/MrBenoit/MatrixCalculator"><img align="center" src="https://img.shields.io/badge/-Matrix Calculator-3f4cba?style=for-the-badge"></a> -&nbsp;A simple matrix calculator. I wrote it out of boredom

- #### <a href="https://mrbenoit.ru"><img align="center" src="https://img.shields.io/badge/-mrbenoit.ru-2880bf?style=for-the-badge"></a> :&nbsp; My personal website | Not work

<br />

Languages 💾
------------

[![Python](    https://img.shields.io/badge/-Python-333333?style=for-the-badge&logo=python&logoColor=white&labelColor=3776FB     )](https://www.python.org/)
[![PostgreSQL](    https://img.shields.io/badge/-PostgreSql-333333?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=2352b8     )](https://www.postgresql.org)
![HTML](    https://img.shields.io/badge/-HTML-333333?style=for-the-badge&logo=HTML&logoColor=white&labelColor=2352b8     )
![CSS](    https://img.shields.io/badge/-CSS-333333?style=for-the-badge&logo=css&logoColor=white&labelColor=2352b8     )


Tools 🛠️
--------

[![VS Code](   https://img.shields.io/badge/-VS_Code-333333?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=007ACC)](https://code.visualstudio.com/)
[![JetBrains](   https://img.shields.io/badge/-JetBrains-333333?style=for-the-badge&logo=jetbrains&logoColor=black&labelColor=faa84b)](https://code.visualstudio.com/)
[![Zsh](       https://img.shields.io/badge/-Zsh-333333?style=for-the-badge&logo=zelle&logoColor=white&labelColor=FF2299               )](https://www.zsh.org/)
[![GitHub](    https://img.shields.io/badge/-GitHub-333333?style=for-the-badge&logo=github&logoColor=white&labelColor=222222           )](https://github.com/)

My Specs 💻
-----------

![Desktop](https://img.shields.io/badge/Desktop-333333?style=for-the-badge&logo=ubuntu&logoColor=white&labelColor=00A4EF)
[![CPU](https://img.shields.io/badge/-Ryzen_5_5600X%E2%81%A0%20%E2%81%A0%20-333333?style=for-the-badge&logo=amd&logoColor=white&labelColor=ED1C24)](https://www.amd.com/en/products/cpu/amd-ryzen-5-5600#product-specs)
[![GPU](https://img.shields.io/badge/-Nvidia_RTX_3070-333333?style=for-the-badge&logo=nvidia&logoColor=white&labelColor=76B900)](https://www.amd.com/en/products/apu/amd-ryzen-5-3500u#product-specs)

[![Mac OS](  https://img.shields.io/badge/-Laptop-333333?style=for-the-badge&logo=apple&logoColor=white&labelColor=black        )]()
[![CPU](https://img.shields.io/badge/-M1-333333?style=for-the-badge&logo=apple&logoColor=white&labelColor=black)](https://www.amd.com/en/products/apu/amd-ryzen-5-3500u#product-specs)

Contact Me 📡
---------------

[![Discord](https://img.shields.io/badge/-%E2%81%A0%20%E2%81%A0%E2%81%A0%20%E2%81%A0mrbenoit00%E2%81%A0%20%E2%81%A0%20-333333?style=for-the-badge&logo=discord&logoColor=white&labelColor=5865F2)](https://discord.gg/5bb3H73deS)
[![Instagram](https://img.shields.io/badge/-@MrBenoit00-333333?style=for-the-badge&logo=instagram&logoColor=white&labelColor=E4405F)](https://www.instagram.com/MrBenoit00)\
[![Reddit](https://img.shields.io/badge/-%E2%81%A0%E2%81%A0u%2FMrBenoit00%E2%81%A0%E2%81%A0-333333?style=for-the-badge&logo=reddit&logoColor=white&labelColor=FF4500)](https://www.reddit.com/user/MrBenoit00)
[![Twitter](https://img.shields.io/badge/-@MrBenoit00-333333?style=for-the-badge&logo=twitter&logoColor=white&labelColor=1DA1F2)](https://twitter.com/MrBenoit00)\
[![GitHub](https://img.shields.io/badge/-%E2%81%A0%20%E2%81%A0MrBenoit%20%E2%81%A0%E2%81%A0-333333?style=for-the-badge&logo=github&logoColor=white&labelColor=181717)](https://github.com/MrBenoit)
[![Telegram](https://img.shields.io/badge/-@MrBenoit-333333?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1DA1F2)](https://t.me/mrbenoit)



GitHub Stats 📊
---------------

![Benoit GitHub Stats](https://github-readme-stats.vercel.app/api?username=mrbenoit&show_icons=true&theme=material-palenight)

Pins 📌
---------------

[![Lapis](https://github-readme-stats.vercel.app/api/pin/?username=mrbenoit&repo=Lapis&theme=material-palenight)](https://github.com/mrbenoit/Lapis)
[![MatrixCalculator](https://github-readme-stats.vercel.app/api/pin/?username=mrbenoit&repo=MatrixCalculator&theme=material-palenight)](https://github.com/mrbenoit/MatrixCalculator)
