---
layout: post

title: 애드투페이퍼 개발자의 하루
cover_image: blog-cover.png

excerpt: "개발자 1인칭 시점에서 애드투페이퍼의 하루를 소개합니다."

author:
  name: 방신우
  bio: Software Engineer
  image: bsw.png
  page: http://github.com/sinwoobang
---

<style>
.image-wrapper {
    text-align: center;
}

.image-caption {
	display:block;
    color: #777;
    font-size:.8em;
    margin-top:-.8em;
    margin-bottom:1.2em;
}
</style>


안녕하세요. [애드투페이퍼](http://add2paper.com) 백엔드 개발자 방신우입니다. 개발자 1인칭 시점에서 회사 생활을 하루로 압축하여 적었습니다. 간략하게 저희 팀 분위기를 느끼실 수 있을 겁니다. 비개발자분들도 이해하실 수 있도록 용어를 최대한 풀어썼습니다. 짧게 설명하기 어려운 내용은 각주를 썼으니 참고해주세요.

이 글은 스포카 기술 블로그 [A씨의 일주일](http://spoqa.github.io/2012/03/20/week-in-spoqa.html)에서 영감을 받았습니다.


## 참고사항
* 업무시간은 오전 10시 ~ 오후 7시입니다.
* 업무용 메신저로 [슬랙(Slack)](http://slack.com)을 이용합니다.
* 슬랙에는 관리자가 설정한 대로 행동하는 봇(bot)이 존재합니다.
* 슬랙에는 채널(channel)이 존재합니다. 카카오톡의 단체대화방과 같은 개념입니다.

<br/>

## 오전 10시 : 업무 시작
팀원들과 아침 인사를 나누고 자리에 앉았습니다. 때마침 10시를 맞아 슬랙(Slack) 봇이 일정을 보내놓았군요.
{% include _image.html img="/images/good_morning/start.png" caption="[그림1: 구글 캘린더를 연동한 슬랙]" %}
* 애디팀 크리스마스 이벤트 / 송년회 안내 (오후 6시 ~ 오후 6시 30분)
* 미니세미나 (오후 6시 30분 ~ 오후 7시)
* 프로덕트팀 회식 (오후 7시 ~ 오후 9시)

&nbsp;&nbsp;벌써 2015년이 끝나갑니다. 송년회 안내, 회식 등 연말을 알리는 일정이 있습니다. 평소에는 오후 7시에 업무를 마무리 하지만, 각종 안내가 있으니 오후 6시까지 일을 마무리해야겠다는 생각도 드는군요.

<br/>

## 개발사항 체크
오늘 할 일을 확인하기 위해 어제 개발했던 사항들을 정리하려 합니다. 저희 팀은 모든 개발 사항을 한 채널에 기록하고 이름을 dev 라고 정했습니다. dev 채널을 통해 어제 개발했던 사항을 확인해야겠군요.
{% include _image.html img="/images/good_morning/dev_channel.png" caption="[그림2: 슬랙 dev 채널]" %}
&nbsp;&nbsp;이전의 개발 기록들을 확인했습니다. 동시에 어제 무슨 일을 했는지 상기합니다. 오늘 할 일에 대한 구상이 잡혀가는군요.

<br/>

## 오전 10시 15분 : 애딧페이 아침마당

{% include _image.html img="/images/good_morning/additpay_haena.png" caption="[그림3: 아침마당 장소를 공지하시는 대표님]" %}

대표님께서 아침마당 장소를 공지해주셨습니다. [애딧페이](http://additpay.com) 서비스는 다 알고 계신가요? 모르시는 분은 다음 [기사](http://www.edaily.co.kr/news/NewsRead.edy?SCD=JE41&newsid=01977846609562112)를 참고해주세요.

&nbsp;&nbsp;저희 팀은 얼마 전에 오픈한 애딧페이 서비스의 성장을 위해 매일 아침 15분간 성장 지표를 공유합니다. 매일 아침에 잠깐 회의를 한다고 해서 이름을 아침마당으로 지었습니다.
의도한 대로 마케팅 수치가 나왔는지, 주 이탈은 어디서 발생하는지 경영기획팀 이외 팀원들도 이 회의를 통해 확인할 수 있습니다.

&nbsp;&nbsp;애딧페이는 꾸준한 성장세를 보입니다. 오늘 지표도 역시 그러했고요. 이제 뿌듯한 마음으로 개발할 수 있겠군요.

<br/>

## 오전 10시 30분 : 스탠드업 미팅

오전 10시 30분에는 팀원 간 업무 공유를 위해 스탠드업 미팅을 합니다. 스탠드업 미팅은 [애자일 개발](https://ko.wikipedia.org/wiki/%EC%95%A0%EC%9E%90%EC%9D%BC_%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4_%EA%B0%9C%EB%B0%9C)에서 사용하는 회의법입니다.
팀원들은 미팅 시작 전, 구글 Docs에 다음과 같은 내용을 적습니다.

* 어제 한 일은 무엇인가?
* 오늘 할 일은 무엇인가?
* 일하는데 장애물로는 무엇이 있는가/있었는가?

모두 일어나서 각자 양식에 맞춰 업무 내용을 공유합니다.[^1] 모두 일어나서 하는 이유는 다음을 지키기 위함입니다.

* 짧은 미팅시간
* 높은 집중력

&nbsp;&nbsp;적기부터 대화까지 모든 과정을 15분 내로 끝냅니다. 애드투페이퍼 개발팀은 크게 백엔드[^2]/프론트엔드[^3]/윈도우 클라이언트[^4] 3분류로 나뉩니다. 스탠드업 미팅은 각자 다른 일을 하는 개발자들 간 소통 벽을 낮춰줍니다.

<br/>

## 오전 10시 45분 : 요약 지표 확인

본 서버 - 사내 서버 간 데이터베이스(DB) 동기화가 끝났군요. 클로이 모레츠가 활동 유저(Active User) 요약 지표를 알려줍니다. 클로이 모레츠는 저희가 미리 설정한 각종 알리미 봇 입니다. 매일 아침 DB 동기화가 끝나면 메인 채널에 지표를 알립니다. 이를 통해 팀원 모두 앱 AU 상황을 알 수 있습니다.
{% include _image.html img="/images/good_morning/chloe.png" caption="[그림4: 요약 지표를 알려주는 클로이 모레츠(봇)]" %}

<br/>

## 낮 12시 : 점심 식사

바쁘게 일하다 보니 어느덧 점심시간입니다. 업무 관련 내용이 아니므로 점심 메뉴 선정은 카카오톡 단체채팅방을 통해 정합니다. 디자이너 Y님께서 점심 메뉴를 선정하셨군요!
{% include _image.html img="/images/good_morning/kakao_lunch.png" caption="[그림5: 점심시간을 알리는 소리, 까똑!]" %}

<br/>

## 오후 2시 : 작업 내용 전송

개발하던 내용을 반 정도 끝냈습니다. 작업 내용을 공유하는 게 좋겠군요. 개발팀 전체가 공유하는 원격 코드 저장소[^5]에 작업하던 내용을 전송[^6]하려 합니다.

우선 작업 내용에 이상이 없는지, 시뮬레이터를 통해 테스트합니다.
{% include _image.html img="/images/good_morning/simulators.png" caption="[그림6: 시뮬레이터로 켠 애드투페이퍼 앱]" %}

&nbsp;&nbsp;확인해보니 작동에는 문제가 없습니다. 이젠 코드를 확인합니다. 코드 버전 관리 기능을 사용하면 쉽게 작업 전/후를 비교할 수 있습니다. [1줄로 짤 코드를 누가 10줄로 만들었어요? 에러 잡기 힘들게](https://www.youtube.com/watch?v=clHOuZmqaZA)와 같은 상황이 없도록 꼼꼼히 코드를 살핍니다.
{% include _image.html img="/images/good_morning/git_highlighting.png" caption="[그림7: 작업 전/후 비교]" %}

코드에도 문제가 없어 보입니다. 이제 원격 코드 저장소로 코드를 전송합니다.

{% include _image.html img="/images/good_morning/codeship.png" caption="[그림8: 일차적으로 코드를 점검해주는 CI]" %}

&nbsp;&nbsp;전송한 지 약 5분이 지났습니다. dev 채널을 확인해보니 CI 결과 메시지가 와있습니다. 과정을 통과했군요. 참, CI를 모르신다고요? CI에 대한 자세한 설명과 애드투페이퍼에서의 활용법은 [테스트와 CI](http://add2paper.github.io/2014/08/06/Test-And-CI/) 글을 통해 확인하실 수 있습니다.

    프로젝트 규모가 커지면 빌드와 테스트하는 데에 많은 자원적, 시간적 비용이 들게 됩니다. 이런 문제점을 해결하기 위해 한 시스템에서 빌드와 테스트를 수행하는데 이를 CI(Continuous Integration) 시스템이라고 합니다.

    - 애드투페이퍼 엔지니어링 블로그 "테스트와 CI"

CI를 통과했다는 것은 제가 전송한 코드가 실제 서버 환경에서 문제없이 작동한다는 것을 의미합니다. 이제 남은 코드를 작업하러 가야겠습니다.

<br/>

## 오후 4시 : 작업 완료

시간이 흘러 작업을 완료했습니다. 오후 2시에 했듯, 개발 내용 점검 후 코드 저장소에 전송합니다. 시뮬레이터, 작업 전/후 비교, CI를 끝냈습니다. 이젠 작업 내용을 master에 붙여야 합니다.
{% include _image.html img="/images/good_morning/branches.png" caption="[그림9: 나누어진 작업내용들]" %}

&nbsp;&nbsp;5가지 색깔 띠가 [그림9]에 있습니다. 색깔 띠를 각각 branch(직역: 나뭇가지)라고 부릅니다. 나무에 기둥을 중심으로 가지가 뻗어있는 걸 연상해주세요.
저희 팀은 큰 작업 단위를 branch로 나눈 후, 작업 완료후에 메인 branch인 master로 합칩니다. 그림의 파랑, 초록, 보라, 노랑 띠들을 맨 위 검정색 띠로 합치는 셈이죠.

{% include _image.html img="/images/good_morning/merge_branches.png" caption="[그림10: 검은색 색깔 띠로 합쳐져가는 branch들]" %}

&nbsp;&nbsp;master에 코드를 합치는 건 예민한 작업입니다. master에 문제가 생기면 서비스에 즉각 타격을 입기 때문이죠. 작업 단위가 클수록 세심히 코드를 살펴야합니다. 꼼꼼한 작업 확인을 위해 저희는 Pull requests(PR)[^7] 기능으로 코드 검토(review)를 합니다.

{% include _image.html img="/images/good_morning/pull_requests.png" caption="[그림11: Pull requests 생성]" %}

PR을 생성했습니다.

{% include _image.html img="/images/good_morning/comment_on_pr.png" caption="[그림12: 코드 검토 모습]" %}

&nbsp;&nbsp;엇, CTO님께서 댓글을 남기셨습니다. 확인해보니 앞으로 사용하지 않을 코드를 안 지웠군요. 충분히 검토했다고 생각했지만 놓쳤던 부분이 있었습니다. 이렇게 코드를 고쳐나간 후, 최종 단계에서 병합(Merge)를 합니다.

{% include _image.html img="/images/good_morning/complete_merge.png" caption="[그림13: 병합 완료]" %}

<br/>

## 오후 6시 : 배포

작업 내용을 서비스에 적용하려면 코드를 서버에 배포해야합니다. 배포 직전에는 앞서 진행한 모든 검토 과정들을 다시 진행합니다. 배포 담당자께서 dev 채널에 미리 공지합니다.

{% include _image.html img="/images/good_morning/deploy.png" caption="[그림14: 코드 배포 준비 모습]" %}

&nbsp;&nbsp;서버 배포를 완료했습니다. 12년 경력 배포 봇이 이를 알려주는군요. 사무실 로비에는 [배포를 알리는 효과음](https://www.youtube.com/watch?v=cAez7KLXlfQ)이 나옵니다.

{% include _image.html img="/images/good_morning/complete_deploy.png" caption="[그림15: 배포 완료]" %}

<br/>

## 오후 7시 : 확인, 퇴근

서비스 정상 적용 여부를 확인합니다. 문제 없는 듯 보입니다. 서버에 에러가 발생하면 에러 내용을 담은 이메일이 오지만, 다행히 이메일은 조용합니다.

&nbsp;&nbsp;어느덧 퇴근 시간이군요. 따뜻한 집밥을 먹으러 가야겠습니다. 팀원들께 인사를 드리고 기분 좋게 바깥 공기를 마십니다.

<br/>

#### 주석

[^1]: 과반수가 없으면 (ex. 다른 회의 참여) 적기만 진행합니다.
[^2]: 서버 관련 업무를 처리합니다.
[^3]: 웹/모바일 관련 업무를 처리합니다.
[^4]: 윈도우 응용 프로그램 관련 업무를 처리합니다.
[^5]: 코드 저장소로 [github](http://github.com/add2paper)를 사용합니다.
[^6]: 푸시(Push) 용어를 쉽게 풀어쓰기 위해 전송이라는 단어로 대체했습니다.
[^7]: 코드 버전 관리에서 제공하는 코드 병합(merge) 요청 기능입니다. 작업자가 pull requests로 코드 병합을 요청하면, 메인 관리자가 코드 검토 후 이를 병합합니다.