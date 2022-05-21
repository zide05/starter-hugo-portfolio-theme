---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Evaluation
subtitle:

design:
  columns: "1"
  background:
    image: 
    image_darken: 1.0
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: 
  spacing:
    padding: ["20px", "0", "20px", "0"]
---

To evaluate your results on metrics mentioned in our paper, please send the system ouputs to <a href="mailto:
chenyiran.robin@bytedance.com">this email</a>. We will send the evaluation results back to you as soon as possible.


The system ouputs files should be named as \[TG/QG/SG/Summ\]-xxx.json (e.g., TG-crosslingual_res.json). The json file should contain language (en,de,es,fr,zh) as key and the outputs list as value:
```json
{
    "en":["system output 1","system output 2"], 
    "es":[], // results can be empty, it will not be evaluated 
}
```
