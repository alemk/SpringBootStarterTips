# Key code snippets: 

## Iterating through items using a div:

```html
   <div th:each="item:${items}">
        <p th:text="${item.property}"></p>
    </div>
```
Change this to a table if you want a more structured format. The div will then be replaced by the ```<tr>``` tag, and the ```<p>``` with a ```<td>``` .
