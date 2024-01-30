# chinese-philosophy
中国哲学书电子化计划

一级目录格式
```json
{
    "name": "道德经",
    "author": "老子",
    "chapters": [
        {
            "name": "体道",
            "paragraphs": [
                {
                    "paragraph": "道可道，",
                    "zhushu": "谓经术政教之道也。"
                }
            ]
        }
    ]
}
```

二级目录格式
```json
{
    "name": "道德经",
    "author": "老子",
    "chapters": [
        {
            "name": "道经",
            "twoChapters": [
                {
                    "name": "体道",
                    "paragraphs": [
                        {
                            "paragraph": "道可道，",
                            "zhushu": "谓经术政教之道也。"
                        }
                    ]
                }
            ]
        }
    ]
}
```