# Scientific Project


This project is based in the detectron2 repository (https://github.com/facebookresearch/detectron2). It consists of a general pipeline with the following steps:
![Pipeline](/docs/pipeline.png)


## Generated report
A report will be generated at the end of the pipeline execution. It will include the following aspects:
- Dataset description
- Optional extra information
- Model training plots
- Test plots using the provided dataset
- Images & their predictions

Some report examples are available in the [reports folder](/reports).


## Usage instructions
### Previous considerations
#### Dataset structure
The actual code requires a specific structure for the folder containing the evaluating dataset:

![Dataset structure](/docs/datasetStructure.jpg)
