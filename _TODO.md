- Prof. Review
    - rewrite considering the feedback on line: "Planners can use different optimizations to achieve their goals"

- Solution/Architecture
    - Static Workflow Planner
        - show the image example + explain it
    - Evaluation (Setup)
        - Insist on the choreographed scheduling, using a diagram maybe (the delegate and become stuff)
    - RE-CHECK
        - Explain listings and figures whenever necessary
        - find better names for the planners + refactor code


- possible extensions/improvements
    - improvements to prediction logic
    - make the metrics collection more scalable while not sacrificing predictions
    - supporting dynamic fan-outs
        so that its possible to, for example, dynamically partition an output and process it in parallel
    - Providing the DAG representation in worker invocations instead of having to download from storage
        - if below a certain threshold, because worker invocation data has size limits
    - ? supporting execution of generic executables as tasks, and not just python functions
        CLI program (input (stdin or cli args) => output (stdout))