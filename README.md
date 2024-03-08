# gateway

This is a lightweight API Gateway written in Go.

## Sample gateway configuration

```
gateway:
  listenAddr: localhost:8000
  routes:
    - name: Service A
      context: /service-a
      target: http://localhost:8001
    - name: Service B
      context: /service-b
      target: http://localhost:8002
```