| title       | description     | category     |  author     | date     |
| :------------- | :----------: | -----------: | -----------: |-----------: |
|  Using focus style for accessibility |  A focus is a pseudo-class used to indicate or highlights an intractable component in a webpage.     | How to    | Ezekiel Lawson   | 2021-09-27    | 

**Further Reading**

| title       | url    |   source    | year     |
| :------------- | :----------: | -----------: | -----------: | 
|  Style focus |  https://https://web.dev/style-focus/   | Web dev    |  2018   |  


| title       | url    |   source    | year     |
| :------------- | :----------: | -----------: | -----------: | 
|  designing usable focus indicators |  https://www.deque.com/blog/give-site-focus-tips-designing-usable-focus-indicators/  |  Caitlin Geier   |  2016   | 

| title       | url    |   source    | year     |
| :------------- | :----------: | -----------: | -----------: | 
|  never-remove-css-outlines |  https://www.a11yproject.com/posts/2013-01-25-never-remove-css-outlines/  |  Guilherme Simões   |  2013  | 


```

a:focus {
  outline: 5px solid red;
  }
```

```
<form class="form-container">
<label for="email">
<input class="email-input" value="Click me to see my focus state">
</label>
<label for="username">
<input class="user-input" value="Click me to see my focus state">
</label>
</form>

.form-container:focus-within {
 background: #ff8;
 color: black;
 padding:20px;
}
```

##Why is it important?**
