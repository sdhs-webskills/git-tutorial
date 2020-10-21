안녕하세요 저는 황준일입니다. 나이는 27살입니다.

## 완전 초기설정
```sh
git config --global user.name "깃허브아이디"
git config --global user.email "깃허브이메일"
git remote add origin "깃허브주소""
```

## 반복
```sh
git add .
git commit -m "커밋 메세지"
git push origin master
```

## 다른 컴퓨터에서 코드 가져오기
```sh
git init # 한 번만 하면 됨
git remote add origin "깃허브주소" # 한 번만 하면 됨
git pull origin master
```