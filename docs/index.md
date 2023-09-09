# content.code.annotate glitch with mermaid2

``` yaml
theme:
  features:
    - content.code.annotate # (1)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.


<div class="annotate" markdown>

```mermaid
graph TD
A[Client] --> B[Load Balancer]
B --> C[Server01]
B --> D[Server02]
B --> box1[An <b>important</b> <a href="http://google.com">link</a>]
```

</div>

(1)

1.  :man_raising_hand: I'm an annotation!
