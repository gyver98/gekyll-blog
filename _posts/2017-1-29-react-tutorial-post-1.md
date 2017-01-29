---
layout: inner
title: 'React Album Search Application : Part1'
date: 2017-01-29 15:45:34
categories: blog development react
tags: blog react
comments: true 
lead_text: 'First Post'
---

React application 만들기 : Part 1
==================

새롭게 배운 내용을 정리하고 공유하기 위해 블로그를 운영하기로 결심하고 처음으로 작성하는 포스트.
이 글에서는 React를 공부하면서 배운 것들, 인터넷을 통해 참조한 여러 자료들을 바탕으로 어떻게 간단한 음악 앨범을 조회하는 application을 만드는지를 공유하고자 한다.

React란?
-------------

React는 Facebook에서 개발한 유저 인터페이스를 위한 JavaScript library이다.
React는 컴포넌트(Component) 기반 architecture 인데 가장 중요한 구성단위인 컴포넌트는 UI를 구성하는 독립적이고 재사용이 가능한 조각이며 개념적으로 React에서의 컴포넌트는 JavaScript의 functions와 같다.
컴포넌트는 Props 라 불리우는 inputs 을 받아들여 화면에 무엇이 보여져야 하는지를 묘사하는 React elements를 리턴한다. 
이러한 아이디어는 한 마디로 다음과 같은 공식으로 표현할 수 있다.
> fn(d) = V.

데이타를 입력으로 받고 view를 리턴하는 함수.


Github Pages
-------------


{% include disqus.html %}