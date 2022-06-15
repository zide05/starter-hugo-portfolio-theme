---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: About MTG
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
MTG is a human-annotated multilingual multiway dataset. Multiway means that the same sample is expressed in multiple languages. It covers **four generation tasks** (story generation, question generation, title generation and text summarization) across **five languages** (English, German, French, Spanish and Chinese). 

<!-- You can find the slides, poster and video about E-KAR at <a href="https://jiangjiechen.github.io/publication/ekar/">here</a>. -->
<style>
table
{
    margin: auto;
}
</style>


## MTG's subsets and sample sizes

<!-- ![MTG-statistics](/uploads/dataset_statistics.jpg) -->
<div  align="center"> 
<img src="/uploads/dataset_statistics.jpg" style="zoom:30%" align=center/>
</div>

<!-- 

| **Task**                                     | **SG, QG, TG, Summ** |
|-----------------------------------------------|---------------------:|
| **For each language**                         |                      |
| Rough training size                           |    76k/61k/270k/164k |
| Annotated training size                       |      15k/15k/15k/15k |
| Annotated development size                    |          2k/2k/2k/2k |
| Annotated test size                           |          3k/3k/3k/3k |
| **For five languages   (en, de, fr, es, zh)** |                      |
| Total Annotated size                          |                 400k |
| Total dataset size                            |                 6.9m |
 -->

<!-- <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTpfCYVe3yAZeuNTYdClxWY8r3siS5cw3qDQQkBHk2gD4kTEwf7dsTigBfimfGHkYEKd8Jk31t4tazK/pubhtml?widget=true&amp;headers=false"></iframe> -->

## MTG's tasks overviews
<!-- 
|        **Task**        |   **Corpus**  | **Domain** |         **Format**         |               **Goal**               |
|:----------------------:|:-------------:|:----------:|:--------------------------:|:------------------------------------:|
|    Story Generation    | ROCStories    | Daily life |           <story>          | Generate the end of the   story      |
|    Question Generation | SQUAD 1.0     | Wikipedia  | <passage,answer, question> | Generate the question of the answer  |
|    Title Generation    | ByteCup       | News       |      <article, title>      | Generate the title of the document   |
|    Text Summarization  | CNN/DailyMail | News       |     <article, summary>     | Generate the summary of the document |
 -->
![MTG-tasks](/uploads/tasks.jpg)

{{< table path="leaderboard.csv" header="true" caption="Table 1: My results" >}}

## Leaderboard
[leaderboard]({{< ref "/leaderboard/leaderboard.md" >}})


