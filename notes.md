### Sources
- https://github.com/PacktPublishing/DevOps-to-MLOps-Bootcamp-Build-Deploy-ML-Systems-End-to-End

### Load testing
hey -n 10000 -c 200 -m POST -H "Content-Type: application/json" -D predict.json http://localhost:30100/predict