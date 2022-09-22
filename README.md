# Pair Programming: Pipeline Execution on AWS

## Introduction

In this exercise, you'll work with a partner to replicate the workflow covered in the [Pipeline Creation](https://github.com/flatiron-school/DS-Deloitte-07062022-Architecting-Pipelines-with-AWS/blob/main/Pipeline%20Creation.ipynb) and [Pipeline Execution](https://github.com/flatiron-school/DS-Deloitte-07062022-Architecting-Pipelines-with-AWS/blob/main/Pipeline%20Execution.ipynb) lectures!

## Objectives

You will be able to:

- Generate a directed acyclic graph (DAG) in the form of a JSON pipeline definition
- Define a set of Pipeline parameters that can be used to parametrize a SageMaker Pipeline
- Execute steps that create a model from the model artifacts used in training
- Perform batch transformation based on the model that was created

## Quick Start

1. Create a `notebook instance` on SageMaker:

![](./images/create-notebook.png)

2. Start the created notebook instance:

![](./images/start-notebook.png)

**Note:** *Your notebook instance will refect a status of `Pending` for a couple minutes (as shown below):*

![](./images/pending.png)

3. Open JupyterLab interface:

![](./images/open-jupyter.png)

4. Upload [the provided notebook](https://github.com/flatiron-school/DS-Deloitte-07062022-PairProgramming-PipelineExecution/blob/solution/Pipeline%20Creation%20and%20Execution%20Workflow.ipynb):

**Note:** *You will not see any files in your directory yet, unlike in the image below.*

![](./images/upload.png)

5. Double-click on the uploaded notebook:

![](./images/open-notebook.png)

6. Run all cells:

![](./images/run-cells.png)

7. Scroll down, then uncomment and run each of the Pipeline Execution steps, which will take about 15 minutes.

![](./images/pipeline-execution-steps.png)

8. Monitor pipeline execution progress using the SageMaker Studio interface:

<table>
    <tr>
        <td>
            <img src="./images/studio.png"/> 
        </td>
        <td>
            <img src="./images/open-studio.png"/>
        </td>
    </tr>
</table>

**Note:** *Click the `SageMaker resources` icon in the navigation pane (as shown), then select `Pipelines` from the dropdown. Double-click on the execution shown in the resulting list of pipeline executions in order to open its corresponding DAG; refresh, if necessary:*

<table>
    <tr>
        <td>
            <img src="./images/studio-interface-1.png"/> 
        </td>
        <td>
            <img src="./images/studio-interface-2.png"/>
        </td>
    </tr>
</table>

9. Don't forget to stop the notebook instance (!):

<table>
    <tr>
        <td>
            <img src="./images/stop-notebook.png"/> 
        </td>
        <td>
            <img src="./images/stopping.png"/>
        </td>
    </tr>
</table>
