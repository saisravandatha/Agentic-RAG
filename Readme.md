Enterprise docs contains not only text also Images, Text, Tables and Graphs. To support that we have multimodal RAG also known as Visual RAG.

Text data -> Page + Modality Metadata
Table data -> Markdown as it preserves the structure
Images/Graph -> Vision  Summary (describe graph / diagram) and we save the image in a place and save its path as metadata

And send them all to text embedding model.