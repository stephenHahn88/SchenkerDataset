# SchenkerDataset

This is the public repository for computer-readable Schenkerian Analysis based on our ISMIR paper, [A New Dataset, Notation Software, and Representation for Computational Schenkerian Analysis](https://ismir2024program.ismir.net/poster_367.html#paper). Here, we hope to build a large dataset to enable broad research on computational Schenkerian analysis and its downstream tasks.

## Access

For questions and access to the **full private dataset**, please contact the first author, Stephen Ni-Hahn, at stephen(dot)hahn(at)duke(dot)edu. The private dataset will only be released for academic purposes.

For the latest version of our notation software, please visit [schenker-notation.netlify.app](schenker-notation.netlify.app)

## Contribute!

For contributions to the dataset, please prepare three versions of your analysis:
1. An image of your graph, either handwritten or using the notation software
2. The musicxml file associated with your graph
3. The JSON format of your analysis, which can be easily generated using our notation software

The folders are organized as follows:
```
SchenkerDataset
└─ {JSON/musicxml/raw_graph} 
    ├─ (Analyst)
    |   ├─ (Composer)
    |   |   ├─ (Your file)
    .   .   .
    .   .   .
    .   .   .
```