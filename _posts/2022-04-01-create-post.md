---
layout: post
title: Creating a technical posts different components
---

## File Format

- Make cookies. 
    1. Gather ingredients.
       - baking soda.
       - sugar.
       - eggs.
       - all-purposed flour.
    2. Mix all ingredients together. 
    3. Bake for 10 minutes.

## Math

We know that $$\cos^2 \theta + \sin^2 \theta = 1.$$
$$P^* = \argmin_{P} \int_{0}^{T}L(t,P,\dot{P})dt$$

## Code

```python
from matplotlib import pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 1001)
y = np.exp(x)
f = plt.plot(x,y)
``` 
![image-1.png]({{ site.baseurl }}/images/image-1.png)

## Image from internet

![](https://imgs.xkcd.com/comics/brand_identity.png)

(Source: [https://xkcd.com/993/](https://xkcd.com/993/))

## Describing Peer Feedback

{::options parse_block_html="true" /}
<div class="got-help">
I learned how to create post from my hw0! 
</div>
{::options parse_block_html="false" /}

{::options parse_block_html="true" /}
<div class="gave-help">
I gave my peers an useful suggestion! 
</div>
{::options parse_block_html="false" /}

{::options parse_block_html="true" /}
<div class="got-help">
It's my first draft of code.

```python
import math
def sigmoid(X):
    return [1 / (1 + math.exp(x)) for x in X]
```
It is modified by my classmate.
```python
import numpy as np
def sigmoid(X):
    return 1 / (1 + np.exp(X))
``` 
</div>
{::options parse_block_html="false" /}