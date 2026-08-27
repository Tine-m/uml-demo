# uml-demo

```mermaid
classDiagram
    Kunde "1" --> "0..*" Ordre : har
    
    class Kunde {
        +int kundeId
    }
    
    class Ordre {
        +int ordre_Id
    }
```

her kommer der noget java kode

```java
int count = 0;
```


her kommer noget sql

```sql
select * from varer;
```
