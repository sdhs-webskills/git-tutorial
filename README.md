안녕하세요 저는 황준일입니다. 나이는 27살입니다.



// 완전 초기설정
git config --global user.name "깃허브아이디"
git config --global user.email "깃허브이메일"
git remote add origin "깃허브주소""


// 반복
git add .
git commit -m "커밋 메세지"
git push origin master

// 다른 컴퓨터
git pull origin master

// 위의 과정을 반복하면 됩니다.