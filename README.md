# protocol_buffers
protocol_buffers_v3

## (TERMINAL - python)
ls
mkdir python
mkdir java
protoc -I=proto --python_out=python basics-part-1/*.proto
## (TERMINAL)
ls
protoc -I=proto --java_out=java basics-part-1/*.proto