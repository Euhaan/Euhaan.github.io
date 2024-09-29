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
- Unity  <mark>(3/5)</mark>
- Unreal Engine <mark>(3/5)</mark>
- Github <mark>(4/5)</mark>
****

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
    - 전반적인 사격 및 반동 시스템 구현
    - 데이터 테이블을 이용한 아이템 관리 시스템 구현
    - 3D 메뉴 연출 구현
    - 피직스 머티리얼을 적용한 부위 별 데미지 구현
    - 라운드 시스템 구현
      <br><br>

#### Insights

1. Animation 및 Camera Shake 조합의 미세한 차이가 가지는 몰입감의 영향을 느꼈습니다.
2. Data Table를 활용한 데이터 관리법에 대해 익혔습니다.
3. Physics Material를 통한 물리적 상호 작용 방법에 대해 익혔습니다.
   <br><br>

#### Skill

<mark>Blueprint</mark> <mark>UnrealEngine5</mark> <mark>Github</mark> <mark>Github</mark>

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
{{ "# Education" | markdownify }}
</div>
<div class="column2">
{{ "

## <font color=6AA8F8>The국제직업전문학교</font>

<i> VR, AR 게임개발 및 에셋 디자이너 양성과정 양성 과정 6기</i>
<br><br>

- 2022.12 ~ 2023.07 (6개월)
- 총 880 시간 과정
- 개인 프로젝트 1개 완성 커리큘럼

<mark>C#</mark> <mark>Unity</mark> <mark>3ds Max</mark> 
<br><br>

- - -

## <font color=6AA8F8>GCC 사관학교</font>

<i>Unreal 엔진을 활용한 멀티 플랫폼 게임 개발자 양성 과정</i>
<br><br>

- 2024.03 ~ 2024.10 (7개월)
- 총 800시간 과정
- C++, Blueprint
- 개인 프로젝트 1개, 팀 프로젝트 1개 완성 커리큘럼

<mark>C++</mark> <mark>Unreal Engine</mark> <mark>Blueprint</mark> <mark>Github</mark>
<br><br>

" | markdownify }}
</div> 
<div>****
