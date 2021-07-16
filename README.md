# Git 백업 방법  


## 원격저장소 만들기 
* github(가장 유명함)
* gitlab 

### Github 
* 원격 저장소에서 깃을 사용
* 협업 프로젝트에 사용
* 개발 이력 남기기
* 오픈 소스에 참여



### 지역 저장소를 원격 저장소에 연결하기
``` 
git remote add origin (원격 저장소 https 주소)
```

### 지역 저장소와 연결된 원격 저장소를 확인
```
git remote -v
```




### 원격 저장소에 올리기 & 내려받기
> push : 지역 저장소의 소스를 원격 저장소로 올리는 것   
  pull : 원격 저장소에서 지역 저장소로 내려 받는 것 



### 원격 저장소에 push 하기
```
git push -u origin master
```

### 원격 저장소에서 pull 하기 
```
git pull origin master
```