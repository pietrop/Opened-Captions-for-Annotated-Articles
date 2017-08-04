# Annotations in google doc

## Convention:

- Work in “suggestion mode” and approve when ready + set permissions.

![Annotations in google doc](/assets/Google doc annotations.png)

- Wrap selection with `[[` `]]`

- initials in square brackets follow by :

```
[[Politicians prospered, but the jobs left and the factories closed]]. The establishment protected itself, but not the citizens of our country. Their victories have not been your victories. Their triumphs have not been your triumphs and while they celebrated in our nation's capital, there was little to celebrate for struggling families all across our land. 

[MY:This line clearly speaks to how many people feel, but in reality there are more people employed in the United States in January 2017 than at any previous time in American history, and inflation-adjusted wages are higher than they have ever been.]
```



Annotation in single square brackets `[` … `]` prefixed with initials. eg `[PP: ...some text goes here... ]`

see [example google doc with annotations here](https://docs.google.com/document/d/1p_Zi-utnPU82xT61evrw0Tvq32F1k6YpKOlmC4qvIo4/edit)


You can have a spreadsheet that converts the initials to the full name of the journalists, and adds twitter handler as well. [Set it up similar to this](https://docs.google.com/spreadsheets/d/1bij4r5mHcQV_g6bIxlAbM5-ElmGjGu_-5NBp2SIfN3c/edit#gid=0)

Will see[ how to connect that to the static site generator in the next section](/generating-an-annotated-article.md).


## Adding an image

Example to add an image, url followed by comma and description. Then new line separation.


```
https://cdn3.vox-cdn.com/uploads/chorus_asset/file/7842655/GettyImages_632194040.jpg, Paul J. Richards/Getty Images
```