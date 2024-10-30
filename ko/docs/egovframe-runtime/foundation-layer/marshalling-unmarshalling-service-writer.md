---
linkTitle: "- Writer.java"
weight: 21.3
title: Marshalling/Unmarshallig 서비스 예제 (Writer.java)
description: Marshalling/Unmarshalling 서비스 예제에서 작가 정보를 처리하는 Writer 클래스이다.
---
# Writer.java

## 개요 

Marshalling/Unmarshallig 서비스 예제입니다. 

**Writer.java**

```java
public class Writer 
{
  private String Name;
  // 생성자
  public Writer() { }
  // 작가명
  public Writer(String Name) {
    this.Name = Name;
  }
  // 작가명 수정
  public void setName(String Name) {
    this.Name = Name;
  }
  // 작가명 리턴 
   public String getName() {
    return Name;
  }
}
```
