# JAVA DIFERENTE

-  Um erro bem comum quando estamos usando uma versão diferente do dart é o java
-  e para resolver isso basta irmos em `android/gradle.properties`
-  e adicionar uma linha

```gradle
org.gradle.java.home=/Library/Java/JavaVirtualMachines/jdk-11.jdk/Contents/Home
```

-  Note que a versao do java pode ser diferente

---

# Erro `exists?`

-  Quando estamos tentando buildar o projeto pode acontecer o problema do `exists?` pois a versao do projeto pode ser um pouco diferente

-  Vá em pasta `.fvm/flutter_sdk/packages/flutter_tools/bin/podhelper.rb` e procure pelo `exists?` o correto é ser `exist?`
