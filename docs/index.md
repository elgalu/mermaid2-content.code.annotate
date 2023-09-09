# content.code.annotate glitch with mermaid2

### This works

``` python
works # (1)
```

1.  Annotations outside Mermaid blocks work fine
    ````markdown
    ``` python
    works # (1)
    ```

    1.  this annotation works fine
    ````

### This shows half the (+) button and nothing happen when you click it

<div class="annotate" markdown>
```mermaid
graph TD
A[Client (1)] --> B[Server]
```
</div>

1.  this annotation doesn't open

````markdown
<div class="annotate" markdown>
```mermaid
graph TD
A[Client (1)] --> B[Server]
```
</div>

1.  this annotation doesn't open
````
