---
layout: inner
title: 'React Music Application : Part1'
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

Create React App
-------------
Create React App은 React application 개발을 위한 새로운 툴로서 복잡한 설정없이 바로 React 프로젝트를 시작할 수 있게 도와준다.

>- npm install -g create-react-Application
>- create-react-app my-app
>- cd my-app/
>- npm start

Create React App을 통해 새로운 Application을 생성한 후 [http://localhost:3000/](http://localhost:3000/) 을 오픈하여 생성된 application을 확인해보자.

Breaking Down the UI
-------------
거의 모든 React application UI는 여러 컴포넌트들의 조합으로 구성되어진다. 날씨 앱을 예로들자면, 지역명을 보여주는 컴포넌트
, 현재 기온을 보여주는 컴포넌트, 5일간의 예측을 나타내는 그래프 컴포넌트들로 구성되어진다.

이러한 이유로 React 앱 개발에 앞서 UI를 컴포넌트 단위로 분해하여 보는것이 좋다.

> 애플리케이션을 컴포넌트들의 조합으로 바라보는 접근 방식에 대해서는 [Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html)를 참조

![enter image description here](https://lh3.googleusercontent.com/HdFWvmidwmlhg2IAieOTe7b09Qa9N2L6JrdAWws4prBX30up3xXuxDccGWx8j_wySf_n0CY_sw=s0 "music_search")


{% include disqus.html %}
