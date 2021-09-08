### Использование Google Protocol Buffers (protobuf) в Java
https://habr.com/ru/company/otus/blog/544204/

Для генерации класса из proto-файла исполнить команду
```
protoc --proto_path=src --java_out=src/main/java/ src/main/proto/album.proto
```

Google Protocol Buffers на MacOs ставится командой 
```
brew install protobuf
```