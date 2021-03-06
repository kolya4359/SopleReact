# chapter_11 : 폼

## 폼이란?

- 사용자로부터 입력을 받기 위해 사용하는 양식

## 제어 컴포넌트

- 사용자가 입력한 값에 접근하고 제어할 수 있게 해주는 컴포넌트
- 값이 리액트의 통제를 받는 입력 폼 엘리먼트

## \<input type="text"> 태그

- 한 줄로 텍스트를 입력받기 위한 HTML xorm
- 리액트에서는 value라는 attribute로 입력된 값을 관리

## \<textarea> 태그

- 여러 줄에 걸쳐서 텍스트를 입력받기 위한 HTML 태그
- 리액트에서는 value라는 attribute로 입력된 값을 관리

## \<select> 태그

- 드롭다운 목록을 보여주기 위한 HTML 태그
- 여러 가지 옵션 중에서 하나 또는 여러 개를 선택할 수 있는 기능을 제공
- 리액트에서는 value라는 attribute로 선택된 옵션의 값을 관리

## \<input type="file"> 태그

- 디바이스의 저장 장치로부터 사용자가 하나 또는 여러 개의 파일을 선택할 수 있게 해주는 HTML 태그
- 서버로 파일을 업로드하거나 자바스크립트의 File API를 사용해서 파일을 다룰 때 사용
- 읽기 전용이기 때문에 리액트에서는 비제어 컴포넌트가 됨

## 여러개의 입력 다루기

- 컴포넌트에 여러 개의 state를 선언하여 각각의 입력에 대해 사용하면 됨

## Input Null Value

- value prop은 넣되 자유롭게 입력할 수 있게 만들고 싶을 경우, 값에 undefined 또는 null을 넣으면 됨
