

**Name - Nikhil Sharma**

**Roll_number - 2410110219**







**MODULE 1**

**Video - 1**

What I learned -

1) Tracing implementation, application and usage.
2) Run tree tracing, checking latency and checking metadata.
3) Metadata addition during and before runtime

Changes I made -

1) Changed the prompts for questions asked to rag to better understand the trace difference and token difference before and after
2) Added a code at the end to test rag and metadata addition at runtime.

Link to the Source File - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_1/tracing_basics.ipynb



**Video - 2**

What I learned - 

1) Types of runs supported by langsmith in @Traceable decorator
2) Different traces for different types of runs and their comparisons and rendering
3) Formatting affects on the Tracing outputs.

Changes I made -

1)Added a code at the end that includes every type of runs to trace all the run trees.

2)Altered the prompt questions to see if any difference would occur in the tracing.

Link to the Source File - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_1/types_of_runs.ipynb



**Video - 3**

What I learned - 

1) Checking Traces created by langgraph and the nodes created
   
2) Using python tracing content manager trace() for more granular control
   
3) Formatting affects on the Tracing outputs.

Changes I made -

1)Changed run types to check if traces would be different while tracing inside a function.

2)Altered a few prompt questions to see if any difference would occur in the tracing.

3)Added my own example with both python's tracing content manager and Langchain's @Traceable decorator


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_1/alternative_tracing_methods.ipynb


**Video - 4**

What I learned - 

1) Meaning of Threads, their occurrence and how they appear on the Run Trees and their linkage.
2) Metadata session_id, thread_id, conversation_id and the uuid value.
3) Formatting affects on the Tracing outputs.

Changes I made -

1)Altered prompts to see if they affect threads and tracing.

2)Added own example at the end which includes multiple threads being created.


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_1/conversational_threads.ipynb

***MODULE 1 FINISH***





**MODULE 2**

**Video - 1**

What I learned - 

1) Creation of Datasets in Langsmith
2) Adding data to the Dataset in Langsmith
3) Debugging Dataset not found error due to key mismatch

Changes I made -

1)Added own example at the end to check another addition of a trace to the database and its metadata


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_2/dataset_upload.ipynb


**Video - 2**

What I learned - 

1) Definition of an Evaluator the reference it takes and the output it gives.
2) Encoding grading prompts for LLMs as Judge
3) Types of Evaluators such as correctness, hallucination, conciseness, code checker 

Changes I made -

1)Added an example at the end trying to get a low, moderate and high output in semantic similarity.
2)Slightly altered prompts to get different semantic scores from the given code.


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_2/evaluators.ipynb


**Video - 3**

What I learned - 

1) Definition of an Experiment and how to operate it in langsmith.
2) Usecases of Experiments such as changing the model to see how the result changes
3) Running Experiments on specific a specific subset of examples

Changes I made -

1)Altered models to see different responses to the experiment.

2)Added Splits to the dataset.

3)Added an experiment of comparing different trace methods for temperature values


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_2/experiments.ipynb


**Video - 4**

What I learned - 

1) Analyzing and filtering different outcomes of the experiments by different input models and prompts in forms of charts.
2) Displaying full input outputs for the iteration with all metrics including latency ,token, stats and eval scores.
3) Comparing Experiments evaluations next to each other.


**Video - 5** 

What I learned - 

1) Meaning and Implementation of Pairwase Experiment
2) Encoding preference scores at the place of individual scores.

Changes I made -

1) Added example of altering temperatures to see output difference and then evaluating them pairwise.
2) Slightly altered prompts to have a higher difference in score of the given dataset comparison.


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_2/pairwise_experiments.ipynb


**Video - 6**

What I learned - 

1) Setting up summary evaluators and its implementations.
2) Metrics for summary evaluators can be only meaningfully evaluated over entire experiments instead of a specific runs.


Source Link - https://github.com/langchain-ai/intro-to-langsmith/blob/main/notebooks/module_2/summary_evaluators.ipynb


***MODULE 2 FINISH***



