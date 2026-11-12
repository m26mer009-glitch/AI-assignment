AI Reasoning Assignment — Submission

Files
-----
reasoning_agent.ipynb
    Notebook containing the current implementation, experiments, and dataset work.

report.pdf
    Summary of the representation, reasoning methods, experiments, and current limitations.

submission.csv
    CSV template with the required columns: id,predicted_label.
    
How to run
----------
1. Open reasoning_agent.ipynb in Google Colab.
2. Run the notebook cells in order, starting with dependency installation and dataset
   loading where needed.
3. Check all printed parsing/evaluation errors and record the actual final metrics.
4. Run the official unseen test examples using the assignment's required input format.
5. Export one row per test example to submission.csv with columns:
       id,predicted_label
6. Ensure predicted_label uses the exact label names required by the assignment.

Current status
--------------
This is a draft submission package, not a verified final system.
- RuleTaker: preliminary development-set result recorded in the working notes:
  89.7% accuracy on 1,000 examples; earlier measured runtime 0.439 seconds.
- CounterBench Alpha V1: preliminary baseline 40.0% (1,000 examples; 0.144 seconds).
- CounterBench Backdoor V2: preliminary baseline 52.5% (200 examples; 0.094 seconds).
- FOLIO: parser and prover experiments exist

