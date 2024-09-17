---
title: "Hey, Developer!"
permalink: /about/
layout: single
classes: wide
comments: false
---

<style>
.outer-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
}
    .two-columns {
        display: flex;
        flex-direction: row;
    }
    .column1 {
        flex-basis: 30%;
        padding: 10px;
        color:  #6AA8F8 !important;
    }
    .column2 {
        display: inline;
        flex-basis: 70%;
        padding: 10px;
    }

    .hover-image-container img {
        display: none; /* 기본적으로 이미지를 숨김 */
        position: absolute;
        transform: translate(-100%, -50%);
        z-index: 10;
    }

    .hover-image-container:hover img {
        display: block; /* 마우스를 올리면 이미지를 표시 */
    }

    .column2 a {
        text-decoration: none;
        color: #6AA8F8 !important;
        font-weight: bold;
    }
    .hover-image-container {
        display: inline;
    }

</style>

<div class="two-columns">
<div class="column1">
<img src="\assets\images\meee.png" width="200">
</div>
<div class="column2">
<br>
{{ "

**<mark>Email</mark>** &ensp; Euhaan99@gmail.com

**<mark>Github</mark>** &ensp; https://github.com/Euhaan

**<mark>Blog</mark>** &ensp; https://Euhaan.github.io

" | markdownify }}


</div>
</div>
- - -
<div class="two-columns">
<div class="column1">
        {{ "# INTRODUCE" | markdownify }}
</div>
<div class="column2">
{{ "## ❛탐구❜로 문제를 분석하고, ❛끈기❜로 ❛단순화❜의 길을 찾아가는 게임 클라이언트 신입 개발자입니다.
<br><br>
<mark><b>❛모❜로 가지 않고 ❛바❜로 서울 가는 개발자</b></mark>
"| markdownify }}

&ensp; 모 개발 회사 사무실에는 ‘어~?’ 를 금지하는
문구<div class="hover-image-container"><a href="#"><sup>[1]</sup></a><img src="\assets\images\posts_img\about/first.jpg" width="400"></div>
가 붙어 있다고 합니다. 개발자들의 밈(meme) 중에 만국 공통으로 유명한 밈은 ‘어? 이게 왜 되지?’, ‘어? 이게 왜 안 되지?’<div class="hover-image-container">
<a href="#"><sup>[2]</sup></a><img src="\assets\images\posts_img\about/second.png" width="400"></div>가 있습니다. 저의 ‘어?’ 는
‘어? 이게 왜 (의도한 대로) 안 되지?’ 밖에 없습니다!
<br><p>
&ensp; 직접 로직을 짜고 실행하는 데에서 흥미를 느끼기에 코드 한 줄, 한 줄의 의미와 왜? 를 알고 있습니다. 여태 해 온 코드의 99%는 제가 구성하고, 구현해낸 코드입니다. 나머지 1%는 패키지나
플러그인을 이용한 코드이며, 모두 코드 리뷰 후에 블로그에 기록용으로 남겨 현재 N개의 포스트가 게시되어 있습니다.</p>
<br>
{{ "
<mark><b>혈을 뚫는 개발자</b></mark>

&ensp; 이슈의 원인을 파악하여 문제를 해결하는 능력이 뛰어납니다. 두 번의 교육 기간 동안 코드 이슈로 강의 시간이 딜레이 되는 경우, 강사님들에게 문제 해결 방법을 제시하여 “쉬는 시간에 ㅇㅇㅇ 학생이 말해
준 대로 수정하니 되었습니다. 자, 여기서~” 와 같은 경험이 여러 차례 있었습니다. 뿐만 아니라, 같은 교육 동기생들이나 팀원이 어려워하는 문제에 해결책을 제시하기도 하였습니다.
<p>&ensp;  해결 경험을 잊지 않고 복기, 공유하기 위하여 개발일지 형식으로 남기고 있습니다. 개발 일지를 작성할 때 가장 중요하게 생각하는 것은 원인에 접근하는 근거입니다.</p>
"| markdownify }}
📝 <div class="hover-image-container"><a href="/unreal/test/" target=_blank> 문제 해결 경험 개발일지 - [UE] Weapon Bone이 있는 스켈레톤의 애니메이션</a></div>
<br>
<br>
{{ "

<mark><b>그밖에</b></mark>

- 공통적으로 사용하는 함수라면 재사용할 수 있는 상황을 고려하여 코드를 짭니다. 상속과 인터페이스를 즐겨 사용합니다.
- 최대한 Tick, Update 구문을 피하기 위하여 Set 함수, 프로퍼티를 즐겨 사용합니다.

"| markdownify }}
</div>
</div>

- - -

<div class="two-columns">
<div class="column1">
{{ "# SKILL" | markdownify }}
</div>
<div class="column2">
{{ "
****
- C# <mark>(4/5)</mark>
- C++ <mark>(3/5)</mark>
- Unity  <mark>(4/5)</mark>
- Unreal Engine <mark>(4/5)</mark>
- Github <mark>(4/5)</mark>
- HTML <mark>(2/5)</mark>
- CSS <mark>(2/5)</mark>

" | markdownify }}
</div> 
</div>

- - -

<div class="two-columns">
<div class="column1">
{{ "# Experience" | markdownify }}
</div>
<div class="column2">
{{ "

## <font color=6AA8F8>The국제직업전문학교</font>
2023.08 ~ 2024.03 (7개월)

- VR, AR 게임개발 및 에셋 디자이너 양성과정 (보조강사)


  " | markdownify }}
</div> 
</div>

- - -

<div class="two-columns">
<div class="column1">
{{ "# Projects" | markdownify }}
</div>
<div class="column2">
{{ "

## <font color=6AA8F8>Coma (VR)</font>

<i>Unity를 이용한, VR 기기를 이용한 3D 방탈출 게임 개발 </i>
<br><br>

#### Description

- 프로젝트 인원 : 1인 개발
- 사용 엔진 : Unity
- 기간 : 2023. 06. 01 ~ 2023. 07. 02 <mark>총 32 일</mark>
  <br><br>

#### What did I do

- 역할 : 프로젝트 기획 및 개발
- 기여
    - 사운드 채널링 시스템 구현
    - 공간 음향 시스템 구현
    - VR 컨트롤러를 활용한 드로잉 시스템 구현
    - 각종 힌트와 키 오브젝트에 대한 상호작용 구현
      <br><br>

#### Insights

1. 튜토리얼 형태의 게임도 플레이어가 의도한대로 흐름을 따라가게 할지에 대해 많은 고민이 들어간다는 것을 느꼈습니다.
2. 초기에 설정한 기능에 대한 세분화의 구성에 따른 작업 속도의 편차를 느꼈습니다.
3. Cinemachiner과 Virtua Camera에 대한 기능 사용법을 익혔습니다.
4. Object Pooling을 활용한 효율적인 자원관리법을 익혔습니다.
   <br><br>

#### Skill

<mark>C#</mark> <mark>Unity</mark> <mark>Github</mark> <mark>VR</mark>
<br><br>

#### Game Play Video

" | markdownify }}

📽️ <a href="https://youtu.be/gNcrb4fBX54" target=_blank> Coma(VR) 인게임 플레이 영상</a>
{{ "
- - - 

## <font color=6AA8F8>WhispersIn The Dark</font>

<i>Unreal Engine5를 활용한 좀비 FPS 게임 개발</i>
<br><br>

#### Description

- 프로젝트 인원 : 1인 개발
- 사용 엔진 : Unreal Engine 5
- 기간 : 2024. 06. 14 ~ 2024. 06. 23 <mark>총 10일</mark>
  <br><br>

#### What did I do

- 역할 : 프로젝트 기획 및 개발
- 기여
    - 
    - 전반적 기능 구현
    - Light 및 Shader 사용
      <br><br>

#### Insights

1. Cinemachine을 이용한 카메라 제어법을 배웠습니다.
2. 3D 환경에서의 Light 및 Shader 의 이용법을 배웠습니다.
3. NaviMesh Agent 을 심화 적용 하였습니다.
   <br><br>

#### Skill

<mark>C++</mark> <mark>UnrealEngine5</mark> <mark>Github</mark> <mark></mark> <mark>Shader</mark>
<br><br>

#### Game Play Video

" | markdownify }}
📽️ <a href="https://youtu.be/_VgQjvCEwF0" target=_blank>WhispersIn The Dark 인게임 플레이 영상</a>
{{ "
<br>

" | markdownify }}
</div> 
</div>

- - -

<div class="two-columns">
<div class="column1">
{{ "# Education" | markdownify }}
</div>
<div class="column2">
{{ "

## <font color=6AA8F8>The국제직업전문학교</font>

<i> VR, AR 게임개발 및 에셋 디자이너 양성과정 양성 과정 6기</i>
<br><br>

- 2022.12 ~ 2023.07 (6개월)
- 총 000 시간 과정
- 개인 프로젝트 1개 완성 커리큘럼

<mark>C#</mark> <mark>Unity</mark> <mark>3ds Max</mark> 
<br><br>

- - -

## <font color=6AA8F8>GCC 사관학교</font>

<i>Unreal 엔진을 활용한 멀티 플랫폼 게임 개발자 양성 과정</i>
<br><br>

- 2024.03 ~ 2024.10 (7개월)
- 총 000 시간 과정
- C++, Blueprint
- 개인 프로젝트 1개, 팀 프로젝트 1개 완성 커리큘럼

<mark>C++</mark> <mark>Unreal Engine</mark> <mark>Blueprint</mark> <mark>Github</mark>
<br><br>

" | markdownify }}
</div> 
</div>
