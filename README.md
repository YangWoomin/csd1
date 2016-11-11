﻿# 1조의 시스템 설계

![](/bleaner.png)

-------------

##조원
>- 양우민(YangWoomin)

>- 김수연(femalecamel)

>- 백지선(ssunnimi)

>- 최유경(youkyungchoi)

-------------

###1. 필요성 

* 매일 사용하는 화장 도구(브러시, 퍼프)는 **비위생적**으로 방치되기 쉬우며, 사용자가 일일이 신경쓰기 쉽지 않다.
따라서, 이를 보완해 줄 시스템이 필요하다. [관련 정보 사이트] [1]
* 이를 보완해 줄 *스마트 뷰티 도구 관리 시스템*이 필요하다.

-------------

###2. 시스템 개요

(꾸미세요)
다양한 모양의 브러시와 퍼프를 세척기 내부에서 세제와 물을 사용하여 세척한다.
세척이 완료되면 자동으로 브러시와 퍼프를 건조한다.
건조가 완료되면 브러시와 퍼프를 살균한다. 또한 살균 시간과 주기를 사용자가 설정할 수 있다.
블리너의 관리 시스템이 브러시와 퍼프에 대한 정보를 저장하고 이를 위생적으로 관리하도록 스마트폰에서 어플리케이션으로 동작한다.

---------------

###3. 기존 관련 사례

* Brush Pearl

![enter image description here](http://media.allure.com/photos/5771a75f3b5256713da4b9c0/master/pass/beauty-trends-blogs-daily-beauty-reporter-2015-09-03-brush-pearl.jpg)

 [사용후기 영상](https://youtu.be/-BnR4_kKj8o)
 
> Brush pearl은 세탁기와 비슷한 형태의 **브러시 세척 기기**이다. 제품 내부에 같이 판매하는 전용 세제를 넣은 뒤, 벽면에 물의 양을 확인할 수 있도록 용량이 표시되어 있다. 내부에 물을 붓고 뚜껑 부분에 브러시를 장착한다. 오른쪽 버튼으로 세탁기처럼 세척시간 설정가능하다. 보관 시 물티슈로 내부를 간단히 닦아 관리할 수 있다.
 
> IoT가 반영이 되지 않은 제품이며 세척율이 낮은 부분을 보완해야 할 필요가 있다. 우리가 구현하려는 시스템은 화장품 소도구 세척기로서 핵심 기능을 포함하고 있는 시판 제품이다. 이 제품의 기능을 근간으로 하여 **IoT 시스템으로 구현**하고자 한다.
 
* 사례2



---------------

[1]: http://blog.naver.com/PostView.nhn?blogId=ppury99&logNo=220670949442&categoryNo=0&parentCategoryNo=6&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView

>
*** 각 조의 github 원격저장소에 md 파일을 올리고 확인해보자 ***

- 내용은 각 조별 시스템 설계 주제로 한다 
-- 필요성, 시스템 개요(만들고자 하는 시스템이 무엇인지 3-4 문장으로 설명), 기존 관련 사례(2개 항목만 간단히 소개)

- 마크다운 문법을 참조하여 md 파일을 작성 (하나의 README.md 파일)
-- 단, 다음 마크다운 문법은 모두 포함하도록 내용을 작성할 것
-- 제목, 목록, 강조(기울인 글씨, 굵은 글씨), 인용, 링크(인라인 링크, 참조 링크), 이미지, 표

- 작성한 md 파일을 github 저장소에 push

* 조 번호, 조원의 이름 및 github 사용자 이름을 포함할 것
* 모든 조원이 파일 작성에 참여하여야 함 (commit 기록으로 확인)

조장이 해당 github 원격저장소의 URL을 과제 결과물로 올릴 것
