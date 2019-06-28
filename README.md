# Python-Assignment
PIAIC 
print(">>>>>>>>>>>>>>>>TO-DO LIST<<<<<<<<<<<<<<<<<")
todolist = []
todolist

def add_item(values):
    result = todolist.append(values)
    return result

addValue = input("Add item")
print("your add item in todo list "+addValue)

todolist.append(addValue)
print(todolist)

def remove_item(values):
    result = todolist.remove(values)
    return result

removeValue = input("Remove item")
print("your remove item in todo list"+removeValue)

todolist.remove(removeValue)
print(todolist)
