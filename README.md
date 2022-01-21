# Configurando arquivos para deploy no K8S

## Execução

Entrar no diretório kubernetes e executar o arquivo .yaml de deploy (deployment.yaml)

Comandos:

- Na raiz do projeto:
    
    executar: kubectl apply -f /kubernetes/deployment.yaml 
    matar: kubectl delete -f /kubernetes/deployment.yaml

- No diretório kubernetes:
    
    executar: kubectl apply -f deployment.yaml 
    matar: kubectl delete -f deployment.yaml

- Fazer bind da porta:

    kubectl port-forward pod/nome_pod porta_maquina:porta_pod

- obs: para saber o nome do pod executar kubectl get pods

    
