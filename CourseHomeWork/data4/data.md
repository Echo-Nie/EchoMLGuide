You just need run the python:

```python
trainset = torchvision.datasets.CIFAR10(root='./data4', train=True, download=True, transform=transform)
testset = torchvision.datasets.CIFAR10(root='./data4', train=False, download=True, transform=transform)
```