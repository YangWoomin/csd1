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

1. 다양한 모양의 브러시와 퍼프를 세척기 내부에서 세제와 물을 사용하여 **세척**한다.
2. 세척이 완료되면 자동으로 브러시와 퍼프를 **건조**한다.
3. 건조가 완료되면 브러시와 퍼프를 **살균**한다. 또한 살균 **시간과 주기**를 사용자가 **설정**할 수 있다.
4. 블리너의 관리 시스템이 브러시와 퍼프에 대한 **정보를 저장**하고 이를 위생적으로 **관리**하도록 스마트폰에서 **어플리케이션**으로 동작한다.

---------------

###3. 기존 관련 사례

* Brush Pearl

![enter image description here](http://media.allure.com/photos/5771a75f3b5256713da4b9c0/master/pass/beauty-trends-blogs-daily-beauty-reporter-2015-09-03-brush-pearl.jpg)

 [사용후기 영상](https://youtu.be/-BnR4_kKj8o)
 
> Brush pearl은 세탁기와 비슷한 형태의 **브러시 세척 기기**이다. 제품 내부에 같이 판매하는 전용 세제를 넣은 뒤, 벽면에 물의 양을 확인할 수 있도록 용량이 표시되어 있다. 내부에 물을 붓고 뚜껑 부분에 브러시를 장착한다. 오른쪽 버튼으로 세탁기처럼 세척시간 설정가능하다. 보관 시 물티슈로 내부를 간단히 닦아 관리할 수 있다.
 
> IoT가 반영이 되지 않은 제품이며 세척율이 낮은 부분을 보완해야 할 필요가 있다. 우리가 구현하려는 시스템은 화장품 소도구 세척기로서 핵심 기능을 포함하고 있는 시판 제품이다. 이 제품의 기능을 근간으로 하여 **IoT 시스템으로 구현**하고자 한다.
 
* 칫솔, 화장용 퍼프 및 화장솔 살균기

![enter image description here](http://thumbnail.10x10.co.kr/webimage/image/add1_600/146/A001465240_01-3.jpg?cmd=thumb&w=300&h=300&fit=true&ws=false)

> 이 제품은 칫솔, 화장용 퍼프 및 화장솔을 한꺼번에 건조, 살균할 수 있는 살균기이다. 일정시간 노출되면 칫솔모나 화장용 퍼프의 방향에 상관없이 모두 건조 살균이 된다.

> 단점은 종합적인 관리가 어렵다는 것이다. 이 기기는 살균 및 건조는 해주나, 근본적인 오염원인 화장품 찌꺼기나 피푸각질 등은 제거하지 못하므로 사용자가 따로 세척을 실시해야 한다. 이 제품 역시 IoT가 반영이 되어 있지 않으며, **살균, 건조 기능을 착안하여 우리 제품을 구현**할 것이다.

| 그 외 사례        |                                        착안점                                     | 
| :--------------: | :-------------------------------------------------------------------------------: | 
| 패밀리 허브       | 냉장고 냉장고의 사용자 편의를 위한 기능들을 우리가 제품의 화장 도구 위생관리에 적용한다. | 
|화장용 브러시 세척기|바닥의 돌기를 이용하여 메이크업 브러시를 세척하는 데 세척율을 높일 수 있다.             | 


---------------

[1]: http://blog.naver.com/PostView.nhn?blogId=ppury99&logNo=220670949442&categoryNo=0&parentCategoryNo=6&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView