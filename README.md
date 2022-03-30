# React-mechansium

React vs ReactDom
----
React는 props, state, context가 바뀔 때 컴포넌트를 재실행시켜주는 것.   
ReactDom은 React에서 재실행시켜준 것을 기반으로 이전 snapshot과 비교해서 변경된 부분이 있으면 그 부분만 실제 DOM에 적용 시켜주는 것.    

자식 컴포넌트에서 prop이 변하지 않아도 부모의 state가 변한다면 자식들도 따라서 재실행이 된다. 하지만 자식 컴포넌트가 재실행된다고해서 실제 DOM에 영향을 주는 것은 아님.
