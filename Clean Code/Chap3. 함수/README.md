# Chap3. 함수

## 팩토리 패턴

### 싱글턴 패턴

- https://gmlwjd9405.github.io/2018/07/06/singleton-pattern.html

### 팩토리 메서드  패턴
  - [메인](https://niceman.tistory.com/143)
  - [서브](https://victorydntmd.tistory.com/299)
### 추상 팩토리 패턴
  - [메인](https://gmlwjd9405.github.io/2018/08/08/abstract-factory-pattern.html)
  - [서브](https://victorydntmd.tistory.com/300)

## Try/Catch 블록 뽑아내기

> 오류 동작 과정을 분리

```js
public void delete(Page page){
  try{
      deletePageAndAllReferences(page);
  }
  catch (Exception e){
      logError(e);
  }
}
```



