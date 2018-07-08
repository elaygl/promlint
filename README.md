# promlint
Prometheus metrics linting tool

## How to use?
with curl:
```
curl -s http://localhost:3000/metrics | docker run -i elaygl/promlint 
```

from local file:
```
cat metrics.prom | docker run -i elaygl/promlint
```
