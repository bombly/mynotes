# Kubectl 使用

## kubectl 管理多集群

### merge 多集群config

```yaml
export KUBECONFIG=~/.kube/config:~/someotherconfig 
kubectl config view --flatten  > newfile
```