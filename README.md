protocol_buffers
protocol_buffers_v3

## (TERMINAL - python)
```terminal
ls
mkdir python
mkdir java
protoc -I=proto --python_out=python basics-part-1/*.proto
```
## (TERMINAL)
ls
protoc -I=proto --java_out=java basics-part-1/*.proto

-I= destination_where_protos_are_located
--java_out= in which folder will new generated files be saved (you can use c++, python, java... and other programming languages)
basics-part-2/*.proto = which files should read. *.proto --> all proto files!

## EXAMPLE
```protoc -I=basics-part-2 --python_out=python basics-part-2/*.proto```


