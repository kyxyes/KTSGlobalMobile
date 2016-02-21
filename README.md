https://guides.github.com/features/mastering-markdown/

# 개발 환경 설치
## node
### 설치
##### node 는 버전 호환성 문제로 4.1.x lts 버전을 설치한다.
 기본 패키지 모두 설치 - npm install


## bower 설치
### 설치
##### npm install -g bower
    bower init
    bower install <package>
    bower uninstall <package>
    bower list
    bower search <package>
    bower lookup <package>
    bower info <package>


    bower install jquer --save
    bower install qunit --save-dev

    bower install ng-idle


# .gitignore 정상 처리 안될 경우
###
'''
$ git rm -r --cached .
$ git add .
$ git commit -m "git ignore appled"
$ git push
'''

## 구현 방향
### v1
##### 우선은 기본적인 기능을 완성하는데 주력

### v2
##### activecampaign과 같이 인트로와 솔루션을 나누어서 구현


## This is an <h2> tag
###### This is an <h6> tag




```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column