---
linkTitle: "- CasterBook.xml"
weight: 21
title: Marshalling/Unmarshallig 서비스 예제 (CasterBook.xml)
description: Marshalling/Unmarshalling 서비스 예제에서 책 정보를 XML 형식으로 정의한 CasterBook.xml 파일이다.
---
# CasterBook.xml

## 개요 

Marshalling/Unmarshallig 서비스 예제입니다. 

**CasterBook.xml**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<book-mg>
  <isbn>9780446618502</isbn>
  <writers xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"  xsi:type="java:egovframework.rte.fdl.divert.Writer">
    <name>J,J.R 툴킨</name>
  </writers>
  <writers xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"  xsi:type="java:egovframework.rte.fdl.divert.Writer">
    <name>J.J.T 툴킨</name>
  </writers>
  <title>반지의 제왕2</title>
</book-mg>
```