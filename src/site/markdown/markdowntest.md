# This is a header
And this is a paragraph

The *quick* brown fox, jumped **over** the lazy [dog](https://en.wikipedia.org/wiki/Dog).

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

```javascript
var const = 1
for(i=0; i<5; i++) {
  console.log(i)
}
```

#### Web
TODO://

#### Configuration

| Environment variable | Description | Default |
|:-------------------- |:------------|:-------:|
|`SPRING_PROFILES_ACTIVE`|Spring active profile.|`development`|
|`LOGGING_LEVEL_com.talkdesk`|Log level for `com.talkdesk` packages.|`debug`|
|`BUGSNAG_API_KEY`|Bugsnag Key for error reporting.||
|`NEW_RELIC_LICENSE_KEY`|NewRelic License Key.||
|`NEW_RELIC_APP_NAME`|Name of the app in NewRelic.||
|`NEW_RELIC_DEBUG_LEVEL`|Log level for NewRelic packages.||
|`RABBITMQ_CONSUMER_URL`|URL for the RabbitMQ consumer.|`ampq://localhost`|

```mermaid
  %% Example of sequence diagram
  sequenceDiagram
    Alice->>Bob: Hello Bob, how are you?
    alt is sick
    Bob->>Alice: Not so good :(
    else is well
    Bob->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
    Bob->>Alice: Thanks for asking
    Bob->>Alice: Thanks for asking
  end
```

```mermaid
%% Example of graph diagram
graph TB
  c1
  c2
  c1-->a2
  subgraph one
  a1-->a2
  end
  subgraph two
  b1-->b2
  end
  subgraph three
  c1-->c2
  end
end
```

```mermaid
graph LR
  id1(Start)-->id2(Stop)
  style id1 fill:#f9f,stroke:#333,stroke-width:4px
  style id2 fill:#ccf,stroke:#f66,stroke-width:2px,stroke-dasharray: 5, 5
end
```

---

> To be or not to be, that is the question.

---

* Milk
* Bread
    * Wholegrain
* Butter

---

1. Tidy the kitchen
2. Prepare ingredients
3. Cook delicious things

---

-> ![cool](http://i.imgur.com/v8IVDka.jpg) <-



---

**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

---

[Dog](https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog")

---

\*literally\*

---

\~\~deleted words\~\~

---


==oooh fancy==

---

The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red

---
table

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

----

Math
Pythagoran theorem is $$a^2 + b^2 = c^2$$.

Bayes theorem:

$$$
P(A | B) = (P(B | A)P(A)) / P(B)
$$$

----

### Solar System Exploration, 1950s – 1960s

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley

---

->Centered Text<-

---

Bold and italic text
*one asterisk on each end makes the text italic*
one asterisk on each end makes text italic

**two asterisks on each end makes text bold**
two asterisks on each end makes text bold

***three asterisk on each end makes text bold and italic***
three asterisk on each end makes text bold and italic

---

attr

# *header*{.red}
paragraph *style me*{.red} more text


```python {data=asdf}
nums = [x for x in range(10)]
```

Use the css-module green on this paragraph. {..green}

---

First Header  | Second Header
  ------------- | -------------
  Content Cell  | Content Cell
  Content Cell  | Content Cell

---

:D :)

:fa-git: git hub
:fa-google: git hub
