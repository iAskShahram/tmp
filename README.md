# Markdown Examples

## Plain Text

This is an example of plain text in Markdown. You can write regular text, include **bold** or *italic* text, and create [hyperlinks](https://www.example.com).

## Tables

Here's an example of a table:

| Name  | Age | Gender |
|-------|-----|--------|
| Alice | 30  | Female |
| Bob   | 25  | Male   |
| Carol | 35  | Female |

## Images

![Example Image](https://via.placeholder.com/150)

## Interactive Line Chart

```{python}
import matplotlib.pyplot as plt

# Sample data
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]

plt.plot(x, y)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Interactive Line Chart Example')
plt.grid(True)
plt.show()



## Static Line Chart Example

![Static Line Chart](https://quickchart.io/chart?c={type:'line',data:{labels:['Jan','Feb','Mar','Apr','May'],datasets:[{label:'Example Data',data:[10,20,30,40,50]}]})
