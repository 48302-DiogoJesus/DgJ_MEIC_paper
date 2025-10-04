- Solution/Architecture

- For the Conclusion maybe possible solution extensions/improvements
    - improvements to prediction logic
    - make the metrics collection more scalable while not sacrificing predictions
    - supporting dynamic fan-outs
        so that its possible to, for example, dynamically partition an output and process it in parallel
    - Providing the DAG representation in worker invocations instead of having to download from storage
        - if below a certain threshold, because worker invocation data has size limits
    - ? supporting execution of generic executables as tasks, and not just python functions
        CLI program (input (stdin or cli args) => output (stdout))
