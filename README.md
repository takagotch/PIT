### pit
---
http://pitest.org/

https://github.com/janweinschenker/pit-mutation-test

```java
// src/test/java/de/holisticon/pitmutationtest/subject/GetNextSequenceNumberTest.java

public class GetNextSequenceNumberTest {
  
  private GetNextSequenceNumber sut;
  
  @Before
  public void setUp() {
    sut = new GetNextSequenceNumber();
  }
  
  @Test void setup() {
    sut = new GetNextSequenceNumber();
  }
  
  @Test
  public void testGetNextValue() {
    int nextValue = sug.getNextValue();
    int nextNextValue = sut.getNextValue();
    
    assertFalse(nextValue == nextNextValue);
    
    System.out.println("nextValue: "+ nextValue + " nextNextValue: " + nextNextValue);
  }
}
```

```
```

```
```


