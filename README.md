<p align="center">
    <img src="./kubernetes.png" height="130"/>
</p>
<p align="center">
    <img src="https://img.shields.io/github/last-commit/wellers0n/first-cluster-k8s-with-kind?style=flat-square"/>
    <a href="https://twitter.com/wellers0n_" target="_blank">
        <img src="https://img.shields.io/twitter/url/https/wellers0n_.svg?style=social"/>
    </a>
</p>

<p>
   <h1 align="center">K8S and Kind</h1>
<p/>
    
<br/>

## K8S

I'm making this project to improve my skills!

## Initing in the your PC

- For clone the project `git clone https://github.com/Wellers0n/first-cluster-k8s-with-kind.git`
- Enter in the folder `cd first-cluster-k8s-with-kind/`

## Commands

#### Init config

```sh
    kind create cluster --name multinode --config ./cluster.yml
```

#### Init nginx with kubectl

```sh
    kubectl run nginx --image nginx
```

#### Commends to get clusters with kind

```sh
    kind get clusters
```

#### Commends to get nodes and pods with kubectl

```sh
    kubectl get namespaces
```

```sh
    kubectl get pods
```

```sh
    kubectl get nodes
```