
# 📝 Lista de Tarefas

Um programa simples em Python para organizar tarefas do dia a dia.

## 💻 Código

```python
tarefas = []

while True:
    print("\n===== LISTA DE TAREFAS =====")
    print("1 - Adicionar tarefa")
    print("2 - Ver tarefas")
    print("3 - Sair")

    opcao = input("Escolha uma opção: ")

    if opcao == "1":
        tarefa = input("Digite sua tarefa: ")
        tarefas.append(tarefa)
        print("Tarefa adicionada!")

    elif opcao == "2":
        print("\nSuas tarefas:")

        for numero, tarefa in enumerate(tarefas, 1):
            print(f"{numero}. {tarefa}")

    elif opcao == "3":
        print("Até mais!")
        break

    else:
        print("Opção inválida!")

## 🚀 Como executar

1. Instale o Python.
2. Salve o código como `tarefas.py`.
3. Abra o terminal.
4. Execute `python tarefas.py`.

## 🛠️ Tecnologias utilizadas

- Python 3

## 🎯 Objetivo

Criar uma solução simples para ajudar na organização das tarefas diárias.

## 👨‍💻 Autor

Desenvolvido por mim!
