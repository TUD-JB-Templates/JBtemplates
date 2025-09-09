---
kernelspec:
  name: python3
  display_name: 'Python 3'
---

# Introduction to Jupyter Book
Jupyter Book is an open-source tool designed to create interactive teaching materials, such as textbooks and tutorials, using Markdown, Jupyter Notebooks, and other formats. It enables educators to combine narrative text, executable code, and multimedia content in a single, shareable resource.

```{warning}
:class: dropdown

Once started with Jupyter Books, you might get hooked!
```

There are two main versions: JB1 (the original) and JB2 (the current, more feature-rich version). Both support integration with tools like Visual Studio Code (VSC) for editing, Git for version control and collaboration, and Python for interactive code examples.

At Delft University of Technology, we actively support the creation and publication of Jupyter Books, providing guidance and infrastructure for both authors and readers. The following chapters will explore these tools and workflows in more detail.

```{code-cell} python
:tag: hide-input

import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(0,2*np.pi,50)
y = np.sin(2*np.pi*x)
z = np.cos(2*np.pi*x)

plt.figure()
plt.plot(x,y,'k.')
plt.plot(x,z,'r--')
plt.xlabel('$x$')
plt.ylabel('$y$')
plt.show()


```