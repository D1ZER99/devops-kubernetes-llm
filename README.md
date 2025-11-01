LLM model from the homework 2 is now running on Kubernetes!

I run this model on __minukube__ using following commands:
- `kubectl apply -f ollama-config.yaml,ollama-pvc.yaml,ollama-app.yaml,streamlit-app.yaml`
- `minikube service streamlit-service`
