# DORC
Analyzing gallbladder removal videos using computer vision to search for surgical errors in real time. Relies on the Cholec80 dataset. Selected files only to protect intellectual property.

LTL LC Action Recognition.xlsx - Summary of surgical steps of the laparoscopic cholecystectomy. Hard-coded linear temporal logic rules that define the surgery process.

SVMToolBackground.ipynb - Created a support vector machine to segment tools in each frame from organ/fat background. Reduced segmentation/preprocessing runtime from 200 to 60 ms/frame.

SampleMultitracker.ipynb - Template code for a generic multitracker tool, used for tracking the movement of tools during the surgery.

ToolsToPhase.ipynb - Using linear temporal logic and Hidden Markov Model to identify surgical phase based on tool presence.
