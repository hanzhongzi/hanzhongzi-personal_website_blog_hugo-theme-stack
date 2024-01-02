# 说明：https://stack.jimmycai.com

新建文章示例:
```shell

hugo new  post/linux_operation/ansible.md
```
目录结构:
```shell
content
└── post
    └── my-first-post
        ├── index.md
        ├── image1.png
        └── image2.png
```

插入图的形式:
```shell
--- content/post/my-first-post/index.md ---
![Image 1](image1.png)
![Image 2](image2.png)
```

图像库:
```
content
└── gallery
    └── my-first-gallery
        ├── index.md
        ├── image1.png
        ├── image2.png
        └── image3.png

--- content/gallery/my-first-gallery/index.md ---
![Image 1](image1.png) ![Image 2](image2.png)
![Image 3](image3.png)

```
它将呈现两行，第一行有两个图像，第二行有一个图像。



