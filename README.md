git init		:working directory 설정;
echo '내용' > README.md :README.md 만들기;
git add README.md	:README 를 staged로 만들기(commit가능하도록);
git commit		:staged -> unmodified;

(로컬저장소와 원격 저장소 동기화);
git remote add origin https://github.com/JinSeoNWoOO/hw.git;
git branch -M main;
git push -u origin main;
