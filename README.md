AWS 자격증 취득을 위해 덤프를 보려했다.

사이트에서 문제를 보는 것으로 그치지 않고, 크롤링을 이용해 문제를 수집하여 엑셀에 저장하고

해당 엑셀과 AWS linghtssail을 이용하여 덤프 문제를 풀 수 있는 간단한 챗봇을 만들려 했다.

하지만 크롤링 코드를 만들고 보니, 해당 덤프 사이트의 robots.txt에서 덤프 문제의 크롤링을 금한다는 것을 확인하였다.

실제로도 해당 덤프 사이트에서 아주 엄격하게 로봇검사를 실행한다.

결국 크롤링은 하지 않기로 하였다.

다만 크롤링 코드를 이미 만들었기에 아쉬워서 깃허브에 올린다.

아주 간단하게 만들었다.

(각 덤프 문제의 1p는 크롤링이 가능하나, 그외 페이지는 전부 차단된다.)