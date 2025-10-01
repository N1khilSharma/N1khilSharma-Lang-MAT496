

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

