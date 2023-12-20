# Annotation Format

```
{<vid_name1>: [
    {
        'text_start': <val>,
        'text_end': <val>,
        'video_start': <val>,
        'video_end': <val>,
        'label': <val>
        },
     {
        'text_start': <val2>,
        'text_end': <val2>,
        'video_start': <val2>,
        'video_end': <val2>,
        'label': <val2>
        },
    ...
],
<vid_name2>: []
...
}
```

text_start: start of text event in character number beginning from start of article
text_end: end of text event in character number beginning from start of article
video_start: video event beginning timestamp
video_end: video event ending timestamp
label: one of Hierarchical, Identical or NoRel