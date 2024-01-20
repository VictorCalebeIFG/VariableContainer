# VariableContainer
VariableContainer, a Python library, simplifies the creation and management of shared JSON-based variables accessible from any code section. An excellent alternative to singletons, it promotes flexible and convenient data handling in Python projects.

### Use:



### GetData
```
container = VariableContainer("container-name")

container.update_data({'a': 1})
container.update_data({'b': 1})

print(container.data)
```
# Não é necessário chamar container.save_data() explicitamente
