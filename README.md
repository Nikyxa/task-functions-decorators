# Task function-decorator

Read this guideline before completing the task:
[Guideline](https://github.com/ketstap162/tasks-guideline)

## Your task
You have function `f1` that takes a list of different data types and your task is:
1. To filter this list and return only integrals using `filter_nums`;
2. To double integers using `double_nums`;
3. To use the format which you can see in the example below and transform your list into string using `transform_nums`.


<details>
<summary>Hint</summary>
You should make your given functions <code>filter_nums</code>, <code>double_nums</code> and <code>transform_nums</code> as decorators for your main function <code>f1</code> and use them in a proper order.
</details>

## Example
```
@Your decorators are here
def f1(items: list):
    return f"To transform this list into string we need to decorate it first!"
           f"After transformation: {', '.join(items)}."

items = [1, "5", "main", 2.4, 3, ["a", "b"], {1, 2, 3}, 9]

f1(items) == "To transform this list into string we need to decorate it first!"
             "Given list: [1, "5", "main", 2.4, 3, ["a", "b"], {1, 2, 3}, 9]"
             "After transformation: "1^2 = 1, 3^2 = 9, 9^2 = 81."
```
