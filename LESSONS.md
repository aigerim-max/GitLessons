# 25 сабақ: Git және GitHub

Бұл жұмыс дәптері берілген [YouTube плейлистінің](https://www.youtube.com/playlist?list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT) тақырып ретімен жасалды. Әр сабақтың нақты видеосын қосып, сол бөлімге келгенде кідіртіп, экрандағы әрекетпен салыстырыңыз. Төмендегі жолдар экранда көрсетілетін қадамдар; олар өздігінен аккаунттағы әрекет орындалды дегенді білдірмейді.

## Қай жерге жазу керек?

VS Code-та **Terminal → New Terminal** басыңыз. Терминал VS Code терезесінің төменгі панелінде ашылады. Командаларды сол панельге, жоба бумасы ашық тұрған кезде енгізіңіз. Браузердегі GitHub әрекеттері арнайы көрсетілген сабақтарда ғана GitHub беттерін қолданыңыз.

## Сабақтар

### 1. Git деген не және не үшін керек?
**Видео:** [#1 — Что такое Git и зачем он нужен](https://www.youtube.com/watch?v=7uiM8BJ_ZMM&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=1)
- **Ашу:** VS Code-та GitLessons бумасын, кейін Source Control (`Ctrl+Shift+G`) бөлімін ашыңыз.
- **Көрсету:** файл өзгерісі мен commit тарихын салыстырыңыз.
- **Команда:** `git status` және `git log --oneline`.
- **Айту:** «Git өзгерістер тарихын сақтайды. GitHub репозиторийді интернетте сақтап, бөлісуге көмектеседі».
- **Күйі:** түсінік тақырыбы; білімді экраннан растау мүмкін емес.

### 2. Git орнату
**Видео:** [#2 — Установка Git](https://www.youtube.com/watch?v=LHuott_frOA&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=2)
- **Ашу:** VS Code → Terminal → New Terminal.
- **Көрсету:** Git нұсқасының нөмірі.
- **Команда:** `git --version`.
- **Айту:** «Нұсқа нөмірі шықса, Git терминалда іске қосылып тұр».
- **Күйі:** Git пәрмендері осы репозиторийде орындалған.

### 3. Git репозиторийін инициализациялау
**Видео:** [#3 — Инициализация репозитория Git](https://www.youtube.com/watch?v=km64378uMCs&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=3)
- **Ашу:** VS Code-та GitLessons бумасы; Explorer және Source Control.
- **Көрсету:** `.git` репозиторийі және алғашқы commit.
- **Команда:** `git status`, `git log --oneline -1`.
- **Айту:** «Бұл бумада Git репозиторийі бұрыннан бар. Оған қайтадан `git init` орындамаймын».
- **Күйі:** расталған.

### 4. Бір нәрсе жұмыс істемесе не істеу керек?
**Видео:** [#4 — Что делать, если ничего не работает](https://www.youtube.com/watch?v=CeP46LN-JL0&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=4)
- **Ашу:** VS Code → Terminal → New Terminal.
- **Көрсету:** нақты қате мәтіні; қате болмаса ойдан қате көрсетпеңіз.
- **Команда:** `git status`, `git remote -v`.
- **Айту:** «Алдымен қатені оқып, тармақ пен remote адресін тексеремін. Қате түсініксіз болса, жою пәрмендерін орындамаймын».
- **Күйі:** бұрынғы push ақауы шешілген; видеодағы бүкіл мысал расталған жоқ.

### 5. GitHub-та тіркелу
**Видео:** [#5 — Регистрация на GitHub](https://www.youtube.com/watch?v=-bsOFzKoA0I&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=5)
- **Ашу:** GitHub → профиль белгішесі → Your repositories.
- **Көрсету:** өз аккаунтыңыз және `GitLessons` репозиторийі; құпия деректі жасырыңыз.
- **Команда:** командалық қадам жоқ.
- **Айту:** «GitHub аккаунтымда GitLessons репозиторийі бар. Құпиясөз бен растау кодын ешкімге көрсетпеймін».
- **Күйі:** репозиторий иесі мен аккаунт расталған.

### 6. Кодты GitHub-қа жүктеу
**Видео:** [#6 — Загрузка кода на GitHub](https://www.youtube.com/watch?v=y94qMJlTtsM&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=6)
- **Ашу:** VS Code терминалы және GitHub → GitLessons → Code.
- **Көрсету:** push нәтижесі және GitHub-тағы файлдар.
- **Команда:** `git push -u origin main`.
- **Айту:** «`main` тармағын `origin/main`-ға жіберіп, бақылау байланысын орнаттым».
- **Күйі:** алғашқы push терминал нәтижесімен расталған.

### 7. Git-тің графикалық интерфейсі
**Видео:** [#7 — Работа с графическим интерфейсом](https://www.youtube.com/watch?v=d4CMlsqTXN4&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=7)
- **Ашу:** VS Code → Source Control (`Ctrl+Shift+G`).
- **Көрсету:** Changes тізімі, файлды басқандағы diff, stage және commit өрісі.
- **Команда:** міндетті емес; күйді тексеру үшін `git status`.
- **Айту:** «Source Control өзгерген файлдарды көрсетеді. Commit жергілікті тарихқа сақтайды, ал push GitHub-қа жібереді».
- **Күйі:** VS Code-тағы интерфейс әрекеті расталған жоқ.

### 8. Код жүктеудің аралас тәсілі
**Видео:** [#8 — Комбинированный способ загрузки кода](https://www.youtube.com/watch?v=bSriiUxMdLo&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=8)
- **Ашу:** VS Code-та файлды өзгертіңіз; кейін Source Control мен Terminal-ды қолданыңыз.
- **Көрсету:** графикалық түрде stage жасау және терминалдағы push.
- **Команда:** `git add <файл>`, `git commit -m "Update lesson"`, `git push`.
- **Айту:** «Файлды интерфейсте дайындап, терминал арқылы commit пен push жасай аламын».
- **Күйі:** дәл осы аралас тәсілмен орындалғаны расталған жоқ.

### 9. GitHub-та репозиторийді жою
**Видео:** [#9 — Как удалить репозиторий на GitHub](https://www.youtube.com/watch?v=psesQl6Rfhw&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=9)
- **Ашу:** GitHub репозиторийі → Settings → Danger Zone.
- **Көрсету:** жою баптауының орнын ғана көрсетіңіз; растау батырмасын баспаңыз.
- **Команда:** жоқ.
- **Айту:** «Бұл әрекет репозиторийді өшіруі мүмкін. Өз жобамды жоймаймын».
- **Күйі:** әдейі орындалмайды; пайдаланушы нақты репозиторийді жоймауды сұрады.

### 10. Репозиторийді клондау
**Видео:** [#10 — Клонирование репозитория](https://www.youtube.com/watch?v=M2eC0O8H0Yo&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=10)
- **Ашу:** GitHub → Code → HTTPS; терминалда клон баратын буманың ата-анасына өтіңіз.
- **Көрсету:** жаңа бумада файлдар мен тарих пайда болғанын көрсетіңіз.
- **Команда:** `git clone https://github.com/aigerim-max/GitLessons.git`.
- **Айту:** «Clone репозиторийді commit тарихымен бірге жаңа бумаға көшіреді».
- **Күйі:** жаңа клон жасалған жоқ.

### 11. Git Graph кеңейтімі
**Видео:** [#11 — Расширение Git Graph](https://www.youtube.com/watch?v=_RHh-Pk3kPA&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=11)
- **Ашу:** VS Code → Extensions (`Ctrl+Shift+X`) → Git Graph.
- **Көрсету:** орнатылған кеңейтімдегі commit графигі.
- **Команда:** балама харагдац: `git log --oneline --graph --decorate --all`.
- **Айту:** «График commit-тердің ретін және тармақтардың қалай дамығанын көрсетеді».
- **Күйі:** пәрмендік график бар; кеңейтім орнатылғаны расталған жоқ.

### 12. Git alias
**Видео:** [#12 — Алиасы](https://www.youtube.com/watch?v=v1plgmrD8R8&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=12)
- **Ашу:** VS Code → Terminal.
- **Көрсету:** `git st` және `git lg` қысқа атауларын орындаңыз.
- **Команда:** `git config --local alias.st "status --short --branch"`; `git config --local alias.lg "log --oneline --graph --decorate --all"`.
- **Айту:** «Alias осы репозиторийде ұзын пәрменді қысқа атаумен іске қосады».
- **Күйі:** жергілікті баптаулар жасалған.

### 13. Өзгерістерді қайтару
**Видео:** [#13 — Отмена изменений в коде](https://www.youtube.com/watch?v=BSHxwpBv-WQ&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=13)
- **Ашу:** VS Code-та тек сынақ файлын өзгертіп, Source Control diff-ийг хар.
- **Көрсету:** `git diff` арқылы өзгерісті тексеріп, тек сынақ файлын қайтарыңыз.
- **Команда:** `git restore -- <сынақ-файл>`.
- **Айту:** «Алдымен өзгерісті қараймын; содан кейін тек сынақ файлын қайтарамын».
- **Күйі:** негізгі жоба файлындағы өзгерісті қайтару жаттығуы орындалған жоқ.

### 14. Тармақтар, 1-бөлім
**Видео:** [#14 — Работа с ветками, часть 1](https://www.youtube.com/watch?v=PEwtswYFvLo&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=14)
- **Ашу:** VS Code → төменгі сол жақтағы тармақ белгісі немесе Source Control тармақ мәзірі.
- **Көрсету:** жаңа `feature/kazakh-lessons` тармағы.
- **Команда:** `git switch -c feature/kazakh-lessons`.
- **Айту:** «Feature тармағын негізгі жұмыстан бөлек жасау үшін аштым».
- **Күйі:** расталған.

### 15. Тармақтар, 2-бөлім
**Видео:** [#15 — Работа с ветками, часть 2](https://www.youtube.com/watch?v=gCuHWIDQMSo&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=15)
- **Ашу:** VS Code терминалы және төменгі сол жақтағы тармақ атауы.
- **Көрсету:** feature тармағындағы сабақ файлының commit-і.
- **Команда:** `git add .`; `git commit -m "Add Kazakh Git lesson workbook"`.
- **Айту:** «Жоба бетін feature тармағында commit жасадым; main өзгеріссіз қалды».
- **Күйі:** расталған.

### 16. Тармақтарды біріктіру
**Видео:** [#16 — Работа с ветками, часть 3: слияние веток](https://www.youtube.com/watch?v=hDcsxin9ZEM&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=16)
- **Ашу:** VS Code терминалы; `main` тармағына ауысыңыз.
- **Көрсету:** feature commit пен merge commit-ін графиктен көрсетіңіз.
- **Команда:** `git switch main`; `git merge --no-ff feature/kazakh-lessons`.
- **Айту:** «Тексерілген feature өзгерістерін main тармағына біріктірдім».
- **Күйі:** жергілікті merge расталған; соңғы commit-тер GitHub-қа push жасалмаған.

### 17. Markdown және README
**Видео:** [#17 — Язык Markdown и файл README](https://www.youtube.com/watch?v=8lEDTrr-G4U&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=17)
- **Ашу:** VS Code Explorer → `README.md`; қажет болса оң жақ батырма → Open Preview.
- **Көрсету:** тақырып, бөлім, сілтеме, пәрмен үлгісі.
- **Команда:** файлға Markdown мәтіні жазылады; Git пәрмені қажет емес.
- **Айту:** «README жобаның мақсатын және оны ашу жолын түсіндіреді».
- **Күйі:** README жасалған.

### 18. Markdown синтаксисі
**Видео:** [#18 — Синтаксис языка Markdown](https://www.youtube.com/watch?v=jCjuXf4WPrQ&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=18)
- **Ашу:** VS Code-та `README.md` → Open Preview.
- **Көрсету:** `# тақырып`, тізім, қалың мәтін және код белгілеуі.
- **Команда:** Markdown мысалы: `## Бөлім`, `- тізім`, `` `git status` ``.
- **Айту:** «Markdown GitHub-та мәтінді оқуға ыңғайлы пішімдейді».
- **Күйі:** README мен сабақ бетінде қолданылған.

### 19. Редактор баптауларын синхрондау
**Видео:** [#19 — Синхронизация настроек редактора](https://www.youtube.com/watch?v=4HgXlmH1yOg&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=19)
- **Ашу:** VS Code → Accounts → Backup and Sync Settings / Turn on Settings Sync.
- **Көрсету:** Settings Sync күйі; кіру кодын жарияламаңыз.
- **Команда:** интерфейсте орындалады.
- **Айту:** «Бұл VS Code баптауларын құрылғылар арасында синхрондайды; Git файлы емес».
- **Күйі:** VS Code аккаунтындағы синхрондау орындалған жоқ.

### 20. Gist
**Видео:** [#20 — Что такое Gist и как с ним работать](https://www.youtube.com/watch?v=y-zATLY24eA&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=20)
- **Ашу:** `gist.github.com` → New gist.
- **Көрсету:** құпия емес қысқа мәтін/код үзіндісі және оның Gist беті.
- **Команда:** интерфейсте орындалады.
- **Айту:** «Gist қысқа код немесе мәтінді бөлісуге арналған».
- **Күйі:** аккаунтта Gist жасалған жоқ.

### 21. GitHub Pages
**Видео:** [#21 — Бесплатный хостинг GitHub Pages](https://www.youtube.com/watch?v=o-iV85RkoHE&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=21)
- **Ашу:** GitHub → GitLessons → Settings → Pages → Build and deployment.
- **Көрсету:** Deploy from a branch → `main` → `/(root)` таңдауы және сайт URL-і пайда болғанда сол URL.
- **Команда:** алдымен өзгерістерді жіберу үшін `git push`.
- **Айту:** «Pages репозиторийдегі статикалық `index.html` бетті интернетте жариялайды».
- **Күйі:** Pages қосылғаны/URL жасалғаны расталмаған.

### 22. GitHub профилі және автор беті
**Видео:** [#22 — Портфолио и страница автора на GitHub](https://www.youtube.com/watch?v=w57rX5YDEio&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=22)
- **Ашу:** GitHub профиль белгісі → Your profile; қажет болса профиль README репозиторийін жасау беті.
- **Көрсету:** профиль және жобалар тізімі; email-ді ашық көрсетпеңіз.
- **Команда:** профиль бетінде орындалады.
- **Айту:** «Профиль GitHub жобаларымды таныстырады. Арнайы профиль README бөлек бапталады».
- **Күйі:** профиль README жасалған жоқ.

### 23. Fork және Pull Request
**Видео:** [#23 — Как сделать Fork и Pull Request](https://www.youtube.com/watch?v=hQTARFi9IOY&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=23)
- **Ашу:** жалпыға ашық басқа репозиторий → Fork; өзгерісті өз fork-қа жіберіп, Contribute → Open pull request.
- **Көрсету:** fork пен PR айырмасын көрсетіңіз. Мұғалім тапсырмаса, бөтен жобаға PR жібермеңіз.
- **Команда:** fork клонданғаннан кейін `git push -u origin <тармақ>`.
- **Айту:** «Fork жеке көшірме ашады, Pull Request өзгерісті бастапқы жобаға қосуды ұсынады».
- **Күйі:** fork немесе PR жасалған жоқ.

### 24. Репозиторийден файлдарды алып тастау ережесі
**Видео:** [#24 — Как исключить файлы из репозитория](https://www.youtube.com/watch?v=RvthmUPfcvY&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=24)
- **Ашу:** VS Code Explorer → `.gitignore`.
- **Көрсету:** уақытша файл үлгілері және Git оларды елемейтінін.
- **Команда:** `git check-ignore -v temp/example.log`.
- **Айту:** «`.gitignore` Git қадағаламауы керек файлдарды белгілейді. Ол бұрын commit жасалған файлды тарихтан өшірмейді».
- **Күйі:** файл жасалған.

### 25. Қорытынды
**Видео:** [#25 — Подведение итогов курса](https://www.youtube.com/watch?v=2ZWqy2xI1JI&list=PLuY6eeDuleIMtvOvJBAbakwcIdEt7IAXT&index=25)
- **Ашу:** VS Code → Explorer/Source Control; GitHub → Code/Commits.
- **Көрсету:** `index.html`, `styles.css`, `README.md`, `LESSONS.md`, `.gitignore`, commit тарихы және Pages URL тек пайда болса.
- **Команда:** `git status --short --branch`; `git log --oneline --graph --decorate --all`; `git push`.
- **Айту:** «Жоба файлдары, commit-тер мен тармақтар жергілікті Git тарихында сақталады; push оларды GitHub-пен синхрондайды».
- **Күйі:** барлық 25 видеоны көріп, қайталау орындалды деп белгіленген жоқ.

## Осы репозиторийдегі расталған күй

Жергілікті `main` тармағына қазақша сабақ беті, README және `.gitignore` қосылды; feature тармағы жасалып, main-ге merge жасалды. `origin` — `https://github.com/aigerim-max/GitLessons.git`. Алғашқы push сәтті болған; кейін жасалған жергілікті commit-терді GitHub-қа жіберу бөлек керек. GitHub веб-сайтында орындалатын Gist, Pages, профиль және Fork/PR қадамдары жоғарыда нұсқаулық ретінде берілген, бірақ орындалды деп белгіленбейді.

> Репозиторийді жою, құпия дерек жариялау немесе танымайтын бөтен жобаға Pull Request жіберу орындалмайды.
