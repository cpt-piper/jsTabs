# jsTabs
Simple javascript tabs

## Prerequisites

Container which consists of two main elements: 
* several separated **tabs** (*blocks*) 
* a **block of buttons** (or additional *div* blocks imitating *buttons*), on which you are going to click to change the content of the **tabs**



### Construction you need to use this script

* ***Main block***
* * **Block of buttons**
* * * *Button #1*
* * * *Button #2*
* * * *Button #N*
* * **Tab with content #1**
* * **Tab with content #2**
* * **Tab with content #N**

*As you may see now, tabs with content are totally separated from each other, the parent is **Main block**.*

### Brief description of variables

Object **tab** is formed of elements containing class from the *button*. 
Variable **info** represents the whole *block of buttons*. Used only for inheritance in addEventListener.
Object **tabContent** is used to manipulate *tabs with content*, contains all elements that have class of separated tabs.

### To make things work we only need some indicators in **.html* file
Simply add class *".info-header-tab"* to your **buttons**, class *".info-header"* to **block of buttons** and class *".info-tabcontent"* **to each** of your **tab with content**.

Last but not the least add to your **.css* file two classes *.show* and *.hide*
```
.show {
    display: flex;
}

.hide {
    display: none;
}
```

#### Feel free to use this code and I hope it will help you to save some time!
